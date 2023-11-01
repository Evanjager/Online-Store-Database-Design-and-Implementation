# Online-Store-Database-Design-and-Implementation
The project will build an online store like Amazon.com selling whatever products you want. 

- Develop a database design.
- Convert that design into SQL DDL. 

Description:
- A Customer is identified by an auto-increment id. Other attributes include first name, last name, email, phone number, street address, city, province/state, postal code, and country. A Customer also has a user id (unique) and password.

- A customer may have one or more payment methods. A Payment Method has an auto-increment id for a key, a payment method type (PayPal, Visa, etc.), payment number, and payment expiry date.

- An Order is placed by one customer. A customer may have multiple orders. An Order has an auto-increment id, order date, and total order amount (e.g. $55.75). Also store the shipment address, city, state, country, and postal code. Use OrderSummary as entity/table name as Order is a keyword in SQL.

- The store sells products. A Product has an auto-increment id, name, price, image URL (string), image (BLOB), and description.

- A product has a category. A category has one or more Products. A Category has an auto-increment id and name.

- Products are part of an order. An order may have one or more products. For each product in an order track the quantity and price.

- An order is shipped with a shipment. A Shipment has an auto-increment id, a shipment date, and a description. A shipment contains only one order.

- A Warehouse contains products. A product may be stored at multiple warehouses with different inventory values. A shipment will be sent from only one warehouse. A Warehouse has an auto-increment id and a name.

- For each customer, track their shopping cart which will contain one or more products each with a quantity and price.

- A product may have reviews by customers. A Review by a customer on a product has an auto-increment id, rating (1 to 5), comment, and review date. A customer does not have to buy a product in order to provide a review. A customer may review a product more than once.


