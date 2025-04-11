# Proyecto_evolve
Proyecto sobre la dependencia en la población Española

# OVERVIEW

El objetivo de este proyecto es depurar y formatear un conjunto de datos que contiene información sobre la población española y la dependencia en ella.
Posteriormente, analizar los datos para generar visualizaciones que confirmen o refuten hipótesis.


## Estructura del Proyecto

```
├── data/               # Archivos de datos sin procesar y procesados
│   ├── raw/
│   └── processed/
├── images/             # Imágenes de análisis
├── src/                # Archivo de Tableau
│   └── Proyecto_Alberto_Vlches.twb
├── Estudio.ipynb       # Archivo Python
├── requirements.txt    # Dependencias del proyecto
└── README.md
```


# LIBRARIES USED

- Pandas
- Seaborn
- Matplotlib.pyplot
- Statsmodels

# HYPOTHESIS

**1. Existe un envejecimiento en la población Española?**

**2. Cuál es el nivel de dependencia en España?**

**3. Sería necesario buscar una solución minimizar los problemas de la dependencia en España?**

# PROCESS FOLLOWED

1. Exploración del conjunto de datos y formulación de hipótesis.
2. Limpieza del conjunto de datos.
3. Transformación del conjunto de datos.
4. Creación de elementos visuales para comprobar o refutar la hipótesis.
5. Explicación de los fundamentos y conclusiones.

# DEVELOPMENT

**1. Existe un envejecimiento en la población Española?**


![scatterplot](https://github.com/AlbertoVilchesLopez/Proyecto_evolve/blob/main/images/Poblaci%C3%B3n_espa%C3%B1ola_desde_1970.jpeg)
![scatterplot](https://github.com/AlbertoVilchesLopez/Proyecto_evolve/blob/main/images/Distribuci%C3%B3n_por_edades.jpeg)



El crecimiento de la población española en más de 10 millones desde 1970 enmascara una realidad demográfica preocupante. 
La pirámide poblacional de 2024 revela un descenso significativo de la población joven y adulta (entre los 15 y 47 años) respecto a población anciana. 








**2. Cuál es el nivel de dependencia en España?**


Para que una persona se considere en situación de dependencia, deben concurrir tres condiciones fundamentales:

 1. La presencia de una limitación, ya sea física, intelectual o sensorial, que afecte significativamente sus capacidades funcionales.
 2. La imposibilidad de realizar de forma autónoma las actividades básicas de la vida diaria.
 3. La necesidad de apoyo o asistencia por parte de una tercera persona para llevar a cabo dichas actividades.

Procedemos a ver el porcentaje de población en estado de dependencia por comunidades autónomas: 

![image](https://github.com/AlbertoVilchesLopez/Proyecto_evolve/blob/main/images/Mapa_Espa%C3%B1a_ccaa.jpeg)
![image](https://github.com/AlbertoVilchesLopez/Proyecto_evolve/blob/main/images/Dependencia_por_ccaa.jpeg)



Podemos observar una cantidad preocupante de personas en situación de dependencia en España, desde el 31,55% de la población en 
Castilla y León hasta el 15,37% en Melilla.
Hablamos de entre un 23 y 26% de la población española que se encuentra en situación de dependencia.







**3. Sería necesario buscar una solución minimizar los problemas de la dependencia en España?**


Mediante la técnica de predicción Holt-Winters, se ha estimado la evolución de la población española para el año 2030.

Los resultados muestran una concentración significativa de población en el rango de edad comprendido entre los 40 y los 74 años, lo que evidencia un claro proceso de envejecimiento demográfico.


![image](https://github.com/AlbertoVilchesLopez/Proyecto_evolve/blob/main/images/Predicci%C3%B3n_de_la_poblaci%C3%B3n.jpeg)

A continuación, se presenta una proyección de la densidad de población en España para el año 2030, elaborada a partir de los datos de la Revisión de 2024 de las Perspectivas de la Población Mundial, publicada por el Departamento de Asuntos Económicos y Sociales de las Naciones Unidas. Esta estimación permite visualizar la evolución esperada de la distribución demográfica y anticipar posibles retos asociados al envejecimiento y la concentración poblacional en determinadas franjas de edad.


![image](https://github.com/AlbertoVilchesLopez/Proyecto_evolve/blob/main/images/Poblaci%C3%B3n_en_2030.jpeg)




# CONCLUSIONS

España está experimentando un claro proceso de envejecimiento poblacional. La baja natalidad y la alta longevidad generan una estructura piramidal invertida.

En 2030, la proporción de personas en edad de trabajar (aproximadamente 20–64 años) disminuirá en comparación con la población dependiente. Esto implica un aumento de la tasa de dependencia (número de personas dependientes por cada 100 en edad laboral), lo cual representa un reto para el sistema de pensiones, la sanidad pública y la economía en general.

Será necesario reforzar políticas de natalidad, conciliación familiar, inmigración y envejecimiento activo para mitigar el impacto.

Por otra parte, la inteligencia artificial, bien aplicada, puede transformar este reto demográfico en una oportunidad para redefinir el envejecimiento.


1. Asistentes virtuales y robótica para el cuidado

Robots sociales y asistentes de IA pueden acompañar a personas mayores, recordándoles tomar medicación, ayudando en tareas cotidianas o incluso detectando caídas o situaciones de emergencia.

Esto permite un envejecimiento más autónomo en el hogar, reduciendo la necesidad de residencias o cuidadores a tiempo completo.

2. Diagnóstico predictivo y salud personalizada

Herramientas de machine learning pueden predecir enfermedades crónicas antes de que se manifiesten, facilitando intervenciones tempranas.

Modelos de IA también ayudan a personalizar tratamientos según los perfiles genéticos, metabólicos y clínicos del paciente.

3. Gestión inteligente de recursos sanitarios

Plataformas de IA pueden optimizar la asignación de citas, camas hospitalarias, rutas de ambulancias y distribución de medicamentos, reduciendo la presión sobre el sistema de salud.

Sistemas predictivos pueden anticipar brotes de enfermedades o necesidades de atención geriátrica en zonas concretas.





