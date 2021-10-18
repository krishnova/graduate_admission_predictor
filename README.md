# GradAdmits - The Graduate Admissions Predictor App

>https://gradadmits.herokuapp.com/

## About the Project

An **end-to-end ML project** that predicts the chances of getting an admit in a University based on different features like *University Rating, Student’s Undergrad GPA,
GRE & TOEFL scores, Research experience and the quality of SOP & LOR*. It returns the chance of getting an admit in a particular university in *percentage* format.


## Description

Following algorithms were used:

* Linear Regression
* Artificial Neural Network (ANN) 
* Random Forest 
* Decision Tree 

**Linear Regression** had the highest accuracy among all the algorithms. Various Regression KPIs like *Root Mean Square Error (RMSE), Mean Square Error (MSE), Mean Absolute Error (MSE), R-square (r2_score)* were analysed. In the end Linear Regression model was deployed due to lack of storage on Heroku. All other models can run locally.


## Dependencies

* tensorflow 	   	```pip install tensorflow```
* scikit-learn     	```pip install -U scikit-learn```
* flask		   	```pip install flask```
* pickle	   	```pip install pickle``` 	
* matplotlib.pyplot	```pip install matplotlib```
* seaborn		```pip install seaborn```
* numpy			```pip install numpy```
* pandas		```pip install pandas```


## Steps to Run this Project

1. Fork this repository 

2. Clone this [GitHub Repository](https://github.com/krishnova/graduate_admission_predictor) in your system. 

3. In command line (anaconda prompt), go to the folder that contains all the project files. Run the command ```python app.py``` which will give you an address like ```localhost:5000``` or ```localhost:8050``` Copy and paste it in the address bar of web browser.
 
4. The project's interface will load locally on the web browser.
 

## Entering Features for Prediction

![GUI_2](https://github.com/krishnova/graduate_admission_predictor/blob/6b337caf1d8895162310b5415bfc6a85e20b3d43/templates/screenshot_1.png)

## Prediction Results

![GUI_3](https://github.com/krishnova/graduate_admission_predictor/blob/6b337caf1d8895162310b5415bfc6a85e20b3d43/templates/screenshot_2.png)


>Link: [GradAdmits App](https://gradadmits.herokuapp.com/)
