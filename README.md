# 📡 Telecom X 2 Challenge

sta segunda parte de Challenge consiste en desarrollar modelos predictivos capaces de prever qué clientes tienen mayor probabilidad de cancelar sus servicios.

---

## 📂 Contenido del Proyecto
- notebooks/: notebooks con el análisis exploratorio y modelos.  
- data/: dataset utilizado para el entrenamiento y validación.  
- results/: métricas y gráficas de resultados.  

---

## ⚙️ Tecnologías Utilizadas
- Python 🐍  
- Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn (Machine Learning)  
- Google Colab  

---

## 🔍 Análisis de Modelos

### Regresión Logística (con normalización)
- *Accuracy*: 80.26%  
- *Recall (clientes que cancelan)*: 54%  
- *F1-Score clase True*: 0.59  
- ✅ Mejor capacidad de identificar clientes en riesgo de churn.  

### Random Forest (sin normalización)
- *Accuracy*: 77.58%  
- *Recall (clientes que cancelan)*: 47%  
- *F1-Score clase True*: 0.52  
- ⚠️ Buen desempeño en la clase "No Churn", pero menos eficaz en detectar cancelaciones.  

*Conclusión:* La *Regresión Logística* es el modelo más adecuado para este caso, aunque ambos requieren mejoras en la predicción de la clase minoritaria.

---

## 📊 Factores Clave que Influyen en la Cancelación

- *Cargos Totales y Mensuales*: Montos más altos incrementan la probabilidad de cancelación.  
- *Antigüedad del Cliente*: Clientes con menor tiempo en la compañía tienen mayor riesgo de churn.  
- *Servicio de Internet (Fibra Óptica)*: Asociado a una mayor tasa de cancelación.  
- *Tipo de Contrato*: Contratos de dos años reducen significativamente el abandono.  
- *Método de Pago (Cheque Electrónico)*: Relacionado con mayor propensión a cancelar.

---

## 🛡️ Estrategias de Retención

- *Contratos a Largo Plazo* → descuentos y beneficios por migrar de contratos mensuales a anuales.  
- *Fidelización de Clientes Nuevos* → programas de bienvenida, encuestas tempranas y seguimiento personalizado.  
- *Mejora del Servicio de Fibra Óptica* → encuestas de satisfacción y soporte especializado.  
- *Optimización de Métodos de Pago* → fomentar pagos automáticos y reducir cheques electrónicos.  
- *Planes Flexibles* → revisar cargos mensuales y ofrecer opciones personalizadas.   

---

## 👩‍💻 Autor
Proyecto desarrollado por Abigail Romo como parte del Telecom X Challenge.
