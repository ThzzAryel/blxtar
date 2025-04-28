<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BLXTAR Loader</title>
    <style>
        body {
            background: linear-gradient(135deg, #0d0d0d, #001f3f, #003366, #4b0082);
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            color: #fff;
        }

        #logo {
            font-size: 48px;
            font-weight: bold;
            color: #ffffff;
            text-shadow: 0 0 15px #4b0082, 0 0 25px #007bff;
            margin-bottom: 20px;
        }

        #loader {
            font-size: 24px;
            animation: pulse 2s infinite;
            margin-bottom: 10px;
        }

        @keyframes pulse {
            0% { opacity: 0.5; }
            50% { opacity: 1; }
            100% { opacity: 0.5; }
        }

        #content {
            display: none;
            font-size: 20px;
            text-align: center;
        }

        .star {
            color: #4b0082;
            font-size: 64px;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>

    <div id="logo">BLXTAR</div>
    <div class="star">&#9733;</div> <!-- Estrela bonita -->
    <div id="loader">Carregando seu script mágico...</div>
    
    <div id="content">
        <h2>Bem-vindo ao BLXTAR!</h2>
        <p>Script carregado com sucesso.</p>
        <p>Desenvolvido com carinho pelo <strong>@thzz_aryell</strong></p>
    </div>

    <script>
        function loadScript() {
            setTimeout(function() {
                document.getElementById('loader').style.display = 'none';
                document.getElementById('content').style.display = 'block';
            }, 3000); // 3 segundos de carregamento
        }
        window.onload = loadScript;
    </script>

</body>
</html>
