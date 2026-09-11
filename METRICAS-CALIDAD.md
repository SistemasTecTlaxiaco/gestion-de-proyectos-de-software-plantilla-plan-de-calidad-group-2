# MÉTRICAS DE CALIDAD



## 1. Propósito



Este documento complementa el Plan de Calidad mediante métricas cuantificables para evaluar el desempeño y la calidad de las historias de usuario del proyecto.



Las métricas permiten transformar los objetivos de calidad en valores que puedan medirse y compararse durante las iteraciones.



---



# 2. Métricas generales



| Métrica | Fórmula | Meta |

|---|---|---:|

| Cumplimiento de criterios | Criterios cumplidos / criterios totales × 100 | ≥ 95 % |

| Cobertura de pruebas | Casos ejecutados / casos planeados × 100 | ≥ 90 % |

| Correcciones exitosas | Defectos corregidos / defectos encontrados × 100 | ≥ 95 % |

| Contenido validado | Contenido validado / contenido publicado × 100 | 100 % |

| Historias aceptadas | HU aceptadas / HU terminadas × 100 | ≥ 95 % |

| Prevención contra corrección | Hp / Hc | ≥ 1.00 |

| Pruebas de conectividad | Pruebas exitosas / pruebas realizadas × 100 | ≥ 90 % |

| Accesibilidad | Criterios cumplidos / criterios evaluados × 100 | ≥ 90 % |



---



# 3. Indicador j



El indicador utilizado para comparar el esfuerzo preventivo y correctivo es:



**j = Horas de prevención / Horas de corrección**



Donde:



- **Hp:** horas utilizadas para prevenir errores.

- **Hc:** horas utilizadas para corregir errores.



## Interpretación



| Valor de j | Interpretación |

|---:|---|

| j > 1 | Mayor esfuerzo preventivo |

| j = 1 | Prevención y corrección equivalentes |

| j < 1 | Mayor esfuerzo correctivo |



El objetivo del proyecto es alcanzar progresivamente:



**j ≥ 1.00**



---



# 4. Estimación por historia de usuario



Para las estimaciones se utiliza un valor académico de referencia de:



**$150 MXN por hora**



Este valor no representa un precio comercial. Se utiliza únicamente para comparar el esfuerzo económico de las actividades de calidad.



| Historia | Prevención | Evaluación | Corrección | j |

|---|---:|---:|---:|---:|

| HU-01 | 4 h | 2 h | 3 h | 1.33 |

| HU-02 | 5 h | 3 h | 5 h | 1.00 |

| HU-03 | 6 h | 3 h | 8 h | 0.75 |

| HU-04 | 6 h | 3 h | 7 h | 0.86 |

| HU-05 | 5 h | 3 h | 6 h | 0.83 |

| HU-06 | 4 h | 3 h | 5 h | 0.80 |



---



# 5. Cálculos



## HU-01



**j = 4 / 3**



**j = 1.33**



La prevención es superior a la corrección estimada.



---



## HU-02



**j = 5 / 5**



**j = 1.00**



Existe equilibrio entre prevención y corrección.



---



## HU-03



**j = 6 / 8**



**j = 0.75**



Existe mayor esfuerzo correctivo que preventivo.



---



## HU-04



**j = 6 / 7**



**j = 0.86**



La prevención todavía es menor que la corrección.



---



## HU-05



**j = 5 / 6**



**j = 0.83**



Existe oportunidad para aumentar la prevención.



---



## HU-06



**j = 4 / 5**



**j = 0.80**



Se requiere incrementar las actividades preventivas.



---



# 6. Indicador global



Las horas estimadas son:



**Prevención = 30 horas**



**Corrección = 34 horas**



Por lo tanto:



**j global = 30 / 34**



**j global = 0.88**



## Interpretación



El resultado **0.88** indica que actualmente se estima un mayor esfuerzo de corrección que de prevención.



Por esta razón, una de las metas de las siguientes iteraciones será incrementar las actividades preventivas.



