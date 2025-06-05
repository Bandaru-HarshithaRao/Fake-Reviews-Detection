# Identifying Fraudulent Product Reviews

## Objective

Classify a large collection of product reviews into fake or genuine, spanning categories such as Home & Office, Sports, etc. Each review includes a rating, a label (CG: Computer-Generated / OR: Original), and the review content. The main task is to determine whether a review is artificially generated or written by a human.

## Dataset Summary

This dataset includes 40,000 total reviews: 20,000 authentic (human-written) and 20,000 fake (machine-generated).  
- **OR** = Original (genuine human-written reviews)  
- **CG** = Computer-Generated (fake, synthetic reviews)

## Python Libraries and Tools Utilized

<ul>
  <li>Numpy</li>
  <li>Pandas</li>
  <li>Matplotlib.pyplot</li>
  <li>Seaborn</li>
  <li>Warnings</li>
  <li>nltk</li>
  <li>nltk.corpus</li>
  <li>String</li>
  <li>sklearn.naive_bayes</li>
  <li>sklearn.feature_extraction</li>
  <li>sklearn.model_selection</li>
  <li>sklearn.ensemble</li>
  <li>sklearn.tree</li>
  <li>sklearn.linear_model</li>
  <li>sklearn.svc</li>
  <li>sklearn.neighbors</li>
</ul>

## Text Preprocessing Strategies

<ul>
  <li>Removing punctuation marks</li>
  <li>Converting all text to lowercase</li>
  <li>Filtering out stopwords</li>
  <li>Stemming to root forms</li>
  <li>Lemmatization to base dictionary form</li>
  <li>Eliminating numeric characters</li>
</ul>

## Methods for Text Vectorization and Normalization

<ul>
  <li>Bag-of-Words using CountVectorizer</li>
  <li>TF-IDF (Term Frequency-Inverse Document Frequency) transformation</li>
</ul>

## Machine Learning Models Implemented

<ol>
  <li>Logistic Regression</li>
  <li>K-Nearest Neighbors</li>
  <li>Support Vector Classifier</li>
  <li>Decision Tree Classifier</li>
  <li>Random Forest Classifier</li>
  <li>Multinomial Naive Bayes</li>
</ol>

## Model Evaluation and Performance Insights

<p>The Support Vector Classifier outperformed other models with a predictive accuracy of over 88%. Logistic Regression also delivered strong results, with accuracy slightly above 86%. Random Forest and Multinomial Naive Bayes each achieved around 84% accuracy. Decision Tree's performance was comparatively lower, reaching just over 73%. The least effective model was K-Nearest Neighbors, which managed only about 58% accuracy in classifying fake reviews.</p>
