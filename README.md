# RETO · AEK

## Descripción del proyecto

El proyecto AEK tiene como objetivo desarrollar una
solución informática que facilite la gestión de una
academia de euskera, mejorando la organización y el
acceso a la información.

El proyecto se divide en tres partes principales:
programación en Java, gestión de bases de datos mediante
MySQL y desarrollo web mediante HTML y CSS.

## Equipo

| Integrante | Usuario Git | Responsabilidad principal |
| --- | --- | --- |
| Unax Villaseca | @unax776 | Programación |
| Kerman Solana | @Solanilla10 | Base de datos |
| Oihan Callao | @polli67 | Desarrollo web |

## Índice de la documentación

- [Programación (Java)](docs/programacion/README.md)
- [Base de datos](docs/bbdd/README.md)
- [Web (HTML y CSS)](docs/web/README.md)
- [Decisiones técnicas](docs/decisiones-tecnicas.md)
- [Pendientes, errores conocidos y mejoras](docs/pendientes.md)
- [Trazabilidad entre módulos](docs/trazabilidad.md)
- [Evidencias de Git](evidencias/git/proceso.md)

## Estructura del repositorio

| Carpeta | Contenido |
| --- | --- |
| `programacion/` | Código fuente de la aplicación Java. |
| `bbdd/sql/` | Scripts de creación y gestión de la base de datos. |
| `web/` | Páginas HTML y hojas de estilos CSS. |
| `docs/` | Documentación técnica de los diferentes módulos. |
| `evidencias/` | Evidencias del trabajo colaborativo, revisiones y auditorías. |

## Cómo empezar

> Apartado pendiente de completar en el LAB 05.

### Requisitos

| Herramienta | Versión | Para qué |
| --- | --- | --- |
| JDK | 21 (por confirmar) | Compilar y ejecutar la aplicación Java. |
| MySQL | 8.0 (por confirmar) | Crear y gestionar la base de datos. |
| Conector JDBC | Pendiente | Conectar Java con MySQL. |
| Navegador web | Actual | Visualizar las páginas web. |

### Orden de puesta en marcha

1. Crear la base de datos siguiendo la
   [guía de reconstrucción](docs/bbdd/README.md).
2. Abrir el proyecto Java y configurar la conexión
   con la base de datos.
3. Abrir el archivo `web/index.html` en el navegador.

### Dependencias entre partes

- Java necesita MySQL para almacenar, consultar y
  modificar los datos.
- JDBC permite establecer la conexión entre Java
  y la base de datos.
- HTML define la estructura de la página web.
- CSS permite definir su diseño y presentación visual.