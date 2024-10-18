# Mendix
This is an app i have developed using mendix

This app is basically on customer purchase portal here i have made three kinds of users:
1.Admin
2.Customer
3.Customer without login

Admin
1. Should be able to create product with the properties namely product name, price, description, product image.
2. Admin should be able to view/create/delete a product.
3. Admin can import bulk products through excell sheet using Excell importer.
4. Admin can view customer details and their payment history.
5. Download the product details, payment details in the form of excell using Excell exporter marketplace module.

Customer with login
1. Sign-up should be done.(register the details like name, email, phone number, username and password)
2. View the product details.
3. Adding the products in cart.
4. Calculate the price of the products in cart(Total number of products, sum of the product price).
5. Enter the payment details(card holder name, card number, cvv) and proceed to pay.
6. Once after the payment is successfull a invoice pdf shoould be given to the customer for download.
7. Each customer should have their payment history.

Customer without Login 
1. View the product details.
2. On clicking any of the product, a pop shouod be displayed to sign-up.
3. Once after sign-up the customer can proceed to purchase.
