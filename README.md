# BDAProject
In this project, given reviews for a product, we essentially identify its features/attributes and then extract opinion about those product features and classify them as positive or negative. We will analyze the opinion expressed for each product feature and observe the good and bad features from a customer's perspective. 

We have used a dataset with approximately 1.5GB of data per product. This dataset is on postgreSQl at the moment. We have used spark to load and work with such a large dataset since spark is great for consistent data and provides an interface for programming clusters with implicit data parallelism.

Following are the processes that we have implemented:

Step 1 : Binary classification - Run BDA.ipynb
Step 2 : Cleaning of kaggle dataset - Cleanup.ipynb
Step 3 : Cleaning of Headphone Dataset - Headphone_Dataset_cleaning.ipynb
Step 4 : Topic Modeling - LDA_Topic_Modeling.ipynb
Step 5 : Sentiment Analysis - Sentiment_Analysis_2.ipynb
