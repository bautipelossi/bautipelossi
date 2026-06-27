# Bautista Pelossi Schweizer

Estudiante avanzado de Licenciatura en Ciencia de Datos en la [Universidad Nacional del Litoral](https://www.unl.edu.ar/) (Santa Fe, Argentina), con ciclo superior orientado a PLN y aplicaciones estadísticas en Economía y Finanzas. Actualmente en intercambio académico en la [Universidad Complutense de Madrid](https://www.ucm.es/) — Facultad de Informática.

Me interesa el cruce entre **modelos de lenguaje**, **recuperación de información** y **economía del desarrollo**.

📬 [LinkedIn](https://www.linkedin.com/in/bautistapelossi/) · [GitHub](https://github.com/bautipelossi)

---

## Proyectos destacados


### 🤖 LLM causal basado en Transformer  · [`fdi-pln2612/p5`](https://github.com/bautipelossi/fdi-pln2612/tree/main/p5)
> Procesamiento de Lenguaje Natural — UCM, 2026

Implementación completa de un LLM causal construyendo cada componente interno del transformer sin librerías de alto nivel.

- **Tokenizador manual** (sin dependencias de terceros).
- **Embeddings posicionales** + cabezales de **multi-head attention** con matrices Q/K/V.
- Normalización por capas, MLP como bloque de abstracción, y cabeza de clasificación para predicción del siguiente token.
- Preentrenamiento por descenso por gradiente y **generación autorregresiva** de texto.

---

### 🔍 Sistema RAG sobre el Quijote · [`fdi-pln2612/p4`](https://github.com/bautipelossi/fdi-pln2612/tree/main/p4)
> Procesamiento de Lenguaje Natural — UCM, 2026

Pipeline de recuperación de información y generación aumentada (RAG) sobre el corpus completo del *Don Quijote de la Mancha*.

- **Motor 1 — TF-IDF**: índice léxico con vectorización sobre lemas, similitud coseno y deduplicación por párrafo.
- **Motor 2 — Búsqueda semántica densa**: embeddings `tok2vec` de spaCy con score híbrido léxico-semántico.
- **Motor 3 — Pipeline RAG**: combina ambos motores para construir contexto con evidencias referenciadas y genera respuestas mediante LLM local (Ollama); fallback extractivo ante indisponibilidad del modelo.
- Pipeline PLN completo: lematización, eliminación de stopwords, normalización y segmentación en chunks con overlap.

---

### 📊 La Paradoja Argentina: análisis empírico del crecimiento económico
> Métodos Econométricos — UCM, 2026 · [Ver artículo](https://drive.google.com/file/d/1FPVKA4pqANJ_jzrl22yWZDsE7q5RLPfu/view?usp=sharing)

Análisis econométrico de los determinantes del crecimiento argentino en el período 1900–2023.

- Integración y homogeneización de bases macroeconómicas históricas heterogéneas.
- Modelos MCO, ECM y ARIMA/ARIMAX; pruebas de cointegración, causalidad de Granger e instrumentos para endogeneidad.
- Test de Chow para el quiebre estructural de 1930: la inversión en capital físico resultó el único determinante robusto del crecimiento a largo plazo.

---

*Santa Fe · Madrid*
