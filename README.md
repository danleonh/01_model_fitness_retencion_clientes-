# 🏋️‍♀️ Proyecto 1 — Model Fitness: Predicción y Retención de Clientes

## 🎯 Objetivo del proyecto
Analizar el comportamiento de los clientes de una cadena de gimnasios para **predecir la cancelación de membresías** y **proponer estrategias de retención** basadas en datos reales.

---

## 📂 Dataset
El conjunto de datos contiene información sobre los clientes de *Model Fitness*, incluyendo variables demográficas, frecuencia de visitas, duración del contrato y gastos adicionales.

**Columnas principales:**
- `Churn`: indicador de cancelación.
- `Contract_period`: duración del contrato (1, 3, 6 o 12 meses).
- `Lifetime`: tiempo como cliente (meses).
- `Avg_class_frequency_total`: frecuencia media de visitas.
- `Avg_additional_charges_total`: gastos adicionales (cafetería, productos, etc.).

---

## 🧠 Metodología
1. **Análisis exploratorio (EDA):**
   - Limpieza de datos y verificación de valores nulos.
   - Visualización de variables clave (edad, contrato, frecuencia).
   - Matriz de correlación para detectar patrones.

2. **Modelado predictivo:**
   - Modelos aplicados: **Regresión Logística** y **Bosque Aleatorio (Random Forest)**.
   - Evaluación de precisión, recall y exactitud.
   - Comparación de desempeño entre modelos.

3. **Segmentación (Clustering):**
   - Aplicación de **K-Means** para agrupar clientes por perfil de comportamiento.
   - Análisis de los grupos con mayor riesgo de cancelación.

---

## 📊 Resultados principales
- El modelo de **Bosque Aleatorio** logró una **precisión del 84 %** en la predicción de cancelaciones.
- Se identificaron **3 clústeres principales**, siendo uno de ellos el grupo con mayor tasa de abandono (clientes con contratos cortos y baja frecuencia de visitas).
- Las estrategias de retención propuestas incluyeron:
  - Promociones a clientes con baja frecuencia.
  - Descuentos por renovación temprana.
  - Comunicación personalizada basada en hábitos detectados.

---

## 🧰 Tecnologías utilizadas
| Herramienta | Uso principal |
|--------------|----------------|
| **Python** | Análisis y modelado |
| **Pandas / NumPy** | Limpieza y manipulación de datos |
| **Matplotlib / Seaborn** | Visualización de datos |
| **Scikit-learn** | Modelado predictivo y clustering |
| **Jupyter Notebook** | Desarrollo y documentación del análisis |

---

## 📎 Archivos del repositorio
| Archivo | Descripción |
|----------|--------------|
| `notebooks/proyecto_1_model_fitness.ipynb` | Análisis completo |
| `data/gym_churn_us.csv` | Dataset procesado |
| `requirements.txt` | Librerías necesarias |
| `images/` | Visualizaciones exportadas |

---

## 💡 Conclusiones
El análisis permitió establecer una visión clara del comportamiento de los clientes y validar que la **predicción del churn** puede ayudar a las empresas del sector fitness a optimizar su **retención** y **estrategia comercial**.

---

## ✉️ Autor
**Daniel León**  
Analista de Datos | Negocios Internacionales  
📧 edleojar@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/danieleonh/) 
