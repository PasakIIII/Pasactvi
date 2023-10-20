<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PASÁCKÁ SEBRANKA</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #343434;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        main {
            padding: 20px;
        }

        .product {
            border: 1px solid #ddd;
            padding: 20px;
            margin: 10px;
            display: inline-block;
        }

        .product img {
            max-width: 100%;
        }
    </style>
</head>
<body style="background-color: #ca598a">
    <header>
        <h1>PASÁCKÉ SLUŽBY</h1>
        <nav>
            <ul>
                <li><a href="#">Domů</a></li>
                <li><a href="#onás"> O nás</a></li>
                <li><a href="#">Obchod</a></li>
                <li><a href="#contact">Kontakty</a></li>
                <li><a href="#dobypasení">Doby pasení</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section id="onás">
            <h2>O nás</h2>
            <p>Jsme profesionální firma specializující se na pasáctví všeho druhu. <br>
               S více než desetiletou zkušeností jsme připraveni vám pomoci s vašemi ovcemi a ostatním dobytkem.</p> <br>
        </section>
        <section>
            <h2>Prodej ovcí</h2>
            <p>Nejlepší ovce z celého světa</p>
        </section>
        
        <section>
            <div class="produkt">
                <img src="/images/ovce2.jpg" alt="Sheep 1" width=" 276" height="183">
                <h3>Model bavorian</h3>
                <p>Cena: 1 000 $</p>
                <p>Tato ovce nejlépe pase na louce plné kvítí, <br>
                   často můžeme ovce vidět v ohradách bavorských statkářů.</p> <br>
                <button>Přidat do návěsu</button>
            </div>

            <div class="produkt"> 
                <img src="/images/ovce1.jpg" alt="Sheep 2" width="276" height="183">
                <h3>Model columbian</h3>
                <p>Cena: 2 300 $</p>
                <p>Tento model ovce pochází až z daleké columbie, kde bývají odchovány na kokainu, <br>
                   proto když ovci do krmiva přidáte 2g kokainu dokáže spást až 250 metrů čtverečních za den.</p> <br>
                <button>Přidat do návěsu</button>
            </div>
<hr>
           <section>
                
            <button onclick="location.href='privateservices2.html'">PODPULTOVKY</button>

            </div>
            
            

        </section>
         
<hr>

        <section id="dobypasení"> <section id="contact">
            <table>
                <tr>
                    <td>
                        <table border="1">
                            <tr>
                                <td>Doby pasení</td>
                            </tr>
                            <tr>
                                <td>Po 9:00-20:00</td>
                            </tr>
                            <tr>
                                <td>Út 9:00-20:00</td>
                            </tr>
                            <tr>
                                <td>St 8:00-23:30</td>
                            </tr>
                            <tr>
                                <td>Čt 8:00-23:30</td>
                            </tr>
                            <tr>
                                <td>Pá 8:00-23:30</td>
                            </tr>
                        </table>
                    </td>
                    <td>
                        <table border="1">
                            <tr>
                                <td>Kontakty:</td>
                            </tr>
                            <tr>
                                <td>e-mail: pasactvi@seznam.cz</td>
                            </tr>
                            <tr>
                                <td>tel.: +420 420 666 123</td>
                            </tr>
                        </table>
                    </td>
                </tr>
            </table>
            </section>
        </section>
    </main>
    
    <footer>
        <center><p>&copy; 2023 PASÁCKÁ SEBRANKA</p></center>
    </footer>
</body>
</html>
