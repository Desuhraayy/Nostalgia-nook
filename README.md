# Nostalgia-nook
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nostalgia Nook</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0e4f7;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header, footer {
            background-color: #ff99cc;
            color: white;
            text-align: center;
            padding: 20px;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: white;
            font-weight: bold;
        }
        .container {
            padding: 20px;
        }
        .products img {
            max-width: 100%;
            height: auto;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .product {
            background: white;
            border: 2px solid #ff99cc;
            border-radius: 10px;
            padding: 10px;
            width: calc(33% - 40px);
            box-sizing: border-box;
            text-align: center;
        }
        .contact-info {
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Nostalgia Nook</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About Us</a>
            <a href="#products">Products</a>
        </nav>
    </header>

    <div id="home" class="container">
        <h2>Welcome to Nostalgia Nook</h2>
        <p>Your go-to place for all things nostalgic! We specialize in reselling toys and items from the 90s and early 2000s, bringing back the joy and memories of your childhood.</p>
    </div>

    <div id="about" class="container">
        <h2>About Us</h2>
        <p>At Nostalgia Nook, we are passionate about bringing back the magic of yesteryears. From Groovy Girls to Polly Pocket, we curate a unique collection of vintage toys and collectibles that take you down memory lane. Our mission is to preserve the joy of the past and make it accessible to collectors and enthusiasts alike.</p>
    </div>

    <div id="products" class="container">
        <h2>Our Products</h2>
        <div class="products">
            <div class="product">
                <img src="placeholder1.jpg" alt="Product 1">
                <h3>Product Name 1</h3>
                <p>Short description of the product.</p>
            </div>
            <div class="product">
                <img src="placeholder2.jpg" alt="Product 2">
                <h3>Product Name 2</h3>
                <p>Short description of the product.</p>
            </div>
            <div class="product">
                <img src="placeholder3.jpg" alt="Product 3">
                <h3>Product Name 3</h3>
                <p>Short description of the product.</p>
            </div>
        </div>
    </div>

    <footer>
        <div class="contact-info">
            <p>Contact us at: <a href="mailto:Deserai.disher@gmail.com">Deserai.disher@gmail.com</a></p>
            <p>Check out our Poshmark store: <a href="https://poshmark.com/closet/desuhraayy" target="_blank">@desuhraayy</a></p>
        </div>
    </footer>
</body>
</html>
