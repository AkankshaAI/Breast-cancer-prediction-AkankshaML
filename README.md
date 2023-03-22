# Breast-Cancer-Early-Prediction

### This website and ML model is built to identify women suffering from breast cancer in its early period .

## Website Frontend
<img src="frontend images/1.jpg" alt="#" width="800" height="500">
<img src="frontend images/2.png" alt="#" width="800" height="500">
<img src="frontend images/3.webp" alt="#" width="800" height="500">
<img src="frontend images/4.webp" alt="#" width="800" height="500">
<img src="frontend images/5.webp" alt="#" width="800" height="500">

## Steps to be Followed 

* Your machine will need numpy, scikit-learn, pandas, flask, pymongo, pymongo[srv], dns, json, and bson to run this code. To get any of these libraries, you can just pip install [insert library here] in a terminal window. To run the code, first pull the github to your computer and then navigate to the folder where app.py is. Then open terminal and run the command flask run. This will direct you to a localhost website where you can interact with the product.

## Detailed Instructions:
* Open command prompt
* Install numpy, scikit-learn, pandas, flask, pymongo, pymongo[srv], dns, json, and bson using pip install [insert library here]
* Then download the github repo to your computer
* Locate the repo in your file explorer -- Open command prompt from that folder's search bar by typing cmd into it
* Then enter flask run in the command prompt
* Appplication may run now
## To use the detection feature:
Navigate to the "Detect" tab using the navigation bar on the website. Then insert values in the range (1-10) into each of the input fields. Click submit and you should see the prediction for the data you inputted. This prediction, as well as the data you input, are saved to the MongoDB database.

## To use the lookup feature:
Navigate to the "Lookup" tab using the navigation bar on the website. A doctor who had access to the database would be able to freely put in any of his patient's IDs. For demonstation purposes, use one of the following IDs: 5f2f13e8218e81e41faf62d2, 5f2f1e3d218e81e41faf62d4, 5f2f3a64755cd3292de46ebd. Click submit and you should see that the data for the patient as well as their prediction and confidence level are visible.

## How it works
Using machine learning, we have developed a program that detects whether a tumor is malignant or benign (given their symptoms or characteristics). To train our model, we used publicly available datasets for breast cancer patients. Using the machine learning algorithm, we implemented a web application where users can input 9 specific characteristics regarding the tumor. The algorithm then returns a breast cancer prediction and confidence value given the corresponding characteristics.

We also utilized a MongoDB database for doctors to look up and store their patients' information securely allowing them to make informed decisions about their healthcare. Because new user inputs and results are continuously added to this database, the pool of resources and references provided for both doctors and patients alike will grow as more individuals use this application.

#### Download all the necessary modules in python 3.6 environmnet
```python 
pip install -r requirements.txt
```
#### Follow above steps to test the application
## Future Improvements
First, we would like to increase the size of our dataset. Bringing access to a greater number of hospitals would give us increased amounts of data will give us more accurate results and would let us be much more confident in the diagnosis. Next, we would also want to increase the number of features in the dataset, giving us more variables to look at and input into the system. This would help take into account many of the other factors involved in the chances of breast cancer in people.

## What We Used
Python
Flask
Numpy
Pandas
Scikit-Learn
MongoDB / Pymongo
HTML/CSS
DNS
Reactjs 

