# Genome-scale metabolic reconstruction of the symbiosis between a leguminous plant and a nitrogen-fixing bacterium

## Project Description
This repository contains the Flux Balance Analysis (FBA) workflow and metabolic models used to investigate the metabolic reprogramming of the nitrogen-fixing bacterium. Unlike studies focused on plant-host symbiosis, this research focused on the __bacterial perspective__. We simulate how the bacterial metabolic network adjusts its fluxes to support nitrogen fixation across three distinct environmental controls: Bulk Soil, the Rhizosphere, and the Nodule environment. The goal is to identify the specific metabolic constraints and pathways that maximise natural nitrogen fixation within the bacteria themselves.

## Objectives
- Simulate the metabolic transition of a bacterium from a free-living state to a nitrogen-fixing state.
- Identify internal metabolic bottlenecks that limit $N_2$ fixation efficiency in non-symbiotic environments.
- Compare ATP production and carbon utilisation strategies across three specific environmental constraint sets.

## Backgroud
Modern agriculture faces a critical dilemma regarding nitrogen availability:
-  __The Chemical Problem__: To meet global food demands, chemical fertilisers (specifically synthetic nitrogen) are used extensively. However, the __2025 British Survey of Fertiliser Practice__ highlights that while nitrogen is essential for chlorophyll and DNA synthesis, its chemical application leads to soil degradation, water pollution, and the release of potent greenhouse gases.
-  __The Natural Solution__: Nature provides an alternative through specialised bacteria capable of __Biological Natrogen Fixation__. These bacteria possess the nitrogenase enzyme, which can break the triple bond of atmospheric $N_2$ and convert it into ammonia ($NH_3$).
-  __The Challenge__: Unlike chemical fertilisers, which are "ready-to-use", natural nitrogen fixation requires the bacteria to undergo __significany metabolic reprogramming__. This research uses __Genome-Scale Modelling (GEM) modelling__ to simulate these internal transitions, helping us understand how bacteria optimise their energy to replace chemical inputs with natural processes.

## Datase & Models
The analysis is conducted using specific iterations of high-quality genome-scale reconstruction:
- __General GEM__: Used for simulating standard metabolic states in control environments.
- __Bacteroid GEM__: A version of the model with specific constraints representing the specialised state required for nitrogen fixation.

## Bioinformation Workflow: Environment Control
- Environment 1: Bulk Soil (Free-living)Constraints: Aerobic conditions, high $O_2$ flux, and competition for limited carbon sources.Objective: Maximise bacterial biomass (growth rate).
- Environment 2: Rhizosphere (Pre-infection)Constraints: Nutrient-rich environment supplemented by organic acids (exudates).Objective: Analyse metabolic adaptation to high-nutrient availability.
- Environment 3: Nodule Environment (Bacterial Focus)Constraints: Micro-aerobic (strictly limited $O_2$), low pH, and $C_4$-dicarboxylates as the primary energy source.Objective: Maximise Nitrogenase flux and Ammonium ($NH_3$) production.

## Repository Contents
The `Code` folder contains the following files:
- `Bacteria name` contains: Coding 
  
The `Data` folder contains the following files:
- `original_models` contains: the original genome-scale modelling 

The `Models` folder contains the following files:
- `Bacteria name` contains: The rename reaction to the standard ID that is used for analysis. 

The `Results` folder contains the following files:
- `Bacteria name` contains: Analysis results from each model.



