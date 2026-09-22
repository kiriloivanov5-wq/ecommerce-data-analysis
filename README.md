# E-Commerce Data Analytics & Statistical Hypothesis Testing

## 📌 Project Description
This project focuses on conducting a comprehensive analysis of e-commerce platform data. The study involved extensive Exploratory Data Analysis (EDA), the creation of pivot tables, the assessment of correlations, and statistical hypothesis testing regarding differences between user segments.

## 🛠 Technology Stack
* **Python** — primary language for analysis
* **Pandas / NumPy** — preprocessing, data aggregation, and pivot table creation
* **SciPy / Statsmodels** — correlation analysis (Pearson) and statistical testing (T-test, Mann-Whitney, ANOVA)
* **Matplotlib / Seaborn** — visualization of distributions, time series, and heatmaps

## 📊 Key Stages and Analysis Results

### 1. Exploratory Data Analysis (EDA) and Business Questions (Item 4)
Analysis was conducted on sales geography, products, and traffic channels:
* **Geography:** Identified the top 3 continents and top 5 countries by sales volume and number of orders.
* **Product Categories:** Determined the top 10 most profitable categories. Compared sales structures in key countries against the overall market.
* **Devices and Traffic:** Calculated sales shares broken down by device types/models and acquisition channels.
* **User Behavior:** Examined email verification and newsletter subscription rates among registered users.

### 2. Pivot Tables
Pivot tables were created to organize multidimensional data:
* Distribution of session counts by **traffic channel** and **device type**.
* Sales volume by **top 10 product categories** and **top 5 countries**.
* Registered users by operating system and browser.

### 3. Statistical Analysis of Relationships (Correlation Analysis)
Linear and non-linear relationships between key metrics were evaluated:
* **Sessions vs. Sales:** Correlation between daily session counts and total sales was assessed. P-values ​​were checked to confirm statistical significance.
* **Traffic Channels and Categories:** Correlation of sessions across different traffic sources was examined.

### 4. Statistical Analysis of Group Differences
Statistical tests were used to compare samples:
* **Registered vs. Unregistered Users:** Daily sales in both groups were analyzed.
* **Traffic Channel Comparison:** Differences in session counts across various sources were evaluated.
* **Europe vs. America (Organic Traffic):** The hypothesis regarding the difference in the share of organic traffic sessions between regions was tested.


