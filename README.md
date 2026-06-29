# Resolución de problemas Ishikawa

Proyecto estático para analizar no conformidades con un diagrama de Ishikawa.

## Cómo usar localmente

1. Instala dependencias:
   ```bash
   npm install
   ```
2. Ejecuta el servidor local:
   ```bash
   npm start
   ```
3. Abre la URL que te muestre la terminal.

## Cómo desplegar en GitHub Pages

Este repositorio ya incluye un flujo de GitHub Actions para publicar en GitHub Pages cuando haces push a `main`.

1. Sube tus cambios a la rama `main`.
2. En GitHub, ve a `Settings` → `Pages`.
3. Si es necesario, habilita la publicación desde `GitHub Actions`.
4. La página quedará disponible en algo como:
   `https://<tu-usuario>.github.io/Resolcuion-de-problemas-ishicawa`

## Acceso privado

- La página usa una clave de acceso en la URL: `?access=<tu-clave>`.
- Puedes cambiar la clave desde el botón `Cambiar clave` en la pantalla de ingreso.
- La nueva clave se guarda en el navegador y también se utiliza para generar el enlace compartido.

> Nota: este método es un control de acceso simple en el cliente. No es equivalente a una protección de servidor, pero funciona para evitar acceso casual desde la URL pública.
