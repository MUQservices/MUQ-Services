
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MUQ Services - Trusted Service Provider Agency</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-color: #1a237e; /* Dark Blue from Logo */
            --secondary-color: #55b7e2; /* Light Blue from Logo */
            --text-color: #333;
            --light-bg: #f5f8ff;
            --card-bg: #ffffff;
        }

        body {
            font-family: 'Montserrat', sans-serif;
            margin: 0;
            background-color: var(--light-bg);
            color: var(--text-color);
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            background: linear-gradient(135deg, var(--primary-color), #283593);
            color: #fff;
            padding: 100px 0 60px 0;
            text-align: center;
            position: relative;
        }

        .logo-container {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            background-color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
            margin: 0 auto 20px auto;
        }

        .logo {
            width: 90%;
            height: auto;
            object-fit: contain;
            border-radius: 50%;
        }

        header h1 {
            font-size: 3em;
            margin: 0;
            font-weight: 700;
            text-shadow: 2px 2px 5px rgba(0,0,0,0.1);
        }

        header p {
            font-size: 1.2em;
            font-weight: 400;
            color: rgba(255, 255, 255, 0.8);
        }

        .section {
            padding: 60px 0;
        }

        .section-title {
            text-align: center;
            font-size: 2.2em;
            font-weight: 700;
            color: var(--primary-color);
            margin-bottom: 40px;
            position: relative;
        }

        .section-title::after {
            content: '';
            position: absolute;
            left: 50%;
            bottom: -10px;
            transform: translateX(-50%);
            width: 80px;
            height: 4px;
            background-color: var(--secondary-color);
            border-radius: 2px;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            list-style: none;
            padding: 0;
        }

        .service-item {
            background-color: var(--card-bg);
            border-radius: 12px;
            box-shadow: 0 8px 24px rgba(0,0,0,0.08);
            padding: 30px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            text-align: center;
        }

        .service-item:hover {
            transform: translateY(-10px);
            box-shadow: 0 12px 30px rgba(0,0,0,0.12);
        }
        
        .service-item h3 {
            color: var(--primary-color);
            font-size: 1.4em;
            font-weight: 700;
            margin-top: 15px;
        }
        
        .service-item p {
            color: #666;
            font-size: 1em;
        }

        .contact-info {
            text-align: center;
            font-size: 1.1em;
            margin-top: 40px;
        }
        
        .contact-info a {
            color: var(--secondary-color);
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        .contact-info a:hover {
            color: var(--primary-color);
            text-decoration: underline;
        }
        
        .contact-btn {
            background-color: var(--secondary-color);
            color: white;
            padding: 15px 30px;
            font-size: 1.1em;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: background-color 0.3s ease;
            display: block;
            margin: 0 auto;
        }
        
        .contact-btn:hover {
            background-color: var(--primary-color);
        }

        .footer {
            background-color: var(--primary-color);
            color: rgba(255, 255, 255, 0.7);
            text-align: center;
            padding: 25px 0;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="logo-container">
                <img src="Untitled design (1).jpg" alt="MUQ Services Logo" class="logo">
            </div>
            <h1>MUQ Services</h1>
            <p>Your Partner in Business Solutions</p>
        </div>
    </header>

    <div class="section about">
        <div class="container">
            <h2 class="section-title">About Us</h2>
            <p style="text-align: center;">
                MUQ Services is a leading agency dedicated to connecting you with genuine professionals for your business needs. We are committed to simplifying your search for reliable experts and providing solutions that help your business grow and succeed.
            </p>
        </div>
    </div>

    <div class="section services">
        <div class="container">
            <h2 class="section-title">Our Expertise</h2>
            <ul class="services-grid">
                <li class="service-item">
                    <h3>Professional Connections</h3>
                    <p>Connecting clients with genuine, skilled professionals and virtual assistants.</p>
                </li>
                <li class="service-item">
                    <h3>Business Support</h3>
                    <p>Offering comprehensive business process outsourcing and administrative support.</p>
                </li>
                <li class="service-item">
                    <h3>Project Management</h3>
                    <p>Providing expert project management and consultancy to guide your projects to success.</p>
                </li>
                <li class="service-item">
                    <h3>Customer Support</h3>
                    <p>Delivering reliable and efficient customer support solutions.</p>
                </li>
                <li class="service-item">
                    <h3>Custom Solutions</h3>
                    <p>Creating personalized service packages tailored to your unique business requirements.</p>
                </li>
            </ul>
        </div>
    </div>

    <div class="section contact">
        <div class="container">
            <h2 class="section-title">Contact Us</h2>
            <div class="contact-info">
                <p>Email: <a href="mailto:muqservices@gmail.com">muqservices@gmail.com</a></p>
                <p>LinkedIn: <a href="https://www.linkedin.com/in/muq-services-0a012a384/" target="_blank">MUQ Services</a></p>
            </div>
        </div>
    </div>

    <footer class="footer">
        <div class="container">
            &copy; 2025 MUQ Services. All Rights Reserved.
        </div>
    </footer>
</body>
</html>
