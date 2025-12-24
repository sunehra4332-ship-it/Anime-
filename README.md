<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anime Video Store</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Anime Video Store</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Welcome to Our Anime Collection</h2>
        <p>Discover the best anime videos, from classics to new releases. Rent or buy DVDs and Blu-rays!</p>
        <img src="https://via.placeholder.com/800x400?text=Anime+Banner" alt="Anime Banner" class="banner">
    </section>

    <section id="products">
        <h2>Featured Products</h2>
        <div class="product-grid">
            <div class="product">
                <img src="https://via.placeholder.com/200x300?text=Naruto" alt="Naruto DVD">
                <h3>Naruto Complete Series</h3>
                <p>$49.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/200x300?text=One+Piece" alt="One Piece DVD">
                <h3>One Piece Vol. 1</h3>
                <p>$19.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/200x300?text=Attack+on+Titan" alt="Attack on Titan DVD">
                <h3>Attack on Titan Season 1</h3>
                <p>$29.99</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form id="contact-form">
            <label for="name">Name:</label>
            <input type="text" id="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" required>
            <label for="message">Message:</label>
            <textarea id="message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2023 Anime Video Store. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</bo
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: white;
    padding: 1rem;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 1rem;
}

nav a {
    color: white;
    text-decoration: none;
}

section {
    padding: 2rem;
    max-width: 1200px;
    margin: 0 auto;
}

.banner {
    width: 100%;
    height: auto;
}

.product-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
    justify-content: center;
}

.product {
    background: white;
    border: 1px solid #ddd;
    padding: 1rem;
    text-align: center;
    width: 200px;
}

.product img {
    width: 100%;
    height: auto;
}

button {
    background-color: #ff6600;
    color: white;
    border: none;
    padding: 0.5rem 1rem;
    cursor: pointer;
}

button:hover {
    background-color: #e55a00;
}

form {
    display: flex;
    flex-direction: column;
    max-width: 400px;
    margin: 0 auto;
}

input, textarea {
    margin-bottom: 1rem;
    padding: 0.5rem;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem;
}
document.getElementById('contact-form').addEventListener('submit', function(e) {
    e.preventDefault();
    alert('Thank you for your message! We\'ll get back to you soon.');
    // In a real app, send data to a server here
});dy>
</html>
