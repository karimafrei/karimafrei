<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biquínis de Crochê</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f3f3f3;
            color: #333;
        }
        header {
            background-color: #0277bd;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #01579b;
        }
        nav a {
            padding: 14px 20px;
            text-decoration: none;
            color: white;
        }
        nav a:hover {
            background-color: #0277bd;
        }
        .container {
            padding: 20px;
        }
        .product {
            display: inline-block;
            width: 30%;
            margin: 10px;
            background-color: white;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            padding: 10px;
        }
        .product img {
            width: 100%;
        }
        .product button {
            background-color: #0277bd;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
        }
        .product button:hover {
            background-color: #01579b;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #0277bd;
            color: white;
        }
    </style>
</head>
<body>

    <header>
        <h1>Biquínis de Crochê - Elegância que Abraça o Sol e o Mar</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#loja">Loja</a>
        <a href="#sobre">Sobre Nós</a>
        <a href="#contato">Contato</a>
    </nav>

    <section id="home" class="container">
        <h2>Bem-vinda à nossa loja!</h2>
        <p>
            Nossos biquínis de crochê são criados à mão, trazendo autenticidade, sofisticação e a harmonia perfeita entre o mar e o sol.
        </p>
    </section>

    <section id="loja" class="container">
        <h2>Loja</h2>

        <div class="product">
            <img src="bikini1.jpg" alt="Biquíni de Crochê Azul">
            <h3>Biquíni Azul Oceano</h3>
            <p>R$150,00</p>
            <button>Adicionar ao Carrinho</button>
        </div>

        <div class="product">
            <img src="bikini2.jpg" alt="Biquíni de Crochê Rosa">
            <h3>Biquíni Rosa Pôr do Sol</h3>
            <p>R$170,00</p>
            <button>Adicionar ao Carrinho</button>
        </div>

        <div class="product">
            <img src="bikini3.jpg" alt="Biquíni de Crochê Verde">
            <h3>Biquíni Verde Mar</h3>
            <p>R$160,00</p>
            <button>Adicionar ao Carrinho</button>
        </div>
    </section>

    <section id="sobre" class="container">
        <h2>Sobre Nós</h2>
        <p>
            Cada biquíni é feito com carinho e dedicação, utilizando materiais de alta qualidade para proporcionar conforto e estilo. Inspirados pela beleza do mar e pelo calor do sol, nossos designs são pensados para realçar sua elegância natural.
        </p>
    </section>

    <section id="contato" class="container">
        <h2>Contato</h2>
        <form>
            <label for="name">Nome:</label><br>
            <input type="text" id="name" name="name" required><br><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br><br>
            <label for="message">Mensagem:</label><br>
            <textarea id="message" name="message" rows="4" required></textarea><br><br>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Biquínis de Crochê. Todos os direitos reservados.</p>
    </footer>

</body>
</html>
![08EFD61D-B923-449A-B0E9-D9F00A863B1E](https://github.com/user-attachments/assets/66a300e6-846b-470b-9c40-92face54c1d4)
