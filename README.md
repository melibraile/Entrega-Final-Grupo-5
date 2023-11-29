![GRUPO 5](https://github.com/melibraile/Entrega-Final-Grupo-5/assets/140036213/862f0410-efd5-424b-8208-00de09ab1a72)
## Integrantes ✒️
* **Mariela Abrego**
* **Melisa Braile** 
* **Tania Damiani**
* **Mariana Grau**
* **Micaela Melian**


## Descripción del proyecto  📌

<p align="justify">
Trabajamos en 2 proyectos:
  
* **Netflix**
En este proyecto trabajamos con datos de la plataforma Netflix. 
Netflix es un servicio de streaming que te ofrece una amplia gama de películas, series y documentales de alta calidad, disponibles en prácticamente cualquier dispositivo conectado a internet.  
El objetivo del proyecto es predecir cuántas semanas va a estar un título top ten en Netflix en las diferentes regiones, teniendo el cuenta el género, el content type y el tipo de estación a la que pertenecen. 
Para el análisis utilizamos un modelo de aprendizaje supervisado.
  
* **Fifa** 
En este proyecto trabajamos sobre datos de Career Mode del videojuego FIFA 15 a FIFA 22. 
El objetivo del proyecto es agrupar a los jugadores en clusters basados en sus características, como la posición, la puntuación general, la edad, el valor de mercado, etc. Este datos se encuentre en la feature overall.El objetivo es analizar esta variable con el valor de venta en euros de los jugadores y comparar resultados. Se analizará cómo estas variables se relacionan con el valor de venta en euros de los jugadores, con el fin de identificar patrones y tendencias que puedan influir en la valoración y comercialización de los jugadores. Para el análisis utilizamos un modelo de aprendizaje no supervisado
</p>

## Datasets 📄

<p align="justify">
  
* **Netflix** El dataset proviene directamente de Netflix. Consta de 2 archivos, uno de ellos con los datos y caracterisiricas de los títulos y series y el otro con información adicional.
 *  netflix_modelo.xlsx: dataset utilizado para los modelos

| Features  | Descripcion |
| ------------- | ------------- |
| region  | indica continente en el cual se proyecta la serie o película  |
| country_name | nombre del país en el cual se proyecta la serie o película  |
| country_iso2  | código ISO del país (Código de dos letras para identificar países según la norma ISO 3166-1)  |
| week | semana en la cuál la película o serie se encontró en el TOP10 |
| category  | indica la clasificación de los títulos en Serie o Película <li>**Movie**</li><li>**Series**</li>   | 
| weekly_rank  |indica la cantidad de semanas que el título estuvo en el TOP10  |
| show_title  | nombre de la serie o película |
| season_title | para el caso de las series indica el título de cada temporada  |
| cumulative_weeks_in_top_10  | cantidad de semanas acumuladas que el título estuvo en el TOP10  |
| Realease Year  | año de lanzamiento de la serie o película |
| Genre | género que identifica la serie o película |   


entorno.xlsx: varios datases con información adicional al dataset principal. Estos dataset aportaron valor al análisis inicial de los datos.



* **Fifa**  El dataset contiene infomración detallada de los jugadores para el Career Mode del videojuego FIFA 15 a FIFA 22. Estos datos permiten realizar múltiples comparaciones para los mismos jugadores a lo largo de las últimas 8 versiones del videojuego.
Los datos se han extraído del sitio web disponible públicamente en sofifa.com.
Se describen a continuación las principales features usadas para el análisis

| Features  | Descripcion |
| ------------- | ------------- |
| sofifa_id  | id |
| player_url| url con la información  |
| short_name  | nombre corto del jugador  |
| long_name | nombre detallado del jugado|
| player_positions  | posición en la que juega <li>**RW - Right Winger (Extremo Derecho)**</li><li>**ST - Striker (Delantero Centro)**</li><li>**CF - Center Forward (Delantero Centro)**</li><li>**CAM - Central Attacking Midfielder (Centrocampista Ofensivo)**</li><li>**CDM - Central Defensive Midfielder (Centrocampista Defensivo)**</li><li>**CM - Central Midfielder (Centrocampista Central)**</li><li>**LM - Left Midfielder (Centrocampista Izquierdo)**</li><li>**RM - Right Midfielder (Centrocampista Derecho)**</li><li>**LW - Left Winger (Extremo Izquierdo)**</li><li>**GK - Goalkeeper (Portero)**</li> | 
| overall  |valoración general o puntaje que se asigna para representar la calidad general del jugador en el videojuego FIFA. Es una medida compuesta que tiene en cuenta múltiples habilidades y atributos del jugador, como velocidad, habilidad con el balón, capacidad de disparo, defensa, entre otros  |
| value_eur | valor de venta del jugador en euros |
| wage_eur  | salario o sueldo que gana el jugador |
| age  | edad del jugador |
| dob | fecha de nacimiento | 
| height_cm  | altura |
| club_team_id| is del club en el que juga  |
| club_name  | nombre del club en el que juega  |
| league_name | liga en la que juega|
| league_level  | nivel de liga   | 

</p>

## Herramientas utilizadas 

<p align="justify">
  ![Jupyter_logo](https://github.com/melibraile/Entrega-Final-Grupo-5/assets/140036213/2459af6b-ffe0-4709-9eeb-fb78dce39375)  Jupiter Notebook
Panda 
Numpy
</p>
