# 🤖 Portfolio: Natural Language Processing (NLP) & Large Language Models

Este repositorio centraliza mis desarrollos en **Procesamiento de Lenguaje Natural (NLP)** y **Modelos de Lenguaje Masivos (LLMs)**, estructurados bajo la metodología **CRISP-DM**. 

Más allá de la implementación técnica de arquitecturas avanzadas, este portafolio está diseñado con un enfoque **Data-Driven orientado a negocio**: traducir datos de texto no estructurados en activos estratégicos que optimizan la toma de decisiones, automatizan operaciones críticas y maximizan el valor empresarial.

---

## 💼 El Valor del NLP en el Entorno Empresarial

En el mercado actual, más del 80% de los datos de una empresa (reseñas, correos, minutas, reportes) son no estructurados. Implementar soluciones robustas de NLP permite transformar ese texto libre en ventajas competitivas medibles:

* **Optimización de la Experiencia del Cliente (CX):** El análisis de sentimientos y tópicos a gran escala (como el procesamiento de más de 100,000 reseñas implementado aquí) permite a las empresas identificar puntos de dolor (*pain points*) en tiempo real, reduciendo la tasa de abandono (*churn*) y guiando la mejora del producto o servicio.
* **Eficiencia Operativa y Escalabilidad:** Al migrar de auditorías manuales de texto a pipelines automatizados con Transformers (BERT) o LLMs locales (Gemma 3), las organizaciones reducen drásticamente los tiempos de procesamiento de días a segundos, eliminando cuellos de botella operativos.
* **Privacidad y Reducción de Costos de Infraestructura:** El despliegue de modelos de código abierto en servidores locales o clusters de IA privados mitiga los costos recurrentes de APIs de terceros (como OpenAI) y garantiza el cumplimiento estricto de gobernanza de datos y privacidad (esencial para sectores financieros, legales o de salud).
* **Sistemas de Recomendación Inteligentes:** Al extraer el contexto semántico profundo de las opiniones de los usuarios, se pueden construir motores de recomendación hiper-personalizados que impactan directamente en el incremento del ticket promedio y la fidelización.

---
## 🛠️ Stack Tecnológico General
- **Lenguajes & Entornos:** Python (Google Colab, Jupyter Notebooks), Linux (Ubuntu/Pop!_OS).
- **Librerías Core de NLP:** Hugging Face (`transformers`), Spacy, NLTK, Scikit-learn.
- **Modelos & Arquitecturas:** BERT, Gemma 3 (vía Ollama), Word2Vec, TF-IDF.
- **Infraestructura & Datos:** MongoDB, Pandas, NumPy, Docker, Proxmox (AI Clusters).

---

## 📂 Proyectos Incluidos

A continuación se detallan los notebooks y desarrollos incluidos en este portafolio:

### 1. Análisis de Sentimientos y Tópicos a Gran Escala (Gemma 3 + MongoDB)
* **Carpeta / Archivo:** `[Enlace a tu notebook o carpeta]`
* **Descripción:** Procesamiento, limpieza y análisis de más de 100,000 reseñas de hospedajes. Implementa un pipeline local para identificar la polaridad del texto y agrupar las principales quejas o sugerencias de los usuarios.
* **Enfoque Técnico:** Orquestación con MongoDB para almacenamiento eficiente, despliegue local de **Gemma 3 (12B)** mediante Ollama y optimización de prompts para extracción estructurada de entidades.

### 2. Clasificación Avanzada de Texto con Arquitecturas BERT
* **Carpeta / Archivo:** `[Enlace a tu notebook o carpeta]`
* **Descripción:** Modelo predictivo diseñado para clasificar texto complejo basado en contextos semánticos profundos.
* **Enfoque Técnico:** Fine-tuning de un modelo basado en **BERT** utilizando PyTorch/Hugging Face, manejo de embeddings densos y optimización de hiperparámetros para mitigar el sobreajuste (*overfitting*) en datasets desbalanceados.

### 3. Minería de Texto Clásica y Procesamiento Base (EDA)
* **Carpeta / Archivo:** `[Enlace a tu notebook o carpeta]`
* **Descripción:** Pipeline de preprocesamiento estándar para la normalización de texto sucio antes de ser introducido a modelos de Machine Learning.
* **Enfoque Técnico:** Tokenización, remoción de *stopwords*, lematización/stemming, vectorización avanzada (TF-IDF, Bag of Words) y reducción de dimensionalidad para visualización de clusters de texto.

---

##  Enfoque Metodológico (CRISP-DM)
Cada proyecto en este repositorio no es solo código; sigue un ciclo de vida orientado a resolver problemas y generar valor:

1.  **Comprensión de los Datos:** Análisis exploratorio inicial (EDA) para entender distribuciones de longitud, palabras más frecuentes y sesgos en los datos.
2.  **Preparación de Datos:** Limpieza rigurosa (remoción de ruido, HTML tags, caracteres especiales y estructuración en bases de datos).
3.  **Modelado:** Evaluación comparativa entre modelos tradicionales (Scikit-Learn) y modelos de última generación (Transformers/LLMs).
4.  **Evaluación:** Uso de métricas estrictas como *F1-Score*, *Precision*, *Recall* y matrices de confusión para validar el rendimiento real.

---

##  Cómo Ejecutar los Proyectos

### Opción: Ejecución Directa en la Nube
Cada notebook (`.ipynb`) incluye un botón superior **"Open in Colab"**. Al hacer clic, se abrirá el entorno de ejecución de Google listo para interactuar con el código. *Nota: Para los proyectos que requieren LLMs locales o bases de datos como MongoDB, consulta las instrucciones específicas dentro de su sección.*

