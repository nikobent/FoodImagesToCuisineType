# FoodImagesToCuisineType
During this project, we created a system that detects the type of cuisine of a cooked food. 
In more details, using a picture of a meal as an input we extract the ingredients of this meal.
The ingredients then are fed to another model which predicts the cuisine type based on the ingredients.
For the picture --> Ingredients model, we used a kaggle dataset from dishes to cuisine.
The second dataset is created by facebook research team


In the main folder there exist the notebooks prepared to train the BoW model and the word Embeddings model with the datasets needed. 
The first dataset comes for kaggle and includes ingredients from dishes with their cuisine.
The second dataset is the result of predicting the ingredients of our testing images using the model of : https://github.com/facebookresearch/inversecooking . 

# How it works
![What happens in the pipeline](https://github.com/nikobent/FoodImagesToCuisineType/blob/masterhwoitworks.png?raw=true "Pipeline")

# How to use the models
Inside the finalDemo folder, there is the option to test the final pipeline. <br>
To do so:<br> 1. place only one Image to demo_images and delete anything in the folder. <br>
	2. download the best model available at the above link and place them outside the demo_images folder.<br>
	3. change the path inside the demo code to your path and you are ready to go.<br>
