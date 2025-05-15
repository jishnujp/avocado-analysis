# **BDM Capstone project** 

# Avocado JuiceBar

### **Business:**	

Avocado JuiceBar is a business that sells juice, shakes and shawarma in Thiruvalla,Kerala  owned and operated by Mr. Richas. He had 3 employees for shawarma and one for juice production, all of them went back to their home (Bihar) in January last week, which led to a temporary shutdown of shawarma production. Now he manages the juice section all by himself. Also he noticed a sudden drop in the number of customers just after that. *He wanted to know how strongly these products are correlated and how this would affect his business.*

### **Data :**

* **Daily Sales data**: He writes down every *order* that he receives, in a book . I.e each order can be identified in separate lines. I took its photo and entered the data in google sheets. Each day's data were stored in different files. (File names were dates).  
  I visited him after 10 pm once a week to interact with him, understand the business and collect data. The data I took were for November,December and  January. Later I collected the same for  February also.  
  Then I used colab and python to extract the consolidated daily sales report of food and drinks separately and an aggregate of how many drinks were sold before the shawarma counter opens (it opens around 3pm) ,how many drinks were sold along with shawarma and how many were sold without shawarma after opening the counter every day.  
* **Cost data:** He writes down his personal and business expenses together,so he was not comfortable with sharing it, however he agreed to send me the pictures of some pages which he felt comfortable to share. So he sent me data of his expenses for 2 weeks.  
* **Product Details :**  There were only 24 products that were mainly sold during the last few months, I wrote down the details of these products during our conversations.

### **Analysis & Observations:**

First I did some exploratory data analysis to understand the business better. Then while focusing on the impact of shawarma shut down, I looked into the **correlation** between food and drinks sales using pandas and  it turned out that they are having only moderate correlation (0.58). The **customer behavior also** reflected the same, only around 38% of the juice was sold along with shawarma per day.  
The cost of production data shows that shawarma has only a thin margin and it turns out that he makes only 500 rs from the shawarma sales each day, whereas juice sales bring him around 3500 per day

### **Conclusions:**

* Since there is no strong correlation between shawarma and juice sales, there won't be any serious impact due to the shut down of shawarma production. However the customer behavior suggests that there could be a short term dip in the juice sales (upto 38%). The short term dip and recovery of juice sales can be seen in February sales data.  
* Even if it took him some time to reopen the shawarma section, there won't be any impact on juice sales (Especially in Summer).  
* The decrease in expense due to lay off of juice section employee will offset the decrease in profit from shawarma closure.  
* *So a temporary shutdown of Shawarma production will not have a significant impact on the profitability of the business.*  
* **Suggestion:**  Low margin and high dependency on variable costs of shawarma makes it risky and vulnerable. He can use this opportunity to either find a way to reduce the cost of production or look for a different product which can give a higher margin.