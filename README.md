# Digital Marketing
- Insights using real-time User-Browsing &amp; User-Purchasing data


# Purchase Behaviour of Users in Online Retail

### Introduction:

- This data is about the users who actually purchased some items after browsing the website and visited certain parts of website

### Problem Statement:
- Customer segmentation is the problem of uncovering information about a firm’s customer base, based on their interactions with the business.
- In most cases this interaction is in terms of their purchase behavior and patterns. We explore some of the ways in which this can be used.

### Approach Taken:
The approach taken is to divide the customer base in different segments, which will help in the understanding of following:
- Customer Understanding.
- Target Marketing.
- Finding Latent Customer Segments.
- Higher Revenue.

For the Customer Segmentation I used **Clustering** Technique.

Here is one of the plots:
![download](https://user-images.githubusercontent.com/36000962/75844814-36757d80-5dfd-11ea-9b42-5e4538c2bdb5.png)

#### The steps include:
- Exploratory Data Analysis
- Deciding the Clustering Strategy:
- Recency
- Frequency
- Monetary Value
- Data Cleaning
- Data Pre-processing.
- K-means Clustering
- Cluster Analysis
- Cluster Description.

### Interpretation of Results:

#### Initial analysis tells us that not all the users who browsed, purchased items.
- Some of them bought.
- Others didn't


- We see the maximum sale is from 22 to 3 hours (11 PM to 3 AM.)
- Comparatively less sales from 4:00 AM to 1:00 PM.
- The customers purchasing during 10:00 PM to 12:00 AM buy more costly items than the users purchasing from 12:00 AM to 3:00 AM.
- We have 41,008 unique customers but almost 10% of total sales are contributed by only 1000 customers (based on the cumulative percentage aggregation in the preceding output).
- The next thing we want to determine is how many unique items the firm is selling.
- Looking at 3-D plot of Recency, Frequency and Monetary values:
- People who buy with a higher frequency and more recency tend to spend more based on the increasing trend in Monetary value with a corresponding increasing and decreasing trend for Frequency and Recency, respectively.
- By looking at the boxplots of different clusters we see the difference in their Amount of purchase with maximum, minimum and median amount.

