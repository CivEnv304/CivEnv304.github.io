---
layout: page
permalink: /Methodologies/
title: Methodologies
page_title: Environmental & Social Lifecycle Assessment (LCA) and Design
page_description:
nav: true
nav_order: 1
---

### Lifecycle of goods and services

#### [Process/Flow Analysis/Mapping](#Process)

- Notebook example

#### [I-O framework to represent production](#I-O framework)

1. Product structure trees & Bills of Materials

2. Calculating total production requirements to satisfy demand

3. Allowing for design alternatives

4. Estimating impact/repercussions/emissions

5. Conducting Analysis
- Process models
- Economic models


### Lifecycle of Products/services

* Cradle-to-Gate

* Cradle-to-Consumer

* Cradle-to-Cradle

<div style="text-align: center;">
<img class="photo" src="{{ site.baseurl }}/assets/img/materials/LCA.png">
</div>

## <a id="Process"></a>Process

### Process/Flow Analysis/Mapping

* Moving from conceptual diagram to the lifecycle of an actual product/service

* Example:  Paper or a notebook (cradle-to-consumer analysis)

* Motivation to develop a framework to represent/model production

## <a id="I-O framework"></a>I-O framework

### I-O Models in Production Economics Representation

<div style="text-align: center;">
<img class="photo" src="{{ site.baseurl }}/assets/img/materials/Product Structure.png">
</div>

Assume demand for 5 "Items".

$$y = [5, 0, 0, 0]'$$

Level 0 Requirements:

$$ [\mathbf{B}_1]^0 y = \mathbf{I}y = [5, 0, 0, 0]' $$

Level 1 Requirements:

$$ [\mathbf{B}_1]^1 y = [\mathbf{B}_1]y = [0, 15, 10, 0]' $$

Level 2 Requirements:

$$ [\mathbf{B}_1]^2 y = [0, 0, 0, 35]' $$

Level k = 3, 4, ... Requirements:

$$ [\mathbf{B}_1]^k y $$

**Total Gross Requirements:**

$$ x = \sum_{k=0}^{\infty}\mathbf{B}_1^k y = [\mathbf{I} - \mathbf{B}_1 ]^{-1}y = [5, 15, 10, 35]' $$

**Alternative Representation**

$$x = \mathbf{B}_1 x + y$$

or,

$$[\mathbf{I} - \mathbf{B}_1 ] x = y $$

### I-O Models in Social & Environmental LCA

Approach to calculate impact/discharges/emissions/consumption

1. Calculate total gross economic activity, $$x$$.

2. Repercussions along K dimensions given by $$F x$$.

where $$F_{kj}$$ is the discharge/emissions/consumption rate of effluent/pollutant/resource k per unit







<!--
The workshop is organized in two main tracks:

1. <u>Nuclear & other Physics-based Imaging technologies</u>
  - Nuclear (& other Physics-based extended)  Computer Vision for Cultural Heritage
  - Particle Accelerators applications: imaging, software and statistical analysis
  - Stastical learning for Astronomy
  - X-ray, Neutron and Proton image analysis and processing for Medical Physics
  - AI-enhanced experimental apparatus
  - Neutron and X-Ray-based Tomographic analysis for applied physics
  - Multimodal analysis methods

2. <u>Generative Models & other disruptive Deep Learning methods for Physical Sciences</u>
  - Density estimation
  - Anomaly detection
  - Physics-informed systems
  - Fast detector simulation
  - Synthetic data augmentation
  - Other SOTA methods for Physics Data Analysis and processing


### Submission and review

We invite submission of papers describing work in the domains suggested above or in closely-related areas.

The workshop's reviewing of submissions will be **double-blind**. Accepted submissions will be presented either as oral resentation or posters at the workshop, and will be published by Springer as Lecture Notes in Computer Science series (LNCS), in the ICIAP 2023 Workshops volume.

The maximum number of pages is 10 + 2 pages for references. While preparing their contributions, authors must follow the guidelines and technical instructions provided by Springer (see [Springer guideline](https://www.springer.com/gp/computer-science/lncs/conference-proceedings-guidelines) and [Springer Overleaf LaTex template](https://www.overleaf.com/latex/templates/pringer-lecture-notes-in-computer-science/kzwwpvhwnvfj#.WuA4JS5uZpi)).

Each accepted paper must be covered by at least **one registered author**. Registration can be either for the full event (5 days) at a regular rate or just for workshops and tutorials (2 days).

### Submission website

The submission website is: [cmt3/BVPAI2023](https://cmt3.research.microsoft.com/BVPAI2023)


### Fees

For more info, see the official ICIAP2023 page at: [https://iciap2023.org/registration](https://iciap2023.org/registration)

<!--
<iframe width="100%" height="500px" src="https://iciap2023.org/registration/"></iframe>


<hr class="wp-block-separator has-alpha-channel-opacity"/>

#### Workshops/Tutorials pass*

<figure class="wp-block-table is-style-stripes">
  <table class="has-fixed-layout">
    <tbody>
      <tr>
        <td><strong>Profile</strong></td>
        <td><strong>Early bird (up to July 25th)</strong></td>
        <td><strong>Late fee</strong></td>
        <td><strong>Onsite</strong></td>
      </tr>
      <tr>
        <td>Regular</td>
        <td>350€</td>
        <td>400€</td>
        <td>450€</td>
      </tr>
      <tr>
        <td>IAPR member</td>
        <td>300€</td>
        <td>350€</td>
        <td>400€</td>
      </tr>
      <tr>
        <td>Student</td>
        <td>250€</td>
        <td>300€</td>
        <td>350€</td>
      </tr>
    </tbody>
  </table>
</figure>

<p>*covers tutorials and workshops only</p>
<p>Rates are in Euro, per person, including taxes (VAT 22%)</p>

<hr class="wp-block-separator has-alpha-channel-opacity"/>


#### Conference pass**

<figure class="wp-block-table is-style-stripes">
  <table class="has-fixed-layout">
    <tbody>
      <tr>
        <td><strong>Profile</strong></td>
        <td><strong>Early bird (up to July 25th)</strong></td>
        <td><strong>Late fee</strong></td>
        <td><strong>Onsite</strong></td>
      </tr>
      <tr>
        <td>Regular</td>
        <td>700€</td>
        <td>750€</td>
        <td>800€</td>
      </tr>
      <tr>
        <td>IAPR member</td>
        <td>600€</td>
        <td>650€</td>
        <td>700€</td>
      </tr>
      <tr>
        <td>Student</td>
        <td>400€</td>
        <td>450€</td>
        <td>500€</td>
      </tr>
      <tr>
        <td>IAPR student member</td>
        <td>350€</td>
        <td>400€</td>
        <td>450€</td>
      </tr>
    </tbody>
  </table>
</figure>

<p>**includes main conference, workshop/tutorials and social events</p>
<p>Rates are in Euro, per person, including taxes (VAT 22%)</p>

<hr class="wp-block-separator has-alpha-channel-opacity"/>

<p><strong>Additional paper:</strong> 150€</p>
<p><strong>Additional gala dinner ticket:</strong> 150€</p>
<p>Rates are in Euro, per person, including taxes (VAT 22%)</p>
-->
