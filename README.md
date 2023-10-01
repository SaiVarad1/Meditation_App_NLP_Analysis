
# Topic Modelling on Meditation App Reviews
Links:
Dataset: https://www.kaggle.com/datasets/dtomruk/app-store-meditation-app-reviews?select=appstore_calm_us.csv

### Google Colab Notebook: 
https://colab.research.google.com/drive/1iM3AAJ4SHpunrqijtFF7jG_BbAxAS7E0?usp=sharing (_also uploaded in repo as well as pdf of final poster_)

### Final Poster with Project Description: 
https://github.com/SaiVarad1/Meditation_App_NLP_Analysis/blob/main/Sai%20V-%20MeditationApp_Poster.pptx.pdf

My project aims to use topic modeling to analyze a dataset of meditation app reviews and highlight the importance of effective hyperparameter tuning.

The dataset consists of columns for the index, date, rating, as well as comments.

I have separated the dataset into two, one for positive reviews (with a rating higher than 3), and one with negative reviews (with a rating less than 3). I then performed topic modeling on the comments of each dataset using BERtopic and then created visualizations representing these clusters of topics.

I will then create different visualizations based on different values for the hyperparameters, namely the n_components and n_neighbors for the positive and negative reviews respectively.

I will then compare and contrast these visualizations to see which parameter values enable the best topic models.
