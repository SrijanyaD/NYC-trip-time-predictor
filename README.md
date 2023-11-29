# NYC-trip-time-predictor


Introduction:

"I had an engaging project where the goal was to build a model predicting the total ride duration for New York City taxi trips. Our primary dataset, released by the NYC Taxi and Limousine Commission, contained essential information like pickup time, geographic coordinates, passenger count, among other variables."


Data Exploration:

"To start, I delved into data exploration. I discovered there were approximately 1.4 million unique IDs in the training dataset. I then conducted univariate analysis, examining attributes such as passengers, vendors, distance, and trip duration. Following this, I moved to bivariate analysis, seeking relationships, patterns, and correlations between various features like trip duration per hour, vendor, and passenger count."


Feature Engineering:

"Next, I focused on feature engineering. Given the manageable number of dimensions, I began with feature selection. Employing backward elimination technique, I identified the most impactful features. Subsequently, I split the data into training and testing sets. Then, I performed feature extraction using Principal Component Analysis (PCA), refining the input features for model training."


Modeling Approach:

"With the selected and extracted features in hand, I initially applied multiple linear regression, aiming to explain the relationship between the continuous dependent variable (ride duration) and multiple independent variables like passenger count, vendors, and distance. However, the evaluation revealed a poor mean squared value and low variance score."

Improvements using XGBoost:

"To address this, I pivoted to using the XGBoost regressor. This decision led to a significant improvement in the RMSE score upon training the tuned XGBoost regressor. This model performed notably better, showcasing enhanced predictive capabilities."


Key Learnings:

"Throughout this project, I covered various aspects of the machine learning development cycle, from comprehensive data exploration, feature engineering techniques like backward elimination and PCA, to model selection and fine-tuning, ultimately improving the predictive performance significantly."
Conclusion:
"In summary, this project was a rewarding journey that taught me the importance of thorough data analysis, feature engineering, and the significance of choosing appropriate models for achieving better predictive outcomes in machine learning tasks

