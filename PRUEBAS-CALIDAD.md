# PRUEBAS DE CALIDAD DEL PROYECTO



## 1. Objetivo
.


Definir las pruebas necesarias para verificar que las historias de usuario

cumplan sus requisitos y criterios de aceptación.



Las pruebas consideran tanto el funcionamiento del sistema como las

condiciones particulares del contexto de la región Mixteca.



---



# 2. Estrategia de pruebas



Las pruebas se realizarán en diferentes niveles:



1\. Pruebas funcionales.

2\. Pruebas de integración.

3\. Pruebas de usabilidad.

4\. Pruebas de rendimiento.

5\. Pruebas de conectividad.

6\. Pruebas de accesibilidad.

7\. Pruebas de contenido.

8\. Pruebas de regresión.



---



# 3. Pruebas funcionales por historia



| ID | Historia | Prueba | Resultado esperado |
|---|---|---|---|
| PF-01 | HU-01 | Buscar palabra existente | Se muestran los resultados correctos |
| PF-02 | HU-01 | Buscar palabra inexistente | Se informa que no existen resultados |
| PF-03 | HU-01 | Búsqueda vacía | El sistema solicita una entrada válida |
| PF-04 | HU-02 | Reproducir pronunciación | El audio comienza correctamente |
| PF-05 | HU-02 | Pausar pronunciación | El audio se detiene |
| PF-06 | HU-02 | Reanudar audio | El audio continúa |
| PF-07 | HU-03 | Enviar aportación válida | La aportación queda registrada |
| PF-08 | HU-03 | Enviar datos incompletos | El sistema solicita completar los campos |
| PF-09 | HU-04 | Consultar memoria cultural | Se muestra el contenido solicitado |
| PF-10 | HU-04 | Navegar entre contenidos | La navegación funciona correctamente |
| PF-11 | HU-05 | Aprobar contenido | El contenido cambia a estado aprobado |
| PF-12 | HU-05 | Rechazar contenido | El contenido cambia a estado rechazado |
| PF-13 | HU-05 | Usuario sin permisos | El sistema impide la acción |
| PF-14 | HU-06 | Reproducir pronunciación | El audio funciona correctamente |
| PF-15 | HU-06 | Pausar pronunciación | El audio se detiene correctamente |



---



# 4. Pruebas de conectividad



Debido al contexto del proyecto se deberán realizar pruebas con diferentes

condiciones de red.



| Prueba | Condición | Resultado esperado |
|---|---|---|
| PC-01 | Conexión estable | Sistema funcional |
| PC-02 | Conexión lenta | Contenido principal disponible |
| PC-03 | Conexión intermitente | El sistema maneja la interrupción |
| PC-04 | Recuperación de conexión | La operación puede continuar |
| PC-05 | Audio con conexión lenta | El audio carga sin errores críticos |



---



# 5. Pruebas de rendimiento



Se evaluarán:


- tiempo de respuesta;

- tiempo de carga;

- tamaño de recursos;

- consumo de datos;

- comportamiento de archivos de audio;

- comportamiento con múltiples consultas.



## Meta



Las funciones principales deberán responder preferentemente en un máximo

objetivo de 3 segundos bajo condiciones de conectividad estable.



En conexiones lentas se priorizará que el contenido esencial pueda ser

consultado aunque los elementos multimedia requieran mayor tiempo.



---



# 6. Pruebas de audio



Los archivos de audio deberán evaluarse considerando:



- formato;

- tamaño;

- calidad;

- tiempo de carga;

- reproducción;

- pausa;

- reanudación;

- compatibilidad;

- conexión limitada.



## Criterios



Un archivo de audio se considerará satisfactorio cuando:



- pueda reproducirse;

- pueda pausarse;

- pueda reanudarse;

- sea compatible con los dispositivos definidos;

- no presente errores críticos;

- tenga un tamaño razonable para el contexto de conectividad.
  
-Comprensión: El mensaje o información transmitida debe ser entendible para el oyente.


---



# 7. Pruebas de usabilidad



Las pruebas de usabilidad evaluarán si los usuarios pueden realizar las

