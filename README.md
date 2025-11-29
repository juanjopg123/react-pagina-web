📘 ReactPaginaWeb

Este proyecto es una aplicación web creada con React utilizando la plantilla estándar de Create React App.
Aquí encontrarás instrucciones sobre instalación, ejecución, scripts disponibles, estructura del proyecto y requisitos.

🚀 Características principales

Proyecto creado con Create React App

Estructura lista para escalar con carpeta components/

Configuración inicial para correr en entorno local

Scripts automáticos para desarrollo y build

📦 Requisitos

Asegúrate de tener instalado lo siguiente en tu sistema:

✅ Node.js (versión 16 o superior)

Descarga desde: https://nodejs.org/

✅ npm (viene con Node)

Puedes verificar la instalación con:

node -v
npm -v

📁 Estructura del Proyecto

reactpaginaweb/
├── node_modules/
├── public/
├── src/
│   ├── components/
│   ├── App.css
│   ├── App.js
│   ├── App.test.js
│   ├── index.css
│   ├── index.js
│   ├── logo.svg
│   ├── reportWebVitals.js
│   └── setupTests.js
├── .gitignore
├── package.json
├── package-lock.json
└── README.md

⚙️ Instalación

Dentro de la carpeta del proyecto, ejecuta:

npm install

Esto instalará todas las dependencias listadas en el package.json.


▶️ Cómo ejecutar el proyecto

Para iniciar el servidor de desarrollo, usa:

npm start

Esto abrirá automáticamente la app en:

👉 http://localhost:3000

El servidor recarga automáticamente al guardar cambios.

🛠️ Scripts disponibles

En el proyecto puedes usar los siguientes comandos:

npm start

Inicia el entorno de desarrollo.

npm run build

Genera la versión optimizada para producción en la carpeta build/.

npm test

Lanza el runner de pruebas en modo interactivo.

npm run eject

⚠️ Irreversible: expone toda la configuración de Create React App.

🌐 Despliegue

La carpeta generada por npm run build contiene archivos listos para subirse a:

GitHub Pages

Netlify

Vercel

Servidores Nginx o Apache