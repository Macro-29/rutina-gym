# Rutina Gym

App para seguir la rutina en el gym: qué toca, cuántas repeticiones y con qué peso lo hiciste.

## Subirla a GitHub Pages

1. Crea un repositorio nuevo, por ejemplo `rutina-gym`.
2. Sube los 5 archivos de esta carpeta a la raíz del repo:
   `index.html`, `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png`.
3. Settings -> Pages -> Source: `Deploy from a branch`, rama `main`, carpeta `/ (root)`. Guardar.
4. En un par de minutos queda en `https://TU-USUARIO.github.io/rutina-gym/`.

## Instalarla en el celular

Abre esa URL en Safari (iPhone) o Chrome (Android), botón compartir -> "Añadir a pantalla de inicio".
Queda como una app: pantalla completa, sin barra del navegador y funciona sin señal.

## Dónde quedan los datos

Los pesos se guardan en el propio celular, en el navegador. No se van al subirla ni al actualizarla.
Usa "Copiar respaldo" cada cierto tiempo y guarda ese texto: con "Pegar respaldo" recuperas todo
en otro celular o si limpias el navegador.

## Al actualizar la app

Cambia `const CACHE = 'rutina-gym-v1'` en `sw.js` a `v2`, `v3`, etc. Sin eso el celular
sigue mostrando la versión vieja.
