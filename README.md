
# Predicting the price of a car

A project on predicting the price of cars using 
vehicule dataset This project is tested over more than one ml models like ExtraTreesRegressor, 
GradientBoostingRegressor, random forest,Out of these 
models GradientBoostingRegressor performed very well giving an accuracy of 85.28 
and mse of 0.52 far better than others.I had use quantilTransformer to solve the skeweness. 


## Acknowledgements

 - [Dataset](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho)


## Tech Stack

- **Programming Language:** Python
- **Front-End:** HTML, CSS, BOOTSTRAP
- **Back-End:** Flask
- **IDE:** Jupyter notebook, Pycharm



## Screenshots of the app
![](Screenshot_Images/Screenshot%20(799).png)
![](Screenshot_Images/Screenshot%20(800).png)


## How to run the app
- Open anaconda powershell
- Create a virtual environment using: conda create -n myenv python=3.6
- Activate the environment using: conda activate myenv
- Install all the required packages using: pip install packages
- Run the app using: python app.py

## Screenshot 

- The first 10 rows of the dataset
![](Screenshot_Images/Screenshot%20(798).png)

- The correlation between features.
![](Screenshot_Images/Screenshot%20(797).png)

## Workflow
### Data Collection: 
usnig the following dataset from kaggle:
https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho 
### Data Preprocessing:
- Checking null values in this case data has no null values.
- Checking the outliers and skewness: handled using quantilTransformer.
- Categorical values was handled using get_dummies.
- Feature selection is done : I drop Car-Name variable and Year after creating new feature called no_Year wish stand for number of year wchich is the current year - year.
- Feature scalling : not used because I choose models that are tree-based.
### Model Creation:
* I used tree models: ExtraTreesRegressor, GradientBoostingRegressor, random forest.
* I select GradientBoostingRegressor because it gives the less mse and best accuracy.

##  Links
[![linkedin](https://jo.linkedin.com/in/nouhaila-bouanane-4a1313242)](https://www.linkedin.com/)
