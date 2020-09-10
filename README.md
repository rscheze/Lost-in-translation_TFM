# Lost-in-translation_TFM
Understand Black-box Predictions

Final work detail:  https://rscheze.wixsite.com/rse-tfm2020

•	Sales representatives require relevant information to address a customer and build rapport.This has a deep impact on customer experience.

•	This work aims to reduce the gap between a model prediction and the information required for Sales representatives to address a customer (Explanation through Explainability(1)).

•	Behind this work, there is not only a classification problem (whether a customer will get a personal loan or not) but also, and most importantly, why a specific person could be more interested in a specific product/service than another and the reasons behind that prediction.

•	This work walks through the entire technical modelling process to be able to build a business plan with the information required for Sales representatives required on the who,how and why.

Requirements 

Running this Project requires Python Notebook and the instalation of the following libraries:

o	collections

o	imblearn

o	folium

o	xgboost  

o	mlens

o	lime

Files used in the Project

o	Raw_data_TFM.CSV (unzip file required)

o	Spain_provincias (used to map with geopandas. Unzip file required).

o	Pobmun19.csv (included as part of the previous work with SAS to add number of population by province. Information included from INE website). Information already included in the Raw_data_TFM file.


Let´s begin!!! 

(1)<<Explainability/interpretability is the dregree to which a human can consistenly predict the model results>> (Kim.Been,Rajiv Khana and Oluwasanmi) 


Although the initial information included in the dataset is real, in order to present this work and to comply with current regulations, all data has been anonymized.  

