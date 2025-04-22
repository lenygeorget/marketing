<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nos Vêtements - Prototype</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; background: #f5f5f5; }
        header {
            background-color: #222;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            padding: 30px;
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        .product {
            background: white;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
            text-align: center;
        }
        .product img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 8px;
        }
        .product h3 {
            margin: 10px 0 5px;
        }
        .product p {
            color: #555;
            margin: 0;
        }
        a.retour {
            display: block;
            margin: 20px auto;
            text-align: center;
            color: #ff4081;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h2>Prototype</h2>
    </header>
    <div class="container">
        <h1>Vêtements de sport</h1>
        <div class="products">
            <div class="product">
                <img src="https://images.unsplash.com/photo-1618354691267-745b3b9c60f9?auto=format&fit=crop&w=800&q=80" alt="T-shirt sport">
                <h3>T-shirt respirant</h3>
                <p>29,90 €</p>
            </div>
            <div class="product">
                <img src="https://images.unsplash.com/photo-1584467735871-3efed205bce4?auto=format&fit=crop&w=800&q=80" alt="Legging sport">
                <h3>Legging performance</h3>
                <p>39,90 €</p>
            </div>
            <div class="product">
                <img src="https://images.unsplash.com/photo-1600181958240-5c473ec167e7?auto=format&fit=crop&w=800&q=80" alt="Veste sport">
                <h3>Veste zippée</h3>
                <p>59,90 €</p>
            </div>
            <div class="product">
                <img src="https://images.unsplash.com/photo-1618358739283-24423f8b470f?auto=format&fit=crop&w=800&q=80" alt="Short sport">
                <h3>Short training</h3>
                <p>24,90 €</p>
            </div>
            <div class="product">
                <img src="https://images.unsplash.com/photo-1598977088703-bb9c76a5bcd6?auto=format&fit=crop&w=800&q=80" alt="Chaussures running">
                <h3>Chaussures running</h3>
                <p>89,90 €</p>
            </div>
        </div>
        <a class="retour" href="index.html">← Retour à l'accueil</a>
    </div>
</body>
</html>
