# flexbox
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo Flexbox</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<main>
    <h1>Itens Organizados com Flexbox</h1>
    <div class="container">
        <div class="item">Item 1</div>
        <div class="item">Item 2</div>
        <div class="item">Item 3</div>
        <div class="item">Item 4</div>
        <div class="item">Item 5</div>
    </div>
</main>

</body>
</html>


body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

main {
    display: flex; /* Utiliza o flexbox para organizar os itens */
    flex-direction: row; /* Organiza os itens em linha (horizontalmente) */
    justify-content: center; /* Centraliza os itens horizontalmente */
    align-items: center; /* Centraliza os itens verticalmente */
    height: 100vh;
}

.container {
    display: flex; /* Utiliza o flexbox para organizar os itens */
    flex-wrap: wrap; /* Permite que os itens sejam quebrados em múltiplas linhas */
    justify-content: center; /* Centraliza os itens horizontalmente */
}

.item {
    background-color: #3498db;
    color: #fff;
    padding: 20px;
    margin: 10px;
    border-radius: 5px;
}
