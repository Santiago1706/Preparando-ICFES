<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pre-ICFES Profesional</title>
    <style>
        /* Estilos generales */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f3f9fe;
            color: #333;
        }

        header {
            background-color: #0056b3;
            color: white;
            padding: 30px 0;
            text-align: center;
        }

        header h1 {
            font-size: 2.8rem;
            margin: 0;
        }

        /* Menú de navegación */
        nav {
            background-color: #003f8a;
            padding: 15px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        nav ul li {
            display: inline-block;
            margin-right: 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 1.2rem;
            padding: 8px 20px;
            border-radius: 4px;
            transition: background-color 0.3s ease;
        }

        nav ul li a:hover {
            background-color: #0056b3;
        }

        /* Sección principal */
        .main-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 100px 50px 50px;
        }

        .main-content .text-section {
            width: 50%;
        }

        .main-content .text-section h2 {
            color: #003f8a;
            font-size: 2.5rem;
        }

        .main-content .text-section p {
            font-size: 1.2rem;
            line-height: 1.6;
        }

        .main-content .text-section button {
            background-color: #007acc;
            color: white;
            border: none;
            padding: 12px 20px;
            font-size: 1rem;
            border-radius: 5px;
            margin-top: 10px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .main-content .text-section button:hover {
            background-color: #005f99;
        }

        .main-content img {
            max-width: 40%;
            height: auto;
        }

        /* Sección beneficios */
        .benefits-section {
            padding: 50px;
            background-color: #f0f8ff;
        }

        .benefits-section h2 {
            text-align: center;
            color: #0056b3;
            margin-bottom: 30px;
        }

        .benefits-section .benefits {
            display: flex;
            justify-content: space-between;
        }

        .benefits-section .benefit {
            width: 30%;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .benefits-section .benefit h3 {
            color: #003f8a;
            margin-bottom: 10px;
        }

        .benefits-section .benefit p {
            font-size: 1.1rem;
        }

        /* Sección equipo docente */
        .team-section {
            padding: 50px;
            background-color: #ffffff;
        }

        .team-section h2 {
            text-align: center;
            color: #0056b3;
            margin-bottom: 30px;
        }

        .team-section .team {
            display: flex;
            justify-content: space-around;
        }

        .team-section .team-member {
            width: 30%;
            text-align: center;
        }

        .team-section .team-member img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
        }

        .team-section .team-member h3 {
            color: #003f8a;
            margin-top: 15px;
        }

        .team-section .team-member p {
            font-size: 1rem;
        }

        /* Sección preguntas frecuentes */
        .faq-section {
            padding: 50px;
            background-color: #f0f8ff;
        }

        .faq-section h2 {
            text-align: center;
            color: #0056b3;
            margin-bottom: 30px;
        }

        .faq-section .faq {
            margin-bottom: 20px;
        }

        .faq-section .faq h3 {
            color: #003f8a;
            font-size: 1.3rem;
        }

        .faq-section .faq p {
            font-size: 1.1rem;
        }

        /* Botones sociales */
        .social-icons {
            margin-top: 50px;
            text-align: center;
        }

        .social-icons a {
            margin: 0 10px;
            display: inline-block;
        }

        .social-icons img {
            width: 40px;
            height: auto;
        }

        /* Sección contacto */
        footer {
            background-color: #003f8a;
            color: white;
            padding: 40px;
            text-align: center;
        }

        footer p {
            font-size: 1.2rem;
            margin: 10px 0;
        }

        footer a {
            color: #f0f8ff;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        /* Responsivo */
        @media (max-width: 768px) {
            .main-content {
                flex-direction: column;
                padding: 150px 20px 50px;
            }

            .main-content .text-section, .main-content img {
                width: 100%;
                text-align: center;
            }

            .benefits-section .benefits, .team-section .team {
                flex-direction: column;
                align-items: center;
            }

            .benefits-section .benefit, .team-section .team-member {
                width: 100%;
                margin-bottom: 20px;
            }
        }
    </style>
</head>
<body>

    <!-- Encabezado -->
    <header>
        <h1>Pre-ICFES Profesional</h1>
    </header>

    <!-- Menú de Navegación -->
    <nav>
        <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#beneficios">Beneficios</a></li>
            <li><a href="#equipo">Equipo Docente</a></li>
            <li><a href="#faq">Preguntas Frecuentes</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>

    <!-- Sección Principal -->
    <section class="main-content" id="inicio">
        <div class="text-section">
            <h2>¡Prepárate para el ICFES con los mejores!</h2>
            <p>En nuestro Pre-ICFES, te ofrecemos la mejor preparación con clases personalizadas, simulacros reales y el acompañamiento de expertos en cada área. Maximiza tus resultados y abre las puertas a las mejores universidades.</p>
            <button onclick="location.href='#inscripcion'">¡Inscríbete Ahora!</button>
        </div>
        <img src="https://example.com/icfes-image.jpg" alt="Estudiante Pre-ICFES">
    </section>

    <!-- Sección Beneficios -->
    <section class="benefits-section" id="beneficios">
        <h2>Nuestros Beneficios</h2>
        <div class="benefits">
            <div class="benefit">
                <h3>Simulacros Reales</h3>
                <p>Familiarízate con el formato del ICFES con simulacros completos y resultados detallados.</p>
            </div>
            <div class="benefit">
                <h3>Clases Dinámicas</h3>
                <p>Nuestras clases interactivas y dinámicas te ayudarán a mantenerte motivado y concentrado.</p>
            </div>
            <div class="benefit">
                <h3>Asesoría Personalizada</h3>
                <p>Identificamos tus áreas de mejora y te brindamos el acompañamiento necesario para superarlas.</p>
            </div>
        </div>
    </section>

    <!-- Sección Equipo Docente -->
    <section class="team-section" id="equipo">
        <h2>Conoce a nuestro equipo</h2>
        <div class="team">
            <div class="team-member">
                <img src="https://example.com/teacher1.jpg" alt="Docente 1">
                <h3>Prof. Andrea Torres</h3>
                <p>Experta en matemáticas y razonamiento cuantitativo.</p>
            </div>
            <div class="team-member">
                <img src="https://example.com/teacher2.jpg" alt="Docente 2">
                <h3>Prof. Carlos Gómez</h3>
                <p>Especialista en ciencias naturales y ciencias sociales.</p>
            </div>
            <div class="team-member">
                <img src="https://example.com/teacher3.jpg" alt="Docente 3">
                <h3>Prof. Laura Pérez</h3>
                <p>Asesora en lectura crítica y competencias ciudadanas.</p>
            </div>
        </div>
    </section>

    <!-- Sección Preguntas Frecuentes -->
    <section class="faq-section" id="faq">
        <h2>Preguntas Frecuentes</h2>
        <div class="faq">
            <h3>¿Cuántas veces puedo realizar simulacros?</h3>
            <p>Puedes realizar simulacros cada semana, con retroalimentación personalizada.</p>
        </div>
        <div class="faq">
            <h3>¿El curso incluye material adicional?</h3>
            <p>Sí, te proporcionamos guías, libros digitales y ejercicios complementarios para reforzar tu aprendizaje.</p>
        </div>
    </section>

    <!-- Iconos de redes sociales -->
    <div class="social-icons">
        <a href="#"><img src="https://example.com/facebook-icon.png" alt="Facebook"></a>
        <a href="#"><img src="https://example.com/twitter-icon.png" alt="Twitter"></a>
        <a href="#"><img src="https://example.com/instagram-icon.png" alt="Instagram"></a>
    </div>

    <!-- Pie de página -->
    <footer id="contacto">
        <p>&copy; 2024 Pre-ICFES Profesional. Todos los derechos reservados.</p>
        <p><a href="mailto:contacto@preicfesprofesional.com">contacto@preicfesprofesional.com</a> | Tel: (123) 456-7890</p>
    </footer>

</body>
</html>
