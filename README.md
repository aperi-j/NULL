# PHASE_04_PR0JECT
Title
A Time Series Analysis of Real Estate Prices in Top 5 Zip Codes"

Background
Real estate investment is a lucrative and dynamic industry that requires careful analysis and decision-making. The fictional real estate investment firm is seeking guidance on identifying the top 5 zip codes for investment opportunities. To address this question, historical data from Zillow Research is utilized. The dataset contains information on various attributes, including RegionID, RegionName, City, State, Metro, SizeRank, CountyName, and value (real estate prices).
Project overview
In these project we shall seek to do the following :

Load the dataset
Understand the dataset
Choose our target variable.
Prepare the dataset (Example : Cleaning the dataset , checking for multicollinearity)
Encode our categorical variables
Make several models
Evaluate our models
Use our models for prediction
Come up with relevant findings.
Business Understanding
Real estate investment is a lucrative and dynamic industry that requires careful analysis and decision-making. The fictional real estate investment firm is seeking guidance on identifying the top 5 zip codes for investment opportunities. To address this question, historical data from Zillow Research is utilized.

Main Objective
The main objective of this project is to identify the top 5 zip codes that offer the best investment potential in terms of real estate prices. By analyzing historical trends and patterns, the project aims to provide actionable insights to the investment firm, enabling them to make informed decisions on where to allocate their resources.
Specific Objectives
Analyze Historical Data: The project involves analyzing the historical data of real estate prices across different zip codes. This includes understanding the trends, patterns, and fluctuations in property values over time.

Identify Promising Zip Codes: Using the analysis of historical data, the project aims to identify the zip codes that have shown consistent growth, stability, or potential for future appreciation. These zip codes are considered the most favorable for investment.

Consider Location Factors: In addition to the historical performance, the project also takes into account location-specific factors such as city, state, and metro. This information helps assess the overall desirability and attractiveness of the investment opportunities.

Evaluate Market SizeRank: The SizeRank attribute provides insights into the relative size and competitiveness of the real estate market in each zip code. This factor helps gauge the potential opportunities and risks associated with investing in a particular area.

Data Understanding
The dataset contains information on various attributes, including RegionID, RegionName, City, State, Metro, SizeRank, CountyName, and value (real estate prices). Our dataset is the Zillow Housing Dataset which was sourced from Zillow Research Page.

Column Name Description
RegionID -This is unique Id for the Regions
SizeRank -This is the ranking done based on the size of the region
RegionName - This field contains the zip code of the region.
RegionType- Type of region is Zip.
StateName - State
City - This column provide the specific City Name of Housing Data
Metro - This provide the name of the metro city around that region
County Name - This is the county name for that region
Months Column - These columns contains the prices of region for every month
Libraries
PYTHON- Programming language
PANDAS- Exploratory data analysis
SEABORN- Visualization
NUMPY - Numerical computing and data analysis
MATPLOTLIB- Visualization
STATSMODELS-statistical analysis and modeling
SCIKIT LEARN- machine learning
SCIPY- scientific computing
MATH- basic mathematical operations
Exploratory data analysis
image.png

image.png

image.png

image.png

         ROI = Net Investment Gain/Cost of Investment x 100
image.png

Modelling
ACF & PACF

image.png

image.png

Forecasts
image.png

image.png

image.png

[ ]

Findings
After performing time series analysis on the 10 zip codes and forecasting total returns for up to three years, we reccomend the company to invest in the following 3 zipcodes:

81611 - Location: Aspen, CO (R.O.I - 132.378817)

10021 - Location: New York, NY (R.O.I - 111.795552)

34102 - Location: Naples, FL (R.O.I - 7.605307)

As for the other 6 zip codes, they are not fit for investement given the negative returns.

Recommendations
We recommend investment in the following regions :

81611 - Location: Aspen, CO

10021 - Location: New York, NY

34102 - Location: Naples, FL

This is because these regions have a positive returns of investments unlike the other regions.

[ ]

Colab paid products - Cancel contracts here
