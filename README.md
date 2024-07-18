# codealpha-task
Documentation: Simple E-commerce Store HTML Structure
Overview
This HTML document sets up a basic e-commerce store webpage with sections for displaying product listings and a shopping cart. It includes necessary metadata, structured content sections, and references to external styles and scripts.

File Structure
HTML Document: index.html
External Stylesheet: styles.css
External JavaScript: script.js
Detailed Structure
1. Document Declaration and Language Setting
html
Copy code
<!DOCTYPE html>
<html lang="en">
<!DOCTYPE html>: Declares the document type and version of HTML used.
<html lang="en">: Defines the root element of the document with English as the language.
2. Head Section
html
Copy code
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple E-commerce Store</title>
    <link rel="stylesheet" href="styles.css">
</head>
<meta charset="UTF-8">: Specifies the character encoding of the document as UTF-8.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Sets the viewport properties for responsive design.
<title>Simple E-commerce Store</title>: Defines the title of the webpage displayed in the browser tab.
<link rel="stylesheet" href="styles.css">: Links an external CSS file (styles.css) for styling the page.
3. Body Section
html
Copy code
<body>
    <header>
        <h1>My E-commerce Store</h1>
    </header>
    <main>
        <section class="product-list">
            <!-- Product listings go here -->
            <div class="product">
                <h2>Product 1</h2>
                <p>Price: $19.99</p>
                <button onclick="addToCart('Product 1')">Add to Cart</button>
            </div>
            <!-- Repeat for other products -->
        </section>
        <section class="shopping-cart">
            <h2>Shopping Cart</h2>
            <ul id="cart-items">
                <!-- Cart items go here -->
            </ul>
        </section>
    </main>
    <script src="script.js"></script>
</body>
<header>: Contains the main heading (<h1>) for the e-commerce store.
<main>: Contains the main content of the webpage.
Product Listing Section (<section class="product-list">): Displays product listings.
Each product is represented by a <div class="product"> containing:
<h2>: Product name.
<p>: Product price.
<button>: Button to add the product to the shopping cart, triggering the addToCart function with the product name as a parameter.
Shopping Cart Section (<section class="shopping-cart">): Displays the shopping cart.
<ul id="cart-items">: Unordered list for dynamically displaying cart items.
<script src="script.js"></script>: Links an external JavaScript file (script.js) for scripting functionalities.
Functionality
addToCart(productName) Function:
Defined in script.js.
Handles adding products dynamically to the shopping cart (cart-items list).
External Files
styles.css:
Contains CSS rules for styling elements such as .product and .shopping-cart.
script.js:
Contains JavaScript functions and logic, including event handling for adding products to the cart.
This documentation provides a comprehensive overview of the structure, functionality, and external dependencies of the Simple E-commerce Store HTML setup. 



