<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tu Nombre - Analista y Desarrollador de Sistemas</title>
    <style>
        /* Estilos CSS */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 20px;
            font-size: 18px;
        }
        .banner {
            background-image: url('tu-imagen-de-banner.jpg');
            background-size: cover;
            height: 400px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #fff;
            text-align: center;
        }
        .banner h1 {
            font-size: 36px;
            margin-bottom: 20px;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            padding: 20px;
        }
        section {
            margin-bottom: 40px;
        }
        .services {
            background-color: #f4f4f4;
            padding: 40px 20px;
            text-align: center;
        }
        .services h2 {
            margin-bottom: 20px;
        }
        .services p {
            font-size: 18px;
            line-height: 1.6;
        }
        .contact {
            background-color: #333;
            color: #fff;
            padding: 40px 20px;
            text-align: center;
        }
        .contact h2 {
            margin-bottom: 20px;
        }
        .contact form {
            max-width: 600px;
            margin: auto;
        }
        .contact input[type="text"],
        .contact input[type="email"],
        .contact textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: none;
            border-radius: 5px;
        }
        .contact input[type="submit"] {
            background-color: #4caf50;
            color: #fff;
            border: none;
            padding: 15px 20px;
            cursor: pointer;
            border-radius: 5px;
        }
        .contact input[type="submit"]:hover {
            background-color: #45a049;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Tu Nombre</h1>
        <nav>
            <a href="#services">Servicios</a>
            <a href="#experience">Experiencia</a>
            <a href="#contact">Contacto</a>
        </nav>
    </header>
    <div class="banner">
        <h1>Analista y Desarrollador de Sistemas</h1>
    </div>
    <div class="container">
        <section id="services" class="services">
            <h2>Servicios</h2>
            <p>Ofrezco servicios de calidad en el campo de la analítica y desarrollo de sistemas de información. Mis servicios incluyen:</p>
            <ul>
                <li>Análisis de requerimientos</li>
                <li>Diseño y desarrollo de sistemas</li>
                <li>Gestión de proyectos de software</li>
                <li>Control de calidad y pruebas</li>
            </ul>
        </section>
        <section id="experience" class="experience">
            <h2>Experiencia</h2>
            <p>Tengo experiencia en el diseño, desarrollo e implementación de sistemas de información en diversos sectores industriales. Mis habilidades incluyen:</p>
            <ul>
                <li>Análisis de sistemas</li>
                <li>Desarrollo de aplicaciones web y móviles</li>
                <li>Administración de bases de datos</li>
                <li>Gestión de proyectos utilizando metodologías ágiles</li>
            </ul>
        </section>
        <section id="contact" class="contact">
            <h2>Contacto</h2>
            <form action="#" method="post">
                <input type="text" name="name" placeholder="Nombre" required><br>
                <input type="email" name="email" placeholder="Correo electrónico" required><br>
                <textarea name="message" placeholder="Mensaje" rows="4" required></textarea><br>
                <input type="submit" value="Enviar">
            </form>
        </section>
    </div>
    <footer>
        <p>Derechos Reservados &copy; 2024 | Tu Nombre</p>
    </footer>
</body>
</html>
