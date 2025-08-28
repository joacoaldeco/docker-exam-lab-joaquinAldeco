# docker-exam-lab-joaquinAldeco
## Archivos incluidos

- `Dockerfile`
- `app.js`
- `package.json`
- `docker-compose.yml`

Instrucciones

 1. Construir la imagen

(consola)
docker build -t mi-app .
Esto crea una imagen llamada mi-app usando el Dockerfile

docker run -p 3000:3000 mi-app
Esto levanta el contenedor y expone el puerto 3000.
Abrir el navegador en http://localhost:3000 para ver el mensaje.

docker-compose up
Esto usa el archivo docker-compose.yml para levantar el servicio app

