# Proyecto TestGame

Este proyecto es una aplicación web que integra un juego desarrollado con Unity y una interfaz de usuario construida con React. A continuación se detallan los componentes y su estructura.

## Estructura del Proyecto

```
getting-started-activity/
├── .env                     # Variables de entorno necesarias para la configuración del proyecto.
├── .gitignore               # Archivos o directorios que deben ser ignorados por Git.
├── example.env              # Ejemplo de configuración de variables de entorno.
├── README.md                # Documentación del proyecto.
├── renovate.json            # Configuración para Renovate, herramienta de automatización de actualizaciones de dependencias.
├── client/                  # Carpeta que contiene el código del cliente.
│   ├── index.html           # Página principal del cliente.
│   ├── main.jsx             # Código principal de la aplicación React.
│   ├── out.css              # CSS generado para el estilo de la aplicación.
│   ├── out.js               # JavaScript generado para la funcionalidad de la aplicación.
│   ├── package.json         # Configuración del proyecto del cliente.
│   ├── style.css            # Estilos CSS para la aplicación.
│   └── vite.config.js       # Configuración para Vite, empaquetador de módulos.
├── public/                  # Carpeta que contiene archivos públicos.
│   ├── JuegoDiscord/        # Carpeta específica para el proyecto de JuegoDiscord.
│   │   ├── dependencies.txt  # Lista de dependencias necesarias para el proyecto de JuegoDiscord.
│   │   ├── GUID.txt          # Identificador único para el proyecto.
│   │   ├── index.html        # Página principal del proyecto de JuegoDiscord.
│   │   ├── ProjectVersion.txt # Versión del proyecto.
│   │   ├── Build/           # Carpeta que contiene archivos del framework del juego.
│   │   │   ├── JuegoDiscord.framework.js
│   │   │   └── JuegoDiscord.loader.js
│   │   └── TemplateData/    # Carpeta que contiene estilos CSS para la plantilla del juego.
│   │       └── style.css
└── server/                  # Carpeta que contiene el código del servidor.
    ├── package.json         # Configuración del proyecto del servidor.
    └── server.js            # Punto de entrada del servidor Express.
```

## Instalación

1. Clona el repositorio en tu máquina local.
2. Navega a la carpeta `getting-started-activity`.
3. Crea un archivo `.env` basado en `example.env` y configura tus variables de entorno.
4. Instala las dependencias del cliente y del servidor ejecutando `npm install` en las carpetas `client` y `server`.

## Ejecución

Para iniciar el servidor, navega a la carpeta `server` y ejecuta:

```
npm start
```

Para iniciar el cliente, navega a la carpeta `client` y ejecuta:

```
npm run dev
```

## Contribuciones

Las contribuciones son bienvenidas. Si deseas contribuir, por favor abre un issue o envía un pull request.

## Licencia

Este proyecto está bajo la Licencia MIT.