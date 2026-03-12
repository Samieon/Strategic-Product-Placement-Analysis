Strategic Product Placement Analysis Using Data 
(Team Id : 6997f7cd05fb21b07dca8319)
Visualization 
1. Introduction 
Retail businesses depend on effective product placement strategies to increase sales and 
enhance the shopping experience. The position of items within the store, such as in aisles, 
near the entrance, or on end-cap displays, can strongly affect customers' buying decisions.
The aim of this project is to study how product positioning, customer demographics, 
pricing, and promotional methods influence overall sales performance. By examining retail 
data and presenting it through visual dashboards, companies can make informed decisions 
about optimal product placement to boost revenue.
This project utilizes Tableau for creating data visualizations and Flask to develop a web￾based interface that showcases interactive dashboards and storytelling features.
2. Problem Statement 
Retail stores frequently face challenges in identifying the most effective product placement 
strategy that increases sales while maintaining an efficient store layout.
The main issue addressed in this project is:
How do product placement, pricing strategies, and customer demographics affect 
product sales in retail stores?
Understanding this connection can help businesses:
• Enhance product placement strategies
• Improve product visibility for customers
• Adjust and optimize pricing strategies
• Boost overall sales performance
3. Objectives of the Project
The primary objectives of this project include:
1. To examine the connection between product placement and the quantity of sales 
generated.
2. To study how customer demographics affect purchasing patterns and decision-making.
3. To analyze the difference between competitor pricing and the store’s pricing strategy.
4. To assess how promotional activities influence product sales performance.
5. To create interactive dashboards and visual stories that provide meaningful business 
insights.
6. To incorporate the analytics dashboard into a web application developed using Flask.
Project objectives describe the specific outcomes a project aims to achieve and help guide 
the team toward measurable results and better decision-making.
4. Data Collection 
The dataset used in this project was obtained from Kaggle, a well-known platform for public 
datasets
Dataset Source: 
https://www.kaggle.com/datasets/amitvkulkarni/impact-of-product-positioning-on-sales
The dataset contains retail sales information including: 
• Product category
• Product position in store 
• Sales volume 
• Price
• Competitor price
• Consumer demographics 
• Promotion status
• Seasonal demand
• Foot traffic 
This dataset helps analyze how different retail factors influence product sales.
5. Data Description 
The dataset contains several important variables used for analysis.
Column Name Product 
Product Category Category of product (Clothing, Electronics, Food)
Product Position Placement location (Aisle, End-cap, Front of Store)
Price Price of product in store
Competitor Price Price of the same product at competitor store
Sales Volume Number of units sold
Promotion Whether promotion was applied
Consumer Demographics Customer group (Families, Seniors, Young Adults, Students) 
Seasonality Seasonal demand factor 
Foot Traffic Customer traffic in store
7. Data Cleaning and Preparation 
Before visualization, the dataset was cleaned and prepared for analysis. 
The following steps were performed:
1. Handling Missing Values
The dataset was inspected to identify missing or incomplete values. Missing values were either 
removed or replaced with appropriate values. 
2. Data Formatting 
Columns such as Price and Sales Volume were converted into numerical formats to allow accurate 
calculations. 
3. Categorization Categorical variables such as: 
• Product Position
• Product Category
• Consumer Demographics were organized properly for easier visualization.
were organized properly for easier visualization. 
4. Data Validation 
The dataset was checked for duplicate records and inconsistent entries to ensure data 
accuracy. 
After cleaning, the dataset was ready for visualization. 
7. Data Visualization Using Tableau 
To analyze the dataset effectively, several visualizations were created using Tableau. 
These visualizations were later combined into a dashboard for interactive exploration. 
Visualizations Created 
1. Average Sales Volume vs Product Category 
 o Shows which category sells the most. 
2. Consumer Demographics vs Sales Volume 
 o Displays which customer groups purchase the most. 
3. Promotion vs Product Category 
 o Shows the impact of promotions on product sales. 
4. Foot Traffic vs Average Sales Volume 
 o Demonstrates how store traffic influences sales. 
5. Competitor Price vs Product Price 
 o Helps analyze pricing strategy against competitors. 
6. Product Category vs Price Distribution 
 o Shows price comparison across categories. 
7. Product Placement vs Sales Volume 
 o Evaluates the impact of location inside store. 
