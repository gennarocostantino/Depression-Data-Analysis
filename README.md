<a name="readme-top"></a>
<br />
<div align="center">

  # Mental-Health Predictor
### A Data-Driven Approach to Boost Mental Health Outcomes and Build Trust in Support Systems

  </a>


</div>

### Depression Data Analysis

**Project Overview:**

This project analyzes a dataset of personal, lifestyle, and family-related attributes to explore potential risk factors for depression. The objective is to identify key factors, such as family dynamics, sociodemographic characteristics, and lifestyle habits, that may influence mental health outcomes. The goal is to create a more comprehensive understanding of how these variables interact and contribute to an individual’s mental well-being, which can help guide future research or inform targeted interventions.

**Approach and Methodology:**

We began by conducting exploratory data analysis (EDA) to investigate the relationships between family/personal health, personal burden, and individual mental health. While While personal burden is often discussed in terms of its economic and emotional effects, its connection to mental health outcomes has not been fully explored. Through EDA, we identified significant patterns and correlations within the data, shedding light on how family/personal-related stressors.

**Stress Indicator Creation:**

A key part of the analysis was the creation of a stress indicator based on various factors, including income, social support, personal burden, family/personal health, and employment status. These variables were selected based on their potential influence on stress and mental health, with the indicator being normalized to ensure comparability across individuals. This stress indicator was then used to further analyze the dataset and uncover how these factors interact with mental health outcomes.

**Hypothesis Testing and Statistical Analysis:**

To validate the stress indicator, we performed hypothesis tests and correlation analysis. We found significant correlations between the stress indicator and key variables, such as income (negative correlation), social support (personal correlation), personal burden (positive correlation), and family/personal health (positive correlation). ANOVA tests for education levels also indicated the relevance of sociodemographic factors in determining stress levels.

**Predictive Modeling:**

We utilized machine learning models, including decision trees and linear regression, to predict stress levels and assess the importance and weight of each feature. The models provided valuable insights into the most significant predictors of stress, including personal burden, social support, and family/personal health. These findings suggest that addressing family-related stressors and improving social support could play a critical role in alleviating stress and enhancing mental health outcomes.

**Unsupervised Learning (K-Means Clustering):** 

To gain deeper insights into the dataset and group individuals with similar characteristics, we applied unsupervised learning techniques, specifically K-means clustering. By segmenting the population into distinct clusters, we were able to identify groups with similar stress levels, personal burdens, and other relevant features. Our goal with clustering is to group individuals based on similar stress profiles to better understand the different stress experiences and tailor support accordingly.

**Conclusion and Insights:**

This analysis highlights how different people stress levels are influenced by factors such as income, personal burden, social support, and family health. By grouping people into distinct clusters, we identified patterns that can help target interventions to reduce stress and improve overall well-being. 
The actionable insights, including wellness programs, flexible work arrangements, and improved support systems, can be applied across various employee groups to create a healthier, more productive workforce.


### Key Objectives

- **Understand Mental Health Drivers**: Investigate the relationship between personal, lifestyle, and family-related factors, such as income, social support, family health, and history of mental illness, and their impact on mental health.
- **Predictive Modeling**: Develop predictive models to assess the likelihood of mental health challenges, particularly focusing on depression, based on a range of demographic and lifestyle attributes.
- **Segmentation through Clustering**: Use unsupervised learning techniques like K-Means clustering to group individuals with similar characteristics, allowing for more targeted insights and actionable recommendations for mental health interventions.
- **Actionable Insights**: Provide actionable insights for companies and organizations to improve employee well-being and mental health, focusing on work-life balance, stress reduction, and support systems.
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
    <li><a href="#conclusions">Conclusions and Next Steps</a></li>
   
  </ol>
</details>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<h2 id="motivation"> Project Motivation </h2>
One of the key actionable business insights from this project is understanding how different factors—such as family, personal responsibilities, financial strain, and personal health—contribute to stress levels among employees. To better understand the diverse experiences of employees, we used clustering techniques to group individuals facing similar stress-related challenges. These clusters help us identify patterns in the data and understand how different factors, like family responsibilities or financial strain, influence stress levels.


