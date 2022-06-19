# Sentiment-Analysis
Twitter sentiment analysis with NLP and amazon feedback sentiment analysis
HELLO, This is a Sentiment Analysis project using Natural Language Processing(NLP). Here data was obtained from Kaggle which contained the tweets(tweets made by thousands of people), labels(the sentiment of people which are in zero's (0) and one's (1) where zero means the person is angry or sad or basically something negative while the one means a positive tweet and the id(which of course is irrelevant to us). The aim of this project is to use the Naive Bays model to test and train the dataset to find the unknown class(data) prediction the steps are taken are:
1.	install packages necessary for the completion of this project(word cloud, Jupyter themes,nltk)
2.	import all the libraries needed
3.	Read the data on a CSV file
4.	EDA(Exploratory Data Analysis) which involves the statistical calculation, graphical representation, and dropping of irrelevant tables)
5.	using worldcloud as a data visualization technique used in representing text data in which the size of each word indicates it frequency or importance. so this was done for the data to know which of the tweets was more than the other and whether the negative was more than positive
6.	Cleaning of the data(removing punctuations and stop words) and converting it to an array
7.	Testing and training of the data that has been cleaned and converted to an array
8.	Visualization of confusion matrix with seaborn heatmap


This same steps apply to the amazon review feedback sentiment analysis but the only different thing is that two models were trained and tested and comared,the nave bays model and the logistic regression,
