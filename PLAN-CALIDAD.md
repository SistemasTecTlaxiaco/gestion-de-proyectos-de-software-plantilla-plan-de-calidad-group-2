# PLAN DE CALIDAD DEL PROYECTO



## GestiÃ³n de Proyectos de Software



**Proyecto:** Plataforma comunitaria para la preservaciÃ³n y transmisiÃ³n de la lengua y memoria cultural de Santa MarÃ­a Cuquila

**Asignatura:** GestiÃ³n de Proyectos de Software

**Unidad:** 2

**Documento:** Plan de Calidad

**Fecha:** Septiembre de 2026



---



# 1. IntroducciÃ³n



El presente Plan de Calidad establece los criterios, objetivos, mÃ©tricas, actividades de prevenciÃ³n, evaluaciÃ³n y correcciÃ³n que se utilizarÃ¡n para controlar la calidad del proyecto de software orientado a la preservaciÃ³n y transmisiÃ³n de la lengua y memoria cultural de Santa MarÃ­a Cuquila.



El sistema contempla funcionalidades para consultar palabras y expresiones, escuchar pronunciaciones, aportar conocimiento comunitario, consultar memoria cultural y validar contenido antes de su publicaciÃ³n.



La calidad del proyecto no se limitarÃ¡ a comprobar que el software funcione. TambiÃ©n se considerarÃ¡n aspectos relacionados con facilidad de uso, accesibilidad, rendimiento, disponibilidad, mantenibilidad, integridad de la informaciÃ³n y adaptaciÃ³n al contexto de la regiÃ³n Mixteca.



Para establecer el plan se toman como referencia prÃ¡cticas de CMMI y MoProSoft, ademÃ¡s de modelos y recomendaciones complementarias como ISO/IEC 25010:2023 y WCAG 2.2.



ISO/IEC 25010:2023 proporciona un modelo de calidad para productos de software que puede utilizarse para especificar, medir y evaluar caracterÃ­sticas de calidad durante el ciclo de vida del producto.



WCAG 2.2 proporciona criterios verificables para mejorar la accesibilidad del contenido web en diferentes dispositivos.



---



# 2. Objetivo general de calidad



Garantizar que el producto de software cumpla los requisitos funcionales y no funcionales definidos para el proyecto, proporcionando una plataforma confiable, usable, accesible y mantenible que pueda funcionar adecuadamente bajo las condiciones tecnolÃ³gicas y de conectividad presentes en la regiÃ³n Mixteca.



---



# 3. Objetivos especÃ­ficos de calidad



## 3.1 Calidad funcional



Garantizar que cada historia de usuario implemente correctamente la funcionalidad descrita y que sus criterios de aceptaciÃ³n puedan comprobarse mediante pruebas.



**Meta:** al menos 95 % de los criterios de aceptaciÃ³n deben cumplirse antes de considerar una historia terminada.



## 3.2 Usabilidad



La plataforma debe permitir que los usuarios consulten informaciÃ³n y reproduzcan pronunciaciones sin requerir conocimientos tÃ©cnicos avanzados.



**Meta:** las funciones principales deben poder realizarse sin asistencia tÃ©cnica durante las pruebas de usuario.



## 3.3 Rendimiento



El sistema debe evitar cargas innecesarias de informaciÃ³n, especialmente en contenido multimedia.



**Meta:** las pÃ¡ginas principales deben responder en un tiempo mÃ¡ximo objetivo de 3 segundos en condiciones de conectividad estable y degradar de manera controlada cuando la conexiÃ³n sea lenta.



## 3.4 Compatibilidad con conectividad limitada



El sistema debe considerar conexiones mÃ³viles lentas o intermitentes.



Se priorizarÃ¡n:



* pÃ¡ginas ligeras;

* imÃ¡genes comprimidas;

* archivos de audio optimizados;

* carga bajo demanda;

* ausencia de elementos innecesarios;

* posibilidad de consultar informaciÃ³n textual sin descargar archivos pesados.



## 3.5 Calidad del contenido



La informaciÃ³n relacionada con palabras, expresiones, pronunciaciones y memoria cultural debe contar con mecanismos de revisiÃ³n y validaciÃ³n antes de su publicaciÃ³n.



**Meta:** 100 % del contenido destinado a publicaciÃ³n debe pasar por un proceso de validaciÃ³n.



## 3.6 Accesibilidad



La interfaz debe considerar principios de accesibilidad, incluyendo texto legible, navegaciÃ³n clara, contraste suficiente y alternativas adecuadas para contenido multimedia.



