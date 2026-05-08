# Viral-Content-Predictor-CS210-Final-Project
Viral Content Predictor that predicts whether social media content will go viral based on social media engagement patterns and measurable engagement metrics. 

## Dataset
[Kaggle Viral Social Media Trends Dataset](https://www.kaggle.com/datasets/atharvasoundankar/viral-social-media-trends-and-engagement-analysis)
-----------------------------------------------------------------------------------------
## Methods
- Data cleaning (Pandas)
- Feature engineering (engagement score, rate)
- Models: Logistic Regression, Random Forest 
----------------------------------------------------------------------------------------
## Goal
Help creators understand what drives virality across platforms like TikTok, Instagram, and YouTube.

-----------------------------------------------------------------------------------------
## How to Run the Project: 

### Requirements
- Python 3.10 +
- Jupyter Notebook/ VS Code

## Setup Steps

**1. Clone the repository**
```bash
git clone <YOUR_LINK>
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

## Run the Project

**1. Open the notebook**
```bash
jupyter notebook
```

**2. Open**
```
Viral_Content_Predictor.ipynb
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

## Important Notes: 
- Dataset must be in the same folder as notebook:
  Cleaned_Viral_Social_Media_Trends.csv
-----------------------------------------------------------------------------------------
## Authors
Shreya Bhatlapenumarti, Dhrithi Venkatesh
