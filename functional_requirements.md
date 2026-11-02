# Functional Requirements (Bakery Management System)

**Roles in the System:** Admin

## 1.1 Admin Authentication

- **1.1.1** Admin can login with their email and password.
- **1.1.2** System validates the admin login credentials.
- **1.1.3** System displays an error message if the login credentials are invalid.
- **1.1.4** Admin is directed to the dashboard after successful login.
- **1.1.5** Admin can view a summary of today's orders and low-stock items on the dashboard.
- **1.1.6** Admin can log out at any time.

## 1.2 Cake Order Management

- **1.2.1** Admin can create a cake order.
- **1.2.2** Admin can enter the customer's name.
- **1.2.3** Admin can enter the customer's phone number.
- **1.2.4** Admin can select the type of cake from the available cakes.
- **1.2.5** Admin can select the size of the cake.
- **1.2.6** Admin can enter the inscription.
- **1.2.7** Admin can select the delivery type.
- **1.2.8** Admin can enter the delivery address for home delivery.
- **1.2.9** Admin can set the delivery or pickup time.
- **1.2.10** Admin can select add-ons.
- **1.2.11** Admin can view the total price of the order.
- **1.2.12** Admin can save the completed cake order.
- **1.2.13** Admin can view the list of all cake orders.
- **1.2.14** Admin can view the details of an individual order.
- **1.2.15** Admin can edit an existing order.
- **1.2.16** Admin can cancel an order.
- **1.2.17** Admin can update the status of an order (e.g., pending, ready, delivered).
- **1.2.18** Admin can generate a report of cake orders by selecting a date range.

## 1.3 Stock Management

- **1.3.1** Admin can view the remaining quantity of all stock items.
- **1.3.2** Admin can add new stock to the system.
- **1.3.3** Admin can update the quantity of existing stock items.
- **1.3.4** Admin can set the minimum stock level for each stock item.
- **1.3.5** System notifies the admin when a stock item is about to run out.
- **1.3.6** System notifies the admin when a stock item has run out.

## 1.4 Stock-Based Order Availability

- **1.4.1** Admin can define the stock items and quantities required for each cake type.
- **1.4.2** System determines which cakes can be ordered based on the current stock.
- **1.4.3** System marks a cake as unavailable for ordering when its required stock is insufficient.
- **1.4.4** Admin can see if all the required stock is available for a cake order while creating it.
- **1.4.5** System reduces the stock quantity automatically when an order is saved.
- **1.4.6** System returns the stock quantity automatically when an order is cancelled.

## 1.5 Menu Management

- **1.5.1** Admin can add a new cake type with its sizes and prices.
- **1.5.2** Admin can edit or remove an existing cake type.
- **1.5.3** Admin can add and edit add-ons (e.g., candles, balloons) and their prices.
