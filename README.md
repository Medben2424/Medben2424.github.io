<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GreenGazon | Landscaping Services</title>
    <style>
        :root {
            --primary-green: #2E8B57;  /* Sea Green */
            --secondary-green: #3CB371; /* Medium Sea Green */
            --light-grass: #90EE90;    /* Light Green */
        }
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background: var(--primary-green);
            color: white;
            padding: 2rem 0;
            text-align: center;
        }
        nav {
            background: var(--secondary-green);
            padding: 1rem;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .hero {
            background: linear-gradient(rgba(46, 139, 87, 0.8), rgba(46, 139, 87, 0.8)), 
                        url('https://images.unsplash.com/photo-1600628421060-939639517883') no-repeat center/cover;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
        }
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 20px;
        }
        .service-card {
            border: 1px solid var(--light-grass);
            padding: 20px;
            margin: 10px 0;
            border-radius: 5px;
        }
        footer {
            background: var(--primary-green);
            color: white;
            text-align: center;
            padding: 1rem 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>GreenGazon</h1>
        <p>Professional Landscaping Services</p>
    </header>
    <nav>
        <a href="#services">Services</a>
        <a href="#testimonials">Testimonials</a>
        <a href="#contact">Contact</a>
    </nav>
    <section class="hero">
        <div>
            <h2>Your Perfect Lawn Starts Here</h2>
            <button style="background: white; color: var(--primary-green); border: none; padding: 10px 20px; font-weight: bold;">Get a Free Quote</button>
        </div>
    </section>
    <div class="container">
        <section id="services">
            <h2>Our Services</h2>
            <div class="service-card">
                <h3>Lawn Maintenance</h3>
                <p>Weekly cutting, edging, and fertilization.</p>
            </div>
            <div class="service-card">
                <h3>Landscape Design</h3>
                <p>Custom garden planning and installation.</p>
            </div>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <p>Email: hello@greengazon.com</p>
        </section>
    </div>
    <footer>
        © 2024 GreenGazon. All rights reserved.
    </footer>
</body>
</html>
