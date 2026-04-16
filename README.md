<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Shri Siddhivinayak Store</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
}

header {
    background: #ff6600;
    color: white;
    text-align: center;
    padding: 15px;
}

nav {
    background: #333;
    display: flex;
    justify-content: center;
}

nav a {
    color: white;
    padding: 14px;
    text-decoration: none;
}

nav a:hover {
    background: #ff6600;
}

.hero {
    text-align: center;
    padding: 20px;
}

.hero img {
    width: 90%;
    max-width: 400px;
}

section {
    padding: 20px;
    text-align: center;
}

.services {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.card {
    background: #f4f4f4;
    margin: 10px;
    padding: 15px;
    width: 250px;
    border-radius: 10px;
}

iframe {
    width: 90%;
    height: 300px;
    border: 0;
    border-radius: 10px;
}

footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 10px;
}

.whatsapp {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background: #25D366;
    color: white;
    padding: 12px 15px;
    border-radius: 50px;
    text-decoration: none;
    font-weight: bold;
}

/* Mobile */
@media (max-width: 600px) {
    .services {
        flex-direction: column;
        align-items: center;
    }
}
</style>
</head>

<body>

<header>
    <h1>Shri Siddhivinayak Store</h1>
    <p>Electronic & Paint Store</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">Services</a>
    <a href="#">Contact</a>
</nav>

<div class="hero">
    <img src="logo.png" alt="Store Logo">
</div>

<section>
    <h2>About Us / हमारे बारे में</h2>
    <p>
        We provide best quality electronics and paints.<br>
        हम आपको बेहतरीन इलेक्ट्रॉनिक्स और पेंट्स उपलब्ध कराते हैं।
    </p>
</section>

<section>
    <h2>Our Services / हमारी सेवाएं</h2>

    <div class="services">
        <div class="card">
            <h3>Electronics</h3>
            <p>All types of electronic items available.</p>
        </div>

        <div class="card">
            <h3>Paints</h3>
            <p>High quality paints and colors.</p>
        </div>

        <div class="card">
            <h3>Repair</h3>
            <p>Electronic repair services available.</p>
        </div>
    </div>
</section>

<section>
    <h2>Contact / संपर्क करें</h2>
    <p>📞 Phone: 9455444892</p>
    <p>📧 Email: shrishiddhivinayak815@gmail.com</p>
    <p>📍 Address: Rampur, Pakka Talab, Jaunpur</p>

    <!-- Google Map -->
    <h3>Our Location / हमारी लोकेशन</h3>
    <iframe 
        src="https://maps.google.com/maps?q=Rampur%20Pakka%20Talab%20Jaunpur&t=&z=13&ie=UTF8&iwloc=&output=embed">
    </iframe>
</section>

<footer>
    <p>© 2026 Shri Siddhivinayak Store</p>
</footer>

<a class="whatsapp" href="https://wa.me/919455444892" target="_blank">
    Chat on WhatsApp
</a>

</body>
</html>
