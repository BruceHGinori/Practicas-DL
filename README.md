# Resumen

Este trabajo es la continuidad del proyecto PAPIME titulado “Propuesta de mejora a la enseñanza del aprendizaje automático aplicado a la Ciencia de Datos (DS) a gran escala” con el número de proyecto PE103124. Se propone aplicar la experiencia para mejorar la enseñanza de la teoría y de la práctica de la DS con los manuales desarrollados; lo cual se aplicará en un diplomado en donde se espera se incorporen los estudiantes al finalizar sus estudios de licenciatura y académicos interesados. 
    
La elaboración de un manual de prácticas a nivel licenciatura para las asignaturas en el área del aprendizaje profundo o Deep Learning (DL) aplicado a datos a gran escala (Big Data). Permite a los estudiantes entender de mejor manera el DL y sus herramientas, utilizando ejercicios prácticos y aplicables en la realidad, que pueden desarrollarse a partir del sexto semestre de la LTICs y de otras licenciaturas afines, en la ENES Morelia.

La realización de este manual de prácticas, así como el contenido del mismo, fue determinado, modificado y adaptado mediante una encuesta aplicada a los alumnos pertenecientes a carreras relacionadas con el campo de estudio, este instrumento ayudó a determinar las áreas de interés con respecto al DL.
	
Nuestra población de muestra, además de los estudiantes, contó con la participación de los docentes y académicos de las diferentes licenciaturas y postgrados dentro de la ENES Morelia y del Campus de la UNAM. La finalidad fue obtener información con relación a las materias de la carrera de LTICs, con el fin de adaptar el contenido de éstas, para un mejor entendimiento de la inteligencia artificial y el DL.

El manual tiene el propósito de brindar una mejor formación académica a los estudiantes de LTICs y licenciaturas afines al DL. Además, resulta ser una herramienta para que los docentes conocieran las necesidades estudiantiles y coadyuvar al autoaprendizaje en esta área.

El manual se conforma de seis prácticas base y cuatro complementarias que ayudan al entendimiento de la aplicación del DL y el Big Data.

# Abstract

This work is a continuation of the PAPIME project entitled "Proposal for Improving the Teaching of Machine Learning Applied to Large-Scale Data Science (DS)" (project number PE103124). The project aims to apply this experience to improve the teaching of DS theory and practice with the developed manuals. This will be implemented in a diploma program that is expected to be enrolled by students and interested academics upon completion of their undergraduate studies.
	
The development of a bachelor's-level practice manual for courses in the field of deep learning (DL) applied to large-scale data (Big Data). It allows students to better understand DL and its tools, using practical and applicable exercises. These exercises can be completed starting in the sixth semester of the LTICs program and other related bachelor's programs at ENES Morelia.

The creation of this practice manual, as well as its content, was determined, modified, and adapted through a survey administered to students in programs related to the field of study. This instrument helped determine areas of interest regarding DL.

In addition to students, our sample included faculty and academics from various undergraduate and graduate programs at ENES Morelia and the UNAM campus. The purpose was to gather information on the LTICs program courses, in order to adapt their content to better understand artificial intelligence and digital learning.

The manual aims to provide better academic training for students of ICTs and related degree programs. It also serves as a tool for teachers to understand student needs and support self-learning in this area.

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
| 3            | Redes Convolucionales y Data Augmentation  [Jupyter](https://github.com/BruceHGinori/Practicas-DL/blob/main/Pr%C3%A1cticas/Pr%C3%A1cticas%20de%20Laboratorio/Pr%C3%A1ctica%203%20Deportes/TF-Deportes.ipynb)  [PDF](https://github.com/BruceHGinori/Practicas-DL/blob/main/Pr%C3%A1cticas/Pr%C3%A1cticas%20de%20Laboratorio/Pr%C3%A1ctica%203%20Deportes/Pr%C3%A1ctica_3_TF_Deportes.pdf)                | 100 Sports Image Classification                           | Exactitud, Precisión, Sensibilidad, F1-Score y Matriz de Confusión | Crear un modelo que pueda hacer multiclasificación de imágenes de 100 deportes diferentes.                             |
