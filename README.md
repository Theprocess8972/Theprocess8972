 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Business Bandits - Steal the Best Deals!</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header -->
    <header class="header">
        <div class="logo">
            <img src="images/bandit-logo.png" alt="Business Bandits Logo">
            <h1>Business Bandits</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Top Deals</a></li>
                <li><a href="#">Categories</a></li>
                <li><a href="#">Blog</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
        </nav>
        <div class="search-bar">
            <input type="text" placeholder="Search deals...">
            <button>Search</button>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h2>Steal the Best Deals on the Internet!</h2>
        <form class="search-form">
            <input type="text" placeholder="Find the best deals on..." />
            <button type="submit">Start Saving</button>
        </form>
    </section>

    <!-- Featured Deals -->
    <section class="featured-deals">
        <h3>Featured Deals</h3>
        <div class="deals-carousel">
            <!-- Add deal items here -->
            <div class="deal-item">
                <img src="images/deal1.jpg" alt="Deal 1">
                <p>Product Name</p>
                <p><span class="original-price">$100</span> $50</p>
                <button>Grab the Deal</button>
            </div>
            <!-- Repeat similar items -->
        </div>
    </section>

    <!-- Categories -->
    <section class="categories">
        <h3>Shop by Category</h3>
        <div class="category-grid">
            <div class="category-item">Electronics</div>
            <div class="category-item">Fashion</div>
            <div class="category-item">Home & Kitchen</div>
            <div class="category-item">Travel Deals</div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="newsletter">
            <h4>Join the Bandit Crew!</h4>
            <input type="email" placeholder="Your email">
            <button>Sign Up</button>
        </div>
        <div class="social-links">
            <a href="#">Instagram</a>
            <a href="#">Twitter</a>
            <a href="#">Facebook</a>
        </div>
    </footer>
</body>
</html>
