# Twitter NLTK ML Sentiment Analysis - Numpy, Pandas, Matplotlib, Seaborn, Scikit-learn
* The machine learning pipeline was developed using Logic Regression, Multinomial Naive Bayes, and SVM classifiers, in addition to Term Frequency-Inverse Document Frequency (TF-IDF), to predict the polarity and subjectivity classifications of Tweets
* The performance of probabilistic classifiers was assessed using F1 scores, ROC-AUC curves, and confusion matrices 
* The data was preprocessed using Snowball stemming and lemmatization to normalize words to their canonical form
* Over 30 000 Tweets were scraped using the Twitter API and cross-referenced with a static CSV dataset for accuracy
* The scraped dataset was serialized into a pickle file to improve future scraping efficiency through de-serialization
* Visualization of the distribution of polarity and subjectivity values was performed using Kernel Distribution Estimate (KDE) plots and Histograms 

