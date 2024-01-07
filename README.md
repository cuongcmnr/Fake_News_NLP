For CountVectorizer:
1.Taking data from kaggle of 20800 data
2.Preprocessing : Remove RE, special character, remove stop words, make all lower case
3.USe bag of words method to make feature matrix with 5000 max features and most 3 consecutive words range.
4.Train test split whith 33% test size
5.Train seven different ML algorithms to the processed dataset.



For TF-IDF:
1.Take train(20800 data) and test(5200) data from kaggle
2.Preprocessing: Make new column using News Title and Whole News and News Author
3.Use TF-IDF transformer to transfer the train and test data into feature matrix.
4.Default train test split
5.Train six different ML algorithms to the processed dataset.


LSTM:
A sequential deep learning model has been implemented using LSTM architecture for binary text classification that performed better with around 99% accuracy. The dataset has been collected from Kaggle and is of the size 20800. The task was to predict if the news is fake or real. Therefore, the pretrained Glove text embedding algorithm has been used as a text vectorization technique. Besides, several classical models have been implemented with BOW, TF-IDF text vectorization methods. Therefore, the LSTM based deep learning model performs better to classify news.
