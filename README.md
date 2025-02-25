# Proyecto Web con Bootstrap

Este proyecto es una página web básica que utiliza **Bootstrap 5** para la estructura y los componentes visuales. Ha sido diseñada con el objetivo de proporcionar una interfaz clara y fácil de usar, incluyendo navegación entre secciones, carrusel de imágenes, un modal de bienvenida, y enlaces a redes sociales en el footer.

## Características

- **Navegación de secciones**: Al hacer clic en los enlaces del menú, se despliega el contenido de las secciones correspondientes.
- **Modal de bienvenida**: Un botón que abre un modal con un mensaje de bienvenida para los usuarios.
- **Carrusel de imágenes**: Un carrusel interactivo que muestra imágenes de artistas.
- **Acordeón**: Un componente de acordeón para mostrar contenido adicional.
- **Enlaces a redes sociales**: Al pie de la página, se incluyen enlaces a plataformas como Facebook, Twitter, Instagram y LinkedIn.

## Estructura del Proyecto
/Proyecto │ ├── /img # Carpeta que contiene las imágenes del proyecto │ ├── drake.jpeg # Imagen de Drake para el carrusel │ ├── donOmar.jpeg # Imagen de Don Omar para el carrusel │ ├── BadBunny.jpeg # Imagen de Bad Bunny para el carrusel │ ├── /css # Carpeta que contiene los archivos CSS │ ├── styles.css # Estilos personalizados para el proyecto │ ├── index.html # Archivo principal de la página web │ ├── README.md # Documento de descripción del proyecto

## Instalación

1. **Clona el repositorio** a tu máquina local:

    ```bash
    git clone https://github.com/luid95/Carrusel-Artistas.git
    ```

## Uso

1. Abre el archivo `index.html` en tu navegador para ver la página web en acción.
2. Haz clic en los enlaces de navegación para desplazarte entre las diferentes secciones de la página.
3. Haz clic en el botón "Mostrar mensaje de bienvenida" para abrir el modal de bienvenida.

### Secciones disponibles:
- **Inicio**: Información general sobre el proyecto.
- **Nosotros**: Detalles sobre la empresa o proyecto.
- **Servicios**: Descripción de los servicios ofrecidos.
- **Contacto**: Información para ponerse en contacto.

### Modal de bienvenida

Al hacer clic en el botón de bienvenida, se abre un modal con el siguiente mensaje:

> "¡Bienvenido a nuestro sitio web! Nos alegra tenerte con nosotros."

### Carrusel de imágenes

El carrusel muestra imágenes de artistas como **Drake**, **Don Omar** y **Bad Bunny**. Los usuarios pueden navegar entre las imágenes utilizando los botones de navegación.

### Footer con enlaces a redes sociales

El pie de página incluye enlaces a varias redes sociales. Estos enlaces redirigen a las plataformas correspondientes (Facebook, Twitter, Instagram, LinkedIn).

## Estilos

### Archivo `styles.css`

El archivo de estilos personalizados (`styles.css`) contiene los siguientes ajustes:

- **Estilos generales**: Para el cuerpo de la página, incluyendo márgenes, relleno y el uso de la tipografía de `Arial, sans-serif`.
- **Estilos para el Header**: El menú de navegación es centralizado con enlaces en blanco que cambian de color al pasar el mouse.
- **Carrusel**: Estilo personalizado para el carrusel de imágenes, con un fondo negro y ajuste de tamaño para las imágenes.
- **Modal de bienvenida**: El modal tiene un fondo oscuro en el encabezado y un fondo más claro en el cuerpo.
- **Enlaces en el Footer**: Los enlaces de redes sociales tienen efectos de hover para cambiar de color cuando el usuario interactúa con ellos.

## Dependencias

- **Bootstrap 5**: Se utiliza para los componentes como el carrusel, acordeón, y modal. Está incluido desde un CDN:
  
    ```html
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    ```

## Contribuciones

Si deseas contribuir al proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama para tu característica (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -am 'Añadir nueva funcionalidad'`).
4. Empuja a tu rama (`git push origin feature/nueva-funcionalidad`).
5. Crea un Pull Request.

## Licencia

Este proyecto está bajo la **Licencia MIT**. Para más detalles, consulta el archivo LICENSE.
