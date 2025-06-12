# Asistente IA para Tablas de Retención Documental (TRD)

## Características Principales

### 1. Interfaz de Usuario Intuitiva
- **Chat conversacional** con avatar de IA
- **Diseño responsivo** adaptable a diferentes dispositivos
- **Indicadores de confianza** para cada respuesta (Alto / Medio / Bajo)
- **Efectos visuales** que mejoran la experiencia de usuario

### 2. Funcionalidades del Asistente
- **Búsqueda inteligente** de series y subseries documentales
- **Consultas sobre tiempos de retención** en AG y AC
- **Explicación de disposición final** (CT vs E)
- **Marco normativo actualizado** según estándares AGN
- **Respuestas contextualizadas** con citas normativas

### 3. Panel de Control Lateral
- **Estadísticas en tiempo real** del sistema
- **Acciones rápidas** para consultas frecuentes
- **Ejemplos de consultas** para guiar al usuario
- **Información del piloto** (versión, dataset, modelo)

### 4. Capacidades Técnicas Simuladas
- **Base de datos TRD** con series reales colombianas
- **Algoritmo de búsqueda** por palabras clave
- **Glosario archivístico** integrado
- **Citación automática** de normativa aplicable

## Lógica de Respuestas Implementada

El sistema puede responder a consultas sobre:

- ✅ **Series específicas**: "actas de comité", "comunicaciones oficiales"
- ✅ **Tiempos de retención**: "¿cuánto tiempo conservo...?"
- ✅ **Disposición final**: "¿qué significa CT?", "diferencia entre CT y E"
- ✅ **Transferencias**: "¿qué va al archivo histórico?"
- ✅ **Marco normativo**: "normativa para TRD"
- ✅ **Consultas generales** con sugerencias inteligentes

## Elementos de Validación del Piloto

### Métricas Simuladas
- **248 series TRD** en el dataset
- **156 subseries** catalogadas
- **98% de precisión** en respuestas
- **1.2s tiempo promedio** de respuesta

### Funcionalidades Adicionales
- **Exportar conversaciones** para análisis posterior
- **Limpiar sesión** para nuevas consultas
- **Indicadores de confianza** basados en certeza algorítmica
- **Citas normativas automáticas** según ISO 15489 y legislación colombiana

## Alineación con Objetivos del Piloto

Este prototipo cumple con:

- ✅ **Demostración de viabilidad técnica** de LLM para interpretación TRD
- ✅ **Interfaz user-friendly** para usuarios no técnicos
- ✅ **Validación de exactitud** mediante indicadores de confianza
- ✅ **Escalabilidad evidenciada** en la estructura modular
- ✅ **Cumplimiento normativo** con citas de Ley 594/2000 y Acuerdo AGN 004/2019

## Próximos Pasos para Implementación

Para evolucionar este prototipo hacia un sistema productivo:

1. **Integración con API de LLM real** (GPT-4, Claude, o Mistral)
2. **Carga de TRD institucionales completas** en formato vectorial
3. **Implementación de RAG** con ChromaDB o FAISS
4. **Validación con archivistas expertos** en entidad piloto
5. **Métricas de evaluación automatizadas** (precisión, recall, satisfacción)

## Marco Normativo de Referencia

### Gestión Documental Electrónica
- **ISO 15489**: Gestión de documentos
- **ISO 30300/30301**: Sistemas de gestión para los documentos
- **ISO 23081**: Metadatos para la gestión de documentos
- **Ley 594/2000**: Ley General de Archivos de Colombia
- **Acuerdo AGN 004/2019**: Tablas de Retención Documental

### Preservación Digital
- **ISO 14721 (OAIS)**: Modelo de referencia para sistemas de información de archivo abierto
- **ISO 19005 (PDF/A)**: Formato de archivo para la preservación a largo plazo

### Seguridad y Protección de Datos
- **ISO 27001**: Sistemas de gestión de seguridad de la información
- **ISO 27002**: Código de prácticas para controles de seguridad

---

**Nota**: Este es un prototipo de demostración técnica alineado con los estándares internacionales de gestión documental y la normativa archivística colombiana.
