# NewProductPerformance
Using python to analyse the performance of 3 different sales methods that were used to advertise a new product line for a fiction company that sells stationary and other office products.

The business goal was to find out which sales method suited their long time customers the best, coming in to 2015 modernity. While revenue is also important, bringing the new product to customers and having them try it is the most important part, as the company has many long time loyal customers and their feedback is important.
Customers were randomly split in to one of 3 groups and the product was advertised through 3 different methods, 
Email - an email was sent to all customers in the email group at the start of the launch and another at week 3 of the launch.
Call - all customers in the call group were called at the start of the product launch to thouroughly discuss the new products and were then directed to the website.
Email + Call. an email was sent to all customers in the email and call group and they were also called for 10 minutes on average during the first week of the launch.
Calling alone was the most labour intensive for the marketing team as each phone call needed roughly 30 minutes to explain the products. Email + Call required less phone time because the customer likely already read about it on the email sent a week ago.

<img width="502" height="443" alt="pfsnip" src="https://github.com/user-attachments/assets/0698c190-f1a4-48fe-96d8-4bfb82e1fcfa" />
Cleaning data 
<img width="550" height="593" alt="dfsnip" src="https://github.com/user-attachments/assets/944b427b-82f5-45c3-81d6-8270dc01be1a" />



This bar chart shows the amount of customers that bought products from the company 6 weeks after the product line was launched. 
The Email sales method got the most amount of customers to try the new product.
<img width="640" height="480" alt="image" src="https://github.com/user-attachments/assets/3da9c212-defe-4aae-b79c-84e2927ae3c7" />

This graph shows sales over time for all 3 groups.
<img width="640" height="480" alt="image" src="https://github.com/user-attachments/assets/681eb864-ec5a-49cd-a5b4-80daa1fe5f4a" />
Until week 4, Email got the most amount of customers to buy products. The week 3 additional email didn’t have a big effect on the number of customers.

The distribution of revenue shows that most customers spent around 50 to 100 dollars.
Splitting the graph in to 3 colours shows how each sales method contributed to gaining revenue and attracting customers.
<img width="640" height="480" alt="image" src="https://github.com/user-attachments/assets/88b3556e-50b2-49a7-8403-d140a61ce7cf" />
The total revenue for each method:
email+Call 408257
Call 227564
Email 672318

Total revenue for the past 6 weeks.
<img width="640" height="480" alt="image" src="https://github.com/user-attachments/assets/0ce6882f-788e-4d6b-aa62-a2a71a28b424" />
The number of customers correlate with revenue.
There arent as many Email and call customers as Email customers during week 1 which suggests the additional phone call gave the customers more to think about and so 
It seems that most Email+Call customers spent more money after week 3 because they spent more time thinking about the product.
The call method has consistently low revenue. 

Average customer spending over the past 6 weeks.
<img width="640" height="480" alt="image" src="https://github.com/user-attachments/assets/9d2c74e2-4e3f-401d-a1c5-a9a112ee8b09" />
This shows that customers who spend more, do so after a longer period of time than the rest of the customers. If we compare it to the total revenue graph, we can see that although average spending per person has increased, the overall revenue isnt higher than the first weeks.

Email and Call customers spent the most amount of money because they were persuaded to buy more products AND more expensive products. They also visited our website more often suggesting that people who spend more tend to research more. 
<img width="640" height="480" alt="image" src="https://github.com/user-attachments/assets/9bd39bdd-a8f2-41d3-bce8-15b1f5102b5a" />
<img width="640" height="480" alt="image" src="https://github.com/user-attachments/assets/3504daf3-ab49-4e97-bb9d-375a9ed7cefd" />

#The key Performance indicators the company needs to track when launching a new product line:
1. Product Adoption Rate
Product adoption is a critical metric to evaluate customer interest in the new product. sales figures suggest that email was the most effective communication method.
To better assess email performance in the future, I recommend tracking: Open Rate, Click-Through Rate and Conversion Rate.
2. Weekly Revenue
Weekly revenue provides insight into the financial success of the launch and customer purchasing behaviour. Launching new products incurs significant costs; monitoring revenue ensures the company is achieving a return on investment (ROI). 
3. Product Stickiness
Product stickiness refers to how often customers return to repurchase the product. High stickiness indicates strong customer satisfaction and product-market fit.

In order to track KPI's better and accurately and perform a more in depth analysis on customer purchase patterns, there need to be more columns implemented in to the database such as: Gender, Age, Type of product, the exact cost of the product and the date when the product was purchased. For this I would recommened a relational database to better store and organise information about the business.

#Summary
In the future it seems that the email method alone would suffice but polishing the email and call method could raise customer satisfaction.
The email had immediate results in informing customers of the new product. Many customers decided to try the new product, but needed more convincing to spend more.
The call method alone wasn't very effective considering the amount of time it takes the marketing team. Since sending all customers the same email doesn’t require much effort, calling customers without sending an email, isn't best practice.
The Email + Call method was most successful at persuading customers to buy more items and spend more money. Rather than sending another email 3 weeks later after the first for the email method, the marketing team could call customers after 3 weeks as a reminder. If the customer has already bought the product, the company could get quick feedback, and if they haven't, some persuading could win them over and give them the confidence to spend more.
Alternatively, the follow-up call can be targeted specifically to customers who did not purchase, allowing for a more personalized and efficient approach.
Also consider increasing outreach efforts in areas that spend the least (North Carolina, Tennessee, Maine, Montana) through additional follow-up calls to boost engagement and encourage purchases.





