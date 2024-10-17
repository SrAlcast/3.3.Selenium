# 🌦️ Laboratorio 3.3 Selenium: Extracción de Datos Meteorológicos

Este repositorio contiene un Jupyter Notebook diseñado para automatizar la navegación web y extraer datos meteorológicos 🕵️‍♂️ relacionados con cinco municipios aleatorios de una lista proporcionada de España, correspondientes a los últimos 10 meses. El notebook utiliza una combinación de herramientas de web scraping y automatización para recopilar esta información de sitios web meteorológicos.

## 🛠️ Herramientas y librerías utilizadas

El proyecto hace uso de varias librerías populares en Python para la extracción y manipulación de datos, incluyendo:

- **BeautifulSoup**: Utilizada para el scraping de contenido HTML.
- **Requests**: Empleada para hacer solicitudes HTTP y obtener el código HTML de las páginas web.
- **Pandas** y **Numpy**: Para la manipulación y análisis de datos.
- **Selenium**: Para la automatización de la interacción con navegadores web.

## 🚀 Funcionalidades principales del Notebook

1. **📌 Selección aleatoria de municipios**: De una lista de municipios de España, se seleccionan aleatoriamente cinco municipios para extraer sus datos meteorológicos.

2. **🌤️ Extracción de datos meteorológicos**: Se automatiza la navegación para obtener información meteorológica de los últimos 10 meses para cada municipio seleccionado, utilizando BeautifulSoup y Selenium.

3. **🤖 Automatización del navegador**: A través de Selenium, se simulan interacciones con páginas web, como la selección de fechas y navegación entre páginas meteorológicas. Esto permite extraer información detallada que no está disponible directamente en el HTML estático.

4. **📊 Organización de datos**: Los datos meteorológicos obtenidos se organizan en estructuras de datos para facilitar su análisis posterior.

5. **⚠️ Manejo de excepciones**: Se implementan controles para manejar errores comunes en la automatización, como elementos no encontrados en la página o tiempos de espera excesivos.

## 💻 Requisitos del sistema

Para ejecutar este notebook correctamente, es necesario instalar las siguientes dependencias:

- Python 3.7 o superior
- `beautifulsoup4`
- `requests`
- `pandas`
- `numpy`
- `selenium`
- `webdriver-manager`

Puedes instalar todas las dependencias ejecutando el siguiente comando:

```bash
pip install -r requirements.txt
```

## 📝 Cómo usar este proyecto

1. Clona este repositorio en tu máquina local:

   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   ```

2. Instala las dependencias:

   ```bash
   pip install -r requirements.txt
   ```

3. Ejecuta el notebook en un entorno local o en JupyterLab.

## 🙌 Créditos

Este proyecto fue desarrollado como parte de una práctica en la que se aprendió a utilizar las herramientas mencionadas para la automatización y scraping web.
