<a name="readme-top"></a>
<br />
<div align="center">

  # Sentiment Analysis Mental-Health Predictor
### Machine Learning and Mental-Health Predictor

  </a>


</div>

## Project Overview

This project utilizes Machine Learning techniques to attempt to increase the accuracy of understanding public sentiment on mental health issues via social media.

This project will attempt to find a solution to the following:

"How does public sentiment towards mental health issues vary across different conditions (e.g., depression, anxiety, suicidal thoughts) on social media, and how can this sentiment inform mental health interventions and policy-making?"

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
The motivation for this project stems from the growing recognition of mental health as a critical societal issue, coupled with the increasing use of social media as a platform for individuals to express their thoughts and experiences related to mental health. 

<h2 id="opportunity"> The opportunity </h2>
The data science opportunity lies in leveraging advanced machine learning and natural language processing (NLP) techniques to analyze vast amounts of textual data from these platforms (social media). By automating the analysis of sentiment in mental health-related conversations, we can uncover deep insights into public sentiment, identify key topics of discussion, and track how these sentiments evolve over time. This capability not only enhances our understanding of public attitudes towards mental health but also provides actionable information that can inform mental health interventions, shape public health campaigns, and influence policy decisions. The potential to impact real-world outcomes, such as improving mental health support and reducing stigma, makes this project both timely and valuable. The ability to automate the analysis of sentiment in mental health-related conversations offers several opportunities:

        Real-time Monitoring: Develop tools that can monitor social media in real-time to detect shifts in public sentiment about mental health issues. This can alert mental health professionals and organizations to emerging concerns or crises, enabling timely interventions.

        Targeted Mental Health Campaigns: By understanding the emotional tone and key topics in public discourse, mental health organizations can tailor their communication strategies to address specific concerns, counteract stigma, and promote mental health awareness more effectively.

        Policy and Decision-Making: Policymakers can use insights from sentiment analysis to inform mental health policies that resonate with the public's needs and concerns. For example, detecting a rise in negative sentiment related to anxiety during a particular period could prompt targeted policy actions or public health campaigns.

        Support for Mental Health Professionals: Mental health professionals can benefit from understanding the broader social context in which their patients operate. Insights from sentiment analysis can help them anticipate and address common challenges faced by their patients, such as stigma or misinformation.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<h2 id="keytakeaway"> Key takeaways </h2>
Scalability: Sentiment analysis can process and analyze large datasets, making it possible to understand public sentiment on a massive scale—far beyond what manual analysis could achieve.

Timeliness: By applying real-time sentiment analysis, organizations can respond quickly to shifts in public mood, enabling more agile and effective interventions.

Contextual Understanding: Beyond simple positive or negative labels, sentiment analysis can provide a nuanced understanding of the public's feelings about specific mental health topics, such as depression, anxiety, or stigma.

Data-Driven Insights: Sentiment analysis can transform unstructured text data into actionable insights, helping to inform decisions in mental health advocacy, public health campaigns, and policy development.

Ethical Considerations: It's essential to approach sentiment analysis with sensitivity, particularly in the context of mental health. Ensuring data privacy, addressing potential biases in models, and considering the ethical implications of the findings are crucial steps in responsible data science practice.    

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<h2 id="data"> The Data</h2>
The data used for this project is derived from various social media platforms where mental health is a common topic of discussion. This includes Twitter data, Reddit posts, and to build our model we have used the Sentiment Analysis for Mental Health (Kaggle) dataset: 

https://www.kaggle.com/datasets/suchintikasarkar/sentiment-analysis-for-mental-health. 

This comprehensive dataset is a meticulously curated collection of mental health statuses tagged from various statements. The dataset amalgamates raw data from multiple sources, cleaned and compiled.

Acknowledgments:
This dataset was created by aggregating and cleaning data from various publicly available datasets on Kaggle. Special thanks to the original dataset creators for their contributions.

Each of the 51074 instances are a unique comments tagged with a specific mental health status.
Including:

<h2 id="dict"> Data Dictionary</h2>

<table>
  <tr>
    <th style="text-align: left; background: lightgrey">Column Name</th>
    <th style="text-align: left; background: lightgrey">Description</th>
  </tr>
  <tr>
    <td style="text-align: left"> <code>unique_id</code> </td>
    <td style="text-align: left">A unique identifier for each entry.</td>
  </tr>
  <tr>
    <td style="text-align: left"><code>Statement</code></td>
    <td style="text-align: left">The textual data or post.</td>
  </tr>
  <tr>
    <td style="text-align: left"><code>Mental Health Status</code></td>
    <td style="text-align: left">The tagged mental health status of the statement.</td>
  </tr>
