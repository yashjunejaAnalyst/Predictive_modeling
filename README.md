# Predictive_modeling
ShowTime OTT Data Analysis Business Report

**Project Title:**

Driving Factors for First-Day Viewership in OTT Content Using Linear Regression

**Context**

An over-the-top (OTT) media service is a media service offered directly to viewers via the internet. The term is most synonymous with subscription-based video-on-demand services that offer access to film and television content, including existing series acquired from other producers, as well as original content produced specifically for the service. They are typically accessed via websites on personal computers, apps on smartphones and tablets, or televisions with integrated Smart TV platforms.

Presently, OTT services are at a relatively nascent stage and are widely accepted as a trending technology across the globe. With the increasing change in customers' social behavior, which is shifting from traditional subscriptions to broadcasting services and OTT on-demand video and music subscriptions every year, OTT streaming is expected to grow at a very fast pace. The global OTT market size was valued at $121.61 billion in 2019 and is projected to reach $1,039.03 billion by 2027, growing at a CAGR of 29.4% from 2020 to 2027. The shift from television to OTT services for entertainment is driven by benefits such as on-demand services, ease of access, and access to better networks and digital connectivity.

With the outbreak of COVID19, OTT services are striving to meet the growing entertainment appetite of viewers, with some platforms already experiencing a 46% increase in consumption and subscriber count as viewers seek fresh content. With innovations and advanced transformations, which will enable the customers to access everything they want in a single space, OTT platforms across the world are expected to increasingly attract subscribers on a concurrent basis.

**Objective:**

To identify and quantify the key drivers influencing first-day content viewership on the ShowTime OTT platform using linear regression. The goal is to optimize content release strategies, marketing spend, and viewer engagement based on predictive insights.

**Approach:**

**1.)	Data Understanding & Loading:**

o	Analyzed a dataset with key features: visitors, ad_impressions, major_sports_event, genre, dayofweek, season, views_trailer, and views_content.

o	Verified structure: 8 variables per content item.

**2.)	Exploratory Data Analysis (EDA):**

o	Univariate Analysis: Identified skewed distributions and popular genres (e.g., Comedy, Sci-Fi).

o	Bivariate Analysis: Evaluated how features like ad_impressions, trailer_views, dayofweek, and season relate to views_content.

**3.)	Feature Engineering:**

o	Converted categorical variables (genre, dayofweek, season) using encoding techniques.

o	Checked for duplicates and missing values (none found).

o	Performed outlier detection (none found in views_content).

**4.)	Model Building:**

o	Applied Ordinary Least Squares Linear Regression.

o	Split data into training and testing sets.

o	Evaluated model using RMSE, MAE, R², and MAPE.

o	Tested model assumptions (linearity, normality, homoscedasticity).

**5.)	Model Diagnostics:**

o	Final model explained ~78% of variance (R²) and had MAPE ~9% on the test set.

o	Residuals were normally distributed.

o	Some non-linearity was detected, suggesting potential for further feature transformation

**Outcome**

**Key Predictors Identified:**

•	Positive influence: ad_impressions, trailer_views, certain genres like Thriller, Sci-Fi, Drama.

•	Negative influence: major_sports_event (strongly reduces viewership).

