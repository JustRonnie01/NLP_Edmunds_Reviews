# NLP_Edmunds_Reviews
Phase 4 Project to determine sentiment analysis (Positive, Neutral, Negative) on car reviews from Edmunds.

Presentation Link 
https://docs.google.com/presentation/d/1BHrI5dpH_0KNKd6FADqzyh3vHXJNE9x_rfapA27Vi8w/edit#slide=id.g1479cb4777d_0_8

Kaggle Dataset 
https://www.kaggle.com/datasets/shreemunpranav/edmunds-car-review

Analysis Overview

    Data Preprocessing:
        Imported necessary libraries.
        Loaded the dataset and performed initial data exploration.
        Handled missing values in the dataset.

    Exploratory Data Analysis (EDA):
        Explored basic information about the dataset using df.info() and df.head().
        Visualized total positive and negative reviews by car brand using bar plots.
        Calculated the ratio of total negative to positive percentage reviews by brand and visualized the results.

    Sentiment Analysis:
        Classified reviews into positive, neutral, and negative categories based on the Edmunds ratings.
        Utilized the TF-IDF Vectorizer to prepare the data for machine learning models.

    Machine Learning Models:
        Trained two different models for sentiment classification: Multinomial Naive Bayes and Complement Naive Bayes.
        Evaluated model performance using accuracy, precision, recall, and F1-score metrics.
        Visualized confusion matrices to analyze model predictions.

Conclusion

The project successfully analyzed car reviews, determined sentiment categories, and implemented machine learning models for sentiment classification. The Complement Naive Bayes model demonstrated better performance, providing valuable insights into customer sentiments regarding different car brands.

Feel free to explore the Jupyter notebook for a detailed step-by-step walkthrough of the analysis.
