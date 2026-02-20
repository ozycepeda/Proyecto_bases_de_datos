# PROYECTO FINAL BASE DE DATOS
Usaremos The Movies Dataset (Kaggle), un conjunto que integra metadatos de ~45,000 películas (estrenos hasta julio 2017) y calificaciones de usuarios para analizar preferencias y construir modelos tipo recomendación. Los metadatos incluyen variables como presupuesto, ingresos, fecha de estreno, idiomas, países/compañías de producción, además de cast/crew y keywords; las calificaciones son en escala 1–5.
El dataset es un ensamble de dos fuentes: TMDB, que provee detalles de películas, créditos y keywords mediante su API abierta, y GroupLens/MovieLens, que provee los ratings y los enlaces de IDs (MovieLens–TMDB–IMDB). Su recolección busca habilitar investigación y proyectos de ciencia de datos, especialmente en análisis de cine y sistemas de recomendación.
Los datos se obtienen desde Kaggle en el repositorio The Movies Dataset. En Kaggle se manejan como un snapshot (archivos estáticos), por lo que no se actualizan con una frecuencia fija dentro de esa publicación, aunque las fuentes originales pueden tener versiones nuevas.
El repositorio incluye archivos como movies_metadata.csv, credits.csv, keywords.csv, links.csv/links_small.csv y ratings_small.csv. En este proyecto trabajaremos principalmente con ratings_small.csv, que contiene 100,000 tuplas (aprox.) y 4 atributos: userId (usuario anónimo), movieId (película), rating (calificación 1–5) y timestamp (fecha/hora en formato UNIX). En este archivo, numéricos: userId, movieId, rating; temporales: timestamp; categóricos: ninguno directo; texto: ninguno. Si se integra con otros archivos, aparecen atributos categóricos y de texto como géneros, idiomas, compañías y keywords.
El objetivo del equipo es usar estos datos para analizar patrones de calificación y desarrollar/validar enfoques de recomendación (p. ej., filtrado colaborativo y, si se enlazan metadatos, recomendación basada en contenido).
Éticamente, aunque los usuarios están anonimizados, las calificaciones reflejan preferencias reales: se debe evitar cualquier intento de reidentificación o cruce con fuentes externas para identificar personas, reportar resultados de forma agregada y reconocer sesgos del dataset (popularidad, usuarios más activos, cobertura desigual por idioma/región), ya que pueden producir recomendaciones que refuercen desigualdades o reduzcan diversidad.

# INTEGRANTES
Alejandro Ozymandias Cepeda Beltran, CU:219451  
Renata Pasalagua Payá, CU:218650  
Mariana Rendón Monroy, CU:217225  
Nicolás Burgueño Rodríguez, CU:218065  
Gerardo Villanueva Vargas, CU:219890  
Paula Fernández Gregorio, CU:218821  