Detecting Twitter Bots in the Early Phase of COVID-19 Pandemic

**You can view the 2nd notebook here:https://nbviewer.org/github/samuel0324/covid19-twitter-bot-detection/blob/7778fb4370f8fa198cad2310f0023d25966d753b/capstone_samuel_park_notebook2.ipynb**

Author: Samuel Park
Date of writing this README file: 12/06/2021
Contact for questions or feedback: samupark24@gmail.com

This project was initiated as capstone at BrainStation Online Data Sciene bootcamp.
It is still work in progress.

As someone interested in national security and information warfare, I ventured to use the data science/machine learning skills I learned from this program
to detect bots in early COVID-19 tweets between March 29th and April 30th, 2020.

The datasets were provided by Shane Smith on Kaggle.
Dataset 1 (early April tweets): https://www.kaggle.com/smid80/coronavirus-covid19-tweets-early-april
Dataset 2 (late April tweets): https://www.kaggle.com/smid80/coronavirus-covid19-tweets-late-april

Notebook1 concatenates all the CSV files and selects only the English tweets.
Notebook2 contains data cleaning, feature engineering, modeling, and interpretations.

Unsupervised learning, specifically K-Means clustering, was employed for modeling.

Useful insights have been discovered for building a bot profile:

- Many of the most frequently tweeting accounts were bots, but not necessarily malicious
- Malicious bots may be optimizing their tweet volume and the risk of detection
- NLP-oriented machine learning modeling is advised (e.g., models that use word embedding/cosine similarity)
- Use unsupervised learning to uncover more patterns for bots and manually label some bot accounts (~100)
- Transition to supervised learning (e.g., Random Forest Classifier) and train on the labeled data
- Test the model and have a human review the results


