# drug_discovery_model
this a guided project by dataprofessor  , In this project I got an exposure to build a computational biology and machine learning project end to end 
# Introduction
 The Chembl database, housing inhibitors for specific proteins crucial in drug development, presents a challenge in selecting optimal inhibitors due to the complexity of available options. To address this issue, the development of a model was undertaken, aiming to establish a descriptor capable of distinguishing the efficacy of inhibitors.

# Objective
 The primary objective of this model is to provide a solution to the inhibitor selection challenge. Leveraging pIC50 values, the model objectively evaluates and ranks inhibitors, assigning a numerical value. A pIC50 value exceeding 5 is deemed indicative of an active inhibitor.

# Model Building  

1. Data retrieval from Chembl marked the initial step, followed by meticulous preprocessing. This involved the calculation of IC50, with a randomly set threshold establishing the activation criteria.
2. Exploratory data analysis and statistical tests supported the threshold selection, utilizing Lapinski descriptors. These tests were designed to verify the distinction between active and inactive molecules.
3. Each molecule received a unique fingerprint through Padel descriptors, generating over 300 distinct fingerprints for analysis.
4. The final model, trained using coronavirus data, accepts canonical smiles and Chembl IDs as input, producing pIC50 values as output.