<h2 id="opportunity"> The opportunity </h2>

The analysis of depression data offers a significant opportunity to improve early detection and interventions for mental health issues. Mental illness, particularly depression, is an increasingly common challenge faced by many individuals across various socioeconomic backgrounds. However, the early detection and personalized intervention mechanisms for at-risk individuals remain limited. By leveraging machine learning and data science techniques, we can address this gap and create impactful solutions.

In this project, the opportunity lies in:

- **Early Detection**: By analyzing lifestyle, socioeconomic, and medical factors, the project aims to identify patterns that predict mental health issues before they become critical.
  
- **Improving Access to Support**: The model developed from this analysis could be integrated into healthcare systems or public health platforms to offer real-time risk assessments, ensuring timely intervention and guidance for individuals showing signs of mental distress.

- **Societal Impact**: Early intervention can lead to improved well-being, reduced economic burden from untreated mental health issues, and better mental health outcomes at a population level. The insights gained from this analysis could guide public health policies and mental health awareness programs.

The goal is to provide organizations with insights that can help them better support employees. For instance, employees experiencing high family burdens may benefit from financial assistance, flexible work arrangements, and mental health resources. By understanding these stress factors, companies can implement targeted interventions to improve work-life balance, reduce stress, and ultimately enhance workplace productivity and retention.
</p>
In summary, this project focuses on identifying and addressing the challenges employees face due to family-related stressors, helping organizations create a supportive environment that benefits both employees and the company.
</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<h2 id="keytakeaway"> Key takeaways </h2>

- **Predictive Potential**: By analyzing socioeconomic, lifestyle, and medical data, this project demonstrates the potential of machine learning to predict mental health issues, providing valuable insights for early detection and intervention.

- **Scalability**: The approach used can be scaled to analyze large datasets, making it feasible for healthcare systems and public health organizations to monitor mental health trends and identify at-risk populations on a much larger scale.

- **Timely Interventions**: The model offers the opportunity to implement real-time mental health assessments, enabling organizations to take preventive measures and provide support before mental health issues escalate.

- **Data-Driven Decision Making**: This project highlights the power of data-driven insights in public health and workplace, helping to inform mental health policy, resource allocation, and targeted interventions based on quantifiable evidence.

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
    <h2>1. Data Collection and Exploration</h2>
    <ul>
      <li><strong>Task:</strong> Source the dataset containing personal, lifestyle, and family-related attributes impacting mental health, such as income, family dynamics, personal burden, and sociodemographic characteristics.</li>
      <li><strong>Objective:</strong> Gather comprehensive data to understand the multifaceted factors affecting mental well-being, forming the foundation for targeted interventions and research.</li>
    </ul>
  </div>
  
  <div style="margin-right: 20px;">
    <h2>2. Data Cleaning and Preprocessing</h2>
    <ul>
      <li><strong>Task:</strong> Clean the dataset by handling missing values, encoding categorical variables, scaling numerical features, and ensuring consistency across all data points.</li>
      <li><strong>Objective:</strong> Prepare clean, consistent, and usable data for analysis, free from outliers and errors that could distort predictive models.</li>
    </ul>
  </div>

  <div style="margin-right: 20px;">
    <h2>3. Stress Indicator Creation and Feature Engineering</h2>
    <ul>
      <li><strong>Task:</strong> Develop a normalized "Stress Indicator" that integrates key features, including income, personal burden, family/personal health, and social support, to measure stress levels across individuals.</li>
      <li><strong>Objective:</strong> Create a robust, comparable measure of stress that can be used to predict mental health outcomes and drive further analysis.</li>
    </ul>
  </div>

</div>

