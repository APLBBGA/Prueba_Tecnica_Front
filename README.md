Instrucciones para Ejecutar el Proyecto
Este proyecto visualiza datos de usuarios obtenidos a través de la API RandomUser. Incluye gráficos y listas sobre género, edades, países y años de registro de los usuarios.

Requisitos

Navegador web 
Pasos para Ejecutar
Preparar el Entorno:

Tener acceso a Internet para cargar la API y el script externo de Chart.js.
Estructura del Proyecto:

El proyecto consta de un archivo index.html y un archivo script.js.
Archivos del Proyecto:

index.html: Contiene la estructura básica del HTML y referencias al archivo script.js y la librería Chart.js.
script.js: Realiza la solicitud a la API, procesa los datos y genera las visualizaciones.
Ejecutar:

Abrir index.html en un navegador web. El archivo se cargará y ejecutará automáticamente el JavaScript, generando las visualizaciones.

Descripción del HTML

<canvas id="genderChart">: Muestra un gráfico de barras con el número de usuarios por género.
<canvas id="ageHistogram">: Muestra un histograma de edades de los usuarios.
<ul id="countryList">: Lista el número de usuarios por país.
<canvas id="registrationYearChart">: Muestra un gráfico de líneas con el número de usuarios registrados por año.

Funcionalidad del JavaScript

Obtención de Datos: Se realiza una solicitud a la API RandomUser para obtener datos de usuarios.
Procesamiento de Datos: Los datos se procesan para obtener estadísticas sobre género, edad, país y año de registro.
Visualización: Se generan gráficos y listas con los datos procesados utilizando Chart.js.
