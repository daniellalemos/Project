<img src='Image/logo.png' width='150'>


# Bioinformatics approaches for polyphenolic compounds production in _Escherichia coli_

### Context

This repository was created as part of the Bioinformatics and Systems Biology project to support its development. The objective was to design an _E. coli_ strain able to produce polyphenolic compounds using known heterologous pathways. 

# Abstract

Prenylflavonoids and furanocoumarins, among the phenolic compounds, have been regarded as appealing metabolites to produce due to their wide range of applications, particularly in medicine. These compounds are difficult and expensive to chemically synthesize and purify. For that reason, they are widely extracted from a variety of plants, despite their low concentration. Therefore, improving the production of these compounds is crucial. In this work, an _Escherichia coli_ strain was designed to produce these polyphenolic compounds using known heterologous pathways. For that, genome-scale metabolic models were used to simulate in vivo behavior and optimize the mutant strain using evolutionary algorithms. It was possible to find strategies that could produce these compounds. However, the estimated flux values were very low, and some approaches use a significant number of genetic modifications which could be a problem in a laboratory context. 

# Files information

It can be found in this repository:

- Models:
  - Python scripts with the information about the GSM models used in this project and the respective insertion of the reactions in the heterologous pathways using the package COBRApy.
  - xml files generated with the new reactions of the pathways.

- Simulations:
  - Python scripts using the COBRApy and MEWpy packages with all the simulations for all the compounds and models in study: wild-type simulations, phenotype simulations and the simulations with the results from the optimizations.

- Optimizations:
  - Python scripts using the COBRApy and MEWpy packages with the optimizations for all the compounds and models in study. It can be found the following optimization problems: GOU (Gene Over/Under expression), GKO (Gene Knockout), ROU (Reaction Over/Under Expression Optimization Problem) and RKO (Reaction Knockout Optimization Problem)
  - csv files with the output from the optimization problems.

- Function of genes:
  - Python script using the Biopython Extasy package to find the function of the genes found in the optimizations.
  - xml files generated with the information about the genes fot all the compounds in stydy.