Se utilizarÃ¡n como referencia los criterios verificables de WCAG 2.2.



## 3.7 Mantenibilidad



El cÃ³digo y la documentaciÃ³n deberÃ¡n mantenerse organizados para facilitar futuras modificaciones.



**Meta:** cada funcionalidad terminada debe contar con documentaciÃ³n mÃ­nima, criterios de aceptaciÃ³n y evidencia de prueba.



---



# 4. Alcance del Plan de Calidad



El Plan de Calidad cubre:



1\. Historias de usuario.

2\. Requisitos funcionales.

3\. Criterios de aceptaciÃ³n.

4\. DiseÃ±o y desarrollo.

5\. Pruebas.

6\. ValidaciÃ³n del contenido.

7\. RevisiÃ³n mediante inteligencia artificial.

8\. MÃ©tricas de calidad.

9\. Costos de prevenciÃ³n y correcciÃ³n.

10\. Control de cambios.

11\. DocumentaciÃ³n.

12\. AdaptaciÃ³n a condiciones de conectividad limitada.



El plan no representa una certificaciÃ³n formal del proyecto en CMMI, MoProSoft, ISO/IEC 25010 o WCAG. Estos modelos y estÃ¡ndares se utilizan como referencias para diseÃ±ar y evaluar las prÃ¡cticas de calidad del proyecto.



---



# 5. AplicaciÃ³n de CMMI



CMMI se utilizarÃ¡ como referencia para organizar las actividades relacionadas con planificaciÃ³n, mediciÃ³n, aseguramiento de calidad, verificaciÃ³n y validaciÃ³n.



La aplicaciÃ³n al proyecto serÃ¡ prÃ¡ctica y proporcional al tamaÃ±o del equipo.



## 5.1 PlanificaciÃ³n



Antes de desarrollar una funcionalidad se identificarÃ¡n:



* historia de usuario;

* objetivo;

* criterios de aceptaciÃ³n;

* riesgos;

* pruebas necesarias;

* responsable;

* evidencia requerida.



## 5.2 MediciÃ³n y anÃ¡lisis



Se registrarÃ¡n mÃ©tricas relacionadas con:



* horas de prevenciÃ³n;

* horas de correcciÃ³n;

* defectos encontrados;

* criterios de aceptaciÃ³n cumplidos;

* pruebas realizadas;

* historias terminadas;

* porcentaje de cobertura de pruebas.



## 5.3 Aseguramiento de calidad



Se realizarÃ¡n revisiones periÃ³dicas de:



* historias de usuario;

* cÃ³digo;

* criterios de aceptaciÃ³n;

* documentaciÃ³n;

* resultados de pruebas;

* cambios realizados.



## 5.4 VerificaciÃ³n



Se comprobarÃ¡ que el producto construido cumple los requisitos especificados.



Ejemplos:



* comprobar que una palabra pueda consultarse;

* comprobar que el audio pueda reproducirse;

* comprobar que una aportaciÃ³n pueda registrarse;

* comprobar que un administrador pueda validar contenido.



## 5.5 ValidaciÃ³n



Se comprobarÃ¡ que la soluciÃ³n realmente responde a las necesidades planteadas para el contexto del proyecto.



La validaciÃ³n considerarÃ¡:



* facilidad de uso;

* comprensiÃ³n de la interfaz;

* conectividad;

* caracterÃ­sticas de los dispositivos;

* utilidad del contenido;

* comprensiÃ³n de las funcionalidades.



---



# 6. AplicaciÃ³n de MoProSoft



MoProSoft es un modelo de procesos dirigido a organizaciones dedicadas al desarrollo y mantenimiento de software. La Norma Mexicana establece que puede utilizarse tanto en organizaciones con procesos establecidos como en organizaciones que todavÃ­a no cuentan con ellos.



Para este proyecto se adaptarÃ¡n sus prÃ¡cticas a una escala acadÃ©mica.



## 6.1 GestiÃ³n del proyecto



Se mantendrÃ¡ control sobre:



* backlog;

* historias de usuario;

* responsables;

* prioridades;

* avances;

* riesgos;

* entregables;

* evidencias.



## 6.2 Desarrollo y mantenimiento de software



Cada historia de usuario seguirÃ¡ el ciclo:



**Requisito â†’ diseÃ±o â†’ desarrollo â†’ prueba â†’ revisiÃ³n â†’ correcciÃ³n â†’ aceptaciÃ³n**



