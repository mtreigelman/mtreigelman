Hello, I’m Michael Reigelman | LinkedIn: [@mtreigelman](https://www.linkedin.com/in/mtreigelman/) | Twitter: [@MtReigelman](https://twitter.com/MtReigelman)

I am currently a Master's Student in Data Science at the [University of San Francisco](https://myusf.usfca.edu/arts-sciences/data-science/program-requirements), and will be graduating in the summer of 2022. 

In addition to the work I've done for school, I also have an interest in working on: data visualizations, maps, ML & prediction modeling, projects related to coding and music, sports analytics, and autonomous control systems.

Tools used in my projects include Python, PySpark, SciKitLearn, Pytorch, Plotly, Unix, SQL , and NoSQL (MongoDB).

Many of my projects from school are private; so if you are curious about any of the projects listed below, please feel free to contact me via [LinkedIn](https://www.linkedin.com/in/mtreigelman/) for more information. 


## Machine Learning Projects:  

###### **[Kaggle Competition (within USF Cohort)](https://www.kaggle.com/competitions/predicting-implicit-ratings-usfca-2022)**:  

- Predict implicit ratings from four features (whether a user is likely to like/buy a specifc item), using data from this [Booking.com Kaggle competition](https://www.kaggle.com/teresasereno/booking-challenge-data). Placed in the top 10 out of 55 teams. 


###### **Linear Regression Model Python Library Creation**:  

- Created Linear & Logistic, and Ridge & Lasso Regression tools (python libraries) to function similarly to scikit-learn's models. These two tools can fit and predict from a user-defined data set. Loss functions can also be selected via the model’s hyperparameters, and include gradient descent, sigmoid, and log-likelihood functions for all classes. These are python object-oriented programming .py files.


###### **Decision Tree Model Python Library Creation**: 

- Created a decision tree model library for both classifiers and regressors in python object-oriented files. From data provided by the user, these models were able split data, fit train data, and predict and score the test data. Speed requirements were also imposed by the grader and were factored into the code (be able to run multiple tests in under 30 secs).  


###### **Random Forest Model Python Library Creation**:  

- The decision tree project above was revamped to become a Random Forest model library for both classifiers and regressors. Bootstrapping was added to the previous code, and a few new classes were needed to get the same functionality. Again, this was done through python’s object-oriented abilities and allowed for the similar data split, modeling training, accuracy scoring, and speed requirements.
 
 
## Data Pipeline Projects
  
###### **COVID-19, U.S. Depression, & Twitter Relationship Analysis using Machine Learning**:
   
- In this project I setup a data pipeline moving information from AWS S3 to a MongoDB distributed database. Machine learning analysis was coded in Databricks to understand a variety of questions about how depression was related to COVID-19 cases and tweet sentiments on various topics. A blog post detailing the questions asked and the results found will be published and linked here in the coming days. 
  
 
 ## Data Science Reports
 
 ###### **K-Means Clustering**:
 
A detailed notebook discussing topics related to K-Means clustering including:
- What K-means is, and how it works
- Practical Applications and Examples
- Inadequacies of K-Means
- Spectral Clustering
- Real-World Applications of K-Means


###### **Feature Imporantance**:
 
A detailed notebook discussing topics related to Feature Importance using data from the National Football League. Topics include:
- Analysis techniques
- Algorithm explanation
- Strategies for using feature importance to improve machine learning models
- Examples and visualizations
 

## Data Acquisition Projects: 

###### **Data File Converter**: 

- Created a series of python scripts to parse .txt files and output a .html, .csv, .json, or .xml file; depending on request. A second set of scripts was created to reverse these changes when required.


###### **Word Search Engine**:  

- From a collection of around 17GB of .txt files, python scripts were created to perform linear searches, index/dictionary searches, and hash table searches of words or phrases contained in the documents. The results were then pushed to a local .html file that could be viewed and navigated by the user in their browser of choice. This would allow for the user to see the results as well as open up the desired file to read the contents all within the browser. Jinja2 was utilized for the HTML file formatting.


###### **Term Frequency Inverse Document Frequency (TFIDF) Tool**: 

- From a large Reuters article database, a TFIDF tool was created in python that would parse and score articles from a .xml format. An evaluation code was provided by the grader to measure the code’s accuracy and speed requirements were also enforced & achieved. 


###### **Article Recommender**:  

- Using an AWS Server, python files ran a temporary website to provide links to articles (.txt files saved on the AWS machine) and recommend similar articles to the user. The user could navigate to an article, read its contents, and be provided with 5 articles like what their selection was about. Jinja2 was used for HTML formatting. The Stanford GLOVE database was also used to get article similarity scores for the recommendations. 

 

###### **Tweet Sentiment Analysis Server**:  

- Created an AWS server was created to run a temporary website where the user could view the last 100 tweets by any Twitter profile and have a color-coded sentiment score appear: red meaning more negative tweets, while green means positive. The user could also view the top 100 followers of any profile, ranked by the number of followers. These python scripts utilized the VaderSentiment library to get the sentiment scores based on the words in each individual tweet. The Twitter API was also used to pull the tweet content, profile information, followers, and followers’ follower counts. Jinja2 was also used for HTML formatting.


## Misc. Python Projects: 

###### **Naïve Bayes Movie Sentiment Analysis**:  

- Using the Naïve Bayes theorem and movie review data, a python script was used to create a sklearn classifier model that would predict whether the review was positive or negative. K-fold cross-validation was used when training this model. 


###### **Images Project**:  

- Created various python functions to edit .png and .jpg files. Changes include blurring and sharpening photos, mirroring/flipping images, adding and removing noise, and highlighting edges. These functions are housed in a Jupyter Notebook and utilized the PIL Image library. 


###### **Word Similarity Project**:  

- Using the GLOVE word vector dataset, a command-line tool was created using python scripts. This tool will pull the closest five words in the 300-vector space to a word input by the user. Converted .txt file to NumPy for speed improvements.


###### **Enron Email Analysis Prior to 2001 Scandal**: 

- From a collection of 1.5GB of emails, converted (to feather), cleaned, and analyzed the messages to see if any suspicious trends existed in executive employee communications prior to the Enron bankruptcy filing in 2001. The data was cleaned, formatted, and condensed in a python script, while visualizations were generated in a Jupyter Notebook using the MatPlotLib and Skilling libraries. Visualizations include heat maps, bar charts, spring layouts, and Kamada layouts.


###### **Object-Oriented Hash Table Class Creation**
- Created a python class to perform hash table management (utilizing iter(), setitem(), getitem(), contains(), and other functions). This class borrowed code from a word search project to create an object-oriented tool. The previous code also used hash tables, however, did not use an object-oriented approach.

<!---
mtreigelman/mtreigelman is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