8. Dashboard Development 
A Tableau Dashboard was created by combining multiple visualizations into one interface. 
The dashboard allows users to: 
• Filter by product category 
• Filter by consumer demographics 
• Analyze sales trends 
• Compare pricing and promotions 
• Understand product placement performance
The dashboard provides a comprehensive view of sales insights. 
9. Story Creation in Tableau 
To present insights clearly, a Tableau Story was developed. 
The story explains the findings step by step. 
Story Points 
Story Point 1: Product Category vs Average Sales Volume 
The first story point analyzes the average sales volume across different product categories. 
The categories analyzed are: 
• Clothing 
• Electronics 
• Food 
From the bar chart visualization, the following observations were made: 
1660
1680
1700
1720
1740
1760
1780
1800
1820
1840
Clothing Electronics Food
Avg Sales
Product Category Avg Sales
Clothing 1830.1
Electronics 1748.6
Food 1727.7
Insight
Clothing products generate the highest average sales volume compared to electronics and 
food.
• Clothing products recorded the highest average sales volume of 1830.1. 
• Electronics products recorded an average sales volume of 1748.6. 
• Food products recorded the lowest average sales volume of 1727.7. 
This indicates that clothing products are the most profitable category in terms of sales 
performance. 
Retailers can use this insight to: 
• Allocate more shelf space for clothing products 
• Place clothing items in highly visible store locations 
• Focus marketing strategies on high-performing categories 
Story Point 2: Product Position vs Sales Volume and Foot Traffic 
The second story point examines how product placement and store foot traffic affect sales 
volume. 
The visualization shows different product positions: 
• Aisle 
• End-cap 
• Front of Store 
Along with different foot traffic levels: 
• High 
• Medium 
• Low 
The analysis reveals: 
• Products placed in high foot traffic areas generate higher sales. 
• Front of Store placement with high traffic produced one of the highest sales volumes 
(1811.7). 
• Aisle placement also shows strong performance with sales around 1900.5 in low 
traffic conditions, indicating product demand also affects results. 
This demonstrates that store layout and customer movement patterns influence purchasing 
behavior. 
Retailers should strategically place popular products in high traffic zones to maximize 
visibility and sales. 
Story Point 3: Product Placement Impact on Sales (Treemap Analysis) 
The third story point visualizes the relationship between product category and store 
placement using a treemap chart. 
Each rectangle represents a combination of: 
• Product Category 
• Store Position 
Key insights include: 
• Clothing products placed at the front of the store recorded the highest sales volume (1923.7). 
• Clothing products placed in aisles also perform strongly with sales around 1832.8. 
• Electronics products show moderate sales across positions. 
• Food products show comparatively lower sales performance. 
The treemap clearly highlights that product placement significantly influences sales 
performance. 
Placing high-demand products in prime store locations such as the front of the store 
increases sales potential. 
10. Web Application Development Using Flask 
To make the dashboard accessible through a web interface, a Flask web application was 
developed. 
The web application contains the following sections: 
• Home Page 
• About Section 
• Tableau Dashboard Integration 
• Tableau Story Integration 
• Contact Page 
The Tableau dashboard and story were embedded using Tableau Public embed code. 
This allows users to interact with the analytics directly on the website. 
11. Key Findings 
1. From the Tableau Story analysis, the following conclusions were drawn: 
2. Clothing is the highest performing product category. 
3. Product placement significantly affects sales performance. 
4. Front-of-store placement improves product visibility and customer engagement. 
5. Foot traffic plays an important role in driving retail sales. 
These insights can help retailers optimize store layout, product positioning, and marketing
strategies.
12. Conclusion 
This project demonstrates how data visualization and analytics can help retail businesses 
improve product placement strategies and increase sales performance. 
Using Tableau dashboards and interactive storytelling, businesses can clearly understand: 
• Customer purchasing behavior 
• Product placement effectiveness 
• Pricing competitiveness 
• Promotional impact 
The integration of analytics into a web application makes the insights easily accessible and 
interactive. 
13. Future Enhancements 
Future improvements for this project could include: 
• Real-time retail sales data integration
• Machine learning models for sales prediction 
• Customer behavior analysis 
• Inventory optimization 
• Mobile responsive dashboard interface 
