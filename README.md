#  House Price Prediction using Linear Regression

##  Objective

The goal of this project is to develop a **Linear Regression model** to predict house prices based on features such as area, number of bedrooms, presence of amenities, and more. This project demonstrates the complete machine learning pipeline—from data preprocessing to evaluation—on a real-world dataset.

---

##  Dataset

The dataset used is `Housing.csv`, which includes the following types of features:
- Numerical: `area`, `bedrooms`, `bathrooms`, `stories`, `parking`
- Categorical: `mainroad`, `guestroom`, `basement`, `furnishingstatus`, etc.
- Target: `price` (the house price in INR)

---

##  Steps Performed

### 1. **Data Loading & Exploration**
- Loaded the dataset using `pandas`
- Displayed sample records and checked for null values
- Explored data types and statistical summaries

### 2. **Data Preprocessing**
- Converted categorical variables into numeric using one-hot encoding
- Checked data integrity and cleaned where necessary

### 3. **Feature Selection & Splitting**
- Selected independent variables (`X`) and dependent variable (`y`)
- Split the data into training and test sets (80/20 ratio)

### 4. **Model Building**
- Trained a **Linear Regression** model using Scikit-Learn

### 5. **Model Evaluation**
- Evaluated the model using:
  - **Mean Squared Error (MSE)**: `1,754,318,687,330.66`
  - **R² Score**: To measure accuracy and variance explained
- Visualized predictions vs actual house prices using scatter plot

---

## Tools & Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - `pandas`, `numpy` – Data manipulation
  - `matplotlib`, `seaborn` – Data visualization
  - `scikit-learn` – Machine Learning (Linear Regression, evaluation)
- **IDE**: Google Colab / Jupyter Notebook

---

## Outcome

- The linear regression model provides a solid baseline for predicting house prices.
- The model captures general trends well, although performance could be improved by:
  - Applying **Polynomial Regression**
  - Performing **Feature Engineering**
  - Trying **Regularization** methods

---

##  How to Run

1. Clone this repository.
2. Open the `Housing_Price_Prediction_(Linear_Regression).ipynb` notebook in Google Colab or Jupyter.
3. Run each cell step-by-step to reproduce the results.

---

##  Acknowledgements

This project is part of my journey into Data Science and Machine Learning.  
The dataset is used for educational purposes to demonstrate regression modeling techniques.

---

## 📬 Contact

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/priyal-seth-2493302a2/) or raise issues in this repo for collaboration or feedback.

