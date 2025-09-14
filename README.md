# IA_2

https://www.canva.com/design/DAGy9qmhyac/SMg23nZDzzmyttg8zZuDCQ/edit?utm_content=DAGy9qmhyac&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

Students' Dropout and Academic Success

## **Motivación**

En muchas instituciones de educación superior, la deserción estudiantil representa un reto crítico: genera pérdidas económicas, afecta los índices de calidad académica y limita las oportunidades de desarrollo personal y profesional de los estudiantes. Con frecuencia, los factores que llevan a un alumno a abandonar sus estudios —como dificultades académicas, problemas socioeconómicos o falta de apoyo institucional— no se detectan a tiempo, lo que dificulta la implementación de estrategias de prevención.
En este contexto, el análisis de datos y las herramientas de machine learning permiten identificar patrones asociados al abandono o éxito académico, facilitando la creación de sistemas predictivos que apoyen a universidades en la toma de decisiones y en el diseño de programas de acompañamiento oportuno.

## **Alcance**

El proyecto busca predecir y clasificar el estado académico de los estudiantes (graduado, matriculado o desertor) a partir de variables socioeconómicas, demográficas y de desempeño académico, utilizando técnicas de machine learning.
De esta manera, se pretende:

Identificar factores relevantes asociados a la deserción.

Construir un modelo que apoye a las universidades en la detección temprana de estudiantes en riesgo.

Sentar las bases para futuras aplicaciones en sistemas de alerta temprana y programas de retención estudiantil.

## **Dataset**

Para el desarrollo del proyecto se utilizará el dataset público “Predict Students Dropout and Academic Success” disponible en el repositorio de la UCI Machine Learning Repository (ID: 697) [UCI, 2021].

Este conjunto de datos fue recolectado en el Instituto Politécnico de Porto (Portugal) y contiene información demográfica, socioeconómica y académica de estudiantes universitarios, con el objetivo de predecir su situación académica final.

Principales características:

Número de instancias (estudiantes): 4,424

Número de atributos predictivos: 37 variables (edad, género, estado civil, notas, origen académico, situación financiera, entre otras).

Variable objetivo: Estado académico del estudiante con 3 clases:

Graduate (graduado)

Dropout (abandona)

Enrolled (aún matriculado)

Tipo de dataset: Tabular, con variables categóricas y numéricas.


## **Caracteristicas**

| **Variable**                                   | **Descripción**                                                                    |
| ---------------------------------------------- | ---------------------------------------------------------------------------------- |
| Marital Status                                 | Estado civil del estudiante                                                        |
| Application mode                               | Vía o modo de admisión a la universidad (ej: examen, cupo especial, transferencia) |
| Application order                              | Orden de preferencia con que eligió el curso/programa en su aplicación             |
| Course                                         | Programa académico en el que se matriculó                                          |
| Daytime/evening attendance                     | Turno de estudio (diurno o nocturno)                                               |
| Previous qualification                         | Nivel de estudios con que ingresó (ej: bachillerato, técnico, etc.)                |
| Previous qualification (grade)                 | Nota/resultado obtenido en esa formación previa                                    |
| Nacionality                                    | Nacionalidad del estudiante                                                        |
| Mother's qualification                         | Nivel educativo de la madre                                                        |
| Father's qualification                         | Nivel educativo del padre                                                          |
| Mother's occupation                            | Ocupación de la madre                                                              |
| Father's occupation                            | Ocupación del padre                                                                |
| Admission grade                                | Nota final de admisión al curso                                                    |
| Displaced                                      | Si el estudiante proviene de otra región                                           |
| Educational special needs                      | Si presenta necesidades educativas especiales                                      |
| Debtor                                         | Si presenta deudas pendientes con la institución                                   |
| Tuition fees up to date                        | Estado de pago de matrícula (al día o atrasado)                                    |
| Gender                                         | Género del estudiante                                                              |
| Scholarship holder                             | Si recibe beca                                                                     |
| Age at enrollment                              | Edad al momento de ingresar                                                        |
| International                                  | Si es estudiante internacional                                                     |
| Curricular units 1st sem (credited)            | Asignaturas acreditadas en el 1er semestre                                         |
| Curricular units 1st sem (enrolled)            | Asignaturas inscritas en el 1er semestre                                           |
| Curricular units 1st sem (evaluations)         | Evaluaciones rendidas en el 1er semestre                                           |
| Curricular units 1st sem (approved)            | Asignaturas aprobadas en el 1er semestre                                           |
| Curricular units 1st sem (grade)               | Promedio de calificaciones en el 1er semestre                                      |
| Curricular units 1st sem (without evaluations) | Asignaturas inscritas pero no evaluadas (abandono parcial)                         |
| Curricular units 2nd sem (credited)            | Asignaturas acreditadas en el 2º semestre                                          |
| Curricular units 2nd sem (enrolled)            | Asignaturas inscritas en el 2º semestre                                            |
| Curricular units 2nd sem (evaluations)         | Evaluaciones rendidas en el 2º semestre                                            |
| Curricular units 2nd sem (approved)            | Asignaturas aprobadas en el 2º semestre                                            |
| Curricular units 2nd sem (grade)               | Promedio de calificaciones en el 2º semestre                                       |
| Curricular units 2nd sem (without evaluations) | Asignaturas inscritas pero no evaluadas en el 2º semestre                          |
| Unemployment rate                              | Tasa de desempleo (macro dato económico del país en ese año)                       |
| Inflation rate                                 | Tasa de inflación (macro dato económico del país)                                  |
| GDP                                            | Producto Interno Bruto (macro dato económico del país)                             |


Pertinencia para el proyecto:
El dataset es adecuado porque permite analizar los factores que influyen en la deserción académica y construir modelos predictivos que apoyen a las instituciones en la detección temprana de estudiantes en riesgo, alineándose con los objetivos del proyecto.
