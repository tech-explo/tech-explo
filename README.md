<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Affiliate Marketing Hub</title>
    <style>
        /* Reset some default styling */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body and Background */
        body {
            font-family: Arial, sans-serif;
            background-color: #fafafa;
            color: #333;
            line-height: 1.6;
        }

        /* Header Styles */
        header {
            background-color: #6200ea;
            color: #fff;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 2.5rem;
        }

        /* Navigation Bar */
        nav {
            background-color: #3700b3;
            display: flex;
            justify-content: center;
            padding: 10px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            font-size: 1rem;
            padding: 10px 20px;
            transition: background-color 0.3s ease;
        }

        nav a:hover {
            background-color: #03dac6;
        }

        /* Main Container */
        .container {
            max-width: 1200px;
            margin: 30px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.1);
        }

        h2 {
            text-align: center;
            margin-bottom: 30px;
        }

        .product {
            display: flex;
            align-items: center;
            margin-bottom: 30px;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 8px;
            background-color: #f9f9f9;
            transition: transform 0.3s ease;
        }

        .product:hover {
            transform: scale(1.02);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }

        .product img {
            max-width: 200px;
            margin-right: 20px;
            border-radius: 8px;
        }

        .product-info {
            flex: 1;
        }

        .product-info h3 {
            font-size: 1.8rem;
            margin-bottom: 10px;
        }

        .product-info p {
            font-size: 1.1rem;
            margin-bottom: 15px;
        }

        .btn {
            background-color: #03dac6;
            color: #000;
            padding: 12px 18px;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1rem;
            transition: background-color 0.3s ease;
        }

        .btn:hover {
            background-color: #018786;
        }

        /* Footer */
        footer {
            background-color: #6200ea;
            color: #fff;
            text-align: center;
            padding: 20px;
        }

        footer p {
            font-size: 1rem;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Affiliate Marketing Hub</h1>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#">Home</a>
        <a href="#products">Products</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Main Content -->
    <div class="container">
        <!-- Featured Products Section -->
        <section id="products">
            <h2>Featured Products</h2>

            <!-- Product 1 -->
            <div class="product">
                <img src="https://via.placeholder.com/200" alt="Product 1">
                <div class="product-info">
                    <h3>Product 1 - Amazing Gadget</h3>
                    <p>This gadget will make your life easier and more fun. Great for tech enthusiasts.</p>
                    <a href="https://affiliate-link-example.com" class="btn" target="_blank">Buy Now</a>
                </div>
            </div>

            <!-- Product 2 -->
            <div class="product">
                <img src="https://via.placeholder.com/200" alt="Product 2">
                <div class="product-info">
                    <h3>Product 2 - Ultimate Lifestyle App</h3>
                    <p>Stay organized and focused with this productivity app. Highly recommended for professionals.</p>
                    <a href="https://affiliate-link-example.com" class="btn" target="_blank">Buy Now</a>
                </div>
            </div>

            <!-- Add more products here as needed -->
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Contact Us</h2>
            <p>If you have any questions or need help with your order, feel free to <a href="mailto:info@example.com">email us</a>.</p>
        </section>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Affiliate Marketing Hub. All rights reserved.</p>
    </footer>

    <!-- JavaScript -->
    <script>
        // Log a simple message when the document is ready
        document.addEventListener('DOMContentLoaded', () => {
            console.log("Welcome to the Affiliate Marketing Hub!");
        });
    </script>
</body>
</html>
