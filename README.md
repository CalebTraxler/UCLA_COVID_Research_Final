# UCLA_COVID_Research_Final
Here exists the repository for my Mathematical Modeling Undergraduate Research under the supervision of Assistant Adjunct Professor Shiba Biswal. During my Junior year at UCLA I applied my knowledge in Applied Mathematics, Machine Learning and Numerical Analysis to make prediction based on real Orange County COVID-19 data.

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
COVID-Modeling/
├── data/
│ ├── covid_wave_data.csv
│ └── population_data.csv
├── scripts/
│ ├── sir_model.py
│ ├── seir_model.py
│ ├── vaccination_model.py
│ └── parameter_estimation.py
├── notebooks/
│ └── model_analysis.ipynb
├── figures/
│ ├── bifurcation.png
│ └── phase_portraits.png
└── README.md

yaml
Always show details

Copy

---


## Usage
### Dependencies
Install required packages:
```bash
pip install numpy scipy matplotlib pandas
Running the Models
SIR Model:

bash
Always show details

Copy
python scripts/sir_model.py
SEIR Model:

bash
Always show details

Copy
python scripts/seir_model.py
Vaccination Model:

bash
Always show details

Copy
python scripts/vaccination_model.py
Parameter Estimation
Run parameter estimation scripts:

bash
Always show details

Copy
python scripts/parameter_estimation.py
Interactive Analysis
Use the Jupyter notebook for interactive exploration:

bash
Always show details

Copy
jupyter notebook notebooks/model_analysis.ipynb
Results
Equilibrium Analysis: Identification and stability of equilibrium points.

Bifurcation Analysis: Transition of disease dynamics as the basic reproduction number varies.

Vaccination Impact: Quantitative analysis of herd immunity thresholds.

Authors
Caleb Traxler

Minh Ton

Nameer Ahmed

Sasha Prostota

Annie Cheng

Department of Mathematics, University of California, Los Angeles

References
Key references used in this project include:

Kermack and McKendrick (1927)

Diekmann, Heesterbeek, and Metz (1990)

Martcheva (2015)

For full citations, see the References section in the paper.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments:
We acknowledge the support and resources provided by UCLA and various public health data repositories.
"""
