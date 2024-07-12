# Config Server

## Descripción

El Config Server es un componente crucial en una arquitectura de microservicios, encargado de centralizar la configuración de las aplicaciones. Este servidor proporciona una solución para gestionar y servir la configuración externa de las aplicaciones de manera centralizada y segura.

## Funcionalidad

El Config Server permite almacenar configuraciones de aplicaciones en un repositorio git, lo que facilita la gestión de versiones y el control de cambios. Las aplicaciones cliente pueden obtener su configuración desde el Config Server al iniciar o en tiempo real, permitiendo una gestión centralizada y coherente de la configuración.

## Beneficios

- **Centralización**: Permite gestionar la configuración de múltiples aplicaciones desde un único lugar.
- **Seguridad**: Facilita el almacenamiento seguro de configuraciones sensibles.
- **Versionado**: Utiliza sistemas de control de versiones como git para gestionar y rastrear cambios en la configuración.
- **Flexibilidad**: Soporta diferentes entornos (desarrollo, pruebas, producción) y perfiles de configuración.
- **Actualización Dinámica**: Permite a las aplicaciones actualizar su configuración sin necesidad de reiniciar.