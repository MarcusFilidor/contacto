<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contacto - Catálogo en Línea</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: white;
            color: #333;
        }
        header {
            background-color: #F4D03F; /* amarillo */
            color: #000;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            background-color: #333; /* gris oscuro */
            overflow: hidden;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            display: inline-block;
            text-align: center;
        }
        nav a:hover {
            background-color: #F4D03F; /* amarillo */
            color: black;
        }
        .contact-form {
            padding: 20px;
            max-width: 600px;
            margin: 20px auto;
            background-color: #f9f9f9;
            border: 1px solid #ddd;
            border-radius: 8px;
        }
        .contact-form h2 {
            color: #F4D03F; /* amarillo */
            text-align: center;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .contact-form input[type="submit"] {
            background-color: #F4D03F; /* amarillo */
            color: black;
            cursor: pointer;
            border: none;
        }
        .contact-form input[type="submit"]:hover {
            background-color: #333; /* gris oscuro */
            color: white;
        }
        footer {
            background-color: #333; /* gris oscuro */
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Catálogo en Línea - Contacto</h1>
    </header>

    <nav>
        <a href="#">Inicio</a>
        <a href="#">Catálogo</a>
        <a href="#">Ofertas</a>
        <a href="#">Recetas Saludables</a>
        <a href="contacto.html">Contacto</a> <!-- Enlace a la página de contacto -->
    </nav>

    <div class="contact-form">
        <h2>Contáctanos</h2>
        <form action="mailto:contacto@ejemplo.com" method="POST" enctype="text/plain">
            <label for="name">Nombre:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Correo Electrónico:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Mensaje:</label>
            <textarea id="message" name="message" rows="6" required></textarea>

            <input type="submit" value="Enviar Mensaje">
        </form>
    </div>

    <footer>
        <p>&copy; 2024 Catálogo de Frutas y Verduras. Todos los derechos reservados.</p>
    </footer>

</body>
</html>
