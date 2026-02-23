<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Summit Coast Capital | Fueling Florida's Future</title>
    <style>
        :root {
            --primary-navy: #002349;
            --accent-blue: #0056b3;
            --text-dark: #333;
            --white: #ffffff;
        }

        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            margin: 0;
            line-height: 1.6;
            color: var(--text-dark);
        }

        /* Hero Section with your luxury property photo */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), 
                        url('your-luxury-house-photo.jpg') center/cover no-repeat;
            height: 80vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: var(--white);
        }

        .logo-placeholder {
            max-width: 300px;
            margin-bottom: 20px;
        }

        .hero h1 {
            font-size: 3rem;
            margin: 0;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        /* Loan Program Grid */
        .programs-container {
            padding: 50px 20px;
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .program-card {
            background: #f8f9fa;
            padding: 30px;
            border-radius: 8px;
            border-top: 5px solid var(--primary-navy);
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            text-align: center;
            transition: transform 0.3s;
        }

        .program-card:hover {
            transform: translateY(-10px);
        }

        .program-card h3 {
            color: var(--primary-navy);
            margin-bottom: 15px;
        }

        .cta-button {
            background: var(--primary-navy);
            color: white;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            display: inline-block;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <section class="hero">
        <img src="summit-coast-logo.png" alt="Summit Coast Capital Logo" class="logo-placeholder">
        <h1>Fueling Florida's Future</h1>
        <p>Private Lending Built for the High-End Investor</p>
    </section>

    <div class="programs-container">
        <div class="program-card">
            <h3>Velocity</h3>
            <p>Fix & Flip Loans<br>Up to 90% LTC | 100% Rehab</p>
        </div>
        <div class="program-card">
            <h3>Pivot</h3>
            <p>Bridge & Stabilization<br>Up to 75% LTV | Short Term</p>
        </div>
        <div class="program-card">
            <h3>Scale</h3>
            <p>JV Equity Partnerships<br>Up to 100% Capital Deals</p>
        </div>
        <div class="program-card">
            <h3>DSCR</h3>
            <p>Long-Term Rental<br>Qualified by Property Cash Flow</p>
        </div>
    </div>

    <div style="text-align: center; padding-bottom: 50px;">
        <a href="#" class="cta-button">Apply Now</a>
    </div>

</body>
</html>
