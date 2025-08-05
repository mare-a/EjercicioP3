## Análisis de ataques de tiburón 
 
El presente trabajo tiene como finalidad analizar los accidentes por ataque de tiburón en playas de diferentes localidades en varios países. Esto representa un punto de partida para definir estadísticas y modelos que ayuden a describir los riesgos y consecuencias, y posteriormente establecer medidas de seguridad en favor de precautelar la vida de los bañistas.
 
## Integrantes  
 
- María Emilia Aguilar  
- Cristian Israel Calderón  
 
## Dependencias y pasos iniciales  
 
- Dataset: "Ataques de tiburones a nivel mundial"  
- Bibliotecas utilizadas: `pandas`, `matplotlib`, `seaborn`, `plotly.express`, `plotly.graph_objects`  
 
## Información básica del dataset
 
El dataset contiene datos sobre ataques de tiburones registrados a lo largo de la historia, incluyendo fecha, hora, país, ubicación, actividad humana al momento del incidente, tipo de ataque, si fue fatal o no, y especie del tiburón involucrado.
 
## Indicaciones iniciales
 
Se realizó una limpieza inicial para excluir columnas vacías, valores indefinidos y duplicados. Además, se normalizaron los datos en las columnas clave para facilitar su análisis, como en `Fatal (Y/N)` y `Type`.
 
## Análisis por tipo de ataque y fatalidad – Aportes de María Emilia

Como parte del análisis exploratorio, se evaluó la relación entre la intención del ataque (`Type`) y su resultado (`Fatal (Y/N)`), buscando identificar patrones entre ataques provocados y no provocados.

### Observaciones principales:

- Los ataques **no provocados** representan la mayoría de los casos registrados.
- La tasa de fatalidad en ataques **provocados** es menor que en los no provocados.
- En general, la mayoría de los ataques **no fueron fatales**.

### Resumen de hallazgos:

| Tipo de Ataque | Total estimado | Porcentaje Fatales | Porcentaje No Fatales |
|----------------|----------------|---------------------|------------------------|
| No provocados  | 2000+          | ~15%                | ~85%                   |
| Provocados     | 400+           | ~8%                 | ~92%                   |
| Inválidos      | 100+           | ~5%                 | ~95%                   |

## Conclusión general

A través del análisis exploratorio y visual de los datos históricos de ataques de tiburón, se identificaron patrones clave como:

- La mayoría de los ataques no son fatales.
- Los ataques no provocados ocurren con mayor frecuencia en actividades recreativas como el surf o la natación.
- Existen diferencias entre países y años, lo cual permite orientar campañas de prevención específicas.

Gracias al trabajo colaborativo, se logró estructurar un enfoque ordenado que incluye limpieza de datos, visualización gráfica, análisis por tipo de ataque, y generación de conclusiones útiles. Este tipo de ejercicios demuestra el valor del análisis de datos como herramienta para comprender fenómenos reales y proponer soluciones con base empírica.


