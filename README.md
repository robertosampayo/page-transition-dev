# Page transition with Highwayjs
Its just a test page where I tried HighwayJs library to make page transitions and animations with gsap 

# Uso Basico del proyecto

1. Descargar proyecto con git clone
2. Correr npm install para instalar las dependencias
3. Correr parsel index.html
	te creara un entorno localhost (Ex: localhost:1234) donde podras ver el desarrollo
4. Para produccion agregar lo siguiente al package.json:

	"name": "nombre-del-proyecto",
	"version": "1.0.0",
	"description": "",
	"main": "index.js",
	"scripts": {
	  "start": "parcel index.html --public-url /",
	  "build": "parcel build index.html"
	},
  "keywords": [],
  "author": "",
  "license": "ISC",
  "dependencies": {
    "material-ui": "^0.20.0",
    "react": "^16.2.0",
    "react-dom": "^16.2.0",
    "react-router-dom": "^4.2.2",
    "typeface-roboto": "0.0.45"
  },

 5. Correr parcel build index.html --public-url /
 6. Esto creara una carpeta llamada "dist" aqui empaquetara todo el proyecto
 7. Para correr el proyecto con apache usar la carpeta dist Ex: http://localhost/page-transition-dev/dist/

 8. Pudes empaquetar parcel quitando el cache y la reduccion de los archivos con parcel build index.html --no-cache --no-minify
