
# DOSW_ParcialT2_PaulaDiaz

## Índice
1. [Datos del estudiante](#1-datos-del-estudiante)
2. [Descripción del proyecto](#2-descripción-del-proyecto)
3. [Despliegue](#3-despliegue)
4. [Estructura del proyecto](#4-estructura-del-proyecto)
5. [Tecnologías y dependencias](#5-tecnologías-y-dependencias)
6. [Configuración y variables de entorno](#6-configuración-y-variables-de-entorno)
7. [Cómo ejecutar](#7-cómo-ejecutar)
8. [Pruebas](#8-pruebas)
9. [Docker](#9-docker)
10. [CI/CD](#10-cicd)
11. [Herramientas de modelado y diseño](#11-herramientas-de-modelado-y-diseño)

## 1. Datos del estudiante
- Nombre completo: [Nombre completo]
- Grupo: [Grupo]
- Profesor agregado como colaborador: Pendiente

## 2. Descripción del proyecto
Servicio base desarrollado en Java con Spring Boot para el parcial práctico de DOSW.
Incluye una estructura MVC, un endpoint de salud y configuración inicial para
persistencia con MongoDB, pruebas, seguridad y despliegue.

## 3. Despliegue
- URL del servicio: Pendiente
- URL del health: Pendiente
- URL de Swagger: Pendiente

## 4. Estructura del proyecto
- `controller`: controladores REST, DTOs, mappers y handlers.
- `core`: servicios, modelos, validadores y utilidades.
- `persistence`: entidades MongoDB, repositorios y mappers.
- `config`: configuración de la aplicación y seguridad.
- `main`: clase principal de Spring Boot.

## 5. Tecnologías y dependencias
- Java 26
- Maven 3.9.16
- Spring Boot 3.5.16
- Spring Web
- Spring Data MongoDB
- Spring Security
- JWT
- Swagger / OpenAPI
- Lombok y MapStruct
- JUnit y Mockito
- JaCoCo

## 6. Configuración y variables de entorno
| Variable | Descripción |
|---|---|
| `MONGODB_URI` | URI de conexión a MongoDB |
| `JWT_SECRET` | Secreto para firmar tokens JWT |
| `PORT` | Puerto del servicio |

No publicar valores reales de credenciales.

## 7. Cómo ejecutar
```bash
mvn clean verify
mvn spring-boot:run
```

Endpoint de salud local:
`http://localhost:8080/api/v1/health`

## 8. Pruebas
Ejecutar `mvn test`.
Reporte JaCoCo: `target/site/jacoco/index.html`, después de ejecutar las pruebas.

## 9. Docker
Pendiente de configurar.

## 10. CI/CD
Pendiente de configurar con GitHub Actions.

## 11. Herramientas de modelado y diseño
- Herramienta de diagramación: Pendiente
- Figma: Pendiente
- Evidencias: Pendientes
