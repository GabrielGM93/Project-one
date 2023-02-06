# Project-one
<p align=center><img src=https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png><p>

# `#RRGGBB` <h1 align=center>¡Bienvenidos a la presentación de mi primer proyecto individual de la etapa de labs! en el rol de un ***Data Engineer***.</h1>

# <h1 align=center> **Labs PROYECTO INDIVIDUAL Nº1** </h1>
Este proyecto tiene como objeto, mostrar las diversas habilidades y destrezas adquiridas y desarrolladas a lo largo de los modulos I, II, III Y IV Concretamente, estos son los temas que hacen referencia directa a la Data Engineering. En ellos alcanzamos suficiencia en el bootcamp,  durante la carrera de Data Science en Henry. Ahora en una nueva etapa el Labs, que recien inicia. Con este proyecto estare presentando lo mejor de mi, no solo con el fin apremiante de aprobar para obtener una calificación con una amplia suficiencia en el tema,  Mas bien demostrar en este rol, los valores, profesionalización, entrega, dedicación y buscar como estudiante destacar el nivel de excelencia en el código requerido, además de las habilidades blandas como empatia y busqueda de la comprensión del trabajo propuesto es la unica forma de tener una excelente interpretación de código a nivel requerido para el desarrollo de la tarea como Data Engineer.
# <h1 align=center> **Area de Proyecto Data Engineering** </h1>
Objetivo del Proyecto: Es simular el entorno de trabajo de un Data Engineer, debiendo realizar tareas inherentes al puesto. Aplicar criterio para realizar el EDA y la utilización de las herramientas. Desarrollar un código prolijo, ordenado, eficiente y comentado. Desarrollar habilidades de aprendizaje en el uso de APIs, Docker y el deployment en Mogenius. Todo lo anterior dentro del marco de tiempo de una semana laboral, debiendo respetar lineamientos para la entrega y posterior presentación de los resultados. Ademas desarrollamos prácticas que integran los contenidos vistos en el bootcamp para facilitar la  adquisición de las habilidades técnicas y de soft skill que se exigen en el mercado laboral.

# <h1 align=center> **I PARTE :** Transformaciones y Tratamientos de datos </h1> 

como el analista de datos requiere estas, y solo estas, transformaciones para sus datos:

En primer lugar generare el campo campo id: según se requiere para cada id que se compondrá de la primera letra del nombre de la plataforma, seguido del show_id ya presente en los datasets (ejemplo para títulos de Amazon = as123) 

## Aplicando:

### a) El Importar librerías para manipular los datos
`Libreria Pandas y la libreria Numpy`

En esta descripción el codigo comienza con estas dos líneas que no son Mostradas, Cualquier otro módulo utilizado si fuera el caso lo cual lo comento como ejemplo debe importarse explícitamente, uno por línea y evitar alias. Evitar importaciones excesivas, pero si es necesario, importaciones de La biblioteca estándar va primero, seguida de las bibliotecas de terceros (como matplotlib). este tipo de consideracion habla de Prolijidad en el código que realizamos.

### b) Ingestaré los archivos csv para verificar estructura, con los comandos:
`df = pd.read_csv('xxxxx.csv')`
`df`

`datos = pd.read_csv('xxxxx.csv')`
`datos.info()`

### c) Luego
`Hacemos la asignacion de variable y las transformaciones para sustituir los valores, generar campo id con el formato requerido (Amazon = as123), utilizando y aplicando basicamente el metodo ".astype('str')" a las columnas que realmente precisamos`

# <h1 align=center> **+ Transformaciones, maturity rating: “general for all audiences"** </h1> 
`Los valores nulos del campo rating los reemplazare por el string “G” (corresponde al maturity rating: “general for all audiences con el siguiente metodo:`

`df = pd.read_csv('amazon_prime_titles-score.csv')`

`df.fillna({"rating" : "G"})`

# <h1 align=center> **+ Tratamientos de datos / Formato fecha AAAA-mm-dd**</h1>
`Las fechas, existentes serán tratadas y transformadas y luego todas tener el formato AAAA-mm-dd en el cual aplique el metodo: pd.to_datetime de la siguiente manera expuesta en el ejemplo a continuación`

`amazon['date_added'] = pd.to_datetime(amazon['date_added'], infer_datetime_format=True, errors='coerce')`

`amazon['date_added'].head()`

# <h1 align=center> **Transformaciones / Nuevos Campos**  </h1>
`El campo duration debe convertirse en dos campos: duration_int y duration_type. El primero será un integer y el segundo un string indicando la unidad de medición de duración: min (minutos) o season (temporadas) aplicando selección de columnas en el dataframe e implementado los metodos:  aplicando metodo str.split() / .tolist() / .head() respectivamente`

# <h1 align=center> **Transformacion de datos / todos los datos en minusculas** </h1>
`Los campos de texto deberán estar en minúsculas, sin excepciones   aplicando metodo str.lower()`



# <h1 align=center> DATA ENGINEER **Nelson Alejandro Castro Andrews** </h1>
## <h1 align=center> XD Sin dejar la empatia a un lado, hasta aqui la primera parte del proyecto individual</h1>
<p align=center><img src="https://i.ytimg.com/an_webp/o-_xr4jgZbs/mqdefault_6s.webp?du=3000&sqp=CIjchJ8G&rs=AOn4CLBSit2Ow0I1_XhDcNUvOAx4GkwamQ"<p>

  
<p align=center> Link (https://youtu.be/watch?v=o-_xr4jgZbs) <p>
# <h1 align=center>**`Data Engineering`**</h1>

<p align="center">
<img src="https://files.realpython.com/media/What-is-Data-Engineering_Watermarked.607e761a3c0e.jpg"  height=300>
</p>


