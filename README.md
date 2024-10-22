# Product review Sentiment Analysis
This project performs sentiment analysis on product reviews to determine whether the sentiment expressed is positive, negative, or neutral. Natural Language Processing (NLP) techniques are used to analyze customer feedback and derive insights into how customers perceive products.

## Project Overview
Objective: Analyze product reviews to classify the sentiment as positive, negative, or neutral.
Approach: NLP techniques are applied to clean, process, and analyze text data from customer reviews.

## Tools and Libraries
Jupyter Notebook: The project is implemented in a Jupyter Notebook
Python Libraries:
NumPy: For numerical computations.
Pandas: For data manipulation and analysis.
nltk: For natural language processing tasks (tokenization, stopwords, etc.).
TextBlob: For simple sentiment analysis.
re: For regular expressions to clean text data.
WordCloud: For visualizing word frequencies.
Seaborn: For creating visualizations.
Cufflinks: For interactive plots.
VADER Sentiment Analyzer from vaderSentiment: For more advanced sentiment scoring.

## Steps in the Analysis
1. Data Loading: Load the dataset containing product reviews.
2. Data Cleaning: Preprocess the reviews by removing special characters, stopwords, and unwanted text.
3. Exploratory Data Analysis (EDA): Generate visualizations to explore the distribution of reviews and common words.
4. Sentiment Analysis: Applied TextBlob and VADER Sentiment Analyzer to classify reviews into positive, negative, or neutral sentiments.
5. Word Clouds: Created word clouds to visualize frequently used words in positive and negative reviews.
6. Result Evaluation: Evaluated the sentiment scores and analyzed the overall distribution of sentiments in the reviews.

## Key Features
Natural Language Processing: Leveraged NLP techniques to process text data.
Sentiment Classification: Utilized both TextBlob and VADER Sentiment Analyzer to classify the sentiment.
Visualizations: Created word clouds and other visualizations using Seaborn and Cufflinks to better understand the data.

## How to Use
Clone the repository and run the Jupyter notebook to perform sentiment analysis on product reviews:
https://github.com/payalkosbatwar/review-sentiment-analysis.git

Install the required libraries:
pip install numpy pandas nltk textblob wordcloud seaborn cufflinks vaderSentiment

Open the notebook in Jupyter:
jupyter notebook <file-name>.ipynb

## Results
The sentiment analysis provides insights into customer satisfaction by classifying the sentiment of each review. Word clouds give a quick overview of common terms in positive and negative feedback, helping to identify key product issues or highlights.
