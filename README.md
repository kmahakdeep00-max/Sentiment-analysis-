# Sentiment-analysis-
Company Name: CodTech IT Solutions
Intern Name: Mahakdeep Kaur
Intern ID: CITS753
Domain: Data Analytics 
Duration: 8 weeks
Project Title: Sentiment Analysis using NLP 


During my CodTech internship, I worked on the project “Sentiment Analysis using NLP”. The task was not just about building a model, but about understanding the complete pipeline of how raw text can be transformed into meaningful insights.

I started with the IMDB dataset, which contained thousands of movie reviews. At first, the data looked messy — uppercase letters, punctuation, and irrelevant words everywhere. To make the dataset usable, I applied preprocessing techniques: converting text to lowercase, removing punctuation, eliminating stopwords, and tokenizing sentences. This step taught me the importance of cleaning data before analysis.

Once the text was clean, I moved to feature extraction. I experimented with two approaches: Bag of Words (CountVectorizer) and TF‑IDF. Bag of Words gave me simple word counts, while TF‑IDF helped highlight important words that carried more meaning. Comparing both methods gave me a deeper understanding of how feature representation impacts model performance.

For classification, I trained multiple models. Naive Bayes with CountVectorizer achieved around 85% accuracy, Naive Bayes with TF‑IDF improved slightly to 87%, but the real breakthrough came with Logistic Regression using TF‑IDF, which reached nearly 90% accuracy. I validated these results using confusion matrices and classification reports.

To make the findings clear, I plotted a comparison graph of all models. The visualization showed a clear difference, with Logistic Regression outperforming the others. This step was crucial because it allowed me to present results not just in numbers but in a way that anyone could understand visually.

Beyond technical implementation, the project gave me valuable learning. I realized how preprocessing directly affects accuracy, how feature extraction changes the way models interpret text, and how different algorithms behave with the same dataset. More importantly, I learned to think critically about why one model performs better than another.

In conclusion, this project was more than just coding — it was about connecting theory with practice. It gave me confidence in handling NLP tasks and showed me how sentiment analysis can be applied in real‑world scenarios like customer feedback, product reviews, and social media monitoring. Logistic Regression with TF‑IDF proved to be the most reliable approach, and this insight will guide me in future projects.
