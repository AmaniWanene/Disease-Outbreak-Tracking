### Capstone Project
### Group 8

**Members**
1. Faith Watene
2. Amani Wanene
3. Evans Oyugi
4. Catherine Wangui
   
# Disease-Outbreak-Tracking

### Business Understanding

***Disease Detection System***

*Business Overview*

This detection system leverages social media data to track outbreaks of influenza and tuberculosis, two significant public health threats with widespread respiratory impacts. By analyzing real-time posts for early signs of disease clusters, the system enables WHO and health agencies to identify potential outbreaks quickly. This proactive approach aims to reduce disease spread, improve response times, and ultimately lower morbidity and mortality rates.

*Problem Statement*

Early detection of influenza and tuberculosis outbreaks is critical, but official reporting often lags behind the initial spread. Social media data could provide an early warning system, but requires AI-powered analysis to identify and track disease trends before they become full-blown epidemics.

*Objectives*

Our main objective is early detection of potential influenza and tuberculosis outbreaks using real time twitter data. Our other objectives include;

1. Track the spread patterns of these diseases by monitoring symptom-related 
   keywords and geospatial data from social posts.  
2. Identify high-risk areas for outbreaks before they are officially reported.  
3. Develop predictive models to forecast the trajectory of potential outbreaks.  
4. Provide early alerts to public health organizations and government agencies to 
   enable faster response and intervention.

 *Proposed Solutions*
   
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

F1 Score for Disease Outbreak Classification: Measures the model's balance between precision and recall in detecting outbreaks.

**Target: F1 Score > 0.85**

Precision of Outbreak Detection: Evaluates the model's accuracy in identifying actual outbreak-related data among all detected cases, minimizing false alarms.

**Target: Precision > 0.90**

AUC-ROC (Area Under the Receiver Operating Characteristic Curve): Indicates the model's ability to distinguish between outbreak and non-outbreak data with high reliability.
**Target: AUC-ROC > 0.90**

Accuracy in Predicting Outbreak Magnitude: Reflects the model’s ability to accurately forecast the size or scale of an outbreak, essential for effective resource allocation.

**Target: Accuracy > 80%**

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


### Data Understanding
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


### Data Preparation






















