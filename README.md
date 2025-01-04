# Named-Entity-Recognition-NER-and-Feature-Engineering

Objective
The goal of this task is to analyze a set of news articles through Named Entity Recognition (NER)
and to engineer numerical features based on these entities for predictive modeling. You will extract
named entities from the articles using an open-source LLM model, create insightful features, and build a
predictive model to determine article popularity based on engagement metrics. This task assesses your
skills in natural language processing, feature engineering, and predictive analytics.
Instructions
1. Data Collection:
• Utilize the provided dataset of news articles:
• [News Articles Dataset](https://www.kaggle.com/datasets/sbhatti/news-articles-dataset)
2. Text Preprocessing:
• Conduct necessary preprocessing steps on the text, including:
– Removing unnecessary whitespace, HTML tags, and special characters.
– Normalizing text (convert to lowercase).
– Tokenizing the text and removing stop words using libraries like NLTK or SpaCy.
3. Named Entity Recognition (NER):
• Use an open-source LLM model (e.g., SpaCy, Hugging Face) to extract named entities from
the cleaned articles.

• Entity Categorization: Ensure entities are categorized correctly into types such as organi-
zations (ORG), locations (GPE), and people (PERSON).

• Create numerical features based on the frequency of each entity type in each article (e.g.,
count of organizations, count of locations).
4. Feature Engineering:
• Combine entity counts with additional features to create a comprehensive feature set:
– Article length (number of words).
– Sentiment scores (using libraries like TextBlob or VADER).
– Engagement metrics (likes, shares, comments) if available in the dataset.
• Innovation: Derive creative features beyond the basic entity counts to enhance the feature
set.
5. Predictive Modeling:
• Train a predictive model using the engineered features to predict article popularity.

• Choose an appropriate model (e.g., Linear Regression, Random Forest) and evaluate its per-
formance using accuracy scores, F1-scores, or mean absolute error (MAE).

6. Visualization:

1

• Create visualizations to show the relationship between named entities and article popularity
using libraries like Matplotlib or Seaborn.
• Include relevant plots, such as:
– Bar charts for entity frequency.
– Scatter plots illustrating correlations.
– Heatmaps for the relationship between entity counts and engagement metrics.
7. Documentation:
• Document the entire process in a report that includes:
– Methodology for data preprocessing and feature extraction.
– Details about the predictive modeling process and performance metrics.
– Insights on how named entities impact article engagement and popularity.

Deliverables
• Jupyter Notebook: Containing code, analysis, visualizations, and comments explaining each
step.
• PDF Report: Summarizing methodology, findings, visualizations, and insights on named entities
and their effects on article engagement.
