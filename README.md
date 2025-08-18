 #  Análisis de Cancelación de Clientes y Modelos Predictivos

---

## Objetivo del Proyecto  
El presente proyecto tiene como propósito **identificar los factores determinantes en la cancelación del servicio (churn)** y evaluar distintos modelos de *machine learning* para predecir dichos casos. A partir de los resultados obtenidos, se proponen **estrategias de retención basadas en datos** que permitan reducir la evasión y mejorar la satisfacción del cliente.  

---

##  Metodología  

- **Fuente de datos:** archivo depurado con variables transformadas y sin valores nulos.  
- **Modelos evaluados:** Árbol de Decisión, Random Forest y K-Nearest Neighbors (KNN normalizado).  
- **Técnica de balanceo:** *undersampling* para equilibrar las clases.  
- **Métricas consideradas:** *Accuracy, Precision, Recall y F1-score*.  
- **Validación:** conjunto de prueba estratificado correspondiente al **30%** de los datos.  

---

##  Comparación de Resultados  

| Modelo              | Accuracy    | Precision    | Recall    | F1-score    |
|---------------------|-------------|--------------|-----------|-------------|
| **Random Forest**   | 0.745972    | 0.516915     | 0.680927  | 0.587692    |
| KNN (normalizado)   | 0.688152    | 0.442604     | 0.666667  | 0.532006    |
| Árbol de Decisión   | 0.725592    | 0.488158     | 0.661319  | 0.561696    |

 **Conclusión:** Se encontro que el mejor modelo para detectar posibles cancelaciones es el Random Forest ya que fue el mas equilibrado en todas sus metricas.  

---




---

##  Interpretación de Resultados  

1. **Antigüedad del cliente**  
   Los resultados evidencian que los clientes con menor tiempo de permanencia presentan una **mayor probabilidad de cancelación**. Esto sugiere que las fases iniciales del ciclo de vida del cliente constituyen un periodo crítico, en el cual la consolidación de la relación comercial y la generación de confianza resultan determinantes para la retención.  

2. **Nivel de uso y facturación**  
   Se observa que los clientes con **bajos niveles de uso o facturación** tienden a presentar una **percepción reducida del valor del servicio**. Esta situación puede derivar en una menor motivación para mantener la suscripción, lo que incrementa la probabilidad de abandono.  

3. **Reclamos y quejas**  
   Una **alta frecuencia de reclamos** se erige como un **indicador sólido de insatisfacción**. Este hallazgo coincide con la literatura sobre gestión de clientes, que señala la relación directa entre experiencias negativas recurrentes y la decisión de cancelación.  

4. **Edad del cliente**  
   La **edad se asocia de manera diferenciada con la propensión a cancelar**. Este comportamiento podría estar vinculado tanto al **tipo de servicio contratado** como al **nivel de tolerancia frente a problemas operativos o de atención al cliente**.  

5. **Tiempo desde el último contacto**  
   Finalmente, se detecta que una **mayor distancia temporal desde la última interacción con la empresa** constituye un **predictor significativo de cancelación**. Este hallazgo sugiere que la desconexión progresiva entre el cliente y la organización puede anticipar la decisión de abandono.  

---

##  Estrategias de Retención Propuestas  

El análisis de las variables asociadas al abandono de clientes permite identificar patrones relevantes para la comprensión del fenómeno de cancelación:  
En conjunto, estos resultados subrayan la importancia de diseñar **estrategias de retención** orientadas a:  
- Fortalecer la relación durante los primeros meses del ciclo de vida del cliente.  
- Incrementar la percepción de valor mediante un uso activo del servicio.  
- Gestionar de manera eficiente los reclamos para reducir la insatisfacción.  
- Mantener interacciones frecuentes que prevengan la desconexión progresiva.

   

---

##  Conclusión General  

El análisis evidencia que la **cancelación de clientes puede predecirse con un alto grado de confiabilidad** mediante el uso de modelos de *machine learning*, destacando **Random Forest** como el modelo de mejor desempeño.  

Este enfoque analítico permite a la empresa **anticiparse a la evasión**, implementar **estrategias preventivas efectivas** y **fortalecer la experiencia del cliente**, contribuyendo así a una **reducción significativa de las pérdidas asociadas al churn**.  

## Autor del Proyecto  
-**Creado por:** *Edgar Alexander Constanza Jovel*   
-**Rol:** Científico de Datos / Data Scientist  
-**Fecha:** Agosto 2025  
-**Email:** alexconstanza@gmail.com
