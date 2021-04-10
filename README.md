# MIDAS-RA-TASKS

I have done both Task-2 and Task-3 which were given in MIDAS-RA internship task. 

Task-2 was a quite simpler task. Where we have to build a CNN model and train on digits and aphabets which were given in dataset provided. And then to check that accuracy for MNIST dataset. This task was having 3 parts:
1) Use this dataset (https://www.dropbox.com/s/pan6mutc5xj5kj0/trainPart1.zip) to train a CNN modek.
2) Next, select only 0-9 training images from the above dataset, and use the pretrained network to train on MNIST dataset. Use the standard MNIST train and test splits.
3) Finally, (https://www.dropbox.com/s/otc12z2w7f7xm8z/mnistTask3.zip), train on this dataset and provide test accuracy on the MNIST test set.

This task was quite simpler, I first used ImageDataGenerator and then trained CNN model on train generator and checked validation accuracy on validation_generator. 

And Taks-3 was quite challenging. I dealt with it by different kinds of approaches. This task was to identify primary categories of that product by using product description as main feature only. As, in given dataset there were many primary categories. But i chose top occuring 15 primary categories only as they were more important and hold value. (I chose that by data analysis of dataset which I have done in my notebook) Then I used CountVectorizer and TF-IDF vectorizer and trained different ML algorithms like KNN, Multinomial Naive Bayes, Random Forest Classifier, LGBM classifier etc. Then I moved to deep learning techniques. I trained a simple LSTM model and used Keras-inbuilt Tokenizer for that. I used very basic LSTM model. It even gave quite good accuracy. By changing/modelling architecture, We could get quite good accuracy. But my main objective during this task was to apply good variety of NLP techniques and get decent accuracy. Then I used Bert tokenizer also in another notebook, which also gave quite good accuracy.

So, thats about my both tasks. My main objective in both taks to learn more and apply different techniques in both taks. If you want to see my other work, you can see my kaggle profile as well:) https://www.kaggle.com/shivammittal274

Thanks