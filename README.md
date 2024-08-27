# Encriptador de Texto

Este proyecto es una aplicación web simple que permite encriptar y desencriptar texto utilizando un algoritmo básico de sustitución de caracteres. Está desarrollado con HTML, CSS y JavaScript.

## Descripción

El encriptador de texto transforma las vocales del texto ingresado según las siguientes reglas:

- `e` se convierte en `enter`
- `i` se convierte en `imes`
- `a` se convierte en `ai`
- `o` se convierte en `ober`
- `u` se convierte en `ufat`

De igual manera, el desencriptador revierte el texto encriptado a su forma original.

## Características

- **Interfaz amigable**: La aplicación cuenta con una interfaz simple donde el usuario puede ingresar el texto que desea encriptar o desencriptar.
- **Validación de entrada**: Solo se permiten letras minúsculas y sin acentos.
- **Copiar al portapapeles**: Permite copiar el resultado encriptado o desencriptado al portapapeles con un solo clic.

## Estructura del Proyecto

- `index.html`: Contiene la estructura básica de la página web.
- `style.css`: Contiene los estilos CSS para la interfaz de usuario.
- `encriptador.js`: Contiene la lógica de encriptación, desencriptación y manipulación del DOM.

## Cómo Usar

1. Abre el archivo `index.html` en tu navegador web.
2. Ingresa el texto que deseas encriptar en el área de texto.
3. Haz clic en el botón "Encriptar" para encriptar el texto.
4. Si deseas desencriptar un texto encriptado, pégalo en el área de texto y haz clic en "Desencriptar".
5. Usa el botón "Copiar" para copiar el resultado al portapapeles.

## Ejemplo

Si ingresas el texto `hola mundo`, al encriptarlo obtendrás `hoberlai munderfat`. Al desencriptarlo nuevamente, obtendrás `hola mundo`.

## Instalación

No es necesario realizar ninguna instalación. Simplemente clona el repositorio y abre `index.html` en tu navegador.