---



# 7. Costo de calidad



Se considera:



**Costo de prevención = Horas de prevención × $150**



**Costo de evaluación = Horas de evaluación × $150**



**Costo de corrección = Horas de corrección × $150**



**Costo total de calidad = Prevención + Evaluación + Corrección**



| HU | Prevención | Evaluación | Corrección | Total |

|---|---:|---:|---:|---:|

| HU-01 | $600 | $300 | $450 | $1,350 |

| HU-02 | $750 | $450 | $750 | $1,950 |

| HU-03 | $900 | $450 | $1,200 | $2,550 |

| HU-04 | $900 | $450 | $1,050 | $2,400 |

| HU-05 | $750 | $450 | $900 | $2,100 |

| HU-06 | $600 | $450 | $750 | $1,800 |

| **TOTAL** | **$4,500** | **$2,550** | **$5,100** | **$12,150** |



---



# 8. Historias que requieren mayor prevención



Las historias con menor indicador j son:



1\. **HU-03 = 0.75**

2\. **HU-06 = 0.80**

3\. **HU-05 = 0.83**

4\. **HU-04 = 0.86**



Estas historias deberán recibir mayor atención preventiva.



Las acciones recomendadas son:



- revisión anticipada de requisitos;

- revisión mediante IA;

- diseño de casos de prueba antes del desarrollo;

- validación de criterios de aceptación;

- pruebas tempranas;

- revisión de conectividad;

- revisión de contenido.



---



# 9. Métricas relacionadas con la Mixteca



La calidad será evaluada considerando las condiciones tecnológicas del contexto.



## Conectividad



**Tasa de éxito con conexión limitada = pruebas exitosas / pruebas realizadas × 100**



Meta:



**≥ 90 %**



## Audio



Se registrará:



- tamaño del archivo;

- formato;

- tiempo de carga;

- tiempo de reproducción;

- comportamiento ante interrupción de conexión.



## Dispositivos



Se deberán realizar pruebas en diferentes dispositivos móviles y computadoras cuando estén disponibles.



## Usabilidad



Se medirá el porcentaje de usuarios que logran completar una tarea sin asistencia.



**Meta: ≥ 90 %**



---



# 10. Registro de defectos



Cada defecto deberá registrar:



| Campo | Descripción |

|---|---|

| ID | Identificador |

| HU | Historia afectada |

| Descripción | Problema encontrado |

| Severidad | Baja, media, alta o crítica |

| Prioridad | Prioridad de corrección |

| Responsable | Persona asignada |

| Estado | Abierto, proceso o cerrado |

| Evidencia | Captura o prueba |

| Corrección | Solución realizada |

| Fecha | Fecha de resolución |



---



# 11. Frecuencia de medición



Las métricas serán revisadas:



- al terminar una historia;

- después de las pruebas;

- después de una corrección importante;

- al finalizar una iteración;

- antes de considerar terminado el producto.



---



# 12. Criterio de mejora



Si una historia presenta:



**j < 1.00**



se deberá analizar la causa del exceso de corrección.



Las posibles acciones son:



- aumentar revisión de requisitos;

- agregar pruebas;

- mejorar criterios de aceptación;

- revisar diseño;

- realizar auditoría mediante IA;

- probar antes de integrar;

- documentar errores recurrentes.



El objetivo es que las siguientes iteraciones requieran menos correcciones.



---



# 13. Conclusión



Las métricas permiten evaluar objetivamente la calidad del proyecto.



El indicador j proporciona una medida sencilla para comparar el esfuerzo destinado a prevenir errores con el esfuerzo requerido para corregirlos.



El resultado global inicial de **0.88** muestra que se debe fortalecer la prevención.



La medición individual por historia permite identificar las funcionalidades que requieren mayor atención y relacionar directamente el esfuerzo de calidad con el backlog.



Además, las métricas de conectividad, audio, usabilidad y validación permiten adaptar la evaluación a las condiciones del contexto de la región Mixteca.



