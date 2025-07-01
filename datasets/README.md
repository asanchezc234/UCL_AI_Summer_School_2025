# UCL AI Summer School 2025 - Datasets

This folder contains various datasets used throughout the UCL AI Summer School 2025 for learning and practicing machine learning techniques. Each dataset serves different educational purposes and covers various domains.

## 📊 Dataset Overview

| Dataset | Rows | Columns | Size | Domain | Purpose |
|---------|------|---------|------|--------|---------|
| `ai_adoption_dataset.csv` | 145,000 | 9 | Large | Technology/Business | AI adoption analysis |
| `datascience_salaries.csv` | 133,350 | 11 | Large | Employment/Finance | Salary prediction & analysis |
| `synthetic_loan_data.csv` | 9,000 | 14 | Small | Finance/Banking | Credit risk assessment |
| `synthetic_health_lifestyle_dataset.csv` | 7,510 | 13 | Small | Healthcare/Lifestyle | Health outcome prediction |
| `cleaned_data.csv` | 64,621 | 11 | Medium | Employment/Finance | Preprocessed version of datascience salaries data for ML |

---

## 🔍 Detailed Dataset Descriptions

### 1. AI Adoption Dataset (`ai_adoption_dataset.csv`)
**Size:** 145,000 rows × 9 columns  
**Domain:** Technology & Business Analytics

**Description:**
A comprehensive dataset tracking AI tool adoption across different countries, industries, and demographics. Contains data from 2023-2024 on various AI tools including ChatGPT, Midjourney, Bard, and Stable Diffusion.

**Features:**
- `country` - Country where adoption was measured
- `industry` - Industry sector (Technology, Healthcare, Education, etc.)
- `ai_tool` - Specific AI tool (ChatGPT, Midjourney, Bard, Stable Diffusion)
- `adoption_rate` - Percentage adoption rate (0-100)
- `daily_active_users` - Number of daily active users
- `year` - Year of measurement (2023-2024)
- `user_feedback` - User feedback text
- `age_group` - Age demographic (18-24, 25-34, 35-44, 45-54, 55+)
- `company_size` - Company size category (Startup, SME, Enterprise)

**Ideal for:**
- **Exploratory Data Analysis (EDA):** Understanding global AI adoption trends
- **Classification:** Predicting high vs. low adoption rates
- **Clustering:** Identifying market segments with similar adoption patterns
- **Text Analysis:** Analyzing user feedback sentiment
- **Time Series Analysis:** Tracking adoption growth over time
- **Geographic Analysis:** Mapping adoption by country and region

---

### 2. Data Science Salaries Dataset (`datascience_salaries.csv`)
**Size:** 133,350 rows × 11 columns  
**Domain:** Employment & Compensation

**Description:**
Comprehensive salary data for data science professionals worldwide. Contains information about job titles, experience levels, company characteristics, and compensation details for 2025.

**Features:**
- `work_year` - Year of employment (2025)
- `experience_level` - Experience level (EN=Entry, MI=Mid, SE=Senior, EX=Executive)
- `employment_type` - Employment type (FT=Full-time, PT=Part-time, CT=Contract, FL=Freelance)
- `job_title` - Specific job title (Data Scientist, Data Engineer, ML Engineer, etc.)
- `salary` - Salary in original currency
- `salary_currency` - Currency of salary (USD, EUR, GBP, etc.)
- `salary_in_usd` - Salary converted to USD
- `employee_residence` - Employee's country of residence
- `remote_ratio` - Percentage of remote work (0=No remote, 50=Partially remote, 100=Fully remote)
- `company_location` - Company's country location
- `company_size` - Company size (S=Small, M=Medium, L=Large)

**Ideal for:**
- **Regression Analysis:** Predicting salaries based on various factors
- **Feature Engineering:** Creating new variables from existing ones
- **Comparative Analysis:** Salary differences across countries, experience levels
- **Classification:** Categorizing salary ranges or employment types
- **Dimensionality Reduction:** Understanding key factors affecting compensation
- **Business Intelligence:** Market research for compensation benchmarking

---

### 3. Synthetic Loan Data (`synthetic_loan_data.csv`)
**Size:** 9,000 rows × 14 columns  
**Domain:** Financial Services & Credit Risk

**Description:**
Artificially generated loan application data simulating real-world banking scenarios. Perfect for learning credit risk assessment and binary classification problems without privacy concerns.

