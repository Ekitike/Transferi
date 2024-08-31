<!DOCTYPE html>
<html lang="en">
<head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PSG Transferi</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f2f5;
            color: #333;
        }
        header {
            background: linear-gradient(90deg, #0056b3, #001f54);
            color: #ffffff;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        header h1 {
            margin: 0;
            font-size: 40px;
            letter-spacing: 2px;
            text-transform: uppercase;
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 20px auto;
        }
        .section {
            margin-bottom: 40px;
            background-color: #ffffff;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s;
        }
        .section:hover {
            transform: scale(1.01);
        }
        .section h2 {
            font-size: 28px;
            margin-bottom: 20px;
            border-bottom: 2px solid #0056b3;
            padding-bottom: 10px;
            color: #0056b3;
        }
        .stats {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
        }
        .stats .stat {
            background-color: #0056b3;
            color: #ffffff;
            padding: 20px;
            border-radius: 10px;
            flex: 1;
            margin: 0 10px;
            text-align: center;
            font-size: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
            font-size: 18px;
        }
        table th, table td {
            padding: 15px;
            text-align: left;
            border-bottom: 1px solid #dee2e6;
        }
        table th {
            background-color: #f1f1f1;
            color: #333;
            text-transform: uppercase;
        }
        table tbody tr:hover {
            background-color: #f8f9fa;
        }
        .player-card-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }
        .player-card {
            background-color: #ffffff;
            border: 1px solid #dee2e6;
            border-radius: 12px;
            overflow: hidden;
            text-align: center;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s, box-shadow 0.2s;
        }
        .player-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
        }
        .player-card img {
            width: 100%;
            height: auto;
        }
        .player-card p {
            margin: 10px 0;
            font-size: 18px;
            color: #333;
        }
        .player-card p:last-child {
            font-weight: 600;
            font-size: 20px;
            color: #0056b3;
        }
        .footer {
            background-color: #001f54;
            color: #ffffff;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
            border-top: 4px solid #0056b3;
        }
        .footer p {
            margin: 0;
            font-size: 16px;
        }
    </style>
</head>
<body>

    <header>
        <h1>PSG Transferi</h1>
    </header>

    <div class="container">
        <div class="section">
            <h2>Transferi</h2>
            <div class="stats">
                <div class="stat">
                    <i class="fa-solid fa-dollar-sign"></i>
                    <h3>Ukupna prodaja</h3>
                    <p>16.5</p>
                </div>
                <div class="stat">
                    <i class="fa-solid fa-money-bill-wave"></i>
                    <h3>Ukupna kupovina</h3>
                    <p>165</p>
                </div>
                <div class="stat">
                    <i class="fa-solid fa-balance-scale"></i>
                    <h3>Omjer prodaje i kupovine</h3>
                    <p>-148.5</p>
                </div>
            </div>
        </div>

        <div class="section">
            <h2>Kupovina</h2>
            <table>
                <thead>
                    <tr>
                        <th><i class="fa-solid fa-user"></i> Ime i prezime</th>
                        <th><i class="fa-solid fa-euro-sign"></i> Cijena (u milionima eura)</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Matvey Safonov</td>
                        <td>15</td>
                    </tr>
                    <tr>
                        <td>Joao Neves</td>
                        <td>60</td>
                    </tr>
                     <tr>
                        <td>Willian Pacho</td>
                        <td>40</td>
                    </tr>
                     <tr>
                        <td>Desire Doue</td>
                        <td>50</td>
                    </tr>
                </tbody>
            </table>
        </div>

        <div class="section">
            <h2>Prodaja</h2>
            <table>
                <thead>
                    <tr>
                        <th><i class="fa-solid fa-user"></i> Ime i prezime</th>
                        <th><i class="fa-solid fa-euro-sign"></i> Cijena (u milionima eura)</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Hugo Ekitike</td>
                        <td>16.5</td>
                    </tr>
                    <tr>
                        <td>Kylian Mbappe</td>
                        <td>0</td>
                    </tr>
                     <tr>
                        <td>Laywin Kurzawa</td>
                        <td>0</td>
                    </tr>
                     <tr>
                        <td>Keylor Navas</td>
                        <td>0</td>
                    </tr>
                     <tr>
                        <td>Sergio Rico</td>
                        <td>0</td>
                    </tr>
                     <tr>
                        <td>Xavi Simons</td>
                        <td>posudba</td>
                    </tr>






                    <tr>
                        <td>Renato Sanches</td>
                        <td>posudba</td>
                    </tr>
                    <tr>
                        <td>Gabriel Moscardo</td>
                        <td>posudba</td>
                    </tr>

                    <tr>
                        <td>Cher Ndour</td>
                        <td>posudba</td>
                    </tr>


                    
                    <tr>
                        <td>Nordi Mukiele</td>
                        <td>posudba</td>
                    </tr>





                    

                </tbody>
            </table>
        </div>

        <div class="section">
            <h2>Ekipa</h2>
            <div class="player-card-container">
                <div class="player-card">
                     


                    <img src="https://www.psg.fr/media/270647/joueurs-24-25_safonov.png?center=0.5,0.5&mode=crop&width=400&height=600&quality=75" alt="">
                    <p>Matvey Safonov</p>
                    <p>39</p>
                
                </div>

                
                <div class="player-card">
                    <img src="https://www.psg.fr/media/271687/joueurs-2425-neves.png?center=0.5,0.5&mode=crop&width=400&height=600&quality=75" alt="">
                    <p>Joao Neves</p>
                    <p>87</p>
                </div>
                <div class="player-card">
                    <img src="https://www.psg.fr/media/272135/joueurs-24-25_pacho.png?center=0.5,0.5&mode=crop&width=400&height=600&quality=75" alt="">
                    <p>Willian Pacho</p>
                    <p>51</p>
                </div>
                <div class="player-card">
                    <img src="https://www.psg.fr/media/272747/card-24-25_doue.png?anchor=center&mode=crop&width=400&height=600&quality=75" alt="">
                    <p>Desire Doue</p>
                    <p>14</p>
                </div>
            </div>
        </div>
    </div>
f
    <footer class="footer">
        <p>&copy; 2024 PSG Transferi. Sva prava zadržana.</p>
    </footer>

</body>
</html>
