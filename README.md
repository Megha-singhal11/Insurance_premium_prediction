# Insurance Premium Project

To give people an estimate of how much they need based on their individual health situation. After that, customers can work with any health insurance carrier and its plans and perks while keeping the projected cost from our study in mind. I am considering variables as age, sex, BMI, number of children, smoking habits and living region to predict the premium. This can assist a person in concentrating on the health side of an insurance policy rather than the ineffective part.

## Dataset_download_url
 https://www.kaggle.com/datasets/noordeen/insurance-premium-prediction

### Software and account Requirement.

1. [Github Account](https://github.com)
2. [Heroku Account](https://dashboard.heroku.com/login)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT cli](https://git-scm.com/downloads)
5. [GIT Documentation](https://git-scm.com/docs/gittutorial)

## Approach :
Applying machine learing tasks like Data Exploration, Data Cleaning, Feature Engineering, Model Building and model testing to build a solution that should able to predict the premium of the personal for health insurance.

### 1.Data Exploration 
Exploring the dataset using pandas, numpy, matplotlib, plotly and seaborn.

### 2.Exploratory Data Analysis 
Plotted different graphs to get more insights about dependent and independent variables/features.

### 3.Feature Engineering 
Numerical features scaled down and Categorical features encoded.

### 4.Model Building 
In this step, first dataset Splitting is done. After that model is trained on different Machine Learning Algorithms such as:
#### i.Linear Regression
#### ii.Decision Tree Regressor
#### iii.Random Forest Regressor
#### iv.Gradient Boosting Regressor
#### v.XGBoost Regressor

### 5.Model Selection 
Tested all the models to check the RMSE & R-squared.

### 6.Pickle File 
Selected model as per best RMSE score & R-squared and created pickle file using pickle library.
Webpage &Deployment : Created a web application that takes all the necessary inputs from the user & shows the output. Then deployed project on the Heroku Platform.


## SETUP

#### Create a conda environment
```conda create -p venv python==3.7 -y```

#### Activate conda environment
```conda activate venv/```

#### To install requirement file
```pip install -r requirements.txt```

#### Add files to git git add . or git add <file_name>
1.To check the git status ```git status```

2.To check all version maintained by git ```git log```

3.To create version/commit all changes by git ```git commit -m "message"```

4.To send version/changes to github ```git push origin main```




#### To setup CI/CD pipeline in heroku we need 3 information
1. HEROKU_EMAIL = singhalmegha11@gmail.com
2. HEROKU_API_KEY = <>
3. HEROKU_APP_NAME = insurance-prem-prediction12

#### TO BUILD DOCKER IMAGE

1.``` build -t <image_name>:<tagname> ```

2.To list docker image ```docker images```

3.To Run docker image ```docker run -p 5000:5000 -e PORT=5000 93719f65bc1e```

4.To check running container in docker ```docker ps``

5.To stop docker conatinerdocker stop <container_id>

## Project Pipeline
1.Data Ingestion

2.Data Validation

3.Data Transformation

4.Model Training

5.Model Evaluation

6.Model Deployement

## Deployment Link:
https://dashboard.heroku.com/apps/insurance-prem-prediction12



