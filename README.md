# Práctica 3: Formularios validados con JS parte 2

## Acerca del Proyecto

Este proyecto es una aplicación web que te permite llenar un formulario, ver los resultados en una página de resultados y vaciar la tabla de resultados si lo deseas.

## Preguntas Frecuentes

### ¿Qué son los arreglos en JavaScript?

Los arreglos en JavaScript son como listas que pueden almacenar múltiples valores. Puedes pensar en ellos como una caja que puede contener diferentes tipos de objetos, como números, cadenas de texto o incluso otros arreglos.

### ¿Qué es el almacenamiento del navegador (sessionStorage y localStorage)?

El almacenamiento del navegador, como `sessionStorage` y `localStorage`, es una forma de guardar datos en el navegador web para que puedan persistir entre sesiones o incluso páginas. 

- **Ventajas**: Es fácil de usar y permite almacenar datos de manera simple.
- **Desventajas**: Tiene un límite de capacidad (generalmente varios megabytes), y los datos se almacenan como cadenas de texto.

Para acceder a estos almacenes desde JavaScript, puedes usar `localStorage.setItem(key, value)` para almacenar datos, `localStorage.getItem(key)` para recuperar datos y `localStorage.removeItem(key)` para eliminar datos.

### ¿Qué es JSON?

JSON (JavaScript Object Notation) es un formato de datos ligero y fácil de leer que se utiliza para estructurar datos. Es muy común en la comunicación entre el navegador y el servidor.

### ¿Qué hacen las funciones JSON.parse() y JSON.stringify()?

- `JSON.parse()`: Convierte una cadena JSON en un objeto JavaScript.
- `JSON.stringify()`: Convierte un objeto JavaScript en una cadena JSON.

Estas funciones son útiles cuando necesitas enviar o recibir datos en formato JSON.

### ¿Cómo funciona window.location.href?

`window.location.href` es una propiedad de JavaScript que te permite cambiar la ubicación actual del navegador. Al asignarle una nueva URL, el navegador redireccionará a esa URL.

### ¿Cómo funciona scriptResultados.js?

`scriptResultados.js` es el archivo JavaScript que maneja la página de resultados. Se encarga de mostrar los datos almacenados en el almacenamiento local en una tabla y también de vaciar la tabla cuando el usuario hace clic en el botón "Vaciar Tabla". La función `mostrarResultados()` actualiza la tabla con los datos almacenados, y cuando se hace clic en el botón "Vaciar Tabla", se borran los datos y se refresca la tabla.

