## Real-time tracking solution

---
## INTRODUCTION 

We are developing a real-time tracking solution to be used by small businesses online or offline using the embedded Google map for ease in tracking real-time goods as opposed to the alert messages received before getting your orders or goods. In this regard, a survey questionnaire was drafted to get potential users to hear their experiences while waiting to get their products, their pain points and to know the way forward.  

The aim of the tracking solution project is to solve the issues with logistic problems by allowing users to track their shipments/packages at any given time. So they do not always need to liaise with their suppliers all the time so we analyzed the dataset and we got some insights from it. 

It will be hosted on a temporary website

---

## APPROACH TO THE PROJECT 

We took the following steps  

Collection & Compilation of Data: Data was collected through the primary method of collection by  sharing the link to the questionnaire on various E-channels such as Instagram, WhatsApp, Twitter, and one-on-one communication 

Google Colab was used for analysis using Python language 

---
## STEPS

Importing necessary libraries on Google Colab using Python 

Read in the dataset 

Get the full information on the dataset using the necessary syntax ( .info(), .head(), . tail(), .shape(), .describe() etc 

Data cleaning: (Dealing with missing values, dropping unnecessary columns, Tackling RealTime_Update, Regrouping nationality column, etc 

EDA (Exploratory Data Analysis) 

Build a Model using linear regression 

Make predictions and get the accuracy 

---
## UNDERSTANDING THE DATASET
We used various methods to understand our data set. Some of these methods are aspects, but not limited to:

The .head() method: This was used to call out the first five entries of the data set
The .tail() method: was used to call the last five entries of the data set so as to know how the data set looks like.
The .shape() method: was used to know the number of rows and columns in the data set. It shows that this data set contains 192 rows and 16 columns
The .info() method is used to know the concise summary of the data set including the columns that allow for null values and those that do not, the number of entries per column, and data types.
We went ahead to check for null values and duplicates. No duplicate was found. However, feedback and feature requests had 27 null values each while real-time tracking usage had just 2 null values.

---
## STATISTICAL SUMMARY OF DATA SET
For "Tracking_Ease", the mean is approximately 3.27, and for "Satisfaction_Level", it is approximately 3.19. This suggests that, on average, respondents rated tracking ease slightly higher than satisfaction level. Both means are close to the midpoint of the rating scale, This suggests that, on average, respondents provided moderate ratings for tracking ease and satisfaction level.

For both columns, the 25th, 50th, and 75th percentiles are relatively close, suggesting that the data is evenly distributed across the range of values.

from our descriptive statistics, using the average (mean) majority of respondents find tracking their packages and satisfaction level moderately easy, suggesting the process might be manageable but there is still room for improvement.

enhancing tracking systems would improve user satisfaction with their entire experience

When both satisfaction level and ease of tracking packages have the same mean value, it suggests a strong correlation between these two variables. Users who find tracking easy are likely to be satisfied, and vice versa. This correlation underscores the importance of addressing both ease of tracking and overall satisfaction simultaneously. Improvements in tracking systems should aim to enhance user experience and satisfaction with the entire shipping process. Continuous monitoring of both metrics is essential to identify and address emerging issues promptly, maintaining high levels of customer satisfaction over time.

---
## ANALYSIS

### DEMOGRAPHY

. The pie chart shows there are more males spread in this data set which carries a weight of 56% while the female and others carries the remaining 47% cumulative.
. The respondents for this study have a high response rate from the 18-35 age group and the lowest response rate from the 65 and above age group.
This implies that our analysis will be based on mostly Gen Z and millennials which are our target audience.

### DEMOGRAPHY VS DELIVERY SERVICE USAGE
The bar charts above show the delivery usage by age, gender, and Nationality.

Age: The chart shows that the age group 18-35 uses delivery services more than other age groups.

Gender: The female gender came up as the highest users of delivery services. The reason could be that women tend to have more shopping needs than the other genders; Males and others.

Nationality: Although this sample is not suitable enough to represent this population, more Nigerians who were the majority of the respondents use delivery services more than other nationalities.

### REAL TIME VS DEMOGRAPHY

By age: Most of the respondent between 18-35 confirm that they are willing to use a real-time trackage solution if in existence. However, respondents who fall in the senior citizens category are not interested in the real-time tracking solution. This could be due to their preferences and might prefer traditional shopping to online shopping or ordering.

By gender: More females are interested in the real-time tracking solution than males are interested. On the contrary, some more non-interested females are interested in the real-time tracking solution than that of non-interested males.

Nationality: most Nigerians claim that they have used a real-time tracking system for their orders/shipments. On the contrary, more Nigerians have not used the real-time tracking solution for their orders/shipments.

### TRACKING EASE VS SATISFACTION

A correlation coefficient of 0.515 indicates a moderately strong positive correlation between "Tracking_Ease" and "Satisfaction_Level".

This means that as the ease of tracking increases, satisfaction levels tend to increase as well.

However, it's important to note that correlation does not imply causation, so while these variables may be correlated, there could be other factors influencing satisfaction levels.

### FREQUENCY OF DELIVERY USAGE
Most respondents rarely or almost never use a delivery service for their orders or packages. even in this era when e-commerce is at its boom, it is surprising to see that such is the case.

However, we still have respondents who use delivery services multiple times a month which indicates, not entirely, the availability of demand.

### CHALLENGES
The above bar chart showing the distribution of challenges indicates that most people experience delay (87 from the response) in deliveries and not so much experience package misplacement.

Communication issues are also part of the issues experienced after delay. There are also people who have never experienced any challenge while using a delivery service.

### SATISFACTION VS REAL-TIME UPDATE IMPORTANCE
A correlation coefficient was used for this analysis and it indicates that there appears to be a very weak positive relationship between Satisfaction_Level and 
RealTime_Update_Importance, but it's not substantial enough to draw strong conclusions.

### MAP INTEGRATION WILLINGNESS
Even without prediction, most of our respondents are willing to use this tracking solution as they see it as a solution worthy of solving their problems.

---
## CONCLUSION AND RECOMMENDATIONS
# FINDINGS
With the research done on this project, we find that Trackage is important to fulfill user needs in the
logistics and delivery industry, if done right.
Research shows that users have an overwhelmingly positive response to the possibility of this functionality.
It is worth noting that the majority of the issues users testing Trackage had were connected to not having backend support, so it stands to reason that with backend support the functionality will be ready to go to
market.

# FUTURE WORK
A user could create an order by going to a logistics website that is integrated with trackage snap goods, upload, and send a dispatch to pick up the goods process which will show on the user's side. Then when processed the status changes to in-transit when time and date are set.

# RECOMMENDATIONS
Recommendations for further research include;
How to make the app more intuitive
How to secure data on the app
The app should be clear on how users can track their packages

---
## THE END
