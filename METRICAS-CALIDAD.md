# MÃ‰TRICAS DE CALIDAD



## 1. PropÃ³sito



Este documento complementa el Plan de Calidad mediante mÃ©tricas cuantificables para evaluar el desempeÃ±o y la calidad de las historias de usuario del proyecto.



Las mÃ©tricas permiten transformar los objetivos de calidad en valores que puedan medirse y compararse durante las iteraciones.



---



# 2. MÃ©tricas generales



| MÃ©trica | FÃ³rmula | Meta |

|---|---|---:|

| Cumplimiento de criterios | Criterios cumplidos / criterios totales Ã— 100 | â‰¥ 95 % |

| Cobertura de pruebas | Casos ejecutados / casos planeados Ã— 100 | â‰¥ 90 % |

| Correcciones exitosas | Defectos corregidos / defectos encontrados Ã— 100 | â‰¥ 95 % |

| Contenido validado | Contenido validado / contenido publicado Ã— 100 | 100 % |

| Historias aceptadas | HU aceptadas / HU terminadas Ã— 100 | â‰¥ 95 % |

| PrevenciÃ³n contra correcciÃ³n | Hp / Hc | â‰¥ 1.00 |

| Pruebas de conectividad | Pruebas exitosas / pruebas realizadas Ã— 100 | â‰¥ 90 % |

| Accesibilidad | Criterios cumplidos / criterios evaluados Ã— 100 | â‰¥ 90 % |



---



# 3. Indicador j



El indicador utilizado para comparar el esfuerzo preventivo y correctivo es:



**j = Horas de prevenciÃ³n / Horas de correcciÃ³n**



Donde:



- **Hp:** horas utilizadas para prevenir errores.

- **Hc:** horas utilizadas para corregir errores.



## InterpretaciÃ³n



| Valor de j | InterpretaciÃ³n |

|---:|---|

| j > 1 | Mayor esfuerzo preventivo |

| j = 1 | PrevenciÃ³n y correcciÃ³n equivalentes |

| j < 1 | Mayor esfuerzo correctivo |



El objetivo del proyecto es alcanzar progresivamente:



**j â‰¥ 1.00**



---



# 4. EstimaciÃ³n por historia de usuario



Para las estimaciones se utiliza un valor acadÃ©mico de referencia de:



**$150 MXN por hora**



Este valor no representa un precio comercial. Se utiliza Ãºnicamente para comparar el esfuerzo econÃ³mico de las actividades de calidad.



| Historia | PrevenciÃ³n | EvaluaciÃ³n | CorrecciÃ³n | j |

|---|---:|---:|---:|---:|

| HU-01 | 4 h | 2 h | 3 h | 1.33 |

| HU-02 | 5 h | 3 h | 5 h | 1.00 |

| HU-03 | 6 h | 3 h | 8 h | 0.75 |

| HU-04 | 6 h | 3 h | 7 h | 0.86 |

| HU-05 | 5 h | 3 h | 6 h | 0.83 |

| HU-06 | 4 h | 3 h | 5 h | 0.80 |



---



# 5. CÃ¡lculos



## HU-01



**j = 4 / 3**



**j = 1.33**



La prevenciÃ³n es superior a la correcciÃ³n estimada.



---



## HU-02



**j = 5 / 5**



**j = 1.00**



Existe equilibrio entre prevenciÃ³n y correcciÃ³n.



---



## HU-03



**j = 6 / 8**



**j = 0.75**



Existe mayor esfuerzo correctivo que preventivo.



---



## HU-04



**j = 6 / 7**



**j = 0.86**



La prevenciÃ³n todavÃ­a es menor que la correcciÃ³n.



---



## HU-05



**j = 5 / 6**



**j = 0.83**



Existe oportunidad para aumentar la prevenciÃ³n.



---



## HU-06



**j = 4 / 5**



**j = 0.80**



Se requiere incrementar las actividades preventivas.



---



# 6. Indicador global



Las horas estimadas son:



**PrevenciÃ³n = 30 horas**



**CorrecciÃ³n = 34 horas**



Por lo tanto:



**j global = 30 / 34**



**j global = 0.88**



## InterpretaciÃ³n



El resultado **0.88** indica que actualmente se estima un mayor esfuerzo de correcciÃ³n que de prevenciÃ³n.



Por esta razÃ³n, una de las metas de las siguientes iteraciones serÃ¡ incrementar las actividades preventivas.



---



# 7. Costo de calidad



Se considera:



**Costo de prevenciÃ³n = Horas de prevenciÃ³n Ã— $150**



**Costo de evaluaciÃ³n = Horas de evaluaciÃ³n Ã— $150**