</table>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<h2 id="roadmap"> Project Roadmap </h2>
<div style="display: flex; align-items: center;">

  <div style="margin-right: 20px;">
    <h2>1. Data Collection</h2>
    <ul>
      <li><strong>Task:</strong> Gather text data related to mental health from various social media platforms like Twitter and Reddit, as well as structured datasets such as Sentiment140.</li>
      <li><strong>Objective:</strong> Compile a comprehensive dataset that includes diverse mental health discussions to ensure a rich variety of sentiment and topic analysis.</li>
    </ul>
  </div>
  
  <div style="margin-right: 20px;">
    <h2>2. Data Cleaning</h2>
    <ul>
      <li><strong>Task:</strong> Handle missing data in text entries, remove irrelevant or noisy data, and standardize text format (e.g., lowercase conversion, removal of special characters).</li>
      <li><strong>Objective:</strong> Ensure the dataset is clean, consistent, and ready for accurate sentiment analysis and modeling.</li>
    </ul>
  </div>

  <div style="margin-right: 20px;">
    <h2>3. Exploratory Data Analysis (EDA)</h2>
    <ul>
      <li><strong>Task:</strong> Explore the cleaned dataset to understand the distribution of sentiments, identify the most commonly discussed mental health topics, and detect underlying patterns or trends.</li>
      <li><strong>Objective:</strong> Gain insights that will guide feature engineering and model development, and formulate hypotheses for further analysis.</li>
    </ul>
  </div>

</div>

<div style="display: flex; align-items: center;">

  <div style="margin-right: 20px;">
    <h2>4. Data Splitting/Model Selection</h2>
    <ul>
      <li><strong>Task:</strong> Split the dataset into training, validation, and test sets. Select appropriate machine learning models, such as Logistic Regression, Naive Bayes, or advanced NLP models like BERT, to analyze sentiment.</li>
      <li><strong>Objective:</strong> Train and fine-tune models to predict sentiment accurately across different mental health topics.</li>
    </ul>
  </div>
  
  <div style="margin-right: 20px;">
    <h2>5. Model Evaluation</h2>
    <ul>
      <li><strong>Task:</strong> Assess the performance of the trained models using validation data. Evaluate models based on accuracy, precision, recall, and F1-score.</li>
      <li><strong>Objective:</strong> Identify the most effective model and understand its strengths and limitations, making adjustments as necessary.</li>
    </ul>
  </div>
  
  <div style="margin-right: 20px;">
    <h2>6. Model Deployment</h2>
    <ul>
      <li><strong>Task:</strong> Deploy the final model to make predictions on unseen test data. Integrate the model into a real-time application, such as a dashboard for mental health professionals to monitor public sentiment.</li>
      <li><strong>Objective:</strong> Provide actionable insights to stakeholders and continue monitoring model performance in real-world scenarios, making updates as needed.</li>
    </ul>
  </div>

</div>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<h2 id="progression"> Project Progression </h2>

Write here .....

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<h2 id="datasource"> Data Source </h2>
The dataset integrates information from the following Kaggle datasets:

3k Conversations Dataset for Chatbot: https://www.kaggle.com/datasets/kreeshrajani/3k-conversations-dataset-for-chatbot
Depression Reddit Cleaned: https://www.kaggle.com/datasets/infamouscoder/depression-reddit-cleaned
Human Stress Prediction: https://www.kaggle.com/datasets/michellevp/predicting-anxiety-in-mental-health-data
Predicting Anxiety in Mental Health Data: 
Mental Health Dataset Bipolar: https://www.kaggle.com/datasets/neelghoshal/reddit-mental-health-data
Reddit Mental Health Data: https://www.kaggle.com/datasets/neelghoshal/reddit-mental-health-data
Students Anxiety and Depression Dataset: https://www.kaggle.com/datasets/sahasourav17/students-anxiety-and-depression-dataset
Suicidal Mental Health Dataset:https://www.kaggle.com/datasets/aradhakkandhari/suicidal-mental-health-dataset
Suicidal Tweet Detection Dataset: https://www.kaggle.com/datasets/aunanya875/suicidal-tweet-detection-dataset 
 
<p align="right">(<a href="#readme-top">back to top</a>)</p>
<h2 id="repository"> Repository </h2>

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

Write here ...

<p align="right">(<a href="#readme-top">back to top</a>)</p>





