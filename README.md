# Cherryblossom-website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CherryBlossom - Makeup</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff0f5;
            color: #333;
        }
        header {
            background-color: #e75480;
            color: white;
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        header h1 {
            font-size: 1.8rem;
        }
        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        nav ul li {
            margin: 0 1rem;
        }
        nav ul li a {
            text-decoration: none;
            color: white;
            font-weight: bold;
        }
        .hero {
            text-align: center;
            padding: 4rem 2rem;
            background: url('https://via.placeholder.com/1200x600') no-repeat center/cover;
            color: white;
        }
        .hero h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
        }
        .btn {
            background-color: #e75480;
            color: white;
            padding: 0.8rem 1.5rem;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }
        .products {
            padding: 2rem;
            text-align: center;
        }
        .products h3 {
            font-size: 2rem;
            margin-bottom: 1rem;
        }
        .product-list {
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
            justify-content: center;
        }
        .product-item {
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 1rem;
            width: 250px;
            background-color: white;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .product-item img {
            max-width: 100%;
            border-radius: 5px;
        }
        .product-item h4 {
            font-size: 1.2rem;
            margin: 1rem 0;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>CherryBlossom</h1>
        <nav>
            <ul>
                <li><a href="#products">Products</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h2>Welcome to CherryBlossom</h2>
        <p>Your ultimate destination for premium blushes and lipsticks.</p>
        <a href="#products" class="btn">Shop Now</a>
    </section>

    <section id="products" class="products">
        <h3>Our Products</h3>
        <div class="product-list">
            <div class="product-item">
                <img src="https://via.placeholder.com/250" alt="Blush">
                <h4>Velvet Touch Blush</h4>
                <p>Price: $15.99</p>
            </div>
            <div class="product-item">
                <img src="https://via.placeholder.com/250" alt="Lipstick">
                <h4>Matte Lipstick</h4>
                <p>Price: $12.99</p>
            </div>
            <div class="product-item">
                <img src="https://via.placeholder.com/250" alt="Blush">
                <h4>Rose Glow Blush</h4>
                <p>Price: $18.99</p>
            </div>
            <div class="product-item">
                <img src="https://via.placeholder.com/250" alt="Lipstick">
                <h4>Shimmer Lipstick</h4>
                <p>Price: $14.99</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 CherryBlossom. All Rights Reserved.</p>
    </footer>
</body>
</html>

