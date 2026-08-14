<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Stream Local - Sin Publicidad</title>
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://content.jwplatform.com/libraries/IDzF9Zmk.js"></script>
    <script src="https://cdn.rawgit.com/jpillora/xhook/1.4.9/dist/xhook.min.js"></script>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body, html {
            width: 100%;
            height: 100%;
            background: #000;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        /* Contenedor con relación 16:9 y tamaño máximo */
        #player-wrapper {
            width: 100%;
            max-width: 1280px;   /* opcional, ajusta según prefieras */
            aspect-ratio: 16 / 9;
            background: #000;
        }
        #player {
            width: 100%;
            height: 100%;
        }
    </style>
</head>
<body>

    <div id="player-wrapper">
        <div id="player"></div>
    </div>

    <script>
        var url = atob("aHR0cHM6Ly9kYWkuZ29vZ2xlLmNvbS9saW5lYXIvaGxzL3BhL2V2ZW50L1o5MUl6OWYwVGstNUxLbHN1Nnp4U2cvc3RyZWFtLzg1YmZkZTBmLTllZDctNDY0NC1iOTYxLTM2NWUxZWJkYjhkMzpTQ0wyL21hc3Rlci5tM3U4");
        var key = atob("ZGF0YTphcHBsaWNhdGlvbi9vY3RldC1zdHJlYW07YmFzZTY0LDFDM0crb2x0bjY4a20xOS9rZXpUd3c9PQ==");
        var lang = "en";
        var audioTrackSet = false;

        $(document).ready(function() {
            // Interceptor para las llaves de cifrado
            xhook.before(function(request) {
                if (request.url.includes('cbsi.live.ott.irdeto.com')) {
                    request.url = key;
                }
            });

            // Configuración del reproductor
            var player = jwplayer("player").setup({
                playlist: [{
                    "sources": [{
                        "default": true,
                        "type": "hls",
                        "file": url,
                        "label": "auto"
                    }]
                }],
                width: "100%",
                height: "100%",
                autostart: true,
                mute: false,
                // Opcional: mostrar controles siempre
                controls: true,
                // Opcional: ocultar el logo de JWPlayer (si tienes licencia)
                // logo: { hide: true }
            });

            // Intenta entrar en pantalla completa automáticamente (puede ser bloqueado)
            // Para mayor fiabilidad, lo ejecutamos tras un clic del usuario.
            // Aquí lo dejamos comentado, pero puedes descomentar y probar:
            // player.requestFullscreen();

            // Alternativa: al hacer clic en cualquier parte del contenedor
            $("#player-wrapper").on("click", function() {
                player.requestFullscreen();
            });
        });
    </script>
</body>
</html>
