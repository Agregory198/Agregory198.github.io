---
title: "Database System Management"
layout: single
classes: wide
excerpt: "Relational database for data processing, validation, and analysis"
header:
  teaser: /assets/images/archaeobase_app.png
---

## Overview

This project provides an application for on-site data collection and processing. This application allows the user to merge and format data from several different sources into a local SQLite database with the future ability to upload the data to a stable MySQL server. The application is built on the streamlit frontend but is packaged as an executable file for the local deployment in the field.

## Novelty
This represents one of the few attempts to build a standard and open-source tool for the collection, curation, processing, and analysis of archaeological data. I began this project to address the overwhelming need for an archaeological-specific application that can be shared freely with international research teams. With current budgetary uncertainty and restrictions to other proprietary online application, the need for an open-source platform has never been this great.

## Methods
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
