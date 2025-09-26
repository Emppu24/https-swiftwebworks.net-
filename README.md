<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Empun palvelut - Ilo Auttaa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #90c5ff;
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-size: cover;
            opacity: 1;
            position: relative;
        }

        header {
            background-image: url('Kuvat/Snapchat-1601874176.jpg');
            background-size: cover;
            background-position: center top;
            color: #000;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            z-index: 1;
        }

        #logo {
            width: 100px;
            height: auto;
        }

        header div:last-child {
            margin-top: 20px;
        }

        nav {
            display: flex;
            justify-content: center;
            padding: 10px;
            background-color: #90c5ff;
        }

        nav a {
            color: #000;
            text-decoration: none;
            margin: 0 20px;
            cursor: pointer;
            transition: transform 0.3s ease;
        }

        section {
            position: relative;
            z-index: 1;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: left;
            padding: 20px;
            z-index: 1;
            background-color: transparent;
            transition: transform 0.3s ease, filter 0.5s ease;
        }

        section div {
            border: 2px solid #496274;
            padding: 15px;
            background-color: transparent;
            max-width: 1200px;
            margin: 0 auto;
        }

        section h2 {
            margin-bottom: 10px;
            text-align: center;
            background-color: #2b3f52;
            color: #ffffff;
            padding: 10px;
        }

        section p {
            margin-right: 20px;
            color: #333;
        }

        img {
            max-width: 100%;
            height: auto;
            margin-top: 10px;
        }

        .text-container {
            flex: 1;
            margin: 0 20px;
        }

        hr {
            margin: 40px 0;
            border: none;
            border-top: 2px solid #5a7c9b;
        }

        .product-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            margin-top: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .product-box {
            border: 2px solid #363a3d;
            padding: 15px;
            background-color: #90bdee;
            max-width: 300px;
            text-align: center;
            margin: 10px;
            transition: transform 0.3s ease;
        }

        .product-box img {
            max-width: 100%;
            height: auto;
            margin-top: 10px;
        }

        footer {
            text-align: center;
            background-image: url('Kuvat/Snapchat-1601874176.jpg');
            background-size: cover;
            background-position: center bottom;
            padding: 10px;
            color: #000000;
            margin-top: 20px;
            font-size: 22px;
        }

        #palvelut {
            padding-top: 50px;
            padding-bottom: 50px;
        }

        .highlighted {
            background-color: #f0f0f0;
        }

        nav a:hover {
            transform: scale(1.1);
        }

        section:hover {
            transform: scale(1.05);
            z-index: 2;
        }

        section:not(:hover) {
            transition: transform 0.3s ease, filter 0.5s ease;
        }

        #yleistietoa {
            background-image: url('Kuvat/pihatyot-karhuilla-1.jpg');
            background-size: cover;
            background-position: center;
            padding-top: 50px;
            padding-bottom: 50px;
        }

        #yleistietoa .text-container {
            background-color: rgba(223, 239, 255, 0.8);
            height: 300px;
            max-width: 600px;
        }

        #Laita_oma .text-container{
            background-color: rgba(236, 245, 255, 0.8);
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
</head>

