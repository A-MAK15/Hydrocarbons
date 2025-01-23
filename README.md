# Hydrocarbons
This project focueses on predicting the melting point and boiling point of hydrocarbons, this information
is important because these molecules are mostly used as fuels therefore the knowledge of their behaviour 
around heated temperatures is very crucial. 

## Features
The initial dataset did not have enough features to produce a quality model, so new features such as Atomic weight
and Aromatic Rings were appended to the dataset, this was achieved through the utilization of smiles which were part
of the initial dataset. 

## The Dataset
The dataset consists of chemical demographics which include:-
-**Class of hydrocarbon**
-**IUPAC name**
-**Melting point**
-**Boiling point**
-**Density**	
-**Flash point**	
-**Autoignition temp**	
-**pubchem_id**	
-**smiles**	
-**Atomic_Weight**	
-**Aromatic_Rings**

## Requirements
To run the project, ensure you have the following installed:

- **Python 3.8+**
- **Libraries**
  - **pandas**
  - **numpy**
  - **rdKit**
  - **seaborn**
  - **scikit-learn**
