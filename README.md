# Home depot product search relevance - Kaggle competition project

This data has information about an online shopping website of a Home Depot Shop. The relevant columns in data are:
1. The search query that the user puts while searching the product  
2. The title of the product that the website returns  
3. The text description of the product the website returns   
4. The relevance score from 1 to 4 stating how relevant the result of the search query was - 1 being not relevant , 4 being very relevant  
  
Currently the task of finding out the relevance score is done by human annotators. The task is to create a model that will find out the relevance score to near human accuracy or better than human accuracy. I have used a transformer model 'all-mpnet-base-v2' to extract embeddings and passed this to multi layer perceptron model using stacked dense layers.
