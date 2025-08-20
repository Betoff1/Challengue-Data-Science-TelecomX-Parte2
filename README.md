# 📊 Proyecto: Telecom X - Churn de Clientes  

## 🔎 1. Introducción  
Telecom X enfrenta un alto nivel de cancelación de clientes (*churn*), lo que representa un impacto significativo en ingresos y retención.  
Este proyecto aplica **técnicas de ciencia de datos** para identificar los principales factores asociados al abandono y proponer estrategias de fidelización basadas en análisis estadístico y modelos predictivos.  

---

## 🎯 2. Objetivo del Proyecto  
- Analizar las variables más influyentes en la cancelación de clientes.  
- Comparar modelos de Machine Learning para predecir el abandono.  
- Proponer estrategias de retención basadas en hallazgos.  

---

## 🛠️ 3. Proceso de Desarrollo  
1. **Exploración y limpieza de datos**: tratamiento de valores nulos, codificación de variables categóricas.  
2. **Balanceo de clases**: se utilizó **SMOTE** para mitigar el desbalance de clientes activos vs cancelados.  
3. **Selección de variables**: mediante correlación y `SelectKBest` se priorizaron las variables más relevantes.  
4. **Modelado predictivo**: se entrenaron tres algoritmos principales:  
   - 🔹 **Regresión Logística**  
   - 🌲 **Random Forest**  
   - 👥 **K-Nearest Neighbors (KNN)**  
5. **Evaluación de desempeño**: métricas utilizadas → Accuracy, Precision, Recall, F1-Score y curva ROC-AUC.  

---

## 💻 4. Software utilizado  
- 🐍 Python 3  
- 📚 Bibliotecas principales:  
  - `pandas`, `numpy` → manipulación de datos  
  - `matplotlib`, `seaborn` → visualización  
  - `scikit-learn` → modelado predictivo y métricas  
  - `imblearn` → balanceo de clases (SMOTE)  

---

## 📈 5. Resultados  
- **Modelo más robusto:** Regresión Logística (AUC ≈ 0.84).  
- Factores más influyentes en el abandono:  
  - ⬆️ Alto consumo de minutos internacionales.  
  - 📞 Número de llamadas al servicio de atención.  
  - 📶 Uso de servicios adicionales (Internet, líneas múltiples).  
  - 💲 Nivel de facturación mensual.  
- Comparación ROC:  
  - Regresión Logística y Random Forest tuvieron desempeños muy similares.  
  - KNN se quedó por debajo (AUC ≈ 0.76).  

---

## 💡 6. Recomendaciones  
- **Optimizar atención al cliente:** reducir el número de reclamos y mejorar tiempos de respuesta.  
- **Estrategias de fidelización:** ofrecer descuentos personalizados a clientes con alta facturación y riesgo de salida.  
- **Promover servicios adicionales** que mejoren la percepción de valor.  
- **Monitorear métricas periódicamente** y recalibrar el modelo con datos nuevos para mantener su efectividad.  

---

## ✍️ 7. Autor  
👤 **Alberto Gonzales**  
