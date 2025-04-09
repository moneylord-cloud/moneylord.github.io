# moneylord.github.io
my-website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>El Events - Wedding & Event Decor & Management</title>
    <style>
        :root {
            --primary: #e8c6b0;
            --secondary: #d4a373;
            --dark: #3a2e24;
            --light: #f8f1e9;
            --accent: #c08552;
        }
        
        body {
            font-family: 'Playfair Display', serif;
            margin: 0;
            padding: 0;
            color: var(--dark);
            background-color: var(--light);
        }
        
        header {
            background-image: linear-gradient(rgba(58, 46, 36, 0.7), rgba(58, 46, 36, 0.7)), url('hero-image.jpg');
            background-size: cover;
            background-position: center;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
        }
        
        .logo {
            font-size: 4rem;
            font-weight: 700;
            margin-bottom: 1rem;
            color: var(--primary);
        }
        
        .tagline {
            font-size: 1.5rem;
            margin-bottom: 2rem;
            font-style: italic;
        }
        
        nav {
            background-color: var(--dark);
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 100;
        }
        
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            margin: 0;
            padding: 0;
        }
        
        nav li {
            margin: 0 1.5rem;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            font-size: 1.1rem;
            transition: color 0.3s;
        }
        
        nav a:hover {
            color: var(--primary);
        }
        
        .btn {
            background-color: var(--accent);
            color: white;
            padding: 0.8rem 1.5rem;
            border: none;
            border-radius: 25px;
            font-size: 1rem;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        
        .btn:hover {
            background-color: var(--secondary);
        }
        
        section {
            padding: 5rem 10%;
        }
        
        .section-title {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 3rem;
            color: var(--dark);
        }
        
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .service-card {
            background-color: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }
        
        .service-card:hover {
            transform: translateY(-10px);
        }
        
        .service-img {
            height: 200px;
            width: 100%;
            object-fit: cover;
        }
        
        .service-content {
            padding: 1.5rem;
        }
        
        .service-title {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            color: var(--accent);
        }
        
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 1rem;
        }
        
        .gallery-item {
            height: 250px;
            overflow: hidden;
        }
        
        .gallery-img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s;
        }
        
        .gallery-item:hover .gallery-img {
            transform: scale(1.1);
        }
        
        footer {
            background-color: var(--dark);
            color: white;
            text-align: center;
            padding: 3rem 0;
        }
        
        .social-icons {
            margin: 1.5rem 0;
        }
        
        .social-icons a {
            color: white;
            margin: 0 0.5rem;
            font-size: 1.5rem;
        }
        
        @media (max-width: 768px) {
            .logo {
                font-size: 2.5rem;
            }
            
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            
            nav li {
                margin: 0.5rem 0;
            }
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <h1 class="logo">El Events</h1>
        <p class="tagline">Creating unforgettable moments with exquisite decor and flawless execution</p>
        <a href="#contact" class="btn">Plan Your Event</a>
    </header>
    
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#about">About Us</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <section id="services">
        <h2 class="section-title">Our Services</h2>
        <div class="services">
            <div class="service-card">
                <img src="wedding-decor.jpg" alt="Wedding Decor" class="service-img">
                <div class="service-content">
                    <h3 class="service-title">Wedding Decor</h3>
                    <p>Transform your wedding venue into a magical space with our custom decor solutions. From floral arrangements to lighting, we create the perfect ambiance for your special day.</p>
                </div>
            </div>
            
            <div class="service-card">
                <img src="event-planning.jpg" alt="Event Planning" class="service-img">
                <div class="service-content">
                    <h3 class="service-title">Event Management</h3>
                    <p>Comprehensive event planning services that handle every detail from concept to execution, ensuring a seamless and stress-free experience for you.</p>
                </div>
            </div>
            
            <div class="service-card">
                <img src="full-service.jpg" alt="Full Service" class="service-img">
                <div class="service-content">
                    <h3 class="service-title">Full Service Packages</h3>
                    <p>Our complete packages combine decor and management for weddings and special events, offering you a one-stop solution for all your event needs.</p>
                </div>
            </div>
        </div>
    </section>
    
    <section id="portfolio" style="background-color: var(--primary);">
        <h2 class="section-title">Our Portfolio</h2>
        <div class="gallery">
            <div class="gallery-item">
                <img src="gallery1.jpg" alt="Wedding Decor" class="gallery-img">
            </div>
            <div class="gallery-item">
                <img src="gallery2.jpg" alt="Corporate Event" class="gallery-img">
            </div>
            <div class="gallery-item">
                <img src="gallery3.jpg" alt="Birthday Party" class="gallery-img">
            </div>
            <div class="gallery-item">
                <img src="gallery4.jpg" alt="Wedding Centerpiece" class="gallery-img">
            </div>
            <div class="gallery-item">
                <img src="gallery5.jpg" alt="Event Lighting" class="gallery-img">
            </div>
            <div class="gallery-item">
                <img src="gallery6.jpg" alt="Table Settings" class="gallery-img">
            </div>
        </div>
    </section>
    
    <section id="about">
        <h2 class="section-title">About El Events</h2>
        <div style="max-width: 800px; margin: 0 auto; text-align: center;">
            <p>Founded in 2015, El Events has grown from a small decor company to a full-service event planning and design firm. Our team of passionate professionals brings creativity, attention to detail, and flawless execution to every event we touch.</p>
            <p>We believe that every event tells a story, and we're dedicated to making yours unforgettable. Whether it's an intimate wedding or a large corporate gathering, we approach each project with the same level of care and enthusiasm.</p>
            <p>Our services are available throughout the region, and we're proud to have created magical moments for hundreds of satisfied clients.</p>
        </div>
    </section>
    
    <section id="contact" style="background-color: var(--light);">
        <h2 class="section-title">Contact Us</h2>
        <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 3rem;">
            <div>
                <h3 style="font-size: 1.5rem; color: var(--accent); margin-bottom: 1rem;">Get in Touch</h3>
                <p><i class="fas fa-phone"></i> +1 (555) 123-4567</p>
                <p><i class="fas fa-envelope"></i> info@elevents.com</p>
                <p><i class="fas fa-map-marker-alt"></i> 123 Event Avenue, Suite 100, Event City, EC 12345</p>
                
                <h3 style="font-size: 1.5rem; color: var(--accent); margin: 2rem 0 1rem;">Follow Us</h3>
                <div class="social-icons">
                    <a href="#"><i class="fab fa-instagram"></i></a>
                    <a href="#"><i class="fab fa-facebook"></i></a>
                    <a href="#"><i class="fab fa-pinterest"></i></a>
                    <a href="#"><i class="fab fa-tiktok"></i></a>
                </div>
            </div>
            
            <div>
                <form>
                    <div style="margin-bottom: 1rem;">
                        <label for="name" style="display: block; margin-bottom: 0.5rem;">Name</label>
                        <input type="text" id="name" style="width: 100%; padding: 0.8rem; border: 1px solid #ddd; border-radius: 5px;">
                    </div>
                    <div style="margin-bottom: 1rem;">
                        <label for="email" style="display: block; margin-bottom: 0.5rem;">Email</label>
                        <input type="email" id="email" style="width: 100%; padding: 0.8rem; border: 1px solid #ddd; border-radius: 5px;">
                    </div>
                    <div style="margin-bottom: 1rem;">
                        <label for="event-type" style="display: block; margin-bottom: 0.5rem;">Event Type</label>
                        <select id="event-type" style="width: 100%; padding: 0.8rem; border: 1px solid #ddd; border-radius: 5px;">
                            <option value="">Select Event Type</option>
                            <option value="wedding">Wedding</option>
                            <option value="corporate">Corporate Event</option>
                            <option value="social">Social Gathering</option>
                            <option value="other">Other</option>
                        </select>
                    </div>
                    <div style="margin-bottom: 1.5rem;">
                        <label for="message" style="display: block; margin-bottom: 0.5rem;">Message</label>
                        <textarea id="message" rows="5" style="width: 100%; padding: 0.8rem; border: 1px solid #ddd; border-radius: 5px;"></textarea>
                    </div>
                    <button type="submit" class="btn">Send Message</button>
                </form>
            </div>
        </div>
    </section>
    
    <footer>
        <p>&copy; 2023 El Events. All rights reserved.</p>
        <p>Creating magical moments, one event at a time.</p>
    </footer>
</body>
</html>
