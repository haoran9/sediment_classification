# sediment_classification
Our study uses multiple machine learning classifiers to identify the sediment types of Caminada dredge pit in eastern part of submarine 
sandy Ship Shoal of Louisiana inner shelf of USA and compares the performance of multiple supervised classification methods.


# abstract 

Machine learning classifiers have been rarely used for the identification of seafloor sediment types in the rapidly-changing 
dredge pits for coastal restoration. Our study uses multiple machine learning classifiers to identify the sediment types of 
Caminada dredge pit in eastern part of submarine sandy Ship Shoal of Louisiana inner shelf of USA and compares the performance 
of multiple supervised classification methods. High-resolution bathymetry and backscatter data and 58 sediment grab samples 
were collected in Caminada pit in August 2018, about 2 years after dredging. Two primary (bathymetry and backscatter) and 
four secondary features were selected in the machine learning models. Three supervised classifications were tested in the 
study area: Decision Trees, Random Forest, and Regularized Logistic Regression. The models were trained using three different
sets of features: 1) all six features, 2) only bathymetry and backscatter, and 3) a subset of selected features. 
The best performing model was the Random Forest method, but its performance was relatively poor when 
dealing with a few mixed (sand and mud) surficial sediment samples. The model provides a new and 
efficient method to predict the change of sediment distribution inside Caminada pit and is more reliable when 
predicting mixed bed with rough pit bottoms. Our results can be used to better understand the impacts on biological communities
by (1) direct defaunation after initial sand excavation, (2) later mud accumulation in topographic lows, and 
(3) other geological and physical processes. In the future, the deposition and redistribution of mud inside 
Caminada pit will continue, likely impacting benthos and water quality.  Backscatter, roughness derived from bathymetry, 
rugosity derived from backscatter, and bathymetry (in the importance order from high to low) were identified as the most effective
predictors of sediment texture for mineral resources management.

The paper can be downloaded in the following link:
https://www.mdpi.com/2073-4441/11/6/1257

You can find the code in classification_R and run it in R_studio. 

