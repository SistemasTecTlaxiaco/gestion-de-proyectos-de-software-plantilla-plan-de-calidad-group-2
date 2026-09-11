# PRUEBAS DE CALIDAD DEL PROYECTO



## 1. Objetivo



Definir las pruebas necesarias para verificar que las historias de usuario

cumplan sus requisitos y criterios de aceptaciÃ³n.



Las pruebas consideran tanto el funcionamiento del sistema como las

condiciones particulares del contexto de la regiÃ³n Mixteca.



---



# 2. Estrategia de pruebas



Las pruebas se realizarÃ¡n en diferentes niveles:



1\. Pruebas funcionales.

2\. Pruebas de integraciÃ³n.

3\. Pruebas de usabilidad.

4\. Pruebas de rendimiento.

5\. Pruebas de conectividad.

6\. Pruebas de accesibilidad.

7\. Pruebas de contenido.

8\. Pruebas de regresiÃ³n.



---



# 3. Pruebas funcionales por historia



| ID | Historia | Prueba | Resultado esperado |

|---|---|---|---|

| PF-01 | HU-01 | Buscar palabra existente | Se muestran los resultados correctos |

| PF-02 | HU-01 | Buscar palabra inexistente | Se informa que no existen resultados |

| PF-03 | HU-01 | BÃºsqueda vacÃ­a | El sistema solicita una entrada vÃ¡lida |

| PF-04 | HU-02 | Reproducir pronunciaciÃ³n | El audio comienza correctamente |

| PF-05 | HU-02 | Pausar pronunciaciÃ³n | El audio se detiene |

| PF-06 | HU-02 | Reanudar audio | El audio continÃºa |

| PF-07 | HU-03 | Enviar aportaciÃ³n vÃ¡lida | La aportaciÃ³n queda registrada |

| PF-08 | HU-03 | Enviar datos incompletos | El sistema solicita completar los campos |

| PF-09 | HU-04 | Consultar memoria cultural | Se muestra el contenido solicitado |

| PF-10 | HU-04 | Navegar entre contenidos | La navegaciÃ³n funciona correctamente |

| PF-11 | HU-05 | Aprobar contenido | El contenido cambia a estado aprobado |

| PF-12 | HU-05 | Rechazar contenido | El contenido cambia a estado rechazado |

| PF-13 | HU-05 | Usuario sin permisos | El sistema impide la acciÃ³n |

| PF-14 | HU-06 | Reproducir pronunciaciÃ³n | El audio funciona correctamente |

| PF-15 | HU-06 | Pausar pronunciaciÃ³n | El audio se detiene correctamente |



---



# 4. Pruebas de conectividad



Debido al contexto del proyecto se deberÃ¡n realizar pruebas con diferentes

condiciones de red.



| Prueba | CondiciÃ³n | Resultado esperado |

|---|---|---|

| PC-01 | ConexiÃ³n estable | Sistema funcional |

| PC-02 | ConexiÃ³n lenta | Contenido principal disponible |

| PC-03 | ConexiÃ³n intermitente | El sistema maneja la interrupciÃ³n |

| PC-04 | RecuperaciÃ³n de conexiÃ³n | La operaciÃ³n puede continuar |

| PC-05 | Audio con conexiÃ³n lenta | El audio carga sin errores crÃ­ticos |



---



# 5. Pruebas de rendimiento



Se evaluarÃ¡n:



- tiempo de respuesta;

- tiempo de carga;

- tamaÃ±o de recursos;

- consumo de datos;

- comportamiento de archivos de audio;

- comportamiento con mÃºltiples consultas.



## Meta



Las funciones principales deberÃ¡n responder preferentemente en un mÃ¡ximo

objetivo de 3 segundos bajo condiciones de conectividad estable.



En conexiones lentas se priorizarÃ¡ que el contenido esencial pueda ser

consultado aunque los elementos multimedia requieran mayor tiempo.



---



# 6. Pruebas de audio



Los archivos de audio deberÃ¡n evaluarse considerando:



- formato;

- tamaÃ±o;

- calidad;

- tiempo de carga;

- reproducciÃ³n;

- pausa;

- reanudaciÃ³n;

- compatibilidad;

- conexiÃ³n limitada.



## Criterios



Un archivo de audio se considerarÃ¡ satisfactorio cuando:



- pueda reproducirse;

- pueda pausarse;

- pueda reanudarse;

- sea compatible con los dispositivos definidos;

- no presente errores crÃ­ticos;

- tenga un tamaÃ±o razonable para el contexto de conectividad.



---



# 7. Pruebas de usabilidad



Las pruebas de usabilidad evaluarÃ¡n si los usuarios pueden realizar las

funciones principales sin conocimientos tÃ©cnicos especializados.



## Actividades



El usuario deberÃ¡ intentar:



1\. Buscar una palabra.

2\. Consultar una expresiÃ³n.

3\. Escuchar una pronunciaciÃ³n.

