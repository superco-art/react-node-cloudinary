# Getting Started with Create React App

Este proyecto es una galeria de imagenes donde se puede buscar la foto por su nombre y cargar cada vez mas fotos.
Fue creado con ### React.Js, ### Node.Js y ### [Cloudinary](https://cloudinary.com/users/register/free ).

## esta organizado en dos partes:

1. La carpeta "my-favorite-pictures" es la parte de frontend con React.
2. La carpeta "api" es la parte del servidor, creado con NODE y la api que se conecta con Claudinary.com.

### Crear una cuenta en Cloudinary 

https://cloudinary.com/users/register/free 

En el dashboard encontraras las claves para poder conectarte. 
En el proyecto, carpeta api, crea un archivo llamado .env donde vas a escribir lasclaves:

API_KEY={YOUR_API_KEY}
CLOUD_NAME={YOUR_CLOUD_NAME}
API_SECRET={YOUR_API_SECRET}

En el terminal ejecuta:

npm install
npm run server

## Dependencias
Para crear nuestra propia api con NODE hay que instalar varias dependencias como: 

```python
npm i axios
npm i express
npm i body-parser
npm i cors
npm i dotenv
npm i nodemon --save dev
npm i eslint
```

Se puede ver si funciona en localhost:7000/photos en Postman o Chrome.

### Run the Frontend

Nota! Asegurate que el Node server (en la carpeta api) esta lanzado.

En la carpeta **my-favorite-pictures** crea un archivo **.env** y add an environment variable to point to the local node.js server e.g:

REACT_APP_API_URL=http://localhost:7000

### Lanzar la aplicacion

```bash
npm install
npm start
```

La aplicacion deberia abrirse en localhost:3000


### Proximamente voy hacer un CRUD para poder editar y borar las fotos.



