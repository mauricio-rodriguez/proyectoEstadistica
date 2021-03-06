Impacto del proceso de vacunación contra el Covid-19
========================================================
author: Grupo 3
date: 11 de Junio de 2021
autosize: true

Importancia
=========================================================
El estudio busca sensibilizar e informar a la población sobre los efectos generados por el proceso de vacunación contra la Covid-19 en las regiones del Perú, por lo que se considera un tema de interés público debido al contexto actual.
<div align="center">
<img src="imgs/imagenVacunas.jpg" width=600 height=400>
</div>

Obtención de los datos
========================================================
Plataforma Nacional de Datos Abiertos
- [Datos sobre vacunados](https://www.datosabiertos.gob.pe/dataset/vacunaci%C3%B3n-contra-covid-19-ministerio-de-salud-minsa-0): 
  - Datos faltantes:  127931 --> 0
  - Observaciones completas: 2671786 --> 4571604
  - Porcentaje de observaciones incompletas: 4.57 --> 0
- [Datos sobre fallecidos](https://www.datosabiertos.gob.pe/dataset/fallecidos-por-covid-19-ministerio-de-salud-minsa/resource/4b7636f3-5f0c-4404-8526):
  - Datos faltantes: 0 -> 1
  - Observaciones completas: 66770 --> 187157
- Data tomada hasta el 8 de junio del 2021


========================================================
<div align="center">
<h2 style="margin:200px 0 20px 0;font-size:400%;">Figuras de merito</h2>
</div>

DataSet: Fallecidos
========================================================
<div align="center">
<p>¿Cómo influye la llegada de las vacunas en la cantidad de fallecidos por COVID?</p>
<img src="P2-figure/FFallecidos.png" width=700 height=432">
<figcaption>El pico más alto de la cantidad de fallecidos fue obtenido durante este periodo.</figcaption>

<figcaption>La máxima cantidad de fallecidos en un dia es 845.</figcaption>
<figcaption>La mínima cantidad de fallecidos en un dia es 1.</figcaption>


</div>

DataSet: Fallecidos
========================================================
<div align="center">
<p>¿Será cierto que los adultos mayores son las personas que más fallecieron por COVID?</p>
<img src="P2-figure/FEdad.png" width=700 height=432>
<figcaption>Las personas que más fallecieron tenían entre 60 y 80 años.</figcaption>
<figcaption>La edad mínima de los fallecidos es 0.</figcaption>
<figcaption>La edad máxima de los fallecidos es 117.</figcaption>

</div>

DataSet: Fallecidos
========================================================
<div align="center">
<p>¿Existe alguna diferencia entre la cantidad de fallecidos y su género?</p>
<img src="P2-figure/FSexo.png" width=700 height=432>
<figcaption>En el Perú, la gran mayoría de personas fallecidas por COVID son hombres.</figcation>
</div>

DataSet: Fallecidos
========================================================
<div align="center">
<p>¿Es cierto que los departamentos del Norte tienen la mayor cantidad de fallecidos por COVID?</p>
<img src="P2-figure/FDepartamento.png" width=700 height=432>
<figcaption>Lima es el departamento con mayor cantidad de fallecidos por COVID</figcaption>
<figcaption>Amazonas es el departamento con menor cantidad de fallecidos.</figcaption>

</div>

DataSet: Proceso de Vacunacion
========================================================
<div align="center">
<p></p>
<img src="P2-figure/FVacunaEdad.png" width=700 height=432 style="margin-top:100px">
<figcaption>La mayor cantidad de vacunados en un día es 153066.</figcaption>
<figcaption>La menor cantidad de vacunados en un día es 86.</figcaption>

</div>

DataSet: Proceso de Vacunacion
========================================================
<div align="center">
<p>¿Es cierto que el género de la mayor cantidad de personas vacunadas es el mismo que de las personas fallecidas?</p>
<img src="P2-figure/VSexo.png" width=700 height=432>
<figcaption>La mayor cantidad de personas vacunadas son mujeres.</figcaption>
</div>

DataSet: Proceso de Vacunacion
========================================================
<div align="center">
<p>¿Existe la misma cantidad de dosis aplicadas en las personas vacunadas del Perú?</p>
<img src="P2-figure/VDosis.png" width=700 height=432>
<figcaption>La mayor cantidad de dosis aplicadas es la primera.</figcaption>
</div>

DataSet: Proceso de Vacunacion
========================================================
<div align="center">
<p>¿Será el mayor fabricante de vacunas del mundo (AstraZeneca) el que distribuye mayor cantidad de vacunas al Perú?</p>
<img src="P2-figure/VFabricantes.png" width=700 height=432>
<figcaption>El fabricante que más cantidad de vacunas distribuye al Perú es Pfizer.</figcaption>
<figcaption>El fabricante que menos cantidad de vacunas distribuye al Perú es Astrazeneca.</figcaption>
</div>

DataSet: Proceso de Vacunacion
========================================================
<div align="center">
<p>¿Es cierto que el departamento con la mayor cantidad de personas vacunadas es el mismo que de las personas fallecidas?</p>
<img src="P2-figure/VDepartamentos.png" width=700 height=432>
<figcaption>El departamento con mayor cantidad de personas vacunadas es Lima.</figcaption>
<figcaption>El departamento con menor cantidad de personas vacunadas es Amazonas.</figcaption>
</div>

========================================================
<div align="center">
<h2 style="margin:250px 0 20px 0;font-size:400%;">Patrones</h2>
</div>

Patrones
========================================================
<div align="center">
<p></p>
<img src="P2-figure/pFallecidosCallao.png" width=700 height=432>
<figcaption></figcation>
</div>

Patrones
========================================================
<div align="center">
<p></p>
<img src="P2-figure/pFallecidosUcayal.png" width=700 height=432>
<figcaption></figcation>
</div>

Patrones
========================================================
<div align="center">
<p></p>
<img src="P2-figure/pFallecidosDios.png" width=700 height=432>
<figcaption></figcation>
</div>

========================================================
<div align="center">
<h2 style="margin:225px 0 20px 0;font-size:300%;">Modelos de Variable Aleatoria</h2>
</div>

Modelos de Variable Aleatoria
========================================================
<div align="center">
<p>Que tan probable es que eligiendo una persona al azar de nuestra muestra, esta sea un adulto mayor de Lima y haya sido vacunado con el fabricante Pfizer. (No es equiprobable)</p>
<p> 0.27 </p>
</div>

<div align="center">
<p>Qué tan probable es que en UCAYALI exista un adulto mayor con 2 dosis y de género masculino</p>
<p> Menor a 0.01 </p>
</div>

<div align="center">
<p>Qué tan probable es que eligiendo una persona al azar esta sea una mujer y tenga 1 dosis</p>
<p> 0.36 </p>
</div>

Modelos de Variable Aleatoria
========================================================
<div align="center">
<p>Qué tan probable es que el fabricante de una vacuna aplicada sea Sinopharm</p>
<p>0.21</p>
</div>

<div align="center">
<p>Qué tan probable es que el género de una persona fallecida sea hombre</p>
<p>0.64</p>
</div>

<div align="center">
<p>Qué tan probable es que la etapa de vida de una persona fallecida sea adulto mayor(60 a más)</p>
<p>0.7</p>
</div>


========================================================
<div align="center">
<h2 style="margin:250px 0 20px 0;font-size:400%;">Relaciones</h2>
</div>

Relaciones
========================================================
<div align="center">
<p>Cantidad de fallecidos en la 2da ola por etapa de vida x Cantidad de vacunados en la 2da ola por etapa de vida</p>
<img src="P2-figure/rMayor.png" width=700 height=432>
<figcaption>Adultos Mayores - Correlación: -0.5704937</figcation>
</div>

Relaciones
========================================================
<div align="center">
<p>Cantidad de fallecidos en la 2da ola por etapa de vida x Cantidad de vacunados en la 2da ola por etapa de vida</p>
<img src="P2-figure/rAdulto.png" width=700 height=432>
<figcaption>Adultos - Correlación: 0.1306875</figcation>
</div>

Relaciones
========================================================
<div align="center">
<p>Cantidad de fallecidos en la 2da ola por etapa de vida x Cantidad de vacunados en la 2da ola por etapa de vida</p>
<img src="P2-figure/rJoven.png" width=700 height=432>
<figcaption>Jóvenes - Correlación: 0.04970341</figcation>
</div>

Relaciones
========================================================
<div align="center">
<p>Cantidad de fallecidos por departamento en la 2da ola x Cantidad de vacunados por departamento en la 2da ola en el departamento con más vacunados</p>
<img src="P2-figure/cantidadFallecidos2ola.png" width=700 height=432>
<figcaption>Lima, es la ciudad con más fallecidos - Correlación: -0.4668205</figcation>
</div>

Relaciones
========================================================
<div align="center">
<p>Cantidad de vacunados por departamento en la 2da ola x Cantidad de vacunados por departamento en la 2da ola en el departamento con más vacunados</p>
<img src="P2-figure/cantidadVacunados2ola.png" width=700 height=432>
<figcaption>Lima, es la ciudad con más vacunados - Correlación: -0.4668205<</figcation>
</div>

Relaciones
========================================================
<div align="center">
<p>Cantidad de fallecidos por departamento en la 2da ola x Cantidad de vacunados por departamento en la 2da ola en el departamento con menos vacunados</p>
<img src="P2-figure/cantidadFallecidos2olaDios.png" width=700 height=432>
<figcaption>Madre de Dios, es la ciudad con menos vacunados - Correlaccón: -0.1124028</figcation>
</div>


Relaciones
========================================================
<div align="center">
<p>Cantidad de vacunados por departamento en la 2da ola x Cantidad de vacunados por departamento en la 2da ola en el departamento con menos vacunados</p>
<img src="P2-figure/cantidadVacunados2olaDios.png" width=700 height=432>
<figcaption>Madre de Dios, es la ciudad con menos vacunados - Correlaccón: -0.1124028</figcation>
</div>

========================================================
<div align="center">
<h2 style="margin:250px 0 20px 0;font-size:400%;">Gracias</h2>
<p>¿Preguntas?</p>
</div>




