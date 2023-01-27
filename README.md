# Ejemplo de projecto con Vite

Según [Fatz](https://www.youtube.com/watch?v=UX4gvort2TU), Vite es una herramienta de generación de proyectos en front-end. Permite crear proyectos en multiples frameworks con un servicor de desarrollo. También es una herramienta de compilación para proyectos de front-end ligera, rápida y fácil de usar. Una de sus ventajas respecto a Webpack es que no compila el proyecto entero al hacer `build`, sino solamente la parte que ha cambiado.

- Crear un proyecto de Vite requiere instalar `node`. Después: `npm create vite`.
- Compilar para producción `npm run build`.
- Levantar en servidor de desarrollo `npm run dev`.
- Ver la versión en producción `npm run preview`

[Esta documentación](https://vitejs.dev/guide/static-deploy.html) de Vite sobre publicar aplicaciones estáticas en Github Pages. En el vídeo explican una manera de desplegar a `gh-pages` utilizando el script de la documentación y el paquete [`gh-pages`](https://github.com/tschaub/gh-pages).
