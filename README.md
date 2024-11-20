<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Bienvenido a oLife, tu tienda de productos naturales y orgánicos para el bienestar y la salud. Descubre nuestro catálogo hoy.">
    <title>oLife - Productos Naturales y Orgánicos</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
    <style>
        /* Estilos generales */
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f8f7;
            color: #333;
            line-height: 1.6;
        }
        header {
            background: linear-gradient(45deg, #4CAF50, #2E7D32);
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            font-size: 2.5rem;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #2E7D32;
        }
        nav a {
            color: white;
            padding: 15px 20px;
            text-decoration: none;
            text-transform: uppercase;
            font-weight: bold;
        }
        nav a:hover {
            background-color: #388E3C;
        }
        .hero {
            background-image: url('https://via.placeholder.com/1600x500');
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            padding: 80px 20px;
        }
        .hero h2 {
            font-size: 2.5rem;
            margin: 0 0 10px;
        }
        .hero p {
            font-size: 1.2rem;
            margin: 0;
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 20px auto;
        }
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .product-item {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .product-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
        }
        .product-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .product-item h3 {
            font-size: 1.5rem;
            margin: 10px 0;
        }
        .product-item p {
            font-size: 1rem;
            margin: 0 0 10px;
        }
        .product-item button {
            background: #4CAF50;
            color: white;
            border: none;
            padding: 10px 15px;
            margin: 10px 0;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s ease;
        }
        .product-item button:hover {
            background: #388E3C;
        }
        footer {
            background: #2E7D32;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
        footer a {
            color: #A5D6A7;
            text-decoration: none;
        }
        footer a:hover {
            color: #C8E6C9;
        }
        /* Responsivo */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }
            .hero h2 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>oLife</h1>
        <p>Productos Naturales para un Estilo de Vida Saludable</p>
    </header>
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#productos">Productos</a>
        <a href="#nosotros">Nosotros</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <section class="hero" id="inicio">
        <h2>Descubre el Poder de la Naturaleza</h2>
        <p>Mejora tu bienestar con productos orgánicos y sostenibles.</p>
    </section>
    <section class="container" id="productos">
        <h2>Nuestros Productos</h2>
        <div class="product-grid">
            <div class="product-item">
                <img src="https://via.placeholder.com/300" alt="Té Orgánico">
                <h3>Té Orgánico</h3>
                <p>Relájate con nuestro té 100% natural.</p>
                <p><strong>$15.00</strong></p>
                <button>Comprar Ahora</button>
            </div>
            <div class="product-item">
                <img src="https://via.placeholder.com/300" alt="Jabón Natural">
                <h3>Jabón Natural</h3>
                <p>Cuidado delicado para tu piel.</p>
                <p><strong>$8.00</strong></p>
                <button>Comprar Ahora</button>
            </div>
            <div class="product-item">
                <img src="https://via.placeholder.com/300" alt="Aceites Esenciales">
                <h3>Aceites Esenciales</h3>
                <p>Aromaterapia para la mente y el cuerpo.</p>
                <p><strong>$20.00</strong></p>
                <button>Comprar Ahora</button>
            </div>
        </div>
    </section>
    <section class="container" id="nosotros">
        <h2>Sobre Nosotros</h2>
        <p>En oLife creemos en lo natural. Todos nuestros productos están diseñados para mejorar tu bienestar de forma sostenible y respetuosa con el medio ambiente.</p>
    </section>
    <section class="container" id="contacto">
        <h2>Contacto</h2>
        <p>¿Tienes preguntas o comentarios? Contáctanos:</p>
        <p><i class="fa fa-envelope"></i> contacto@olife.com</p>
        <p><i class="fa fa-phone"></i> +123 456 7890</p>
    </section>
    <footer>
        <p>&copy; 2024 oLife. Todos los derechos reservados.</p>
        <p>Siguenos en <a href="#">Instagram</a>, <a href="#">Facebook</a>, y <a href="#">Twitter</a>.</p>
    </footer>
</body>
</html>
