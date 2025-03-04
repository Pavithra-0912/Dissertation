#  Dissertation: Understanding the Drivers of Healthy Life Expectancy in Wales

##  Introduction

Welcome to the repository containing the source code, datasets, and analysis used in my MSc dissertation project, **Understanding the Drivers of Healthy Life Expectancy in Wales**. This study investigates **socio-demographic, behavioral, and health-related determinants** affecting self-reported health outcomes in Wales. 

Using data from the **National Survey for Wales (NSW) (2021–2023)**, this research applies **logistic regression models** to identify key factors influencing health disparities.

---

##  Features

This project includes:

- **Comprehensive Analysis**: Utilizing data from **20,000+ respondents** from the National Survey for Wales.
- **Advanced Statistical Modeling**: Logistic regression models to examine the influence of socio-demographic and health-related variables.
- **Health Disparities Investigation**: Analyzing the impact of **income, age, lifestyle behaviors**, and **chronic conditions** on self-reported health.
- **Model Performance Visualization**: Using **Forest Plots** and **ROC Curves** to evaluate predictive accuracy.
- **Comparative Insights**: Contrasting findings with similar research conducted in **England**.

---

##  Installation & Setup

### **Prerequisites**
Ensure the following software and libraries are installed:

- **R (v4.0 or later)**
- **RStudio (recommended)**
- Required R packages:
  - `dplyr`
  - `haven`
  - `ggplot2`
  - `broom`
  - `gridExtra`
  - `gtable`
  - `stringr`

### **Steps to Run the Project**

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name
2. **Install Required Packages (in RStudio):**
   ```bash
   install.packages(c("dplyr", "haven", "ggplot2", "broom", "gridExtra", "gtable", "stringr"))
3. **Load the Dataset:**
   ```bash
   data <- read_dta("data/nsw_2021-23_anonymised_respondent_file.dta")
4. **Run the Analysis:**
   ```bash
   Open analysis_script.R in RStudio.
   Execute the script to generate results.

**Data Analysis Workflow**
This project follows a structured workflow:

### **1. Data Preparation**
- Data cleaning and preprocessing.
- Recoding categorical variables for analysis.
### **2. Exploratory Data Analysis (EDA)**
- Descriptive statistics for socio-demographic and health-related variables.
- Visualizations to identify trends and patterns.
### **3. Logistic Regression Modeling**
- Predicting self-reported health using:
- Socio-demographic factors (age, sex, income, deprivation, education).
- Behavioral factors (smoking, alcohol consumption, physical activity).
- Chronic health conditions (musculoskeletal, mental health disorders).
- Evaluating model performance and significance.
### **4. Model Performance Evaluation**
- Odds Ratios & Confidence Intervals: Assessing the impact of independent variables.
- Forest Plots: Visualizing key health determinants.
- ROC Curves: Evaluating predictive performance.
## Findings

The study identifies critical socio-demographic, behavioral, and health-related factors influencing **Healthy Life Expectancy (HLE)** in Wales. Using data from the **National Survey for Wales (2021-2023)**, key findings include:

1. **Major Determinants of Self-Reported Health**:
   - **Age (65+)**: Older individuals are significantly more likely to report poor health.
   - **Body Mass Index (Obesity)**: Strongly associated with negative health outcomes.
   - **Smoking & Alcohol Consumption**: Current smokers and high-risk drinkers report lower health ratings.
   - **Income & Socioeconomic Status**: Individuals in the **lowest quintile** are twice as likely to report poor health compared to those in the **highest income groups**.
   - **Chronic Conditions**:
     - **Musculoskeletal disorders**: One of the strongest predictors of poor health.
     - **Mental Health Conditions**: Anxiety and depression substantially impact self-reported well-being.
     - **Neurological & Cardiovascular Diseases**: Highly associated with negative health outcomes.

2. **Regional & Socioeconomic Disparities**:
   - Individuals in **rural areas** and **low-income regions** experience significantly poorer health.
   - **Wales vs. England**: While similar health determinants exist, **Wales has higher rates of chronic conditions**, particularly in former industrial areas.

3. **Health Behaviors & Preventable Risks**:
   - **Smoking and Physical Inactivity** significantly increase the risk of poor health.
   - **Higher well-being scores** correlate with a significantly lower likelihood of self-reported poor health.

4. **Predictive Model Performance**:
   - **Logistic Regression Analysis** identified the most significant predictors.
   - **Forest Plots** visualize how different factors influence self-reported health.
   - **ROC Curves** show that the model accurately predicts individuals at risk of poor health.

5. **Policy Implications**:
   - **Smoking cessation programs**, **obesity interventions**, and **mental health services** are essential.
   - Addressing **income-related health disparities** should be a priority for policymakers.

---

## Future Work

While this study provides important insights, further research is needed to **enhance understanding of HLE determinants**. Recommended areas for future exploration include:

1. **Longitudinal Studies**:
   - This study uses cross-sectional data, limiting causal inference.
   - Future studies should **track individuals over time** to determine whether factors like **smoking or physical inactivity** directly lead to adverse health outcomes, or if deteriorating health causes unhealthy behaviors.

2. **Expanding the Scope of Health Determinants**:
   - Additional factors such as **nutrition, housing conditions, and healthcare accessibility** should be included in future research.
   - Investigating **urban vs. rural health inequalities** will provide deeper insights into geographic disparities.

3. **Assessment of Public Health Interventions**:
   - Evaluate the effectiveness of **smoking cessation programs**, **obesity reduction strategies**, and **mental health services**.
   - Conduct **randomized controlled trials (RCTs)** or **quasi-experimental studies** to determine which policies yield the best results.

4. **Integration of Advanced Statistical Techniques**:
   - Future studies should use **multilevel modeling** and **causal mediation analysis** to explore the complex interactions between socioeconomic status, behavior, and health.
   - **Machine learning models** could improve predictive accuracy.

5. **Comparative Studies Beyond Wales**:
   - Future research should analyze **regional disparities** by comparing Wales to other UK nations or **international contexts**.

---

This research highlights **significant health disparities in Wales** and emphasizes the need for **targeted public health interventions**. Future studies should adopt **long-term data tracking**, **expanded health determinants**, and **new analytical techniques** to refine our understanding of **Healthy Life Expectancy (HLE)**.

### Contact
#### Email: pavithrraa123@gmail.com
#### LinkedIn: www.linkedin.com/in/pavithra-vasudevan-b64ab7167


