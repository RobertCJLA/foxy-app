# Módulo Backend Core

Este directorio contiene el servidor principal desarrollado en Go que actúa como la API Gateway y centro de control del negocio para Foxy.

---

## Responsabilidades del Módulo

1. **API Gateway & Enrutamiento**: Exponer endpoints REST/HTTP estandarizados para la aplicación móvil (`mobile`).
2. **Autenticación y Autorización**: Manejo de sesiones de usuario (estudiantes y docentes) mediante JWT y control de acceso basado en roles.
3. **Persistencia Relacional**: Operaciones CRUD en la base de datos PostgreSQL (usuarios, historial de actividades, metadatos de archivos).
4. **Orquestador de Servicios**: Canalizar peticiones intensivas de generación de material al microservicio de IA (`ai-service`).

---

## Funciones Principales

- **Gestión de Usuarios y Perfiles**: Registro, login y almacenamiento de preferencias educativas.
- **Gestión de Documentos**: Recepción y almacenamiento de archivos subidos por el usuario para su posterior procesamiento por la IA.
- **Orquestación de Planes y Pruebas**: Coordinación del flujo de solicitud de planes de estudio, flashcards y tests hacia el servicio de IA.
- **Validación de Datos**: Validación de formatos y restricciones de entrada según los esquemas compartidos en `docs/schemas/`.
