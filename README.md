# Coursera_RAG_work
# Books Recommendation System

Este proyecto tiene como objetivo desarrollar un sistema de recomendación de libros utilizando técnicas de procesamiento de lenguaje natural y aprendizaje automático.

## Descripción

El sistema de recomendación de libros utiliza un modelo de transformadores de oraciones para crear embeddings de descripciones de libros y un cliente de base de datos vectorial para almacenar y buscar estos embeddings. Además, se integra con Azure OpenAI para generar recomendaciones basadas en las consultas del usuario.

## Estructura del Proyecto

- **embeddings.ipynb**: Este notebook contiene el código para cargar los datos de libros, crear embeddings, almacenar los embeddings en una base de datos vectorial y realizar búsquedas basadas en consultas del usuario.
- **books.csv**: Archivo CSV que contiene datos de diversos libros.

## Requisitos

- Python 3.9 o superior
- Pandas
- QdrantClient
- SentenceTransformers
- Azure OpenAI