No se considerarÃ¡ terminada una historia Ãºnicamente porque el cÃ³digo funcione.



## 6.3 GestiÃ³n de procesos



Las actividades de calidad se documentarÃ¡n para poder repetirlas en futuras iteraciones.



Entre ellas:



* revisiÃ³n de historias;

* revisiÃ³n de criterios;

* pruebas;

* registro de defectos;

* correcciones;

* evaluaciÃ³n de mÃ©tricas.



## 6.4 GestiÃ³n de recursos



Los recursos considerados son:



* equipo de desarrollo;

* computadoras;

* dispositivos mÃ³viles;

* conexiÃ³n a Internet;

* repositorio GitHub;

* herramientas de desarrollo;

* herramientas de prueba;

* inteligencia artificial como apoyo a la revisiÃ³n.



---



# 7. Matriz CMMI + MoProSoft aplicada al proyecto



| Necesidad del proyecto | CMMI                     | MoProSoft                  | AplicaciÃ³n                                 |

| ---------------------- | ------------------------ | -------------------------- | ------------------------------------------ |

| Planificar historias   | PlanificaciÃ³n            | GestiÃ³n de proyectos       | Definir alcance, responsable y criterios   |

| Medir calidad          | MediciÃ³n y anÃ¡lisis      | GestiÃ³n de procesos        | Registrar mÃ©tricas                         |

| Revisar requisitos     | GestiÃ³n de requisitos    | Desarrollo y mantenimiento | Revisar claridad y verificabilidad         |

| Revisar producto       | Aseguramiento de calidad | Desarrollo y mantenimiento | Revisiones antes de aceptar                |

| Realizar pruebas       | VerificaciÃ³n             | Desarrollo y mantenimiento | Ejecutar casos de prueba                   |

| Validar con usuarios   | ValidaciÃ³n               | GestiÃ³n de proyectos       | Comprobar utilidad                         |

| Controlar cambios      | GestiÃ³n de configuraciÃ³n | GestiÃ³n de proyectos       | Registrar modificaciones                   |

| Analizar riesgos       | GestiÃ³n de riesgos       | GestiÃ³n de proyectos       | Identificar problemas antes del desarrollo |



---



# 8. Historias de usuario evaluadas



El anÃ¡lisis de calidad se realizarÃ¡ sobre las seis historias de usuario principales del proyecto:



| ID    | Historia de usuario              | Prioridad |

| ----- | -------------------------------- | --------- |

| HU-01 | Consultar palabras y expresiones | Alta      |

| HU-02 | Escuchar pronunciaciones         | Alta      |

| HU-03 | Aportar conocimiento             | Media     |

| HU-04 | Consultar memoria cultural       | Media     |

| HU-05 | Validar contenido                | Alta      |

| HU-06 | Escuchar pronunciaciones         | Media     |



Estas historias constituyen la unidad principal para el anÃ¡lisis de prevenciÃ³n, correcciÃ³n y costo de calidad.



---



# 9. Costo de calidad



Para este proyecto se utilizarÃ¡ una clasificaciÃ³n simplificada:



### Costos de prevenciÃ³n



Son las horas utilizadas para evitar que aparezcan errores.



Ejemplos:



* anÃ¡lisis de requisitos;

* revisiÃ³n de historias;

* diseÃ±o de criterios de aceptaciÃ³n;

* revisiÃ³n mediante IA;

* planificaciÃ³n de pruebas.



### Costos de evaluaciÃ³n



Son las horas utilizadas para detectar problemas.



Ejemplos:



* pruebas funcionales;

* pruebas de usabilidad;

* revisiÃ³n de contenido;

* pruebas de conectividad;

* inspecciÃ³n de cÃ³digo.



### Costos de correcciÃ³n



Son las horas utilizadas para resolver errores encontrados despuÃ©s de la implementaciÃ³n.



Ejemplos:



* corregir errores de programaciÃ³n;

* modificar una interfaz;

* optimizar audio;

* corregir criterios;

* modificar contenido.



---



# 10. Indicador j: prevenciÃ³n contra correcciÃ³n



Para medir la relaciÃ³n entre prevenciÃ³n y correcciÃ³n se utilizarÃ¡:



**j = Horas de prevenciÃ³n / Horas de correcciÃ³n**



InterpretaciÃ³n:



* **j > 1:** existe mayor esfuerzo preventivo que correctivo.

* **j = 1:** el esfuerzo preventivo y correctivo es equivalente.

