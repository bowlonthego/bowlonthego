
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bowl on the Go</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f8f8f8;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ffcc00;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }
        h1 {
            margin: 0;
            color: #333;
        }
        p {
            color: #555;
        }
        .menu {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin: 20px 5%;
        }
        .menu-item {
            background-color: white;
            border: 1px solid #ccc;
            border-radius: 8px;
            padding: 20px;
            width: 30%;
            text-align: center;
            transition: transform 0.2s, box-shadow 0.2s;
            margin-bottom: 20px;
        }
        .menu-item:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 16px rgba(0,0,0,0.3);
        }
        .menu-item h2 {
            color: #ff6600;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        img {
            width: 100%;
            border-radius: 8px;
        }
        .instagram-link {
            margin: 20px 0;
        }
        @media (max-width: 768px) {
            .menu-item {
                width: 100%;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Bowl on the Go</h1>
    <p>Delicious Rice Bowls for Only Rp 15.000!</p>
</header>

<section class="menu">
    <div class="menu-item">
        <h2>Chicken Curry Rice Bowl</h2>
        <img src="https://example.com/chicken_curry.jpg" alt="Chicken Curry Rice Bowl">
        <p>Ayam tender dalam saus kari yang kaya rasa.</p>
        <p>Harga: Rp 15.000</p>
    </div>
    <div class="menu-item">
        <h2>Tamago Curry Rice Bowl</h2>
        <img src="https://example.com/tamago_curry.jpg" alt="Tamago Curry Rice Bowl">
        <p>Kombinasi saus kari dan telur rebus yang lembut.</p>
        <p>Harga: Rp 15.000</p>
    </div>
    <div class="menu-item">
        <h2>Pesan Sekarang!</h2>
        <p>Pesan di GrabFood & GoFood.</p>
        <p>Ikuti kami untuk promo terbaru!</p>
    </div>
</section>

<div class="instagram-link">
    <h2>Follow Us on Instagram!</h2>
    <a href="https://www.instagram.com/bowl.onthe_go/profilecard/?igsh=MTg4NzhqbXNiZ3U1bA==" target="_blank" style="color: #ff6600; text-decoration: none;">@bowl.onthe_go</a>
</div>

<footer>
    <p>© 2024 Bowl on the Go. All rights reserved.</p>
</footer>

</body>
</html>
