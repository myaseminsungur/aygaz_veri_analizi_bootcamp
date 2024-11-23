# Medical Appointment No-Shows Analysis

## Dataset Overview
- **Size**: 110,527 medical appointments
- **Time Period**: 2016
- **Location**: Brazil
- **Target Variable**: No-show status
- **Features**: 14 columns including patient demographics and medical conditions

### Key Features
- Patient demographics (age, gender)
- Health conditions (hypertension, diabetes, alcoholism, handicap)
- Appointment details (scheduled day, appointment day, SMS reminder)
- Social welfare indicator (scholarship)

## Libraries Used
- **pandas**: Data manipulation and analysis
- **numpy**: Numerical operations
- **matplotlib**: Basic plotting
- **seaborn**: Statistical data visualization
- **scikit-learn**: Data preprocessing

## Analysis Performed

### 1. Data Preprocessing
- Missing value analysis and imputation
- Feature engineering (age groups, lead time)
- Data type conversions
- Outlier detection

### 2. Exploratory Data Analysis
- Distribution analysis of numerical variables
- Categorical variable analysis
- Correlation analysis
- Health conditions analysis

### 3. Statistical Analysis
- Age group distributions
- Gender-based health patterns
- No-show rates across different categories
- SMS effectiveness analysis

### 4. Multivariate Analysis
- Health conditions and SMS impact
- Age groups and appointment attendance
- Gender and scholarship interactions
- Combined health conditions analysis

## Business Problem
Predicting patient no-shows to help healthcare facilities optimize appointment scheduling and resource allocation.

## Proposed Solution
CatBoost classifier for predicting no-shows, leveraging its automatic handling of categorical variables and minimal preprocessing requirements.

## Author
MÜNEVVER YASEMİN SUNGUR

## Last Updated
23.11.2024
