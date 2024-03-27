# Resume-Job-Matcher

Data Collection:
jobs_data_collection.ipynb


# Methodology 
The project involves the following steps:

* Data Preparation: Loading and combining job data, removing duplicates.
* Text Preprocessing: Preprocessing job descriptions and titles, removing irrelevant words, lemmatization.
* Word2Vec and Clustering: Training Word2Vec models, creating combined vectors, applying K-Means clustering.
* Resume Matching: Preprocessing resumes, converting them to vector representations, matching them to jobs.
* Visualization and Analysis: Visualizing word clouds, using t-SNE for dimensionality reduction, evaluating clustering.


# Results
* The system provides a list of top matching jobs for a given resume, based on the similarity between the resume and job descriptions and titles.
