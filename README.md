# Data Analysis Report

## 1. Correlation Heatmap
A heatmap was generated to visualize the correlation between numerical features. The following insights were observed:
- Strong correlations between certain variables indicate possible redundancy or multicollinearity.
- Features like **Distance (km)** and **TARGET (delivery time)** show a moderate correlation, suggesting that longer distances may lead to increased delivery times.
- Other environmental factors, such as **temperature** and **humidity**, show weaker correlations with delivery time, indicating a lesser direct impact.

## 2. Pairplot Analysis
A pairplot was used to examine the relationships between **TARGET, Distance (km), temperature, humidity, Delivery_person_Age, and Delivery_person_Ratings**.
- **TARGET vs. Distance (km)**: A noticeable upward trend indicates that as the distance increases, delivery time tends to increase.
- **TARGET vs. Delivery_person_Age**: Minimal correlation suggests that the age of the delivery person does not significantly impact delivery time.
- **TARGET vs. Delivery_person_Ratings**: Little to no correlation suggests that customer ratings of delivery personnel do not directly affect delivery time.

## 3. Distribution and Boxplot Analysis
Histograms and boxplots were used to visualize the distributions of **TARGET, Distance (km), and Temperature**.
- **TARGET Distribution**: The delivery time appears to have a right-skewed distribution, indicating that most deliveries occur within a certain time range, but some take significantly longer.
- **Distance (km) Distribution**: The data suggests that most deliveries occur within shorter distances, with a few long-distance outliers.
- **Temperature Distribution**: This feature appears normally distributed, implying consistent temperature variation.

Boxplots reveal:
- The presence of **outliers in TARGET and Distance**, which may represent unusually long delivery times or long-distance orders.

## 4. Scatterplot Analysis
Scatterplots were generated to explore relationships between:
- **Distance (km) vs. TARGET**: A clear positive correlation shows that higher distances generally lead to longer delivery times.
- **Temperature vs. TARGET**: The plot does not show a strong trend, suggesting that temperature does not significantly impact delivery time.

## **Key Insights:**
1. Distance is the strongest predictor of delivery time (**TARGET**), with longer distances leading to longer delivery times.
2. Environmental factors (temperature, humidity) have minimal direct impact on delivery time.
3. There are significant **outliers** in both delivery time and distance, which might indicate extreme cases such as traffic congestion or special circumstances.
4. Customer ratings of delivery personnel and delivery person’s age do not show a strong relationship with delivery time.

This report provides a focused summary based on the generated figures, revealing key data trends and relationships.