<div style="display: flex; align-items: center;">

  <div style="margin-right: 20px;">
    <h2>4. Exploratory Data Analysis (EDA)</h2>
    <ul>
      <li><strong>Task:</strong> Conduct detailed analysis to identify patterns and correlations between variables, focusing on the relationships between stress levels, family health, personal burden, and sociodemographic factors.</li>
      <li><strong>Objective:</strong> Uncover insights into how personal, family-related, and lifestyle factors contribute to stress, guiding the feature selection and model-building strategies.</li>
    </ul>
  </div>
  
  <div style="margin-right: 20px;">
    <h2>5. Hypothesis Testing and Statistical Analysis</h2>
    <ul>
      <li><strong>Task:</strong> Perform hypothesis testing and correlation analysis to validate the significance of key features, such as income, social support, personal burden, and family health.</li>
      <li><strong>Objective:</strong> Quantify the relationships between variables and validate the importance of stress-related factors to ensure reliable predictions.</li>
    </ul>
  </div>
  
  <div style="margin-right: 20px;">
    <h2>6. Predictive Modeling</h2>
    <ul>
      <li><strong>Task:</strong> Apply machine learning techniques like decision trees, random forests, and linear regression to predict stress levels based on the identified features.</li>
      <li><strong>Objective:</strong> Identify the most influential predictors of stress, including personal burden, social support, and family/personal health, to support targeted interventions.</li>
    </ul>
  </div>

</div>

<div style="display: flex; align-items: center;">

  <div style="margin-right: 20px;">
    <h2>7. Unsupervised Learning and Clustering</h2>
    <ul>
      <li><strong>Task:</strong> Apply K-means clustering to group individuals with similar stress profiles, segmenting the population based on shared characteristics such as stress levels, family burden, and social support.</li>
      <li><strong>Objective:</strong> Identify distinct groups with unique stress experiences, enabling tailored support interventions and insights into patterns of mental health challenges.</li>
    </ul>
  </div>
  
  <div style="margin-right: 20px;">
    <h2>8. Actionable Insights and Recommendations</h2>
    <ul>
      <li><strong>Task:</strong> Analyze the results of the clustering and predictive modeling to derive actionable insights for interventions, including wellness programs, flexible work arrangements, and enhanced social support initiatives.</li>
      <li><strong>Objective:</strong> Provide organizations with targeted strategies to address stress, enhance mental health, and improve overall well-being for employees.</li>
    </ul>
  </div>
  
  <div style="margin-right: 20px;">
    <h2>9. Conclusion and Future Work</h2>
    <ul>
      <li><strong>Task:</strong> Summarize the key findings, focusing on the predictive models, the significance of various features, and the insights derived from clustering.</li>
      <li><strong>Objective:</strong> Demonstrate how understanding stress levels and their underlying factors can inform better mental health support and interventions, with potential for future research to refine and improve interventions based on emerging data.</li>
    </ul>
  </div>

</div>


</div>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<h2 id="progression"> Project Progression </h2>

### Project Progression:

1. **Initial Project Direction**:
   - The project initially began by analyzing text data from mental health-related posts across various online platforms. The goal was to perform sentiment analysis on these texts to identify patterns and correlations with mental health issues, with the aim of developing a predictive model for mental health risk based on sentiment.
   - **Challenge**: However, the dataset lacked a clear target variable (such as a mental health diagnosis or outcome), which hindered the development of a supervised learning model. 
   - **Decision**: Given this limitation, it was decided to shift focus to a more structured dataset that included both features and target variables for predicting mental health outcomes.