4\. Consultar informaciÃ³n cultural.

5\. Realizar una aportaciÃ³n cuando corresponda.



## Indicador



**Tasa de Ã©xito = tareas completadas correctamente / tareas realizadas Ã— 100**



### Meta



**â‰¥ 90 %**



---



# 8. Pruebas de accesibilidad



Se revisarÃ¡n aspectos como:



- legibilidad;

- tamaÃ±o de texto;

- navegaciÃ³n;

- etiquetas;

- contraste;

- estructura de contenido;

- elementos multimedia.



Como referencia se utilizarÃ¡n los criterios de WCAG 2.2.



---



# 9. Pruebas de contenido



El contenido cultural y lingÃ¼Ã­stico requiere una revisiÃ³n adicional.



Se comprobarÃ¡:



- exactitud;

- integridad;

- consistencia;

- claridad;

- origen de la informaciÃ³n;

- estado de validaciÃ³n.



El contenido que requiera validaciÃ³n no deberÃ¡ considerarse publicado hasta

completar el proceso correspondiente.



---



# 10. Pruebas de seguridad y permisos



Especialmente para HU-05 se comprobarÃ¡:



- acceso autorizado;

- acceso no autorizado;

- permisos administrativos;

- aprobaciÃ³n;

- rechazo;

- modificaciÃ³n;

- registro de cambios.



## Resultado esperado



Un usuario sin los permisos correspondientes no deberÃ¡ poder realizar

acciones administrativas.



---



# 11. Pruebas de regresiÃ³n



DespuÃ©s de corregir un defecto se deberÃ¡n repetir las pruebas relacionadas

para comprobar que la correcciÃ³n no haya generado nuevos problemas.



Ejemplo:



Si se corrige la reproducciÃ³n de audio de HU-02, deberÃ¡n repetirse:



- reproducciÃ³n;

- pausa;

- reanudaciÃ³n;

- prueba en dispositivo mÃ³vil;

- prueba con conexiÃ³n limitada.



---



# 12. Registro de pruebas



Cada prueba deberÃ¡ documentarse con:



| Campo | DescripciÃ³n |

|---|---|

| ID | Identificador |

| HU | Historia relacionada |

| Fecha | Fecha de ejecuciÃ³n |

| Responsable | Persona que realiza la prueba |

| CondiciÃ³n | Ambiente de prueba |

| Resultado esperado | Resultado definido |

| Resultado obtenido | Resultado real |

| Estado | Aprobada / Fallida |

| Evidencia | Captura o registro |

| Observaciones | Comentarios |



---



# 13. Criterios de aprobaciÃ³n



Una historia podrÃ¡ aprobarse cuando:



- las pruebas crÃ­ticas sean exitosas;

- los criterios de aceptaciÃ³n se cumplan;

- no existan defectos crÃ­ticos abiertos;

- los problemas importantes estÃ©n documentados;

- las pruebas de conectividad correspondientes sean satisfactorias;

- exista evidencia de las pruebas.



---



# 14. RelaciÃ³n con el indicador j



Las pruebas forman parte de las actividades de evaluaciÃ³n.



Una mayor cantidad de pruebas preventivas puede ayudar a detectar errores

antes de que lleguen a una etapa de correcciÃ³n mÃ¡s costosa.



Por esta razÃ³n, los resultados de las pruebas podrÃ¡n utilizarse para ajustar

las horas de prevenciÃ³n y correcciÃ³n estimadas para cada historia.



---



# 15. RelaciÃ³n con CMMI



Las pruebas apoyan principalmente las actividades de:



- verificaciÃ³n;

- validaciÃ³n;

- mediciÃ³n;

- aseguramiento de calidad.



El resultado de cada prueba debe conservarse como evidencia.



---



# 16. RelaciÃ³n con MoProSoft



Las pruebas forman parte del proceso de desarrollo y mantenimiento del

software.



Los resultados permiten:



- controlar la calidad;

- detectar defectos;

- documentar correcciones;

- evaluar entregables;

- mejorar procesos.



---



# 17. Criterios para cierre de defectos



Un defecto solamente podrÃ¡ cerrarse cuando:



1\. se haya implementado una correcciÃ³n;

2\. se haya ejecutado nuevamente la prueba;

3\. el resultado sea satisfactorio;

4\. no se haya generado una regresiÃ³n;

5\. exista evidencia;

6\. se registre la fecha de cierre.



---



# 18. ConclusiÃ³n



El plan de pruebas permite verificar de manera sistemÃ¡tica las

funcionalidades del proyecto.



La estrategia no se limita a comprobar que las funciones principales

funcionen, sino que considera conectividad, rendimiento, audio, usabilidad,

accesibilidad, seguridad y calidad del contenido.



Esto permite adaptar el proceso de calidad a las condiciones del contexto

Mixteca y reducir la posibilidad de detectar errores Ãºnicamente despuÃ©s de

haber terminado el desarrollo.


