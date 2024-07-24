# Netflix Data Exploration and Visualization

![Netflix Logo](https://upload.wikimedia.org/wikipedia/commons/0/08/Netflix_2015_logo.svg)

## About

Netflix, Inc. is an American streaming service and production company, offering a vast library of films and TV series, including Netflix Originals. As of March 31, 2023, it has 232.5 million paid memberships in over 190 countries. Founded by Reed Hastings and Marc Randolph in 1997, Netflix started as a DVD rental business before shifting to streaming in 2007, transforming home entertainment.

### Dataset Features

- **Show_id**: Unique ID for every Movie / TV Show
- **Type**: Identifier - A Movie or TV Show
- **Title**: Title of the Movie / TV Show
- **Director**: Director of the Movie
- **Cast**: Actors involved in the movie/show
- **Country**: Country where the movie/show was produced
- **Date_added**: Date it was added on Netflix
- **Release_year**: Actual Release year of the movie/show
- **Rating**: TV Rating of the movie/show
- **Duration**: Total Duration - in minutes or number of seasons
- **Listed_in**: Genre
- **Description**: The summary description

## Insights and Analysis

### Statistical Summary

- The dataset contains 12 features with a mix of alphanumeric data.
- There are null values in director, cast, country, date_added, duration columns
- The Data is imputed by filling it with 'Unknown Column_Name'

### Data Visualization

#### 📊 Content Distribution

- ***70:30*** ratio of Movies to TV shows in Netflix
- By this inference we can say that Netflix's primary focus is on Movies when compared to TV Shows

#### 🕚 Duration of Movies and TV Shows on Netflix

**Movies:**
- **Common Duration:** Most movies have durations between 100 to 150 minutes.
- **Median Length:** The median movie duration is around 125 minutes.
- **Range of Durations:** Movie lengths typically range from 50 to 200 minutes.
- **Longer Outliers:** There are outliers with durations up to just below 300 minutes.

**TV Shows:**
- **Short Duration Trend:** Most TV shows have a short duration in terms of seasons, as indicated by the concentration of data points within the lower end of the scale.
- **Variability:** The whisker extending upwards and the outliers above it show that while most shows have fewer seasons, there are some with significantly more.
- **Outliers:** The presence of outliers suggests that a few TV shows have many more seasons than the typical range.


#### 📅 Movies and TV Shows Added Over Time

**Movies:**
Almost around 1400 movies were added to Netflix platform in the 2019 from covid
- **Steady Growth:** There’s a consistent increase in the number of movies added each year.
- **Significant Jump:** A notable surge occurs between 2014 and 2016.
- **Peak Volume:** The highest number of movies added is in 2020, between 1200 and 1400.

**TV Shows:**
Almost around 1424 shows were added to Netflix platform in the 2019 from covid
- **Increasing Trend:** The number of shows added each year shows an upward trend.
- **Significant Growth:** There is a noticeable increase in the number of shows added, especially between 2014 and 2016.
- **Peak in 2020**: The year 2020 marks the highest point, with the number of shows added reaching a peak.


### Directors and Actors

#### 🎬 Directors with the Most Movies or TV Shows



- **Rajiv Chilaka** is the most appeared Director on Netflix


#### 🕺 Most Appeared Actors



- **Anupam Kher** is the most appeared actor on Netflix

### Regional Insights

#### 🌎 Overview of Movies and TV Shows by Country


- Strategic content production in the USA and India reflects Netflix's focus on key subscriber growth markets.
- Diverse global content curated from countries like the UK, Canada, France, Japan caters to varied cultural preferences.
- Regional viewing preferences shape Netflix's content strategies, e.g., India prefers movies while South Korea leans towards TV shows.

#### 🌍 Comparison between Movies and TV Shows by Country


This graph references that there are wide range of countries which uses Netflix as Streaming service all around the world.
- The **United States** stands out with the highest count, indicating a strong preference for Netflix in the region.
-**India’s Position:** India follows as the second-highest, showcasing its significant market for Netflix.
- **Top European Countries:** The United Kingdom, France, and Germany are among the top European countries using Netflix.

### Release Strategies

#### 📅 Best Month to Launch a TV Show / Movie


**Movies:**
- It is best time to release movies is in July month, Worst time to release movie is in February
- It suggests that January, April, July and December are the most popular months for movie releases, with the highest number of movies coming out. This could be due to summer breaks and holiday seasons, which are prime times for moviegoers.

**TV Shows:**
- Best week to release TV Shows is in December, Worst week to release TV Shows is in February
- This chart can be useful for networks to plan their release schedules and for advertisers
- The data suggests that certain months are preferred for releases, which could be due to seasonal viewer availability or industry trends.

#### 📆 Best Week to Launch

**Movies:**
- **Peak Release Times:** Significant peaks around week 40 and week 52 suggest popular times for movie releases, likely coinciding with holidays or festivals.
- **Release Distribution:** The distribution of releases varies throughout the year, with some weeks seeing more activity than others.
- **End-of-Year Surge:** There’s a notable increase in releases towards the end of the year, which may be strategic for award considerations or holiday viewership. This shows that there is seasonality, to get maximum viewership from the audience if Netflix releases movies.

**TV Shows:**
Best week to release TV show is 27th week of year, Next best week to release TV show is 31st week of year,
Worst week to release TV Show is 10th week
- Significant peaks in the 27th week and 31st week of the year with a reach of 80 shows in that week.
- The graph shows fluctuations in the number of TV shows released each week, indicating seasonal trends or strategic release timing by networks.


### Content Ratings

#### 🍿 Distribution of Content Ratings


Most the content in Netflix is mature content requires under the guidance of adults or parents with a rating TV-MA
- **Mature Content:** The “TV-MA” rating has the highest count, indicating a significant amount of content intended for mature audiences.
- **Variety of Ratings:** A range of ratings from “G” for general audiences to “NC-17” for adults only shows the diversity of content available.
- **Family-Friendly Options:** Ratings like “TV-G” and “PG” suggest the presence of content suitable for younger viewers and kids.

### **Business Recommendations:**

### 1.   **Best Release Time**
- **Monthly**

   - The high-quality content should be released during the months of *January, July, August, October, and December* could lead to increased viewer interest and engagement as these months have historically seen higher upload counts, which shows higher demand
- **Weekly**

    - The *first week* of each month can be designated as a "Featured Release Week," where the platform introduces a major TV shows or movie. Subsequently, the other three week period can be promoted with the movies which are released in the first week.
- Most of the movies or TV shows are released on **Friday**

### **2.   Lag Difference**
-  Acquiring most recent movies and shows will increase the audience viewership as there is more mean lag difference in the top 10 most produced countries. This could cater to the audience's preference for up-to-date TV shows and movies.

- While creating content, take into consideration the popular actors/directors
for that country. Also take into account the director-actor combination which
is highly recommended

### **3.   Localise the content**
- Popularity of TV shows in Asian countries, particularly South Korea and Japan, Netflix should increase its investment in producing and acquiring Asian TV shows.
- Significant investment in content production in the USA and the emphasis on India, Netflix should continue to focus on these markets.
- 
### **4.Regional Focus:**
- Tailor content offerings based on regional preferences and cultural nuances.

### **5.Content Discovery and Personalization:**
- **Improved Recommendation Algorithms:** Enhance personalized recommendations by leveraging machine learning and user behavior data.
- **Content Tags and Metadata:** Improve content tagging and metadata to enhance search accuracy and content discovery.

### **6.User Experience and Interface:**
- **Responsive Design:** Optimize the platform for various devices (mobile, web, smart TVs) to provide a seamless experience.
- **Intuitive Navigation:** Simplify menus, categories, and search filters for easy content exploration.

### **7.Streaming Quality and Performance:**
- **High-Quality Streaming:** Invest in robust infrastructure to deliver smooth streaming experiences even during peak hours.
- **Adaptive Bitrate Streaming:** Implement adaptive streaming to adjust quality based on users’ internet speeds.
- **Diverse Genres:** Explore a wide range of genres to cater to varied audience interests.