**Costo de correcciÃ³n = Horas de correcciÃ³n Ã— $150**



**Costo total de calidad = PrevenciÃ³n + EvaluaciÃ³n + CorrecciÃ³n**



| HU | PrevenciÃ³n | EvaluaciÃ³n | CorrecciÃ³n | Total |

|---|---:|---:|---:|---:|

| HU-01 | $600 | $300 | $450 | $1,350 |

| HU-02 | $750 | $450 | $750 | $1,950 |

| HU-03 | $900 | $450 | $1,200 | $2,550 |

| HU-04 | $900 | $450 | $1,050 | $2,400 |

| HU-05 | $750 | $450 | $900 | $2,100 |

| HU-06 | $600 | $450 | $750 | $1,800 |

| **TOTAL** | **$4,500** | **$2,550** | **$5,100** | **$12,150** |



---



# 8. Historias que requieren mayor prevenciÃ³n



Las historias con menor indicador j son:



1\. **HU-03 = 0.75**

2\. **HU-06 = 0.80**

3\. **HU-05 = 0.83**

4\. **HU-04 = 0.86**



Estas historias deberÃ¡n recibir mayor atenciÃ³n preventiva.



Las acciones recomendadas son:



- revisiÃ³n anticipada de requisitos;

- revisiÃ³n mediante IA;

- diseÃ±o de casos de prueba antes del desarrollo;

- validaciÃ³n de criterios de aceptaciÃ³n;

- pruebas tempranas;

- revisiÃ³n de conectividad;

- revisiÃ³n de contenido.



---



# 9. MÃ©tricas relacionadas con la Mixteca



La calidad serÃ¡ evaluada considerando las condiciones tecnolÃ³gicas del contexto.



## Conectividad



**Tasa de Ã©xito con conexiÃ³n limitada = pruebas exitosas / pruebas realizadas Ã— 100**



Meta:



**â‰¥ 90 %**



## Audio



Se registrarÃ¡:



- tamaÃ±o del archivo;

- formato;

- tiempo de carga;

- tiempo de reproducciÃ³n;

- comportamiento ante interrupciÃ³n de conexiÃ³n.



## Dispositivos



Se deberÃ¡n realizar pruebas en diferentes dispositivos mÃ³viles y computadoras cuando estÃ©n disponibles.



## Usabilidad



Se medirÃ¡ el porcentaje de usuarios que logran completar una tarea sin asistencia.



**Meta: â‰¥ 90 %**



---



# 10. Registro de defectos



Cada defecto deberÃ¡ registrar:



| Campo | DescripciÃ³n |

|---|---|

| ID | Identificador |

| HU | Historia afectada |

| DescripciÃ³n | Problema encontrado |

| Severidad | Baja, media, alta o crÃ­tica |

| Prioridad | Prioridad de correcciÃ³n |

| Responsable | Persona asignada |

| Estado | Abierto, proceso o cerrado |

| Evidencia | Captura o prueba |

| CorrecciÃ³n | SoluciÃ³n realizada |

| Fecha | Fecha de resoluciÃ³n |



---



# 11. Frecuencia de mediciÃ³n



Las mÃ©tricas serÃ¡n revisadas:



- al terminar una historia;

- despuÃ©s de las pruebas;

- despuÃ©s de una correcciÃ³n importante;

- al finalizar una iteraciÃ³n;

- antes de considerar terminado el producto.



---



# 12. Criterio de mejora



Si una historia presenta:



**j < 1.00**



se deberÃ¡ analizar la causa del exceso de correcciÃ³n.



Las posibles acciones son:



- aumentar revisiÃ³n de requisitos;

- agregar pruebas;

- mejorar criterios de aceptaciÃ³n;

- revisar diseÃ±o;

- realizar auditorÃ­a mediante IA;

- probar antes de integrar;

- documentar errores recurrentes.



El objetivo es que las siguientes iteraciones requieran menos correcciones.



---



# 13. ConclusiÃ³n



Las mÃ©tricas permiten evaluar objetivamente la calidad del proyecto.



El indicador j proporciona una medida sencilla para comparar el esfuerzo destinado a prevenir errores con el esfuerzo requerido para corregirlos.



El resultado global inicial de **0.88** muestra que se debe fortalecer la prevenciÃ³n.



La mediciÃ³n individual por historia permite identificar las funcionalidades que requieren mayor atenciÃ³n y relacionar directamente el esfuerzo de calidad con el backlog.



AdemÃ¡s, las mÃ©tricas de conectividad, audio, usabilidad y validaciÃ³n permiten adaptar la evaluaciÃ³n a las condiciones del contexto de la regiÃ³n Mixteca.


