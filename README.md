# Financial-Advisor-Recommendation-Analysis

#### Motivation

This project was created for the NUS Datathon 2025 Advanced Category, where the task involved building a recommendation system for financial services. The focus was to develop a model that could effectively match financial advisors to potential clients to optimize insurance policy conversions. The project provided a structured way to practice handling relational datasets—spanning agent, client, and policy info—while addressing critical concerns regarding ethical AI and bias mitigation in predictive modeling.

#### Methodology

The analysis uses a series of relational datasets including agent performance history, client demographics, and policy transaction records. The data is first integrated and reviewed for right-skewed distributions, particularly in features like Agent Tenure. Summaries and visualizations such as boxplots and heatmaps help identify the key drivers of conversion and examine the distribution of agent experience.

Feature engineering included extracting variables for advisor reliability and selecting economic indicators that influence a client's likelihood to purchase. For our model, Logistic Regression was used to predict conversion probabilities, and it was chosen for its high interpretability and probabilistic output. To ensure ethical standards, sensitive attributes like Client Age were excluded from the modeling process to prevent demographic bias.
