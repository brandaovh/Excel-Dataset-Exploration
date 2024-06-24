# UNDER CONSTRUCTION

# Airbnb Listings - Toronto

## Project Overview
This project was conducted as part of the "Math for Data Analytics" class and involved a comprehensive dataset analysis of Airbnb listings in Toronto, focusing on descriptive and inferential statistical analysis using MS Excel.

The dataset used for this analysis is stored in the file `datasetExploration.xlsx`. It contains the original and cleaned datasets, data dictionary, pivot tables, graphs and statistical analysis. Additionally, the final report summarizing the analysis findings can be found in the file `finalReport.docx`. Feel free to explore these files.

## Data Source
The dataset was obtained as a csv file from [Inside Airbnb](https://insideairbnb.com/) website and includes detailed information about accommodations in Toronto as of January 8th, 2024.

## Motivation
The goal is to leverage expertise in the travel and tourism industry to extract meaningful insights and analyze the implications of the 5-star review system in the digital space.

## Techniques Used
- Log normalization
- Univariate descriptive statistics
- Risk Ratio/Odds Ratio
- Chi-Square Test
- ANOVA
- Correlation
- Linear regression

## Key Findings

- **Review Score Variance**: Listings with fewer than 20 reviews showed significant variance in review scores, skewing results. Excluding these listings from the analysis improved the score distribution, enhancing the accuracy of guest satisfaction analysis.

- **Superhost Performance**: Superhosts consistently achieved higher ratings across all categories, including overall score, accuracy, cleanliness, and communication. This highlights the value of the Superhost status as an indicator of higher quality listings.

- **Impact of Superhost Status**: The influence of Superhost status on review scores was most pronounced in overall rating, accuracy, cleanliness, and communication. However, weaker effects were observed in check-in, location, and value categories, suggesting that these aspects may be influenced by other factors beyond a host's control.

- **Response Times and Communication Scores**: Hosts with faster response times correlated significantly with higher communication scores. This indicates that responsiveness is a critical factor in guest satisfaction, emphasizing the importance of timely communication.

- **Neighborhood Influence**: Variability between neighborhoods exceeded within-neighborhood variance, suggesting that the choice of neighborhood significantly influences Airbnb ratings. This finding underscores the importance of location in guest satisfaction and listing performance.

- **Correlations Among Review Categories**: Strong positive correlations were found among accuracy, cleanliness, communication, value, and overall rating scores. This suggests that improvements in one area could positively affect perceptions in others, highlighting the interconnected nature of guest experiences.

- **Challenges in Predictive Modeling**: Due to the complex relationships among review categories, a linear regression model may not be suitable for accurately predicting overall review scores. This suggests the need for more sophisticated models to capture the nuances of guest satisfaction.

## Lessons Learned

- **Challenges with Scalar Data**: Performing statistical analysis using scalar data, such as 5-star reviews, due to issues like grade inflation. This can skew the distribution, making traditional statistical methods assuming normality less reliable.

- **Excel's Limitations with Large Numbers**: While importing data, I encountered issues with Excel's handling of large numbers, where some values were converted from numbers to text. This occurs because Excel only stores up to 15 significant digits in a number, converting any digits beyond the fifteenth place to zeros. Fortunately, this limitation did not impact my data analysis, as the affected variable was nominal and could be classified accordingly.

- **The Utility of Power Query for Data Cleaning**: Although not covered in this specific class, later I discovered the benefits of using Power Query for data cleaning. Power Query offers a robust way to track changes and steps taken to modify the dataset, providing a transparent and reproducible data cleaning process. If I could change something on my assignment, would be the inclusion of Power Query.

- **The Importance of the Null Hypothesis in Statistical Analysis**: Focusing on the null hypothesis in statistical analysis is crucial because it ensures rigor and reliability in drawing conclusions from data. It also helps to reduce the amount of bias and guards against premature conclusions.