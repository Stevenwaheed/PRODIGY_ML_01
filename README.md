# PRODIGY_ML_01
<p>
I performed a house price prediction task using a dataset from Kaggle. 
The dataset initially contained 80 features, but I selected only the numerical features for analysis.
These included various measurements related to the house's area, rooms, bathrooms, garage, and outdoor spaces, along with the target variable, which is the sale price.

To ensure that the variables' different scales do not introduce bias in the model fitting, I scaled the selected features. 
Scaling helps to give equal importance to each feature during the model learning process.

Using the scaled features, I built a Linear Regression model to predict the house prices. 
The model learned a function that estimates the sale price based on the selected features.

To evaluate the performance of the model, I calculated the mean absolute error (MAE). 
The MAE quantifies the average difference between the predicted sale prices and the actual sale prices of the houses. 
In my case, the calculated MAE was 26680.44.

Overall, I used data preprocessing techniques, built a Linear Regression model, and assessed its performance using the MAE metric to predict house prices based on the selected numerical features.
</p>