funciones principales sin conocimientos técnicos especializados.



## Actividades



El usuario deberá intentar:



1\. Buscar una palabra.

2\. Consultar una expresión.

3\. Escuchar una pronunciación.

4\. Consultar información cultural.

5\. Realizar una aportación cuando corresponda.



## Indicador



**Tasa de éxito = tareas completadas correctamente / tareas realizadas × 100**



### Meta



**≥ 90 %**



---



# 8. Pruebas de accesibilidad



Se revisarán aspectos como:



- legibilidad;

- tamaño de texto;

- navegación;

- etiquetas;

- contraste;

- estructura de contenido;

- elementos multimedia.



Como referencia se utilizarán los criterios de WCAG 2.2.



---



# 9. Pruebas de contenido



El contenido cultural y lingüístico requiere una revisión adicional.



Se comprobará:



- exactitud;

- integridad;

- consistencia;

- claridad;

- origen de la información;

- estado de validación.



El contenido que requiera validación no deberá considerarse publicado hasta

completar el proceso correspondiente.



---



# 10. Pruebas de seguridad y permisos



Especialmente para HU-05 se comprobará:



- acceso autorizado;

- acceso no autorizado;

- permisos administrativos;

- aprobación;

- rechazo;

- modificación;

- registro de cambios.



## Resultado esperado



Un usuario sin los permisos correspondientes no deberá poder realizar

acciones administrativas.



---



# 11. Pruebas de regresión



Después de corregir un defecto se deberán repetir las pruebas relacionadas

para comprobar que la corrección no haya generado nuevos problemas.



Ejemplo:



Si se corrige la reproducción de audio de HU-02, deberán repetirse:



- reproducción;

- pausa;

- reanudación;

- prueba en dispositivo móvil;

- prueba con conexión limitada.



---



# 12. Registro de pruebas



Cada prueba deberá documentarse con:



| Campo | Descripción |
|---|---|
| ID | Identificador |
| HU | Historia relacionada |
| Fecha | Fecha de ejecución |
| Responsable | Persona que realiza la prueba |
| Condición | Ambiente de prueba |
| Resultado esperado | Resultado definido |
| Resultado obtenido | Resultado real |
| Estado | Aprobada / Fallida |
| Evidencia | Captura o registro |
| Observaciones | Comentarios |



---



# 13. Criterios de aprobación



Una historia podrá aprobarse cuando:



- las pruebas críticas sean exitosas;

- los criterios de aceptación se cumplan;

- no existan defectos críticos abiertos;

- los problemas importantes estén documentados;

- las pruebas de conectividad correspondientes sean satisfactorias;

- exista evidencia de las pruebas.



---



# 14. Relación con el indicador j



Las pruebas forman parte de las actividades de evaluación.



Una mayor cantidad de pruebas preventivas puede ayudar a detectar errores

antes de que lleguen a una etapa de corrección más costosa.



Por esta razón, los resultados de las pruebas podrán utilizarse para ajustar

las horas de prevención y corrección estimadas para cada historia.



---



# 15. Relación con CMMI.



Las pruebas apoyan principalmente las actividades de:



- verificación;

- validación;

- medición;

- aseguramiento de calidad.



El resultado de cada prueba debe conservarse como evidencia.



---



# 16. Relación con MoProSoft



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



Un defecto solamente podrá cerrarse cuando:



1\. se haya implementado una corrección;

2\. se haya ejecutado nuevamente la prueba;

3\. el resultado sea satisfactorio;

4\. no se haya generado una regresión;

5\. exista evidencia;

6\. se registre la fecha de cierre.



---



# 18. Conclusión



El plan de pruebas permite verificar de manera sistemática las

funcionalidades del proyecto.



La estrategia no se limita a comprobar que las funciones principales

funcionen, sino que considera conectividad, rendimiento, audio, usabilidad,

accesibilidad, seguridad y calidad del contenido.



Esto permite adaptar el proceso de calidad a las condiciones del contexto

Mixteca y reducir la posibilidad de detectar errores únicamente después de

haber terminado el desarrollo.




