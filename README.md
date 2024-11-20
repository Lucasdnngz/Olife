<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>oLife - Productos Naturales</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #4CAF50;
        }
        .hero {
            text-align: center;
            padding: 50px 20px;
            background-image: url('https://via.placeholder.com/1500x500');
            background-size: cover;
            color: white;
        }
        .container {
            padding: 20px;
        }
        .product {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .product-item {
            background: white;
            border: 1px solid #ddd;
            border-radius: 10px;
            width: 300px;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .product-item img {
            max-width: 100%;
            border-radius: 10px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenido a oLife</h1>
        <p>Productos Naturales para tu Bienestar</p>
    </header>
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#productos">Productos</a>
        <a href="#nosotros">Nosotros</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <section class="hero" id="inicio">
        <h2>Descubre el poder de lo natural</h2>
        <p>Transforma tu vida con nuestros productos 100% naturales.</p>
    </section>
    <section class="container" id="productos">
        <h2>Nuestros Productos</h2>
        <div class="product">
            <div class="product-item">
                <img src="https://via.placeholder.com/300" alt="Producto 1">
                <h3>Té Orgánico</h3>
                <p>Mejora tu digestión y relájate con nuestro té orgánico.</p>
                <p><strong>$15.00</strong></p>
                <button>Comprar Ahora</button>
            </div>
            <div class="product-item">
                <img src="https://via.placeholder.com/300" alt="Producto 2">
                <h3>Jabón Natural</h3>
                <p>Cuida tu piel con nuestros jabones hechos a mano.</p>
                <p><strong>$8.00</strong></p>
                <button>Comprar Ahora</button>
            </div>
            <div class="product-item">
                <img src="https://via.placeholder.com/300" alt="Producto 3">
                <h3>Aceites Esenciales</h3>
                <p>Encuentra la paz interior con nuestros aceites esenciales.</p>
                <p><strong>$20.00</strong></p>
                <button>Comprar Ahora</button>
            </div>
        </div>
    </section>
    <section class="container" id="nosotros">
        <h2>Sobre Nosotros</h2>
        <p>En oLife, creemos en el poder de la naturaleza para mejorar tu vida. Nuestros productos están hechos con ingredientes naturales, sostenibles y libres de químicos.</p>
    </section>
    <section class="container" id="contacto">
        <h2>Contacto</h2>
        <p>¿Tienes preguntas? Contáctanos en:</p>
        <p>Email: contacto@olife.com</p>
        <p>Teléfono: +123 456 7890</p>
    </section>
    <footer>
        <p>&copy; 2024 oLife. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
