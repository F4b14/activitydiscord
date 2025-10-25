# Getting Started Activity

Este proyecto es una aplicación que integra un cliente React y un servidor Express, diseñado para interactuar con la API de Discord. A continuación se detallan los componentes principales del proyecto y su propósito.

## Estructura del Proyecto

```
getting-started-activity/
├── .env                     # Variables de entorno necesarias para la configuración del proyecto.
├── .gitignore               # Archivos y directorios que deben ser ignorados por Git.
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
├── public/                  # Carpeta que contiene recursos públicos.
│   ├── JuegoDiscord/        # Proyecto específico de JuegoDiscord.
│   │   ├── dependencies.txt  # Lista de dependencias necesarias para JuegoDiscord.
│   │   ├── GUID.txt          # Identificador único para el proyecto.
│   │   ├── index.html        # Página principal del proyecto de JuegoDiscord.
│   │   ├── ProjectVersion.txt # Versión del proyecto.
│   │   ├── Build/           # Archivos de construcción del juego.
│   │   │   ├── JuegoDiscord.framework.js # Parte del framework del juego.
│   │   │   └── JuegoDiscord.loader.js    # Cargador del framework del juego.
│   │   └── TemplateData/    # Datos de plantilla para el juego.
│   │       └── style.css    # Estilos CSS para la plantilla del juego.
└── server/                  # Carpeta que contiene el código del servidor.
    ├── package.json         # Configuración del proyecto del servidor.
    └── server.js            # Punto de entrada del servidor Express.
```

## Instalación

1. Clona el repositorio en tu máquina local.
2. Navega a la carpeta `getting-started-activity`.
3. Crea un archivo `.env` basado en `example.env` y configura tus variables de entorno.
4. Instala las dependencias del cliente y del servidor:
   - Para el cliente: `cd client && npm install`
   - Para el servidor: `cd server && npm install`
5. Inicia el servidor: `npm start` en la carpeta `server`.
6. Inicia el cliente: `npm run dev` en la carpeta `client`.

## Uso

Accede a la aplicación en tu navegador en `http://localhost:3000` para el cliente y `http://localhost:3001` para el servidor.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o un pull request si deseas contribuir al proyecto.

## Licencia

Este proyecto está bajo la Licencia MIT.