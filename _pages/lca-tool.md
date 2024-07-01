---
layout: page
permalink: /lca-tool/
title: LCA Computational Resources
page_title: LCA Computational Resources
description:
nav: true
nav_order: 4
---


We provide a detailed video walkthrough of applying EIO-LCA to evaluate the environmental and economic impacts of manufacturing a T-shirt. Starting with a conceptual overview of LCA, we dives into a numerical example, detailing a 'cradle to consumer' analysis. This involves populating demand vectors to represent costs in terms of manufacturing, transportation, and retail sectors, all quantified in dollar amounts.

The video further explores calculating the transportation and retailing costs associated with t-shirt orders. We demonstrate how to input values using Matlab scripts and Excel for analysis, and therefore, examine various impacts such as job creation, economic activity, and environmental effects like greenhouse gas emissions and eutrophication potential.

By this video, we wish to guide the users on how to use provided tools and resources, available in an online repository, to replicate the analysis or apply it to different sectors.This comprehensive approach not only educates on the technical process of conducting an I-O LCA but also emphasizes its practical implications in real-world scenarios.


<iframe width="896" height="504" src="https://www.youtube.com/embed/4fbfhU_6FU8?si=V3cukiZwjLLw4sWS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


## EIO-LCA Tool

This is the Matlab version of the 2017 industry-by-industry model of the US economy. It is intended for users with an advanced understanding of economic input-output life cycle assessment. The file loads data from [USEEIOv2.01-411](https://catalog.data.gov/dataset/useeio-v2-0-1-411), and this is where we expect updates. The script will calculate economic, social, and environmental impact/outputs. You need to have Matlab and Microsoft Office installed on your computer to use this tool fully.

The tool is available at [EIO-LCA Tool](https://github.com/JingYu-NU/EIO-LCA-tool).

## Files included in this archive

* **data.mat**:
Matlab storage file that stores all matrices used in the model, including the current Economic matrices and environmental matrix.

  A: The 2012 industry-by-industry direct requirements matrix from [USEEIOv2.01-411](https://catalog.data.gov/dataset/useeio-v2-0-1-411).

  R: The direct + indirect impact coefficients

* **EIOLCA_Template.xlsx**:
The file includes the input data for the Matlab model, and the output file shows the model results. The spreadsheets are:

  1. Inputs: the input used in the model. It is defined by users and measured by dollars of activity in the corresponding economic sector.

  2. Summary Outputs: The outputs are summarized by the list of economic, social, and environmental impacts that are considered within this Matlab model.

  3. Economic Activity: The output of economic activities for each sector, including total and direct output.

  4. GHG Emissions: The total and direct output of CO2 emissions of each economic sector.

  5. Sector Outputs: The output of all metrics for all economic sectors.

* **EIOLCA_Template - Copy.xlsx**:
  A copy of the EIOLCA_Template file.

* **eiolca.m**:
  Matlab model code.

## Model Use:

  To use this Matlab model, users need to define the values of their target's economic activities (in 2012 dollars) in column D (y$) of the spreadsheet "Inputs" in EIOLCA_Template.xlsx. For example, to model $1000 of 'Drinking water and wastewater treatment,' 1000 should be inserted into cell D25. Note that multiple economic activities could be defined to represent the LCA goal in column D.

  The remaining activity takes place in Matlab. First, make sure that the current working directory in Matlab is the directory in which EIOLCA_Template.xlsx resides. The changes to the EIOLCA_Template.xlsx need to be saved before proceeding to run the Matlab code. Run the Matlab code, and there will be output files in Matlab called 'aggregateOutputs,' 'x,' 'direct,' 'GHG,' and 'sectorOutputs.' Users may copy and paste them into the corresponding spreadsheet to analyze these output data with headings, names, and codes of corresponding sectors.
