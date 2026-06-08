#  🍔 FoodHub: Food Delivery Demand Analysis
**Author:** Bridgette Davis  
**Tools:** Python · Pandas · Matplotlib · Seaborn · NumPy
---
## 📋 Project Overview
FoodHub is a food aggregator company operating in New York that connects customers 
to multiple restaurants through a single smartphone app. As the city's restaurant 
count grows, FoodHub serves students and busy professionals who rely on food 
delivery for their daily meals.
As the Data Scientist on this project, I analyzed FoodHub's order data to 
understand restaurant demand patterns and identify opportunities to improve 
the customer experience.
---
## 📦 Dataset
| Data Type | Description |
|---|---|
| `order_id`| Unique ID of the order 
| `customer_id`| ID of the customer who placed the order 
| `restaurant_name`| Name of the restaurant 
| `cuisine_type`| Type of cuisine ordered 
| `cost`| Cost of the order 
| `day_of_the_week`| Weekday (Mon–Fri) or Weekend (Sat–Sun) 
| `rating`| Customer rating out of 5 
| `food_preparation_time`| Minutes from order confirmation to pick-up 
| `delivery_time`| Minutes from pick-up to drop-off

---
## ❓ Key Business Questions Answered
1. How many orders were placed in total?
2. Which restaurants received the most orders?
3. Which cuisine types are most popular?
4. How do order volumes differ between weekdays and weekends?
5. What is the distribution of food preparation and delivery times?
6. What is the average cost of orders?
7. How are customer ratings distributed?
8. What percentage of orders are not rated?
9. Which cuisine types take the longest to prepare?
10. What factors most affect the overall delivery experience?
---
## 🔑 Key Findings
- **Top Restaurant:** Shake Shack received the most orders with over 200, ranking #1 out of the top 5 most ordered restaurants
- **Most Popular Cuisine:** American cuisine dominates with nearly 600 orders overall; it is also the most ordered cuisine on weekends with 415 orders
- **Delivery Time:** Most deliveries are completed between 28–29 minutes; the median is 25 minutes with an IQR of 20–28 minutes and no outliers
- **Weekday vs Weekend Deliveries:** Weekend deliveries average 22.5 minutes vs 28.3 minutes on weekdays — weekends are about 6 minutes faster
- **Customer Ratings:** The majority of orders go unrated — 736 orders had no rating given; among rated orders, 5-star ratings are the most common, with no 1 or 2-star ratings recorded
- **Cuisine Variety:** The top 4 cuisines each received between 200–600 orders; all remaining cuisines had fewer than 100 orders each
---
## 💡 Business Recommendations
- **Encourage feedback:** Prompt frequent customers in particular to leave ratings after every order
- **Reward ratings:** Offer discounts or loyalty points to customers who provide feedback to increase rating participation
- **Recognize top restaurants:** Continue offering promotions to high-rated restaurants to maintain quality and encourage them to prompt their own customers to rate
- **Double down on American cuisine:** Maintain a strong selection of American cuisine restaurants as it is consistently the most ordered, especially on weekends
---
## 🛠️ Python Skills Demonstrated
`Pandas` · `Matplotlib` · `Seaborn` · `NumPy` · `Exploratory Data Analysis (EDA)`  
`Data Cleaning` · `Data Visualization` · `Statistical Analysis` · `Business Insights`
---
## 📁 Files
| File | Description 
|---|---|
|[foodhub_python_analysis.ipynb](https://github.com/davisbridg-projects/foodhub-python-analysis/blob/main/foodhub_python_analysis.ipynb) |Full Python notebook with code, visualizations, and analysis 

