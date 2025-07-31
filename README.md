# bubble-online-store
Minimalistic eCommerce store built on Bubble.io that allows users to manage products, filter through a live storefront, add items to a cart, and process orders. 

**Feature List**

- Inventory Management
- Storefront Display
- Cart Functionality
- Price & Keyword Filters
- Order Management

---

## Demo App Link
🔗 [Click to view demo app](https://savoir-61748.bubbleapps.io/version-test/products)

⚠️ Data may reset periodically.

---

## Project Features

**Products Page (Inventory Management)**
- Displays all products in a structured table format
- Every row displays Product image, title, description, unit price
- Every row has toggle to mark the product as visible/invisible on the storefront
- Products can be removed from the store
- New products can be added via "Add New Product" button which opens a form where users can input product title, description, upload image, and set unit price
- New products are hidden by default unless toggled on.
<br>


**Storefront Page (Customer-Facing)**
- Dynamically shows all products enabled for storefront visibility.
- Each product card displays: Product image, title, description, and price.
- Each product card also displays and "Add to Cart" icon that opens a quantity selector using which quantity of item can be increased or decreased
- Live Search Filter compares keywords against product titles and descriptions and displays partial as well as complete matches
- Price Range Filter lets user define minimum or maximum price limits or define both values to dispaly products whose unit price falls within the selected price range
- Clear button resets all filters and shows the full list of available products in store
- Cart counter in the header updates in real-time based on items added or removed.
<br>


**Cart Page (Order Summary & Payment)**
- Displays cart items which are part of an order pulled directly from Bubble’s database.
- Each line item shows product image, name, unit price, quantity, and sub-total.
- Calculates and displays: total sub-total value of all items, fixed tax value and grand total value
- Pay button shows popup confirming payment success
<br>


**Orders Page (Admin Order Tracking)**
- Table layout showcasing all recent orders
- Each row includes: order number; customer name, email address, and shipping address; list of products with quantities; total price of the order; order status displayed with color-coded labels
- Dropdown filter offers filtering through orders based on their order status

