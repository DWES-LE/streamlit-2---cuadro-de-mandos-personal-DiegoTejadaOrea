# 馃搱 Cuadro de mandos personal 馃搳
 
> Usa este repositorio para crear un cuadro de mandos personal con Streamlit. Documenta los siguientes apartados del README.
> Incluye en tu README la url de donde has publicado tu aplicaci贸n. Pon la `url` tambi茅n en el `About` de tu repositorio.

## Objetivo
Dise帽o de un cuadro de mandos personal para visualizaci贸n de datos filtrados, que tras la ejecucion muestar en base a unos datos personales el pokemon al que se ajustan los datos introducidos.

## Los datos
Los datos son las caracteristicas de los pokemons:
- Nombre
- Total
- HP
- Attack
- Defense
- Sp. Atk
- Sp. Def
- Speed
- Url_img
- Generation
- Type 1
- Type 2

## B煤squeda de los datos y documentaci贸n de los datos
He escogido los datos de la web https://pokemondb.net/pokedex/all, que es una base de datos de todos los pokemons que existen en la franquicia de videojuegos Pokemon. Para la extraccion de datos he realizado programas de escraping en python, que me han permitido extraer los datos de la web y guardarlos en un archivo csv.

En la carpeta datos estan todos los ficheros de datos que he utilizado en el proceso, el archivo final utilizado para la aplicacion es el archivo `datos_pokemon_actualizados.csv`.

## Prepara tu aplicaci贸n.
La aplicacion se llama `app.py` y en `requirements.txt` tienes las dependencias que necesitas para ejecutarla. Puedes usar `pipreqs` para generar el fichero de dependencias. 

## Carga y an谩lisis de conjunto de dato con pandas
Los datos se van actualizando cada vez que se ejecuta el programa, por lo que no es necesario cargarlos en un dataframe, sino que se cargan directamente en el dataframe. Conforme seleccionas los datos, se van actualizando los datos del dataframe y se muestra el pokemon que se ajusta a los datos introducidos.

## Visualizaci贸n de los datos
El dato final es una imagen del pokemon que se ajusta a los datos introducidos. Pero tambien se muestran los datos del pokemon escritos en la pantalla.

## Dise帽a la interacci贸n que van a tener tus datos
Los filtros estan en el sidebar.
Son mediante un slider para los datos numericos y mediante un selectbox para los datos categoricos.


## Publica la aplicaci贸n.
La app esta desplegada mediante Streamlit Cloud en la siguiente url: 
https://diegotejadaorea-streamlit-2---cuadro-de-mandos-perso-app-tnwf79.streamlit.app/