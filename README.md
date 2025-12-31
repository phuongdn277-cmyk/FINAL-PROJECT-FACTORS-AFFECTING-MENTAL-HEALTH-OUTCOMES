# FINAL PROJECT: FACTORS AFFECTING MENTAL HEALTH OUTCOMES
This is the final project of the Data Analyst course. It is about analyzing Global Mental Health data to draw relevant conclusions.
# Mental Health Global 2025 Analysis

## Project Goals
- Analyze global mental health data to identify factors associated with mental health outcomes.  
- Examine how demographic, clinical, lifestyle, and treatment-related factors affect mental health outcomes.  
- Provide actionable insights and recommendations to improve mental health care and well-being.  

---

## Data Sources
- **Dataset:** Mental Health Global 2025 (https://github.com/phuongdn277-cmyk/FINAL-PROJECT-FACTORS-AFFECTING-MENTAL-HEALTH-OUTCOMES/blob/main/data/Global_Mental_Health_Dataset_2025.csv)
- **Source:** https://www.kaggle.com/datasets/ankushnarwade/global-mental-health-dataset-2025/data.
- **Description:**
  + The dataset contains 2500 records and 15 columns
  + The last updated time of the dataset: 18/12/2025
  + Each record represents an anonymous patient
- **Structure:**
  + `Patient_ID:` Unique anonymized identifier assigned to each patient record
  + `Age:` Age of the individual in years (18 to 80)
  + `Gender:` Gender of the patient
  + `Country:` Country of residence of the patient
  + `Depression_Score:` Depression severity score based on the PHQ-9 scale (0–27)
  + `Anxiety_Score:` Anxiety severity score based on the GAD-7 scale (0–21)
  + `Stress_Level:` Self-reported stress level (Low, Medium, High, Severe)
  + `Sleep_Hours :` Average number of hours slept per night
  + `Physical_Activity:` Level of regular physical activity (None, Low, Moderate, High)
  + `Chronic_Illness:` Indicates presence of any ongoing physical health condition (Yes/No)
  + `Mental_Health_History:` Whether the patient has a prior mental health diagnosis (Yes/No)
  + `Treatment:` Type of mental health treatment received (None, Therapy, Medication, Both)
  + `Days_of_Treatment:` Total number of days the patient has undergone treatment
  + `Outcome:` Overall treatment outcome or mental health status (Poor, Fair, Good, Excellent)
  + `Work_Status:` Current employment or academic status of the patient
- **Data Overview:**

|      | Patient_ID   |   Age | Gender   | Country       |   Depression_Score |   Anxiety_Score | Stress_Level   |   Sleep_Hours | Physical_Activity   | Chronic_Illness   | Mental_Health_History   | Treatment   |   Days_of_Treatment | Outcome   | Work_Status   |
|-----:|:-------------|------:|:---------|:--------------|-------------------:|----------------:|:---------------|--------------:|:--------------------|:------------------|:------------------------|:------------|--------------------:|:----------|:--------------|
| 2380 | MH2381       |    63 | Male     | Germany       |                 20 |              19 | Medium         |           6.4 | Moderate            | No                | No                      | Therapy     |                 344 | Fair      | Employed      |
| 2062 | MH2063       |    52 | Male     | Brazil        |                 19 |              15 | Severe         |           7.5 | Moderate            | No                | Yes                     | Medication  |                 182 | Poor      | Retired       |
|  511 | MH0512       |    19 | Male     | Australia     |                 15 |               2 | Low            |           8.4 | Low                 | No                | Yes                     | Both        |                 284 | Excellent | Student       |
|    3 | MH0004       |    32 | Female   | Australia     |                 19 |              16 | Low            |          10   | Moderate            | No                | Yes                     | Both        |                 254 | Excellent | Employed      |
| 1346 | MH1347       |    19 | Female   | United States |                  0 |              21 | Medium         |          10.5 | Moderate            | No                | Yes  | Unknown     |                 264 | Good      | Student       |

---

## Tools and Technologies Applied
- **Programming Language:** Python 3.x  
- **Libraries:** pandas, numpy, matplotlib, seaborn, statsmodels, scikit-learn  
- **Analysis Techniques:**  
  - Data cleaning & preprocessing  
  - Exploratory Data Analysis (EDA)  
  - Correlation analysis  
  - Visualization (Bar Plots, Box Plots, Heatmaps)  
  - Ordinal Logistic Regression  

---




