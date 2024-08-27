## OSA-screening
This repository contains two machine learning models developed using XGBoost, which have demonstrated the best accuracy for predicting the likelihood of:
- Moderate to severe OSA (AHI ≥ 15)
- Severe OSA (AHI ≥ 30)  

Both models use key body profile features to assess the risk of OSA in individuals.  


## Input and output formats
The models accept the following body profile data as input:  
- Age (in years)
- Sex (Male/Female)
- Body Mass Index (BMI)
- Neck circumference (in cm)
- Waist circumference (in cm)

Each model outputs a prediction as either:
- 0: Low risk of moderate to severe OSA (AHI ≥ 15) / severe OSA (AHI ≥ 30)
- 1: High risk of moderate to severe OSA (AHI ≥ 15) / severe OSA (AHI ≥ 30)
