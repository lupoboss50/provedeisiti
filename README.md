<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Invito di Compleanno</title>
    <style>
        body {
            /* Sfondo blu brillante */
            background-color: #004aad; 
            color: white;
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
            text-align: center;
            padding: 20px;
            box-sizing: border-box;
        }
        .container {
            background: rgba(255, 255, 255, 0.1);
            padding: 40px 20px;
            border-radius: 20px;
            box-shadow: 0 8px 32px rgba(0,0,0,0.3);
            width: 100%;
            max-width: 350px;
        }
        h1 {
            font-size: 28px;
            margin: 0 0 10px 0;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        h2 {
            font-size: 22px;
            margin: 0;
            font-weight: 300;
        }
        .divider {
            width: 50px;
            height: 3px;
            background-color: white;
            margin: 25px auto;
            border-radius: 5px;
        }
        .question {
            font-size: 26px;
            font-weight: bold;
            margin: 30px 0 40px;
            line-height: 1.3;
        }
        .buttons {
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        .btn {
            font-size: 18px;
            font-weight: bold;
            padding: 15px 40px;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            text-decoration: none;
            color: white;
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
            transition: transform 0.1s;
        }
        .btn:active {
            transform: scale(0.95);
        }
        .btn-yes {
            background-color: #25D366; /* Verde WhatsApp */
        }
        .btn-no {
            background-color: #ff3b30; /* Rosso */
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Il 23.06</h1>
        <h2>A casa mia</h2>
        
        <div class="divider"></div>

        <div class="question">Allora vieni al devasto?</div>

        <div class="buttons">
            <!-- Sostituisci IL_TUO_NUMERO con il tuo numero reale -->
            <a href="https://wa.me/IL_TUO_NUMERO?text=Ciao%20Monica%2C%20ci%20sar%C3%B2%20alla%20festa" class="btn btn-yes">Sì</a>
            <a href="https://wa.me/IL_TUO_NUMERO?text=Ciao%20Monica%2C%20non%20ci%20sar%C3%B2%20alla%20festa" class="btn btn-no">No</a>
        </div>
    </div>

</body>
</html>