* **j < 1:** existe mayor esfuerzo correctivo que preventivo.



Las horas son una estimaciÃ³n acadÃ©mica para comparar el esfuerzo requerido por cada historia de usuario. No representan una factura comercial.



Para calcular el costo se utiliza un valor interno de referencia de:



**$150 MXN por hora de trabajo**



---



# 11. CÃ¡lculo de j por historia de usuario



| HU        | PrevenciÃ³n (h) | EvaluaciÃ³n (h) | CorrecciÃ³n (h) | j = PrevenciÃ³n/Corr. | Costo prevenciÃ³n | Costo evaluaciÃ³n | Costo correcciÃ³n | Costo total |

| --------- | -------------: | -------------: | -------------: | -------------------: | ---------------: | ---------------: | ---------------: | ----------: |

| HU-01     |              4 |              2 |              3 |                 1.33 |             $600 |             $300 |             $450 |      $1,350 |

| HU-02     |              5 |              3 |              5 |                 1.00 |             $750 |             $450 |             $750 |      $1,950 |

| HU-03     |              6 |              3 |              8 |                 0.75 |             $900 |             $450 |           $1,200 |      $2,550 |

| HU-04     |              6 |              3 |              7 |                 0.86 |             $900 |             $450 |           $1,050 |      $2,400 |

| HU-05     |              5 |              3 |              6 |                 0.83 |             $750 |             $450 |             $900 |      $2,100 |

| HU-06     |              4 |              3 |              5 |                 0.80 |             $600 |             $450 |             $750 |      $1,800 |

| **Total** |         **30** |         **17** |         **34** |             **0.88** |       **$4,500** |       **$2,550** |       **$5,100** | **$12,150** |



### InterpretaciÃ³n



El indicador global es:



**j = 30 / 34 = 0.88**



Esto significa que, en la estimaciÃ³n inicial, el proyecto dedica menos horas a prevenciÃ³n que a correcciÃ³n.



Por lo tanto, existe una oportunidad clara de mejorar la calidad mediante mayor inversiÃ³n preventiva.



El objetivo para las siguientes iteraciones serÃ¡ elevar progresivamente el indicador hacia:



**j â‰¥ 1.00**



Esto significa que se buscarÃ¡ invertir al menos una hora de prevenciÃ³n por cada hora estimada de correcciÃ³n.



---



# 12. AnÃ¡lisis individual de las historias



## HU-01 â€“ Consultar palabras y expresiones



### Riesgos



* bÃºsqueda poco clara;

* resultados incompletos;

* errores ortogrÃ¡ficos;

* tiempos de respuesta elevados.



### PrevenciÃ³n



* definir criterios de bÃºsqueda;

* revisar estructura de datos;

* crear casos de prueba.



### EvaluaciÃ³n



* buscar palabras existentes;

* buscar palabras inexistentes;

* probar diferentes combinaciones.



### CorrecciÃ³n



Se estiman 3 horas debido a posibles ajustes en bÃºsqueda, presentaciÃ³n y datos.



### j



**j = 4 / 3 = 1.33**



La prevenciÃ³n es superior a la correcciÃ³n estimada.



---



# 13. HU-02 â€“ Escuchar pronunciaciones



### Riesgos



* archivos de audio demasiado grandes;

* reproducciÃ³n lenta;

* formato incompatible;

* interrupciones por conectividad.



### PrevenciÃ³n



* utilizar formatos optimizados;

* comprimir audio;

* establecer tamaÃ±o mÃ¡ximo;

* diseÃ±ar carga bajo demanda.



### EvaluaciÃ³n



* probar diferentes dispositivos;

* probar conexiones lentas;

* comprobar reproducciÃ³n y pausa.



### CorrecciÃ³n



Se estiman 5 horas debido a la complejidad adicional del contenido multimedia.



### j



**j = 5 / 5 = 1.00**



La prevenciÃ³n y la correcciÃ³n tienen el mismo esfuerzo estimado.



---



# 14. HU-03 â€“ Aportar conocimiento



### Riesgos



* informaciÃ³n incorrecta;

* formularios difÃ­ciles de utilizar;

* datos incompletos;

* aportaciones sin validaciÃ³n.



### PrevenciÃ³n



* definir campos obligatorios;

* validar entradas;

* establecer reglas de contenido;

* definir flujo de revisiÃ³n.



### EvaluaciÃ³n



* probar datos completos;

* probar datos incompletos;

* probar entradas invÃ¡lidas.



