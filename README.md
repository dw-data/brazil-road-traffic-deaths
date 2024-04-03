# Why are traffic deaths in Brazil rising again? 

This repository countains the source code and data for the DW Data story about road traffic deaths in Brazil.

You can read the story in [Portuguese](https://www.dw.com/pt-br/o-que-explica-a-nova-alta-de-mortes-no-tr%C3%A2nsito-do-brasil/a-68552779). There's also a [Spanish version of this story](https://www.dw.com/es/el-flagelo-de-los-accidentes-de-tr%C3%A1nsito-en-am%C3%A9rica-latina/a-68693381) that focus on Latin American data.

## Data sources

This story consists of an analysis of the historical evolution of Brazilian road traffic deaths, which are also compared to worldwide trends.

For the Brazilian road traffic deaths, we used data from the Ministry of Health, taken from the [Datasus mortality monitoring platform](https://datasus.saude.gov.br/mortalidade-desde-1996-pela-cid-10). The [2000-2021 population estimates](https://datasus.saude.gov.br/populacao-residente) were also taken from Datasus. For the 2022 population, we performed a simple linear regression with the 2000-2021 population estimates.

Data about the composition of the Brazilian fleet comes from the [Ministry of Transportation](https://www.gov.br/transportes/pt-br/assuntos/transito/conteudo-Senatran/frota-de-veiculos-2023).

For other countries, figures come from the [World Health Organization database](https://www.who.int/data/gho/data/indicators/indicator-details/GHO/estimated-road-traffic-death-rate-\(per-100-000-population).

Income level and regional country classifcations come from the [World Bank](https://datatopics.worldbank.org/world-development-indicators/the-world-by-income-and-region.html).


## Repository structure

The `code` directory contains the Jupyter Notebooks with the step-by-step data analysis. 

The `data` directory contains the data files that were used in the analysis, already manually cleaned.

The `output` repository contains the processed CSV files which were used to create Datawrapper visualizations.
