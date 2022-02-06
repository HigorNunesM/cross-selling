# cross-selling

The idea of this project is to create suggestions of products for costumers to purchase based on past purchases. We use the same methodology as Apriori but doing the math without the library.

We analyze the purchases history to generate metrics such as Support and Confidence, creating association rules between the products.

Then we analyze the purchase history of each client separately to create a recommendation list for the client. Giving them personalized suggestion that they are likely to adhere.


As a bonus we also analyze the most selling items, to suggest those for clients that are not currently buying the company’s best products.
