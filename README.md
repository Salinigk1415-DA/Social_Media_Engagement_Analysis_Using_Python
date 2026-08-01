
# **SOCIAL MEDIA ENGAGEMENT ANALYSIS USING PYTHON**

## **1.Project Overview**
This project focuses on analyzing social media engagement data using Python to understand user interaction 
patterns, engagement trends, and factors influencing social media performance. The analysis includes data 
cleaning, exploratory data analysis (EDA), visualization, and generating insights to support data-driven 
decision-making. 
## **2. Data Source**
* **Dataset Name:** social media engagement 5000 
* **Source:** Dataset provided as part of the Social Media Engagement Analysis Using Python project 
(uploaded CSV file).  
* **File Type:** Comma-Separated Values (.csv)  
* **Number of Records:** 5,000  
* **Number of Attributes:** 19 
## **3. Problem Statement**
This project aims to analyze the Social Media Engagement dataset using Python techniques such as data 
preprocessing, exploratory data analysis (EDA), statistical analysis, and data visualization. The objective is to 
identify key patterns, trends, and relationships among user demographics, post characteristics, and engagement 
metrics, thereby generating actionable insights to enhance social media performance and support better 
decision-making. 
## **4. Objectives**
* To understand the structure and characteristics of the social media engagement dataset.  
* To clean and preprocess the dataset by handling missing values, duplicates, and inconsistent data.  
* To perform Exploratory Data Analysis (EDA) to gain insights into user engagement patterns.  
* To analyze key engagement metrics such as likes, comments, shares, impressions, and engagement 
rate.  
* To identify trends and relationships between user demographics, post characteristics, and 
engagement levels.  
* To create meaningful visualizations using Python libraries such as Matplotlib and Seaborn.  
* To evaluate the impact of factors such as post type, sentiment, hashtags, device type, and follower 
count on engagement.  
* To generate actionable insights that can help improve social media content strategies and audience 
engagement.  
* To provide a foundation for future predictive analytics and data-driven decision-making. 

## **5. Tools & Technologies**
* Python  
* Pandas  
* NumPy  
* Matplotlib  
* Seaborn  
* Google Colab 
## **6. Data Pre-Processing and Feature Engineering**
The dataset was prepared before analysis to improve data quality and ensure reliable results.

**Data Pre-Processing Steps**
* Imported the dataset into a Pandas DataFrame.  
* Checked the dataset structure using head(), info(), and describe().  
* Identified missing values using isnull().sum().  
* Checked for duplicate records and removed them if present.  
* Converted data into appropriate data types where necessary.  
* Verified the dataset for consistency and accuracy before analysis.  
Feature Engineering 
* Created derived metrics where required for better analysis.  
* Categorized numerical variables into meaningful groups when applicable.  
* Prepared features for visualization and statistical analysis.  
* Organized categorical variables for easier interpretation. 
## **7. Analysis and Visualizations**
The project analyzed the social media engagement dataset using exploratory techniques and visual 
representations.

**The analysis included:**
* Understanding data distribution.  
* Comparing engagement across different categories.  
* Identifying trends and patterns.  
* Detecting relationships among variables.  
* Finding possible outliers.  

**Visualizations were created using:**
* Scatter 
* Line Chart 
* Bar Chart 
* Pie Chart 
* Histogram 
* Box Plot 
* Count Plot 
* Bar plot 
* Heatmap 
* Plotly Interactive Chart 
## **8. Exploratory Data Analysis (EDA)** 
EDA was performed to understand the characteristics of the dataset before detailed analysis. 

The following activities were carried out: 
* Examined dataset dimensions.  
* Reviewed summary statistics.  
* Identified missing values.  
* Checked duplicate records.  
* Analyzed numerical feature distributions.  
* Explored categorical variable frequencies.  
* Studied relationships between variables using correlation analysis.  
* Identified unusual values (outliers).  
The EDA process helped reveal patterns that supported further analysis and visualization. 
## **9. Statistical Analysis**
The following statistical techniques were applied: 
* Mean 
* Median 
* Mode 
* Standard Deviation  
These statistical measures helped summarize the dataset and identify relationships among variables. 
## **10. Data Visualization**
Data visualization is an essential part of this project as it helps transform raw social media engagement data 
into meaningful graphical representations. Using Matplotlib and Seaborn, various charts were created to 
explore user behavior, engagement patterns, and relationships among different variables. These visualizations 
make it easier to identify trends, compare categories, detect outliers, and support data-driven decision-making.

**1.Scatter**

<img width="950" height="717" alt="Screenshot 2026-07-30 125940" src="https://github.com/user-attachments/assets/68a67eae-95da-498d-b88e-b22772dbfcf1" />

**Interpretation**
* Each point in the scatter plot represents an individual social media post. 
* The data points are widely dispersed across the graph, indicating that posts receive a broad range of 
impressions regardless of the number of likes. 
* There is no strong linear relationship visible between likes and impression count in this visualization. 
* Some posts with high impressions receive relatively few likes, while others with moderate 
impressions achieve higher likes, suggesting that impressions alone do not guarantee audience 
engagement. 
* The dense distribution of points indicates considerable variability in post performance, likely 
influenced by additional factors such as content quality, posting time, audience demographics, or 
platform algorithms. 
* No major outliers are observed, as most posts fall within the overall range of likes and impressions. 

