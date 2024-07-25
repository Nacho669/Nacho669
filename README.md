<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TennisProAdvice</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bienvenidos a TennisProAdvice</h1>
        <p>Consejos de los mejores jugadores de tenis para mejorar tu juego.</p>
        <img src="imagen-principal.jpg" alt="Jugador de tenis en acción">
    </header>

    <nav>
        <ul>
            <li><a href="#home">Inicio</a></li>
            <li><a href="#about">Nosotros</a></li>
            <li><a href="#tips">Consejos y Trucos</a></li>
            <li><a href="#gallery">Galería</a></li>
            <li><a href="#contact">Contacto</a></li>
        </ul>
    </nav>

    <section id="home">
        <h2>Consejos Destacados</h2>
        <article>
            <h3>Mejora tu saque</h3>
            <p>Consejos de Roger Federer para perfeccionar tu saque.</p>
            <img src="federer-saque.jpg" alt="Roger Federer">
        </article>
        <article>
            <h3>Estrategias de juego</h3>
            <p>Tácticas de Rafael Nadal para dominar el partido.</p>
            <img src="nadal-estrategia.jpg" alt="Rafael Nadal">
        </article>
    </section>

    <section id="about">
        <h2>Nosotros</h2>
        <p>En TennisProAdvice, nuestra misión es ayudarte a mejorar tu juego con consejos de los mejores jugadores de tenis del mundo.</p>
        <h3>Equipo</h3>
        <p>Conoce a nuestros expertos en tenis.</p>
    </section>

    <section id="tips">
        <h2>Consejos y Trucos</h2>
        <article>
            <h3>Para Principiantes</h3>
            <p>Consejos básicos para quienes se inician en el tenis.</p>
        </article>
        <article>
            <h3>Intermedios</h3>
            <p>Técnicas avanzadas para jugadores de nivel medio.</p>
        </article>
        <article>
            <h3>Avanzados</h3>
            <p>Estrategias y ejercicios para jugadores avanzados.</p>
        </article>
    </section>

    <section id="gallery">
        <h2>Galería</h2>
        <img src="imagen1.jpg" alt="Imagen de tenis 1">
        <img src="imagen2.jpg" alt="Imagen de tenis 2">
        <img src="imagen3.jpg" alt="Imagen de tenis 3">
        <video controls>
            <source src="video1.mp4" type="video/mp4">
            Tu navegador no soporta el elemento de video.
        </video>
    </section>

    <section id="contact">
        <h2>Contacto</h2>
        <form action="enviar.php" method="post">
            <label for="name">Nombre:</label>
            <input type="text" id="name" name="name">
            <label for="email">Correo Electrónico:</label>
            <input type="email" id="email" name="email">
            <label for="message">Mensaje:</label>
            <textarea id="message" name="message"></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 TennisProAdvice. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
