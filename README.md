# Análisis de Modelos Predictivos

Este proyecto incluye tres modelos predictivos aplicados a diferentes conjuntos de datos: regresión lineal, regresión logística y árbol de decisión. A continuación, se presenta un resumen del análisis de cada modelo.

## 1. Regresión Lineal
**Error Cuadrático Medio (MSE):**
- Valor: 3.6698
- Interpretación: Indica un ajuste aceptable del modelo, aunque se debe comparar con el rango de precios del dataset para evaluar su efectividad.

**Coeficientes del Modelo:**
- Año del automóvil: 0.3987 (aumento en el precio por cada año adicional).
- Kilómetros recorridos: 0.000015914 (muy poco impacto en el precio).
- Otras variables: Coeficientes negativos (como −2.4605, −4.0072 y −2.8480) sugieren que aumentos en estas características reducen el precio, mientras que 1.3570 indica un impacto positivo significativo.

**Intercepto:**

Valor: −790.7793 (sin sentido práctico en el contexto del modelo, ya que implica un precio negativo).

## 2. Regresión Logística
**Conjunto de Datos:** Se utilizó el dataset de Heart Disease Cleveland UCI para predecir la presencia de enfermedad cardíaca.
**Precisión del Modelo:** 0.82, mostrando que el modelo tiene un desempeño moderado.
**Matriz de Confusión:**
- Verdaderos Positivos: 32 (Enfermedad) y 42 (No Enfermedad).
- Falsos Negativos: 10 (Enfermedad) y 6 (No Enfermedad).
**Reporte de Clasificación:**
- F1-score: 0.80 para la clase 1 (enfermedad) y 0.84 para la clase 0 (sin enfermedad), indicando un buen equilibrio entre precisión y exhaustividad.

**Conclusión:** El modelo es eficaz en la predicción de enfermedades cardíacas, con un rendimiento equilibrado en ambas clases.
