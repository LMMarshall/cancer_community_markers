# cancer_community_markers
 This is a project for cancer death rates based on 41 community markers from the Public Health England Fingerprints data source.
 
 The data covers 299 local authority areas in England, and the markers for each of these 'communities' include things like diabetes rates, air pollution, noise, mental health,
 education, etc.
 
 4 files are included in this repository:
 
 * Cancer_by_community_fetch_and_preprocessing.ipynb -- a notebook that fetches and preprocesses the data
 * Cancer_Regression_Explore.ipynb -- a notebook for initial exploratory analysis
 * Cancer_Regression_Predict.ipynb -- a notebook that splits the data into test, training, and validation sets and runs through various models to find the strongest predictor
 * Cancer_Regression_Explain.ipynb -- a notebook that focuses on an explanatory rather than predictive approach; highlights the factors showing the highest explanatory power.
