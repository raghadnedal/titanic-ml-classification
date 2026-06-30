# Titanic EDA Project

This project is an Exploratory Data Analysis (EDA) on the Titanic dataset using Python.

## Project Goal

The goal of this project is to understand the Titanic dataset and analyze the factors that affected passenger survival.

## Questions

This project answers the following questions:

- How many passengers survived?
- What is the difference between male and female survival?
- Did passenger class affect survival?
- Did age affect survival?
- How many missing values are in the dataset?
- What is the distribution of Fare?

## Libraries Used

- NumPy
- Pandas
- Matplotlib

## Dataset

The dataset contains information about Titanic passengers, such as:

- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

## Data Cleaning

The dataset was cleaned by:

- Checking missing values
- Handling missing Age values
- Handling missing Embarked values
- Removing unnecessary columns
- Creating new useful columns such as FamilySize and AgeGroup

## Main Insights

- Most passengers did not survive.
- Female passengers had a much higher survival rate than male passengers.
- First-class passengers had the highest survival rate.
- Third-class passengers had the lowest survival rate.
- Fare distribution is right-skewed.
- Age and Cabin contain missing values.

## Files

- Titanic_EDA.ipynb
- Titanic-Dataset.csv
- README.md
