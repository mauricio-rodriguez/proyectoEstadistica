Impacto del proceso de vacunación contra el Covid-19
========================================================
author: Grupo 4
date: 3 de Agosto de 2021
autosize: true

Importancia
=========================================================
El estudio busca sensibilizar e informar a la población sobre los efectos generados por el proceso de vacunación contra la Covid-19 en las regiones del Perú, por lo que se considera un tema de interés público debido al contexto actual.
<div align="center">
<img src="imgs/imagenVacunas.jpg" width=600 height=400>
</div>

========================================================
<div align="center">
<h2 style="margin:200px 0 20px 0;font-size:400%;">Objetivos</h2>
</div>

Objetivos
========================================================
- Analizar la cantidad de fallecidos en el periodo de la segunda ola.
- Hallar la comparación del impacto de la vacunación en los diferentes departamentos del país.
- Visualizar la curva de fallecidos desde el inicio de la vacunación según la etapa de vida.
- Determinar si es que existe relación entre las distintas vacunas con la cantidad de fallecidos en los distintos departamentos.


========================================================
<div align="center">
<h2 style="margin:200px 0 20px 0;font-size:400%;">Parametros del estudio</h2>
</div>

Parametros del estudio
========================================================
- Nivel de confianza: 95% 

<h3>Tamaño de la muestra:</h3>
- [Datos sobre vacunados](https://www.datosabiertos.gob.pe/dataset/vacunaci%C3%B3n-contra-covid-19-ministerio-de-salud-minsa-0): 
  - Observaciones completas:11 039 761
- [Datos sobre fallecidos](https://www.datosabiertos.gob.pe/dataset/fallecidos-por-covid-19-ministerio-de-salud-minsa/resource/4b7636f3-5f0c-4404-8526):
  - Observaciones completas: 194843
- Data tomada hasta el 14 de julio del 2021


========================================================
<div align="center">
<h2 style="margin:200px 0 20px 0;font-size:400%;">Análisis descriptivo</h2>
</div>

DataSet: Fallecidos
========================================================
<div align="center">
<p>Personas fallecidas por edad</p>

<img src="S3_presentacion-figure/fallecidos_edad.png" width=700 height=432">

<figcaption>Se visualiza que las edades de las personas que más han fallecido por la pandemia tenían entre 60 y 75 años</figcaption>
<figcaption>A su vez, la mayor cantidad de fallecidos son personas mayor de 40 años</figcaption>
<figcaption>Esta gráfica, nos permite entender los rangos más afectados por covid-19</figcaption>


</div>

DataSet: Fallecidos
========================================================
<div align="center">
<p>Fallecidos por Covid-19 por día</p>

<img src="S3_presentacion-figure/fallecidos_curva.png" width=700 height=432>
<figcaption>Se puede observar claros picos en el aumento de fallecidos por día dados por la</figcaption>
<figcaption>primera y segunda ola de contagios en conjunto del sinceramiento de cifras realizado por el Gobierno.</figcaption>
<figcaption>Podemos observar, que el decremento rápido de los fallecimientos por día coincide con la llegada y el proceso de vacunación.</figcaption>

</div>

DataSet: Fallecidos
========================================================
<div align="center">
<p>Fallecidos de covid 19 por departamentos</p>

<img src="S3_presentacion-figure/fallecidos_departamento.png" width=700 height=432>
<figcaption>Como se observa en la gráfica, el departamento con mayor porcentaje de fallecidos en proporción a su población es Ica, a pesar de que Lima sea el departamento con un número de mayor de fallecidos. Con ello, podemos analizar el impacto del covid 19 por departamento en función de su poblacion con la finalidad de estudiar las estrategias sanitarias implementadas por el gobierno.</figcaption>

</div>

DataSet: Fallecidos
========================================================
<div align="left">
<div>
<h3>Edad promedio de fallecidos por covid 19</h3>
<p align="left">Promedio de fallecidos: 66 años</p>
<p>Podemos observar que el sector más afectado por la pandemia son los adultos mayores o de tercera edad. Esta información es útil para nuestro estudio ya que podemos saber cuál fue el sector en el que se debió enfocar la atención y recursos médicos durante la emergencia.</p>
</div>

<div>
<h3>Rango de edad de fallecidos por covid 19</h3>
<p>Rango de edad: 117 años</p>
<p>El rango de edad de personas fallecidas a causa de Covid-19 nos indica todas las edades las cuales abarca nuestra muestra. Determinado por el máximo y mínimo de edad. Este dato nos sirve para confirmar que estamos tomando en cuenta todos los datos de fallecidos para cada una de nuestras gráficas en las que utilizamos este dato.</p>
</div>

</div>


DataSet: Fallecidos
========================================================
<div align="left">
<h3>Cantidad máxima y mínima de fallecidos por día</h3>
<p>Mínima: 1 persona | Máxima: 846</p>
<p>La cantidad máxima y mínima de fallecidos por día nos indican los límites en los cuales se encuentra nuestra muestra. Esta información es útil para nuestro estudio ya que podemos evaluar si el momento actual de la pandemia puede ser considerado como estable o crítico.</p>

<h3>Edad máxima y mínima de fallecidos</h3>
<p>Mínima: 0 persona | Máxima: 117</p>
<p>Lo cual indica que hubo menores de edad fallecidos con menos de 1 año de edad. Podemos utilizar estos datos con la edad promedio de fallecidos por covid para determinar cuantos y cuales rangos de edad se han visto seriamente afectados por la Covid-19.</p>

</div>

DataSet: Proceso de Vacunacion
========================================================
<div align="center">
<p>Fecha de vacunacion en funcion de la edad</p>
<img src="S3_presentacion-figure/vacunacion_fechaedad.png" width=700 height=432>
<figcaption> A inicios de abril en donde terminó la vacunación de personal de primera línea y empezó la vacunación de personas mayores, iniciando con los rangos más altos de edad, para lo cual en mayo se puede observar el pico de promedio de edad más alto registrado</figcaption>
</div>


DataSet: Proceso de Vacunacion
========================================================
<div align="center">
<p></p>
<img src="S3_presentacion-figure/vacunacion_departamento.png" width=700 height=432>
<figcaption>En la gráfica se observa, que el departamento de Tacna ha tenido un progreso mayor en proporción a comparación de Lima, donde se ha administrado el mayor número de dosis. Esto nos permite, analizar la planificación realizada por el gobierno para la distribución y proceso de vacunación contra la covid 19.</figcaption>
</div>


========================================================
<div align="center">
<h3 style="margin:250px 0 20px 0;font-size:400%;">Análisis inferencial y descriptivo</h3>
</div>

Pruebas de hipótesis
========================================================
<div align="center">
<h2>Primera hipótesis</h2>
<div>
<img src="S3_presentacion-figure/h0.jpg">
</div>
<div>
<img src="S3_presentacion-figure/h0_1.png">
</div>
</div>

Pruebas de hipótesis
========================================================
<div align="center">
<h2>Segunda hipótesis</h2>
<div>
<img src="S3_presentacion-figure/h1.jpg">
</div>
<div>
<img src="S3_presentacion-figure/h1_1.png">
</div>
<div>
<img src="S3_presentacion-figure/h1_2.png">
</div>
</div>

Pruebas de hipótesis
========================================================
<div align="center">
<h2>Tercera hipótesis</h2>
<div>
<img src="S3_presentacion-figure/h2.jpg">
</div>
<div>
<img src="S3_presentacion-figure/h2_1.png">
</div>
<div>
<img src="S3_presentacion-figure/h2_2.png">
</div>
<div>

</div>
</div>

Regresión - Relaciones
========================================================
- Cantidad de fallecidos en la 2da ola por etapa de vida x Cantidad de vacunados en la 2da ola por etapa de vida
- Cantidad de fallecidos por departamento en la 2da ola x Cantidad de vacunados por departamento en la 2da ola en el departamento con más vacunados
- Cantidad de fallecidos por departamento en la 2da ola x Cantidad de vacunados por departamento en la 2da ola en el departamento con menos vacunados

Regresión - Primera relación
========================================================
<div align="center">
<h2>Cantidad de fallecidos en la 2da ola por etapa de vida x Cantidad de vacunados en la 2da ola para Adultos Mayores</h2>
<img src="S3_presentacion-figure/regresion_1_mayores.png" width=700 height=432>
<figcaption></figcation>
</div>

Regresión - Primera relación
========================================================
<div align="center">
<h2>Cantidad de fallecidos en la 2da ola por etapa de vida x Cantidad de vacunados en la 2da ola para Adultos</h2>
<img src="S3_presentacion-figure/regresion_1_adultos.png" width=700 height=432>
<figcaption></figcation>
</div>

Regresión - Primera relación
========================================================
<div align="center">
<h2>Cantidad de fallecidos en la 2da ola por etapa de vida x Cantidad de vacunados en la 2da ola para Jovenes</h2>
<img src="S3_presentacion-figure/regresion_1_jovenes.png" width=700 height=432>
<figcaption></figcation>
</div>

Regresión - Segunda relación
========================================================
<div align="center">
<h2>Cantidad de fallecidos por departamento en la 2da ola x Cantidad de vacunados por departamento en la 2da ola en el departamento con más vacunados</h2>
<img src="S3_presentacion-figure/regresion_2_lima.png" width=700 height=432>
<figcaption></figcation>
</div>

Regresión - Tercera relacion
========================================================
<h2>Cantidad de fallecidos por departamento en la 2da ola x Cantidad de vacunados por departamento en la 2da ola en el departamento con menos vacunados</h2>
<div align="center">
<h2></h2>
<img src="S3_presentacion-figure/regresion_2_madre.png" width=700 height=432>
<figcaption></figcation>
</div>

========================================================
<div align="center">
<h2 style="margin:250px 0 20px 0;font-size:400%;">Reflexiones y conclusiones</h2>
</div>

Reflexiones
========================================================
- Con la data abierta proporcionada por el Estado con respecto al proceso de vacunación y los fallecidos se logro realizar procesos de análisis con respecto a nuestros objetivos propuestos.
- Gracias al análisis realizado se ha podido evaluar y observar la situación del covid-19 en el territorio peruano.


Conclusiones
========================================================
- En primer lugar, se pudo analizar la cantidad de fallecidos en el periodo de la segunda ola y a su vez obtener un gráfico para la visualización de la misma por región y edad.
- Por otra parte, a través de la relación entre el numero de fallecidos y vacunados, se pudo realizar un análisis de regresión lineal logrando visualizar el impacto en cada proceso por región.
- A su vez, se logró visualizar la cantidad de fallecidos según las olas de contagio por covid-19.
- Finalmente, no se pudo determinar la relación entre distintos fabricantes de vacunas, sin embargo se logró visualizar el proceso de vacunación en proporción a su población con la finalidad de observar el avance en todo el país.

========================================================
<div align="center">
<h2 style="margin:250px 0 20px 0;font-size:400%;">Gracias</h2>
<p>¿Preguntas?</p>
</div>




