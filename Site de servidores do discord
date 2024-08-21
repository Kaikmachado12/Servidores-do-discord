<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Divulgação de Servidores Discord</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #E0FFFF; /* Azul bebê */
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            color: #333;
        }
        header {
            background-color: #B0E0E6;
            width: 100%;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            color: #005f73;
        }
        #login-button {
            margin-top: 10px;
            background-color: #008CBA;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        main {
            margin-top: 20px;
            width: 80%;
        }
        .server-form {
            background-color: #f0f8ff;
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        .server-form h2 {
            margin-top: 0;
            color: #0077b6;
        }
        .server-form label {
            display: block;
            margin-bottom: 8px;
            font-weight: bold;
        }
        .server-form input,
        .server-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .server-form button {
            background-color: #008CBA;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .server-list {
            margin-top: 20px;
        }
        .server-item {
            background-color: #bde0fe;
            padding: 15px;
            border-radius: 10px;
            margin-bottom: 10px;
        }
        .server-item h3 {
            margin: 0;
            color: #005f73;
        }
        .server-item p {
            margin: 5px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Divulgação de Servidores Discord</h1>
        <button id="login-button">Login com Discord</button>
    </header>

    <main>
        <section class="server-form">
            <h2>Adicione seu Servidor</h2>
            <label for="server-name">Nome do Servidor:</label>
            <input type="text" id="server-name" placeholder="Digite o nome do servidor">

            <label for="server-description">Descrição do Servidor:</label>
            <textarea id="server-description" rows="4" placeholder="Descreva seu servidor"></textarea>

            <button id="publish-button">Publicar Servidor</button>
        </section>

        <section class="server-list">
            <h2>Servidores Publicados</h2>
            <div id="servers-container">
                <!-- Os servidores aparecerão aqui -->
            </div>
        </section>
    </main>

    <script>
        document.getElementById('publish-button').addEventListener('click', function() {
            const serverName = document.getElementById('server-name').value;
            const serverDescription = document.getElementById('server-description').value;

            if (serverName && serverDescription) {
                const serverItem = document.createElement('div');
                serverItem.className = 'server-item';

                const serverTitle = document.createElement('h3');
                serverTitle.textContent = serverName;
                serverItem.appendChild(serverTitle);

                const serverDesc = document.createElement('p');
                serverDesc.textContent = serverDescription;
                serverItem.appendChild(serverDesc);

                document.getElementById('servers-container').appendChild(serverItem);

                // Limpar campos após adicionar o servidor
                document.getElementById('server-name').value = '';
                document.getElementById('server-description').value = '';
            } else {
                alert('Por favor, preencha todos os campos.');
            }
        });

        // Placeholder para a funcionalidade de login com Discord
        document.getElementById('login-button').addEventListener('click', function() {
            alert('Função de login com Discord será implementada.');
        });
    </script>
</body>
</html>
