# Jorge Francisco Acosta Alcalá

Backend developer en formación. Ingeniería en Software, últimos semestres.
**Busco prácticas profesionales en un equipo de backend.**

```yaml
focus:      backend, APIs REST, bases de datos, contenedores
languages:  [Java, Python, TypeScript, C#, Kotlin]
frameworks: [Spring Boot, FastAPI, Express, .NET]
data:       [PostgreSQL, pgvector, MongoDB, Redis, H2]
infra:      [Docker, Kubernetes, Linux, Git, AWS Cognito]
testing:    [pytest]
client:     [React, Angular, Flutter]
status:     open_to_internship
```

## Proyecto principal

### [ContextForge](https://github.com/JorgeFaa/ContextForge)

Pipeline RAG con búsqueda híbrida: similitud vectorial (HNSW sobre pgvector) más full-text search de Postgres (GIN + `tsvector`), fusionados con Reciprocal Rank Fusion. Responde citando los fragmentos usados. El LLM es intercambiable (Ollama local o Anthropic).

```
documento -> loader -> chunker -> embeddings -> pgvector
pregunta  -> [vector search | full-text search] -> RRF -> LLM -> respuesta + fuentes
```

`Python` `FastAPI` `PostgreSQL` `pgvector` `sentence-transformers` `Docker` `pytest`

## Más proyectos

- **[Lyceum Backend](https://github.com/JorgeFaa/lyceum-backend)** (en desarrollo): asistente de estudio sobre el pipeline de ContextForge. Apuntes a base de conocimiento consultable, cuestionarios de repaso, JWT multiusuario.
  `FastAPI` `SQLAlchemy` `Alembic` `PostgreSQL` `pgvector`
- **[DataForge](https://github.com/JorgeFaa/DataForge)**: administrador de bases de datos locales sobre Docker, distribuido como AppImage. Spring Boot + H2, cliente de escritorio en Flutter. Variante [API para Postgres](https://github.com/JorgeFaa/DataForge-API) para Docker y Kubernetes.
  `Java 21` `Spring Boot` `Flutter` `Docker`
- **[Soli Librería](https://github.com/JorgeFaa/Soli-Libreria)**: plataforma de libros full-stack. API REST versionada (`/api/v3`), búsqueda paginada con filtros, reseñas, JWT con AWS Cognito.
  `Spring Boot` `Spring Security` `PostgreSQL` `AWS Cognito` `React` `Kotlin`
- **[PersonAPI](https://github.com/JorgeFaa/PersonAPI)**: API REST (usuarios) + servicio SOAP en .NET (personas) que se comunican entre sí. PostgreSQL, MongoDB, caché en Redis, Swagger, manifiestos de Kubernetes.
  `Python` `C# / .NET` `Redis` `Kubernetes`
- **[Velvet Compendium](https://github.com/JorgeFaa/Velvet-Compendium)**: API REST con CRUD completo, Swagger, `docker-compose up`.
  `Node.js` `Express` `MongoDB`

## En curso

Arquitectura limpia · Kubernetes (de escribir manifiestos a operar despliegues) · testing automatizado en APIs de Java · evaluación de búsqueda híbrida y embeddings

---

[jorgefranciscoacostaa@gmail.com](mailto:jorgefranciscoacostaa@gmail.com) · [LinkedIn](https://www.linkedin.com/in/jorge-francisco-acosta-alcal%C3%A1-574986365/)
