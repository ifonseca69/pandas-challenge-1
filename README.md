# pandas-challenge-1
HW_Module_4
# We have our best sales from our best customer Kendra Garret with a sales profit of $36.58 millons with margin profit of 44.46%.

![Best_customer](Best_customer_24741.png)

![Sales_summary](summary_sales.png)

# Module 4 Challenge

Start Assignment

-   Due  Monday  by  10:59pm
-   Points  100
-   Submitting  a text entry box or a website url

### Background

Welcome to this module challenge focused on data analysis with Python's Pandas library. As a crucial component in various fields, such as data science, machine learning, and business intelligence, practical data analysis involves examining, cleaning, processing, and extracting useful information from large datasets. This assignment provides a hands-on opportunity to develop these skills.

In this challenge, we'll dive into a dataset from a fictional e-commerce company, exploring and analyzing data to address real-world business questions. Your mission will involve identifying top customers, popular product categories, calculating profits, and more. By the end of this task, you'll have a practical understanding of data exploration, transformation, and analysis, preparing you for more complex data scenarios in your future career.

### Files

Download the following files to help you get started:

[Module 4 Challenge filesLinks to an external site.](https://static.bc-edx.com/ai/ail-v-1-0/m4/lms/starter/Starter_Code.zip)

### Before You Begin

Before starting the assignment, be sure to complete the following steps:

-   Create a new repository for this project called  `pandas-challenge-1`.  **Do not add this homework assignment to an existing repository**.
    
-   Clone the new repository to your computer.
    
-   Inside your local Git repository, add the starter files from your file downloads.
    
-   Push these changes to GitHub or GitLab.
    

### Challenge Instructions

#### Part 1: Explore the Data

In this part, you will import the data and use Pandas to learn more about the dataset.

-   Import the data from the CSV file.
    
-   View the column names.
    
-   Use the describe function to gather some basic statistics.
    
-   Use the provided space to explore and make yourself familiar with the data. Feel free to create more cells as needed.
    
-   Answer the following questions using Pandas:
    
    -   What three item categories had the most entries?
        
    -   For the category with the most entries, which subcategory had the most entries?
        
    -   Which five clients had the most entries in the data?
        
        -   Store the client ids of those top 5 clients in a list.
    -   How many total units (the qty column) did the client with the most entries order?
        

#### Part 2: Transform the Data

Now that you have a better understanding of the data you will be asked to transform the data for better and easier analysis.

-   Create a column that calculates the subtotal for each line using the unit_price and the qty.
    
-   Create a column for shipping price. Assume a shipping price of $7 per pound for orders over 50 pounds and $10 per pound for items 50 pounds or under.
    
-   Create a column for the total price using the subtotal and the shipping price along with a sales tax of 9.25%.
    
-   Create a column for the cost of each line using unit cost, qty, and shipping price (assume the shipping cost is exactly what is charged to the client).
    
-   Create a column for the profit of each line using line cost and line price.
    

#### Part 3: Confirm Your Work

After transforming data, it's always a good idea to verify the results. You have email receipts showing the total prices for 3 orders.

Order ID 2742071 had a total price of $152,811.89 Order ID 2173913 had a total price of $162,388.71 Order ID 6128929 had a total price of $923,441.25

-   Confirm that your calculations match the receipts. Remember, each order has multiple lines.

#### Part 4: Summarize and Analyze

Use the new columns with confirmed values to find the following information.

-   How much did each of the top 5 clients by quantity spend? Use your work from Part 1 for client ids?
    
-   Create a summary DataFrame showing the totals for the top 5 clients with the following information: total units purchased, total shipping price, total revenue, and total profit.
    
-   Create a function to change the currency to millions of dollars. Format the data and rename the columns to names suitable for presentation. Then, sort the DataFrame in descending order by total profits.
    
-   Write a brief 2-3 sentence summary of your findings.
    

### Hints and Considerations

-   Use the Pandas DataFrame  [documentationLinks to an external site.](https://pandas.pydata.org/docs/reference/frame.html)  to find helpful functions. Feel free to use functions that you didn’t learn in class if you find they make the work easier!
    
-   Remember to make functions whenever appropriate and name them well. Functions are helpful both for performing operations and for making code more readable.
    
-   Don’t forget to use all the steps in the analytical process! It can be especially hard to remember the steps that come before the coding starts. Define the question before you begin, and make sure to read to the end of the instructions first. If there are steps that don’t make sense yet, use the space reserved for data exploration to try and understand it.
    

### Requirements

#### Explore the Data (30 points)

-   View the column names. (4 points)
    
-   Use the describe function. (4 points)
    
-   Correctly identify the category with the most entries. (4 points)
    
-   For the category with the most entries, correctly identify the subcategory with the most entries. (5 points)
    
-   Correctly identify the 5 clients with the most entries in the data. (5 points)
    
-   Store the client ids of those top 5 clients in a list. (4 points)
    
-   Display the total units (the qty column) that the client with the most entries ordered. (4 points)
    

#### Transform the Data (30 points)

-   Create a column that calculates the subtotal for each line using the unit_price and the qty. (6 points)
    
-   Create a column for shipping price. Assume a shipping price of $7 per pound for orders over 50 pounds and $10 per pound for items 50 pounds or under. (6 points)
    
-   Create a column for the total price using the subtotal and the shipping price along with a sales tax of 9.25%. (6 points)
    
-   Create a column for the cost of each line using unit cost, qty, and shipping price (assume the shipping cost is exactly what is charged to the client). (6 points)
    
-   Create a column for the profit of each line using line cost and line price. (6 points)
    

#### Part 3: Confirm Your Work (15 points)

-   Confirm that Order ID 2742071 had a total price of $152,811.89. (5 points)
    
-   Confirm that Order ID 2173913 had a total price of $162,388.71. (5 points)
    
-   Confirm that Order ID 6128929 had a total price of $923,441.25. (5 points)
    

#### Part 4: Summarize and Analyze (25 points)

-   Calculate the total revenue from each of the top 5 clients in Part 1. (5 points)
    
-   Create a summary DataFrame showing the totals for the top 5 clients with the following information: total units purchased, total shipping price, total revenue, and total profit. (5 points)
    
-   Create a function to change the currency to millions of dollars. Format the data and rename the columns to names suitable for presentation. Then, sort the DataFrame in descending order by total profits. (5 points)
    
-   Write a brief 2-3 sentence summary of your findings. (10 points)
    

### Grading

This challenge will be evaluated against the requirements and assigned a grade according to the following table:

Grade



### Submission

To submit your Challenge assignment, click Submit, and then provide the URL of your GitHub repository for grading.

**NOTE**

You are allowed to miss up to two Challenge assignments and still earn your certificate. If you complete all Challenge assignments, your lowest two grades will be dropped. If you wish to skip this assignment, click Next, and move on to the next module.

Comments are disabled for graded submissions in Bootcamp Spot. If you have questions about your feedback, please notify your instructional staff or your Student Success Manager. If you would like to resubmit your work for an additional review, you can use the Resubmit Assignment button to upload new links. You may resubmit up to three times for a total of four submissions.

**IMPORTANT**

**It is your responsibility to include a note in the README section of your repo specifying code source and its location within your repo**. This applies if you have worked with a peer on an assignment, used code that you did not author or create sourced from a forum such as Stack Overflow, or you received code outside of curriculum content from support staff such as an Instructor, TA, Tutor, or Learning Assistant. This will provide visibility to grading staff of your circumstance in order to avoid flagging your work as plagiarized.

If you are struggling with a challenge assignment or any aspect of the academic curriculum, please remember that there are student support services available for you:

1.  Ask the class Slack channel/peer support.
    
2.  AskBCS Learning Assistants exists in your class Slack application.
    
3.  Office hours facilitated by your instructional staff before and after each class session.
    
4.  [Tutoring GuidelinesLinks to an external site.](https://docs.google.com/document/d/1hTldEfWhX21B_Vz9ZentkPeziu4pPfnwiZbwQB27E90/edit?usp=sharing)  - schedule a tutor session in the Tutor Sessions section of Bootcampspot - Canvas
    
5.  If the above resources are not applicable and you have a need, please reach out to a member of your instructional team, your Student Success Advisor, or submit a support ticket in the Student Support section of your BCS application.
    

### References

Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.

[Previous](https://bootcampspot.instructure.com/courses/6455/modules/items/1298500)[Next](https://bootcampspot.instructure.com/courses/6455/modules/items/1298505)

© 2024 edX Boot Camps LLC

### External References
https://stackoverflow.com/questions/47414848/pandas-select-all-columns-without-nan
https://stackoverflow.com/questions/41271673/format-numbers-in-pandas-as-currency-in-thousands-or-millions