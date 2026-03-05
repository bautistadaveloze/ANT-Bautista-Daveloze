# 🧠 Aplicaciones Reales de Machine Learning

A continuación se presentan cinco productos reales que utilizan Machine Learning, explicando su aplicación, el tipo de aprendizaje que emplean y los datos necesarios para su funcionamiento.

---

# 🎬 Caso 1 — Netflix

## 🔹 Aplicación
Sistema de recomendación personalizado de películas y series.

## 🔹 Problema que resuelve
Ayuda a cada usuario a encontrar contenido relevante según sus gustos, mejorando la experiencia dentro de la plataforma.

## 🔹 Enfoque de ML
**Aprendizaje Supervisado**

**Justificación:**  
El sistema se entrena con datos históricos de comportamiento (contenido visto, calificaciones, tiempo de reproducción) para predecir futuras preferencias.

## 🔹 Datos utilizados
- Historial de visualización  
- Calificaciones otorgadas  
- Tiempo de reproducción  
- Búsquedas realizadas  
- Datos demográficos anónimos  

---

# 📧 Caso 2 — Gmail

## 🔹 Aplicación
Filtro automático de correos spam.

## 🔹 Problema que resuelve
Clasifica correos electrónicos para evitar que mensajes no deseados lleguen a la bandeja principal.

## 🔹 Enfoque de ML
**Aprendizaje Supervisado**

**Justificación:**  
El modelo se entrena con millones de correos previamente etiquetados como “spam” o “no spam”.

## 🔹 Datos utilizados
- Texto del mensaje  
- Dirección del remitente  
- Enlaces incluidos  
- Archivos adjuntos  
- Acciones del usuario (marcar como spam)  

---

# 🚗 Caso 3 — Uber

## 🔹 Aplicación
Predicción de demanda y sistema de precios dinámicos.

## 🔹 Problema que resuelve
Optimiza la asignación de conductores y ajusta tarifas según la oferta y demanda en tiempo real.

## 🔹 Enfoque de ML
**Aprendizaje Supervisado + Aprendizaje por Refuerzo**

**Justificación:**  
- Supervisado: utiliza datos históricos de viajes para predecir demanda futura.  
- Refuerzo: ajusta decisiones dinámicamente en función de resultados obtenidos (ejemplo: reducir tiempos de espera).

## 🔹 Datos utilizados
- Historial de viajes  
- Ubicación GPS  
- Fecha y hora  
- Condiciones de tráfico  
- Clima  
- Conductores disponibles  

---

# 🛒 Caso 4 — Mercado Libre (Argentina)

## 🔹 Aplicación
Sistema de recomendación y detección de fraude.

## 🔹 Problema que resuelve
- Sugiere productos personalizados.  
- Identifica transacciones sospechosas para prevenir fraudes.

## 🔹 Enfoque de ML
**Aprendizaje Supervisado**

**Justificación:**  
Se entrena con datos históricos de compras y fraudes detectados para predecir comportamientos futuros.

## 🔹 Datos utilizados
- Historial de compras  
- Búsquedas realizadas  
- Información de transacciones  
- Ubicación del usuario  
- Tipo de dispositivo  
- Patrones de comportamiento  

---

# 🏥 Caso 5 — DASA (Brasil)

## 🔹 Aplicación
Interpretación automática de prescripciones médicas.

## 🔹 Problema que resuelve
Digitaliza recetas médicas y mejora la eficiencia del sistema de salud.

## 🔹 Enfoque de ML
**Aprendizaje Supervisado + Procesamiento de Lenguaje Natural (NLP)**

**Justificación:**  
Se entrena con ejemplos de recetas correctamente interpretadas para reconocer texto médico y medicamentos.

## 🔹 Datos utilizados
- Texto de recetas médicas  
- Etiquetas con interpretaciones correctas  
- Base de datos de medicamentos  
- Datos anonimizados de pacientes  

---

# 📊 Síntesis Comparativa

| Empresa        | Aplicación Principal                     | Tipo de ML |
|---------------|-------------------------------------------|------------|
| Netflix       | Recomendación de contenido                | Supervisado |
| Gmail         | Clasificación de spam                     | Supervisado |
| Uber          | Predicción de demanda y precios dinámicos | Supervisado + Refuerzo |
| Mercado Libre | Recomendaciones y detección de fraude     | Supervisado |
| DASA          | Interpretación de recetas médicas         | Supervisado + NLP |

---

> En todos los casos, el Machine Learning permite analizar grandes volúmenes de datos para mejorar decisiones, personalizar servicios y optimizar procesos.