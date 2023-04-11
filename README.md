# Pet project E-commerce
The answered questions:
1) What is the number of users we have who have made a purchase only once? 
92,102 users have made a purchase only once, which is around 96% out of the total number of users (96,096).

Which brings us to a conclusion that the items sold on the e-commerce platform are:

Big-ticket items: Products that are expensive and have a long lifespan, such as furniture, appliances, and electronics, are usually bought once and used for several years.
Special-occasion items: Products that are used for special events or occasions, such as wedding dresses, tuxedos, and prom dresses, are typically bought once and used for that specific occasion.
Unique or rare items: Products that are unique, rare, or collectible, such as vintage or limited-edition items, are often bought once by collectors or enthusiasts.

2) What is the average number of orders per month that are not delivered for various reasons?

Aside from the delivered items, most orders are shipped, which is a good thing. However, they might not be delivered to the customer within a one month span due to long estimated date of arrival.

Next, 29 orders on average are unavailable. It may be related to the fact that a partical item maybe run out of stock but is still listed on the website. Another reason may be related to quality issue. Therefore, I suggest this e-commerce platform to pay more attention to their inventory management and incoming quality control.

Third, 24 orders on average are canceled. This may be related to the fact that a lot of purchases made by the customers are made due to impulsive buying. In other words, after reconsideration, the customer may realize that this particular item is not necessary and they simply cancel their orders. High delivery fee and long ETA dates might also contribute to orders being canceled.

3) For each product, determine on which day of the week the product is most frequently purchased
Considering the fact that this is an e-commerce platform, it is difficult to make any assumptions as to what kind of products these are based on the most frequently day of purchase:

Big-ticket items: Consumers may be more likely to research and purchase big-ticket items on weekdays, when they have access to their work computers and may have more time to research and compare options. However, some consumers may also browse and make purchases on weekends, especially if they have more free time or are more comfortable making purchases from home.

Special-occasion items: Consumers may be more likely to search and purchase special-occasion items on weekdays, as they may need to plan ahead and schedule fittings or consultations with the retailer or designer. However, some consumers may also browse and purchase on weekends, especially if they have a specific event coming up or need to receive the item quickly.

Unique or rare items: Consumers who are interested in unique or rare items may be more likely to browse and make purchases on weekends, as they may have more leisure time to explore specialized online marketplaces or auction sites. However, some collectors or enthusiasts may also make purchases on weekdays, depending on their personal schedule and preferences.

4) What is the average number of purchases per week for each user (by month)?
Again, we see that the highest number of weekly purchases is 1.35. Which confirms our assumption that this e-commerce platform sells only big-ticket, special-occasion, and unique or rare items.

5) Using pandas, conduct a cohort analysis of users. In the period from January to December, identify the cohort with the highest retention rate in the third month.

A cohort with the highest retention rate on a third month comes from the users that made the first purchase in June - 0.41% which is still an extremely low percentage. It would be weird to assume that we could get a higher number considering that the vast majority of our users make purchases only once.

6) Often for qualitative audience analysis, segmentation-based approaches are used. Create an RFM segementation of users to assess audience quality. In clustering, selected the following metric: R (receny) - time from the user's last purchase to the current date. F (frequency) - total number of purchases by the user over time. M (monetary value) - the total amount of purchases over time. For each RFM segment, created boundaries for the recency, frequency, and monetary metrics for interpreting these clusters. 

##Defining the segments
Best Customers – This group consists of those customers who are found in R-Tier-1, F-Tier-1 and M-Tier-1, meaning that they transacted recently, do so often and spend more than other customers. A shortened notation for this segment is 4-4-4; we’ll use this notation going forward.
High-Spending New Customers – This group consists of those customers in 4-1-1 and 4-1-2. These are customers who transacted only once, but very recently and they spent a lot. A shortened notation for this segment is 4-1-X, where X is either 1 or 2.
Lowest-Spending Active Loyal Customers – This group consists of those customers in segments 4-4-1 and 4-4-2 (they transacted recently and do so often, but spend the least). A shortened notation for this segment is 4-4-1/2.
Churned Best Customers – This segment consists of those customers in groups 1-4-4 and 2-4-4 (they transacted frequently and spent a lot, but it’s been a long time since they’ve transacted).

Suggestions for retention of each segment:

Best Customers: To retain these customers, the e-commerce platform could offer personalized incentives and rewards, such as exclusive discounts or early access to new products, to encourage them to continue transacting on the platform. The platform could also provide excellent customer service and support to ensure that these customers feel valued and appreciated.

High-Spending New Customers: offering additional incentives and rewards for their second purchase, such as a discount or free gift might be beneficial to retain them. The platform could also send personalized follow-up emails to thank these customers for their purchase and encourage them to return to the platform.

Lowest-Spending Active Loyal Customers: The e-commerce platform could provide incentives to encourage those customers to increase their spending, such as a loyalty program or points system that rewards customers for making more purchases. The platform could also offer personalized product recommendations and promotions based on the customer's purchase history and preferences.

Churned Best Customers: I'd suggest offering win-back promotions or discounts to encourage those customers to return to the platform. The platform could also conduct surveys or reach out to these customers to understand why they stopped transacting and address any concerns or issues they may have had with the platform.
