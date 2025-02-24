# KeyYemCeeApparel
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KeyYemCee Apparel</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #222;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
            background: white;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 10px;
        }
        .gallery img {
            width: 100%;
            border-radius: 8px;
        }
        footer {
            text-align: center;
            padding: 15px;
            background: #222;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>KeyYemCee Apparel</h1>
        <p>Quality Apparel for Kids and Students</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About Us</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="about">
            <h2>About Us</h2>
            <p>Located in Kannur, Kerala, KeyYemCee Apparel specializes in high-quality kids' T-shirts and school/college uniforms.</p>
        </section>
        <section id="gallery">
            <h2>Our Collection</h2>
            <div class="gallery">
                <img src="shirt1.jpg" alt="Kids T-Shirt">
                <img src="uniform1.jpg" alt="School Uniform">
                <img src="shirt2.jpg" alt="College Uniform">
            </div>
        </section>
    </div>
    <footer>
        <p>Visit us at Varam Road, Kannur | Contact: info@keyyemcee.com</p>
    </footer>
</body>
</html>
