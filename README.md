# OLS Regression Analysis on Video Views

## Overview

This project aims to analyze the factors influencing the number of views for a digital media company’s show. After an initial success, the show experienced a decline in viewership, prompting the company to understand what went wrong. Using Ordinary Least Squares (OLS) regression, this analysis explores the key variables—such as weekends, character presence, and ad impressions—to provide insights into the drivers of video views.

## Business Problem

A digital media company, similar to platforms like Voot, Hotstar, or Netflix, launched a new show that garnered strong initial viewership. However, the viewership declined significantly after some time, and the company is unsure about the reasons for this drop. They need insights into which factors are driving engagement and which are not, so they can optimize future episodes and marketing efforts to improve and sustain viewer numbers.

## How the Problem Is Addressed

To tackle this issue, an OLS regression model was built using several features that might influence video views, such as:

- **Weekend Effect**: Whether showing videos on weekends impacts views.
- **Character Presence**: Whether the appearance of a specific character affects audience engagement.
- **Ad Impressions**: The impact of ad exposure on viewer numbers.

By analyzing these factors, the model helps the company understand which elements correlate strongly with higher or lower viewership, providing actionable insights to guide content strategies and advertising decisions.

## Dataset

The dataset includes 80 observations with the following key variables:

- **Views_show**: The dependent variable, representing the number of views on each video.
- **Weekend**: A binary variable indicating whether the video was shown on a weekend.
- **Character_A**: A binary variable indicating the presence of a specific character in the video.
- **Ad_impression_million**: The number of ad impressions (in millions) related to the video.

## Methodology

- The analysis was conducted using the Ordinary Least Squares (OLS) regression method via the statsmodels library.
- The model performance was evaluated based on metrics such as R-squared, adjusted R-squared, and the significance of each predictor (p-values).
- The focus was on identifying key factors that explain video views and offer insights into the decline in viewership.

## Key Results

- **R-squared**: The model explains approximately 80.3% of the variance in video views, indicating a strong fit.
- **Significant Predictors**:
  - **Weekend**: A significant positive impact on video views (p-value < 0.001), suggesting that episodes shown on weekends draw more viewers.
  - **Ad Impression (Million)**: Significant positive effect (p-value < 0.001), showing that higher ad impressions are strongly correlated with increased viewership.
  - **Character_A**: No statistically significant impact (p-value = 0.167), indicating that the presence of a specific character doesn’t necessarily drive more views.

## Business Impact

- **Optimizing Content Strategy**: The significant weekend effect highlights an opportunity to schedule future episodes during high-engagement times, such as weekends, to maximize viewer turnout.
- **Improving Advertising Strategies**: The strong positive impact of ad impressions shows that targeted and increased ad exposure can lead to higher viewership, suggesting a need for better advertising allocation for underperforming episodes.
- **Character Relevance**: Since the specific character’s presence is not statistically significant, it suggests that focusing on content diversity or promoting other engaging elements may be more effective in improving viewership.

Overall, these insights can guide the company’s decision-making on content scheduling, advertising, and promotional strategies, helping to sustain viewership and recover from the observed decline.

## Conclusion

The OLS regression analysis provides valuable insights into what drives video views, emphasizing the importance of timing (weekends) and ad exposure. These findings help the media company optimize future content releases and advertising efforts, improving viewer engagement.

## Requirements

To run the analysis, ensure you have the following libraries installed:

- `pandas`
- `statsmodels` 
- `numpy`
- `python`


