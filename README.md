<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>All in One Seva Sansthan | समाज सेवा का अनूठा प्रयास</title>
    <style>
        :root {
            --primary: #4CAF50;
            --secondary: #FF9800;
            --dark: #333;
            --light: #f4f4f4;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            line-height: 1.6;
            color: var(--dark);
            background-color: #f9f9f9;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            background: linear-gradient(135deg, var(--primary), #2E7D32);
            color: white;
            padding: 1rem 0;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        .logo {
            font-size: 2rem;
            font-weight: bold;
            margin-bottom: 0.5rem;
        }
        
        .tagline {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        nav {
            background-color: var(--dark);
            padding: 0.7rem 0;
        }
        
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
        }
        
        nav ul li {
            margin: 0 15px;
        }
        
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s ease;
        }
        
        nav ul li a:hover {
            color: var(--secondary);
        }
        
        .hero {
            background: url('https://images.unsplash.com/photo-1521791136064-7986c2920216?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80') no-repeat center center/cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            position: relative;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.6);
        }
        
        .hero-content {
            position: relative;
            z-index: 1;
            max-width: 800px;
            padding: 0 20px;
        }
        
        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 1.5rem;
        }
        
        .btn {
            display: inline-block;
            background: var(--secondary);
            color: white;
            padding: 0.7rem 1.5rem;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: all 0.3s ease;
        }
        
        .btn:hover {
            background: #F57C00;
            transform: translateY(-3px);
        }
        
        .section {
            padding: 4rem 0;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 2rem;
            font-size: 2rem;
            color: var(--primary);
        }
        
        .about-content {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            align-items: center;
        }
        
        .about-text {
            flex: 1;
            min-width: 300px;
            padding: 0 20px;
        }
        
        .about-image {
            flex: 1;
            min-width: 300px;
            text-align: center;
        }
        
        .about-image img {
            max-width: 100%;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .services {
            background-color: var(--light);
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .service-card {
            background: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            transition: all 0.3s ease;
        }
        
        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.1);
        }
        
        .service-card h3 {
            color: var(--primary);
            margin-bottom: 1rem;
            font-size: 1.5rem;
        }
        
        .achievements {
            text-align: center;
        }
        
        .stats {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin: 2rem 0;
        }
        
        .stat-item {
            padding: 1.5rem;
            min-width: 200px;
        }
        
        .stat-number {
            font-size: 2.5rem;
            font-weight: bold;
            color: var(--primary);
            margin-bottom: 0.5rem;
        }
        
        .donation {
            background: linear-gradient(135deg, var(--primary), #2E7D32);
            color: white;
            text-align: center;
            padding: 3rem 0;
        }
        
        .donation-box {
            background: white;
            color: var(--dark);
            padding: 2rem;
            border-radius: 10px;
            max-width: 600px;
            margin: 0 auto;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }
        
        .donation-box h2 {
            color: var(--primary);
            margin-bottom: 1rem;
        }
        
        .upi-id {
            background: #f4f4f4;
            padding: 1rem;
            border-radius: 5px;
            font-family: monospace;
            font-size: 1.2rem;
            margin: 1rem 0;
            display: inline-block;
        }
        
        .contact {
            background-color: var(--light);
        }
        
        .contact-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .contact-info {
            background: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }
        
        .contact-info h3 {
            color: var(--primary);
            margin-bottom: 1rem;
            font-size: 1.5rem;
        }
        
        .contact-info p {
            margin-bottom: 0.5rem;
        }
        
        footer {
            background-color: var(--dark);
            color: white;
            text-align: center;
            padding: 2rem 0;
            margin-top: 2rem;
        }
        
        .social-links {
            margin: 1rem 0;
        }
        
        .social-links a {
            color: white;
            margin: 0 10px;
            font-size: 1.5rem;
            transition: all 0.3s ease;
        }
        
        .social-links a:hover {
            color: var(--secondary);
        }
        
        .language-toggle {
            text-align: center;
            margin: 1rem 0;
        }
        
        .language-toggle button {
            background: none;
            border: none;
            color: var(--primary);
            font-weight: bold;
            cursor: pointer;
            padding: 0.5rem 1rem;
            border-radius: 5px;
            transition: all 0.3s ease;
        }
        
        .language-toggle button.active {
            background: var(--primary);
            color: white;
        }
        
        .language-toggle button:hover {
            background: rgba(76, 175, 80, 0.1);
        }
        
        .hindi {
            display: block;
        }
        
        .english {
            display: none;
        }
        
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            
            nav ul li {
                margin: 5px 0;
            }
            
            .hero {
                height: 300px;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">All in One Seva Sansthan</div>
            <div class="tagline">सेवा परमो धर्मः | Service is the Supreme Duty</div>
        </div>
    </header>
    
    <nav>
        <div class="container">
            <ul>
                <li><a href="#about">हमारे बारे में</a></li>
                <li><a href="#services">हमारी सेवाएँ</a></li>
                <li><a href="#achievements">उपलब्धियाँ</a></li>
                <li><a href="#donate">दान करें</a></li>
                <li><a href="#contact">संपर्क करें</a></li>
            </ul>
        </div>
    </nav>
    
    <section class="hero">
        <div class="hero-content">
            <h1 class="hindi">समाज सेवा का अनूठा प्रयास</h1>
            <h1 class="english" style="display: none;">A Unique Initiative for Social Service</h1>
            <p class="hindi">शिक्षा, स्वास्थ्य और सशक्तिकरण के माध्यम से समाज को बदलने का संकल्प</p>
            <p class="english" style="display: none;">Commitment to transform society through education, health and empowerment</p>
            <a href="#donate" class="btn hindi">अभी दान करें</a>
            <a href="#donate" class="btn english" style="display: none;">Donate Now</a>
        </div>
    </section>
    
    <div class="language-toggle">
        <button onclick="toggleLanguage('hindi')" class="active">हिंदी</button>
        <button onclick="toggleLanguage('english')">English</button>
    </div>
    
    <section id="about" class="section">
        <div class="container">
            <h2 class="section-title hindi">हमारे बारे में</h2>
            <h2 class="section-title english" style="display: none;">About Us</h2>
            <div class="about-content">
                <div class="about-text">
                    <p class="hindi">All in One Seva Sansthan एक गैर-लाभकारी संगठन है जो समाज के हर वर्ग की सेवा करने के लिए समर्पित है। हमारा उद्देश्य शिक्षा, स्वास्थ्य, महिला सशक्तिकरण, बच्चों के कल्याण और गरीबों की मदद करना है। हमारी टीम पूरी निष्ठा और मेहनत से समाज में बदलाव लाने के लिए काम करती है।</p>
                    <p class="english" style="display: none;">All in One Seva Sansthan is a non-profit organization dedicated to serving all sections of society. Our aim is to help through education, health, women empowerment, child welfare and assistance to the poor. Our team works with complete dedication and hard work to bring about change in society.</p>
                </div>
                <div class="about-image">
                    <img src="https://images.unsplash.com/photo-1522071820081-009f0129c71c?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Team Photo">
                </div>
            </div>
        </div>
    </section>
    
    <section id="services" class="section services">
        <div class="container">
            <h2 class="section-title hindi">हमारी सेवाएँ</h2>
            <h2 class="section-title english" style="display: none;">Our Services</h2>
            <div class="services-grid">
                <div class="service-card">
                    <h3 class="hindi">शिक्षा का प्रसार</h3>
                    <h3 class="english" style="display: none;">Education</h3>
                    <p class="hindi">हम गरीब बच्चों को निःशुल्क शिक्षा, स्टेशनरी और कोचिंग उपलब्ध कराते हैं। शिक्षा ही वह माध्यम है जिससे समाज में बदलाव लाया जा सकता है।</p>
                    <p class="english" style="display: none;">We provide free education, stationery and coaching to poor children. Education is the medium through which change can be brought in society.</p>
                </div>
                <div class="service-card">
                    <h3 class="hindi">स्वास्थ्य सेवाएँ</h3>
                    <h3 class="english" style="display: none;">Health Services</h3>
                    <p class="hindi">हम निःशुल्क मेडिकल कैंप, दवाइयाँ और स्वास्थ्य जागरूकता कार्यक्रम आयोजित करते हैं ताकि हर व्यक्ति स्वस्थ जीवन जी सके।</p>
                    <p class="english" style="display: none;">We organize free medical camps, medicines and health awareness programs so that every person can live a healthy life.</p>
                </div>
                <div class="service-card">
                    <h3 class="hindi">महिला सशक्तिकरण</h3>
                    <h3 class="english" style="display: none;">Women Empowerment</h3>
                    <p class="hindi">हम महिलाओं को आत्मनिर्भर बनाने के लिए सिलाई, कढ़ाई, कंप्यूटर कोर्स और अन्य रोजगारपरक प्रशिक्षण देते हैं।</p>
                    <p class="english" style="display: none;">We provide sewing, embroidery, computer courses and other vocational training to make women self-reliant.</p>
                </div>
                <div class="service-card">
                    <h3 class="hindi">गरीबों की मदद</h3>
                    <h3 class="english" style="display: none;">Help for the Poor</h3>
                    <p class="hindi">हम जरूरतमंदों को भोजन, कपड़े और आवश्यक सामान वितरित करते हैं। विशेषकर ठंड के मौसम में कंबल वितरण जैसे कार्यक्रम चलाए जाते हैं।</p>
                    <p class="english" style="display: none;">We distribute food, clothes and essential items to the needy. Special programs like blanket distribution are run especially in winter season.</p>
                </div>
                <div class="service-card">
                    <h3 class="hindi">आपदा राहत</h3>
                    <h3 class="english" style="display: none;">Disaster Relief</h3>
                    <p class="hindi">बाढ़, भूकंप या अन्य आपदाओं के समय हम पीड़ितों को राहत सामग्री पहुँचाने में सक्रिय भूमिका निभाते हैं।</p>
                    <p class="english" style="display: none;">During floods, earthquakes or other disasters, we play an active role in delivering relief materials to the victims.</p>
                </div>
            </div>
        </div>
    </section>
    
    <section id="achievements" class="section achievements">
        <div class="container">
            <h2 class="section-title hindi">हमारी उपलब्धियाँ</h2>
            <h2 class="section-title english" style="display: none;">Our Achievements</h2>
            <div class="stats">
                <div class="stat-item">
                    <div class="stat-number">5000+</div>
                    <div class="hindi">बच्चों को शिक्षा</div>
                    <div class="english" style="display: none;">Children Educated</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">200+</div>
                    <div class="hindi">मेडिकल कैंप</div>
                    <div class="english" style="display: none;">Medical Camps</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">1000+</div>
                    <div class="hindi">महिलाओं को प्रशिक्षण</div>
                    <div class="english" style="display: none;">Women Trained</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">50,000+</div>
                    <div class="hindi">लोगों की मदद</div>
                    <div class="english" style="display: none;">People Helped</div>
                </div>
            </div>
        </div>
    </section>
    
    <section id="donate" class="section donation">
        <div class="container">
            <h2 class="section-title hindi">दान करें</h2>
            <h2 class="section-title english" style="display: none;">Donate</h2>
            <div class="donation-box">
                <h3 class="hindi">आपका छोटा सा योगदान बड़ा बदलाव ला सकता है</h3>
                <h3 class="english" style="display: none;">Your small contribution can make a big difference</h3>
                <p class="hindi">हमारे मिशन का हिस्सा बनें और समाज सेवा में सहयोग करें। आप निम्नलिखित तरीकों से दान कर सकते हैं:</p>
                <p class="english" style="display: none;">Become part of our mission and contribute to social service. You can donate through the following methods:</p>
                
                <h4 class="hindi">UPI के माध्यम से दान:</h4>
                <h4 class="english" style="display: none;">Donate via UPI:</h4>
                <div class="upi-id">9060709157</div>
                
                <p class="hindi">अन्य दान विकल्पों के लिए कृपया हमसे संपर्क करें</p>
                <p class="english" style="display: none;">For other donation options, please contact us</p>
                
                <a href="#contact" class="btn hindi">संपर्क करें</a>
                <a href="#contact" class="btn english" style="display: none;">Contact Us</a>
            </div>
        </div>
    </section>
    
    <section id="contact" class="section contact">
        <div class="container">
            <h2 class="section-title hindi">संपर्क करें</h2>
            <h2 class="section-title english" style="display: none;">Contact Us</h2>
            <div class="contact-grid">
                <div class="contact-info">
                    <h3 class="hindi">हमारा पता</h3>
                    <h3 class="english" style="display: none;">Our Address</h3>
                    <p>गाँव - तरौरा, पोस्ट - पीरबधौना</p>
                    <p>पुलिस स्टेशन - डनियावां, जिला - पटना</p>
                    <p>पिन कोड - 801305, बिहार, भारत</p>
                </div>
                <div class="contact-info">
                    <h3 class="hindi">संपर्क सूचना</h3>
                    <h3 class="english" style="display: none;">Contact Information</h3>
                    <p><strong>फोन:</strong> <a href="tel:+919060709157">9060709157</a></p>
                    <p><strong>ईमेल:</strong> <a href="mailto:ernstsonu6@gmail.com">ernstsonu6@gmail.com</a></p>
                </div>
            </div>
        </div>
    </section>
    
    <footer>
        <div class="container">
            <div class="logo">All in One Seva Sansthan</div>
            <div class="hindi">समाज सेवा का संकल्प</div>
            <div class="english" style="display: none;">Commitment to Social Service</div>
            
            <div class="social-links">
                <a href="#"><i class="fab fa-facebook"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-youtube"></i></a>
            </div>
            
            <p class="hindi">© 2023 All in One Seva Sansthan. सर्वाधिकार सुरक्षित</p>
            <p class="english" style="display: none;">© 2023 All in One Seva Sansthan. All Rights Reserved</p>
        </div>
    </footer>
    
    <script>
        function toggleLanguage(lang) {
            // Hide all elements of other language
            const elementsToHide = document.querySelectorAll(`.${lang === 'hindi' ? 'english' : 'hindi'}`);
            elementsToHide.forEach(el => {
                el.style.display = 'none';
            });
            
            // Show all elements of selected language
            const elementsToShow = document.querySelectorAll(`.${lang}`);
            elementsToShow.forEach(el => {
                el.style.display = 'block';
            });
            
            // Update active button
            document.querySelectorAll('.language-toggle button').forEach(btn => {
                btn.classList.remove('active');
            });
            event.target.classList.add('active');
        }
    </script>
    
    <!-- Font Awesome for social icons -->
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</body>
</html>
