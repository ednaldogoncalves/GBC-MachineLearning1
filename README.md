### About

- These codes are part of the Machine Learning I (AASD 4000) course studies of the Postgraduate in Applied A.I. Solutions Development (T431) program at George Brown College.
- For more information about the program, visit the [Website](https://www.georgebrown.ca/programs/applied-ai-solutions-development-program-postgraduate-t431).
  
![](https://www.georgebrown.ca/themes/custom/de_theme/logo.svg)

------------

# Task 1 - Python Web Scraping

- This task tests your understanding of Python language in applying it to a specific well-defined task of web scraping.
- Create a Python script for enabling web scraping.
- Input: Url (medium article)
- Output: File stored in your local machine with the text from the url
- Submission files: .txt and .py file

### You require the following libraries to accomplish that.
- **os** - File storing in the local directory of your machine
- **requests** - Used for sending requests with url as input and get html source as response
- **beautifulSoup** - Used in parsing html source response (https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

### Steps to be followed to complete this task
1. Import library
2. Study the library usage in its documentation
3. Fill in the blank provided in the Script (Write your code between Code goes here and Code ends here comments)
4. Run the python script with the given url of medium article
5. By running the script, a new folder called “scraped_articles” would be created in your local machine.
6. Please find the .txt file and upload that as the submission file along with your python file.

# Task 2 - Github
- This task tests your understanding of Github commands and processes in pushing new code into the existing repo.
- Replicate the answer from the previuos Python script for enabling web scraping into a Jupyter Notebook. Push these three files (text file, python script and notebook) into your Github account.
- Input(s): Text (.txt), Python script (.py) and Notebook (.ipynb)
- Output: Github account with these three files pushed, reviewed and merged into the master branch of your repo

### You require the following to accomplish that.
- **python script** - Task 1 answer ([task1.py](https://github.com/ednaldogoncalves/GBC-MachineLearning1/blob/github_task/task1.py))
- **Text file** - Task 1 text file ([papa-what-is-a-neural-network-c5e5cc427c7.txt](https://github.com/ednaldogoncalves/GBC-MachineLearning1/blob/github_task/scraped_articles/papa-what-is-a-neural-network-c5e5cc427c7.txt))
- **Notebook** - Replicated answer in a notebook file ([task2.ipynb](https://github.com/ednaldogoncalves/GBC-MachineLearning1/blob/github_task/task2.ipynb))
- **Github repo** - Your repo that you have created already

### Steps to be followed to complete this task
1. Open a new jupyter notebook and name it task2.ipynb
2. Replicate the answer you’ve got in Task1 into cells inside the newly created notebook
3. Choose one of your classmate and add him/her as a collaborator in your Repo's settings
4. Create a new branch called "github_task"
5. Commit the .py, .ipynb and .txt files
6. Push these files into the branch
7. Create a Pull Request with a Reviewer you have selected
8. Wait for approval from your reviewer
9. Merge the branch into the master branch
10. Submit the repo link as the submission file

# Task 5 - Pandas Covid Data Analysis
- This task tests your understanding of Pandas library for the purpose of analyzing and visualizing data.
- Create a Python notebook for enabling data analysis on Covid data.
- **Input:** Question Notebook, Covid data
- **Output:** Notebook containing solutions within provided cells
- **Submission file:** .ipynb file ([Pandas_Covid_Analysis_Solutions.ipynb](https://github.com/ednaldogoncalves/GBC-MachineLearning1/blob/github_task/Pandas_Covid_Analysis_Solutions.ipynb))

### Steps to be followed to complete this task
1. Launch Jupyter Notebook from your python environment
2. Open the notebook in the browser
3. Check the dataset provided
4. Read its fields in the description
5. Have the Pandas documentation ready by your side
6. Fill in the cell with your solutions for all questions
7. Hint: Certain questions require you to plot the data
8. Read plotly documentation to plot a series and a dataframe
9. Once completed and satisfied with your answers, Please save the notebook and submit the .ipynb file as the submission file.

# Task 6 - Predicting Real Estate House Prices
- This task is used to test your understanding of scikit-library and its application of building a very simple Linear Regression model on the provided dataset.

### Steps to be followed to complete this task
1. Please see the attached notebook for further instructions.
2. Dataset: Real_estate.csv
3. Import the necessary libraries
4. You are required to complete (fill in code) between the spaces provided.
5. For submission, please submit the finished, saved notebook (.ipynb) file ([Real_Estate_Price_Prediction.ipynb](https://github.com/ednaldogoncalves/GBC-MachineLearning1/blob/github_task/Real_Estate_Price_Prediction.ipynb)).

# Task 7 - AutoFeatureSelector Tool
- This task is to test your understanding of various Feature Selection methods outlined in the lecture and the ability to apply this knowledge in a real-world dataset to select best features and also to build an automated feature selection tool as your toolkit¶

### Use your knowledge of different feature selector methods to build an Automatic Feature Selection tool
- **Pearson Correlation**
- **Chi-Square**
- **RFE**
- **Embedded**
- **Tree (Random Forest)**
- **Tree (Light GBM)**

### Steps to be followed to complete this task
1. Individual Feature Selection methods
2. Ensembling (Grouping) all the methods' results to obtain the best set of features
3. Convert the notebook answer into a Python script
4. Submit two files
- Notebook (.ipynb) ([AutoFeatureSelector.ipynb](https://github.com/ednaldogoncalves/GBC-MachineLearning1/blob/github_task/AutoFeatureSelector.ipynb)).
- Python (.py) ([AutoFeatureSelector.py](https://github.com/ednaldogoncalves/GBC-MachineLearning1/blob/github_task/AutoFeatureSelector.py)).
7. The byproduct of this task is you would have created your very own FeatureSelector Tool that you can use in your data projects.

# Task 8 - Data Imputation
- This task tests your ability to do data imputation with different strategies on different algorithms.

## SimpleImputer
#### This notebook outlines the usage of Simple Imputer (Univariate Imputation).
#### Simple Imputer substitutes missing values statistics (mean, median, ...)

## IterativeImputer
#### This notebook outlines the usage of Iterative Imputer (Multivariate Imputation).
#### Iterative Imputer substitutes missing values as a function of other features

## Dataset:
- [https://github.com/subashgandyer/datasets/blob/main/heart_disease.csv]

**Demographic**
- Sex: male or female(Nominal)
- Age: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)

**Behavioral**
- Current Smoker: whether or not the patient is a current smoker (Nominal)
- Cigs Per Day: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarettes, even half a cigarette.)

**Medical(history)**
- BP Meds: whether or not the patient was on blood pressure medication (Nominal)
- Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)
- Prevalent Hyp: whether or not the patient was hypertensive (Nominal)
- Diabetes: whether or not the patient had diabetes (Nominal)

**Medical(current)**
- Tot Chol: total cholesterol level (Continuous)
- Sys BP: systolic blood pressure (Continuous)
- Dia BP: diastolic blood pressure (Continuous)
- BMI: Body Mass Index (Continuous)
- Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)
- Glucose: glucose level (Continuous)

**Predict variable (desired target)**
- 10 year risk of coronary heart disease CHD (binary: “1”, means “Yes”, “0” means “No”)

## Steps to be followed to complete this task
1. The attached notebook gives you the detailed instructions.
2. Submit two files Notebook (.ipynb)
- ([Preprocessing_05_Simple_Imputer.ipynb](https://github.com/ednaldogoncalves/GBC-MachineLearning1/blob/github_task/Preprocessing_05_Simple_Imputer.ipynb)).
- ([Preprocessing_06_Iterative_Imputer_Solution.ipynb](https://github.com/ednaldogoncalves/GBC-MachineLearning1/blob/github_task/Preprocessing_06_Iterative_Imputer_Solution.ipynb)).

# Task 9 - Best Random Forests
- This task tests your ability to build a Random Forest Machine Learning Algorithm and also tests your ability to build a Random Search Random Forest Machine Learning Algorithm.
- Kindly see the attached notebook for instructions and the task requirements are outlined there in detail.

## Dataset:
- [https://www.kaggle.com/datasets/cdc/behavioral-risk-factor-surveillance-system?select=2015.csv]

### Task Requirements
- Build a RandomForest for the above dataset (not one but many with different sets of parameters)
- Explore RandomizedSearchCV in Scikit-learn documentation
- Create a parameter grid with these values
    - n_estimators : between 10 and 200
    - max_depth : choose between 3 and 20
    - max_features : ['auto', 'sqrt', None] + list(np.arange(0.5, 1, 0.1))
    - max_leaf_nodes : choose between 10 to 50
    - min_samples_split : choose between 2, 5, or 10
    - bootstrap : choose between True or False
- Create the estimator (RandomForestClassifier)
- Create the RandomizedSearchCV with estimator, parameter grid, scoring on roc auc, n_iter = 10, random_state=RSEED(50) for same reproducible results
- Fit the model
- Explore the best model parameters
- Use the best model parameters to predict
- Plot the best model ROC AUC Curve
- Plot the Confusion Matrix
- Write any insights or observations you found in the last

### Inlcude a document answering the following questions...
1. What is GridSearchCV, RandomizedSearchCV.
2. Why there is RCV when GSCV is already there.
3. When to use what CV.
4. Can we use it together if yes, in what order or in no order.
- ([Best_Random_Forests.ipynb](https://github.com/ednaldogoncalves/GBC-MachineLearning1/blob/github_task/Best_Random_Forests.ipynb)).
- ([Task9_Answer.docx](https://github.com/ednaldogoncalves/GBC-MachineLearning1/blob/github_task/Task9_Answer.docx)).

# Task 10 : Benchmark Top ML Algorithms
- This task tests your ability to use different ML algorithms when solving a specific problem.

### Dataset
Predict Loan Eligibility for Dream Housing Finance company

Dream Housing Finance company deals in all kinds of home loans. They have presence across all urban, semi urban and rural areas. Customer first applies for home loan and after that company validates the customer eligibility for loan.

Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have provided a dataset to identify the customers segments that are eligible for loan amount so that they can specifically target these customers.

Train: https://raw.githubusercontent.com/subashgandyer/datasets/main/loan_train.csv

Test: https://raw.githubusercontent.com/subashgandyer/datasets/main/loan_test.csv

## Task Requirements
### You can have the following Classification models built using different ML algorithms
- Decision Tree
- KNN
- Logistic Regression
- SVM
- Random Forest
- Any other algorithm of your choice

### Use GridSearchCV for finding the best model with the best hyperparameters

- Build models
- Create Parameter Grid
- Run GridSearchCV
- Choose the best model with the best hyperparameter
- Give the best accuracy
- Also, benchmark the best accuracy that you could get for every classification algorithm asked above

#### Your final output will be something like this:
- Best algorithm accuracy
- Best hyperparameter accuracy for every algorithm

**Table 1 (Algorithm wise best model with best hyperparameter)**

Algorithm   |     Accuracy   |   Hyperparameters
- DT
- KNN
- LR
- SVM
- RF
- anyother

**Table 2 (Best overall)**

Algorithm    |   Accuracy    |   Hyperparameters

### Submission
- Submit Notebook containing all saved ran code with outputs ([Benchmark_ML_Algorithms.ipynb](https://github.com/ednaldogoncalves/GBC-MachineLearning1/blob/github_task/Benchmark_ML_Algorithms.ipynb)).
- Document with the above two tables ([Task10_Benchmark.docx](https://github.com/ednaldogoncalves/GBC-MachineLearning1/blob/github_task/Task10_Benchmark.docx)).