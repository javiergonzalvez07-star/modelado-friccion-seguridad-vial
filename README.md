# Simulación de Seguridad Vial: Influencia de la Adherencia y el Factor Humano

Este proyecto desarrolla un modelo físico-matemático para analizar la probabilidad y gravedad de los alcances vehiculares en distintos escenarios viales (Autovía vs. Zona Urbana). El objetivo principal es evaluar la eficacia de la inversión en infraestructuras de alta adherencia según la velocidad de la vía.

## 🛠️ Stack Tecnológico

* **Lenguaje:** Python 3.x
* **Bibliotecas:** `NumPy` para el modelado matemático y `Matplotlib` para la visualización de datos.
* **Entorno:** Jupyter Notebook / Google Colab.

## 📈 Desafíos Resueltos

### 1. Modelado del "Muro" de Reacción

Se implementó un modelo de frenado que integra el tiempo de reacción humano como una variable crítica. Esto permite visualizar la distancia de seguridad "real" frente a la teórica.

### 2. Análisis de Sensibilidad del Firme ()

Mediante la variación del coeficiente de rozamiento, el estudio identifica los puntos de corte de seguridad en:

* **Escenario Autovía (120 km/h):** Se determinó que se requiere un  para evitar colisiones a 100m.
* **Escenario Urbano (50 km/h):** Se analizó cómo la reducción de velocidad mitiga la dependencia de la calidad del material.

### 3. Optimización de Recursos en Infraestructuras

El proyecto concluye con un análisis coste-beneficio, demostrando que la inversión en pavimentos premium es crítica en vías rápidas, mientras que en zonas urbanas el factor determinante de seguridad es el tiempo de reacción.

## 🧠 Valor Diferencial

Este trabajo no es solo una calculadora de frenado; es un ejercicio de **Ingeniería de Diseño**.

* **Corrección de Modelos:** Se detectaron y corrigieron inconsistencias de unidades (km/h a m/s) para garantizar la validez física del simulador.
* **Abstracción Técnica:** Se incluyeron notas sobre la interacción neumático-asfalto para reconocer las limitaciones del modelo simplificado.


### **Cómo leer este Notebook**

1. **Definición de Funciones:** Modelado de la física de impacto y rozamiento.
2. **Visualización de Escenarios:** Gráficas comparativas de velocidad de impacto vs. .
3. **Conclusiones Técnicas:** Recomendaciones para la gestión de seguridad vial.