### CorrecciÃ³n



Se estiman 8 horas porque los errores pueden involucrar interfaz, validaciÃ³n y almacenamiento.



### j



**j = 6 / 8 = 0.75**



Existe mayor esfuerzo correctivo que preventivo.



---



# 15. HU-04 â€“ Consultar memoria cultural



### Riesgos



* informaciÃ³n extensa;

* navegaciÃ³n complicada;

* imÃ¡genes pesadas;

* dificultad de consulta con Internet lento.



### PrevenciÃ³n



* organizar la informaciÃ³n por categorÃ­as;

* optimizar imÃ¡genes;

* utilizar contenido ligero;

* definir navegaciÃ³n sencilla.



### EvaluaciÃ³n



* probar navegaciÃ³n;

* revisar tiempos de carga;

* comprobar visualizaciÃ³n en dispositivos mÃ³viles.



### CorrecciÃ³n



Se estiman 7 horas.



### j



**j = 6 / 7 = 0.86**



Se requiere aumentar las actividades preventivas.



---



# 16. HU-05 â€“ Validar contenido



### Riesgos



* publicaciÃ³n de informaciÃ³n incorrecta;

* ausencia de responsable;

* falta de trazabilidad;

* aprobaciÃ³n accidental.



### PrevenciÃ³n



* definir roles;

* establecer estados;

* registrar cambios;

* establecer criterios de aprobaciÃ³n.



### EvaluaciÃ³n



* probar aprobaciÃ³n;

* probar rechazo;

* comprobar historial.



### CorrecciÃ³n



Se estiman 6 horas.



### j



**j = 5 / 6 = 0.83**



Existe oportunidad para aumentar la prevenciÃ³n.



---



# 17. HU-06 â€“ Escuchar pronunciaciones



### Riesgos



* duplicidad con contenido de audio;

* reproducciÃ³n inconsistente;

* archivos demasiado pesados;

* dificultades de acceso desde dispositivos mÃ³viles.



### PrevenciÃ³n



* reutilizar componentes;

* definir estÃ¡ndares de audio;

* optimizar archivos;

* establecer criterios de compatibilidad.



### EvaluaciÃ³n



* probar reproducciÃ³n;

* probar pausa;

* probar dispositivos diferentes;

* probar conexiÃ³n lenta.



### CorrecciÃ³n



Se estiman 5 horas.



### j



**j = 4 / 5 = 0.80**



El esfuerzo preventivo debe incrementarse.



---



# 18. AdaptaciÃ³n al contexto de la Mixteca



La calidad del software debe evaluarse considerando las condiciones reales en las que podrÃ­a utilizarse.



No se puede asumir que todos los usuarios tendrÃ¡n:



* Internet de alta velocidad;

* equipos modernos;

* telÃ©fonos con gran capacidad de almacenamiento;

* conexiÃ³n permanente;

* conocimientos tÃ©cnicos avanzados.



Por esta razÃ³n, el plan considera:



## 18.1 Conectividad



Las pruebas deben incluir conexiones lentas e intermitentes.



## 18.2 Dispositivos



Se deben realizar pruebas en telÃ©fonos y computadoras con diferentes capacidades.



## 18.3 Contenido multimedia



Los archivos de audio deben mantenerse optimizados para evitar consumo innecesario de datos.



## 18.4 Interfaz



La interfaz debe utilizar lenguaje claro, navegaciÃ³n sencilla y elementos visuales fÃ¡ciles de identificar.



## 18.5 Disponibilidad



Las funciones principales deben degradar de forma controlada cuando la conexiÃ³n no sea estable.



## 18.6 Cultura y contenido



La informaciÃ³n comunitaria debe tener mecanismos de revisiÃ³n para evitar modificaciones o publicaciones sin autorizaciÃ³n.



---



# 19. MÃ©tricas de calidad



| MÃ©trica                   | FÃ³rmula                                          | Meta   |

| ------------------------- | ------------------------------------------------ | ------ |

| Cumplimiento de criterios | criterios cumplidos / criterios totales Ã— 100    | â‰¥ 95 % |

| Cobertura de pruebas      | casos ejecutados / casos planeados Ã— 100         | â‰¥ 90 % |

| Correcciones              | defectos corregidos / defectos encontrados Ã— 100 | â‰¥ 95 % |

| Contenido validado        | contenido validado / contenido publicado Ã— 100   | 100 %  |

| Historias aceptadas       | HU aceptadas / HU terminadas Ã— 100               | â‰¥      |




