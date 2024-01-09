# Robust and Interpretable Early Triaging Support (RIETS) for predicting Severity among hospitalized COVID-19 Patients

Sang Won Baek | Samsung Medical Center 

# Preprint available at the following website
https://preprints.jmir.org/preprint/52134/accepted

# Web-based application available at the following URL
https://riets-web.azurewebsites.net/

## Model Pipeline Overview

RIETS is a machine learning-based system developed for early triaging of hospitalized COVID-19 patients, predicting the progression to severe conditions within 15 days of hospitalization based on clinical and laboratory biomarkers.

![RIETS Model Pipeline](Images/Figure2.png?raw=true)

## Abstract

- [Background](#Background)
- [Objective](#Objective)
- [Methods](#Methods)
- [Results](#Results)
- [Conclusions](#Conclusions)
- [Keywords](#Keywords)
- [Contact](#Contact)

## Background

Many existing models for predicting COVID-19 severity risked high bias or showed low to moderate discrimination, often lacking clinical interpretability and relying on early pandemic period data. RIETS addresses these shortcomings.

## Objective

The primary goal of this study was to develop and validate RIETS, a machine learning-based system predicting the progression to severe COVID-19 conditions, based on routinely available clinical and laboratory biomarkers.

## Methods

The study used data from 5,945 hospitalized COVID-19 patients across 19 hospitals in South Korea, with model development and external validation conducted through cross-validation and bootstrapped sampling techniques.

## Results

RIETS, developed on a deep neural network, demonstrated excellent discrimination (AUROC, 0.937) and high calibration, satisfying all criteria of low bias risk. It proved effective in predicting severity in Omicron cases as well.

## Conclusions

RIETS provides a reliable prediction tool for early triaging of COVID-19 patients. Its high performance and generalizability, coupled with the use of routinely collected features, make it a promising tool for clinical practice.

## Keywords

COVID-19, prognosis, prediction model, early triaging, interpretability, machine learning.

## Citing RIETS model

If you use RIETS in your research, please use the following BibTeX entry.

```
@article{sangwonbaek,
  title={Development and validation of Robust and Interpretable Early Triaging Support system for patients hospitalized with COVID-19: Predictive algorithm modeling and interpretation study },
  author={Sangwon Baek, B.S., Yeon Joo Jeong, M.D., Yun-Hyeon Kim, M.D., Jin Young Kim, M.D., Jin Hwan Kim, M.D., Eun Young Kim, M.D., Jae-Kwang Lim, M.D., Jungok Kim, M.D., Zero Kim, Ph.D., Kyunga Kim†, Ph.D., Myung Jin Chung†, M.D., Ph.D.},
  journal={under review at JMIR},
  year={2023}
}
```
