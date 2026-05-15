# House Value Prediction

## Overview
This repository documents a machine learning project designed to predict median house values. The work emphasizes practical preprocessing methods to improve accuracy, focusing on handling missing data, balancing the dataset and correcting skewed distributions. The project demonstrates how structured data preparation directly impacts the reliability of predictive models.

## Dataset
The dataset used in this project was obtained from the [BostonHousing.csv](https://github.com/selva86/datasets/blob/master/BostonHousing.csv).
It contains socioeconomic and housing features for Boston suburbs. Important columns include:
- **crim**: Crime rate per capita  
- **zn**: Land zoned for large lots  
- **indus**: Non-retail business acres  
- **chas**: Charles River dummy variable  
- **nox**: Nitric oxide concentration  
- **rm**: Average rooms per dwelling  
- **age**: Proportion of older homes  
- **dis**: Distance to employment centers  
- **rad**: Highway accessibility index  
- **tax**: Property tax rate  
- **ptratio**: Pupil–teacher ratio  
- **b**: Demographic measure (based on proportion of Black residents)  
- **lstat**: Percentage of lower status population  
- **medv**: Median home value (in $1000s)
These features provide the basis for regression modeling and allow exploration of socioeconomic factors influencing housing prices.

## Methodology
1. Data Preprocessing
- Missing values addressed through imputation.
- SMOTE applied to balance underrepresented cases.
- Log transformation used to normalize skewed variables.

2. Feature Engineering
- Selection of relevant predictors.
- Transformation of categorical and numerical variables for compatibility with regression models.

3. Model Development
- Regression models trained and evaluated.
- Metrics include RMSE, MAE, and R².
- Cross‑validation applied to confirm generalization.

## Results
- Preprocessing improved prediction accuracy compared to baseline models.
- Balanced dataset reduced bias in outputs.
- Log transformation stabilized regression results.

## Repository Layout
All project files are contained in a single folder:
- House-value-prediction/ → Includes code, preprocessing scripts, and outputs.

## Future Work
- Incorporation of geospatial features for location‑aware predictions.
- Deployment as a web application for real‑time estimation.
- Testing of ensemble methods such as Random Forest and Gradient Boosting.

 
Submitted as part of CSE427 Lab Project