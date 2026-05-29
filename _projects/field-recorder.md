---
title: "Field Recording Application"
layout: single
classes: wide
excerpt: "Data collection, storage, and curation"
header:
  teaser: /assets/images/recorder_app.png
---

## Overview

This project provides an all-in-one data recording application for field archaeologists. The application is split into several different forms including photo, context, and artifact entry recording. Each form can be exported as a CSV and be directly imported into its sister applications 'ArchaeoBase'.

Archaeologists have continued to depend on large, corporate, proprietary software to manage their databases and data collection strategies. This has led to an ineven playing field in which every university needs to adopt different strategies according to which software licenses they have. This application and its sister 'ArchaeoBase' application are built on the same SQL database and tables to allow for standard data colleciton via open-source code. This is the first serious attempt to move archaeologists out of the shadow of corporations and better define their own data collection and curation strategies.

## Methods

This application is built with a streamlit front end, but is individually distributed via an executable file. Since archaeologists work and record data in regions with unstable internet access, it is important to provide a means of local processing and storage. As such, the local database is built in SQLite and mirrors the database and tables used in the ArchaeoBase application. Once the user exports the file from this application, they can immediately import it into the ArchaeoBase app to validate, visualize, and permenantly append the data to a stable database.

