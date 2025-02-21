# EmployeeDataset
This project involves analyzing an employee dataset to uncover insights related to employee demographics, education levels, payment tiers, and other factors. The analysis is performed using Python libraries such as Pandas, Seaborn, and Matplotlib
## Dataset Overview
The dataset contains the following columns:

* Education: The education level of the employee (Bachelors, Masters, PhD).
* JoiningYear: The year the employee joined the company.
* City: The city where the employee is based (Bangalore, New Delhi, Pune).
* PaymentTier: The payment tier of the employee (1, 2, 3).
* Age: The age of the employee.
* Gender: The gender of the employee (Male, Female).
* EverBenched: Whether the employee has ever been benched (Yes, No).
* ExperienceInCurrentDomain: The number of years of experience the employee has in their current domain.
* LeaveOrNot: Whether the employee has left the company (1 for Yes, 0 for No).
## Data Preprocessing
* Loading the Data: The dataset is loaded using Pandas.
* Data Cleaning: The dataset is checked for null values and duplicates, which are then removed.
* Encoding Categorical Variables: Categorical variables are encoded using LabelEncoder.
## Exploratory Data Analysis (EDA)
* Education Distribution: A pie chart is created to show the distribution of education levels among employees.
* Joining Year Distribution: A count plot is created to show the number of employees joining each year.
* City and Joining Year Distribution: A stacked bar plot is created to show the distribution of employees by joining year and city.
* Gender and Education: A count plot is created to show the distribution of education levels across genders.
* Payment Tier and Gender: A count plot is created to show the distribution of payment tiers across genders.
* Gender, Payment Tier, and Joining Year: A heatmap is created to show the distribution of employees by gender, payment tier, and joining year.
* Ever Benched and Gender: A count plot is created to show the distribution of bench status across genders.
* Experience in Current Domain: A count plot is created to show the distribution of experience in the current domain across genders and payment tiers.
* Leave or Not: A stacked bar plot is created to show the distribution of employees who have left the company by gender and bench status.
## Machine Learning Model
* Data Preparation: The dataset is split into features (X) and target (y), and then into training and testing sets.
* Model Training: A Support Vector Machine (SVM) model is trained on the training data.
* Model Evaluation: The model is evaluated using a confusion matrix, accuracy score, and classification report.
## Key Findings
* Education Levels: The majority of employees have a Bachelor's degree, followed by a smaller percentage with Master's degrees, and the smallest percentage with PhDs.
* Joining Year Trends: There is consistent growth in the number of employees joining each year, with a peak in 2017.
* Gender Disparity: Male employees significantly outnumber female employees across all payment tiers, particularly in higher tiers.
* Bench Status: More male employees have been benched compared to female employees.
* Experience in Current Domain: The distribution of experience in the current domain varies across genders and payment tiers.
##Conclusion<br>
This project provides valuable insights into the employee demographics, education levels, payment tiers, and other factors. The analysis highlights potential disparities and trends that can inform decision-making and policy development within the company.


