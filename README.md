# Fsd
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic E-Commerce Store</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Welcome to Our Store</h1>
        
        <div class="products">
            <!-- Product list will go here dynamically -->
        </div>
        
        <div class="cart">
            <h2>Your Cart</h2>
            <ul id="cart-items">
                <!-- Cart items will go here -->
            </ul>
            <button onclick="checkout()">Proceed to Checkout</button>
        </div>
    </div>

    <script src="app.js"></script>
</body>
</html>
