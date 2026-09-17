---
title: "Effects of coastal resource intensificaiton in southern Africa 4,000 years ago"
layout: single
classes: wide
excerpt: "Hierarchical modeling of technological change through the later Holocene in southern Africa in response to coastal intensification"
header:
  teaser: /assets/images/archaeobase_app.png
---

## Overview
This project aims to evaluate the effect that increasing coastal resource use had on hunter-gatherer technological and social strategies at Steenbokfontein Cave in South Africa 4,000 years ago. For most of human history, people have aggregated around lakes, rivers, and coasts. Aquatic environments provide humans access to dense, predictable, and defensible resources such as fish and shellfish. Aquatic resource abundance has determined the permanence of these settlements. Seasonal aggregation would have allowed hunter-gatherers from far and wide to temporarily share knowledge, resources, technology, and build social relationships. Permanent aggregation around dense and reliable aquatic resources would have provided an opportunity to develop specialized technologies and practice coordinated resource sharing and distribution, which are key features that define “complex hunter-gatherers.” Therefore, aquatic resources plausibly served as a lynchpin in the development of key evolutionary traits in hunter-gatherers, most notably reduced mobility, surplus accumulation and sharing, and technological innovation; yet surprisingly few studies have directly evaluated how aquatic resources structured hunter-gatherer mobility patterns and technological strategies.

## Novelty
This is a multivariate project that examines whether hunter-gatherer technological strategies changed when they increased shellfish consumption at Steenbokfontein Cave. I use Bayesian models to evaluate the relationship of several stone tool variables including utility, length, mass, and raw material. I use gt_summary and ggplot2 to develop publish-quality tables and figures.

I first describe the composition of hunter-gatherer toolkits, including the raw stone material, types, and frequencies of their stone technology. I describe these data in tabular and graphical representations. I then construct a Bayesian model with catgeorical and dirichlet families to evaluate whether there are significant trends in raw material and toolkit composition as hunter-gatheres focused on coastal resources.

I then evaluate three specific artifact classes most commonly found in archaeological contexts to evaluate whether there are technological shifts sensitive to increased coastal resource exploitation. Namely, I examine stone flakes, cores, and scrapers. I use attributes I recorded from the tools to evaluate shifts in tool utility, reduction, and retouch intensity. To do this, I modeled several Bayesian GLMs composed of simple, hierarchical, and second order polynomials. I then evaluate which model fit the data best using a leave-one-out analysis. I then visualize and compute the rate of change between tool utility, reduction, and retouch intensity for the three stone tool classes.
## Hypothesis
I expect shifts in toolkits as hunter-gatherers increased coastal resource use. If my models show significant shifts in toolkit composition and rates of change between tool utility, reduction, and retouch intensity, then there is evidence to support this hypothesis.
  
![AppTech Workflow](/assets/images/ArchaeoBase_AppTech.drawio.png)

This project uses streamlit as the front end with a FastAPI backend, allowing easy and efficeint deployability. The data is then imported via text or comma-separated-values files. These data are stored in a temporary 'daily' table via SQLite. The application provides several different pages that allow the user to modify, validate, or visualize the input data. Once the data are vetted, they are uploaded to a permenant datatable that can be further exported, analyzed, or processed within or outside the aplication.

![Lithics Workflow](/assets/images/archaeoBase_workflow.drawio.png)
This diagram compares the old and new workflow with my application. The old workflow was multilayered with different file types that came from three different sources and needed to be uploaded, validated, and  modified independent of one anoter. Furthermore, the old workflow exclusively used proprietary systems such as Microsoft Access database and excel, and Esri's Geographic Information System. The new workflow provides a single data entry platform with built-in validation, visualization, and analysis functions. This new application uses open-source tools to streamlines and standardizes data collection, curation, and analysis.

## Features

- Automated preprocessing
- Feature engineering
- Data validation, curation, and storage
- Data visualization and analysis
- Interactive interface
