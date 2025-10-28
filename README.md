<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Holistic Energy Healing - Transform Your Life</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
        }

        .header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 2rem;
        }

        .logo-container {
            display: flex;
            align-items: center;
            gap: 1rem;
        }

        .logo {
            width: 50px;
            height: 50px;
        }

        .logo-text {
            font-size: 1.5rem;
            font-weight: bold;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 2rem;
        }

        nav a {
            color: white;
            text-decoration: none;
            transition: opacity 0.3s;
        }

        nav a:hover {
            opacity: 0.8;
        }

        .hero {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 150px 2rem 100px;
            text-align: center;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            animation: fadeInUp 1s;
        }

        .hero p {
            font-size: 1.3rem;
            margin-bottom: 2rem;
            animation: fadeInUp 1.2s;
        }

        .cta-button {
            background: white;
            color: #667eea;
            padding: 1rem 2.5rem;
            border: none;
            border-radius: 50px;
            font-size: 1.1rem;
            cursor: pointer;
            transition: transform 0.3s, box-shadow 0.3s;
            animation: fadeInUp 1.4s;
        }

        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 4rem 2rem;
        }

        .services {
            background: #f8f9fa;
        }

        .section-title {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 3rem;
            color: #667eea;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .service-card {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.1);
            transition: transform 0.3s, box-shadow 0.3s;
            cursor: pointer;
        }

        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 40px rgba(0,0,0,0.15);
        }

        .service-icon {
            width: 60px;
            height: 60px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 1.5rem;
            font-size: 1.8rem;
        }

        .service-card h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            color: #333;
        }

        .service-card p {
            color: #666;
            line-height: 1.8;
        }

        .about {
            background: white;
        }

        .about-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 3rem;
            align-items: center;
        }

        .about-text h2 {
            font-size: 2.5rem;
            margin-bottom: 1.5rem;
            color: #667eea;
        }

        .about-text p {
            margin-bottom: 1rem;
            color: #666;
            font-size: 1.1rem;
        }

        .about-image {
            width: 100%;
            height: 400px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            border-radius: 15px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 4rem;
            color: white;
        }

        .contact {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
        }

        .contact-info {
            text-align: center;
            margin-bottom: 3rem;
        }

        .contact-info p {
            font-size: 1.2rem;
            margin-bottom: 1rem;
        }

        .phone-link {
            color: white;
            text-decoration: none;
            font-size: 2rem;
            font-weight: bold;
            display: inline-block;
            padding: 1rem 2rem;
            background: rgba(255,255,255,0.1);
            border-radius: 50px;
            transition: background 0.3s;
        }

        .phone-link:hover {
            background: rgba(255,255,255,0.2);
        }

        .contact-form {
            max-width: 600px;
            margin: 0 auto;
        }

        .form-group {
            margin-bottom: 1.5rem;
        }

        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 500;
        }

        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 0.8rem;
            border: none;
            border-radius: 8px;
            font-size: 1rem;
        }

        .form-group textarea {
            resize: vertical;
            min-height: 150px;
        }

        .submit-button {
            background: white;
            color: #667eea;
            padding: 1rem 3rem;
            border: none;
            border-radius: 50px;
            font-size: 1.1rem;
            cursor: pointer;
            transition: transform 0.3s;
            width: 100%;
        }

        .submit-button:hover {
            transform: translateY(-3px);
        }

        .footer {
            background: #2d3748;
            color: white;
            text-align: center;
            padding: 2rem;
        }

        .footer a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        .footer a:hover {
            text-decoration: underline;
        }

        .success-message {
            background: #48bb78;
            color: white;
            padding: 1rem;
            border-radius: 8px;
            margin-bottom: 1rem;
            display: none;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @media (max-width: 768px) {
            .nav-container {
                flex-direction: column;
                gap: 1rem;
            }

            nav ul {
                flex-wrap: wrap;
                justify-content: center;
                gap: 1rem;
            }

            .hero h1 {
                font-size: 2rem;
            }

            .hero p {
                font-size: 1rem;
            }

            .about-content {
                grid-template-columns: 1fr;
            }

            .services-grid {
                grid-template-columns: 1fr;
            }

            .phone-link {
                font-size: 1.5rem;
                padding: 0.8rem 1.5rem;
            }
        }
    </style>
</head>
<body>
    <header class="header">
        <div class="nav-container">
            <div class="logo-container">
                <svg class="logo" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
                    <circle cx="50" cy="50" r="45" fill="none" stroke="white" stroke-width="2"/>
                    <circle cx="50" cy="50" r="35" fill="none" stroke="white" stroke-width="2"/>
                    <circle cx="50" cy="50" r="25" fill="none" stroke="white" stroke-width="2"/>
                    <path d="M 50 10 L 50 35" stroke="white" stroke-width="2"/>
                    <path d="M 50 65 L 50 90" stroke="white" stroke-width="2"/>
                    <path d="M 10 50 L 35 50" stroke="white" stroke-width="2"/>
                    <path d="M 65 50 L 90 50" stroke="white" stroke-width="2"/>
                    <circle cx="50" cy="50" r="8" fill="white"/>
                </svg>
                <div class="logo-text">Holistic Energy Healing</div>
            </div>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="hero">
        <h1>Transform Your Life Through Energy Healing</h1>
        <p>Discover balance, peace, and wellness through ancient healing practices</p>
        <button class="cta-button" onclick="document.getElementById('contact').scrollIntoView({behavior: 'smooth'})">Book a Session</button>
    </section>

    <section id="services" class="services">
        <div class="container">
            <h2 class="section-title">Our Healing Services</h2>
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon">ðŸ™</div>
                    <h3>Reiki Healing</h3>
                    <p>Experience the gentle power of universal life force energy. Reiki helps reduce stress, promotes relaxation, and supports the body's natural healing abilities through hands-on energy transfer.</p>
                </div>

                <div class="service-card">
                    <div class="service-icon">ðŸ§ </div>
                    <h3>Clinical Hypnotherapy</h3>
                    <p>Access your subconscious mind to overcome limiting beliefs, break unwanted habits, and achieve your goals. A safe, effective therapeutic approach for lasting positive change.</p>
                </div>

                <div class="service-card">
                    <div class="service-icon">âœ¨</div>
                    <h3>Pranic Healing</h3>
                    <p>Harness the power of life energy (prana) to cleanse and energize your body's energy field. This no-touch healing modality promotes physical, emotional, and mental well-being.</p>
                </div>

                <div class="service-card">
                    <div class="service-icon">ðŸ’Ž</div>
                    <h3>Crystal Healing</h3>
                    <p>Tap into the vibrational frequencies of crystals to restore balance and harmony. Each crystal carries unique properties that support healing and spiritual growth.</p>
                </div>

                <div class="service-card">
                    <div class="service-icon">ðŸ˜‡</div>
                    <h3>Angel Therapy</h3>
                    <p>Connect with angelic guidance for healing, protection, and spiritual insight. Receive divine messages and support from your guardian angels and archangels.</p>
                </div>

                <div class="service-card">
                    <div class="service-icon">ðŸŒŸ</div>
                    <h3>Combination Sessions</h3>
                    <p>Experience the synergy of multiple healing modalities in one session. Customized treatments designed to address your unique needs and accelerate your healing journey.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="about">
        <div class="container">
            <div class="about-content">
                <div class="about-text">
                    <h2>About Our Practice</h2>
                    <p>Welcome to Holistic Energy Healing, where ancient wisdom meets modern wellness. We are dedicated to helping you achieve optimal health and spiritual growth through proven energy healing modalities.</p>
                    <p>Our certified practitioners bring years of experience and a deep commitment to your well-being. We believe in treating the whole person - mind, body, and spirit - to facilitate profound and lasting transformation.</p>
                    <p>Whether you're seeking relief from physical discomfort, emotional healing, or spiritual development, we offer a safe and nurturing space for your healing journey.</p>
                </div>
                <div class="about-image">
                    <span>â˜¯ï¸</span>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2 class="section-title" style="color: white;">Get In Touch</h2>
            <div class="contact-info">
                <p>Call us for a consultation or to book your healing session</p>
                <a href="tel:+918902733882" class="phone-link">
                   +918902733882
                </a>
            </div>
            <div class="contact-form">
                <div id="successMessage" class="success-message">
                    Thank you! Your message has been sent successfully. We'll get back to you soon.
                </div>
                <form id="contactForm">
                    <div class="form-group">
                        <label for="name">Name</label>
                        <input type="text" id="name" name="name" required>
                    </div>
                    <div class="form-group">
                        <label for="email">Email</label>
                        <input type="email" id="email" name="email" required>
                    </div>
                    <div class="form-group">
                        <label for="phone">Phone</label>
                        <input type="tel" id="phone" name="phone" required>
                    </div>
                    <div class="form-group">
                        <label for="service">Service Interested In</label>
                        <input type="text" id="service" name="service" placeholder="e.g., Reiki Healing">
                    </div>
                    <div class="form-group">
                        <label for="message">Message</label>
                        <textarea id="message" name="message" required></textarea>
                    </div>
                    <button type="submit" class="submit-button">Send Message</button>
                </form>
            </div>
        </div>
    </section>

    <footer class="footer">
        <p>&copy; 2025 Holistic Energy Healing. All rights reserved.</p>
        <p style="margin: 1rem 0;"> Call us: <a href="tel:+918902733882">+918902733882</a></p>
        <p>Transform your life through the power of energy healing.</p>
    </footer>

    <script>
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const phone = document.getElementById('phone').value;
            const service = document.getElementById('service').value;
            const message = document.getElementById('message').value;
            
            const formData = {
                name: name,
                email: email,
                phone: phone,
                service: service,
                message: message,
                timestamp: new Date().toISOString()
            };
            
            console.log('Form submitted:', formData);
            
            document.getElementById('successMessage').style.display = 'block';
            document.getElementById('contactForm').reset();
            
            setTimeout(function() {
                document.getElementById('successMessage').style.display = 'none';
            }, 5000);
        });

        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });
    </script>
</body>
</html>
