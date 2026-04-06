# Reto de Automatización: Semana 4 - Riwi

## Objetivo
Potenciar el flujo de trabajo de la solución implementando un sistema RAG (Retrieval-Augmented Generation) conectado desde n8n, utilizando Supabase como base de datos vectorial para recuperar conocimiento de contexto antes de enviarlo al modelo de lenguaje.

---

## Requisitos del Desafío

### 1. Base de Datos Vectorial en Supabase
- Configurar una base de datos en Supabase y adaptarla para que funcione como una base de datos vectorial (pgvector).
- Crear las tablas y funciones necesarias para almacenar y realizar la búsqueda por similitud (embeddings).

### 2. Chunking y Procesamiento desde n8n
- Configurar un proceso (workflow) en n8n que tome los documentos o la información relevante del proyecto y le aplique un proceso de "chunking" (división de texto en fragmentos más pequeños y procesables).
- Integrar la generación de embeddings para estos fragmentos utilizando la API del LLM o herramientas integradas.

### 3. Implementación del RAG
- Crear el flujo completo del sistema RAG:
  1. Recibir una consulta en el flujo de automatización de n8n.
  2. Transformar la consulta en un embedding.
  3. Recuperar el contexto más relevante desde la base de datos vectorial en Supabase.
  4. Enviar la consulta junto al contexto al LLM configurado.
  5. Retornar la respuesta enriquecida al ambiente final.

### 4. Mantenimiento del Proyecto
- Continuar realizando las ceremonias de la célula (Daily, refinamientos, etc.).
- Asegurarse de que el equipo mantenga ordenado el repositorio en GitHub y un correcto seguimiento de las actividades en el Tablero de Proyectos.

---

## Entregables
1. Código fuente o exportación del workflow en n8n (JSON) encargado del chunking e inserción de datos.
2. Código fuente o exportación del workflow en n8n encargado de la consulta RAG y comunicación con Supabase y el LLM.
3. Esquema SQL o documentación de las tablas vectoriales configuradas en Supabase.
4. Actualización del repositorio con el registro diario continuo.

¡Muchos ánimos elevando la inteligencia de la solución!
