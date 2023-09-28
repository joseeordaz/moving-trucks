# moving-trucks

MA611 Group Project: Moving Trucks
Contributors: Ria, Jose, Samantha
Date: 02/05/2023

Introduction:
The City of Boston’s Moving Truck Permits dataset serves as a crucial window into understanding the flow of trucks within Boston. Through rigorous analysis of this dataset, we aim to uncover notable patterns and insights, which could be instrumental for urban planning and transportation decisions.

Objective:
Our primary aim is to provide comprehensive insights into the best modeling techniques suitable for this dataset. These insights will guide researchers and policymakers in making well-informed decisions regarding transportation planning and resource allocation within the city.

Dataset Source:
The dataset was obtained from the Open Data Portal of the City of Boston. This portal is a rich resource, offering access to various datasets managed and maintained by the city. Our focus revolves around the Moving Truck Permits dataset, which provides details about the permits issued for moving trucks across different time periods.

Key Findings:
There's a distinct seasonality observed with permit issuance.
A consistent growth trend is seen in the number of permits.
The pandemic in 2020 noticeably affected permit issuance, with a marked dip observed.
Models and Analysis:
We employed several time series models for our analysis:

Holt-Winters Exponential Smoothing (with GARCH improvement)
ARIMA (with GARCH improvement)
Time Series Linear Model (TSLM)
Seasonal Naive Prediction Strategy (SNAIVE)
Neural Network Autoregression (NNAR)
Post analysis, the HW-GARCH, ARIMA-GARCH, and NNAR models stood out in terms of performance, showcasing promising results for forecasting.

Recommendations:
For future forecasts and policymaking:

Consider HW-GARCH, ARIMA-GARCH, or NNAR due to their demonstrated efficiency.
Utilize the entire dataset rather than splitting it to maximize forecast accuracy.
Regularly refresh the models and cross-check predictions with real-world data for consistency.
Conclusion:
Through our study, we have presented pivotal insights and forecasting techniques beneficial for researchers and policymakers in Boston. The findings from our analysis can significantly influence transportation strategies, subsequently enhancing urban planning and residents' quality of life.
