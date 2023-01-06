# Power BI Desktop 

# Objetivos

1. Conocimiento principales funciones Power BI Desktop
2. Crear Dashboard
3. Con DAX generar métricas y columnas calculadas


# Descripción general

Power BI es una herramientas de anális de datos y creación de ifnormes de instalación local muy utilizada en Business Intelligence, dentro de las muchas ventajas que ofrece, es que permite conectar, transformar y analizar grandes volúmenes de datos y a partir de estos datos poder construir modelos que se relacionen (relacionales) de forma fácil y automatizada, a su vez poder realizar cálculos complejos de forma rápida y sencilla utilizando DAX, como presentación de resultados permite crear informes de manera personaliza e interactivos, permitiendo realizar analítica avanzada. 

# Recursos
Ruta de aprendizaje [Donde iniciar](https://learn.microsoft.com/en-us/training/powerplatform/power-bi?WT.mc_id=powerbi_landingpage-docs-link)

Comunidad PowerBI [Forums](https://community.powerbi.com/t5/Forums/ct-p/PBI_Comm_Forums)

Galería [Dashboards](https://community.powerbi.com/t5/Data-Stories-Gallery/bd-p/DataStoriesGallery)

Cheat Sheet [DAX](https://community.powerbi.com/t5/Data-Stories-Gallery/DAX-Cheat-Sheet-Success-of-CSS-Selector/td-p/559474)

# Fundamentos de Power BI

## Extracción y Transformación

Como se mencionó anteriormente para la **extracción y transformación** de datos Power BI permite conectarse e importa datos de múltiples orígenes tales como: 

* Archivos planos y carpetas: csv, text, xls, etc.

* Bases de datos: SQL, Access, Oracle, IBM, Azure, etc.

* Servicios en línea: Sharepoint, GitHub, Dynamics 365, Google Analytics, Salesforce, servicio Power BI, etc.

* Otros: Web feeds, scripts R, Spark, Hadoop, etc.

Al completarse la extracción (importación) de datos existen funciones importantes para la **transformación de los datos** que se encuentran distribuidas en las pestañas siguientes:

* Inicio: La pestaña incluye configuraciones generales y operaciones comunes de transformación de datos.

* Transformación: La pestaña incluye herramientas para modificar columnas existentes.

* Agregar columna: ofrece operaciones para crear nuevas columnas como reglas condicionales, operaciones de texto, cálculos, etc.

## Modelo de Datos

Una vez realizados los pasos anteriores podemos iniciar a crear **modelos de datos** entiendace como modelado a preparar los datos par aque estén concectados y puedan usarse de forma conjunta, es decir establecer **relaciones** entre las tablas a utilizar.

Podemos dividir los modelos o esquemas en dos tipos: 

* Modelo en estrella: Hay una tabla central (tabla de hechos) rodeada de otras tablas (tablas de dimensiones)

### ![image](https://user-images.githubusercontent.com/111929312/210885604-bf245365-c437-47ba-ba18-976b9db687dc.png)


* Modelo en copo de nieve: deriva del modelo en estrella donde las tablas de dimensiones se separan en múltiples tablas.

### ![image](https://user-images.githubusercontent.com/111929312/210886144-e678e7c8-c792-4bc5-8eb8-9007db7a3ba5.png)


## Métricas con DAX

DAX es catalogado como un lenguaje de programación utilizado en Power BI con el cual se pueden crear métricas o columnas calculadas y esto poderlo agregar al modelo. La sintaxis es intuitiva y ayuda a generar métricas avanzadas variables, así como cálculos complejos. 

Las columnas calculadas son utilizadas para obtener un valor para cada registro (fila), y las métricas son utilizadas para agregar un valor.

## Visualización de informes

Al momento de visualizar los resultados con gráficas podemos realizarlos desde la **vista de inicio** las herramientas de Power BI nos permitirán añadir gráficas e introducir diferentes datos hasta modificar las gráficas.

* **Páginas del informe:** muestran las diferentes hojas de las que se compone el dashboard.

* **Opciones de visualización:** es el panel principal donde seleccionamos el tipo de grafica que queremos crear.

* **Panel de filtros:** permite configurar los filtros.

* **Campo/Formato/Analytics:** permiten introducir los datos, modificar los campos o añadir análisis, como líneas de tendencia, etc.

* **Panel de datos:** contiene las diferentes tablas, columnas, métricas y columnas calculadas que contiene el informe.

![image](https://user-images.githubusercontent.com/111929312/210890633-8e4be906-051d-42a7-ae36-163564663267.png)


# Proyecto práctico

### 1. Extracción y transformación de datos

Par obtener los datos nos vamos a Inicio > Obtener datos > seleccionamos de las opciones el tipo de archivo a conectar/cargar, en este caso utilizaremos CSV > damos doble click o bien seleccionamos Conectar, nos mostrara el navegador de documentos y seleccionamos nuestro archivo > por ultimo seleccionamos Cargar.

![image](https://user-images.githubusercontent.com/111929312/210902743-fea55a3d-bba0-451f-b224-a6fd104192a4.png)
                                 **--------------------------------------------------**
![image](https://user-images.githubusercontent.com/111929312/210902823-ccc75fb2-4604-41ee-8c7c-39d92b0cb445.png)

En la pestaña de **Transformación de Datos** se abrirá una nueva ventana en la cual tendremos múltiples opciones de transformación dentro de las que podemos mencionar la pestaña **Vista** y las opciones Calidad de columnas, Distribución de columnas y Perfil de columna, estas opciones permitirán claridad de la calidad de los datos por columna y poder decidir qué acciones tomar.  

![image](https://user-images.githubusercontent.com/111929312/210907060-e8025510-87cf-4e84-90c6-df207604c9fb.png)

También es importante conocer el tipo de datos que contiene cada columna, esto lo podemos realizada en la pestaña Inicio > Tipo de Datos

![image](https://user-images.githubusercontent.com/111929312/210907146-938205ee-775d-4d15-978f-e6a037382223.png)

### 2. Modelado de datos
### 3. Generar métricas y columnas calculadas con DAX
### 4. Visualización de datos con informes     


*Referencias 
1) Curso Completo de Power BI Desktop - Coursera Project Network

