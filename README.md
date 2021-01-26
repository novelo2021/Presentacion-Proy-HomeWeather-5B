# Examen-Parcial-1-Big-Data-5B
## HomeWeather

## Descripción General
## El siguiente documento consta sobre la documentación del proyecto IoT "HomeWeather" en el cuál se redacta el propósito y funcionamiento del mismo
### Propósito
### El kit "Home Weather" proporciona un equipo sofisticado de automatización, a traves de internet enviando datos recopilados de los sensores, que realiza acciones sin intervención del usuario, desde accionar ventanas, encender lámparas, ventiladores o cualquier equipo que el usuario desee.

## Diagrama general de flujo de datos

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
