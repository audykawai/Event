<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Korean Beauty Event</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff5f7;
            color: #000000;
            line-height: 1.6;
        }
        
        header {
            background: linear-gradient(135deg, #ffb6c1, #d8bfd8);
            color: black;
            text-align: center;
            padding: 2rem 0;
            box-shadow: 0 4px 30px rgba(0,0,0,0.1);
            position: relative;
            overflow: hidden;
        }
        
        .header-content {
            position: relative;
            z-index: 2;
        }
        
        .header-image {
            position: absolute;
            width: 150px;
            opacity: 0.2;
        }
        
        .header-image-1 {
            top: 20px;
            left: 20px;
        }
        
        .header-image-2 {
            bottom: 20px;
            right: 20px;
            transform: rotate(15deg);
        }
        
        h1 {
            margin: 0;
            font-size: 2.5rem;
            text-shadow: 1px 1px 3px rgba(0,0,0,0.2);
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 2rem;
        }
        
        .hero-image {
            width: 100%;
            border-radius: 15px;
            margin: 1.5rem 0;
            box-shadow: 0 8px 20px rgba(0,0,0,0.1);
        }
        
        .event-info {
            background-color: white;
            border-radius: 15px;
            padding: 2rem;
            margin-bottom: 2rem;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
        }
        
        .price-tag {
            background-color: #f3e5f5;
            color: #9c27b0;
            padding: 1rem;
            border-radius: 10px;
            text-align: center;
            font-weight: bold;
            font-size: 1.2rem;
            margin: 1.5rem 0;
            border-left: 5px solid #ba68c8;
        }
        
        .workshop-section {
            display: flex;
            flex-wrap: wrap;
            gap: 1.5rem;
            margin: 2rem 0;
        }
        
        .workshop-card {
            flex: 1 1 300px;
            background: white;
            border-radius: 12px;
            padding: 1.5rem;
            box-shadow: 0 4px 8px rgba(0,0,0,0.05);
            border-top: 4px solid #ffb6c1;
            transition: transform 0.3s ease;
        }
        
        .workshop-card:hover {
            transform: translateY(-5px);
        }
        
        .workshop-card h3 {
            color: #ba68c8;
            margin-top: 0;
        }
        
        .workshop-image {
            width: 100%;
            height: 800px;
            object-fit: cover;
            border-radius: 8px;
            margin-bottom: 1rem;
        }
        
        .registration {
            background: linear-gradient(135deg, #f3e5f5, #ffebee);
            padding: 2rem;
            border-radius: 15px;
            margin-top: 2rem;
        }
        
        .registration h2 {
            color: #ab47bc;
            text-align: center;
            margin-top: 0;
        }
        
        .form-container {
            background: white;
            padding: 1.5rem;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.05);
        }
        
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 1rem;
            margin: 2rem 0;
        }
        
        .gallery img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 8px;
            transition: transform 0.3s ease;
        }
        
        .gallery img:hover {
            transform: scale(1.03);
        }
        
        footer {
            text-align: center;
            padding: 1.5rem;
            background-color: #f3e5f5;
            margin-top: 2rem;
            color: #7e57c2;
        }
        
        @media (max-width: 700px) {
            .container {
                padding: 1rem;
            }
            
            .workshop-section {
                flex-direction: column;
            }
            
            .header-image {
                width: 100px;
            }
        }
    </style>
