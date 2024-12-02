<!--perus määrittelyt-->
<!DOCTYPE html>
<html lang="fi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <!--title ja iconi-->
    <title>AutoSivusto - Etusivu</title>
    <link rel="stylesheet" href="style.css">
    <link rel="icon" type="image/xicon" href="../Kuvat/favicon.ico">
</head>
<!--Näkyvä osio alkaa-->
<body>
    <header>
        <h1>AutoSivusto</h1>
        <nav aria-label="päävalikko">
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
        <section class="video-container">
            <!-- Taustavideo -->
            <video autoplay muted loop>
                <source src="../Kuvat/auto-häivytys.mp4" type="video/mp4">
            </video>
            
            <!-- Sivun pääsisältö -->
            <div class="content">
                <h2>Tervetuloa AutoSivustolle!</h2>
                <p>Oletko kiinnostunut autoista, uusimmista malleista, alan uutisista ja käytännön vinkeistä auton hankintaan ja huoltoon? 
                AutoSivusto on sinua varten! Sivustomme tarjoaa kattavasti tietoa autoista, 
                oli kyseessä sitten tulevaisuuden sähköautot, klassikkoautojen huolto tai käytetyn auton osto-opas.</p>
                
                <h3>Täältä löydät muun muassa:</h3>
                <ul>
                    <li><strong>Autouutiset:</strong> Pysy ajan tasalla autoteollisuuden uusimmista käänteistä ja trendeistä. Lue uusista automalleista, tekniikan innovaatioista ja alan tärkeimmistä tapahtumista.</li>
                    <li><strong>Autonostajan opas:</strong> Harkitsetko uuden tai käytetyn auton ostoa? Oppaastamme löydät vinkkejä auton valintaan ja tietoa eri ominaisuuksista, jotta osaat tehdä oikean päätöksen.</li>
                    <li><strong>Autohuolto ja ylläpito:</strong> Vinkkejä ja ohjeita auton perushuoltoon ja kunnossapitoon, jotta autosi säilyy hyvässä kunnossa ja toimii moitteettomasti vuodesta toiseen.</li>
                    <li><strong>Yhteystiedot ja kysymyspalsta:</strong> Ota yhteyttä kysymyksilläsi tai anna palautetta. Voit myös tutustua yleisimpiin kysymyksiin ja vastauksiin autoilusta.</li>
                </ul>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Niko Palola</p>
    </footer>
</body>
</html>
