README TFM SEBASTIÁN ALONSO DE LA FUENTE CHÁVEZ

Tenemos 3 tipos de archivos.

CUADERNILLOS SCRAPPERS:
	
	- Scrapper_Historical_and_Individual_Stats_UltimateTennisStatistics.ipynb: Es el script que obtiene las estadísticas históricas de cada jugador  de manera individual y lo guarda en un CSV llamado ‘tennis_players_historical_and_individual_stats.csv’.

	- Scrapper_Rivalries_Top100_Stats_UltimateTennisStatistics.ipynb: Es el script que obtiene las estadísticas históricas de cada jugador del top 100 en sus enfrentamientos contra sus mayores 75 rivales (contra los que más partidos ha jugado) y lo guarda en un CSV llamado ‘tennis_players_rivalries_stats_top100.csv’.

CUADERNILLOS ENTRENAMIENTOS: 

	- Entrenamiento_Estadísticas_Históricas_Individuales.ipynb: Es el cuadernillo que entrena los diferentes modelos de regresión y redes neuronales usando como fuente de datos el CSV ‘tennis_players_historical_and_individual_stats.csv’.

	- Entrenamiento_Estadísticas_Históricas_Rivalries.ipynb: Es el cuadernillo que entrena los diferentes modelos de regresión y redes neuronales usando como fuente de datos el CSV ‘tennis_players_rivalries_stats_top100.csv’.

CSV: 

	Como ya hemos indicado, son la salida de cada uno de los scrappers y alimentan cada uno de los cuadernillos de entrenamiento.

Para hacer funcionar el segundo scrapper correctamente se debe hacer alojar la carpeta de la extensión uBlock-Origin donde se quiere, (se recomienda en la misma ruta donde se aloja el scrapper) e indicar su ruta en el código. Es una extensión bloqueadora de anuncios y pop-ups que se puede cargar en las opciones del driver de selenium para que abra un chrome con esa extensión funcionando.
