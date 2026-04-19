<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unir Hatsune Miku Bot 💖</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }
        body {
            background-color: #121212;
            color: #ffffff;
            padding: 2rem;
            max-width: 600px;
            margin: 0 auto;
        }
        .header-img {
            width: 100%;
            border-radius: 12px;
            margin-bottom: 2rem;
        }
        h1 {
            color: #39C5BB;
            font-size: 1.8rem;
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        .divider {
            height: 2px;
            background: linear-gradient(90deg, #39C5BB, #9D65C9);
            margin: 1rem 0;
            border-radius: 2px;
        }
        .texto-destacado {
            font-size: 1.1rem;
            margin-bottom: 2rem;
            color: #eeeeee;
        }
        h2 {
            color: #9D65C9;
            font-size: 1.4rem;
            margin: 2rem 0 1rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        ol {
            margin-left: 1.5rem;
            margin-bottom: 2rem;
            line-height: 2;
            font-size: 1.1rem;
        }
        .numero {
            font-weight: bold;
            color: #39C5BB;
            font-size: 1.2rem;
        }
        .menu-tag {
            background-color: #252525;
            padding: 0.3rem 0.6rem;
            border-radius: 6px;
            font-family: monospace;
        }
        .botones {
            display: flex;
            gap: 1rem;
            margin-bottom: 2rem;
            flex-wrap: wrap;
        }
        .btn {
            padding: 0.6rem 1.2rem;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
            border: none;
            cursor: pointer;
            font-size: 1rem;
        }
        .btn-whatsapp {
            background-color: #25d366;
            color: white;
        }
        .btn-whatsapp:hover {
            background-color: #128c7e;
        }
        .btn-copiar {
            background-color: #9D65C9;
            color: white;
        }
        .btn-copiar:hover {
            background-color: #7b4fa3;
        }
        .nota {
            color: #bbbbbb;
            font-style: italic;
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        .final {
            color: #39C5BB;
            font-weight: bold;
            font-size: 1.1rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
    </style>
</head>
<body>
    <img src="https://i.postimg.cc/Vsh06KVh/4b93c87c47e875c130e3beff83792383.jpg" alt="Banner Hatsune Miku" class="header-img">

    <h1>☇ Hatsune Miku Bot</h1>
    <div class="divider"></div>
    <p class="texto-destacado">Hecho con mucho amor, dedicación y esfuerzo por Yoel 💖</p>

    <h2>☇ ¿Cómo unir el bot a tu grupo?</h2>
    <div class="divider"></div>

    <ol>
        <li>Guarda el número del bot: <span class="numero">5492281367797</span></li>
        <li>Entra a tu grupo de WhatsApp y ve a <strong>"Añadir participantes"</strong></li>
        <li>Selecciona el contacto del bot y confirma</li>
        <li>Envía <span class="menu-tag">.menu</span> para activarlo 🚀</li>
    </ol>

    <div class="botones">
        <a href="https://wa.me/5492281367797?text=Hola%20Miku!%20Quiero%20agregarte%20a%20mi%20grupo%20%F0%9F%92%96" target="_blank" class="btn btn-whatsapp">Abrir Chat con el Bot</a>
        <button onclick="copiarNumero()" class="btn btn-copiar">Copiar Número</button>
    </div>

    <p class="nota">🎤 Versión personalizada con todas las funciones increíbles</p>
    <p class="final">💜 ¡Gracias por usar mi bot! Disfrútalo al máximo</p>

    <script>
        function copiarNumero() {
            navigator.clipboard.writeText('5492281367797');
            alert('✅ Número copiado correctamente!');
        }
    </script>
</body>
</html>

