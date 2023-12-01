# Shivanjali_DBMS_Lab4
Lab session 4 - DBMS

Supplier Table:
• Stores information about suppliers, including ID, name, city, and phone number.
Customer Table:
• Contains details about customers, such as ID, name, phone number, city, and gender.
Category Table:
• Holds information about product categories, including ID and name.
Product Table:
• Stores product details like ID, name, description, and the category it belongs to.
Supplier Pricing Table:
• Manages pricing information from suppliers for various products.
Order Table:
• Records order details, such as order ID, amount, date, customer ID, and pricing ID.
Rating Table:
• Captures ratings given by customers for their orders.

Respected data inserted in the respective tables.

Solution coded for given queries:

1. Display the total number of customers based on gender who have placed individual orders of worth at least Rs.3000.
2. Display all the orders along with product name ordered by a customer having Customer_Id=2
3. Display the Supplier details who can supply more than one product.
4. Find the least expensive product from each category and print the table with category id, name, product name and price of the product
5. Display the Id and Name of the Product ordered after “2021-10-05”.
6. Display customer name and gender whose names start or end with character 'A'.
7. Create a stored procedure to display supplier id, name, Rating(Average rating of all the products sold by every customer) and
Type_of_Service. For Type_of_Service, If rating =5, print “Excellent Service”,If rating >4 print “Good Service”, If rating >2 print “Average
Service” else print “Poor Service”. Note that there should be one rating per supplier.
