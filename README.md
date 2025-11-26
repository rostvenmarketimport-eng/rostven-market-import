# rostven-market-import
pagina web de rostven market import  para servicios de importacion
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rostven Market Imports</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #f5f5f5;
            color: #222;
        }
        header {
            background: #1a1a1a;
            color: #fff;
            padding: 40px;
            text-align: center;
        }
        nav {
            background: #e63946;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .section {
            max-width: 1100px;
            margin: auto;
            padding: 40px 20px;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .product-card {
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
            text-align: center;
        }
        .product-card img {
            width: 100%;
            border-radius: 10px;
        }
        footer {
            background: #1a1a1a;
            color: #fff;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
        .btn {
            background: #e63946;
            color: #fff;
            padding: 10px 20px;
            border: none;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            margin-top: 10px;
        }
    </style>
</head>
<body>

<header>
    <h1>Rostven Market Imports</h1>
    <p>Importamos calidad, entregamos confianza.</p>
</header>

<nav>
    <a href="#inicio">Inicio</a>
    <a href="#productos">Productos</a>
    <a href="#nosotros">Nosotros</a>
    <a href="#contacto">Contacto</a>
</nav>

<section id="inicio" class="section">
    <h2>Productos 100% Seguros y Verificados</h2>
    <p>En Rostven Market Imports trabajamos con proveedores certificados alrededor del mundo 
    para garantizar que cada producto es auténtico, seguro y de la más alta calidad.</p>
</section>

<section id="productos" class="section">
    <h2>Nuestros Productos</h2>
    <div class="products">

        <div class="product-card">
            <img src="tu-imagen-1.jpg" alt="Producto 1">
            <h3>Producto 1</h3>
            <p>Descripción corta del producto.</p>
            <a class="btn" href="#">Comprar</a>
        </div>

        <div class="product-card">
            <img src="tu-imagen-2.jpg" alt="Producto 2">
            <h3>Producto 2</h3>
            <p>Descripción corta del producto.</p>
            <a class="btn" href="#">Comprar</a>
        </div>

        <div class="product-card">
            <img src="tu-imagen-3.jpg" alt="Producto 3">
            <h3>Producto 3</h3>
            <p>Descripción corta del producto.</p>
            <a class="btn" href="#">Comprar</a>
        </div>

    </div>
</section>

<section id="nosotros" class="section">
    <h2>Sobre Nosotros</h2>
    <p>Somos Rostven Market Imports, una empresa dedicada a la importación de productos internacionales
    100% seguros, originales y verificados. Nuestro compromiso es ofrecerte confianza, calidad y un servicio excepcional.</p>
</section>

<section id="contacto" class="section">
    <h2>Contacto</h2>
    <p>📞 Teléfono: +00 0000 0000</p>
    <p>📧 Email: contacto@rostvenimports.com</p>
    <p>📍 Ubicación: Tu ciudad, País</p>
</section>

<footer>
    © 2025 Rostven Market Imports - Todos los derechos reservados.
</footer>

</body>
</html>
