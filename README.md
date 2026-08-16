<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Underground Pratas 925</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #0f0f11;
            color: #f1f1f1;
            padding-bottom: 80px;
        }

        header {
            background-color: #18181c;
            padding: 20px 15px;
            text-align: center;
            border-bottom: 2px solid #333;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        header h1 {
            color: #fff;
            font-size: 1.5rem;
            letter-spacing: 2px;
            text-transform: uppercase;
        }

        header p {
            color: #aaa;
            font-size: 0.85rem;
            margin-top: 4px;
        }

        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 10px;
        }

        .catalog-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 12px;
        }

        @media (min-width: 768px) {
            .catalog-grid {
                grid-template-columns: repeat(4, 1fr);
                gap: 20px;
            }
        }

        .product-card {
            background: #1c1c21;
            border-radius: 10px;
            overflow: hidden;
            border: 1px solid #2a2a32;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }

        .img-container {
            position: relative;
            width: 100%;
            padding-top: 100%; /* ProporÃ§Ã£o 1:1 */
            background-color: #25252b;
        }

        .img-container img {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .badge-prata {
            position: absolute;
            top: 8px;
            left: 8px;
            background: rgba(0, 0, 0, 0.75);
            color: #e0e0e0;
            font-size: 0.65rem;
            padding: 3px 6px;
            border-radius: 4px;
            border: 1px solid #555;
            z-index: 2;
        }

        .info {
            padding: 12px 10px;
            display: flex;
            flex-direction: column;
            gap: 8px;
            flex-grow: 1;
        }

        .product-title {
            font-size: 0.85rem;
            color: #ddd;
            font-weight: 500;
            line-height: 1.2;
            height: 2.4em;
            overflow: hidden;
            display: -webkit-box;
            -webkit-line-clamp: 2;
            -webkit-box-orient: vertical;
        }

        .product-price {
            font-size: 1.05rem;
            font-weight: bold;
            color: #25D366;
        }

        .btn-cart {
            background: #2b2b36;
            color: #fff;
            border: none;
            padding: 8px;
            border-radius: 5px;
            font-size: 0.75rem;
            font-weight: bold;
            cursor: pointer;
            width: 100%;
        }

        .btn-whatsapp {
            background: #25D366;
            color: #fff;
            text-decoration: none;
            text-align: center;
            padding: 8px;
            border-radius: 5px;
            font-size: 0.75rem;
            font-weight: bold;
            display: block;
        }

        /* Floating Cart Notification */
        .cart-bar {
            position: fixed;
            bottom: 0;
            left: 0;
            right: 0;
            background: #18181c;
            border-top: 1px solid #333;
            padding: 12px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            z-index: 1000;
        }

        .cart-btn-send {
            background: #25D366;
            color: #fff;
            border: none;
            padding: 10px 16px;
            border-radius: 20px;
            font-weight: bold;
            font-size: 0.85rem;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <header>
        <h1>Underground Pratas</h1>
        <p>Prata 925 LegÃ­tima</p>
    </header>

    <div class="container">
        <div class="catalog-grid">

            <!-- Item 155 - Argola Fio Quadrado 1,5 mm -->
            <div class="product-card">
                <div class="img-container">
                    <span class="badge-prata">Prata 925 LegÃ­tima</span>
                    <img src="https://img1.conectavenda.com.br/cristiano_rafael_vendramini_/413/50e3d37d-52d5-46cc-9f08-8ba5cbc4383f.webp" alt="Argola Fio Quadrado 1,5 mm">
                </div>
                <div class="info">
                    <div class="product-title">Argola Fio Quadrado 1,5 mm</div>
                    <div class="product-price">R$ 60,00</div>
                    <button class="btn-cart" onclick="addCart('Argola Fio Quadrado 1,5 mm', 60.00)">+ Adicionar ao Carrinho</button>
                    <a href="https://wa.me/5561981642480?text=OlÃ¡!%20Gostaria%20de%20consultar%20a%20disponibilidade/tamanho%20da%20Argola%20Fio%20Quadrado%201,5%20mm" class="btn-whatsapp" target="_blank">Consultar Tamanhos</a>
                </div>
            </div>

            <!-- Item 156 - Argola CoraÃ§Ã£o Fio Chanfrado 1,5cm 2mm -->
            <div class="product-card">
                <div class="img-container">
                    <span class="badge-prata">Prata 925 LegÃ­tima</span>
                    <img src="https://img1.conectavenda.com.br/cristiano_rafael_vendramini_/413/a6575ac2-8b45-402f-b697-2ef4dec35ae2.webp" alt="Argola CoraÃ§Ã£o Fio Chanfrado 1,5cm 2mm">
                </div>
                <div class="info">
                    <div class="product-title">Argola CoraÃ§Ã£o Fio Chanfrado 1,5cm 2mm</div>
                    <div class="product-price">R$ 65,00</div>
                    <button class="btn-cart" onclick="addCart('Argola CoraÃ§Ã£o Fio Chanfrado 1,5cm 2mm', 65.00)">+ Adicionar ao Carrinho</button>
                    <a href="https://wa.me/5561981642480?text=OlÃ¡!%20Gostaria%20de%20consultar%20a%20disponibilidade/tamanho%20da%20Argola%20CoraÃ§Ã£o%20Fio%20Chanfrado%201,5cm%202mm" class="btn-whatsapp" target="_blank">Consultar Tamanhos</a>
                </div>
            </div>

        </div>
    </div>

    <!-- Barra do Carrinho -->
    <div class="cart-bar">
        <div>
            <span>Itens no carrinho: <strong id="cart-count">0</strong></span>
        </div>
        <button class="cart-btn-send" onclick="sendOrder()">Finalizar Pedido no WhatsApp</button>
    </div>

    <script>
        let cart = [];

        function addCart(nome, preco) {
            cart.push({ nome, preco });
            document.getElementById('cart-count').innerText = cart.length;
            alert(nome + ' adicionado ao carrinho!');
        }

        function sendOrder() {
            if (cart.length === 0) {
                alert('Seu carrinho estÃ¡ vazio!');
                return;
            }
            let texto = 'OlÃ¡! Gostaria de fazer o pedido dos seguintes itens:\n\n';
            let total = 0;
            cart.forEach((item, index) => {
                texto += `${index + 1}. ${item.nome} - R$ ${item.preco.toFixed(2)}\n`;
                total += item.preco;
            });
            texto += `\n*Total: R$ ${total.toFixed(2)}*`;
            
            let url = `https://wa.me/5561981642480?text=${encodeURIComponent(texto)}`;
            window.open(url, '_blank');
        }
    </script>
</body>
</html>
