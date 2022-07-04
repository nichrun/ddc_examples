# Data Driven Chemistry Examples
Example cheminformatics type data analysis for ddc course

## Moonshot data
Moonshot dataset is a good example of real world pharmaceutical data. Source of data is https://github.com/postera-ai/COVID_moonshot_submissions. I attempted some regression models using fingerprint to predict IC50, however this were unsuccessful. May need graph based approach.

## Neural Network
Successfully implemented a multilayer perceptron model to predict cLogP

## Tanimoto similarity
Simple RDKit project is using fingerprints to calculate the similarity of molecules. 

## "example_data_analysis.ipynb"
Contains a few attempts at predicting IC50.
Issues could include: not enough data, messy data, mixture of scaffolds interfering with eachother
At the end of this notebook is a comparison of H-bond donor and acceptors. Can be seen that proposed drugs have more H-bond acceptors than donors, suggesting the binding site consits of H-bond donors
