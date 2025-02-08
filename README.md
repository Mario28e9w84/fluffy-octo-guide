<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Il Mio Sito Web</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Benvenuto su Il Mio Sito</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Chi Siamo</a></li>
                <li><a href="#">Contatti</a></li>
            </ul>
        </nav>
    </header>

    <section>
        <h2>Chi Siamo</h2>
        <p>Questo è un esempio di sito web creato con HTML, CSS e JavaScript.</p>
        <button onclick="saluta()">Cliccami!</button>
    </section>

    <script src="script.js"></script>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
}

header {
    background-color: #333;
    color: white;
    padding: 20px;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

function saluta() {
    alert("Ciao! Benvenuto nel Codice penale.");
}
<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Codice Penale Americano</title>
    <link rel="stylesheet" href="style.css">
    <script src="script.js" defer></script>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;600&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <h1>Codice Penale Americano</h1>
        <p>Leggi e sanzioni federali degli Stati Uniti</p>
    </header>

    <section class="content">
        <h2>1. Reati contro la persona</h2>
        <p><strong>Omicidio di primo grado:</strong> punibile con ergastolo o pena di morte.</p>
        <p><strong>Omicidio colposo:</strong> punibile con 5-10 anni di carcere.</p>
        <p><strong>Aggressione aggravata:</strong> fino a 15 anni di carcere.</p>

        <h2>2. Reati contro il patrimonio</h2>
        <p><strong>Furto aggravato:</strong> sopra i $1.000, punibile con 5-20 anni di carcere.</p>
        <p><strong>Frode finanziaria:</strong> fino a $1.000.000 di multa e 25 anni di carcere.</p>

        <h2>3. Reati contro lo Stato</h2>
        <p><strong>Terrorismo:</strong> ergastolo o pena di morte.</p>
        <p><strong>Tradimento:</strong> punibile con ergastolo.</p>
    </section>

    <footer>
        <p>© 2025 Codice Penale USA | Font: Montserrat | Powered by Aragosta Smeraldo</p>
    </footer>
</body>
</html>
body {
    font-family: 'Montserrat', sans-serif;
    margin: 0;
    padding: 0;
    color: white;
    text-align: center;
    background-size: cover;
    background-position: center;
    transition: background 1s ease-in-out;
}

header {
    background: rgba(0, 0, 0, 0.6);
    padding: 20px;
}

h1 {
    font-weight: 600;
    font-size: 2.5em;
}

p {
    font-weight: 300;
    font-size: 1.2em;
}

.content {
    padding: 30px;
    background: rgba(0, 0, 0, 0.6);
    border-radius: 10px;
    margin: 20px auto;
    width: 80%;
}

h2 {
    color: #FFD700;
    margin-top: 20px;
}

footer {
    background: rgba(0, 0, 0, 0.8);
    padding: 15px;
    margin-top: 20px;
}
const backgrounds = [
    "url('https://source.unsplash.com/1600x900/?new-york')",
    "url('https://source.unsplash.com/1600x900/?los-angeles')",
    "url('https://source.unsplash.com/1600x900/?san-francisco')",
    "url('https://source.unsplash.com/1600x900/?chicago')",
    "url('https://source.unsplash.com/1600x900/?washington')"
];

function changeBackground() {
    document.body.style.backgroundImage = backgrounds[Math.floor(Math.random() * backgrounds.length)];
}

setInterval(changeBackground, 5000); // Cambia sfondo ogni 5 secondi
changeBackground();
