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

| Modelo              | Accuracy | Precision | Recall | F1-score |
|---------------------|----------|-----------|--------|----------|
| **Random Forest**   | 0.751    | 0.544     | 0.662  | 0.597    |
| KNN (normalizado)   | 0.732    | 0.516     | 0.645  | 0.573    |
| Árbol de Decisión   | 0.656    | 0.424     | 0.642  | 0.510    |

 **Conclusión parcial:** El modelo **Random Forest** obtuvo el mejor equilibrio entre métricas, destacando en *Recall*, lo que lo convierte en la alternativa más confiable para **detectar posibles cancelaciones**.  

---




---

##  Interpretación de Resultados  

- **Antigüedad baja:** mayor probabilidad de cancelación.  
- **Menor uso o facturación:** refleja una menor percepción de valor.  
- **Alta frecuencia de reclamos:** indicador robusto de insatisfacción.  
- **Edad del cliente:** asociada con el tipo de servicio o nivel de tolerancia.  
- **Tiempo desde último contacto:** la desconexión anticipa posibles cancelaciones.  

---

##  Estrategias de Retención Propuestas  

- **Fidelización temprana:** incentivos para nuevos clientes en los primeros meses.  
- **Segmentación por uso:** identificar clientes de bajo consumo para ofrecer servicios personalizados.  
- **Seguimiento post-reclamo:** activar alertas automáticas y contacto humano tras incidencias.  
- **Campañas proactivas de contacto:** reenganchar a clientes con largos periodos sin interacción.  
- **Optimización de promociones:** ajustar descuentos de acuerdo con el perfil y comportamiento del cliente.  

---

##  Conclusión General  

El análisis demuestra que la cancelación de clientes puede **predecirse con alto nivel de confiabilidad** mediante modelos de *machine learning*, siendo **Random Forest** el de mejor desempeño.  

Este enfoque analítico permite a la empresa **anticiparse a la evasión, aplicar estrategias preventivas y fortalecer la experiencia del cliente**, reduciendo significativamente las pérdidas asociadas al churn.  
