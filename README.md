# Ganesha
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MAHA GANAPATHI BHAKTHA BRUNDHAM</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }
        body {
            background: #fff8f0;
            color: #333;
            text-align: center;
            padding: 20px;
        }
        header {
            background: linear-gradient(135deg, #ff9933, #ff6600);
            color: white;
            padding: 30px 20px;
            border-radius: 15px;
            margin-bottom: 30px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }
        .logo {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid white;
            margin-bottom: 15px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
        }
        h1 {
            font-size: 2rem;
            margin-bottom: 5px;
            text-transform: uppercase;
        }
        .subtitle {
            font-size: 1.1rem;
            font-weight: 600;
            margin-bottom: 10px;
            letter-spacing: 1px;
        }
        .location {
            font-size: 0.95rem;
            opacity: 0.95;
            margin-top: 8px;
            background: rgba(0, 0, 0, 0.15);
            display: inline-block;
            padding: 6px 15px;
            border-radius: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
        }
        .events-section {
            background: white;
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            margin-bottom: 30px;
        }
        .events-section h2 {
            color: #ff6600;
            margin-bottom: 20px;
            font-size: 1.5rem;
        }
        .event-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            text-align: left;
        }
        .event-card {
            background: #fff5eb;
            border-left: 5px solid #ff6600;
            padding: 15px 20px;
            border-radius: 8px;
        }
        .event-card h3 {
            color: #d35400;
            font-size: 1.1rem;
            margin-bottom: 8px;
        }
        .event-card p {
            font-size: 0.95rem;
            color: #555;
            line-height: 1.5;
        }
        footer {
            margin-top: 40px;
            font-size: 0.9rem;
            color: #777;
            padding: 20px;
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <img src="logo.png" alt="Maha Ganapathi Logo" class="logo">
            <h1>MAHA GANAPATHI BHAKTHA BRUNDHAM</h1>
            <div class="subtitle">Ganesh Chaturthi Mahotsavam · 2026</div>
            <div class="location">📍 Karanam gari street, Patamata, Vijayawada - 520010</div>
        </header>

        <section class="events-section">
            <h2>🌺 EVENT DETAILS 🌺</h2>
            <div class="event-grid">
                
                <div class="event-card">
                    <h3>🗓 Ganesh Chaturthi (Day Start)</h3>
                    <p><strong>Date:</strong> 14 Sep 2026 (Monday)<br><strong>Time:</strong> 6:00 AM</p>
                </div>

                <div class="event-card">
                    <h3>🍚 Food Donation (Annadhanam)</h3>
                    <p><strong>Date:</strong> 17 Sep 2026<br><strong>Time:</strong> 12:00 PM</p>
                </div>

                <div class="event-card">
                    <h3>🍬 Laddu Auction</h3>
                    <p><strong>Date:</strong> 20 Sep 2026<br><strong>Time:</strong> 7:00 PM</p>
                </div>

                <div class="event-card">
                    <h3>🌊 Day of Visarjan</h3>
                    <p><strong>Date:</strong> 20 Sep 2026 (Sunday)<br><strong>Time:</strong> 4:00 PM</p>
                </div>

            </div>
        </section>

        <footer>
            <p>Ganapati Bappa Moriya 🙏</p>
        </footer>
    </div>

</body>
</html>
