<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Primeiro Site</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f4f4f4;
            margin: 0;
            padding: 20px;
        }
        header {
            background: #4A90E2;
            color: white;
            padding: 20px;
            text-align: center;
        }
        section {
            background: white;
            padding: 20px;
            margin-top: 20px;
            border-radius: 8px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Bem-vindo ao meu site!</h1>
    </header>

    <section>
        <h2>Sobre mim</h2>
        <p>Este é um exemplo simples de página HTML com um pouco de CSS embutido.</p>
    </section>

</body>
</html>/* Reset básico */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Corpo geral */
body {
    font-family: "Arial", sans-serif;
    background-color: #f4f4f4;
    color: #333;
    line-height: 1.6;
    padding: 20px;
}

/* Container centralizado */
.container {
    max-width: 900px;
    margin: auto;
    background: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

/* Títulos */
h1, h2, h3 {
    color: #4A90E2;
    margin-bottom: 10px;
}

/* Botão estilizado */
.btn {
    display: inline-block;
    padding: 10px 20px;
    background-color: #4A90E2;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    transition: 0.3s;
}

.btn:hover {
    background-color: #357ABD;
}

/* Cards */
.card {
    background: #ffffff;
    padding: 15px;
    border-radius: 6px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    margin-bottom: 20px;
}

.card h3 {
    margin-bottom: 8px;
}

/* Navegação simples */
nav ul {
    list-style: none;
    display: flex;
    gap: 15px;
    margin-bottom: 20px;
}

nav a {
    color: #4A90E2;
    text-decoration: none;
    font-weight: bold;
}

nav a:hover {
    text-decoration: underline;
}// Exibe uma mensagem no console
console.log("JavaScript carregado com sucesso!");

// Muda o texto de um elemento ao clicar em um botão
function mudarTexto() {
    const titulo = document.getElementById("titulo");
    titulo.textContent = "O texto mudou graças ao JavaScript!";
}

// Mostra um alerta de boas-vindas ao abrir a página
window.onload = function() {
    alert("Bem-vindo ao site!");
};
