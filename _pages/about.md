---
permalink: /
title: "Christopher Krasniak, PhD"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a data scientist with a background in neuroscience excited about exploring data to answer interesting questions and solve business problems. I'm especially interested in biotech and tech, but I can get excited about almost any challenging field.

Experience
======
- The Data Incubator — Data Science Fellow
    - Learned broad set of Data Science tools
    - Completed capstone project predicting rental income from data scraped from AirBnB by combining NLP and XGBoost regression
    - Project selected for the prestigious Capstone Showcase presentation
- Cold Spring Harbor Laboratory – Graduate researcher
    - Led individual project aimed at understanding the basic neuroscience of decision-making
    - Designed and conducted experiments, and created automated pipeline for data preprocessing and transfer
    - Created analysis scripts including feature engineering, Machine Learning, and statistical testing, to create figures for a manuscript
- [International Brain Laboratory](https://www.internationalbrainlab.com/) – Researcher
    - Collaborated with a 20+ member team to create the first standardized behavioral task in systems neuroscience
    - Co-authored a [paper in eLife](https://elifesciences.org/articles/63711) including the 200+ pages of detailed technical procedures
    - Contributed to the [largest single-cell electrophysiology dataset to date](https://www.biorxiv.org/content/10.1101/2022.05.09.491042v2)
- Colby College Research Methods and Statistics in Psychology TA
    - Assisted students with coursework, experimental design, and hypothesis testing


Recent Projects
======
 
Ongoing work -> Web app for optimized income from short-term rentals
----
- scraped ~500k AirBnB listings from 30 cities 
- created preprocessing pipeline to seamlessly filter and clean data
- trained XGBoost model to predict occupancy rates for each listing using all availbale data, including NLP of text fields and feature engineering of location, price, etc.
- created webapp to take user input and predict monthly earnings for the details of a user's listing
- allows users to try different listing details (description, name, # guests, etc.) to optimize income
- [Code here](https://github.com/cskrasniak/rentals)


Cortex-wide neural imaging in behaving mice
----
- Found that neural information predictive of behavior is both distributed throughout the brain, but specifically localized at different times
- Collected 100Tb of imaging data
- Implemented automated preprocessing and data transfer (batch script executing python and MATLAB scripts)
- Created multi-stage analytic pipeline (PCA, custom curve fitting, feature engineering, cross-validated logistic regression, Bernoulli testing, permutation testing) to create publication-ready figures (matplotlib, seaborn)
- Presented at International Brain Lab Annual Meeting with manuscript in preparation
- [Code here](https://github.com/cskrasniak/wfield/tree/master/notebooks)

![Logistic regression weights across the mouse cortex for decoding stimulus side](../images/model_comparison_weights_frame_3.png)

Inhibition scan of cortex
----
- Found different roles of visual cortex and secondary motor cortex in the standard drift-diffusion model
- Integrated 2d laser scanning (MATLAB) with existing custom behavioral task code (Python) [code here](https://github.com/cskrasniak/lesion_project/tree/master/GalvoScanning)
- Fit behavior to a psychometric function using maximum likelihood optimization [code here](https://github.com/cskrasniak/lesion_project/blob/master/thesis_scan_analysis)
- Created a drift-diffusion model simulation to compare behavioral results to the model


