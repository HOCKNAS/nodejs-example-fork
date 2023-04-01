# Introducción:
Este es un repositorio bifurcado de [https://github.com/bclswl0827/v2ray-heroku](https://github.com/bclswl0827/v2ray-heroku) que tiene la función de crear un servidor V2Ray en heroku de la manera más sencilla.

Heroku no fomenta esta actividad, por lo que debes bifurcar este proyecto para evitar ser bloqueado por Heroku.

Para aquellos que no tienen una gran necesidad, Heroku es la solución perfecta para aquellos que quieren usar V2Ray para obtener datos móviles gratis:
* 2TB por mes
* 550 horas por mes (~23 días, por supuesto, necesitas dormir 8 horas al día, por lo que 550 horas son más que suficientes)

Aquí tienes las instrucciones:

[![4G Gratis](https://img.youtube.com/vi/79jkqGWi0zU/0.jpg)](https://www.youtube.com/watch?v=79jkqGWi0zU)

=============================================================

# V2Ray Heroku

**Si necesitas implementar V2Ray VLESS, consulta este artículo [vless](https://github.com/bclswl0827/v2ray-heroku/tree/vless)**

## Descripción general

El proyecto V2Ray WebSocket en Heroku debe ser utilizado de manera responsable o será bloqueado.

Después de implementarlo, cada vez que se inicie se cargará la versión más reciente de V2Ray.

## Implementación

### Empezar

 1. Bifurca este proyecto en tu cuenta de GitHub (en la PC puedes ver el botón Fork en la esquina superior derecha, por ejemplo, si tu cuenta se llama "ejemplo").
 2. Cambia el nombre del proyecto a cualquier nombre que no contenga las palabras clave "v2ray" y "heroku" (por ejemplo, cámbialo a "demo").
 3. Edita el archivo `README.md`, reemplaza la ruta `kim7tin/v2heroku` con tu propia ruta (por ejemplo, "ejemplo/demo").

> [![Deployar](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/hieunv95/free4g)

 4. Vuelve a la página principal del proyecto, haz clic en el enlace para implementar V2Ray.

### Argumentos

Los siguientes argumentos se utilizarán durante el proceso de instalación.

| Argumento | Predeterminado | Descripción |
| :--- | :--- | :--- |
| `ID` | `ad806487-2d26-4636-98b6-ab85cc8521f7` | ID de usuario de VMess |
| `AID` | `64` | AlterID, un número entre 0 y 65535 |
| `WSPATH` | `/` | |

## Acceder a CloudFlare

Los siguientes dos métodos pueden conectar la aplicación con CloudFlare, lo que aumenta la velocidad a un cierto nivel:

1. Enlaza el nombre de dominio con la aplicación y conecta el nombre de dominio con CloudFlare.
2. Proxy inverso a través de CloudFlare worker.

## Nota

 1. ** Por favor, no abuses de este proyecto, hay muy pocos servicios gratuitos como Heroku, por favor, úsalo sabiamente y con
