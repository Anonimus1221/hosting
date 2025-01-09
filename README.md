<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Conoce a Magist</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to right, #4e54c8, #8f94fb);
            color: white;
            text-align: center;
            overflow-x: hidden;
        }
        header {
            padding: 20px;
            background: rgba(0, 0, 0, 0.5);
            animation: fadeInDown 1.5s ease;
        }
        header h1 {
            margin: 0;
            font-size: 3em;
            background: linear-gradient(to right, #ff8c00, #ff0080);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            text-fill-color: transparent;
            animation: textGlow 3s infinite;
        }
        header p {
            font-size: 1.2em;
            margin-top: 10px;
            opacity: 0.8;
        }
        main {
            padding: 40px 20px;
            animation: fadeInUp 1.5s ease;
        }
        section {
            margin: 20px auto;
            max-width: 800px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            padding: 20px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
            transform: scale(0.9);
            transition: transform 0.3s ease;
        }
        section:hover {
            transform: scale(1);
        }
        section h2 {
            font-size: 2.5em;
            margin-bottom: 15px;
            animation: slideInLeft 1s ease;
        }
        section p {
            font-size: 1.2em;
            line-height: 1.8;
            animation: slideInRight 1s ease;
        }
        footer {
            padding: 10px;
            background: rgba(0, 0, 0, 0.7);
            position: fixed;
            bottom: 0;
            width: 100%;
            text-align: center;
        }
        footer p {
            margin: 0;
            font-size: 0.9em;
        }
        .btn {
            display: inline-block;
            margin: 20px auto;
            padding: 12px 30px;
            background: #ffffff;
            color: #2575fc;
            font-size: 1.2em;
            border: none;
            border-radius: 25px;
            text-decoration: none;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        .btn:hover {
            background: #ff8c00;
            color: white;
            transform: translateY(-5px);
        }

        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes slideInLeft {
            from {
                opacity: 0;
                transform: translateX(-50px);
            }
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        @keyframes slideInRight {
            from {
                opacity: 0;
                transform: translateX(50px);
            }
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        @keyframes textGlow {
            0% {
                text-shadow: 0 0 5px #ff8c00, 0 0 10px #ff0080, 0 0 20px #ff0080;
            }
            50% {
                text-shadow: 0 0 20px #ff8c00, 0 0 30px #ff0080, 0 0 40px #ff0080;
            }
            100% {
                text-shadow: 0 0 5px #ff8c00, 0 0 10px #ff0080, 0 0 20px #ff0080;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenido a Magist</h1>
        <p>Una inteligencia artificial diseñada para potenciar tus ideas</p>
    </header>
    <main>
        <section>
            <h2>¿Qué es Magist?</h2>
            <p>Magist es una innovadora inteligencia artificial creada para ayudarte en diversas tareas, desde programación hasta resolución de problemas complejos. Diseñada con tecnología avanzada, Magist se adapta a tus necesidades y aprende contigo.</p>
        </section>
        <section>
            <h2>Características Principales</h2>
            <ul>
                <li>Asistencia en tiempo real para desarrollo de software y proyectos.</li>
                <li>Capacidad de adaptación a diferentes industrias.</li>
                <li>Aprendizaje continuo para ofrecer mejores respuestas.</li>
                <li>Interacción intuitiva y amigable.</li>
            </ul>
        </section>
        <section>
            <h2>¿Cómo usar Magist?</h2>
            <p>Comienza simplemente interactuando con Magist a través de comandos de texto o preguntas. Magist está aquí para guiarte, aprender contigo y resolver tus dudas.</p>
            <a href="#" class="btn">Aprender Más</a>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Magist AI. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
