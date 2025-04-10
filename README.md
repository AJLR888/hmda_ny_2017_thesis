**######## Intersectional biases in loan denial prediction. An interpretability with SHAP values #################

1.- Project description:
	@  This study evaluates Logistic Regression and LightGBM models for predicting loan denials using the 2017 HMDA dataset in New York City.
	@  It focuses on fairness and bias mitigation among intersectional demographic groups, using different datasets sizes.
	@  The analysis uses SHAP values to uncover the impact of the different features.
	@  Dataset size affects fairness and model performance.
	@  Many models were used in the whole project yet the model "hmdaNY_19092024_0800_LightGBMAdvanced" was the one used in our final evaluation (Chapter 4, 5, 6)
	@  The PDF report was created on LaTeX based on the template of: 
		% Steve Gunn (http://users.ecs.soton.ac.uk/srg/softwaretools/document/templates/)
		% Sunil Patel (http://www.sunilpatel.co.uk/thesis-template/)


2.- Data sets:
	Original dataset: hmda_2017_ny.csv
	Dataset used in the models: hmdaNY_02092024_1603_Ready_2.csv


3.- Requirements and instructions:

	@  The code is ready to run on google collab. We used the m The python file include the code to install the packages needed. The versions used are the following:
		
			Pandas version: 2.2.2
			NumPy version: 1.26.4
			Scikit-learn version: 1.5.2
			Matplotlib version: 3.7.1
			Seaborn version: 0.13.1
			SHAP version: 0.46.0
			LightGBM version: 4.5.0
			SciPy version: 1.13.1
			Joblib version: 1.4.2
			Imbalanced-learn (imblearn) version: 0.12.3
			AIF360 version: 0.6.1

	@  IMPORTANT to place the dataset on the right path: df = pd.read_csv('/content/drive/My Drive/Colab Notebooks/hmdaNY_02092024_1603_Ready_2.csv')
	@  There are two main parts of this work:
			a) Data cleaning process. Was done in local environment (personal computer), the initial data set used is "hmda_2017_ny.csv" 
			b) Model evaluation was done on Google Collab, the data set used is "hmdaNY_02092024_1603_Ready_2.csv"


4.- We are sharing the link here (please, copy & paste on the address bar):

https://cityuni-my.sharepoint.com/:f:/g/personal/antonio-jose_lopez-roldan_city_ac_uk/Et6UfMqgEPxJqdrBNETgFFYBaX1gXV84cuk621cImHFFiA?e=Gixqdh


**
