### Capstone Project
### Group 8

**Members**
1. Faith Watene wanguufaith@gmail.com/0797921974
2. Amani Wanene /0711833383
3. Evans Oyugi /0794604048
4. Catherine Wangui jangkatrina@gmail.com/0727151179
   
# Disease-Outbreak-Tracking

### 1. Business Understanding

***Disease Detection System***

*1.1 Business Overview*

This detection system leverages social media data to track outbreaks of influenza and tuberculosis, two significant public health threats with widespread respiratory impacts. By analyzing real-time posts for early signs of disease clusters, the system enables WHO and health agencies to identify potential outbreaks quickly. This proactive approach aims to reduce disease spread, improve response times, and ultimately lower morbidity and mortality rates.

*1.2 Problem Statement*

Early detection of influenza and tuberculosis outbreaks is critical, but official reporting often lags behind the initial spread. Social media data could provide an early warning system, but requires AI-powered analysis to identify and track disease trends before they become full-blown epidemics.

*1.3 Objectives*

Our main objective is early detection of potential influenza and tuberculosis outbreaks using real time twitter data. Our other objectives include;

1. Track the spread patterns of these diseases by monitoring symptom-related 
   keywords and geospatial data from social posts.  
2. Identify high-risk areas for outbreaks before they are officially reported.  
3. Develop predictive models to forecast the trajectory of potential outbreaks.  
4. Provide early alerts to public health organizations and government agencies to 
   enable faster response and intervention.

 *1.4 Proposed Solutions*
   
 1. Collect real-time social media data from Twitter using Twibot: and keyword- 
    based filtering.
2. Apply natural language processing (NLP) techniques to detect mentions of 
   disease symptoms, concerns, and outbreak-related keywords.
3. Conduct sentiment analysis to identify posts indicating fear, panic or growing 
   anxiety around potential outbreaks.
4. Leverage machine learning models like SVMs and neural networks to classify 
   social posts as related to disease outbreaks or not.
5. Utilize anomaly detection algorithms to identify unusual spikes in outbreak- 
   related keywords and phrases.
6. Map the geospatial and temporal data to visualize disease spread patterns and 
   high-risk clusters.
7. Validate social media-derived insights against official health reports to 
   ensure accuracy.
8. Develop predictive models to forecast outbreak trajectories and build an 
   automated alert system for public health authorities.

***Metrics of Success***

Accuracy 0.90

Recall 0.90

**StakeHolders**

1. World Health Organization (WHO)
  Global health agency responsible for coordinating pandemic preparedness and 
  response

2. National/Regional Public Health Organizations
  Disease control centers, epidemiology departments in countries/regions

3. Emergency Response Agencies
  Disaster management authorities, emergency medical teams

4. Government Policymakers
  Health ministers, legislators responsible for public health policies

5. Healthcare Providers
  Hospitals, clinics, and other medical facilities that need early warning

6. Public Health Researchers and Epidemiologists
  Academics and analysts studying disease trends and mitigation strategies

7. The General Public
  Citizen stakeholders who benefit from faster outbreak response and containment


### 2. Data Understanding
Our data originates from twitter and was scrapped using Twibot. We have a total of 20 columns and below is the description.

id - Unique identifier for each tweet entry in the dataset.

tweetText - Text content of the tweet.

tweetURL - URL link to the original tweet on Twitter.

type - The kind of social media post(tweets in our case)

tweetAuthor - The person/ organisation that posted the tweet.

handle - The username of the tweet author.

geo - The provided geographical location related to the tweet.

mentions - Other twitter users mentioned in the tweet.

hashtags - The hashtags used in the tweet.

replyCount - The number of replies a tweet has.

likeCount - The number of likes a tweet has.

views - The number of views a tweet has.

bookmarkCount - The number of times a tweet has been bookmarked.

createdAt - The day and time the tweet was published.

allMediaURL - The URL to all media content related to the tweet.

videoURL - The URL for only videos related to the tweet.

source_file - The name of tje file a tweet data entry originated from.

combined_timestamp - The timestamp cmbining both the date and time of processing or entry.


### 3. Data Preparation

Data preparation focuses on cleaning and preprocessing the raw social media data. This includes:

 - **Text Preprocessing:** Removing noise, normalizing text, filtering for 
     keywords.
   
 - **Handling Missing Values:** Ensuring data consistency and filling gaps as 
     needed.
   
 - **Keyword Filtering:** Focusing on disease-related terms that may signal 
     outbreaks.
   
This step ensures that the data is structured, relevant, and ready for model input.

### 4. Modelling

Various machine learning models are applied to analyze the cleaned data. Models are evaluated based on their accuracy in detecting outbreak-related posts, as well as their ability to identify trends over time. Techniques such as natural language processing (NLP) are used to interpret text data and classify posts according to potential outbreak relevance.

### 5. Evaluation

The model's performance is evaluated through metrics such as accuracy, precision, and recall, helping to determine its effectiveness in detecting early warning signs. Additionally, insights such as detected trends and potential high-risk locations are analyzed to gauge the model's practical value for public health applications.

### 6. Deployment

This pproject is deployed here (https://disease-csv-visual.vercel.app/)

### 7. How to use this Notebook

1. Clone this repository.
   
2. Install any required dependencies listed in the notebook.
   
3. Run each cell sequentially to follow the project's workflow, from data preparation to model evaluation.

 ### 8. Conclusion

This project demonstrates how AI-driven analysis of social media data can support public health initiatives by providing early warning signals of disease outbreaks, potentially enabling faster and more effective response efforts.
  





















