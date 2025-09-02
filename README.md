Entrega de Dashboard con la Herramienta Google Sheets.
Este proyecto consiste en la creación de un dashboard interactivo y un análisis exploratorio de datos sobre las ventas globales de videojuegos. Utilizando un conjunto de datos extraído de vgchartz.com, que contiene información sobre videojuegos con ventas superiores a 100,000 copias, se realizó un análisis detallado para identificar los títulos, géneros y plataformas más exitosos a lo largo del tiempo.


Objetivos del Proyecto:

Transformar y limpiar los datos.
Realizar un análisis descriptivo de las ventas globales de videojuegos.
Crear un dashboard interactivo en Google Sheets para visualizar las principales métricas.
Documentar el proceso y destacar los hallazgos clave.


Conjunto de Datos:

El dataset incluye videojuegos con más de 100k ventas globales y contiene:

Rank: Posición en el ranking global.
Name: Nombre del videojuego.
Platform: Plataforma de lanzamiento (ej. PS2, Xbox, PC).
Year: Año de lanzamiento.
Genre: Género del videojuego.
Publisher: Compañía publicadora.
NA_Sales, EU_Sales, JP_Sales, Other_Sales: Ventas por región (millones).
Global_Sales: Ventas globales (millones).

Transformación y Limpieza de los Datos:

Eliminación de registros incompletos.
Conversión de ventas a formato numérico en millones.
Normalización de fechas y depuración de valores inconsistentes.
Unificación de métricas en millones de unidades.

Dashboard:

El dashboard desarrollado en Google Sheets incluye las siguientes visualizaciones:

Ventas por género → Los géneros de Acción (1,827M) y Deportes (1,308M) dominan el mercado.

Ventas por plataforma → La PS2 (1,256M) y PS3 (1,032M) lideran como consolas más exitosas.

Ventas totales por año → Se observa un pico de ventas entre 2007 y 2009, con un declive progresivo a partir de 2010.

Top 10 juegos más vendidos → Lidera Grand Theft Auto V (104M) y Wii Sports (82.74M).

Top 10 juegos menos vendidos → Algunos títulos apenas alcanzaron ventas globales de 0.01M.





Informe y Hallazgos Clave

Tras realizar el análisis exploratorio de los 16,598 registros de videojuegos, se obtuvieron los siguientes hallazgos clave:

Ventas globales totales:
La suma total de ventas globales es de 8,820.35 millones de unidades.
Esto indica la magnitud del mercado analizado y permite contextualizar las ventas individuales de cada videojuego.

Top 5 videojuegos más vendidos (Global_Sales)

Posición	Videojuego	Plataforma	Ventas Globales (millones)
1	Wii Sports	Wii	82.74
2	Super Mario Bros	NES	40.24
3	Mario Kart Wii	Wii	35.52
4	Tetris	GB	35.00
5	New Super Mario Bros	DS	30.80

Plataformas con mayores ventas globales:

Wii lidera el mercado con ventas acumuladas superiores a 2100 millones de unidades.
PS2 y DS también muestran un rendimiento muy alto, superando cada una los 1,500 millones de unidades en ventas acumuladas.

Géneros más vendidos:

Los géneros Acción y Deportes son los que mayor número de unidades vendieron globalmente.
Otros géneros destacados son Plataformas y Shooter, mostrando un fuerte impacto en el mercado global.

Ventas por región:

América del Norte (NA_Sales): 3,100 millones de unidades (aprox. 35% del total global).
Europa (EU_Sales): 2,500 millones de unidades (aprox. 28%).
Japón (JP_Sales): 1,400 millones de unidades (aprox. 16%).
Resto del mundo (Other_Sales): 1,820 millones de unidades (aprox. 21%).

Esto muestra que América del Norte y Europa son los principales mercados, mientras que Japón y el resto del mundo también tienen un peso relevante.

Tendencias a lo largo del tiempo

La mayoría de los videojuegos con mayores ventas se lanzaron entre 2000 y 2010, coincidiendo con la era de plataformas como Wii, PS2 y DS.
Existe una disminución progresiva en las ventas de videojuegos más recientes, probablemente debido a la fragmentación del mercado y la aparición de nuevas plataformas digitales.

Hallazgos adicionales: 

Los videojuegos de marcas consolidadas, como Mario y Tetris, dominan el top de ventas globales.
Las plataformas domésticas (consolas de sobremesa) tienden a tener mayores ventas globales acumuladas que las consolas portátiles o PC.
La venta de videojuegos muestra un patrón regional claro: ciertos títulos venden más en su región de origen, mientras que otros logran un éxito global.

Instrucciones de Uso:
Accede al Dashboard en Google Sheets: https://docs.google.com/spreadsheets/d/1ES2Re-QyYJv0UF3wM02F91uPzk6YFD9RPpkn0_1SvGE/edit?usp=sharing

Explora las diferentes hojas:
Datos Originales
Análisis con Tablas Dinámicas
Dashboard de Visualización
Informe Explicativo

Base de datos utilizada: https://www.kaggle.com/datasets/gregorut/videogamesales/data
