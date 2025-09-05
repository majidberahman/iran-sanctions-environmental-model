# iran-sanctions-environmental-model
This repository contains the data and code for the paper "Sanctions as a Catalyst of Environmental Collapse in Iran." The aim is to provide a fully reproducible framework for the analysis of a multi-actor dynamical model and to examine the relationship between sanctions and environmental outcomes.
This repository contains the data and code for the paper titled: "Sanctions as a Catalyst of Environmental Collapse: A Multi-Actor Dynamical Model for Iran."

The datasets for this simulation were sourced from the World Bank's data portal (data.worldbank.org). The repository includes four key data files from 1990 to 2020 for Iran:

API_EN.GHG.CO2.PC.CE.AR5_DS2_en_csv_v2_493289: CO2 emissions per capita.

API_EG.ELC.RNWX.ZS_DS2_en_csv_v2_493651: Renewable electricity consumption (% of total).

API_AG.LND.FRST.ZS_DS2_en_csv_v2_493149: Forest area (% of land area).

API_ER.H2O.FWTL.ZS_DS2_en_csv_v2_493513: Freshwater withdrawal (% of internal renewable water resources).

The simulation code, developed and executed in Google Colab, is organized into several sections corresponding to the paper's methodology:

Data Processing: In the first section, the four datasets are loaded, and the initial five rows and columns of each file are displayed to confirm data format.

Exploratory Data Analysis (EDA): The second section visualizes the data over time, with a specific focus on illustrating the impact of sanctions.

Model Simulation: The subsequent sections simulate the multi-actor dynamical model based on the equations presented in the paper. The code includes dedicated analyses for:

Delay is Costly

Impact of Gradual Sanctions Removal

System Stability and Resilience

This repository aims to provide a transparent and reproducible framework for researchers and policymakers to explore the intricate dynamics between sociopolitical pressures and environmental outcomes in Iran. The code is well-documented to facilitate understanding and replication of the study's findings.
