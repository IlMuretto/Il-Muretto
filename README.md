# Il-Muretto
<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rosticceria La Buona Tavola</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>La Buona Tavola</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#about">Chi Siamo</a></li>
                <li><a href="#contact">Contatti</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <h2>Benvenuti alla Rosticceria La Buona Tavola</h2>
        <p>Dove il gusto autentico incontra la tradizione!</p>
        <a href="#menu" class="btn">Scopri il Menu</a>
    </section>

    <section id="menu">
        <h2>Il Nostro Menu</h2>
        <div class="menu-items">
            <div class="item">
                <h3>Arancini</h3>
                <p>Croccanti e ripieni di delizia. €2,50</p>
            </div>
            <div class="item">
                <h3>Pollo allo Spiedo</h3>
                <p>Succoso e saporito. €12,00</p>
            </div>
            <div class="item">
                <h3>Lasagne al Forno</h3>
                <p>La vera ricetta italiana. €8,00</p>
            </div>
            <div class="item">
                <h3>Verdure Grigliate</h3>
                <p>Perfette per accompagnare ogni piatto. €5,00</p>
            </div>
        </div>
    </section>

    <section id="about">
        <h2>Chi Siamo</h2>
        <p>La Rosticceria La Buona Tavola nasce dalla passione per la cucina casalinga e tradizionale. Offriamo piatti preparati con ingredienti freschi e di alta qualità, portando il sapore autentico delle nostre terre direttamente a casa tua.</p>
    </section>

    <section id="contact">
        <h2>Contatti</h2>
        <p>Vieni a trovarci o contattaci per ordinare!</p>
        <ul>
            <li>Indirizzo: Via Roma 123, Milano</li>
            <li>Telefono: <a href="tel:+391234567890">+39 123 456 7890</a></li>
            <li>Email: <a href="mailto:info@labuonatavola.it">info@labuonatavola.it</a></li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2025 Rosticceria La Buona Tavola. Tutti i diritti riservati.</p>
    </footer>
</body>
</html>

/* styles.css */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    color: #333;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #e63946;
    color: #fff;
    padding: 10px 20px;
}

header .logo h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    display: flex;
    margin: 0;
    padding: 0;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.hero {
    background: url('rosticceria.jpg') no-repeat center center/cover;
    color: #fff;
    text-align: center;
    padding: 100px 20px;
}

.hero h2 {
    font-size: 2.5em;
    margin: 0;
}

.hero .btn {
    display: inline-block;
    margin-top: 20px;
    padding: 10px 20px;
    background: #f4a261;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
    font-size: 1.2em;
}

.hero .btn:hover {
    background: #e76f51;
}

section {
    padding: 40px 20px;
    text-align: center;
}

#menu .menu-items {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

#menu .item {
    background: #f4f4f4;
    border: 1px solid #ddd;
    border-radius: 5px;
    padding: 20px;
    width: 200px;
}

#menu .item h3 {
    margin-top: 0;
    color: #e63946;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}
