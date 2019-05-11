# Streaming-Sentiment-Analysis
Twitter streaming sentiment analysis using Spark and socket programming

Instructions to run the notebook file

Link to Dataset: http://cs.stanford.edu/people/alecmgo/trainingandtestdata.zip

Step1 : Run the 'Logistic Regression Sentiment Analysis Model.ipynb' notebook file

Prerequisites for step1: 
1. Ensure DataSet "training.1600000.processed.noemoticon.csv" is available in working directory.
2. Change the parameters in 'outputfile' and 'modeldir' to locations of your choice.

Prerequisite for step2 and step3: The saved model location should be defined in parameter 'modeldir'.

Step2: Run the 'twitter_API.ipynb' notebook file.
Step3: Once the notebook displays the message 'Waiting for TCP Connection', run the 'spark streaming.ipynb' file. 
Step4: Load the "result_sample.csv" file to Tableau. (In attachment the Tableau data is already stored in packaged workbook)