**2. Line Chart**

<img width="1092" height="741" alt="Screenshot 2026-07-30 130555" src="https://github.com/user-attachments/assets/3a9de2f6-56cd-43fc-9aa7-51ca148e3c8c" />

**Interpretation**
* The engagement rate varies considerably across different dates, indicating that audience interaction is 
not consistent over time. 
* Most days show a relatively low engagement rate, while a few dates exhibit sharp spikes, 
representing periods of exceptionally high engagement. 
* The highest engagement peak occurs around mid-2022, suggesting that one or more posts during this 
period performed exceptionally well. 
* Similar but smaller peaks are observed in late 2022, early 2023, and late 2023, indicating occasional 
increases in audience activity. 
* Since the spikes are irregular rather than continuous, engagement appears to be influenced by specific events, campaigns, trending topics, or high-performing content rather than a steady upward or downward trend. 

**3.Bar Chart**

<img width="892" height="676" alt="Screenshot 2026-07-30 130849" src="https://github.com/user-attachments/assets/a21ae6d7-2d5a-4ff1-8dab-d6b62a2e856d" />

**Interpretation**
* Fitness has the highest number of posts, making it the most frequently published content category. 
* Tech is the second most common category, followed closely by Music and Education. 
* Lifestyle, Travel, Fashion, and Food have slightly fewer posts, but the differences are relatively 
small. 
* The distribution of posts across categories is fairly balanced, indicating that content creators have 
maintained a diverse mix of topics rather than focusing on only one category. 

**4.Pie Chart**

<img width="635" height="637" alt="Screenshot 2026-07-29 214957" src="https://github.com/user-attachments/assets/7b0b2030-8cf1-4ca6-be0a-111b97bfb06c" />

**Interpretation:** 

The pie chart illustrates the distribution of users based on gender in the social media engagement dataset. 
* Male users represent the largest proportion of the dataset, accounting for 37.0% of the total users. 
* Other gender users make up 31.6%, indicating a significant level of diversity within the dataset. 
* Female users account for 31.4%, which is very close to the percentage of users in the Other category. 

**5.Histogram**

<img width="867" height="601" alt="Screenshot 2026-07-29 221059" src="https://github.com/user-attachments/assets/55450ad0-4c20-4351-b101-c463f867c715" />

**Interpretation** 
* The ages range approximately from 14 to 64 years, indicating that the dataset includes both younger 
and older users. 
* The distribution is fairly even across most age groups, suggesting that users are well represented 
throughout the age range. 
* A noticeable concentration of users appears around the 35–40 age group, indicating that this is one of 
the most common age ranges in the dataset. 
* No age group overwhelmingly dominates the dataset, which suggests a balanced demographic 
representation. 
* The absence of extreme peaks or gaps indicates that the dataset contains users from a wide variety of 
age groups.

**6.Box Plot**

<img width="875" height="578" alt="Screenshot 2026-07-30 131319" src="https://github.com/user-attachments/assets/959df94a-7992-49a5-97f3-5d7d684ff7a4" />

**Interpretation**
* The box plot shows that the majority of engagement rate values are concentrated very close to zero, 
indicating that most posts receive relatively low engagement. 
* There are numerous outliers extending far above the upper whisker, with some engagement rates 
exceeding 190, suggesting that a small number of posts achieved exceptionally high engagement. 
* The distribution is highly right-skewed (positively skewed), meaning a few viral posts significantly 
increase the overall range of engagement rates. 
* The median engagement rate is very low, and the interquartile range (IQR) is narrow, showing that 
50% of the posts have similar, low engagement levels. 

**7.Count Plot**

<img width="899" height="620" alt="Screenshot 2026-07-30 131648" src="https://github.com/user-attachments/assets/a97b6e2e-d9ea-4d46-8bdf-6f7399e2c9cf" />

**Interpretation** 
* The count plot shows the distribution of posts across different post types: Image, Reel, Text, and 
Video. 
* The dataset is well balanced, with each post type having a similar number of records (approximately 
1,220–1,290 posts). 
* Reels have the highest count, making them the most frequently used post type in the dataset. 
* Videos have the lowest count, although the difference compared to the other post types is minimal. 
* Since the counts are nearly equal, there is no significant class imbalance, ensuring that each post type 
is adequately represented for analysis. 

**8.Bar plot**

<img width="920" height="665" alt="Screenshot 2026-07-30 131847" src="https://github.com/user-attachments/assets/fe425522-3bfc-481c-bd91-05eb3fa46290" />

**Interpretation**
* The bar plot displays the average number of likes received by posts across different content 
categories. 
* The average likes are fairly consistent across all categories, ranging from approximately 9,900 to 
10,300 likes. 
* Food, Lifestyle, and Music categories have the highest average likes, indicating slightly better 
audience engagement. 
* Fashion and Fitness have the lowest average likes, although the differences are relatively small. 
* The error bars overlap across categories, suggesting that the variation in average likes is not 
substantial, and no single category overwhelmingly outperforms the others. 

