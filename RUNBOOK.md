# Runbook: Adding New Student Project Pages

This guide explains how to publish a new cohort of student Life Cycle Assessment (LCA) projects on the CivEnv 304 site. The 2024–25 class created eight videos; follow these steps once per cohort (and repeat steps 3–4 for each video).

## 1. Gather Project Assets
- **Video:** Confirm the YouTube URL and note the 11-character video ID (the part after `watch?v=`). If YouTube is unavailable, export an `.mp4`.
- **Metadata:** Record the display title, short description (1 sentence), author list, and the academic year.
- **Thumbnail:** Request or create a hero image (`.png` or `.jpg`). Save files in `assets/img/materials/` and keep names short (e.g., `2024-water-refill.png`). Avoid spaces to reduce quoting headaches.

## 2. Create One Markdown Page per Project
1. Decide on a slug using lowercase words separated by hyphens (e.g., `projects-reused-bottle`).
2. Copy an existing page such as `_pages/projects-water-bottle.md` into `_pages/projects-<slug>.md`.
3. Update the [YAML front matter](https://jekyllrb.com/docs/front-matter/):
   ```yaml
   ---
   layout: page
   permalink: /projects-reused-bottle/
   title: Life Cycle Assessment of Reused Water Bottles
   page_title: Life Cycle Assessment of Reused Water Bottles
   nav: false
   nav_order: 1
   ---
   ```
4. Replace the iframe with the new video ID:
   ```html
   <iframe
     width="896"
     height="504"
     src="https://www.youtube.com/embed/VIDEO_ID?si="
     title="YouTube video player"
     frameborder="0"
     allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
     referrerpolicy="strict-origin-when-cross-origin"
     allowfullscreen>
   </iframe>
   ```
   - Drop the `?si=` parameter unless YouTube provides one; leaving it empty is harmless.
   - If hosting locally, uncomment and update the `<video>` block (see existing comment for syntax) and place the file in `assets/video/`.

## 3. Update the Student Project Index
The index lives in `_pages/student-projects.md`.

1. Add a year heading to keep the page scannable:
   ```markdown
   ## 2025 Projects
   ```
2. For each project, duplicate an existing `<div>` block and update:
   - `img src`: point to the new thumbnail (`{{ site.baseurl }}/assets/img/materials/2024-water-refill.png`).
   - `<a href>`: link to the new page (`{{ site.baseurl }}/projects-reused-bottle`).
   - `<h4>`: video title.
   - `<p>`: author list (optionally include section or quarter).
3. Keep consistent ordering (alphabetical by title) or group by theme; just document the convention in a short HTML comment so future edits stay aligned.

## 4. Verify Locally
1. Install dependencies if needed: `bundle install`.
2. Build and serve: `bundle exec jekyll serve`.
3. Visit `http://127.0.0.1:4000/student%20projects` and each new project permalink.
4. Check:
   - Thumbnails load and have descriptive `alt` text.
   - Video plays.
   - Metadata renders correctly on mobile breakpoints (shrink the browser).

## 5. Commit and Publish
1. `git status` to confirm only intended files changed.
2. `git add` each new page, updated index, and assets.
3. `git commit -m "Add 2025 student project pages"`
4. Push and open a pull request. Summarize the eight new projects and attach the YouTube playlist if available.

## Yearly Checklist at a Glance
- [ ] Eight project markdown pages updated with correct front matter and iframe.
- [ ] Thumbnails saved under `assets/img/materials/` with sane names.
- [ ] `_pages/student-projects.md` includes a new section for the current year with all eight entries.
- [ ] `bundle exec jekyll serve` passes and pages render as expected.
- [ ] Pull request reviewed and merged.

