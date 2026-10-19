# AulaDeploy

Aplicación web estática y progresiva para acompañar el estudio del despliegue de aplicaciones web. Representa un panel de operaciones con proyectos ficticios de DAW, entornos, versiones e historial de despliegues.

## Ejecutar en local

No requiere instalar dependencias. Desde la raíz del proyecto:

```bash
python3 -m http.server 8080 --directory dist
```

Después se abre `http://localhost:8080`.

## Comprobaciones

```bash
node --check dist/js/app.js
python3 tests/smoke_test.py
```

## Estructura

- `dist/index.html`: estructura y contenido de la interfaz.
- `dist/css/styles.css`: identidad visual y diseño adaptable.
- `dist/js/app.js`: datos de ejemplo, navegación e interacciones.
- `dist/assets/favicon.svg`: icono de la aplicación.
- `tests/smoke_test.py`: prueba básica de integridad.

## Alcance de la versión 0.1

- Panel general con indicadores.
- Catálogo filtrable de cuatro proyectos.
- Ficha detallada e historial por proyecto.
- Formulario validado para registrar solicitudes de despliegue.
- Diseño adaptable y navegación accesible.

La aplicación es demostrativa: no envía datos a un servidor ni realiza despliegues reales.

## Copyright 

Desarrollado por 2 de DAW

## Guía para ejecutar AulaDeploy en local

### 1. Requisitos

Para utilizar AulaDeploy necesitamos:

- Un ordenador con Windows, Linux o macOS.
- Git instalado para clonar el repositorio.
- Visual Studio Code u otro editor de código.
- Un navegador web actualizado.

### 2. Clonar el repositorio

Abrimos una terminal y ejecutamos:

git clone https://github.com/AndresMV12/AulaDeploy-0.1.git

Después entramos en la carpeta del proyecto:

cd AulaDeploy-0.1

### 3. Abrir el proyecto

Abrimos la carpeta descargada en Visual Studio Code:

code .

### 4. Ejecutar la aplicación

Seguimos las instrucciones de ejecución que aparecen
en este README para iniciar AulaDeploy en local.

### 5. Comprobaciones

Una vez iniciada la aplicación debemos comprobar:

- Que la página se visualiza correctamente.
- Que los archivos del proyecto están disponibles.
- Que no aparecen errores durante la ejecución.
- Que las funciones principales se pueden utilizar.

### 6. Información adicional

Esta documentación facilita que otros desarrolladores
puedan descargar y ejecutar el proyecto.

La mejora está relacionada con la issue #2.

## Solución de problemas frecuentes

### La aplicación no se abre en el navegador

Si AulaDeploy no se abre correctamente, debemos comprobar
que estamos utilizando la dirección adecuada para acceder
a la aplicación.

También podemos intentar actualizar la página o abrirla
en otro navegador.

### No aparecen los archivos del proyecto

Debemos comprobar que el repositorio se ha clonado
correctamente y que estamos trabajando en la carpeta
adecuada.

### Aparecen errores al ejecutar la aplicación

Podemos revisar los mensajes que aparecen en la terminal
y comprobar que seguimos las instrucciones de ejecución
indicadas en el README.

### Los cambios no se visualizan

Si modificamos algún archivo y no aparecen los cambios,
podemos actualizar el navegador y comprobar que los
archivos se han guardado correctamente.