---
title: "ML Lithics Classification"
layout: single
excerpt: "Machine learning workflow for lithic classification and predictive analysis."
header:
  teaser: /assets/images/ml_project.png
---

## Overview

This project provides an application for archaeologists to input their data and recieve predictions on whether the stone flakes were produced via freehand or bipolar methods.

## Rationale
Bipolar and freehand reduction strategies provide tradeoffs in stone tool production and intensification. For instance, bipolar reduction has been linked to stone tools that are more elongated anf thinner, reflecting a highly versatile and light-weight tool for highly mobile hunter-gatherer gourps. In contrast, freehand reduction leaves wider and thicker flakes, leaving a heavier and less transportable toolkit. Bipolar reduction can also reduce the target stone down to millimeters, providing an abundent source of stone flakes. Meanwhile, freehand reduction leaves the target stone larger and produces fewer stone flakes. Therefore, archaeologists need to be able to determine which flakes were produced via bipolar or freehand reduction because it is important to interpret prehistoric behavior.

## Methods
This application was built with several machine learning models trained on subsets of experimental data. In particular, I modeled the experimental data with logistic regression, random forests, and gradient boosting algorithms. I ran several subsets of the data features to provide users with a flexible application that has a higher probability of providing predictions for researchers who may not have recorded all of the required features. The trade off for the reduced subsets is training accuracy.

To operate the application, the user simply uploads their data as a CSV file. If the system detects features with the required naming scheme, these will be read in and the closest matching model will produce predictions based on the input data. If some or all of the columns do not match the feature names, the user has the option to manually select which column is associated with the column names required to run the models. This provides the user the oppurtunity to chnage feature names within the application instead of having to make these modification in external software like Excel or R.

The current models were only trained on quartz and crypto-crystalline silicates (CCS). The system will try to detect the raw material column automatically, but provides a drop-down option if it cannot detect this column. The user can then choose which model (quartz or CCS) that they wish to use to make the predictions. On avergae, the CCS models had 3-7% lower accuracy than the quartz-trained models.

## Features

- Automated preprocessing
- Feature engineering
- Classification pipeline
- Interactive interface

## Results

I achieved the best accuracy with numeric and nominal variables at a 95% accuracy rate. However, most users will not have recorded all of these features. So, the next smallest model using numeric features, only, produced an accuracy of 89%.
