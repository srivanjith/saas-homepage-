<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>SaaS Landing Page</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', sans-serif;
        }

        body {
            background: #f5f7fb;
            color: #333;
        }

        header {
            background: linear-gradient(135deg, #4f46e5, #6366f1);
            color: white;
            padding: 20px 10%;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav h2 {
            font-size: 24px;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 25px;
        }

        nav ul li {
            cursor: pointer;
        }

        .hero {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 80px 10%;
            gap: 40px;
        }

        .hero-text h1 {
            font-size: 48px;
            line-height: 1.2;
        }

        .hero-text p {
            margin: 20px 0;
            font-size: 18px;
            opacity: 0.9;
        }

        .hero-text button {
            padding: 14px 30px;
            border: none;
            border-radius: 8px;
            background: white;
            color: #4f46e5;
            font-size: 16px;
            cursor: pointer;
            font-weight: bold;
        }

        .hero-box {
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.15);
            width: 300px;
        }

        .hero-box h3 {
            margin-bottom: 15px;
        }

        .hero-box p {
            font-size: 14px;
            color: #555;
        }

        .features {
            padding: 80px 10%;
            text-align: center;
        }

        .features h2 {
            font-size: 36px;
            margin-bottom: 40px;
        }

        .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }

        .card {
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.08);
        }

        .card h3 {
            margin-bottom: 15px;
        }

        footer {
            background: #111827;
            color: white;
            text-align: center;
            padding: 30px;
            margin-top: 60px;
        }

        @media (max-width: 900px) {
            .hero {
                flex-direction: column;
                text-align: center;
            }
        }
    </style>
</head>

<body>

<header>
    <nav>
        <h2>Cloudify</h2>
        <ul>
            <li>Features</li>
            <li>Pricing</li>
            <li>Contact</li>
        </ul>
    </nav>

    <section class="hero">
        <div class="hero-text">
            <h1>Build Faster With<br>Modern SaaS Platform</h1>
            <p>Manage projects, teams, and analytics in one powerful cloud solution.</p>
            <button>Get Started</button>
        </div>

        <div class="hero-box">
            <h3>Live Dashboard</h3>
            <p>Track real-time metrics, performance, and growth from one dashboard.</p>
        </div>
    </section>
</header>

<section class="features">
    <h2>Powerful Features</h2>

    <div class="feature-grid">
        <div class="card">
            <h3>Analytics</h3>
            <p>Real-time insights to track business performance.</p>
        </div>

        <div class="card">
            <h3>Security</h3>
            <p>Enterprise-grade security with encrypted data.</p>
        </div>

        <div class="card">
            <h3>Automation</h3>
            <p>Automate workflows and boost productivity.</p>
        </div>
    </div>
</section>

<footer>
    <p>© 2025 Cloudify SaaS. All rights reserved.</p>
</footer>

</body>
</html>
