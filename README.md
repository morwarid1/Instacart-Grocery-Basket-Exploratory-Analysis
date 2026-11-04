# Instacart Grocery Basket Analysis

**Instacart Grocery Basket Analysis**

Instacart is an online grocery store that operates through an app. They want to uncover more information about their sales patterns.

My role as a data analyst is to perform an initial exploratory data analysis of some of their data in order to derive insights and suggest strategies for better segmentation based on the provided criteria.

The Instacart stakeholders are most interested in the variety of customers and their purchasing behaviors in their database.

My analysis will include creating a targeted marketing strategy by helping the stakeholders with the following questions.

**Key Questions**

1. What are the busiest days of the week and hours of the day?
2. Are there particular times of the day when people spend the most money?
3. Which departments have the highest frequency of product orders?
4. What are the different types of customers in the system, and how do their ordering behaviors differ?
5. What is the distribution among users in regard to their brand loyalty?
6. Are there differences in ordering habits based on a customer's loyalty status?
7. Are there differences in ordering habits based on a customer's region?
8. Is there a connection between age and family status in terms of ordering habits?
9. What different classifications does the demographic information suggest?
10. What differences can you find in the ordering habits of different customer profiles?

Overall, the process was very smooth. I worked on orders.csv, products.csv, customers.csv, department.csv, order_product_prior.csv, and a few more data files.

I started by importing the data into Jupyter to do descriptive analysis, followed by subsetting, consistency checks, combining and exporting, deriving new variables, grouping and aggregating data, data visualization, and finally coding etiquette and exporting to Excel.

In between each step, I exported the data into separate Excel sheets.

The skills, tools, and procedures used in Jupyter were the following: data wrangling, data merging, deriving variables, grouping and aggregating data, reporting in Excel, and population flows.

Writing commands in Python was very easy and clean.

I used many libraries such as pandas, NumPy, os, matplotlib.pyplot, seaborn, and SciPy.

The only challenge that I faced was while creating new variables, but I was able to solve the problem with loc and aggregation.

All these procedures helped me answer the stakeholders' questions. The answers to the main questions are the following:

**Solutions**

1. The busiest days of the week are the first day of the week and the last day of the week, and 4 to 5 a.m. is the busiest hour of the day.
2. Looking at the graph, people spend the most money in the morning before 10 a.m.
3. Looking at the graph, department ID 10.25 has the highest ordering frequency.
4. There are three types of customers: regular customers, loyal customers, and new customers. Their ordering behaviors differ based on the number of products they order.
5. Regular customers have the highest number of orders, followed by loyal customers and then new customers.
6. Yes — based on customer loyalty status, regular customers place the highest number of orders, followed by loyal customers, with new customers placing the fewest (almost half the number of regular customers' orders).
7. Yes, the value counts in all four regions differ. Region Three has the highest number of orders, followed by Region Four, Region Two, and Region One. The number of orders in Region One is almost half of Region Three.
8. Yes — single adults have the highest number of orders, compared to young parents and seniors, with the second-highest and lowest number of orders respectively.
9. Family status plays a role in the ordering habits of customers, as mentioned above. Age plays a role in the ordering habits of customers, as mentioned above. Region plays a role in the ordering habits of customers, as mentioned above. Income and certain types of goods do not seem to impact ordering habits.
10. I can see an increase in the mean ordering behavior from seniors, single adults, and young parents, with the lowest, second-highest, and highest number of orders respectively.

**My recommendations:**

Instacart should focus on regular customers, Region Three, single adults, department ID 10.25, the first and last days of the week, and morning orders.

One thing I would do differently to improve is subsetting, to make the data lighter.
