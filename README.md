## Project Description
This project is about build an end-to-end machine learning project to predict the price of a car. The project also involves creating an API with FastAPI,
while using Sreamlit to create the interface. The final part of the project is to dockerize the project and deploy the project. 

## Steps 
1. Load Data 
2. Clean the Data
3. Performed Exploratory Data Analysis 
4. Remove Outliers
5. Build a Validation Framework (Train/Valida/Test)
6. Train A Model 
7. Feature Engineering 
8. Create API Using FastAPI 
9. Build a web interface  for the model using Streamlit  
19. Dockerize the application

## Environment Configuration
- Installing virtual Env
    - pip install pipenv 

- Installing Packages
    - pipenv install jupyter notebook pandas numpy matplotlib seaborn scikit-learn fastapi streamlit

- Starting Virtual Env
    - pipenv shell 

- Starting Notebook
    - jupyter-notebook 

## Dataset

### Url
- https://www.kaggle.com/datasets/deepcontractor/car-price-prediction-challenge

### Description
- CSV file - 19237 rows x 18 columns (Includes Price Columns as Target)

### Attributes
- ID
- Price: price of the care(Target Column)
- Levy
- Manufacturer
- Model
- Prod. year
- Category
- Leather interior
- Fuel type
- Engine volume
- Mileage
- Cylinders
- Gear box type
- Drive wheels
- Doors
- Wheel
- Color
- Airbags