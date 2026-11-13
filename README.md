# CS3SY26_ProjectProposal by 9Mg, Mg03, Mg10, Mg30

## Project Proposal Template

### Project Title or Name of the Application	: TTC and Migudarbs Online shopping
### Section			   	      : 9-Magnesium
### Group Members			    : Hesus Naganos B. Enriquez, Kenneth Eduard Catral, Eduardo Vitangcul
### Date (Proposal Date)  : November 13, 2026

### Project Description: A common problem for sellers on a normal online shopping platform is that they have to do manual computations for themselves on statistics and information that would help their business and their future decisions. Meanwhile, a problem that buyer's face is that they get products on their feed that doesn't even correlate with their interest and price-range. This program aims to help solve these problems step by step and we will integrate it into an online shop of our own. This will help sellers with business related statistics that could help them with making future choices on products as well as how they will adapt to change and stay relevant with customer interest. This will also help customers by making an algorithm that sort certain products to pop up more in the buyer's feed relevant to the tags they put in their interests and the price-range that they can afford. In context, once a user enters their preferred product category tags and price range, the algorithm class will scan through a list of products and then it will take the products that pass the algorithm and put them in the user's feed. Our target users include online buyers that are aware of their budget and what they want, and all sellers, whether small-scale or large-scale.

Classes With their attributes and methods and notes on how they interact with other classes:
### 1.• Customer: Has attributes for account information, which are name, address, username, and password. It handles account creation/authentication through signUp() and login(), and lets shoppers to submit purchases with the method place_order().
### 2. Product: Represents the items available in the store, by having attributes for description, product_type, price, stock_quantity, view_count, and buy_count. Sellers can manage inventory by using add_product(), edit_product(), and remove_product(), while updateStock() and enoughStock() prevent overselling. Its getFeed() method acts as an algorithm, by prioritizing items that match the buyer's preferred tags (from product_type) and highest view/buy counts.
### 3. Order: Connects directly to a Customer to record or store each transaction's date, status, and order name. It also helps with seller statistics  using calc_total(), calc_profit(), and calc_avg_sales(), which are all about the flow of money or profit of the seller.
### 4. Order_Details: Tracks specific quantity of each item purchased in an order and computing the subtotal through calc_total().
### 5. Payment: Connects to Order to handle checkout transactions, storing the total amount due and paymentMethod while ensuring successful transactions through verifyPayment().

<img width="1266" height="568" alt="CS3_ProjectProposal-ClassDiagram_CATRAL,ENRIQUEZ,VITANGCUL" src="https://github.com/user-attachments/assets/df97432f-96fb-4ac6-ade2-546c341f6174" />

### Objectives:
# Objective 1: Make a safe login and sign-up system for shoppers and store owners
# Objective 2: Build a clean product page where users can easily search and view items.
# Objective 3: Create a working shopping cart that adds up prices and completes orders smoothly.
# Objective 4: Set up a simple seller page to add, edit, or delete products and to give them their selling statistics.
# Objective 5: Make an algorithm where the products of which the buyers lean into the most will be what shows up on their main feed.

