# Práctica 1: Web scraping
# Acciones más activas de España y su histórico desde Enero 2019

## Descripción
Este repositiorio ha sido creado para realizar la Práctica 1 de la asignatura _"Tipología y ciclo de vida de los datos"_ del Máster en Ciencia de Datos de la _Universitat Oberta de Catalunya (UOC)_.

Este script recoge los datos de las acciones de las cincuenta empresas más activas en la bolsa española, así como el histórico de cada una de ellas desde Enero de 2019.

## Miembros del equipo
La actividad ha sido realizada por *María Dolores Higuera González* y *Andrea González Vicario*.

## Explicación de ficheros
En este repositorio encontramos:

* Este archivo de texto *README* en el que se explica la estructura general de la entrega.
* Una carpeta *Files* que contiene la colección de archivos .csv generados.
* Un archivo *script_web_scraping.ipynb* con el código de ejecucion del scrapeo web.
* Un archivo de texto *LICENSE* que describe la licencia escogida.

## Prerrequisitos 
Para poder ejecutar el programa que extrae la información deseada es necesario hacer ciertas instalaciones antes.

- Son necesarias las siguientes bibliotecas:

  ```
  pip install pandas
  pip install requests
  pip install re
  pip install beautifulsoup4
  pip install selenium
  ```

- Además, es necesario descargar la extensión _ChromeDriver_ para el navegador Google Chrome siguiendo los pasos de la siguiente web:
  https://chromedriver.chromium.org/downloads
  
  Para saber la versión de tu navegador Chrome basta con clicar en los 3 puntos del menú superior a la derecha y en Ayuda, Infromación de Google Chrome.
  
  Una vez descargado, se debe dejar la extensión en la ruta que se vaya a determinar en el script.
  
  ```
  # Ejemplo Mac:
  PATH = "/Applications/chromedriver"
  # Ejemplo Windows:
  PATH = "C:\Program Files (x86)\chromedriver.exe"
  ```
  
  
## License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">

See the [LICENSE](LICENSE.md) file for license rights and limitations (<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>).
