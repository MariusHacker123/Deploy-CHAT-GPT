<!DOCTYPE html>
<html lang="no">
<head>
    <meta charset="UTF-8">
    <title>Manchester United Ultimat Fan Universe</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-red: #DA291C;
            --secondary-black: #000000;
            --accent-gold: #FFD700;
            --background-gray: #f4f4f4;
        }
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            background: linear-gradient(135deg, var(--background-gray), #e0e0e0);
            color: #333;
            line-height: 1.6;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        header {
            background: linear-gradient(to right, var(--primary-red), #8B0000);
            color: white;
            text-align: center;
            padding: 30px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            clip-path: polygon(0 0, 100% 0, 100% 85%, 0 100%);
        }
        .navigation {
            display: flex;
            justify-content: center;
            background: var(--secondary-black);
            padding: 15px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }
        .navigation a {
            color: white;
            text-decoration: none;
            margin: 0 20px;
            font-weight: bold;
            transition: all 0.3s ease;
            position: relative;
        }
        .navigation a:hover {
            color: var(--accent-gold);
            transform: scale(1.1);
        }
        .navigation a::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -5px;
            left: 50%;
            background-color: var(--accent-gold);
            transition: width 0.3s ease;
        }
        .navigation a:hover::after {
            width: 100%;
            left: 0;
        }
        .section {
            background: white;
            border-radius: 10px;
            padding: 30px;
            margin: 20px 0;
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        .section:hover {
            transform: translateY(-10px);
        }
        .player-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }
        .player-card {
            text-align: center;
            background: #f9f9f9;
            padding: 15px;
            border-radius: 8px;
            transition: all 0.3s ease;
        }
        .player-card:hover {
            background: var(--primary-red);
            color: white;
        }
        .iframe-button-container {
            text-align: center;
            margin: 20px 0;
        }
        .iframe-button {
            display: inline-block;
            background: var(--primary-red);
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            text-decoration: none;
            transition: background 0.3s ease;
        }
        .iframe-button:hover {
            background: var(--accent-gold);
            color: var(--secondary-black);
        }
        footer {
            background: var(--secondary-black);
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>🔴 Manchester United Ultimat Fan Universe 🏆</h1>
        <p>Passion, Prestasjon, Stolthet</p>
    </header>

    <nav class="navigation">
        <a href="#hjem">Hjem</a>
        <a href="#spillere">Spillere</a>
        <a href="#historie">Historie</a>
        <a href="#trofeer">Trofeer</a>
    </nav>

    <div class="container">
        <section id="hjem" class="section">
            <h2>Velkommen til Den Røde Delen av Fotballuniverset!</h2>
            <p>Manchester United - mer enn en klubb, en global livsstil!</p>
        </section>

        <section id="spillere" class="section">
            <h2>Våre Legendariske Spillere</h2>
            <div class="player-grid">
                <div class="player-card">
                    <h3>Bruno Fernandes</h3>
                    <p>Midtbanemaestro</p>
                </div>
                <div class="player-card">
                    <h3>Marcus Rashford</h3>
                    <p>Angrepets Spydspiss</p>
                </div>
                <div class="player-card">
                    <h3>Casemiro</h3>
                    <p>Defensiv Gigant</p>
                </div>
            </div>
        </section>
    </div>

    <div class="iframe-button-container">
        <a class="iframe-button" href="https://copilotstudio.microsoft.com/environments/Default-1b6bba49-6f35-4d82-9fca-4827d417cd3e/bots/crc1e_ndlaAssistent/webchat" target="_blank">Gå til Assistent</a>
    </div>

    <iframe src="https://copilotstudio.microsoft.com/environments/Default-1b6bba49-6f35-4d82-9fca-4827d417cd3e/bots/crc1e_ndlaAssistent/webchat" frameborder="0" style="width: 100%; height: 100%;"></iframe>

    <footer>
        <p>&copy; 2024 Manchester United Ultimat Fan Universe. All rights reserved.</p>
    </footer>
</body>
</html>
