# Data Analysis Report

## Food Time Dataset BIAnalysis

### Dataset Information
- **File Name:** Food_Time_Data_Set_BIAnalysis.csv
- **Format:** CSV

### Data Analysis
#### Distribution of Numerical Features
- Delivery persons' ages range between **20-40 years**, and most have ratings above **4.5**.
- Temperature ranges from **15-30°C**, with a peak at **23-24°C**.
- Humidity peaks at **60-70%**, while precipitation remains below **0.5**.
- Distance (km) has a **maximum frequency between 0-35 km**.
- Delivery time (Target) ranges from **5-150 minutes**, with most deliveries occurring within **25-50 minutes**.

#### Unique Values of All Features
- Examined unique values across all dataset features.

### Visualization
#### Correlation Matrix
- 11 pairs of features show correlation.
- 4 pairs have correlation values close to **±0.5**, and 3 pairs are close to **1**.

#### Pairplot of Correlated Features
- **Positive correlation:** Target (Delivery Time) vs. Distance.
- **Negative correlation:** Temperature vs. Humidity.

#### Histograms & Boxplots
- Most delivery times are **below 50 minutes**.
- Most distances are **below 20 km**.
- Temperatures mostly fall between **20-25°C**.
- Data shows outliers in some distributions.

#### Scatterplots
- **Distance vs. Target:** Positive correlation with outliers.
- **Temperature vs. Target:** Higher delivery times when temperature is below **15°C** or above **25°C**.

#### Frequency Count of Categorical Features
- Most frequent **order type:** Snacks, followed by Drinks and Meals.
- Most frequent **traffic level:** High, followed by Moderate.
- Most common **weather conditions:** Clear sky, haze, mist.

### Insights
#### Common Type of Order and Vehicle
- **Most ordered food type:** Snacks.
- **Most common delivery vehicle:** Motorcycle.

#### Relationship between Target and Traffic
- **Higher traffic levels increase delivery time.**
- **Very high traffic:** Delivery time can exceed **140 minutes**, with a median of **60 minutes**.

#### Relationship between Distance and Target
- **Longer distances correlate with longer delivery times.**
- Most frequent deliveries occur within **10-30 km**, taking **20-80 minutes**.

#### Impact of Weather on Delivery Time
- **Overcast clouds:** Median delivery time is **60 minutes**.
- **Clear sky:** Median delivery time is **40 minutes**, with many outliers.
- **Light and moderate rain:** Few data points available.

#### Influence of Delivery Person Age and Rating on Target
- No strong correlation between **age or rating** and delivery time.
- **Age range:** Mostly between **20-40 years**.
- **Ratings:** Mostly between **4-5 stars**.
- Delivery time is typically between **10-80 minutes** for all age groups and ratings.

---
This report summarizes the key findings from the dataset, providing insights into delivery time, influencing factors, and trends in food delivery services.
