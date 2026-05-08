# Viral-Content-Predictor-CS210-Final-Project
## Project Overview

The Viral Content Predictor is a machine learning and data analytics project designed to predict whether social media content will become viral based on measurable engagement metrics. As the influence of platforms such as TikTok, Instagram, and YouTube, is increasing overtime, understanding virality has become crucial for digital marketing, business advertising, and content strategy.

This project analyzes social media engagement patterns using data preprocessing, exploratory data analysis, feature engineering, and machine learning classification models.

-----------------------------------------------------------------------------------------------------

## Objectives 
*  Clean and preprocess the social media engagement data
* Analyze all the engagement patterns and virality trends
* Engineer engagement-based features for prediction
* Build different classification models to predict viral content
* Evaluate model performance using machine learning metrics
* Visualize engagement behavior across different platforms

-----------------------------------------------------------------------------------------------------

## Dataset
[Kaggle Viral Social Media Trends Dataset](https://www.kaggle.com/datasets/atharvasoundankar/viral-social-media-trends-and-engagement-analysis)

### Dataset Features: Uses social media engagement metrics to determine a viral VS non-viral post
* Platform
* Views
* Likes
* Shares
* Comments
* Engagement Rate
* Post Date
* Viral Classification
-----------------------------------------------------------------------------------------------------

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
-----------------------------------------------------------------------------------------------------

## Methodology

### 1. Data Cleaning & Preprocessing

The dataset was cleaned by:

* Removing missing values
* Removing duplicate rows
* Standardizing column formats
* Validating engagement metrics
----
### 2. Feature Engineering

New engagement-based features were created, including:

* Engagement Score
* Engagement Rate
* Like-to-View Ratio
* Share-to-View Ratio
* Comment-to-View Ratio

These engineered features improved the predictive capabilities of the classification models.

----
### 3. Exploratory Data Analysis (EDA)

EDA was performed to identify engagement patterns and relationships between variables.

Visualizations included:

* Histograms
* Scatterplots
* Boxplots
* Correlation Heatmaps
* Platform Comparison Charts
----

### 4. Machine Learning Models

The following classification models were implemented:

* Logistic Regression
* Random Forest Classifier

The models were trained to predict whether a social media post would become viral based on engagement metrics.

-----------------------------------------------------------------------------------------------------

## Model Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Cross Validation
* Confusion Matrix

The evaluation process helped determine which model performed best for virality prediction.

-----------------------------------------------------------------------------------------------------

## Key Findings

* Likes were the strongest correlation with virality.
* Shares demonstrated a very moderate influence on viral prediction.
* Comments had a weaker predictive strength compared to likes and shares.
* Engagement-based ratios improved predictive performance more effectively than raw engagement metrics.
* Different social media platforms displayed unique engagement behaviors.

-----------------------------------------------------------------------------------------------------

## Project Structure

```bash
├── Viral_Content_Predictor-_Data_Management_Final Project.ipynb
├── Cleaned_Viral_Social_Media_Trends.csv
├── README.md
```

-----------------------------------------------------------------------------------------------------
## Methods
- Data cleaning (Pandas)
- Feature engineering (engagement score, rate)
- Models: Logistic Regression, Random Forest 
-----------------------------------------------------------------------------------------------------
## Goal
Help creators understand what drives virality across platforms like TikTok, Instagram, and YouTube.

-----------------------------------------------------------------------------------------------------
## Installation & Setup: 

### Requirements
- Python 3.10 +
- Jupyter Notebook/ VS Code

## Setup Steps

**1. Clone the repository**
```bash
git clone https://github.com/shreyabhatlap/Viral-Content-Predictor-CS210-Final-Project.git
```

**2. Go into the project folder**
```bash
cd Viral-Content-Predictor
```

**3. Create virtual environment**
```bash
python -m venv venv
```

**4. Activate environment**
```bash
# Mac/Linux
source venv/bin/activate

# Windows
venv\Scripts\activate
```

**5. Install dependencies**
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```
---

## How To Run the Project

**1. Open the notebook**
```bash
jupyter notebook
```

**2. Open**
```
Viral_Content_Predictor- Data Management Final.ipynb
```

**3. Run all cells from top → bottom OR click "Run All"**

---

## Expected Outputs
- Dataset loads: `(5000, 11)`
- After cleaning: `(3796, 10)`
- Model results for:
  - Instagram  
  - TikTok  
  - YouTube  

- Graphs:
  - EDA plots  
  - Correlation heatmap  
  - Feature importance  
  - ROC curves

## Running the Predictor: 
At the end of the notebook run: predict_viral(.....)
Example outputs: 
- High engagement --> VIRAL
- Low engagement --> Not Viral
-----------------------------------------------------------------------------------------------------

## Important Notes: 
- Dataset must be in the same folder as notebook:
  Cleaned_Viral_Social_Media_Trends.csv
-----------------------------------------------------------------------------------------
## Authors
Shreya Bhatlapenumarti, Dhrithi Venkatesh
