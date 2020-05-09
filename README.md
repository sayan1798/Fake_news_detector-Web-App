# Fake_news_detector-Web-App

All news are not real, right? So how will you detect the fake news? We will be using Multinomial Naive Bayes method to classify the news article scrapped from the news article link, as fake or real.

Data:

The dataset we’ll use for this python project- we’ll call it news.csv. This dataset has a shape of 7796×4. The first column identifies the news, the second and third are the title and text, and the fourth column has labels denoting whether the news is REAL or FAKE.

NOTE:Since the dataset is large. I have uploaded the dataset in zip format named 'news'. Unzip the file to extract the dataset.
     or The dataset can be downloaded from [here](https://drive.google.com/file/d/1er9NJTLUA3qnRuyhfzuN0XUsoIC4a-_q/view)
     
requirements.txt file - It contains the list of libraries required to run the heroku app.

Running the project on local machine:

Ensure that you are in the project home directory. Create the machine learning model by running below command -
python fake_news_detection.py
This would create a serialized version of our model into a file model.pkl

Run app.py using below command to start Flask API
python app.py
By default, flask will run on port 5000.

Navigate to URL http://127.0.0.1:5000 


Checkout the app on this [link] https://sayantan66-fake-news-detect.herokuapp.com/

For Testing the app try these two news urls:

1. https://www.ndtv.com/world-news/kim-jong-un-death-news-north-korea-leader-alive-and-well-says-south-korea-2218715

2. https://n5ti.com/stories/1275/
.
