<h1>Airline Customer Satisfaction Project Summary</h1>

In this project, I aimed to analyze a dataset from an airline passenger satisfaction survey to identify the key factors that influence passenger satisfaction and develop a predictive algorithm.</br>
The dataset contains 22 features related to various aspects of the flight experience, including passenger demographics, travel details, and satisfaction levels with services like inflight wifi, seat comfort, food and drink, cleanliness, and more. The target variable, **Satisfaction**, classifies whether passengers were satisfied, neutral, or dissatisfied with their experience.

During the data analysis, I observed a strong correlation between arrival and departure delays, though both contained some missing values. To handle this, I combined the delay variables, which helped manage the null values. Additionally, I found that delays, while present, had a minimal impact on overall satisfaction, as the airline generally arrived on time. In fact, including delay data in the model resulted in only a 0.03 percentage point difference in performance when compared to a model without delay-related features.

I also identified outliers in the dataset, but surprisingly, removing them lowered the model's performance. This suggested that these outliers might provide valuable insights, helping the algorithm understand how to deal with unusual data points.

Ultimately, I developed a Random Forest algorithm that achieved a high accuracy rate of 96.47%, successfully predicting passenger satisfaction based on the available features.
