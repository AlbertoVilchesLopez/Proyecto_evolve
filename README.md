# Proyecto_evolve
Proyecto sobre la dependencia en la población Española
# OVERVIEW

https://www.canva.com/design/DAFyF6kBUXE/w10cTbYW8N0NeiWTxkI5ow/edit?utm_content=DAFyF6kBUXE&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

El objetivo de este proyecto es depurar y formatear un conjunto de datos que contiene información sobre la población española y la dependencia en ella.
Posteriormente, analizar los datos para generar visualizaciones que confirmen o refuten hipótesis.


## Estructura del Proyecto

```
├── data/               # Archivos de datos sin procesar y procesados
│   ├── raw/
│   └── processed/
├── images/             # Imágenes de análisis
├── dashboards/         # Archivos de Tableau
├── src/                # Script Python (ETL y Visualiación)
│   └── Estudio.ipynb
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

# DEVELOPEMENT

**1. Existe un envejecimiento en la población Española?**

![scatterplot](https://github.com/AlbertoVilchesLopez/Proyecto_evolve/blob/main/images/Poblaci%C3%B3n_espa%C3%B1ola_desde_1970.jpeg)

As we can see in this plot, the shark attacks have increased in the last century. We can atribute that to different hypothesis. 
1. is that we have more resources to navigate
2. change of weather , although we don't have the data to demonstrate that
3. change on the human life conditions
4. maybe also change in the sense of peril

Let's see the data in another graphic so that we can analize it deeper.

![image](https://github.com/emmacunill/project_em/blob/main/images/hist_attacks_years.png?raw=true)

In this graphic we see only the number of attacks from the 1800 to the actual moment.

To be able to give response on which of our 4 hypothesis is true, we still need to analize deeper.

Let's understand why the sharks are not only not getting, tired, but getting fiercer.




**2. Cuál es el nivel de dependencia en España?**

Shall we take a look at the activities people were doing when the attackes occurred?

The answer is obviously, YES, WE SHALL!! 

![image](https://github.com/emmacunill/project_em/blob/main/images/activities.png?raw=true)

From the data we get from the graphic, we can assume that the great mass of the attacks come from lifestyle. 

Let's get more specific and see only data on the activities from the last 50 years.

![image](https://github.com/emmacunill/project_em/blob/main/images/activities_years.png?raw=true)

In perspective, we can see a decrease on the maybe considered more "survival" colum, fishing. And an increase of the "surf" column. But what also caught my attention is the shark interacting accidents has neither decreases or increases, so I want to check if that is because they are mostly concentrated recently or they're equally divided throughout the years.

![image](https://github.com/emmacunill/project_em/blob/main/images/shark_int_years.jpg?raw=true)

We can see that most of the shark interacting attacks are on increase in recent years. So maybe the hypothesis that the sense of peril has changed might also be true. Also meaning that humans are getting more annoying. 

But is it all humans or just a fraction?



**3. Sería necesario buscar una solución minimizar los problemas de la dependencia en España?**

Let's prove the obvious answer, that we're not going to say."

First let's check how the attacks over the years get distributed against the gender of the victims. 

Is it always more or less the same pattern or is it diverse?

![image](https://github.com/emmacunill/project_em/blob/main/images/years_sex.jpg?raw=true)

As we can see from the plot, men have always been the winners of getting attacked by sharks.

Now let's also check if we can extract more information from the age and the gender. 

Is it just a fase, or are they like that?

![image](https://github.com/emmacunill/project_em/blob/main/images/sex_age.png?raw=true)

We can see from this box plot that between men and women, women number of attacks tend to be more stable along the age, the min and the max are more distant and the 50% of the data is also wider, meaning the data is more stable. Whilst men tend to be attacked by sharks on a more concentrated range of age.

Maybe that has something to do with the activities that men and women are doing when the attacked happens.

![image](https://github.com/emmacunill/project_em/blob/main/images/sex_activities.png?raw=true)

The men normally do more adrenaline activities, so maybe they also have the peril sense lower and provoke more atacks? Let's see how many of the attacks where provoked between man and women.

![image](https://github.com/emmacunill/project_em/blob/main/images/provoked_sex.jpg?raw=true)

We see that most of the provoked attacks are by men. Let's also check shark interacting, because os sense of peril, to compare men and women participation, to end our hypothesis.

![image](https://github.com/emmacunill/project_em/blob/main/images/sh_int_sex.jpg?raw=true)

At least 75% of the shark interactinc¡g attacks are by men. Let's see how many of them are provoked.

![image](https://github.com/emmacunill/project_em/blob/main/images/type_sex.png?raw=true)



# CONCLUSIONS

Seing that a great number of attacks are provoked, and all the other data we analized: We can definitely say that sharks are not getting tired, they're just getting angrier as we humans change our lifestyle, and become more annoying, by getting more stupid, mostly men.

