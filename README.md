# Proyecto asignatura Estadística (MAT3) GIN2 Grupos 1 y 3:PARTE 1 y PARTE 2. CUrso 2020-2021

Poned los nombres de los autores

## Contenidos


### 1  Parte 1: Estadística Descriptiva (1 punto sobre 10 de la notafinal. Entregad por Aula Digital antes del 21 de abril)

La proyecto se entrega engrupos de 4 persones. Cada grupo tendrá asignado unnombre de ciudadquepodréis consultar en la página de la asignatura en Aula Digital. La práctica consiste en obtener los datosde la ciudad asignada, correspondientes afebrero de 2020, de la web de Airbnb y redactar un informeutilizando Rmarkdown respondiendo a las siguientes cuestiones1.Cargad en undataframelos datos del ficherolistings.csv(descomprimido a partir delistings.csv.gz). Esta tabla de datos contiene datos sobre muchas variables:

* neighbourhood property_type
* accommodates
* beds
* bedrooms
* bathrooms
* price
* security_deposit
* minimum_nights
* review_scores_rating
* number_of_reviews
* host_response_time
* requires_license
* review_scores_cleanliness
* cleaning_fee
* etc.

Construid un nuevodata frameque contenga solo la información relativa a como mínimo3 variables no numéricas y 7 variables numéricas.  Hay queescoger forma obligatorialas variablesneighbourhoodyprice.  Las variables relativas a precioso (por ejemplo,priceysecurity_deposit)  se  consideran  numéricas,  pero  primero  deben  convertirsea valores numéricos eliminando los símbolos$o€;  por ejemplo utilizando la funcióngsub("pattern=[\\$]",replacement="",x="$10,000"); haced (help(gsub))

### 2. Renombrar las columnas deldataframecon nombres en castellano o catalán.

### 3.Para las variables numéricas, calcular los siguientes estadísticos y mostrar en una tabla los siguientevalores: cantidad de valores no válidos, mínimo, máximo, media, varianza, cuartiles y mediana.

### 4.Para las variables no numéricas, generad las tablas de frecuencias absolutas de cada uno de sus valores.

### 5.Dibujar diagramas de cajas(boxplots) e histogramas de todas las variables numéricas, mostrandoun mínimo de 2boxplotpor fila. Ajustad la altura de los gráficos para que no queden demasiadopequeños.

### 6.Dibuja un diagrama de tarta para una de las variables no numéricas agrupando como “Otros” losvalores que representen un porcentaje inferior al 1% del total.

### 7.Calcular el valor medio de alguna de las variables numéricas según el barrio, de menor a mayor y sintener en cuenta nombres de Barrio incorrectas (""o"N/A").

### 8. Dibuja unboxplotde la variable precio, para los 5 barrios más caros (precio medio más alto) y los 5barrios más baratos (precio medio más bajo), en un mismo diagrama. Losboxplotsdeben indicartambién el valor medio de los datos.9.Para 4 de las variables numéricas dibujar los diagramas de dispersión dos a dos, con colores diferentespara cada barrio ( “neighbourhood”).

### 9.Para 4 de las variables numéricas dibujar los diagramas de dispersión dos a dos, con colores diferentespara cada barrio ( “neighbourhood”).

### 10.Por las mismas variables elegidas en el apartado anterior calcular los coeficientes de correlación dos ados de las variables, sin tener en cuenta los valoresNA.

### 11.Selecciona dos variables numéricas, y para cada una de ellas organiza sus valores en un máximo de 5intervalos con ala funcióncut.

### 12.A partir de los datos en intervalos obtenidos en el apartado anterior construid una tabla de contingenciade las dos variables y dibuja el diagrama de mosaico asociado a la mesa.



Se valorará la claridad y los comentarios de los resultados obtenidos. Si se detectantrabajos copiadosquedaránsuspendidos todos los alumnos implicados. Todas las preguntas se pueden contestar a partirde la información de los manuales de AprendeR1, AprendeR2 y concretamente AprendeR2 tema 8, a parte delos enlaces proporcionados en este documento, y, en general, haciendo búsquedas en internet. También puedebasar su informe en los ejemplos publicados en la web de la asignatura, Además, puede consultar dudas conel resto de los compañeros de curso a través del Foro de la asignatura a Aula Digital o en discord.

El documento en formato .Rmd y el informe en .html o .pdf se debe en la actividad correspondiente delAulaDigital antes del 21 de abril.


