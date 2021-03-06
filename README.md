# Bamazon

This is a Node.js command line application that stores store information in a MySQL Database and allows customers to buy in stock items and managers to update and purchase items.

Check it out below!

---

**Photo Walk-through of Customer and Manager Apps:**

*Run **bamazonCustomer.js** in the terminal:*

* mySQL database before the customer purchase (Note Pretty Shrubs - ID 11):
![https://user-images.githubusercontent.com/31671905/33743338-64d96cde-db7a-11e7-9349-a1f439c29221.png](https://user-images.githubusercontent.com/31671905/33743338-64d96cde-db7a-11e7-9349-a1f439c29221.png)

* Customer makes the purchase of 3 "Pretty Shrubs":
![https://user-images.githubusercontent.com/31671905/33743397-a79c3bd2-db7a-11e7-89ea-0a89cf0532b1.png](https://user-images.githubusercontent.com/31671905/33743397-a79c3bd2-db7a-11e7-89ea-0a89cf0532b1.png)

* mySQL database after the purchase-- stock quantity, number sold, and revenue have been updated (ID 11):
![https://user-images.githubusercontent.com/31671905/33743453-de01b256-db7a-11e7-96b5-c8c803133cb6.png](https://user-images.githubusercontent.com/31671905/33743453-de01b256-db7a-11e7-96b5-c8c803133cb6.png)

---

*Run **bamazonManager.js** in the terminal:*

* A manager requests to look at low stock items (note ID 5, 6, 9 from previous mySQL picture, with stock < 5):
![https://user-images.githubusercontent.com/31671905/33743456-dfcf3cac-db7a-11e7-9a7a-58517b958602.png](https://user-images.githubusercontent.com/31671905/33743456-dfcf3cac-db7a-11e7-9a7a-58517b958602.png) 

* A manager chooses to add items to existing inventory (10 items added to ID 9):
![https://user-images.githubusercontent.com/31671905/33743458-e1eb665a-db7a-11e7-93f8-6fc8a279a28c.png](https://user-images.githubusercontent.com/31671905/33743458-e1eb665a-db7a-11e7-93f8-6fc8a279a28c.png)

* mySQL after the items have been added-- quantity has been updated:
![https://user-images.githubusercontent.com/31671905/33743459-e40e6702-db7a-11e7-9209-3ae9c2f1de2d.png](https://user-images.githubusercontent.com/31671905/33743459-e40e6702-db7a-11e7-9209-3ae9c2f1de2d.png)

* A manager chooses to add a brand new item to the product choices:
![https://user-images.githubusercontent.com/31671905/33743460-e6275440-db7a-11e7-87d0-326337050160.png](https://user-images.githubusercontent.com/31671905/33743460-e6275440-db7a-11e7-87d0-326337050160.png)

* mySQL after the new item has been added (ID 21):
![https://user-images.githubusercontent.com/31671905/33743469-e96d7df0-db7a-11e7-98b9-8742a072b869.png](https://user-images.githubusercontent.com/31671905/33743469-e96d7df0-db7a-11e7-98b9-8742a072b869.png)

---

**Technologies Used:**

Node.js | Inquirer NPM | MySQL

