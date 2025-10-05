# Master's Thesis Literature Review

This repository contains critical reviews of scientific papers focusing on the mathematical and statistical aspects of vector-borne disease modeling for my master's thesis literature review.

## About

This collection provides in-depth critiques of key papers in vector-borne disease modeling, focusing on frameworks that explore human mobility, transmission dynamics, and disease control strategies. Each review includes:

- Critical analysis of the mathematical models and assumptions,

- Interpretation of results and implications for disease control,

- Figures, flowcharts, and equations to illustrate key concepts,

- References and links to the original publications.

- Identification of inconsistencies or methodological issues


## Paper Reviews

## 1. The Effects of Human Movement on the Persistence of Vector-Borne Diseases.

- **Authors:** C. Cosner, J.C. Beier , R.S. Cantrell, D. Impoinvil, L. Kapitanski, M.D. Potts, A. Troyo, S. Ruan

- **Published:** Journal of Theoretical Biology, 2009

- **DOI/Link:** <https://doi.org/10.1016/j.jtbi.2009.02.016>

- **Key Issues Identified:** 

Mathematical inconsistencies: The model neglects the possible recovered population in the differential equations, which contradicts the study’s claim of following the Ross–Macdonald framework.

Vector population assumptions: The effective mosquito population in each patch is erroneously neglected, despite claims that mosquitoes can move between meta-population patches.

Terminology issues: The paper uses mathematically incorrect or misleading terms, such as “discrete diffusion,” which does not exist in standard mathematical literature and may confuse readers about the model’s assumptions.


## 2. Assessing the Interplay Between Human Mobility and Mosquito Borne Diseases in Urban Environments

- **Authors:** E. Massaro, D. Kondor, and C. Ratti

- **Published:** Scientific Reports, Volume 9, Article 16911, in 2019

- **DOI/Link:** <https://doi.org/10.1038/s41598-019-53127-z>

- **Key Issues Identified:**

Mathematical inconsistencies: The model neglects the recovered population in the differential equations, contradicting the claimed use of the Ross–Macdonald framework.

Vector population assumptions: The effective mosquito population in each patch is erroneously neglected, despite claims that mosquitoes can move between meta-population patches.

Misuse of fundamental concepts:

The paper treats rate and probability interchangeably, despite their distinct mathematical meanings.

Probabilities are incorrectly assumed to have linear behavior over time.

The binomial distribution is erroneously applied to model transitions between SEIR compartments.

The carrying capacity in the logistic model is introduced with an incorrect interpretation.

Temperature-dependent variables are used without specifying how temperature is incorporated into the model.


## 3. Vector-borne epidemics driven by human mobility

- **Authors:** David Soriano-Paños, Juddy Heliana Arias-Castro, Adriana Reyna-Lara, Hector J. Martínez, Sandro Meloni, Jesús Gómez-Gardeñes

- **Published:** Physical Review Research, 2020

- **DOI/Link:** <https://doi.org/10.1103/PhysRevResearch.2.013312>

- **Key Issues Identified :**

The model is formulated in a deterministic setting. While developing it, the probability that an individual in the i‑th population at time t becomes infected was incorrectly derived. However, the simulations still reflect realistic outcomes because the parameter values used effectively approximate the infinite population assumption inherent in the deterministic framework.