</head>
<body>
    <header>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRg7zRpTNAlVTcC_QNat5r6MpO807BbN0R2xQ&s" alt="Korean Beauty" class="header-image header-image-1">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTLj4psMXCtZv2KFX7Yd0AGDLWeRP-pF_xbRg&s" alt="Korean Makeup" class="header-image header-image-2">
        <div class="header-content">
            <h1>Korean Beauty Workshop</h1>
            <p>Learn the secrets of K-Beauty makeup, hairstyling, and fashion</p>
        </div>
    </header>
    
    <div class="container">
        <img src="https://img.freepik.com/premium-photo/korean-girl-is-holding-up-makeup-product_1290348-748.jpg?w=360" alt="Korean Beauty Workshop" class="hero-image">
        
        <section class="event-info">
            <h2>About the Event</h2>
            <p>Join us for an exciting day of learning and transformation at our Korean Beauty Workshop! This event will teach you all about the latest trends in Korean beauty, from flawless makeup techniques to stylish hairstyles and outfit coordination.</p>
            
            <p>Our expert instructors will guide you through hands-on sessions where you'll learn to create the perfect Korean-inspired look. Whether you're a beauty beginner or an experienced enthusiast, this workshop will help you master the art of K-Beauty.</p>
            
            <div class="price-tag">
                Ticket Price: Rp 150.000 per person
            </div>
            
            <h3>What You'll Learn:</h3>
            <div class="workshop-section">
                <div class="workshop-card">
                    <img src="https://storage.oresa.id/live/images/img-news/1655480964_62aca284f3719.jpeg" alt="Korean Hairstyling" class="workshop-image">
                    <h3>Korean Makeup</h3>
                    <p>Learn the step-by-step process to achieve the perfect Korean glass skin look, gradient lips, and natural eye makeup that enhances your features.</p>
                </div>
                
                <div class="workshop-card">
                    <img src="https://pantau.sgp1.cdn.digitaloceanspaces.com/images/220407033029-racun-drakor-menyebar-di-indonesia-korean-look-akan-jadi-tren-makeup-lebaran.jpeg" alt="Korean Hairstyling" class="workshop-image">
                    <h3>Korean Hairstyling</h3>
                    <p>Master popular Korean hairstyles including soft waves, half-up dos, and cute hair accessories techniques.</p>
                </div>
                
                <div class="workshop-card">
                    <img src="https://i.pinimg.com/736x/db/73/81/db7381eff54d825859bab4865a6709fe.jpg" alt="Korean Hairstyling" class="workshop-image">
                    <h3>Korean Fashion</h3>
                    <p>Discover how to put together stylish Korean-inspired outfits that are both trendy and comfortable.</p>
                </div>
            </div>
            
            <h3>Event Gallery</h3>
            <div class="gallery">
                <img src="https://luxshinehair.com/wp-content/uploads/2023/01/cute-korean-hairstyles-6.jpg" alt="Korean Beauty 1">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQioD3Uw1k2NR0jpzXwCUXwvUcOzL4HB17DhA&s" alt="Korean Beauty 2">
                <img src="https://coverclap.com/assets/blog/beginners-guide-to-korean-makeup/korean-makeup-look-eyebrows-beginners.jpeg" alt="Korean Beauty 3">
                <img src=https://thechicsavvy.com/wp-content/uploads/2025/04/Korean-Hairstyle7-775x1024.webp" alt="Korean Beauty 4">
            </div>
            
            <h3>What's Included:</h3>
            <ul>
                <li>Hands-on instruction from professional beauty experts</li>
                <li>All necessary tools and products to use during the workshop</li>
                <li>Goodie bag with sample products</li>
                <li>Light refreshments</li>
                <li>Certificate of participation</li>
            </ul>
        </section>
        
        <section class="registration">
            <h2>Register Now</h2>
            <p>Secure your spot today! Limited seats available.</p>
            
            <div class="form-container">
                <!-- Replace this iframe with your actual Google Form embed code -->
                <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSfBrUC2oEZU3Oq4atVyt8Bhz5bQJDFt9zTNby4Zq4DuP2dOVQ/viewform?embedded=true" width="100%" height="1000%" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
                <p style="text-align: center; color: #ab47bc; margin-top: 1rem;">*After submitting the form, you will receive payment instructions via email.</p>
            </div>
        </section>
    </div>
    
    <footer>
        <p>© 2023 Korean Beauty Workshop | Contact us: info@koreanbeautyworkshop.com</p>
    </footer>
</body>
</html>
