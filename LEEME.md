# ArtSam_01 — App de Lealtad PWA

## Archivos incluidos
- `index.html` — La app completa
- `manifest.json` — Configuración PWA (para instalar en celular)
- `sw.js` — Service Worker (offline + notificaciones)

## Cómo publicarla GRATIS en GitHub Pages

1. Crea una cuenta en github.com
2. Crea un repositorio nuevo llamado `artsam-loyalty`
3. Sube los 3 archivos (index.html, manifest.json, sw.js)
4. Ve a Settings → Pages → Source: main branch
5. Tu app estará en: https://TU_USUARIO.github.io/artsam-loyalty

## Contraseña de administrador
Está en index.html, línea con: const ADMIN_PASS = "artsam2024"
Cámbiala antes de publicar.

## Para los clientes
- Entran con su email y nombre
- Ven sus sellos acumulados
- Pueden agregar la tarjeta a Google Wallet (si configuras el enlace)

## Para ti como administrador
- Toca "Acceso administrador" en la pantalla de login
- Ingresa la contraseña
- Registra clientes con el botón +
- Agrega o quita sellos tocando al cliente
- Resetea cuando canjea el premio

## Personalización
En index.html puedes cambiar:
- TOTAL_SELLOS = 10 (cantidad de sellos para el premio)
- ADMIN_PASS = "artsam2024" (contraseña admin)
- Premio: busca "Sticker, Poster o Llavero" y cambia el texto
