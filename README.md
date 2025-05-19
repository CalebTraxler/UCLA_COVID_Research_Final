# COVID-19 Infection Dynamics: Extended SIR and SEIR Models

## Project Overview
This repository contains the source code, data, and supplementary materials for the research paper titled **"Analysis of COVID-19 Infection Dynamics: Extended SIR Model Approach"**. The project focuses on mathematical modeling of COVID-19 infection dynamics using extended Susceptible-Infected-Recovered (SIR) and Susceptible-Exposed-Infected-Recovered (SEIR) models, incorporating demographic factors such as birth and death rates, as well as vaccination effects.

---

## Table of Contents
- [Introduction](#introduction)
- [Model Descriptions](#model-descriptions)
- [Data](#data)
- [Code Structure](#code-structure)
- [Usage](#usage)
- [Results](#results)
- [Authors](#authors)
- [References](#references)
- [License](#license)

---

## Introduction
COVID-19 has posed unprecedented global health challenges. Understanding the transmission dynamics through robust mathematical modeling is critical for effective public health interventions. This project employs advanced epidemiological models to provide insights into disease spread, equilibrium stability, and vaccination impacts.

---

## Model Descriptions
- **Extended SIR Model:** Incorporates demographic processes (birth and death rates).
- **Vaccination Model:** Extends the SIR model by adding a vaccinated compartment.
- **SEIR Model:** Includes an exposed compartment, accounting for the latency period of COVID-19.

---

## Data
The analysis is based on COVID-19 infection data from Orange County, California, covering four distinct epidemic waves:
- Wave 1: April 2020 – September 2020
- Wave 2: October 2020 – March 2021
- Wave 3: July 2021 – October 2021 (Delta Variant)
- Wave 4: December 2021 – February 2022 (Omicron Variant)

Data includes daily case numbers, demographic statistics, and vaccination rates.

---

## Code Structure
```bash
COVID-Modeling/
├── data/
│   ├── covid_wave_data.csv
│   └── population_data.csv
├── scripts/
│   ├── sir_model.py
│   ├── seir_model.py
│   ├── vaccination_model.py
│   └── parameter_estimation.py
├── notebooks/
│   └── model_analysis.ipynb
├── figures/
│   ├── bifurcation.png
│   └── phase_portraits.png
└── README.md
