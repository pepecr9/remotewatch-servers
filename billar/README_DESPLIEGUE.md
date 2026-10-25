# Billar RemoteWatch - servidor Render

Sube la carpeta `billar` a tu repositorio GitHub `remotewatch-servers`.
En Render crea New > Web Service con Root Directory `billar`, Build Command `npm install`, Start Command `npm start`, Instance Free.
La URL `https://TU-SERVICIO.onrender.com/` redirige al modo multi.
IMPORTANTE: esto no enlaza aun el cliente de Cloudflare. Para conectarlo, abre la app del billar de RemoteWatch con `?websocketserver=wss://TU-SERVICIO.onrender.com/ws` (ajusta el separador a `&` si ya hay `?`).
Prueba primero `/dist/multi.html` en Render y una mesa entre dos navegadores. No asumas que el servidor esta probado hasta realizar la prueba.

Fuente original: Tailuge billiards, licencia GPL-3.0. Conserva atribucion y licencia al redistribuir.
