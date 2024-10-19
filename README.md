<a name="readme-top"></a>
<br />
<div align="center">

  # Depression Data Analysis - Mental-Health Predictor
### Machine Learning and Mental-Health Predictor

  </a>


</div>

## Project Overview

This project focuses on analyzing a dataset related to personal and lifestyle attributes to explore potential risk factors for depression. The aim is to understand how various factors such as age, lifestyle habits, and medical history may contribute to mental health outcomes. By analyzing these data points, we hope to identify patterns and correlations that could inform future research or intervention strategies.

This project will attempt to find a solution to the following:

Identify Risk Factors: Determine the most common attributes associated with depression.
Correlate Lifestyle Choices: Explore how lifestyle choices (e.g., smoking, physical activity, diet) relate to mental health.
Predictive Modeling: Develop models that can predict the likelihood of depression based on personal and lifestyle attributes.

## Table of Contents
  
  <ol>
    <li><a href="#motivation">Project Motivation</a></li>
    <li><a href="#opportunity">The opportunity</a></li>
    <li><a href="#keytakeaway">Key Takeaway</a></li>
    <li><a href="#data">The Data</a></li>
    <li><a href="#dict">Data Dictionary</a></li>
    <li><a href="#roadmap">Project Roadmap</a></li>
    <li><a href="#progression">Project progression</a></li>
    <li><a href="#datasource">Data Source</a></li>
    <li><a href="#repo">Repository</a></li>
    <li><a href="#learnings">Learnings</a></li>
    <li><a href="#conclusions">Conclusions</a></li>
    <li><a href="#next">Next Steps</a></li>
  </ol>
</details>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<h2 id="motivation"> Project Motivation </h2>
The motivation for this project stems from the growing recognition of mental health as a critical societal issue, and trying to understand how various factors such as age, lifestyle habits, and medical history may contribute to mental health outcomes. 

<h2 id="opportunity"> The opportunity </h2>

The analysis of depression data offers a significant opportunity to improve early detection and interventions for mental health issues. Mental illness, particularly depression, is an increasingly common challenge faced by many individuals across various socioeconomic backgrounds. However, the early detection and personalized intervention mechanisms for at-risk individuals remain limited. By leveraging machine learning and data science techniques, we can address this gap and create impactful solutions.

In this project, the opportunity lies in:

- **Early Detection**: By analyzing lifestyle, socioeconomic, and medical factors, the project aims to identify patterns that predict mental health issues before they become critical.
  
- **Improving Access to Support**: The model developed from this analysis could be integrated into healthcare systems or public health platforms to offer real-time risk assessments, ensuring timely intervention and guidance for individuals showing signs of mental distress.

- **Societal Impact**: Early intervention can lead to improved well-being, reduced economic burden from untreated mental health issues, and better mental health outcomes at a population level. The insights gained from this analysis could guide public health policies and mental health awareness programs.

This project presents a unique opportunity to contribute to a crucial area in public health, with the potential to make a meaningful difference in the lives of those struggling with mental illness.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<h2 id="keytakeaway"> Key takeaways </h2>

- **Predictive Potential**: By analyzing socioeconomic, lifestyle, and medical data, this project demonstrates the potential of machine learning to predict mental health issues, providing valuable insights for early detection and intervention.

- **Scalability**: The approach used can be scaled to analyze large datasets, making it feasible for healthcare systems and public health organizations to monitor mental health trends and identify at-risk populations on a much larger scale.

- **Timely Interventions**: The model offers the opportunity to implement real-time mental health assessments, enabling organizations to take preventive measures and provide support before mental health issues escalate.

- **Nuanced Understanding**: Beyond the binary outcome of mental illness prediction, this analysis sheds light on the deeper relationships between factors such as income, age, and lifestyle, offering a more comprehensive understanding of mental health determinants.

- **Data-Driven Decision Making**: This project highlights the power of data-driven insights in public health, helping to inform mental health policy, resource allocation, and targeted interventions based on quantifiable evidence.

- **Ethical Implications**: The sensitive nature of mental health data necessitates careful consideration of privacy and ethical concerns. Ensuring fairness, addressing biases, and maintaining transparency in predictive models are critical to responsible mental health interventions.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<h2 id="data"> The Data</h2>