<body>

    <header>
        <div id="logo">
            <img src="Kuvat/empun-palvelut-logo.webp" alt="Logo">
        </div>
        <div>
            <h1>Empun palvelut - Ilo auttaa!</h1>
            <p style="color: #000000;">Etsitkö auttavaa kättä askareissa ja huolloissa Porvoonseudun alueella? Empun palvelut 4HY on täällä auttamassa!</p>
        </div>
        
    </header>

    <nav>
        <a href="#Laita_oma">Laita oma</a>
        <a href="#yleistietoa">Yleistietoa</a>
        <a href="#palvelut">Palvelut</a>
        <a href="#footer">Yhteystiedot</a>
    </nav>

    <hr>

    <section id="Laita_oma">
        <div class="text-container">
            <h2>Tähän Title <title></title></h2>
            <div>
                <p>Tähän Oma teksti</p>
                <p>Tähän Oma teksti</p>
            </div>
        </div>
        <img src="Kuvat/Screenshot 2024-01-24 132955.png" alt="Emil">
    </section>

    <hr>

    <section id="yleistietoa">
        <div class="text-container">
            <h2>Yleistietoa</h2>
            <div>
                <p>Empun Palvelut 4HY yritykseni kautta autan asiakkaitani tarjoamalla heille laadukkaita palveluita.</p>
                <p>Tavoitteenani on palvella asiakkaita, jotka eivät itse pääse kiireisen arjen takia tai eivät itse pysty hoitamaan pihatöitä, polkupyörän huoltoa, auton renkaiden vaihtoa yms. Empun palvelut tarjoaa auttavan käden asiakkaiden arjen askareissa ja pyrin aina tarjoamaan asiakkailleni parasta mahdollista palvelua. Asiakastyytyväisyys on minulle tärkeä arvo, jonka takia teen yhteistyötä jokaisen asiakkaan kanssa luotettavasti ja vastuullisesti.</p>
            </div>
        </div>
    </section>

    <hr>

    <section id="palvelut">
        <div class="text-container">
            <h2>Palvelut</h2>
            <div class="product-container">
                <div class="product-box">
                    <h3>Pihatyöt</h3>
                    <img src="Kuvat/1664b7a0-670e-416f-a585-05f11e3d3518.jpg" alt="Pihatyöt Photo">
                    <p> Pihatyöpalveluihin kuuluu mm. nurmenleikkuu, lumityöt ja maalaus.
                        <br><br>
                        Kaikki 25€/tunti</p>
                </div>
                <div class="product-box">
                    <h3>Huoltopalvelut</h3>
                    <img src="Kuvat/metu vahaus.jpg" alt="Huoltopalvelut Photo">
                    <p> Tarjoan autoille renkaanvaihtopalveluita
                        <br>
                        Renkaanvaihto: 25€ (+vanteiden pesu 5€)
                        <br> <br>
                        Polkupyörät
                        <br>
                        Tarjoan polkupyörille renkaanvaihto ja huoltopalveluita.
                        <br>
                        Perushuolto alkaen 20€, sisältää pesun, ketjujen rasvauksen ja pyörän läpikäynnin sekä pikkuvikojen korjauksen  
                        <br> <br>
                        Renkaanvaihto: 15€</p>
                </div>
                <div class="product-box">
                    <h3>Puutyöt</h3>
                    <img src="Kuvat/puutyot-4k.webp" alt="Puutyöt Photo">
                    <p>Laaja valikoima puutöitä:
                        <br>
                        Katajasta tehtyjä voiveitsiä ja lastoja (rajoitetusti puulajin rauhoittamisesta johtuen)  
                        <br>
                        Tilaustyönä myös esimerkiksi käsintehtyjä huonekaluja ja koirien noutokapuloita
                        <br>
                        Normaalit veitset: 4€
                        <br>
                        Ketun muotoiset voiveitset: 6€
                        <br>
                        Pienet lastat: 5€
                        <br>
                        Isot lastat: 7€</p>
                </div>
            </div>
        </div>
    </section>

    <hr>

    <div id="footer">
    <footer>
        <h4>Empun palvelut - Ilo auttaa!</h4>
        <div>
            <p>045 8408668</p>
            <p>vainio.emil24@gmail.com</p>
            <p>Porvoo</p>
            <a href="https://www.facebook.com/profile.php?id=100091254562278" target="_blank" rel="noopener noreferrer">
                <i class="fab fa-facebook-square"></i>
            </a>
        </div>
    </footer>
    </div>

    <script>
        document.addEventListener("DOMContentLoaded", function () {
            document.querySelectorAll("nav a").forEach(function (button) {
                button.addEventListener("mouseover", function () {
                    this.style.transform = "scale(1.1)";
                });
                button.addEventListener("mouseout", function () {
                    this.style.transform = "scale(1)";
                });
            });

            document.querySelectorAll("section").forEach(function (section) {
                section.addEventListener("mouseover", function () {
                    this.style.transform = "scale(1.05)";
                    this.style.zIndex = "2";
                    document.querySelectorAll("section:not(:hover)").forEach(function (otherSection) {
                        otherSection.style.filter = "blur(1px)";
                    });
                });
                section.addEventListener("mouseout", function () {
                    this.style.transform = "scale(1)";
                    this.style.zIndex = "1";
                    document.querySelectorAll("section").forEach(function (otherSection) {
                        otherSection.style.filter = "blur(0)";
                    });
                });
            });
        });

        document.addEventListener("DOMContentLoaded", function () {
            document.querySelectorAll('nav a').forEach(anchor => {
                anchor.addEventListener('click', function (e) {
                    e.preventDefault();
                    
                    const targetId = this.getAttribute('href');
                    const targetSection = document.querySelector(targetId);

                    window.scrollTo({
                        top: targetSection.offsetTop,
                        behavior: 'smooth'
                    });
                });
            });
        });
    </script>


</body>

</html>
