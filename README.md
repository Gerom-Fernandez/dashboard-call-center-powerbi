# 📞 Dashboard Call Center — Power BI

> **Proyecto de Analista de Datos | Análisis de experiencia de clientes en atención telefónica**

---

## 🏢 Contexto del Proyecto

Análisis completo de un **call center de atención al cliente** a partir de datos de llamadas, tiempos de respuesta, calificaciones y reviews escritas por los usuarios.

El objetivo fue entender **dónde se pierde la satisfacción del cliente** y **qué variables influyen más en la calificación final** de la atención.

---

## 🎯 Preguntas de Negocio

| # | Pregunta |
|---|---|
| 1 | ¿De qué se quejan los clientes cuando escriben una review? |
| 2 | ¿Cómo fluyen las llamadas desde su origen hasta su resolución, y en qué etapa se pierde satisfacción? |
| 3 | ¿Qué variables afectan más la calificación final de la atención? |

---

## 📊 Estructura del Dashboard

El reporte tiene **3 páginas**, cada una enfocada en un tipo de análisis distinto.

### Página 1 — Nube de Palabras
- Análisis de **texto libre** a partir de las reviews de clientes
- Las palabras más repetidas fueron **"seguimiento"**, **"espera"**, **"tiempo"** y **"esperar"**
- Hallazgo: el principal punto crítico de la experiencia son los **tiempos de respuesta**
- Datos no estructurados transformados en insights accionables

### Página 2 — Diagrama Sankey
- Flujo completo de las llamadas: **origen** (consultas, llamadas y quejas) → **destino** (solución satisfactoria, derivación a supervisor o solución insatisfactoria)
- Permite identificar en qué etapas del proceso se generan más problemas o pérdida de satisfacción

### Página 3 — Performance con IA
- Uso del **análisis de influencia automática** (Key Influencers) de Power BI para detectar qué variables afectan más la calificación
- Árbol de descomposición para profundizar en los factores
- **Resultado destacado:** cuando el representante es **PDC** y la llamada supera los **42 minutos**, la calificación promedio disminuye en **5,39 puntos**

---

## 🛠️ Stack Utilizado

| Herramienta | Uso |
|---|---|
| Power BI | Modelado y construcción del reporte |
| DAX | Medidas y cálculos |
| Visuales personalizados | Word Cloud y Sankey |
| IA de Power BI | Key Influencers y árbol de descomposición |

---

## 📁 Archivos del Repositorio

| Archivo | Descripción |
|---|---|
| `Proyecto Día 6.pbix` | Archivo de Power BI con las 3 páginas del reporte |

---

## 📌 Aprendizajes

- El análisis de datos no se trata solo de números o gráficos: también implica **comprender el comportamiento de las personas**
- Los datos no estructurados (texto libre) pueden revelar problemas que los KPIs numéricos no muestran
- El diagrama Sankey es ideal para visualizar flujos de procesos y detectar dónde se "pierden" casos
- Las herramientas de IA de Power BI ayudan a priorizar qué variables atacar primero

---

## 👤 Autor

**Gerom Fernández** — Analista de Datos Junior | Ingeniero en Informática
📍 Santiago, Chile · [LinkedIn](https://linkedin.com/in/gerom-fernandez)