The dataset used for this project comes from the [Depression Dataset on Kaggle] (https://www.kaggle.com/datasets/anthonytherrien/depression-dataset/data). This comprehensive dataset focuses on socioeconomic, lifestyle, and medical factors related to mental health, particularly depression. It provides valuable insights for building machine learning models that predict the likelihood of mental illness.

This dataset contains 413,768 entries, each representing an individual's demographic information, lifestyle choices, and mental health history. The dataset includes features such as age, income, smoking status, physical activity level, history of mental illness, and family history of depression.

### Key Features:
- **Age**: The age of the respondent.
- **Income**: Standardized income data for the individual.
- **Smoking Status**: Whether the respondent is a current, former, or non-smoker.
- **Physical Activity Level**: Indicates whether the respondent has a sedentary, moderate, or active lifestyle.
- **Employment Status**: Reflects whether the individual is employed or unemployed.
- **History of Mental Illness**: Indicates whether the individual has a history of mental illness. (TARGET)
- **Family History of Depression**: Information about the presence of depression in the respondent's family.
- **Chronic Medical Conditions**: Whether the individual suffers from chronic health conditions.
- **Alcohol Consumption & Dietary Habits**: Data on the individual's alcohol consumption and dietary preferences.

### Acknowledgments:
This dataset was compiled and cleaned by [Anthony Therrien](https://www.kaggle.com/anthonytherrien) from various publicly available sources. It provides a rich resource for understanding how various factors contribute to mental health outcomes, particularly the prevalence of depression.

---

Let me know if you need any adjustments to this!

<h2 id="dict"> Data Dictionary</h2>

<table>
  <tr>
    <th style="text-align: left; background: lightgrey">Column Name</th>
    <th style="text-align: left; background: lightgrey">Description</th>
  </tr>
  <tr>
    <td>Name</td>
    <td>The name of the individual (anonymized for privacy).</td>
  </tr>
  <tr>
    <td>Age</td>
    <td>The age of the individual (in years).</td>
  </tr>
  <tr>
    <td>Marital Status</td>
    <td>The marital status (e.g., Single, Married, Divorced, Widowed).</td>
  </tr>
  <tr>
    <td>Education Level</td>
    <td>The highest level of education attained (e.g., High School, Bachelor's, Master's).</td>
  </tr>
  <tr>
    <td>Number of Children</td>
    <td>The number of children the individual has.</td>
  </tr>
  <tr>
    <td>Smoking Status</td>
    <td>Indicates whether the individual is a smoker or non-smoker.</td>
  </tr>
  <tr>
    <td>Physical Activity Level</td>
    <td>The level of physical activity (e.g., Sedentary, Moderate, Active).</td>
  </tr>
  <tr>
    <td>Employment Status</td>
    <td>Employment status (e.g., Employed, Unemployed, Retired).</td>
  </tr>
  <tr>
    <td>Income</td>
    <td>Annual income of the individual (in USD).</td>
  </tr>
  <tr>
    <td>Alcohol Consumption</td>
    <td>Level of alcohol consumption (e.g., Low, Moderate, High).</td>
  </tr>
  <tr>
    <td>Dietary Habits</td>
    <td>Indicates the dietary habits (e.g., Healthy, Moderate, Unhealthy).</td>
  </tr>
  <tr>
    <td>Sleep Patterns</td>
    <td>Quality of sleep (e.g., Good, Fair, Poor).</td>
  </tr>
  <tr>
    <td>History of Mental Illness</td>
    <td>Whether the individual has a history of mental health issues (Yes/No).</td>
  </tr>
  <tr>
    <td>History of Substance Abuse</td>
    <td>Indicates if there is a history of substance abuse (Yes/No).</td>
  </tr>
  <tr>
    <td>Family History of Depression</td>
    <td>Indicates if there is a family history of depression (Yes/No).</td>
  </tr>
  <tr>
    <td>Chronic Medical Conditions</td>
    <td>Whether the individual has chronic medical conditions (Yes/No).</td>
  </tr>
</table>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<h2 id="roadmap"> Project Roadmap </h2>
<div style="display: flex; align-items: center;">

  <div style="margin-right: 20px;">
    <h2>1. Data Collection</h2>
    <ul>
      <li><strong>Task:</strong> Source the dataset from the Depression Dataset on Kaggle, containing information on demographic, socioeconomic, and lifestyle factors related to mental health.</li>
      <li><strong>Objective:</strong> Gather comprehensive data that captures multiple aspects influencing mental health to build a robust predictive model.</li>
    </ul>
  </div>
  
  <div style="margin-right: 20px;">
    <h2>2. Data Cleaning</h2>
    <ul>
      <li><strong>Task:</strong> Handle missing values, encode categorical variables, scale numeric features like income, and ensure that all data is prepared for machine learning models.</li>
      <li><strong>Objective:</strong> Ensure the data is clean, consistent, and ready for analysis, with no outliers or missing values to affect the model performance.</li>
    </ul>
  </div>

  <div style="margin-right: 20px;">
    <h2>3. Exploratory Data Analysis (EDA)</h2>
    <ul>
      <li><strong>Task:</strong> Conduct an in-depth exploration of the data to identify relationships, patterns, and trends. This includes examining age, income, and lifestyle factors against mental health outcomes.</li>
      <li><strong>Objective:</strong> Gain insights into how different variables interact with mental illness, guiding feature selection and model-building strategies.</li>
    </ul>
  </div>

</div>

<div style="display: flex; align-items: center;">

  <div style="margin-right: 20px;">
    <h2>4. Data Splitting/Model Selection</h2>
    <ul>
      <li><strong>Task:</strong> Split the data into training and test sets. Experiment with machine learning models like Logistic Regression and Random Forest for classification.</li>
      <li><strong>Objective:</strong> Choose the best model that effectively predicts the likelihood of mental illness based on the features provided.</li>
    </ul>
  </div>
  
  <div style="margin-right: 20px;">
    <h2>5. Model Evaluation</h2>
    <ul>
      <li><strong>Task:</strong> Evaluate the models using key metrics like accuracy, precision, recall, and F1-score. Use cross-validation to assess model generalization.</li>
      <li><strong>Objective:</strong> Identify the most effective model, refining hyperparameters for optimal performance.</li>
    </ul>
  </div>
  
  <div style="margin-right: 20px;">
    <h2>6. Feature Engineering and Advanced Modeling</h2>
    <ul>
      <li><strong>Task:</strong> After initial evaluations, refine features by engineering new ones or removing redundant variables. Explore advanced models like XGBoost or Neural Networks to improve predictions.</li>
      <li><strong>Objective:</strong> Boost model accuracy and robustness, ensuring it generalizes well to unseen data and provides actionable insights.</li>
    </ul>
  </div>


</div>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<h2 id="progression"> Project Progression </h2>

1. **Initial Project Direction**:
   - The project initially began by exploring text data related to mental health posts from various online platforms. The goal was to perform sentiment analysis and identify correlations with mental health issues, intending to build a predictive model.
   - **Challenge**: Unfortunately, the dataset lacked a clear target variable (such as a mental health diagnosis or outcome), which limited the ability to develop a supervised learning model.
   - **Decision**: Given this limitation, we decided to shift our focus to a more structured dataset that includes relevant features and target variables.

2. **Dataset Shift**:
   - After assessing the challenges with the initial text data, we decided to pivot to the [Depression Dataset on Kaggle](https://www.kaggle.com/datasets/anthonytherrien/depression-dataset/data).
   - This dataset provides detailed information about individuals' demographic, lifestyle, and medical factors that are related to mental health outcomes, especially depression. It includes features such as age, income, employment status, and history of mental illness, which are essential for building a supervised learning model.

3. **Current Progress**: PENDING
   - **Data Cleaning**: We have successfully cleaned the dataset, handled missing values, encoded categorical features, and standardized numerical columns such as income.
   - **Exploratory Data Analysis (EDA)**: Extensive EDA was performed to uncover key insights regarding the relationships between variables such as income, age, and lifestyle habits, and how they relate to the likelihood of mental illness.
   - **Modeling**: Logistic Regression and Random Forest models have been implemented, with hyperparameter tuning to optimize the models. We have evaluated these models using metrics like accuracy, precision, recall, and F1-score.
   - **Model Tuning**: We also experimented with hyperparameters such as regularization strength, solver types, and penalties for Logistic Regression to improve performance. PENDING

4. **What's Missing**:
   - **Advanced Modeling**: While initial models have been built, more advanced techniques (e.g., XGBoost, Neural Networks) could be explored to enhance predictive accuracy.
   - **Feature Engineering**: There is an opportunity to refine feature engineering, either by generating new features from existing data or removing those that add redundancy or noise.
   - **Deployment and Impact**: Next steps include deploying the final model in a real-world setting, such as creating a dashboard to monitor mental health risk or developing a web application for real-time predictions.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<h2 id="datasource"> Data Source </h2>
The dataset integrates information from the following Kaggle dataset:

[Depression Dataset on Kaggle](https://www.kaggle.com/datasets/anthonytherrien/depression-dataset/data). 
 
<p align="right">(<a href="#readme-top">back to top</a>)</p>
<h2 id="repo"> Repository </h2>

* `data` 
    - contains link to copy of the dataset (stored in a publicly accessible cloud storage)
    - saved copy of aggregated / processed data as long as those are not too large (> 10 MB)

* `model`
    - `joblib` dump of final model(s)

* `notebooks`
    - contains all final notebooks involved in the project

* `docs`
    - contains final report, presentations which summarize the project

* `references`
    - contains papers / tutorials used in the project

* `src`
    - Contains the project source code (refactored from the notebooks)

* `.gitignore`
    - Part of Git, includes files and folders to be ignored by Git version control

* `conda.yml`
    - Conda environment specification

* `README.md`
    - Project landing page (this page)

* `LICENSE`
    - Project license
<p align="right">(<a href="#readme-top">back to top</a>)</p>
<h2 id="learnings"> Learnings </h2>

Write here ...

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<h2 id="conclusions"> Conclusions </h2>

Write here...


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<h2 id="next"> Next Steps </h2>

**What's Missing**:
   - **Advanced Modeling**: While initial models have been built, more advanced techniques (e.g., XGBoost, Neural Networks) could be explored to enhance predictive accuracy.
   - **Feature Engineering**: There is an opportunity to refine feature engineering, either by generating new features from existing data or removing those that add redundancy or noise.
   - **Deployment and Impact**: Next steps include deploying the final model in a real-world setting, such as creating a dashboard to monitor mental health risk or developing a web application for real-time predictions.

<p align="right">(<a href="#readme-top">back to top</a>)</p>





