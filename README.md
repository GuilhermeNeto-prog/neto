<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agro Forte e Sustentável</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>🌱 Agro Forte e Sustentável</h1>
    <p>Tecnologia, produtividade e preservação ambiental caminhando juntas.</p>
</header>

<section class="sobre">
    <h2>Sobre o Projeto</h2>
    <p>
        O Agro Forte e Sustentável promove práticas agrícolas responsáveis,
        incentivando o uso consciente dos recursos naturais, a inovação tecnológica
        e a produção de alimentos de qualidade.
    </p>
</section>

<section class="beneficios">
    <h2>Benefícios</h2>
    <div class="card">
        <h3>🌾 Produção Eficiente</h3>
        <p>Maior produtividade com menos desperdício.</p>
    </div>

    <div class="card">
        <h3>💧 Uso Consciente da Água</h3>
        <p>Sistemas de irrigação inteligentes e sustentáveis.</p>
    </div>

    <div class="card">
        <h3>🌳 Preservação Ambiental</h3>
        <p>Proteção do solo, das florestas e da biodiversidade.</p>
    </div>
</section>

<section class="contador">
    <h2>Impacto Positivo</h2>
    <button onclick="mostrarMensagem()">Ver Resultado</button>
    <p id="resultado"></p>
</section>

<footer>
    <p>© 2026 Agro Forte e Sustentável</p>
</footer>

<script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #f4fff4;
    color: #333;
}

header {
    background: #2e7d32;
    color: white;
    text-align: center;
    padding: 40px;
}

section {
    padding: 30px;
}

.beneficios {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
}

.card {
    background: white;
    border-radius: 10px;
    padding: 20px;
    flex: 1;
    min-width: 220px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

button {
    background: #388e3c;
    color: white;
    border: none;
    padding: 12px 20px;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background: #2e7d32;
}

footer {
    background: #1b5e20;
    color: white;
    text-align: center;
    padding: 15px;
}
# 🌱 Agro Forte e Sustentável

Projeto desenvolvido para conscientizar sobre a importância da agricultura sustentável.

## Objetivos
- Promover práticas agrícolas sustentáveis.
- Incentivar o uso eficiente dos recursos naturais.
- Demonstrar os benefícios da tecnologia no campo.

## Tecnologias
- HTML5
- CSS3
- JavaScript

## Como executar
1. Baixe os arquivos.
2. Abra o arquivo `index.html` no navegador.
