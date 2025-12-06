# Proyecto de Ejemplo: Intro a Bootstrap y Sass

En este ejercicio, aprenderemos a integrar **Bootstrap 5** en un proyecto web utilizando **Sass** para la personalización de estilos, gestionando las dependencias a través de **NPM**.

## 📋 Descripción del Proyecto

Este proyecto es una landing page sencilla que demuestra cómo potenciar Bootstrap mediante Sass.

**Tecnologías utilizadas:**

- **HTML5**: Estructura semántica de la página.
- **Sass (SCSS)**: Preprocesador CSS utilizado para organizar los estilos y personalizar Bootstrap.
- **Bootstrap 5**: Framework CSS para el diseño responsivo y componentes preconstruidos.
- **NPM (Node Package Manager)**: Gestor de paquetes utilizado para instalar Bootstrap.

**Funcionalidades clave:**

- **Personalización de Bootstrap**: Hemos modificado la variable `$primary` de Bootstrap para usar nuestro propio color verde.
- **Nuevos colores**: Hemos extendido la paleta de colores de Bootstrap (`$theme-colors`) agregando colores personalizados como `royalgreen` y `royalred`, lo que nos permite usar clases como `btn-royalgreen` o `bg-royalred`.
- **Componentes**: Uso de Navbar, Grid System (filas y columnas), Botones y Tooltips.
- **Estructura Modular**: Los estilos Sass están organizados en carpetas (`abstracts`, `vendors`, etc.) siguiendo buenas prácticas.

---

## 🚀 Guía de Inicio Rápido

Sigue estas instrucciones para descargar y ejecutar el proyecto en tu computadora.

### 1. Requisitos Previos

Asegúrate de tener instalado lo siguiente:

- **Visual Studio Code (VSCode)**: Tu editor de código.
- **Node.js**: Necesario para usar NPM. Puedes descargarlo desde [nodejs.org](https://nodejs.org/).
- **Live Server (Extensión de VSCode)**: Recomendado para ver los cambios en tiempo real.

### 2. Descargar el Proyecto (Clonar)

Abre tu terminal (o Git Bash) y ejecuta el siguiente comando para descargar los archivos desde GitHub:

```bash
git clone https://github.com/Frontend-021-1/m3l5-bootstrap-sass.git
```

Luego, entra a la carpeta del proyecto:

```bash
cd m4d1-intro-bootstrap
```

### 3. Instalar Dependencias

Este paso es **crucial**. Como Bootstrap no está incluido directamente en los archivos (para ahorrar espacio no se incluye la carpeta node_modules en el repositorio como práctica común), necesitamos pedirle a NPM que lo descargue. NPM se encargará de leer el archivo `package.json` y descargar todas las dependencias listadas.

Ejecuta el siguiente comando en la terminal dentro de la carpeta del proyecto (recuerda usar Git Bash si es que estás en Windows):

```bash
npm install
```

Esto creará una carpeta llamada `node_modules` que contendrá Bootstrap y todo lo necesario para que funcione.

### 4. Ejecutar el Proyecto

Para ver el proyecto en tu navegador:

1.  Abre el archivo `index.html` en VSCode.
2.  Haz clic derecho en cualquier parte del código y selecciona **"Open with Live Server"** (o usa el botón "Go Live" en la barra inferior a la derecha).

¡Listo! Deberías ver la página web funcionando con los estilos de Bootstrap aplicados.

---

## 💡 Nota sobre Sass

Los estilos CSS finales (`assets/css/main.css`) ya están incluidos en el proyecto, por lo que **no necesitas compilar Sass para ver la página**.

Sin embargo, si deseas hacer cambios en los estilos (en la carpeta `assets/scss`), necesitarás una herramienta para recompilar el código Sass a CSS (como la extensión "Live Sass Compiler" de VSCode).
