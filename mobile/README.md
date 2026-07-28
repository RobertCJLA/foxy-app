# Módulo Mobile

Este directorio alberga la aplicación móvil multiplataforma desarrollada en React Native para Foxy.

---

## Responsabilidades del Módulo

1. **Interfaz de Usuario (UI/UX)**: Proveer una experiencia intuitiva, fluida y accesible tanto para estudiantes como para docentes.
2. **Consumo de APIs**: Comunicación con el servidor principal en Go (`backend`) para autenticación, gestión de perfiles y solicitudes de generación de contenido.
3. **Interacción en Tiempo Real**: Soporte de eventos en tiempo real para la resolución y evaluación instantánea de pruebas y tests.
4. **Gestión de Archivos**: Captura y carga de documentos (PDFs, imágenes de apuntes, textos) enviados por el usuario para alimentar el motor adaptativo.

---

## Funciones Principales

### Para Estudiantes
- **Visualizador de Planes de Estudio**: Malla curricular interactiva con seguimiento de avance.
- **Reproductor de Flashcards**: Sistema interactivo de tarjetas de memorización autodidacta.
- **Módulo de Evaluación**: Interfaz de cuestionarios y tests con retroalimentación inmediata.

### Para Docentes
- **Generador Asistido de Contenidos**: Formularios para parametrizar y recibir planes educativos de asignatura.
- **Explorador de Recursos**: Vista de sugerencias didácticas y material de apoyo.

### Integración de IA
- **Envío de Contexto**: Interfaz para adjuntar documentos que personalizan la respuesta de la IA.
