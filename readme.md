# 📉 Análisis de Evasión de Clientes – Telecom X

Este proyecto tiene como objetivo analizar el comportamiento de los clientes de **Telecom X** con el fin de entender las causas detrás de la **evasión (churn)** y proponer estrategias de retención basadas en datos.

## 🧠 Objetivo

Detectar patrones de abandono en los clientes, identificar las variables más influyentes y proponer recomendaciones para reducir la tasa de churn mediante un enfoque de análisis de datos exploratorio.

---

## 🗂️ Contenido

- `TelecomX.ipynb`: Notebook principal con todo el análisis.
- `README.md`: Descripción general del proyecto.

---

## ⚙️ Herramientas y Librerías

- Python 3.x
- Pandas
- Matplotlib / Seaborn
- NumPy
- Scikit-learn (para futuros modelos predictivos)
- Jupyter Notebook

---

## 🧼 Limpieza y Tratamiento de Datos

- Conversión y limpieza de campos como `TotalGasto` (valores nulos y tipo de dato).
- Eliminación de columnas no relevantes.
- Transformación de variables categóricas y numéricas para análisis y visualización.

---

## 📊 Análisis Exploratorio de Datos (EDA)

Se analizaron variables categóricas y numéricas en relación con el estado de abandono (`abandono` = 1):

### 🔸 Variables Numéricas más relevantes

| Variable        | Correlación con abandono | Insight clave |
|----------------|---------------------------|---------------|
| Meses de contrato | -0.344 (moderada negativa) | Clientes nuevos abandonan más. |
| Cargo mensual | +0.190 (débil positiva) | Altos cargos mensuales podrían generar insatisfacción. |
| Cargo total | -0.194 (débil negativa) | Clientes con mayor gasto total tienden a quedarse. |
| Cuentas diarias | +0.190 (débil positiva) | Usuarios intensivos también abandonan. |

### 🔸 Variables Categóricas clave

- Los contratos **mes a mes** tienen tasas de abandono mucho más altas.
- La falta de **servicios complementarios** (respaldo, soporte técnico) se asocia con más churn.
- Clientes sin dependientes o con **facturación electrónica** muestran mayor propensión al abandono.

---

## 📌 Conclusiones

- El abandono se concentra en clientes nuevos, con bajo compromiso y contratos flexibles.
- Clientes con cargos mensuales altos y poco historial acumulado presentan mayor riesgo de irse.
- El uso frecuente del servicio no garantiza fidelidad.

---

## ✅ Recomendaciones

- **Fidelización temprana**: Ofrecer seguimiento y beneficios en los primeros meses.
- **Incentivos a largo plazo**: Promover contratos anuales mediante descuentos y beneficios exclusivos.
- **Mejora de la experiencia**: Monitorear usuarios intensivos para brindar soporte proactivo.
- **Revisión de precios**: Evaluar si los clientes con tarifas altas perciben suficiente valor.

---

## 🚀 Futuro

El siguiente paso será construir un **modelo predictivo de churn** usando algoritmos de machine learning (Logistic Regression, Random Forest, XGBoost, etc.) para anticipar abandonos y tomar decisiones proactivas.

---

## ✍️ Autor

**Wilmer Lozano**  
[Data Analyst Portfolio](https://wlozanoh.github.io/WilmerLozano-Data-AnalystPortfolio/)  
📍 Perú  
🔗 [GitHub](https://github.com/WLozanoH)

---

## 📎 Licencia

Este proyecto se distribuye bajo la Licencia MIT. Puedes reutilizarlo libremente citando la fuente.
