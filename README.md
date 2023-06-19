# Political-Tweet-Prediction-and-Bot-Detection
The project involved implementing a machine learning model to analyze political tweets and classify them accordingly. We utilized various features such as the number of political entities, total interactions, hashtags, mentions, and more to make accurate predictions. Additionally, we incorporated bot detection techniques, considering features like description length, followers-to-all ratio, retweet total ratio, and user engagement metrics. The project provided me with hands-on experience in data analysis, feature engineering, and model training for political tweet prediction and bot detection.

# Explaining the approach

data_explanations = '''
We used all of the datasets that is provided to us: 'annotation_users', 'annotation_tweets', 'tweet-data', 'evoluations3', 'training data'.
'''

feature_explanations = '''
Politics:
We created verified status and protected account features and checked these features:
['num_political_entities','total_interactions','num_hashtags','num_mentions','text_len','description_political_num','num_retweets', 'RFP'] 


BOT:
We created a daily tweet ratio feature and checked these features: 
['description_len', 'followers_to_all_ratio', 'retweet_total_ratio', 'num_median_favorites', 'check_is_protected', 'num_of_tweets', 'num_median_hashtags', 'user_friends_count', 'user_followers_count']]
'''

model_explanations = '''
We used Random Forest for increasing the accuracy. At each round, we will try to use different models such as K-Folds. We tried LogisticRegression model too, but it gave us a worse score of Accuracy, therefore we did not use it.
'''

additional_explanations = '''
We will try to consider words, dates, number of retweets in other models too. So we are planning to increase the total accuracy. 
'''
