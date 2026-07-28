# Módulo AI Service

Este directorio contiene el microservicio de Inteligencia Artificial desarrollado en Python, encargado del procesamiento de lenguaje natural, generación de embeddings y RAG (Retrieval-Augmented Generation) para Foxy.

---

## Responsabilidades del Módulo

1. **Ingesta y Extracción de Documentos**: Extracción de texto a partir de archivos PDF, imágenes o notas entregadas por los usuarios.
2. **Generación de Embeddings**: Vectorización de contenido textual e interacción con PostgreSQL (`pgvector`) para búsquedas de similitud.
3. **Pipeline de RAG**: Recuperación de información relevante según el perfil del usuario y el material subido.
4. **Integración con API AI**: Conexión abstraction-layer con proveedores de LLM (Gemini, OpenAI, etc.) para inferencia y razonamiento.

---

## Funciones Principales

- **Generador de Planes de Estudio**: Creación de rutas de aprendizaje estructuradas según temas y documentos del estudiante.
- **Generador de Flashcards y Cuestionarios**: Extracción automática de conceptos clave para la creación de pruebas autodidactas.
- **Asistente Pedagógico para Docentes**: Síntesis de planes de clase, búsqueda de fuentes bibliográficas y recomendación de actividades.
- **Motor Adaptativo**: Ajuste dinámico del nivel de dificultad, tono y contenido en respuesta a los insumos del usuario.
