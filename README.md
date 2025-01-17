<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AROI TNPY 2024</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        /* General styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }
        header {
            background: linear-gradient(to right, #007bff, #0056b3);
            color: #fff;
            text-align: center;
            padding: 2rem;
        }
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        header p {
            font-size: 1.2rem;
        }
        nav {
            background: #004a99;
            color: #fff;
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 2rem;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }
        nav a:hover {
            color: #ffcc00;
        }
        .banner {
            background: url('https://source.unsplash.com/1600x400/?conference,medical') no-repeat center center/cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #fff;
            text-align: center;
        }
        .banner h2 {
            font-size: 2.5rem;
            background: rgba(0, 0, 0, 0.6);
            padding: 1rem;
            border-radius: 5px;
        }
        .container {
            padding: 2rem 5%;
        }
        .section {
            margin-bottom: 3rem;
        }
        .section h2 {
            margin-bottom: 1rem;
            font-size: 1.8rem;
            color: #004a99;
        }
        .workshop {
            background: #fff;
            padding: 1.5rem;
            border: 1px solid #ddd;
            border-radius: 8px;
            margin-bottom: 1rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .workshop h3 {
            color: #007bff;
        }
        .workshop p {
            margin: 0.5rem 0;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 2rem 0;
        }
        table, th, td {
            border: 1px solid #ddd;
        }
        th, td {
            padding: 1rem;
            text-align: center;
        }
        th {
            background: #007bff;
            color: #fff;
        }
        td {
            background: #f8f9fa;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 2rem 0;
            margin-top: 2rem;
        }
        footer a {
            color: #ffcc00;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>AROI TNPY 2024</h1>
        <p>"Transforming Radiation Oncology: Embracing Compassion, Technology, and Quality Care"</p>
    </header>
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#workshops">Workshops</a></li>
            <li><a href="#registration">Registration</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section class="banner">
        <h2>Welcome to the 39th AROI TNPY Conference</h2>
    </section>
    <div class="container">
        <!-- About Section -->
        <div id="about" class="section">
            <h2>About the Conference</h2>
            <p>The 39th AROI Tamil Nadu and Pondicherry Chapter Conference will be held on September 20-21, 2024, at Christian Medical College, Vellore. The conference will focus on cutting-edge advancements in radiation oncology under the theme "Transforming Radiation Oncology: Embracing Compassion, Technology, and Quality Care."</p>
        </div>
        <!-- Workshops Section -->
        <div id="workshops" class="section">
            <h2>Pre-Conference Workshops</h2>
            <div class="workshop">
                <h3>Workshop 1: Gynecology Brachytherapy with Advanced Applicators</h3>
                <p><strong>Date:</strong> September 19, 2024 | <strong>Time:</strong> 1 PM - 4 PM</p>
                <p>This hands-on workshop focuses on advanced techniques for treating cervical cancer using hybrid applicators such as the Venezia. Participants will gain practical experience in image-guided brachytherapy with one-on-one guidance from experienced faculty.</p>
            </div>
            <div class="workshop">
                <h3>Workshop 2: Radiation Oncology Plan Evaluation</h3>
                <p><strong>Date:</strong> September 20, 2024 | <strong>Time:</strong> 8 AM - 12 PM</p>
                <p>Learn advanced plan evaluation techniques for high-precision radiation therapy. This workshop provides in-depth insights into optimizing treatment plans for common cancer types, guided by expert faculty.</p>
            </div>
        </div>
        <!-- Registration Section -->
        <div id="registration" class="section">
            <h2>Registration Fees</h2>
            <table>
                <thead>
                    <tr>
                        <th>Category</th>
                        <th>Early Bird 1</th>
                        <th>Early Bird 2</th>
                        <th>Regular</th>
                        <th>Spot</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>AROI Member</td>
                        <td>₹4000</td>
                        <td>₹5000</td>
                        <td>₹6000</td>
                        <td>₹7000</td>
                    </tr>
                    <tr>
                        <td>Non-Member</td>
                        <td>₹5000</td>
                        <td>₹6000</td>
                        <td>₹7000</td>
                        <td>₹8500</td>
                    </tr>
                    <tr>
                        <td>Students</td>
                        <td>₹3000</td>
                        <td>₹4000</td>
                        <td>₹4500</td>
                        <td>₹5000</td>
                    </tr>
                </tbody>
            </table>
        </div>
        <!-- Contact Section -->
        <div id="contact" class="section">
            <h2>Contact Us</h2>
            <p>Email: <a href="mailto:aroitnpy2024@cmcvellore.ac.in">aroitnpy2024@cmcvellore.ac.in</a></p>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 AROI TNPY. All rights reserved. Inspired by modern web design.</p>
    </footer>
</body>
</html>
