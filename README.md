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

## Results
Regression was utilized to produce this model, the equation for the melting point is y = 0.98639651(Atomic_Weight) + 38.33524031(Aromatic_Ring) - 198.04331785.
The equation for the boiling point is y = 2.27486982(Atomic_Weight) + 26.90195984(Aromatic_Ring) - 136.90058508. Other results can be seen below:
**Melting Point**
- Coefficients                      	: [[ 0.98639651 38.33524031]]
- Intercepts                        	: [-198.04331785]
- Mean squared error                	: 2220.421
- Root mean squared error (RMSE)    	: 47.121
- Coefficient of determination (R^2)	: 0.637

**Boiling Point**
- Coefficients                      	: [[ 2.27486982 26.90195984]]
- Intercepts                        	: [-136.90058508]
- Mean squared error                	: 353.49
- Root mean squared error (RMSE)    	: 18.801
- Coefficient of determination (R^2)	: 0.94
