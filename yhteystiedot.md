<!--perus määrittelyt-->
<!DOCTYPE html>
<html lang="fi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!--title ja iconi-->
    <title>AutoSivusto - Yhteystiedot</title>
    <link rel="stylesheet" href="yhteystiedot.css">
    <link rel="icon" type="image/xicon" href="../Kuvat/favicon.ico">
</head>
<!--Näkyvä osio alkaa-->
<body>
    <header>
        <h1>AutoSivusto</h1>
        <nav>
            <!--Navigointi-->
            <ul>
                <li><a href="index.html">Etusivu</a></li>
                <li><a href="uutiset.html">Autouutiset</a></li>
                <li><a href="opas.html">Autonostajan opas</a></li>
                <li><a href="huolto.html">Autohuolto</a></li>
                <li><a href="yhteystiedot.html">Yhteystiedot</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!--yhteystiedot-->
        <section>
            <h2>Yhteystiedot</h2>
            <p>Ota yhteyttä AutoSivuston asiakaspalveluun, voit lähettää viestin oheisella lomakkeella.</p>
            <p><strong>Sähköposti:</strong> niko.palola@centria.fi</p>
        </section>

        <!--nimiosio-->
        <section class="contact-form">
            <h3>Lähetä viesti</h3>
            <form action="#" method="post">
                <label for="name">Nimi:</label>
                <input type="text" id="name" name="name" required>
<!--sähköpostiosio-->
                <label for="email">Sähköposti:</label>
                <input type="email" id="email" name="email" required>
<!--viestiosio-->
                <label for="message">Viesti:</label>
                <textarea id="message" name="message" rows="5" required></textarea>
<!--lähetä nappi-->
                <button type="submit">Lähetä</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Niko Palola</p>
    </footer>
</body>
</html>
