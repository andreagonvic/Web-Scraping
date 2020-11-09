# Práctica 1: Web scraping
# Acciones más activas de España y su histórico desde Enero 2019

## Descripción
Este repositiorio ha sido creado para realizar la Práctica 1 de la asignatura _"Tipología y ciclo de vida de los datos"_ del Máster en Ciencia de Datos de la _Universitat Oberta de Catalunya (UOC)_.

Este script recoge los datos de las acciones de las cincuenta empresas más activas en la bolsa española, así como el histórico de cada una de ellas desde Enero de 2019.

## Miembros del equipo
La actividad ha sido realizada por *María Dolores Higuera González* y *Andrea González Vicario*.

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
See the [LICENSE](LICENSE.md) file for license rights and limitations (Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License).
