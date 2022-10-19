# stadium-attendance
Este trabajo trata de un análisis de un conjunto de datos del año 2016, que contiene información general sobre 88 países. Incluye variables como la población, PIB per cápita, nivel de alfabetización, tasas de natalidad y mortalidad, entre otras. Además, contiene datos de carácter futbolístico, como el ranking FIFA de la selección de cada país, asistencia promedio a los estadios en la liga local y el factor de ventaja de equipos locales en la liga. Este último dato hace referencia a que tan probable es que en un partido de la liga doméstica el equipo local obtenga un triunfo.

El dataset contiene valores nulos en varias de sus columnas, como ‘Climate’, ‘Literacy’, ‘Phones’, ‘Birthrate’, ‘Deathrate’, 'UEFA_Rank' y 'Attendance'. 
Para la columna 'Climate' se rellenaron los valores nulos generando promedios de clima para cada región del país respectivo. Los valores nulos de las columnas ‘Literacy’, ‘Phones’, ‘Birthrate’ y ‘Deathrate’, no pudieron ser completados, por lo que esos registros fueron eliminados. La columna ‘UEFA_Rank’ fue eliminada, ya que no era necesaria para el trabajo.
Se generaron dos dataframe, uno con los registros que poseen un valor válido en ‘Attendance’ y otro para los que tienen un valor nulo en dicha columna.
Finalmente, en el dataframe con valores válidos para 'Attendance' se creo una columna nueva llamada ‘ratio_att’, que nace a partir de la división de ‘Attendance’ por ‘Population’.