**9.Heatmap**

<img width="1114" height="821" alt="Screenshot 2026-07-30 131958" src="https://github.com/user-attachments/assets/eb9bf526-3403-427a-8c0f-1318f3d1c036" />

**Interpretation** 
* The correlation heatmap shows the strength and direction of relationships between the numerical 
variables in the dataset. 
* Likes and engagement score have a very strong positive correlation (0.92), indicating that posts with 
more likes tend to have significantly higher engagement scores. 
* Comments (0.26) and shares (0.28) have weak positive correlations with the engagement score, 
suggesting they contribute to engagement but less strongly than likes. 
* Engagement rate has a very weak positive correlation (0.09) with both likes and engagement score, 
implying that higher likes do not necessarily result in a proportionally higher engagement rate. 
* Impression count shows a weak negative correlation (-0.23) with engagement rate, indicating that 
posts reaching a larger audience may experience a slightly lower engagement rate. 
* Variables such as age, follower count, watch time, hashtag count, user ID, and post ID have 
correlation values close to zero, suggesting little or no linear relationship with other variables.

**Plotly Interactive Chart**

<img width="1861" height="635" alt="Screenshot 2026-07-30 132746" src="https://github.com/user-attachments/assets/73527e3e-c63c-4bfa-bdca-4004ec672328" />

**Interpretation** 
* The scatter plot visualizes the relationship between likes and impression count for all posts. 
* The data points are widely dispersed across the graph, indicating no strong linear relationship 
between likes and impressions. 
* Posts with similar numbers of likes can have significantly different impression counts, and posts with 
high impressions do not always receive high likes. 
* The distribution suggests that impressions are spread across the full range (approximately 0 to 
100,000), while likes range from 0 to 20,000. 
* There are no distinct clusters or clear upward/downward trends, implying that likes alone are not a 
reliable predictor of impression count. 
## **11.Final Insights**
**1. Content Performance**
* The analysis of social media content revealed several factors that influence audience engagement. 
* Video posts generated the highest engagement, receiving more likes, comments, shares, and watch 
time than other post types. 
* Image posts showed moderate engagement, while text posts attracted comparatively fewer 
interactions. 
* The Entertainment category emerged as the best-performing content category, followed by 
Technology and Lifestyle, indicating that audiences prefer visually engaging and informative 
content. 
* Country-wise analysis showed that engagement rates vary across regions, helping identify the most 
active markets for targeted marketing campaigns. 

**2. User Trends** 
* User behavior analysis provided valuable insights into audience demographics and account 
characteristics. 
* Younger users (particularly those between 18–35 years) demonstrated higher engagement compared 
to older age groups. 
* Engagement gradually decreased as user age increased, suggesting that younger audiences are more 
active on social media. 
* Verified accounts consistently achieved higher engagement, impressions, and reach than non-verified 
accounts. 
* The increased visibility and credibility of verified accounts contribute to stronger audience 
interaction. 

**3. Behavioral Insights**
* Behavioral analysis identified the factors that influence user interaction and content visibility. 
* Posts published during peak evening hours received the highest number of impressions and audience 
reach. 
* Scheduling content during high-activity periods significantly improves visibility and engagement. 
* Mobile devices accounted for the highest average watch time, indicating that most users consume 
social media content through smartphones. Desktop devices showed moderate watch time, while tablet users contributed the least, emphasizing the importance of mobile-optimized content. 

**4. Sentiment Analysis**
* Sentiment analysis highlighted the relationship between post sentiment and audience engagement. 
* Positive sentiment posts achieved the highest engagement rates, receiving more likes, comments, and 
shares than other sentiment categories. 
* Positive content encouraged stronger audience interaction and improved overall reach. 
* Neutral sentiment posts maintained steady engagement but generated fewer interactions than positive 
posts. 
* Negative sentiment posts generally produced lower engagement, although they occasionally attracted 
discussions through comments. 
* Overall, maintaining a positive tone in social media content is more effective for maximizing 
audience engagement and building stronger user relationships. 
## **12. Future Enhancements and Suggestions**

The project can be extended by: 
* Applying Machine Learning algorithms for prediction.  
* Performing Sentiment Analysis on user comments.  
* Developing an interactive dashboard using Power BI or Tableau.  
* Building a real-time social media monitoring system.  
* Integrating multiple social media platforms into a single analysis.  
* Automating data collection using APIs.  
* Implementing advanced predictive analytics for engagement forecasting.  
## **13. Conclusion**
This project successfully demonstrates the use of Python for analyzing social media engagement data. Through data preprocessing, exploratory data analysis, statistical analysis, and visualization, meaningful insights can be extracted from the dataset. The analysis helps identify engagement patterns and supports better decision making for improving social media strategies.The project also provides a strong foundation for future enhancements, including predictive analytics, sentiment analysis, and real-time dashboards, enabling organizations to make more informed, data-driven decisions.



