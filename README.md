# **Airbnb Listings EDA: New York 2024**  

## **Overview**  
This project performs **Exploratory Data Analysis (EDA)** on New York Airbnb listings to identify trends and patterns in rental data. The analysis is powered by **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn** for data cleaning, visualization, and extracting actionable insights for both guests and hosts.  

---

## **Objective**  
The primary objectives of this project are:  
1. Analyze **room types, pricing, and availability** across neighborhoods.  
2. Examine **host behavior** and listing trends.  
3. Detect **outliers** in pricing data.  
4. Provide **recommendations** for guests and hosts based on findings.  

---

## **Dataset Overview**  
The dataset includes **20,765 entries** and **22 features**, such as:  
- **id**: Unique identifier for each listing  
- **name**: Title of the Airbnb listing  
- **host_name**: Name of the host  
- **neighborhood_group**: Borough where the listing is located  
- **latitude/longitude**: Geographical coordinates of the listing  
- **price**: Nightly rental price  
- **room_type**: Type of accommodation (e.g., entire home, private room)  
- **reviews_per_month**: Average number of reviews per month  
- **availability_365**: Number of available days per year  

---

## **Workflow**  

### **1. Data Cleaning**  
- **Missing data handling**: Addressed null values in `price`, `neighborhood`, and `beds`.  
- **Data type correction**: Converted `last_review` to **datetime**.  
- **Outlier removal**: Capped prices above **$1,000** to mitigate skewed results.  

### **2. Exploratory Data Analysis (EDA)**  
1. **Room Type Distribution**:  
   - Bar charts show that **entire homes/apartments** dominate the market.  

2. **Neighborhood Group Analysis**:  
   - **Manhattan** has the highest average rental prices.  

3. **Availability Trends**:  
   - Heatmaps reveal correlations between `price`, `availability_365`, `reviews`, and `beds`.  

4. **Price Distribution**:  
   - Histograms show most listings fall between **$50-$300**.  

5. **Host Listings**:  
   - Boxplots identify hosts with multiple listings, indicating professional hosting.  

6. **Review Behavior**:  
   - Pair plots examine the relationship between reviews, price, and availability.  

---

## **Data Visualizations**  
- **Pair Plot**: Displays correlations between `price`, `availability`, and `reviews`.  
- **Heatmap**: Shows relationships among numerical features.  
- **Histograms & Boxplots**: Detect pricing outliers.  
- **Bar Charts**: Visualize room type and neighborhood distribution.  

---

## **Key Insights**  

1. **Price Trends**:  
   - **Manhattan** has the highest rental prices, with **entire homes/apartments** costing more than private/shared rooms.  

2. **Room Type Preference**:  
   - Entire homes dominate, but **private rooms** offer more budget-friendly options.  

3. **Outliers**:  
   - Listings priced above **$10,000** were filtered out to prevent skewed analysis.  

4. **Availability Patterns**:  
   - High-availability listings tend to have lower prices and more reviews, suggesting positive guest experiences.  

5. **Host Behavior**:  
   - A trend of **professional hosting** is evident, with hosts managing multiple listings.  

---

## **Recommendations**  

### **For Guests**  
- Choose listings with **high availability** and positive reviews for a better experience.  
- Consider **private rooms** in Brooklyn for cost-effective options compared to Manhattan.  

### **For Hosts**  
- Increase **availability** and **response rates** to attract more bookings.  
- Adjust pricing to remain competitive within your borough.  

---

## **Conclusion**  
This analysis provides valuable insights into New York’s Airbnb market, helping both guests and hosts make data-driven decisions.
---
