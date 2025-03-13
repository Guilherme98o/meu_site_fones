<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja de Fones de Ouvido</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }

        header {
            background-color: #2c3e50;
            color: white;
            padding: 15px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        .product-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 20px;
        }

        .product {
            background-color: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 10px;
            padding: 20px;
            width: 200px;
            text-align: center;
            border-radius: 8px;
        }

        .product img {
            max-width: 100%;
            border-radius: 8px;
        }

        .product h3 {
            margin: 10px 0;
        }

        .product p {
            color: #555;
        }

        .product .price {
            font-size: 1.2em;
            color: #e74c3c;
            margin: 10px 0;
        }

        .product button {
            background-color: #27ae60;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
        }

        .product button:hover {
            background-color: #2ecc71;
        }

        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        .contact-info {
            margin: 10px 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Loja de Fones de Ouvido</h1>
        <p>Compre os melhores fones de ouvido!</p>
    </header>

    <div class="product-container">
        <!-- Produto 1 -->
        <div class="product">
            <img src="https://via.placeholder.com/200x200" alt="Fone 1">
            <h3>Fone Premium</h3>
            <p>Fone de ouvido com som de alta qualidade e conforto.</p>
            <p class="price">R$ 299,90</p>
            <button>Comprar</button>
        </div>

        <!-- Produto 2 -->
        <div class="product">
            <img src="https://via.placeholder.com/200x200" alt="Fone 2">
            <h3>Fone Bluetooth</h3>
            <p>Sem fio, ideal para esportes e mobilidade.</p>
            <p class="price">R$ 199,90</p>
            <button>Comprar</button>
        </div>

        <!-- Produto 3 -->
        <div class="product">
            <img src="https://via.placeholder.com/200x200" alt="Fone 3">
            <h3>Fone de Ouvido Gamer</h3>
            <p>Som surround para a melhor experiência de jogos.</p>
            <p class="price">R$ 350,00</p>
            <button>Comprar</button>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 Loja de Fones de Ouvido</p>
        <div class="contact-info">
            <p>Entre em contato: contato@lojafo.com</p>
        </div>
    </footer>

</body>
</html>
