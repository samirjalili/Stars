<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mein Portfolio</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #0f172a, #1e293b);
    color: white;
}

/* Header */
header {
    text-align: center;
    padding: 60px 20px;
}

h1 {
    font-size: 50px;
    margin-bottom: 10px;
    animation: fadeIn 2s ease-in-out;
}

p {
    color: #cbd5e1;
}

/* Buttons */
.btn {
    display: inline-block;
    margin-top: 20px;
    padding: 12px 25px;
    background: #38bdf8;
    color: black;
    border-radius: 8px;
    text-decoration: none;
    font-weight: bold;
    transition: 0.3s;
}

.btn:hover {
    transform: scale(1.1);
    background: #0ea5e9;
}

/* Sections */
section {
    padding: 60px 20px;
    text-align: center;
}

.card {
    background: rgba(255,255,255,0.05);
    padding: 20px;
    margin: 15px;
    border-radius: 12px;
    display: inline-block;
    width: 250px;
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-10px);
    background: rgba(255,255,255,0.1);
}

/* Footer */
footer {
    text-align: center;
    padding: 30px;
    color: #94a3b8;
}

/* Animation */
@keyframes fadeIn {
    from { opacity: 0; transform: translateY(-20px); }
    to { opacity: 1; transform: translateY(0); }
}
</style>

</head>

<body>

<header>
    <h1>👋 Hallo, ich bin samir jalili</h1>
    <p>Ich lerne gerade IT und möchte Fachinformatiker werden</p>
    <a class="btn" href="#about">Mehr über mich</a>
</header>

<section id="about">
    <h2>Über mich</h2>
    <p>Ich interessiere mich für Computer, Programmieren und Technik.</p>
</section>

<section>
    <h2>Meine Skills</h2>

    <div class="card">💻 HTML</div>
    <div class="card">🎨 CSS</div>
    <div class="card">⚡ JavaScript Basics</div>
</section>

<section>
    <h2>Meine Ziele</h2>

    <div class="card">
        🚀 Ausbildung in der IT
    </div>

    <div class="card">
        🧠 Programmieren lernen
    </div>

    <div class="card">
        💼 Praktikum finden
    </div>
</section>

<footer>
    © 2026 - Mein erstes IT Portfolio
</footer>

</body>
</html>
