# 🔷 Metodología para Desarrollo de LLM Archivístico

## 🔷 Fase 1: Diagnóstico y definición del caso de uso

| Elemento | Descripción |
|----------|-------------|
| **Objetivo** | Identificar problemas archivísticos específicos que puedan beneficiarse del uso de LLM |
| **Actividades** | - Entrevistas a archivistas y responsables de gestión documental<br>- Revisión normativa (Ley 594/2000, ISO 15489, OAIS, etc.)<br>- Análisis de procesos clave y puntos de dolor |
| **Resultado esperado** | Documento de requerimientos funcionales y éticos del LLM |
| **Ejemplo de casos de uso** | Generación de metadatos, clasificación documental, redacción de actas o respuestas a PQR, consulta de normativas archivísticas |

## 🔷 Fase 2: Curación y preparación del corpus documental

| Elemento | Descripción |
|----------|-------------|
| **Objetivo** | Construir un corpus especializado y legalmente seguro |
| **Actividades** | - Recolección de corpus: leyes, acuerdos del AGN, TRD, manuales, metadatos, casos de uso<br>- Anonimización y limpieza de datos<br>- Clasificación temática y lingüística (lenguaje técnico archivístico, español colombiano) |
| **Resultado esperado** | Dataset estructurado para entrenamiento y ajuste fino |
| **Consideraciones clave** | Cumplimiento de normas de protección de datos (Ley 1581/2012), licencia de uso del contenido, representatividad del corpus |

## 🔷 Fase 3: Entrenamiento y ajuste fino del modelo (Fine-Tuning)

| Elemento | Descripción |
|----------|-------------|
| **Objetivo** | Afinar un LLM preexistente con conocimientos archivísticos |
| **Actividades** | - Selección del modelo base (ej. GPT-4, LLaMA, Mistral, Falcon)<br>- Entrenamiento supervisado con prompts archivísticos<br>- Validación cruzada con expertos documentales |
| **Resultado esperado** | Modelo ajustado al dominio archivístico con comportamiento consistente |
| **Indicadores de éxito** | Exactitud en respuestas, nivel de comprensión del lenguaje técnico, capacidad de citar normativa archivística relevante |

## 🔷 Fase 4: Evaluación, validación ética y control de calidad

| Elemento | Descripción |
|----------|-------------|
| **Objetivo** | Validar el modelo bajo criterios técnicos, archivísticos y éticos |
| **Actividades** | - Evaluación funcional: precisión, cobertura, lenguaje inclusivo<br>- Evaluación con usuarios finales (archivistas, gestores documentales)<br>- Panel de revisión ética (transparencia, sesgo, explicabilidad) |
| **Resultado esperado** | Informe de validación técnica y social del LLM |
| **Herramientas de soporte** | Benchmarks especializados (Exact Match, BLEU, ROUGE, criterios semánticos), checklist de sesgos y riesgos éticos |

## 🔷 Fase 5: Despliegue, gobernanza y mejora continua

| Elemento | Descripción |
|----------|-------------|
| **Objetivo** | Implementar el modelo y establecer un marco de gobernanza archivístico |
| **Actividades** | - Integración con SGDEA o portales institucionales<br>- Capacitación a funcionarios en el uso ético del LLM<br>- Mecanismos de retroalimentación y control archivístico<br>- Plan de actualización continua del modelo |
| **Resultado esperado** | Modelo en operación con guía de uso, monitoreo y mejora |
| **Modelo de gobernanza propuesto** | Comité interdisciplinario (archivo, IA, jurídico, ciudadanía), políticas de revisión del conocimiento, límites de uso automatizado |

## 🧩 Opcional: Entregables sugeridos por fase

| Fase | Entregables |
|------|-------------|
| **Diagnóstico** | Informe de necesidades y oportunidades |
| **Corpus** | Dataset documentado y categorizado |
| **Fine-tuning** | Modelo ajustado y validado |
| **Evaluación** | Informe de calidad y riesgos |
| **Despliegue** | Manual de uso, guía de gobernanza, protocolo de actualización |

---
* Autor Jhon Gonzalez jhon.gonzalez@gmail.com
* Esta metodología integra estándares archivísticos internacionales (ISO 15489, ISO 14721-OAIS) con marcos éticos de IA (ISO/IEC 23894, NIST AI RMF) para garantizar el desarrollo responsable de sistemas inteligentes en el dominio archivístico.*
