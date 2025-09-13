
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MUQ Services - Trusted Service Provider Agency</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-color: #1a237e; /* Dark Blue */
            --secondary-color: #55b7e2; /* Light Blue */
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
            width: 180px;
            height: 180px;
            border-radius: 50%;
            background-color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
            margin: 0 auto 30px auto;
            border: 5px solid var(--secondary-color);
            position: absolute;
            left: 50%;
            top: -90px;
            transform: translateX(-50%);
            z-index: 2;
        }

        .logo-img {
            width: 92%;
            height: 92%;
            object-fit: contain;
            border-radius: 50%;
            display: block;
        }

        header h1 {
            font-size: 3.5em;
            margin: 70px 0 0 0;
            font-weight: 700;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1);
        }

        header p {
            font-size: 1.4em;
            font-weight: 500;
            color: rgba(255, 255, 255, 0.9);
            margin-top: 10px;
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

        .contact-section {
            text-align: center;
            margin-top: 40px;
        }

        .contact-btn {
            background-color: var(--secondary-color);
            color: #fff;
            font-size: 1.2em;
            font-weight: 600;
            border: none;
            border-radius: 8px;
            padding: 14px 40px;
            cursor: pointer;
            transition: background 0.3s;
            margin-top: 20px;
            margin-bottom: 20px;
            box-shadow: 0 4px 16px rgba(85, 183, 226, 0.15);
        }

        .contact-btn:hover {
            background: var(--primary-color);
            color: #fff;
        }

        .contact-info {
            display: none;
            text-align: center;
            font-size: 1.1em;
            margin-top: 20px;
            animation: fadeIn 0.5s;
        }

        .contact-info p {
            margin: 5px 0;
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

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px);}
            to { opacity: 1; transform: translateY(0);}
        }

        .footer {
            background-color: v
