# LegalCaseTextClassification

1. Abstract

	Reading and searching for legal case documents is time-consuming for lawyers. Therefore, this project apply machine learning, deep learning and especially Natural Language Processing to build the text classification model, which can classifies each part/head text in a legal document into different category. In a legal document, there are several sub-texts, which might vary for each document. However, in our project we define six specific head texts that appear in a single document. They are facts, order and decision, reasons/analysis, issues, rules and procedure history, which play label/target variables role in our predictive models. The reasons we choose these categories as our labels is because we found them appear very frequently in our dataset. The models will assist 

2. Contribution

	Built all traditional machine learning models as based-line models to compare with deep learning models. 
		 Classify each part of a legal document into different categories, which is foundation to support search engine, resulting in reducing time-consuming for lawyers. 
		 
3. Result/Conclusion

	We built all models based on two approaches, TF-IDF and word2vector. Consider TF-IDF approach, the logistic regression model and SVM give the highest  accurracy score on test dataset, approximately 0.669, followed by LGBM, 0.6021. In word2vector approach, The SVM results the highest accuracy score on test dataset, 0.646, followed by LGBM, 0.612, and XGB, 0.601. In conclusion, TF-IDF approah results higher accuracy score than word2vector approach. Consider model types, logistic regression, SVM, LGBM and XGB give the high accuracy score for this particular project.
	
5. Objective

	 Built end-to-end development of machine learning algorithms as base-line models.

4. Tasks: 

  	a. Cleansed data using data preprocessing techniques to make data useful for machine learning models.(In Cleaned_Data folder)
	
  	b. Encoded the text data using TF-IDF and Word2vector to make appropriate inputs for predictive models.(In Model Development)
	
  	c. Built all classification ML algorithms such as logistic regression, SVM, LGBM,..etc.(In Model Development)
	
  	d. Evaluated the all the models' performance based on TF-IDF and word2vector approaches.(In Model Development)
	


