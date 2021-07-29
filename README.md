# Creación del entorno de desarrollo

## Backend

### Crear entorno virtual para el backend
Dentro de la carpeta del proyecto crear el entorno virtual usando este comando
```bash
python -m venv .venv
```


### Activar el entorno virtual
Dentro de la carpeta del proyecto activamos el entorno virtual usando este comando
```bash
source .venv/bin/activate
```

### Instalar dependencias

Dentro de la carpeta del proyecto instalamos las dependencias con el siguiente comando, es requerido tener habilitado el entorno virtual
```bash
pip install -r requirements.txt
```


## Frontend


### Instalar dependencias
Para instalar las dependencias del Front de la aplicación primeramente debemos ubicarnos en la carpeta ```frontend```, para ello puedes usar el comando ```cd frontend```. Estando dentro de la carpeta del front ejecutamos el siguiente comando para instalar las dependencias

```bash
npm install
```


## Levantar los servicios
Para el correcto funcionamiento de la aplicación ambos servicios deben estar levantados

### Backend
Para levantar el servicio del backend debes estar ubicado en la carpeta raiz del proyecto y ejecutar el siguiente comando:
```bash
python manage.py runserver
```
El backend se levanta en la siguiente URL http://127.0.0.1:8000/
### Frontend
Para levantar el servicio del frontend debes estar ubicado en la carpeta ```frontend``` y ejecutar el siguiente comando
```bash
npm run serve
```
El frontend se levanta en la siguiente URL  http://localhost:8080/