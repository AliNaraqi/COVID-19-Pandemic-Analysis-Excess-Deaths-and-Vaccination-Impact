# COVID-19 Pandemic Analysis: Excess Deaths and Vaccination Impact

## 📋 Project Overview

This project analyzes the relationship between COVID-19 cases, excess deaths, and vaccination campaigns across 34 countries from 2020-2023. By merging emergency department (ED) excess mortality data with comprehensive COVID-19 metrics, we explore how vaccination campaigns and pandemic waves affected mortality rates globally.

## 🎯 Objectives

- Examine the correlation** between COVID-19 metrics and excess deaths
- Evaluate vaccination impact on reducing excess mortality
- Identify pandemic waves** and temporal patterns in excess deaths
- Compare pre-vaccine vs post-vaccine periods** to assess vaccine effectiveness
- Visualize trends** across different countries and time periods

## 📊 Datasets

The initial dataset is provided in `archive.zip` which contains:
- `covid.csv` - COVID-19 data with 373,495 records
- `ED.csv` - Excess deaths data with 135,628 records

### 1. COVID-19 Data (`covid.csv`)
- Source: https://www.kaggle.com/datasets/patricklford/covid-19
- Size: ~373,495 records
- Features**: 
  - Daily cases and deaths
  - Testing metrics
  - Hospitalization data
  - Vaccination rates
  - Demographics and economic indicators
  - Stringency index (lockdown measures)
- Coverage: 255+ countries

### 2. Excess Deaths Data (`ED.csv`)
- Source: https://www.kaggle.com/datasets/patricklford/covid-19
- Size: ~135,628 records
- Features**:
  - Weekly excess deaths by country
  - Demographic breakdowns (age, gender)
  - Multiple death causes
- Coverage**: 34 OECD member countries

## 🔧 Project Structure

```
Covid_19/
│
├── covid.csv                          # COVID-19 dataset
├── ED.csv                             # Excess deaths dataset
├── covid.ipynb                        # Main analysis notebook
├── README.md                          
├── archive.zip                         # Initial dataset containing covid.csv and ED.csv
├── Outputs (Generated):
│   ├── merged_covid_excess_deaths.csv # Complete merged dataset
│   ├── summary_statistics.csv         # Country-level summary metrics (in summary.zip)
│   ├── vaccination_analysis.csv       # Vaccination impact analysis (in vaccination.zip)
│   └── pandemic_phases.csv            # Wave and peak analysis
│
Note: Summary and vaccination analysis results are also available in zipped format:
- `summary.zip` - Contains summary statistics
- `vaccination.zip` - Contains vaccination analysis results
```

