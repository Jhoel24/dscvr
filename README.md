# Agencia de Marketing DSCVR - Sitio Web Corporativo

Este repositorio contiene el código fuente del sitio web de la agencia de marketing DSCVR. El diseño está inspirado en una estética futurista y aprovecha las tecnologías web modernas para proporcionar una experiencia única a los usuarios.

## Características del Sitio

- **Experiencia de Usuario Futurista**: Con la integración de Three.js, ofrecemos una interfaz rica en gráficos 3D para capturar la visión futurista de nuestra agencia.
- **Registro de Usuarios**: Formularios interactivos que permiten a los visitantes registrarse para obtener más información sobre nuestros servicios.
- **Gestión de Suscripciones**: Un sistema back-end para manejar suscripciones y mantener a nuestros clientes actualizados con las últimas ofertas y noticias.

## Tecnologías Implementadas

- **Three.js**: Para renderizar gráficos 3D en la web.
- **PHP**: Para el manejo del lado del servidor, incluyendo la gestión de formularios y suscripciones.
- **SCSS**: Para escribir estilos CSS eficientes y mantenibles.

## Estructura del Repositorio

```plaintext
/
├── public/           # Archivos accesibles al público
│   ├── css/          # Hojas de estilo CSS
│   ├── img/          # Imágenes y recursos gráficos
│   ├── js/           # Código JavaScript para el front-end
│   └── index.php     # Página de inicio
├── src/              # Código fuente
│   ├── js/           # Scripts de Three.js y otros
│   ├── php/          # Scripts PHP del lado del servidor
│   └── scss/         # Estilos SCSS
├── .gitignore        # Archivos y carpetas ignoradas por git
├── package.json      # Configuración de Node.js y scripts
└── README.md         # Documentación del proyecto
```

## Configuración Local

Para configurar el sitio web en un entorno local, siga estos pasos:

1. Clone el repositorio en su entorno de desarrollo local.
2. Ejecute `npm install` para instalar las dependencias de Node.js necesarias.
3. Utilice `npm run scss` para compilar los archivos SCSS a CSS.
4. Configure un servidor local PHP para servir el sitio, como XAMPP o MAMP, o use el servidor incorporado en PHP con `php -S localhost:8000 -t public`.
5. Abra `http://localhost:8000` en su navegador para acceder al sitio.

## Política de Contribuciones

Este repositorio es privado y el código fuente es exclusivo de DSCVR. Cualquier modificación, distribución o implementación del código debe ser aprobada por los propietarios de la agencia.

## Licencia

Este proyecto y todos los archivos contenidos en este repositorio están protegidos por derechos de autor y son propiedad exclusiva de DSCVR. El uso no autorizado, la copia, la modificación y la distribución están estrictamente prohibidos.

---

© 2024 DSCVR. Todos los derechos reservados.