2. **Dataset Shift**:
   - After evaluating the challenges with the text data, we pivoted to using the [Depression Dataset on Kaggle](https://www.kaggle.com/datasets/anthonytherrien/depression-dataset/data). This dataset includes detailed information about individuals' demographics, lifestyle, and medical factors that are related to mental health outcomes, specifically depression.
   - The dataset offered key features such as age, income, employment status, and mental health history, making it ideal for building a supervised learning model to predict mental health risks.

3. **Data Cleaning**:
   - The dataset underwent thorough cleaning, including handling missing values, encoding categorical variables, and scaling numerical features like income. This step ensured that all data was prepared for effective use in machine learning models and that the features were consistent across the dataset.
   - **Objective**: To ensure that the dataset was complete, consistent, and ready for analysis, allowing for accurate and meaningful model predictions.

4. **Exploratory Data Analysis (EDA)**:
   - An extensive EDA was performed to explore the relationships between key features, such as income, age, and lifestyle habits, and their influence on mental health outcomes. This analysis helped identify significant patterns and correlations that were useful for feature selection.
   - **Objective**: To gain insights into how various factors interact with mental health and guide the feature engineering and modeling steps.

5. **Feature Engineering**:
   - A crucial step in our analysis was the creation of a "stress indicator" variable, which combined multiple features such as income, social support, personal burden, and family health. This stress indicator helped quantify the level of stress experienced by individuals and was key to predicting mental health outcomes.
   - **Objective**: To create a comprehensive and interpretable feature that could effectively capture stress levels across individuals, guiding model predictions.

6. **Hypothesis Testing and Statistical Analysis**:
   - We performed hypothesis tests and correlation analysis to validate the stress indicator. Key findings included significant correlations between the stress indicator and variables such as income (negative correlation), social support (positive correlation), personal burden (positive correlation), and family/personal health (positive correlation).
   - **Objective**: To confirm the relationships between the stress indicator and mental health, further supporting the validity of our feature selection and the effectiveness of the stress indicator.

7. **Predictive Modeling**:
   - We implemented machine learning models, including Logistic Regression and Random Forest, to predict mental health outcomes based on the selected features. Hyperparameter tuning was performed for both models to optimize their performance. Model evaluation was conducted using metrics such as accuracy, precision, recall, and F1-score.
   - **Objective**: To determine the best predictive model based on the relationships identified during EDA and statistical analysis, and to fine-tune the models for optimal performance.

8. **Unsupervised Learning (K-Means Clustering)**:
   - We applied K-Means clustering to the dataset to group individuals with similar characteristics, such as stress levels, personal burdens, and sociodemographic factors. This helped identify distinct clusters with varying stress profiles, enabling targeted interventions based on group characteristics.
   - **Objective**: To segment the population based on similar stress experiences and to understand the diversity in stress profiles within the dataset, providing actionable insights for interventions.

9. **Final Model Evaluation**:
   - The Random Forest model was found to be the most effective model for predicting mental health outcomes. It was evaluated using cross-validation and key performance metrics to ensure its robustness and generalizability. 
   - **Objective**: To select the best model that provides the most accurate and reliable predictions, which can be used for practical applications.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<h2 id="datasource"> Data Source </h2>

### Data Source

The dataset used in this project integrates information from the following Kaggle dataset:

- **[Depression Dataset on Kaggle](https://www.kaggle.com/datasets/anthonytherrien/depression-dataset/data)**: A comprehensive collection of data capturing demographic, socioeconomic, and lifestyle factors relevant to mental health, specifically focusing on depression.

### Related Articles

- **[Alcohol intake, smoking, sleeping hours, physical activity, and the metabolic syndrome](https://pubmed.ncbi.nlm.nih.gov/17239432/)**: This article explores the relationship between various lifestyle factors and their impact on metabolic syndrome, offering valuable insights into how lifestyle habits influence mental health.
  
- **[Stress Assessment Questionnaires](https://academic.oup.com/occmed/article/73/3/175/7143170#google_vignette)**: This paper provides a detailed overview of commonly used stress assessment tools, which are relevant for understanding the psychosocial factors contributing to mental health.

 
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
<h2 id="learnings"> Project license </h2>

If you wish to use, distribute, or modify any part of this project, including its findings, please ensure proper attribution is given to the original work. Specifically, you must provide appropriate credit to the author Gennaro Costantino, and include a reference to the project or repository. You may not use the material for commercial purposes without explicit permission.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<h2 id="conclusions"> Conclusions and Next Steps </h2>

The project has successfully identified key predictors of mental health outcomes and developed a robust predictive model for assessing mental health risks. By leveraging supervised learning techniques, clustering, and advanced model tuning, we were able to uncover actionable insights for improving employee well-being. The next steps will involve deploying this model to help organizations implement more effective mental health programs and interventions.


<p align="right">(<a href="#readme-top">back to top</a>)</p>




