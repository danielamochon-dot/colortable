<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Tablas de Colores - Arte</title>
    <style>
        body { 
            font-family: sans-serif; 
            margin: 40px; 
            background-color: #f4f4f4; 
            line-height: 1.6;
        }
        .container { 
            max-width: 800px; 
            margin: 0 auto 60px auto; 
            background: white; 
            padding: 20px; 
            box-shadow: 0 4px 8px rgba(0,0,0,0.1); 
            border-radius: 8px;
        }
        img { 
            width: 100%; 
            height: auto; 
            display: block; 
            margin-bottom: 20px; 
            border-radius: 4px;
        }
        table { 
            width: 100%; 
            border-collapse: collapse; 
            text-align: center; 
        }
        th, td { 
            border: 1px solid #ddd; 
            padding: 12px; 
            width: 25%; 
        }
        /* Colores de las cabeceras */
        .p1-green { background-color: #88D8B0; }
        .p1-blue { background-color: #89CFF0; }
        .p1-lilac { background-color: #DCD0FF; }
        .p1-yellow { background-color: #FFFACD; }
        .p2-blue { background-color: #5A99AD; color: white; }
        .p2-gray { background-color: #9094A8; color: white; }
        .p2-green { background-color: #8DA36F; }
        .p2-orange { background-color: #E2A786; }
        .p3-orange { background-color: #C88A65; }
        .p3-pink { background-color: #E4A299; }
        .p3-beige { background-color: #EAD8C1; }
        .p3-red { background-color: #8B2B23; color: white; }
    </style>
</head>
<body>
    <div class="container">
        <img src="Copia de Claude-Monet-The-Waterlily-Pond-with-the-Japanese-Bridge-1899.jpg" alt="Waterlily Pond">
        <table>
            <tr>
                <th class="p1-green">Green</th>
                <th class="p1-blue">Blue</th>
                <th class="p1-lilac">Lilac</th>
                <th class="p1-yellow">Yellow</th>
            </tr>
            <tr>
                <td>#88D8B0</td><td>#89CFF0</td><td>#DCD0FF</td><td>#FFFACD</td>
            </tr>
            <tr>
                <td>(136, 216, 176)</td><td>(137, 207, 240)</td><td>(220, 208, 255)</td><td>(255, 250, 205)</td>
            </tr>
        </table>
    </div>
    <div class="container">
        <img src="Copia de MB-Mon-21_Monet_Steilkueste-von-Aval_1 2.jpg" alt="Cliffs">
        <table>
            <tr>
                <th class="p2-blue">Blue</th>
                <th class="p2-gray">Gray</th>
                <th class="p2-green">Green</th>
                <th class="p2-orange">Orange</th>
            </tr>
            <tr>
                <td>#5A99AD</td><td>#9094A8</td><td>#8DA36F</td><td>#E2A786</td>
            </tr>
            <tr>
                <td>(90, 153, 173)</td><td>(144, 148, 168)</td><td>(141, 163, 111)</td><td>(226, 167, 134)</td>
            </tr>
        </table>
    </div>
    <div class="container">
        <img src="cc4512ce9e2845f140221c0baa3de41e.jpg" alt="Dress Detail">
        <table>
            <tr>
                <th class="p3-orange">Orange</th>
                <th class="p3-pink">Pink</th>
                <th class="p3-beige">Beige</th>
                <th class="p3-red">Red</th>
            </tr>
            <tr>
                <td>#C88A65</td><td>#E4A299</td><td>#EAD8C1</td><td>#8B2B23</td>
            </tr>
            <tr>
                <td>(200, 138, 101)</td><td>(228, 162, 153)</td><td>(234, 216, 193)</td><td>(139, 43, 35)</td>
            </tr>
        </table>
    </div>
</body>
</html>
