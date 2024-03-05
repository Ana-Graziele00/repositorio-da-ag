<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sistema Solar</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        section {
            padding: 20px;
        }
        img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 0 auto;
        }
        .planet-info {
            text-align: center;
            margin-top: 20px;
        }
        .planet-info a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <header>
        <h1>Sistema Solar</h1>
    </header>
    <section>
        <img src="sistema_solar.jpg" alt="Sistema Solar">
        <div class="planet-info">
            <h2>Informações sobre os Planetas</h2>
            <ul>
                <li><a href="#sol-info">Sol</a></li>
                <li><a href="#terra-info">Terra</a></li>
                <li><a href="#marte-info">Marte</a></li>
            </ul>
        </div>
        <div id="sol-info">
            <h2>Sol</h2>
            <p>O Sol é a estrela central do sistema solar. É uma esfera quase perfeita de plasma, que gera calor e luz por meio da fusão nuclear. Saiba mais sobre o <a href="sol.html">Sol</a>.</p>
        </div>
        <div id="terra-info">
            <h2>Terra</h2>
            <p>A Terra é o terceiro planeta do sistema solar e o único atualmente conhecido por abrigar vida. Saiba mais sobre a <a href="terra.html">Terra</a>.</p>
        </div>
        <div id="marte-info">
            <h2>Marte</h2>
            <p>Marte é o quarto planeta do sistema solar. Ele é conhecido como o "planeta vermelho" devido à sua aparência avermelhada. Saiba mais sobre <a href="marte.html">Marte</a>.</p>
        </div>
    </section>
</body>
</html>
