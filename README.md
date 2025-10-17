<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bread and Pastry Product</title>
    <style>
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            background: #f9f4ef;
            margin: 0;
            padding: 0;
        }
        header {
            background: #d2b48c;
            color: #fff;
            padding: 2rem 0 1rem 0;
            text-align: center;
        }
        .logo {
            width: 100px;
            height: 100px;
            margin: 0 auto 1rem auto;
            display: block;
        }
        h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        .description {
            font-size: 1.2rem;
            color: #6b4f2a;
            margin-bottom: 2rem;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }
        main {
            max-width: 800px;
            margin: 2rem auto;
            background: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.07);
            padding: 2rem;
        }
        .products {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 2rem;
        }
        .product {
            background: #f4e3d7;
            border-radius: 8px;
            padding: 1.5rem;
            box-shadow: 0 2px 8px rgba(0,0,0,0.04);
            text-align: center;
        }
        .product h2 {
            margin-top: 0;
            font-size: 1.3rem;
            color: #8b5c2b;
        }
        .product p {
            color: #5e4632;
            font-size: 1rem;
        }
        @media (max-width: 600px) {
            .products {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <!-- Simple bread logo using SVG -->
        <svg class="logo" viewBox="0 0 100 100">
            <ellipse cx="50" cy="60" rx="40" ry="25" fill="#fff7e6" stroke="#a67c52" stroke-width="4"/>
            <ellipse cx="50" cy="45" rx="30" ry="20" fill="#eac086" stroke="#a67c52" stroke-width="2"/>
            <ellipse cx="50" cy="40" rx="15" ry="8" fill="#d2b48c" />
        </svg>
        <h1>Bread and Pastry Product</h1>
        <div class="description">
            Welcome to Bread and Pastry Product! We bring you a delightful selection of baked goods made from the finest ingredients, crafted with passion and care. Whether you’re craving a sweet treat or a classic roll, our bakery has something for everyone.
        </div>
    </header>
    <main>
        <div class="products">
            <div class="product">
                <h2>Cinnamon Roll</h2>
                <p>Soft, fluffy rolls swirled with cinnamon sugar and topped with creamy glaze. Perfect for breakfast or an indulgent snack.</p>
            </div>
            <div class="product">
                <h2>Brownies</h2>
                <p>Rich and fudgy chocolate brownies with a crackly top. Satisfy your chocolate cravings with every bite.</p>
            </div>
            <div class="product">
                <h2>Dinner Roll</h2>
                <p>Classic, buttery dinner rolls that are light and airy. Ideal for accompanying any meal or enjoying on their own.</p>
            </div>
            <div class="product">
                <h2>Bento Cake</h2>
                <p>Adorable mini cakes packed in bento boxes, perfect for gifting or enjoying solo. Customizable flavors and cute designs.</p>
            </div>
            <div class="product">
                <h2>Swiss Roll</h2>
                <p>Delicate cake rolled with sweet cream filling. A timeless pastry that’s both elegant and delicious.</p>
            </div>
        </div> 
    </main>
</body>
</html>