**Features:**
- `CustomerID` - Unique customer identifier
- `Name` - Customer name (synthetic)
- `Age` - Customer age
- `Gender` - Gender identity
- `MaritalStatus` - Marital status (Single, Married, Divorced, Widowed)
- `EducationLevel` - Education level (High School, Bachelor, Master, PhD, Other)
- `EmploymentStatus` - Employment status (Employed, Unemployed, Self-employed, Student, Retired)
- `AnnualIncome` - Annual income in currency units
- `LoanAmountRequested` - Requested loan amount
- `PurposeOfLoan` - Loan purpose (Personal, Home, Car, Education)
- `CreditScore` - Credit score (300-850 range)
- `ExistingLoansCount` - Number of existing loans
- `LatePaymentsLastYear` - Number of late payments in past year
- `LoanApproved` - Target variable (Yes/No)

**Ideal for:**
- **Binary Classification:** Predicting loan approval (Yes/No)
- **Feature Importance Analysis:** Understanding key factors in loan decisions
- **Imbalanced Learning:** Handling potential class imbalance in approvals
- **Risk Assessment:** Building credit scoring models
- **Ethical AI:** Exploring bias and fairness in lending decisions
- **Business Rules:** Creating interpretable decision criteria

---

### 4. Synthetic Health & Lifestyle Dataset (`synthetic_health_lifestyle_dataset.csv`)
**Size:** 7,510 rows × 13 columns  
**Domain:** Healthcare & Lifestyle Analytics

**Description:**
Synthetic health and lifestyle data capturing various health indicators, lifestyle choices, and wellness metrics. Designed for exploring relationships between lifestyle factors and health outcomes.

**Features:**
- `ID` - Unique individual identifier
- `Age` - Individual's age
- `Gender` - Gender identity (Male, Female, Other)
- `Height_cm` - Height in centimeters
- `Weight_kg` - Weight in kilograms
- `BMI` - Body Mass Index (calculated)
- `Smoker` - Smoking status (Yes/No)
- `Exercise_Freq` - Exercise frequency (None, 1-2 times/week, 3-5 times/week, Daily)
- `Diet_Quality` - Diet quality rating (Poor, Average, Good, Excellent)
- `Alcohol_Consumption` - Alcohol consumption level (None, Low, Moderate, High)
- `Chronic_Disease` - Presence of chronic disease (Yes/No)
- `Stress_Level` - Stress level (1-10 scale)
- `Sleep_Hours` - Average sleep hours per night

**Ideal for:**
- **Health Outcome Prediction:** Predicting chronic disease risk
- **Lifestyle Analysis:** Understanding relationships between lifestyle factors
- **Clustering:** Identifying lifestyle patterns and health profiles
- **Regression Analysis:** Predicting continuous health metrics (BMI, sleep, stress)
- **Feature Engineering:** Creating composite health scores
- **Public Health Research:** Exploring population health trends

---

### 5. Cleaned Data (`cleaned_data.csv`)
**Size:** 64,621 rows × 11 columns  
**Domain:** Employment & Compensation (Preprocessed)

**Description:**
This is a cleaned and preprocessed version of the data science salaries dataset. Missing values have been handled, outliers have been addressed, and the data is ready for machine learning applications.

**Features:**
Same as `datascience_salaries.csv` but with:
- Missing values imputed or removed
- Outliers handled appropriately
- Data types optimized
- Consistent formatting across all fields

**Ideal for:**
- **Machine Learning Model Training:** Ready-to-use clean data
- **Algorithm Comparison:** Testing different ML algorithms
- **Cross-validation:** Robust model evaluation
- **Feature Selection:** Identifying most important predictors
- **Hyperparameter Tuning:** Optimizing model performance
- **Production-ready Pipelines:** Demonstrating clean data workflows

---

## 🚀 Getting Started

### Loading Data in Python
```python
import pandas as pd

# Load any dataset
df = pd.read_csv('dataset_name.csv')

# Quick exploration
print(df.info())
print(df.describe())
print(df.head())
```
---

## 📚 Notebooks Using These Datasets

- **`introduction/demonstrations.ipynb`** - Basic data loading and exploration
- **`preprocessing_EDA/data_cleaning.ipynb`** - Data cleaning techniques
- **`preprocessing_EDA/exploratory_data_analysis.ipynb`** - EDA methods
- **`supervised_learning/regression_analysis.ipynb`** - Regression modeling
- **`unsupervised_learning/clustering_analysis.ipynb`** - Clustering techniques
- **`unsupervised_learning/dimensionality_reduction.ipynb`** - PCA and UMAP



---

*Last updated: July 2025*
*UCL AI Summer School 2025*
