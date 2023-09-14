# Resumen

Este trabajo forma parte del proyecto PAPIME titulado “Propuesta de mejora a la enseñanza del aprendizaje automático aplicado a la Ciencia de Datos a gran escala” con el número de proyecto PE106021. Se propone la elaboración de un manual de prácticas a nivel licenciatura para las asignaturas en el área de aprendizaje profundo o Deep Learning (DL) usando herramientas a gran escala (Big Data). Con el fin de ayudar a los estudiantes a entender el DL y sus herramientas, utilizando prácticas, que pueden desarrollarse a partir del sexto semestre de la LTICs y de otras licenciaturas afines, en la ENES Morelia que requieren los conocimientos del DL.

La realización de este manual de prácticas, así como el contenido del mismo, fue determinado, modificado y adaptado mediante una encuesta aplicada a los alumnos pertenecientes a carreras relacionadas con el campo de estudio, este instrumento ayudó a determinar las áreas de interés con respecto al DL.
	
Nuestra población de muestra además de los estudiantes contó con la participación de los docentes y académicos de las diferentes licenciaturas y postgrados dentro de la ENES Morelia y del Campus de la UNAM. La finalidad es obtener información con relación a las materias de la carrera de LTICs, con el fin de adaptar el contenido de estas, para un mejor entendimiento de la inteligencia artificial y el DL.

El manual tiene el propósito de brindar una mejor formación académica a los estudiantes de LTICs y licenciaturas afines al DL. Además, resulta ser una herramienta para que los docentes conocieran las necesidades estudiantiles y coadyuvar al autoaprendizaje en esta área.

El manual se conforma de seis prácticas base y cuatro complementarias que ayudan al entendimiento de la aplicación del DL y el Big Data.

# Abstract

This work is part of the PAPIME project titled “Proposal to improve the teaching of machine learning applied to large-scale Data Science” with project number PE106021. The development of a practice manual at the undergraduate level is proposed for subjects in the area of deep learning (DL) using large-scale tools (Big Data). In order to help students understand the DL and its tools, using practices that can be developed from the sixth semester of the LTICs and other related degrees, at ENES Morelia that require knowledge of the DL.

The creation of this practice manual, as well as its content, was determined, modified and adapted through a survey applied to students belonging to careers related to the field of study. This instrument helped determine the areas of interest with respect to the DL.

Our sample population, in addition to the students, included the participation of teachers and academics from the different undergraduate and graduate degrees within ENES Morelia and the UNAM Campus. The purpose is to obtain information in relation to the subjects of the LTICs career, in order to adapt their content, for a better understanding of artificial intelligence and DL.

The manual has the purpose of providing better academic training to students of LTICs and degrees related to DL. In addition, it turns out to be a tool for teachers to know student needs and contribute to self-learning in this area.

The manual is made up of six base and four complementary practices that help understand the application of DL and Big Data.

# Estructura del repositorio

Este repositorio constiste de dos carpetas principales:
- Manual
- Prácticas

En la carpeta "Manual" se encuentra el Manual de Prácticas el cual contiene toda la información relacionada al marco teórico y la metodología utilizada en este proyecto.

En la carpeta "Prácticas" se encuentran todas las prácticas desarrolladas en este proyecto divididas en dos carpetas:
- Actividades Complementarias
- Prácticas de Laboratorio

A su vez cada pŕactica se encuentra en una carpeta en la que se encuentra lo siguiente:
- Jupyter notebook donde se desarrolla paso a paso la práctica.
- Archivo **.pdf** en el cual se describe la metodología y el código usado en el Jupyter notebook. En el caso de la práctica 5, este archivo se ha omitido debido a que lo necesario está explicado en el Jupyter notebook.
- Archivo **.md** donde se describe cómo descargar los datos utilizados en la práctica.

# Estructura de las prácticas
Cada una de las prácticas presentadas en el anexo contienen las siguientes fases,
en el orden en que se muestran:

1. Objetivo de la práctica.
2. Conceptos.
3. Herramientas a usar.
4. Desarrollo. <br>
  a) Entender el Problema. <br>
  b) Definir un criterio de evaluación. <br>
  c) Preparar los datos. <br>
  d) Construir el modelo. <br>
  e) Análisis de errores. <br>
  f) Implementación. <br>

# Prácticas de Laboratorio
| N°  Práctica | Nombre                                                     | Dataset                                         | Criterio de  Evaluación     | Descripción                                                                                                                                                                     |
|--------------|------------------------------------------------------------|-------------------------------------------------|-----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1            | Clasificación Binaria y Redes Convolucionales Básico  [Jupyter](https://github.com/BruceHGinori/Practicas-DL/blob/main/Pr%C3%A1cticas/Pr%C3%A1cticas%20de%20Laboratorio/Pr%C3%A1ctica%201%20Mosquitos/TF-Mosquitos.ipynb)  [PDF](https://github.com/BruceHGinori/Practicas-DL/blob/main/Pr%C3%A1cticas/Pr%C3%A1cticas%20de%20Laboratorio/Pr%C3%A1ctica%201%20Mosquitos/Pr%C3%A1ctica_1_TF_Mosquitos.pdf)                | Mosquitos Aedes y Aegiptys                           | Exactitud | Crear una red neuronal básica para clasificar dos especies diferentes de mosquitos analizando las imágenes proporcionadas.                             |
| 2            | Clasificación Binaria y Redes Convolucionales Avanzado  [Jupyter](https://github.com/BruceHGinori/Practicas-DL/blob/main/Pr%C3%A1cticas/Pr%C3%A1cticas%20de%20Laboratorio/Pr%C3%A1ctica%202%20Pulmones/TF-Pulmones.ipynb)  [PDF](https://github.com/BruceHGinori/Practicas-DL/blob/main/Pr%C3%A1cticas/Pr%C3%A1cticas%20de%20Laboratorio/Pr%C3%A1ctica%202%20Pulmones/Pr%C3%A1ctica_2_TF_Pulmones.pdf)                | COVID-19 Xray Dataset (Train \& Test Sets)                           | Exactitud | Aplicar lo aprendido en la actividad de los moquitos pero aplicado a imágenes de Rayos X de diferentes pacientes.                             |
