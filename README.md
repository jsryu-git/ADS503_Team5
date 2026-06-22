# ADS503_Final  
Final project repository for USD MS_ADS503 Team 5  

### Installation  
To use this project, first clone the repo on your device using the commands below:  

`git init`  
`git clone https://github.com/jsryu-git/ADS503_Team5.git`  

### Partner(s)/Contributor(s)  
**Authors:**  
* [Mehson Delan](https://github.com/masondelan)  
* [Malik Tisani](https://github.com/mtisaniUSD)  
* [Vince Garcia](https://github.com/VinceGarcia11)  
* [Jun Sik Ryu](https://github.com/jsryu-git)  

### Project Overview  

Diabetes is one of the most prevalent chronic diseases in the United States and is associated with substantial long-term health complications and healthcare costs. Early identification of individuals at elevated risk can support preventative interventions and improve patient outcomes.
This project applies predictive analytics and machine learning techniques to identify diabetes status using demographic, behavioral, and health-related indicators collected through the Behavioral Risk Factor Surveillance System (BRFSS) survey.
Multiple supervised learning models were developed and compared to determine which modeling approach provides the strongest predictive performance while maintaining interpretability.


### Problem Statement  

Diabetes is one of the most common chronic health conditions and is associated with significant long term health complications. Early identification of individuals at risk can improve prevention and treatment outcomes. The goal of this project is to develop predictive models that classify diabetes status based on demographic, behavioral, and health related indicators.

### Goals  
•	Explore relationships between health indicators and diabetes status
•	Develop reproducible machine learning workflows in R
•	Compare multiple predictive modeling approaches
•	Evaluate model performance using cross-validation and independent testing
•	Identify influential predictors associated with diabetes risk
•	Recommend a final model based on predictive performance and interpretability

### Non-Goals  
* Providing medical diagnoses or treatment recommendations  
* Replacing professional healthcare expertise  
* Developing a production ready healthcare application  

### Data Sources  
Diabetes Health Indicators Dataset
•	Source: Kaggle
•	Dataset Link: https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset

### Variables
The dataset includes demographic, behavioral, and health-related characteristics such as:
•	Body Mass Index (BMI)
•	High Blood Pressure
•	High Cholesterol
•	Smoking Status
•	Physical Activity
•	General Health
•	Mental Health
•	Physical Health
•	Age
•	Income
•	Education

### Methods  
The project follows the predictive modeling framework presented in Applied Predictive Modeling (Kuhn & Johnson, 2013).

Exploratory Data Analysis
•	Data quality assessment
•	Missing value analysis
•	Outlier review
•	Class distribution analysis
•	Predictor-response exploration
•	Correlation analysis

Data Preparation
•	Feature engineering
•	Variable transformation
•	Standardization
•	Near-zero variance screening
•	Training/testing split

Predictive Modeling
The following models were evaluated:
1.	Logistic Regression
2.	Elastic Net
3.	Random Forest
4.	Gradient Boosting Machine (GBM)

Model Evaluation
Models were evaluated using:
•	ROC AUC
•	Accuracy
•	Sensitivity
•	Specificity
•	Balanced Accuracy
•	Cross-validation performance

### Repository Structure  
```text
ADS503_Team5/
│
├── Data/
│   ├── Raw Data/
│
├── EDA.qmd
├── Preprocessing_and_baseline_models.qmd
├── model_tuning.qmd
├── Final_Report_Team5.qmd
│
├── Presentation/
├── Figures/
│
└── README.md
```

### Technologies  
* R  
* PowerPoint  
* Word  
* Excel  
* GitHub
* ChatGPT 5.4  
* Google Gemini  

### References  

Centers for Disease Control and Prevention. (2024). Diabetes overview. https://www.cdc.gov/diabetes/
Kuhn, M., & Johnson, K. (2013). Applied predictive modeling. Springer.
Teboul, A. (2023). Diabetes Health Indicators Dataset. Kaggle. https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset

### Deliverables
Technical Report Presentation [https://youtu.be/kFCeR0yXadw]  
Technical Report Deliverable [https://github.com/jsryu-git/ADS503_Team5/blob/ec151892e75e04495e86e2d40e2b7561d7215e6e/Final_Project_Report-Team5_Full.qmd]  
Non-Technical Presentation [<video controls src="https://github.com/jsryu-git/ADS503_Team5/blob/ec151892e75e04495e86e2d40e2b7561d7215e6e/Nontechnical_Summary-Team5.mp4" title="ADD LINK"></video>]
