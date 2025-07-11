<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RAMESH OIL MILL - Premium Quality Oils</title>
    <meta name="description" content="Ramesh Oil Mill offers 100% pure traditional oils including groundnut, gingelly, and coconut oils. Natural, chemical-free products for cooking and wellness.">
    <meta name="keywords" content="pure oil, traditional oil mill, groundnut oil, gingelly oil, coconut oil, natural oils, Tamil Nadu oil mill">
    
    <!-- Favicon -->
    <link rel="icon" href="images/favicon.ico" type="image/x-icon">
    
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&family=Noto+Sans+Tamil:wght@400;500;600&display=swap" rel="stylesheet">
    
    <!-- CSS -->
    <style>
        :root {
            --primary-color: #FFD700;
            --secondary-color: #0056b3;
            --accent-color: #FF6B00;
            --text-color: #333;
            --light-bg: #FFF9E6;
            --white: #FFFFFF;
            --black: #000000;
            --shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            --border-radius: 8px;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Poppins', 'Noto Sans Tamil', sans-serif;
            background-color: var(--light-bg);
            color: var(--text-color);
            line-height: 1.6;
        }
        
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Header Styles */
        header {
            background: linear-gradient(135deg, var(--primary-color), var(--accent-color));
            padding: 20px 0;
            text-align: center;
            box-shadow: var(--shadow);
            position: relative;
        }
        
        .logo {
            max-width: 150px;
            margin-bottom: 15px;
        }
        
        h1 {
            font-size: 2.5rem;
            color: var(--secondary-color);
            margin-bottom: 10px;
            font-weight: 700;
        }
        
        h2 {
            font-size: 2rem;
            color: var(--secondary-color);
            margin: 25px 0 15px;
        }
        
        h3, h4 {
            color: var(--secondary-color);
            margin: 15px 0;
        }
        
        .tagline {
            font-size: 1.2rem;
            font-weight: 500;
            color: var(--accent-color);
            margin-bottom: 15px;
        }
        
        hr {
            border: 0;
            height: 2px;
            background: linear-gradient(to right, transparent, var(--secondary-color), transparent);
            margin: 20px auto;
            max-width: 800px;
        }
        
        /* Hero Section */
        .hero {
            padding: 40px 0;
            text-align: center;
            background-color: var(--white);
            margin: 20px 0;
            border-radius: var(--border-radius);
            box-shadow: var(--shadow);
        }
        
        .hero p {
            max-width: 800px;
            margin: 0 auto;
            font-size: 1.1rem;
            padding: 0 20px;
        }
        
        /* Product Showcase */
        .section-title {
            background-color: var(--secondary-color);
            color: var(--white);
            padding: 15px;
            margin: 30px 0 20px;
            border-radius: var(--border-radius);
            text-align: center;
        }
        
        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin: 30px 0;
        }
        
        .product-card {
            background: var(--white);
            border-radius: var(--border-radius);
            overflow: hidden;
            box-shadow: var(--shadow);
            transition: transform 0.3s ease;
        }
        
        .product-card:hover {
            transform: translateY(-5px);
        }
        
        .product-img {
            width: 100%;
            height: 250px;
            object-fit: cover;
        }
        
        .product-info {
            padding: 15px;
            text-align: center;
        }
        
        .product-name {
            font-weight: 600;
            margin-bottom: 10px;
            color: var(--secondary-color);
        }
        
        /* Tables */
        .price-table {
            width: 100%;
            max-width: 800px;
            margin: 20px auto;
            border-collapse: collapse;
            background: var(--white);
            box-shadow: var(--shadow);
            border-radius: var(--border-radius);
            overflow: hidden;
        }
        
        .price-table th {
            background-color: var(--secondary-color);
            color: var(--white);
            padding: 12px;
            text-align: center;
        }
        
        .price-table td {
            padding: 10px;
            text-align: center;
            border-bottom: 1px solid #eee;
        }
        
        .price-table tr:nth-child(even) {
            background-color: #f9f9f9;
        }
        
        .price-table tr:hover {
            background-color: #f1f1f1;
        }
        
        /* Image Gallery */
        .image-gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin: 30px 0;
        }
        
        .gallery-img {
            width: 300px;
            height: 200px;
            object-fit: cover;
            border-radius: var(--border-radius);
            transition: transform 0.3s ease;
            box-shadow: var(--shadow);
        }
        
        .gallery-img:hover {
            transform: scale(1.05);
        }
        
        /* Footer */
        footer {
            background-color: var(--secondary-color);
            color: var(--white);
            padding: 30px 0;
            text-align: center;
            margin-top: 50px;
        }
        
        .contact-info {
            margin-bottom: 20px;
        }
        
        .contact-info a {
            color: var(--white);
            text-decoration: none;
            display: inline-block;
            margin: 0 10px;
            font-size: 1.1rem;
        }
        
        .contact-info a:hover {
            color: var(--primary-color);
        }
        
        .social-links {
            margin: 20px 0;
        }
        
        .social-links a {
            color: var(--white);
            font-size: 1.5rem;
            margin: 0 10px;
            transition: color 0.3s ease;
        }
        
        .social-links a:hover {
            color: var(--primary-color);
        }
        
        .copyright {
            font-size: 0.9rem;
            opacity: 0.8;
        }
        
        /* Responsive Adjustments */
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            
            h2 {
                font-size: 1.5rem;
            }
            
            .products-grid {
                grid-template-columns: 1fr;
            }
            
            .price-table {
                font-size: 0.9rem;
            }
            
            .gallery-img {
                width: 100%;
                max-width: 200px;
            }
        }
        
        /* Animation */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .fade-in {
            animation: fadeIn 1s ease forwards;
        }
        
        /* Button Styles */
        .btn {
            display: inline-block;
            background-color: var(--accent-color);
            color: white;
            padding: 10px 20px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 500;
            margin: 10px 5px;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
        }
        
        .btn:hover {
            background-color: var(--secondary-color);
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .btn-outline {
            background: transparent;
            border: 2px solid var(--accent-color);
            color: var(--accent-color);
        }
        
        .btn-outline:hover {
            background: var(--accent-color);
            color: white;
        }
     
    </style>
</head>
<body>
    <!-- Header Section -->
    <header class="fade-in">
        <div class="container">
            <img src="images/logo.png" alt="Ramesh Oil Mill Logo" class="logo">
            <h1>RAMESH OIL MILL</h1>
            <h4 >HUNDRED PERCENT PURE <i class="fas fa-check-circle"></i></h4>
        </div>
    </header>
    
    <!-- Hero Section -->
    <section class="hero fade-in">
        <div class="container">
            <p>At Ramesh Oil Mill, we blend tradition with quality to deliver the finest oils to your home and business. With decades of expertise in oil extraction and production, we are committed to offering pure, natural, and chemical-free oils that preserve the authentic taste and nutritional value you deserve. Whether it's for cooking, wellness, or industrial use, our range of premium oils is crafted with care, trust, and a passion for excellence.</p>
            <p style="font-weight: 600; margin-top: 15px; color: var(--accent-color);">Experience purity. Choose Ramesh Oil Mill.</p>
            <a href="#products" class="btn">Our Products</a>
            <a href="#contact" class="btn btn-outline">Contact Us</a>
        </div>
    </section>
    
    <!-- Product Label Showcase -->
    <section class="container fade-in">
        <center>
            <img src="images/label.jpg" alt="Ramesh Oil Mill Product Label" style="max-width: 100%; height: auto; border-radius: var(--border-radius); box-shadow: var(--shadow);">
        </center>
    </section>
    
    <hr>
    
    <!-- Main Products Section -->
    <section id="products" class="container fade-in">
        <h2 class="section-title">OUR PRODUCTS</h2>
        <center>
            <h4>Ground Nut Oil, Gingely Oil, Coconut Oil, Ground Nuts</h4>
        </center>
        
        <div class="products-grid">
            <div class="product-card">
                <img src="images/oil.png" alt="Groundnut Oil" class="product-img">
                <div class="product-info">
                    <h3 class="product-name">Groundnut Oil</h3>
                    <p>Pure, cold-pressed groundnut oil with rich flavor and high smoke point.</p>
                </div>
            </div>
            
            <div class="product-card">
                <img src="images/222.jpeg" alt="Gingelly Oil" class="product-img">
                <div class="product-info">
                    <h3 class="product-name">Gingelly Oil</h3>
                    <p>Traditional sesame oil with authentic taste and numerous health benefits.</p>
                </div>
            </div>
            
            <div class="product-card">
                <img src="images/gnd img.png" alt="Ground Nuts" class="product-img">
                <div class="product-info">
                    <h3 class="product-name">Ground Nuts</h3>
                    <p>Premium quality peanuts for direct consumption or oil extraction.</p>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Product Prices Section -->
    <section class="container fade-in">
        <h2 class="section-title">PRODUCT PRICES</h2>
        
        <table class="price-table">
            <tr>
                <th>Product Name</th>
                <th>Price per Liter</th>
                <th>500ml</th>
                <th>300ml</th>
                <th>200ml</th>
            </tr>
            
            <tr>
                <td>கடலை எண்ணெய் (Groundnut Oil)</td>
                <td>₹220</td>
                <td>₹110</td>
                <td>₹66</td>
                <td>₹44</td>
            </tr>
            
            <tr>
                <td>நல்லெண்ணெய் (Gingelly Oil)</td>
                <td>₹380</td>
                <td>₹190</td>
                <td>₹114</td>
                <td>₹76</td>
            </tr>
            
            <tr>
                <td>தேங்காய்எண்ணெய் (Coconut Oil)</td>
                <td>₹300</td>
                <td>₹150</td>
                <td>₹80</td>
                <td>₹60</td>
            </tr>
            
            <tr>
                <td>விலக்கெண்ணெய் (Castor Oil)</td>
                <td>₹250</td>
                <td>₹125</td>
                <td>₹75</td>
                <td>₹50</td>
            </tr>
            
            <tr>
                <td>நிலக்கடலை (Groundnuts)</td>
                <td>₹120/kg</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
            </tr>
        </table>
        
        <div class="image-gallery">
            <img src="images/4.jpeg" alt="Oil Products" class="gallery-img">
            <img src="images/co oil.png" alt="Coconut Oil" class="gallery-img">
            <img src="images/oil.png" alt="Oil Mill" class="gallery-img">
        </div>
    </section>
    
    <!-- Byproducts Section -->
    <section class="container fade-in">
        <h2 class="section-title">பிண்ணாக்கு (Oil Cake)</h2>
        
        <table class="price-table">
            <tr>
                <th>PRODUCTS</th>
                <th>PRICE PER KG</th>
            </tr>
            
            <tr>
                <td>கடலை (Groundnut Cake)</td>
                <td>₹50</td>
            </tr>
            
            <tr>
                <td>எள் (Sesame Cake)</td>
                <td>₹30</td>
            </tr>
            
            <tr>
                <td>கொட்ட முத்து (Coconut Cake)</td>
                <td>₹20</td>
            </tr>
        </table>
        
        <div class="image-gallery">
            <img src="images/sesame 5lt.png" alt="Sesame Oil" class="gallery-img">
            <img src="images/grd3.jpeg" alt="Groundnut Cake" class="gallery-img">
            <img src="images/sesame5 lt.png" alt="Sesame Products" class="gallery-img">
        </div>
    </section>
    
    <!-- Oil Processing Section -->
    <section class="container fade-in">
        <h2 class="section-title">எண்ணெய் ஆட்டுவதற்கு (Oil Processing)</h2>
        
        <table class="price-table">
            <tr>
                <th>PRODUCTS</th>
                <th>PRICE PER KG</th>
            </tr>
            
            <tr>
                <td>கடலை </td>
                <td>₹12</td>
            </tr>
            
            <tr>
                <td>எள் </td>
                <td>₹14</td>
            </tr>
            
            <tr>
                <td>கொட்ட முத்து </td>
                <td>₹12</td>
            </tr>
        </table>
    </section>

    <section class="container fade-in">
        <h2 class="section-title">காய்  உடைப்பதற்கு</h2>
        
        <table class="price-table">
            <tr>
                <th>PRODUCT</th>
                <th>PRICE PER KG</th>
            </tr>  
            <tr>
                <td>கடலை காய் </td>
                <td>₹2.50</td>
            </tr>
        </table>
    </section>
    
    <!-- Footer -->
    <footer id="contact" class="fade-in">
        <div class="container">
            <h2>CONTACT US</h2>
            
            <div class="contact-info">
                <a href="tel:7299997489"><i class="fas fa-phone"></i> 7299997489</a>
                <a href="tel:8300165464"><i class="fas fa-phone"></i> 8300165464</a>
                <a href="mailto:giridharanramesh@gmail.com"><i class="fas fa-envelope"></i> giridharanramesh@gmail.com</a>                
            </div>        
            <div class="social-links">
              <a href="7299997489," aria-label="WhatsApp"><i class="fab fa-whatsapp"></i></a>
            </div>            
            <p class="copyright">© 2023 Ramesh Oil Mill. All Rights Reserved.</p>
        </div>
    </footer>
    
    <!-- Script for animations -->
    <script>
        // Simple intersection observer for scroll animations
        document.addEventListener('DOMContentLoaded', function() {
            const fadeElements = document.querySelectorAll('.fade-in');
            
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.style.opacity = 1;
                    }
                });
            }, { threshold: 0.1 });
            
            fadeElements.forEach(el => {
                el.style.opacity = 0;
                observer.observe(el);
            });
            
            // Smooth scrolling for anchor links
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function(e) {
                    e.preventDefault();
                    document.querySelector(this.getAttribute('href')).scrollIntoView({
                        behavior: 'smooth'
                    });
                });
            });
        });
    </script>
</body>
</html>
