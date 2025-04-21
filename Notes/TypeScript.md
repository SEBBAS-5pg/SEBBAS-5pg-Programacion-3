# Pasos para crear un proyecto
1. Crear una carpeta para proyecto 📁
2. Acceder a la carpeta por terminal
3. Comando yarn para crear el proyecto
```bash
yarn create vite
```
4. Colocamos el nombre del proyecto y elegimos el framework
- Para desplegar el proyecto 
```bash
yarn dev #dentro de la carpeta del proyecto
```
---

<p align="center">
  <a href="https://nodejs.org/es" target="blank">
    <img src="
    https://nodejs.org/static/images/logo.svg
    " width="120" alt="Node logo"/>
  </a>
</p>

## Node
¿Que es Node?
Es un entorno de ejecucion que permite ejecutar codigo javascript en el lado del servidor utilizando:

### Vite:
Vite usa ES Modules y sirve los archivos de inmediato desde un servidor local.
Al iniciar el proyecto (vite), Vite crea un servidor de desarrollo ultrarrápido.
No es necesario agrupar todo el código antes de servirlo.
Solo transpila y envía los archivos a medida que el navegador los solicita.

### Modelo Asincronico:
Permite que una tarea se inicie y continue ejecutandose en segundo plano emientras el programa sigue ejecutando otras tareas Esto evita que el programa quede bloqueado esperando que una operación termine.

### Modelo Orientado a Eventos:
El codigo responde a ciertos eventos como solicitud de usuario, la llegada de datos, un clic en la interfaz, etc. todo manejado por *Event Loop*; El Event Loop trabaja en ciclos y revisa constantemente si hay tareas pendientes en diferentes colas (queues).

- *Hot reload:* Cada vez que se hace una modificacion lo carga en la pagina

<img src="https://i.stack.imgur.com/BTm1H.png" width="400" alt="Funcion de Node"/>

## Yarn 

¿que es yarn?
Yarn es un administrador de paquetes para JavaScript.*Un administrador de paquetes* es una herramienta esencial que facilita la gestión de las bibliotecas necesarias para que un proyecto se ejecute correctamente, mejorando la productividad y consistencia en el desarrollo.
