# Conceptos de Bases de Datos

![uth](https://github.com/Vaquin/Act.1---Conceptos-de-BDs/assets/141975352/cf885e96-2118-4766-bae5-be02d4e974c9)

UNIVERSIDAD TECNOLÓGICA DE HERMOSILLO

Carrera:
Ingeniería En Desarrollo y Gestión de Software / TSU Tecnologías de la Información Desarrollo de Software Multiplataforma

Alumno:
Vaca Vega Gabriel Enrique
TIDS 5-2

Profesor:
Chenoweth Chenoweth Ivan Rogelio

Asignatura:
Base de Datos para Computo en la Nube

![Descripción del GIF](https://media.giphy.com/media/kPrlykW2TpVU4HWx2O/giphy.gif)

Fecha de entrega:
Sabado 27 de Enero de 2024

---

## Índice
- [Introducción](#introducción)
- [Mapas Conceptuales](#mapas-conceptuales)
- [Conceptos del Modelo Relacional](#conceptos-del-modelo-relacional)
- [Diferencias entre Relacional y No Relacional](#diferencias-entre-relacional-y-no-relacional)
- [Mejores SGBD más Usados](#mejores-sgbd-más-usados)
- [Comparativa de SGBD más Comunes](#comparativa-de-sgbd-más-comunes)
- [Funciones de los SGBD](#funciones-de-los-sgbd)
- [Tipos de DB](#tipos-de-db)
- [Integridad de Entidades e Integridad Referencial](#integridad-de-entidades-e-integridad-referencial)
- [Transformación de E-R a Modelo Relacional](#transformación-de-e-r-a-modelo-relacional)
- [Normalización](#normalización)
- [ACID vs BASE y Teorema CAP](#acid-vs-base-y-teorema-cap)
- [Quizzes de SQLZoo](#quizzes-de-sqlzoo)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)

---

## Introducción
[Texto de introducción explicando el propósito del documento y un breve resumen de lo que se incluirá.]
Este documento busca explorar y profundizar en los aspectos fundamentales de las bases de datos, enfocándose en el Modelo Relacional y su comparación con los modelos No Relacionales. A través de un análisis detallado y mapas conceptuales elaborados a partir de fuentes sugeridas, se busca brindar una comprensión clara de los conceptos clave como la normalización, integridad de datos, y las diferencias entre los Sistemas de Gestión de Bases de Datos (SGBD) más utilizados. Además, se realiza una práctica aplicada mediante la transformación de un modelo Entidad-Relación a un Modelo Relacional, seguida de la realización de ejercicios prácticos en SQL para consolidar el aprendizaje teórico. Este trabajo no solo es un requisito académico sino también una herramienta valiosa para comprender mejor el diseño, la implementación y la gestión eficiente de bases de datos en el ámbito profesional.

---

## Mapas Conceptuales
Descripción y enlaces a los mapas conceptuales creados para cada fuente sugerida.

---

## Conceptos del Modelo Relacional
Resumen y explicación de los conceptos del modelo relacional, basado en [AWS - Data Modeling](https://aws.amazon.com/es/what-is/data-modeling/).
![7978288d-358a-4131-b950-ce1e52e4959c](https://github.com/Vaquin/Act.1---Conceptos-de-BDs/assets/141975352/5b892b71-b431-4875-9e58-4148b79baab9)

---

## Diferencias entre Relacional y No Relacional
Análisis de las diferencias entre bases de datos relacionales y no relacionales, referenciando a [SlideShare - NoSQL](https://es.slideshare.net/dipina/nosql-introduccin-a-las-bases-de-datos-no-estructuradas).
![b3b4652f-d3a1-4690-a1e6-ceaab955cf92](https://github.com/Vaquin/Act.1---Conceptos-de-BDs/assets/141975352/0ba9fd8c-4784-40c5-9760-75b7b2bc8572)

---

## Mejores SGBD más Usados
Lista y breve descripción de los SGBD más populares actualmente.
![3e274c84-2a9d-40e8-bf88-80d1a6009098](https://github.com/Vaquin/Act.1---Conceptos-de-BDs/assets/141975352/855300da-dec4-4213-9c52-e465d23cc0af)

---

## Comparativa de SGBD más Comunes
Cuadro comparativo de las características de varios SGBD comunes.
![8b109053-969d-4dfe-b86e-c62943e4c350](https://github.com/Vaquin/Act.1---Conceptos-de-BDs/assets/141975352/2011fe13-8417-4fc4-8d2c-f2b20920c5b0)

---

## Funciones de los SGBD
Descripción de las funciones principales de los Sistemas de Gestión de Bases de Datos.
![d9d265a1-6979-4b84-beda-ef4f0b3ad1bf](https://github.com/Vaquin/Act.1---Conceptos-de-BDs/assets/141975352/3bc332d3-9cd0-4a51-9859-d73c320594b3)

---

## Tipos de DB
Inclusión del mapa conceptual sobre los diferentes tipos de bases de datos.
![ae7e13c3-2b00-403c-ba07-5c25f3b7d3c8](https://github.com/Vaquin/Act.1---Conceptos-de-BDs/assets/141975352/7c1ac359-869d-48cb-ba61-745c168753f9)

---

## Integridad de Entidades e Integridad Referencial
Explicación de los conceptos de integridad de entidades e integridad referencial.
![86498fd4-d76a-4b6f-a94c-0746195f3d42](https://github.com/Vaquin/Act.1---Conceptos-de-BDs/assets/141975352/fd083c2e-ae17-4756-be56-d286bf98a62b)

---

## Transformación de E-R a Modelo Relacional
Descripción del proceso de transformación con un ejercicio específico.
![image](https://github.com/Vaquin/Act.1---Conceptos-de-BDs/assets/141975352/5f724604-5f62-4699-9e0f-b094281c462c)

---

## Normalización
Mapa conceptual y explicación de la normalización en bases de datos (1FN, 2FN y 3FN).
![bd288427-a00e-4c8b-a9ae-dbdee7067650 (1)](https://github.com/Vaquin/Act.1---Conceptos-de-BDs/assets/141975352/f144712b-490c-49ad-8e69-9f6e0ef79213)

---

## ACID vs BASE y Teorema CAP
Descripción y comparación de los conceptos ACID, BASE y el Teorema CAP.
![20463b3b-2016-4a7c-8c50-85a43f6ad3c6](https://github.com/Vaquin/Act.1---Conceptos-de-BDs/assets/141975352/83ce99c6-763e-4879-8f7e-2128b8565d81)
![image](https://github.com/Vaquin/Act.1---Conceptos-de-BDs/assets/141975352/223875a9-567e-414a-94f4-b5bb2808d8f7)

---

## Quizzes de SQLZoo
Reflexiones y aprendizajes clave de los quizzes realizados en [SQLZoo](https://sqlzoo.net/wiki/SELECT_basics).
![image](https://github.com/Vaquin/Act.1---Conceptos-de-BDs/assets/141975352/b78d83e7-46b6-44b9-8e50-65731fad22b7)

---

## Conclusiones
[Texto con las conclusiones personales y reflexiones sobre lo aprendido.]
Podemos concluir que la elección entre un modelo relacional y un modelo no relacional depende significativamente del tipo de aplicación, los requisitos de datos y el contexto específico de uso. Mientras los modelos relacionales ofrecen una estructura organizada y una fuerte integridad de datos, los modelos no relacionales proporcionan flexibilidad y escalabilidad. La comprensión de conceptos como la normalización y la integridad de datos es crucial para mantener la calidad y la coherencia en los sistemas de bases de datos. La realización de ejercicios prácticos en SQL y la aplicación de teorías en un contexto real fortalece la capacidad de diseñar y gestionar bases de datos de manera efectiva. Este trabajo ha proporcionado una base sólida en conceptos de bases de datos, herramientas esenciales para el desarrollo profesional en el campo de la tecnología de la información.

---

## Bibliografía

Lista de todas las fuentes utilizadas para realizar la actividad.

https://sacavix.com/2023/01/bases-de-datos-que-aprender-en-el-2023
​​https://www.tutorialspoint.com/mongodb/mongodb_overview.htm
https://sqlzoo.net/wiki/SELECT_basics  (QUIZES DE REFUERZO) 

INTERVIEW RDBMS

https://www.toptal.com/sql/interview-questions
https://www.datacamp.com/blog/top-sql-interview-questions-and-answers-for-beginners-and-intermediate-practitioners

---

