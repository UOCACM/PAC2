<h1 align="center"> Limpieza de Datos </h1>
<h3 align="center"> M2.851 - Tipología y ciclo de vida de los datos (aula 2) -Master en Ciencia Datos </h3>
<h3 align="center"> Autores: </h3>
<h3 align="center"> Almudena Caballero Manzanas </h3>
<h3 align="center"> Ángel A. Urbina Sánchez </h3>
<h5 align="center"> Practica 2 - <a href="https://www.uoc.edu/">Universitat Oberta de Catalunya</a> (Primavera 2022) </h5>

[![Release](https://img.shields.io/github/release/vhesener/Closures.svg?style=plastic&colorB=68B7EB)]()

<p>En esta práctica se elabora un caso práctico orientado a aprender a identificar los datos
relevantes para un proyecto analítico y usar las herramientas de integración, limpieza, validación
y análisis de las mismas.</p>
<p>Además, se debe entregar un vídeo explicativo de la práctica, donde ambos integrantes del
equipo expliquen con sus propias palabras el desarrollo de la práctica, basándose en las
preguntas del enunciado para justificar y explicar el código desarrollado. Este vídeo se deberá
entregar a través de un enlace a Google Drive que se deberá proporcionar junto con enlace al
repositorio Git.</b>.</p>
<p> Bla, bla 3
Elegimos <a href=https://www.emagister.com>Emagister</a>, Bla, bla 2 </p>
<p>Consideramos que la información relevante para desarrollar esta decisión es:<p>
<ul>
    <li> Descripción del máster: tipología, duración, metodología, …</li>
    <li> Precio</li>
    <li> Entidad</li>
    <li> Programa</li>
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> Consideración Generales</h2>
<p> La estructura de la solución diseñada es modular con el objetivo de simplicar el mantenimiento y el proceso de mejora en futuras versiones.</p>
<p> Para simplificar la identificaciones de posibles bugs e incidencias en la ejecución asi como para favorecer el desarrollo de mejoras sobre el código propuesto se documenta todo el proceso en los diferentes logs. (Terminal & Fichero )</p>
<p> Los pasos considerados han sido</p>
<ul>
    <li><b>Generación Archivo Links</b> Extracción informacion Links de los diferentes masters</li>
    <li><b>Extracción Información Masters</b> Se lee archivo anterior con listado de links de cada master individual. Se extrae la información de cada uno de los Masters</li>
    <li><b>Extracción Imagenes</b> Extracción de información en formato grafico. Se trata de los Logos de las diferentes instituciones que ofrecen cursos.</li>
</ul>

<p> Se han desarrollado dos maneras diferentes de obtención de la informacion de los Masteres:</p>
<ul>
    <li><b>MODO SECUENCIAL</b> El acceso a los diferentes links WEB se desarrolla de forma secuencial (Mayor tiempo de ejecución).</li>
    <li><b>MODO MULTIPROCESO</b> El acceso a los diferentes links WEB se desarrolla de forma paralela (Menor tiempo de ejecución).</li>
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :floppy_disk: Descripción archivos proyecto</h2>

<p>Este proyecto se ha desarrollado integramente en Python utilizando la herramienta Visual Studio Code. Continene varios archivos en formato notebook, y varios directorios con la siguiente estructura.:</p>
<h4>CODIGOS:</h4>
<ul>
  <li><b>PRA01.ipynb</b> - Contiene todo el código Python del WebScraping desarrollado.(Formato Notebook Python)</li>
  <li><b>loggingUOCPRA01.conf</b> - Archivo Auxiliar de configuración de loggins para el archivo Python anterior. (Formato txt)</li>
  <li><b>UOCPRA01.log</b> - Archivo auxiliar log en formato .txt resultado de la ejecución del archivo python.</li>
</ul>

<h4>RESULTADOS:</h4>
<ul>
  <li><b>InfoMaster-07-04-22.xlsx</b> - Contiene la información extraida de la Web en formato (.xlsx).</li>
  <li><b>InfoMaster-07-04-22.csv</b> - Si existe. Contiene la información extraida de la Web en formato (.csv).</li>
    <li><b>Datos disponibles en: </b> <a href= https://zenodo.org/record/6425416#.YlBHLchBxPY>Zenodo</a> con DOI 10.5281/zenodo.6425416</li>
</ul>

<h4>IMAGENES:</h4>
<ul>
  <li><b>XXXXXX.jpg</b> - Conjunto de Archivos de Imagenes Descargados (.jpg).</li>
  <li><b>XXXXXX.png</b> - Conjunto de Archivos de Imagenes Descargados (.png).</li>
</ul>

<h4>DESCRIPCION:</h4>
<ul>
  <li><b>M2851_PRA1.docx</b> - Incluye el contenido de la practica en formato (.docx)</li>
  <li><b>M2851_PRA1.pdf</b> - Incluye el contenido de la practica en formato (.pdf)</li>
</ul>

<h4>VIDEOS EXPLICATIVOS:</h4>
<ul>
  <li><b>Presentación Almudena Caballero Manzanas</b> <a href= https://drive.google.com/file/d/1yzYDhucSoljTRzljLoGkDkt15mEl1Q5v/view?usp=sharing >  - Link Drive UOC</li></a> 
  <li><b>Presentación Ángel A. Urbina Sánchez</b> <a href= https://drive.google.com/file/d/1Da2KcpkXvfB_MXrfnwwuIWv0LuGIu-rn/view?usp=sharing > - Link Drive UOC</a> </li>
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- CREDITS -->
<h2 id="credits"> :scroll: Creditos</h2>

Agradecemos a los diferentes autores de las siguientes referencias el habernos facilitado el trabajo de desarrollo:

<ul>
  <li>https://stackoverflow.com/questions/66876071/extracting-a-complex-substring-using-regex-with-data-from-a-string-in-python</li>
  <li>https://stackoverflow.com/questions/14473180/regex-to-get-a-filename-from-a-url</li>
  <li>https://medium.com/@kunal.rustagi/boost-your-web-crawler-using-multiple-processes-in-python-3cc3ff519226</li>
  <li>https://coderzcolumn.com/tutorials/python/logging-config-simple-guide-to-configure-loggers-from-dictionary-and-config-files-in-python</li>
</ul>

