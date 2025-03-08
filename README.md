# Urban Style Store

Urban Style Store es una tienda en línea de ropa urbana moderna. Este proyecto está desarrollado con JavaScript y React para ofrecer una experiencia de usuario fluida e interactiva.

## Tecnologías Utilizadas

- **React**: Framework para construir interfaces de usuario interactivas.
- **JavaScript (ES6+)**: Lenguaje de programación utilizado para la lógica del frontend.
- **CSS / SCSS**: Estilizado responsivo para mejorar la experiencia del usuario.
- **Bootstrap 5**: Utilizado para el diseño y estructura del sitio.

## Características

- **Catálogo de productos**: Lista de productos con nombre, descripción, imagen y precio.
- **Carrito de compras**: Permite agregar productos al carrito y visualizar los seleccionados (localstorage).
- **Diseño responsivo**: Adaptado para funcionar en dispositivos móviles y de escritorio.
- **Interfaz moderna**: Diseño atractivo con colores y tipografía adecuados para una tienda de ropa urbana.

## Instalación y Uso

### Prerrequisitos

Asegúrate de tener instalado Node.js y npm en tu sistema.

### Clonar el repositorio

```sh
  git clone https://github.com/julicode10/urban-store.git
  cd urban-store
```

### Instalar dependencias

```sh
  npm install
```

### Ejecutar en modo desarrollo

```sh
  npm run dev
```

### Ejecutar en modo producción

```sh
  npm run build
```

El servidor se iniciará en `http://localhost:5173`.

## Estructura del Proyecto

```
 urban-style-store/
  |-- public/
      |-- img/         # Imágenes del sitio
  |-- src/
      |-- assets/      # Imágenes y estilos
      |-- components/  # Componentes reutilizables
      |-- data/        # Datos de prueba (archivo json)
      |-- App.jsx      # Componente principal
      |-- index.css    # Estilos globales
      |-- main.jsx     # Punto de entrada de la aplicación
  |-- index.html       # Archivo HTML de entrada
  |-- package.json
  |-- README.md
  |-- vite.config.js   # Configuración de Vite
```

## Licencia

Este proyecto está bajo la licencia MIT. Puedes ver más detalles en el archivo `LICENSE`.
