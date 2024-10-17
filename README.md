# OLS Regression Analysis on Video Views

## Overview

This project focuses on conducting an Ordinary Least Squares (OLS) regression analysis to understand the factors influencing the number of views on a video. The analysis aims to identify how specific features such as the weekend factor, character presence, and ad impressions impact video views.

## Dataset

The dataset comprises 80 observations and includes the following features:

- **Views_show**: The dependent variable representing the number of views on the video.
- **Weekend**: A binary variable indicating whether the video was shown on a weekend.
- **Character_A**: A binary variable indicating the presence of a specific character in the video.
- **Ad_impression_million**: The number of ad impressions (in millions) associated with the video.

## Methodology

- Conducted an OLS regression analysis using the statsmodels library.
- Evaluated the model's performance based on R-squared, adjusted R-squared, and the significance of each predictor using p-values.

## Key Results

- **R-squared**: The model explains approximately 80.3% of the variance in video views.
- **Significant Predictors**:
  - **Weekend**: Positively impacts views (p-value < 0.001).
  - **Ad Impression (million)**: Also shows a significant positive effect (p-value < 0.001).
  - **Character_A**: Not statistically significant (p-value = 0.167).


## Conclusion

The analysis highlights that the day of the week and ad impressions significantly influence video views. Understanding these factors can help optimize content strategies and advertising approaches for greater viewer engagement.

## Requirements

To run the analysis, ensure you have the following libraries installed:

- `pandas`
- `statsmodels`
- `numpy`

## How to Run

1. Clone the repository.
2. Install the required libraries.
3. Run the analysis script.


