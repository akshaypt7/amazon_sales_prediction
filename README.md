# amazon_sales_prediction
We are trying to predict future sales of products  from amazon to improve the inventory performance. 


We have gathered the data from 2019 to 2020 April for a particular seller account in Amazon. 

What we want to do was to predict the quantities sold of each product in a given day. 

We also created a baseline model which will predict the most frequent quantity for each product. The Random Forest model we created performed better than the baseline model. 

Some of the challenges we faced was -
1) Pre-processing the data we received from amazon in the format that we need.
2) Make sure there is no data-leakage (and removing all the columns that do)
3) 


The inspiration behind this project was to implement what was learnt in a personalized project. It was successful, We understood how difficult it is to process the data and the decisions that we have to take along the way. 
This project also helped to work with Entity Embedding, and we were able to improve the performance of the models by using it. We have worked with Entity Embedding both using keras and fastai. This was done to have a better understanding on how entity embeddings work. 

We used Principal Component Analysis(PCA) to visualize the entity embedding to see the relation ship between the categories.


Future Plans Includes :
Create a web app which takes in the raw-data from amazon and predicts the future sales for each product. 
