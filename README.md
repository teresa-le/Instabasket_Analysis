
# Optimizing Instabasket Orders Fulfillment for a Grocery Store Chain

MM&A is a grocery store chain that offers grocery orders delivery services. Customer satisfaction and the in-shopping experience has been negatively impacted due to the increasing volume of Instabasket shoppers. To complete these orders, Instabasket shoppers often need to visit multiple aisles. MM&A would like to create one aisle with 1000 products that maximize the following metrics:
* the number of orders that utilize the aisle, and 
* the average % of items in each order that utilize in-aisle items.

The solution needed to meet the following constraints: 
* Only 1000 products can be included in total. (3% of the total)
* Only 100 frozen products can be included. 
* Only 100 refrigerated products can be included.


## Data Sources

This data has been adapted from “The Instacart Online Grocery Shopping Dataset 2017" by the Rotman School of Management.  
https://www.kaggle.com/competitions/instacart-market-basket-analysis/.


## 🛠 Skills
Excel, Python, Tableau, Data Cleaning, Data Analysis, Data Visualization 


## Actions 

### Assumptions & Constraints 
We conducted an exploratory analysis and cleaned the data using Python and Excel. We then used Python to help select our top 1000 products. For our solution, we used the inverted Pareto strategy. Rather than focusing on the lower-performing 20%, we prioritize the essential 80%, specifically targeting the top 83% of products across categories, departments, aisles, and our entire product range. By embracing this inverted Pareto 80/20 principle, concentrating on the most popular items within departments, aisles, and product names, we've significantly expanded our product coverage while maintaining a high fill-in rate, transcending the limitations of relying solely on product popularity.


## Results
For the two main key metrics used to measure success, we achieved the following: 
* Number of Orders that Utilize Instabasket Aisle (Order Fulfillment Rate): 48.7%
* Average % of Products Use Instabasket Aisle: 89.3%

We estimate on average, we would be saving 15 minutes per order and on average, would need on average 50% fewer aisles to complete orders (3 vs. 6 aisles). 

To view a copy of the complete presentation, you can go <a href="https://docs.google.com/presentation/d/1vS8dmFt5MpRSoHzwUz5GZ9kqWjYAZXvK/edit?usp=sharing&ouid=108620003158556993566&rtpof=true&sd=true">here</a>.

