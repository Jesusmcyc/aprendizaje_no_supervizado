# Reporte de Segmentación de Clientes — RetailMax
**Dirigido a:** Equipo de Marketing  
**Elaborado por:** Jesus Moreno Cruz y Corro  
**Fecha:** Junio 2026  

---

## Introducción

El presente reporte resume los hallazgos obtenidos a partir de un análisis de clustering aplicado a la base de datos de clientes de RetailMax. El objetivo fue identificar segmentos de clientes con características similares en cuanto a edad, ingreso anual y calificación de gasto (Spending Score), con el fin de proporcionar al equipo de marketing información accionable para diseñar campañas más efectivas y personalizadas.

Se utilizó el algoritmo K-Means con cinco clusters como número óptimo, determinado mediante el Método del Codo (Elbow Method). Adicionalmente, se incorporó la variable de género para enriquecer el perfil de cada segmento.

---

## Perfiles de los Segmentos

### Cluster 0 — Clientes Mayores de Bajo Poder Adquisitivo
- **Edad promedio:** 46 años  
- **Ingreso anual promedio:** $26,750  
- **Spending Score:** 18/100  

Este segmento está compuesto por clientes maduros con ingresos bajos y muy poco gasto en la tienda. Su baja calificación de gasto sugiere que compran con poca frecuencia o en montos reducidos.

**Recomendación:** Diseñar promociones orientadas al ahorro, como descuentos por volumen, programas de lealtad con recompensas accesibles y ofertas en productos de primera necesidad. El objetivo es incrementar la frecuencia de visita sin presionar su capacidad adquisitiva.

---

### Cluster 1 — Jóvenes Activos
- **Edad promedio:** 25 años  
- **Ingreso anual promedio:** $41,090  
- **Spending Score:** 62/100  

Clientes jóvenes con ingresos moderados y una disposición relativamente alta al gasto. Son un segmento con potencial de crecimiento significativo conforme aumenten sus ingresos.

**Recomendación:** Enfocar campañas en redes sociales, influencer marketing y experiencias de marca. Ofrecer programas de membresía con beneficios exclusivos para fidelizarlos desde una edad temprana. Las promociones por tiempo limitado y las tendencias de temporada funcionan bien en este perfil.

---

### Cluster 2 — Clientes Premium
- **Edad promedio:** 33 años  
- **Ingreso anual promedio:** $86,100  
- **Spending Score:** 82/100  
- **Composición por género:** 54% mujeres  

Este es el segmento más valioso para el negocio. Clientes jóvenes con alto ingreso y alto gasto. Son los compradores más activos y rentables de la tienda.

**Recomendación:** Invertir en experiencias VIP, acceso anticipado a nuevas colecciones y un servicio al cliente premium. Campañas de lujo accesible, suscripciones exclusivas y eventos privados son altamente efectivos. Este segmento justifica el mayor presupuesto de marketing por su alto retorno de inversión.

---

### Cluster 3 — Alto Ingreso, Bajo Gasto (Oportunidad Estratégica)
- **Edad promedio:** 40 años  
- **Ingreso anual promedio:** $86,100  
- **Spending Score:** 19/100  

Este es el segmento con mayor potencial sin explotar. Tienen el mismo nivel de ingresos que el Cluster 2, pero gastan muy poco. Esto puede deberse a falta de oferta relevante, experiencias previas negativas o simplemente desconocimiento de la propuesta de valor de RetailMax.

**Recomendación:** Este grupo merece una estrategia de reactivación urgente. Se recomienda realizar encuestas de satisfacción para identificar barreras, ofrecer experiencias personalizadas y comunicar beneficios premium que no están aprovechando. Una campaña de retargeting con incentivos específicos podría detonar un incremento significativo en ventas.

---

### Cluster 4 — Clientes Maduros Moderados
- **Edad promedio:** 56 años  
- **Ingreso anual promedio:** $54,380  
- **Spending Score:** 49/100  
- **Composición por género:** 100% hombres  

Clientes de mayor edad con ingresos medios y un gasto moderado y estable. Son compradores predecibles y leales, pero con poca variación en sus patrones de consumo.

**Recomendación:** Campañas de fidelización enfocadas en consistencia y confianza. Comunicación directa vía correo electrónico o medios tradicionales. Productos de calidad duradera y garantías extendidas son argumentos de compra efectivos para este perfil.

---

## Conclusiones

El análisis de clustering reveló cinco segmentos claramente diferenciados con necesidades, comportamientos y potenciales de gasto distintos. La estrategia de marketing de RetailMax debe abandonar el enfoque de campaña única y adoptar una comunicación segmentada que hable directamente al perfil de cada grupo.

La prioridad inmediata debe ser el **Cluster 3**, que representa una oportunidad de revenue significativa con clientes que ya tienen la capacidad económica pero no están siendo activados. En segundo lugar, el **Cluster 2** debe recibir atención continua para mantener y profundizar su lealtad, ya que constituye la base más rentable del negocio.

---

*Análisis realizado con Python (scikit-learn, pandas, seaborn, matplotlib). Dataset: RetailMax (200 registros). Algoritmo: K-Means con k=5, validado mediante Elbow Method.*
