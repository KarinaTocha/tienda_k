# tienda_k
# Proyecto: Página Web Dinámica con JavaScript, HTML y CSS

## Descripción del Proyecto

Este proyecto consiste en crear una página web dinámica que incluya las siguientes secciones y características:

1. **Menú Hamburguesa**: Un menú de navegación accesible que colapse en una vista tipo "hamburguesa" para dispositivos móviles.
2. **Footer**: Un pie de página con información relevante (derechos de autor, enlaces rápidos, etc.).
3. **Navegación (Nav)**: Una barra de navegación funcional para moverse entre las diferentes secciones.
4. **Login y Registro**: Formularios funcionales para que los usuarios puedan iniciar sesión o registrarse.
5. **Productos**: Una lista de productos organizados por categorías.

El objetivo es implementar esta página utilizando solo **JavaScript**, **HTML**, y **CSS**, aplicando buenas prácticas de desarrollo web.

---

## Estructura Requerida

### Archivos y Directorios
Organiza el proyecto de la siguiente manera:
project/ 
│ ├── index.html # Página principal 
├── login.html # Página de inicio de sesión 
├── register.html # Página de registro 
├── productos.html # Página de productos 
│ ├── css/ │ ├── styles.css # Archivo principal de estilos
│ ├── js/ │ ├── main.js # Archivo principal de JavaScript 
│ ├── productos.js # Funciones relacionadas con productos 
│ ├── img/ # Carpeta para imágenes 
└── README.md # Documentación del proyecto


---

## Requisitos

### 1. **HTML**
- Utiliza etiquetas semánticas como `<header>`, `<nav>`, `<section>`, `<footer>`, `<article>`, etc.
- Diseña formularios para login y registro con campos básicos:
  - **Login**: Email y contraseña.
  - **Registro**: Nombre, email, contraseña, confirmar contraseña.

### 2. **CSS**
- Aplica estilos modernos para hacer la página visualmente atractiva.
- Utiliza flexbox y grid para organizar los elementos.
- El menú hamburguesa debe mostrarse solo en dispositivos pequeños y estar accesible mediante CSS y JavaScript.

### 3. **JavaScript**
- Usa JavaScript para:
  - Mostrar/Ocultar el menú hamburguesa.
  - Validar los formularios de login y registro.
  - Cargar dinámicamente la lista de productos y categorías desde un arreglo de objetos.

---

## Funcionalidades

### Menú Hamburguesa
- **Desktop**: El menú se muestra como una barra horizontal fija en la parte superior.
- **Móvil**: El menú se colapsa y se abre al hacer clic en el ícono de hamburguesa.

### Footer
- Debe incluir enlaces rápidos y derechos de autor.

### Productos
- Lista de productos generada dinámicamente desde un arreglo de objetos en `productos.js`.
- Cada producto debe tener:
  - Nombre
  - Precio
  - Imagen
  - Categoría
- Los productos deben organizarse por categorías y mostrarse en una cuadrícula.

### Login y Registro
- Validación en tiempo real de los campos.
- Mensajes de error si los campos no son válidos (por ejemplo, contraseñas que no coincidan).

---


