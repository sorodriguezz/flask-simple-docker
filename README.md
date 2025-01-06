# Flask API simple with Docker

## Descripción
Este proyecto contiene una aplicación sencilla en flask. Donde la parte central es entender y aprender como levantar este proyecto en docker por medio de Dockerfile

## Dependencias
- Docker

## Ejecución

1. Usar ```docker build -t flask_app .```
2. Luego de crear la imagen usar ```docker run -dp 5000:5000 --name flask_container flask_app```

