# Contador_pedagogico
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contador Pedagógico Interactivo - README</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f9f9f9;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 25px 35px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.08);
        }
        h1, h2, h3 {
            color: #2c3e50;
            border-bottom: 2px solid #ecf0f1;
            padding-bottom: 10px;
            margin-top: 30px;
        }
        h1 {
            font-size: 2.2em;
        }
        h2 {
            font-size: 1.8em;
        }
        p {
            margin-bottom: 15px;
        }
        ul {
            list-style-type: disc;
            padding-left: 20px;
        }
        li {
            margin-bottom: 12px;
        }
        a {
            color: #3498db;
            text-decoration: none;
            transition: color 0.3s ease;
        }
        a:hover {
            color: #2980b9;
            text-decoration: underline;
        }
        strong {
            color: #2c3e50;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Contador Pedagógico Interactivo</h1>
        <p>Este es un temporizador interactivo diseñado como una herramienta de aula para gestionar el tiempo de las actividades de los estudiantes. Combina una estética visual atractiva, inspirada en los videojuegos LEGO y Fortnite, con funcionalidades pedagógicas para mantener a los estudiantes concentrados y motivados.</p>

        <h2>✨ Características Principales</h2>
        <ul>
            <li><strong>Tiempo Personalizable:</strong> Se pueden establecer minutos y segundos fácilmente.</li>
            <li><strong>Mensajes Pedagógicos:</strong> Muestra mensajes de orientación y motivación en puntos clave del conteo (al inicio, al 75%, 50% y 25% del tiempo).</li>
            <li><strong>Diseño Atractivo:</strong> Interfaz visual con colores vibrantes, una fuente audaz y botones con estilo de videojuego para captar la atención de los estudiantes.</li>
            <li><strong>Barra de Progreso Visual:</strong> Una barra de progreso, similar a una barra de "escudo" o energía, muestra el tiempo restante de forma intuitiva.</li>
            <li><strong>Efectos de Sonido:</strong> Emite un sonido de notificación agradable cuando el tiempo se acaba.</li>
            <li><strong>Optimizado para la Web:</strong> Creado como un único archivo <code>index.html</code>, listo para ser publicado en servicios como Netlify.</li>
        </ul>

        <h2>🚀 Cómo Usarlo en PowerPoint</h2>
        <p>El objetivo principal de este contador es ser insertado en presentaciones de PowerPoint para dinamizar las clases.</p>
        
        <h3>1. Publicar en Netlify:</h3>
        <ul>
            <li>Ve a <a href="https://app.netlify.com/drop" target="_blank" rel="noopener noreferrer">Netlify Drop</a>.</li>
            <li>Arrastra y suelta el archivo <code>index.html</code> del contador en la página.</li>
            <li>Netlify generará una URL pública. Cópiala.</li>
        </ul>

        <h3>2. Insertar en PowerPoint:</h3>
        <ul>
            <li>Necesitas el complemento gratuito <strong>"Web Viewer"</strong>. Búscalo e instálalo desde <strong>Insertar > Obtener complementos</strong>.</li>
            <li>Una vez instalado, ve a <strong>Insertar > Web Viewer</strong>.</li>
            <li>Pega la URL de Netlify en el campo que aparece y haz clic en "Preview".</li>
            <li>¡Listo! El contador interactivo funcionará dentro de tu diapositiva. (Requiere conexión a internet durante la presentación).</li>
        </ul>

        <h2>🛠️ Tecnologías Utilizadas</h2>
        <ul>
            <li><strong>HTML5</strong></li>
            <li><strong>CSS3</strong> (con <strong>Tailwind CSS</strong> para el diseño rápido)</li>
            <li><strong>JavaScript</strong> (para toda la lógica del temporizador y la interactividad)</li>
            <li><strong>Tone.js</strong> (para los efectos de sonido)</li>
            <li><strong>Google Fonts</strong> (para la tipografía personalizada)</li>
        </ul>
    </div>
</body>
</html>


