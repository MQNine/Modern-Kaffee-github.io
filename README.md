<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Frankfurts Modern Caffee</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
            margin: 0;
            padding: 0;
            background: url('https://source.unsplash.com/1600x900/?coffee,modern-cafe') no-repeat center center fixed;
            background-size: cover;
            color: white;
            height: 100vh;
        }

        header {
            text-align: center;
            padding: 50px 0;
            background-color: rgba(0, 0, 0, 0.7);
        }

        header h1 {
            font-size: 3.5em;
            margin: 0;
            text-transform: uppercase;
            font-weight: bold;
        }

        header p {
            font-size: 1.4em;
            margin-top: 10px;
        }

        nav {
            text-align: center;
            background-color: rgba(0, 0, 0, 0.8);
            padding: 15px;
        }

        nav a {
            color: white;
            margin: 0 20px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1em;
        }

        nav a:hover {
            color: #ff6f61;
        }

        .section {
            padding: 50px 20px;
            text-align: center;
            background-color: rgba(0, 0, 0, 0.6);
        }

        .section h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
            color: #ff6f61;
        }

        .section p {
            font-size: 1.3em;
            color: white;
            max-width: 900px;
            margin: 20px auto;
        }

        .menu, .wine-menu {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 30px;
            justify-items: center;
            margin-top: 30px;
        }

        .menu div, .wine-menu div {
            background-color: rgba(255, 255, 255, 0.9);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .menu div h3, .wine-menu div h3 {
            color: #333;
            font-size: 1.8em;
            margin-bottom: 10px;
        }

        .menu div img, .wine-menu div img {
            width: 100%;
            max-height: 250px;
            object-fit: cover;
            border-radius: 8px;
            margin-bottom: 15px;
        }

        .menu div ul {
            list-style-type: none;
            padding: 0;
        }

        .menu div ul li {
            font-size: 1.2em;
            color: #444;
        }

        .contact-form {
            max-width: 600px;
            margin: 50px auto;
            padding: 30px;
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
        }

        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 15px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 8px;
            font-size: 1em;
        }

        .contact-form button {
            background-color: #ff6f61;
            color: white;
            padding: 15px;
            border: none;
            border-radius: 8px;
            font-size: 1.2em;
            cursor: pointer;
            width: 100%;
        }

        .contact-form button:hover {
            background-color: #d85f52;
        }

        .footer {
            text-align: center;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.8);
            color: white;
        }

        .footer p {
            margin: 5px 0;
        }

        .footer a {
            color: #ff6f61;
            text-decoration: none;
            font-weight: bold;
        }

        .footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<header>
    <h1>Frankfurts Modern Caffee</h1>
    <p>Die perfekte Mischung aus Café und Unterhaltung!</p>
</header>

<nav>
    <a href="#menu">Speisekarte</a>
    <a href="#wine-menu">Wein Karte</a>
    <a href="#entertainment">Unterhaltung</a>
    <a href="#contact">Kontakt</a>
</nav>

<section id="menu" class="section">
    <h2>Unsere Speisekarte</h2>
    <p>Erlebe unvergessliche Geschmackserlebnisse im Modern Caffee, perfekt für den Alltag oder für besondere Anlässe!</p>

    <div class="menu">
        <div>
            <img src="https://images.unsplash.com/photo-1521747116042-5c3f18a49a3f" alt="Kaffee">
            <h3>Kaffee & Heißgetränke</h3>
            <ul>
                <li>Kaffee - 2,50 €</li>
                <li>Cappuccino - 3,00 €</li>
                <li>Latte Macchiato - 3,50 €</li>
                <li>Heiße Schokolade - 3,00 €</li>
            </ul>
        </div>
        <div>
            <img src="https://images.unsplash.com/photo-1542224522-c3f01907210d" alt="Smoothie">
            <h3>Alkoholfreie Getränke</h3>
            <ul>
                <li>Fruchtsäfte - 2,50 €</li>
                <li>Limonade - 2,80 €</li>
                <li>Mineralwasser - 1,80 €</li>
                <li>Eistee - 3,00 €</li>
            </ul>
        </div>
        <div>
            <img src="https://images.unsplash.com/photo-1511918984147-b7367fdbebc4" alt="Cocktail">
            <h3>Alkoholische Getränke</h3>
            <ul>
                <li>Wein (Rot/Weiß) - 4,00 €</li>
                <li>Craft Beer - 5,00 €</li>
                <li>Cocktails - ab 6,00 €</li>
                <li>Whisky - 6,50 €</li>
            </ul>
        </div>
        <div>
            <img src="https://images.unsplash.com/photo-1521747116042-5c3f18a49a3f" alt="Toast">
            <h3>Speisen (Unter der Woche)</h3>
            <ul>
                <li>Avocado Toast - 6,00 €</li>
                <li>Frühstücks-Bowl - 7,50 €</li>
                <li>Quiche - 8,00 €</li>
                <li>Würzige Suppe - 5,00 €</li>
            </ul>
        </div>
        <div>
            <img src="https://images.unsplash.com/photo-1505740428762-ea464db6e39f" alt="Risotto">
            <h3>Special Dishes (Besondere Anlässe)</h3>
            <ul>
                <li>Trüffel-Risotto - 15,00 €</li>
                <li>Rinderfilet mit Gemüse - 18,00 €</li>
            </ul>
        </div>
    </div>
</section>

<section id="wine-menu" class="section">
    <h2>Unsere Wein Karte</h2>
    <div class="wine-menu">
        <div>
            <h3>Weißweine</h3>
            <ul>
                <li>Chardonnay - 5,00 €</li>
                <li>Riesling - 4,50 €</li>
            </ul>
        </div>
        <div>
            <h3>Rotweine</h3>
            <ul>
                <li>Pinot Noir - 5,50 €</li>
                <li>Merlot - 5,00 €</li>
            </ul>
        </div>
    </div>
</section>

<section id="entertainment" class="section">
    <h2>Unterhaltungsprogramm</h2>
    <p>Samstags ab 20 Uhr bieten wir aufregende Unterhaltung mit Live-Musik und spannenden Events.</p>
</section>

<section id="contact" class="section">
    <h2>Kontakt & Reservierungen</h2>
    <p>Hast du eine Frage oder möchtest du einen Tisch reservieren? Wir freuen uns, von dir zu hören!</p>

    <div class="contact-form">
        <form action="mailto:Abdulfrankfurt515@gmail.com" method="post" enctype="text/plain">
            <label for="name">Name</label>
            <input type="text" id="name" name="name" required>

            <label for="email">E-Mail</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Nachricht</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <button type="submit">Anfrage senden</button>
        </form>
    </div>
</section>

<div class="footer">
    <p>Öffnungszeiten:</p>
    <p>Montag - Freitag: 8:00 Uhr - 20:00 Uhr</p>
    <p>Freitag: 8:00 Uhr - 00:00 Uhr</p>
    <p>Samstag: 8:00 Uhr - 02:00 Uhr</p>
    <p>Telefon: <strong>+49 123 456 789</strong></p>
    <p>© 2025 Frankfurts Modern Caffee. Alle Rechte vorbehalten.</p>
</div>

</body>
</html>
