# Examen-Parcial-1-Big-Data-5B 
### Novelo Espadas Esteban Andrés
### Pat Chim Marco Antonio
### Pérez Rodríguez Rosa Ivette
## HomeWeather
## Descripción General
## El siguiente documento consta sobre la documentación del proyecto IoT "HomeWeather" en el cuál se redacta el propósito y funcionamiento del mismo
### Propósito
### El kit "HomeWeather" proporciona un equipo sofisticado de automatización, a traves de internet enviando datos recopilados de los sensores, que realiza acciones sin intervención del usuario, desde accionar ventanas, encender lámparas, ventiladores o cualquier equipo que el usuario desee.
## Diagrama de flujo de información
![flujograma](img/diagramaflujo.png)
## 5V's de Big Data
## - Volumen
### Nuestro proyecto, al enviar los datos sensados de los dispositivos al servidor, el volumen se vuelve masivo porque los datos son recopilados y enviados en internet por medio del dispositivo NODEmcu ESP8266.
## - Velocidad
### Los datos almacenados del senso son procesados de manera rápida y devueltos al dispositivo NODEmcu para la toma de decisiones, que es el proceso principal de la autmatización.
## - Valor
### El proyecto recopila datos sobre el estado del tiempo, temperatura, humedad, intensidad de luz, datos valiosos para el análisis y forma de trabajar del dispositivo final.
## - Veracidad
### Nuestra forma de comprobar la veracidad de nuestros datos es a traves de la repetición constante de los datos, ya que los sensores envian información cada 20 segundos, de igual manera, el constante mantenimiento de los sensores y equipos ayuda a que los datos no fallen o puedan ser incorrectos.
## - Variedad
### Al momento de que el módulo NODEmcu recopila la información, dicha información se almacena de forma numérica, después del proceso de encapsulación, la manda en forma de texto e la base de datos alojada en el servidor, dicha información, cuando es presentada de forma gráfica puede ser descargada en formato de Excel para un mejor análisis.
## Diagrama ETL
## Extracción de la información
### Los datos que serán recopilados en el proyecto, se obtienen de los diferentes sensados con respecto a los cambios meteorológicos, el sensor DTH-22 nos propociona la información sobre el estado actual de la temperatura y la húmedad del ambiente, el sensor ARD-355 mide la precipitación con una placa integrada, y el sensor GY-302 mide los valores de la intensidad lumínica, estos datos son enviados a la base de datos, a traves de la pagina web administrativa se pueden realizar consultas con la API integrada a esta.
## Transformación de la información
### Con los datos extraidos y analizados por medio la API, la información de la estación meteorológica manda la nueva información recopilada a los actuadores de los dispositivos, como lo podrían ser lámparas, motores para ventanas, etc.
## Carga de la iformación
### La información también puede ser representada por medio de gráficos, estos son llamados por sentencias incluídos en la programación PHP, además de contar con la prestación de las gráficas de Google Charts, ajustando los valores con respecto a nuestro proyecto, en los gráficos se muestra siempre en el eje de las X el tiempo transcurrido, mientras que en el eje de las Y los valores correspondientes de la temperatura, húmedad y luminocidad, la precipitación es representada con un odómetro que indica el nivel de posible precipitación.
