\# PLAN DE CALIDAD DEL PROYECTO



\## Gestión de Proyectos de Software



\*\*Proyecto:\*\* Plataforma comunitaria para la preservación y transmisión de la lengua y memoria cultural de Santa María Cuquila

\*\*Asignatura:\*\* Gestión de Proyectos de Software

\*\*Unidad:\*\* 2

\*\*Documento:\*\* Plan de Calidad

\*\*Fecha:\*\* Septiembre de 2026



\---



\# 1. Introducción



El presente Plan de Calidad establece los criterios, objetivos, métricas, actividades de prevención, evaluación y corrección que se utilizarán para controlar la calidad del proyecto de software orientado a la preservación y transmisión de la lengua y memoria cultural de Santa María Cuquila.



El sistema contempla funcionalidades para consultar palabras y expresiones, escuchar pronunciaciones, aportar conocimiento comunitario, consultar memoria cultural y validar contenido antes de su publicación.



La calidad del proyecto no se limitará a comprobar que el software funcione. También se considerarán aspectos relacionados con facilidad de uso, accesibilidad, rendimiento, disponibilidad, mantenibilidad, integridad de la información y adaptación al contexto de la región Mixteca.



Para establecer el plan se toman como referencia prácticas de CMMI y MoProSoft, además de modelos y recomendaciones complementarias como ISO/IEC 25010:2023 y WCAG 2.2.



ISO/IEC 25010:2023 proporciona un modelo de calidad para productos de software que puede utilizarse para especificar, medir y evaluar características de calidad durante el ciclo de vida del producto.



WCAG 2.2 proporciona criterios verificables para mejorar la accesibilidad del contenido web en diferentes dispositivos.



\---



\# 2. Objetivo general de calidad



Garantizar que el producto de software cumpla los requisitos funcionales y no funcionales definidos para el proyecto, proporcionando una plataforma confiable, usable, accesible y mantenible que pueda funcionar adecuadamente bajo las condiciones tecnológicas y de conectividad presentes en la región Mixteca.



\---



\# 3. Objetivos específicos de calidad



\## 3.1 Calidad funcional



Garantizar que cada historia de usuario implemente correctamente la funcionalidad descrita y que sus criterios de aceptación puedan comprobarse mediante pruebas.



\*\*Meta:\*\* al menos 95 % de los criterios de aceptación deben cumplirse antes de considerar una historia terminada.



\## 3.2 Usabilidad



La plataforma debe permitir que los usuarios consulten información y reproduzcan pronunciaciones sin requerir conocimientos técnicos avanzados.



\*\*Meta:\*\* las funciones principales deben poder realizarse sin asistencia técnica durante las pruebas de usuario.



\## 3.3 Rendimiento



El sistema debe evitar cargas innecesarias de información, especialmente en contenido multimedia.



\*\*Meta:\*\* las páginas principales deben responder en un tiempo máximo objetivo de 3 segundos en condiciones de conectividad estable y degradar de manera controlada cuando la conexión sea lenta.



\## 3.4 Compatibilidad con conectividad limitada



El sistema debe considerar conexiones móviles lentas o intermitentes.



Se priorizarán:



\* páginas ligeras;

\* imágenes comprimidas;

\* archivos de audio optimizados;

\* carga bajo demanda;

\* ausencia de elementos innecesarios;

\* posibilidad de consultar información textual sin descargar archivos pesados.



\## 3.5 Calidad del contenido



La información relacionada con palabras, expresiones, pronunciaciones y memoria cultural debe contar con mecanismos de revisión y validación antes de su publicación.



\*\*Meta:\*\* 100 % del contenido destinado a publicación debe pasar por un proceso de validación.



\## 3.6 Accesibilidad



La interfaz debe considerar principios de accesibilidad, incluyendo texto legible, navegación clara, contraste suficiente y alternativas adecuadas para contenido multimedia.



Se utilizarán como referencia los criterios verificables de WCAG 2.2.



\## 3.7 Mantenibilidad



El código y la documentación deberán mantenerse organizados para facilitar futuras modificaciones.



\*\*Meta:\*\* cada funcionalidad terminada debe contar con documentación mínima, criterios de aceptación y evidencia de prueba.



\---



\# 4. Alcance del Plan de Calidad



El Plan de Calidad cubre:



1\. Historias de usuario.

2\. Requisitos funcionales.

3\. Criterios de aceptación.

4\. Diseño y desarrollo.

5\. Pruebas.

6\. Validación del contenido.

7\. Revisión mediante inteligencia artificial.

8\. Métricas de calidad.

9\. Costos de prevención y corrección.

10\. Control de cambios.

11\. Documentación.

12\. Adaptación a condiciones de conectividad limitada.



El plan no representa una certificación formal del proyecto en CMMI, MoProSoft, ISO/IEC 25010 o WCAG. Estos modelos y estándares se utilizan como referencias para diseñar y evaluar las prácticas de calidad del proyecto.



\---



\# 5. Aplicación de CMMI



CMMI se utilizará como referencia para organizar las actividades relacionadas con planificación, medición, aseguramiento de calidad, verificación y validación.



La aplicación al proyecto será práctica y proporcional al tamaño del equipo.



\## 5.1 Planificación



Antes de desarrollar una funcionalidad se identificarán:



\* historia de usuario;

\* objetivo;

\* criterios de aceptación;

\* riesgos;

\* pruebas necesarias;

\* responsable;

\* evidencia requerida.



\## 5.2 Medición y análisis



Se registrarán métricas relacionadas con:



\* horas de prevención;

\* horas de corrección;

\* defectos encontrados;

\* criterios de aceptación cumplidos;

\* pruebas realizadas;

\* historias terminadas;

\* porcentaje de cobertura de pruebas.



\## 5.3 Aseguramiento de calidad



Se realizarán revisiones periódicas de:



\* historias de usuario;

\* código;

\* criterios de aceptación;

\* documentación;

\* resultados de pruebas;

\* cambios realizados.



\## 5.4 Verificación



Se comprobará que el producto construido cumple los requisitos especificados.



Ejemplos:



\* comprobar que una palabra pueda consultarse;

\* comprobar que el audio pueda reproducirse;

\* comprobar que una aportación pueda registrarse;

\* comprobar que un administrador pueda validar contenido.



\## 5.5 Validación



Se comprobará que la solución realmente responde a las necesidades planteadas para el contexto del proyecto.



La validación considerará:



\* facilidad de uso;

\* comprensión de la interfaz;

\* conectividad;

\* características de los dispositivos;

\* utilidad del contenido;

\* comprensión de las funcionalidades.



\---



\# 6. Aplicación de MoProSoft



MoProSoft es un modelo de procesos dirigido a organizaciones dedicadas al desarrollo y mantenimiento de software. La Norma Mexicana establece que puede utilizarse tanto en organizaciones con procesos establecidos como en organizaciones que todavía no cuentan con ellos.



Para este proyecto se adaptarán sus prácticas a una escala académica.



\## 6.1 Gestión del proyecto



Se mantendrá control sobre:



\* backlog;

\* historias de usuario;

\* responsables;

\* prioridades;

\* avances;

\* riesgos;

\* entregables;

\* evidencias.



\## 6.2 Desarrollo y mantenimiento de software



Cada historia de usuario seguirá el ciclo:



\*\*Requisito → diseño → desarrollo → prueba → revisión → corrección → aceptación\*\*



No se considerará terminada una historia únicamente porque el código funcione.



\## 6.3 Gestión de procesos



Las actividades de calidad se documentarán para poder repetirlas en futuras iteraciones.



Entre ellas:



\* revisión de historias;

\* revisión de criterios;

\* pruebas;

\* registro de defectos;

\* correcciones;

\* evaluación de métricas.



\## 6.4 Gestión de recursos



Los recursos considerados son:



\* equipo de desarrollo;

\* computadoras;

\* dispositivos móviles;

\* conexión a Internet;

\* repositorio GitHub;

\* herramientas de desarrollo;

\* herramientas de prueba;

\* inteligencia artificial como apoyo a la revisión.



\---



\# 7. Matriz CMMI + MoProSoft aplicada al proyecto



| Necesidad del proyecto | CMMI                     | MoProSoft                  | Aplicación                                 |

| ---------------------- | ------------------------ | -------------------------- | ------------------------------------------ |

| Planificar historias   | Planificación            | Gestión de proyectos       | Definir alcance, responsable y criterios   |

| Medir calidad          | Medición y análisis      | Gestión de procesos        | Registrar métricas                         |

| Revisar requisitos     | Gestión de requisitos    | Desarrollo y mantenimiento | Revisar claridad y verificabilidad         |

| Revisar producto       | Aseguramiento de calidad | Desarrollo y mantenimiento | Revisiones antes de aceptar                |

| Realizar pruebas       | Verificación             | Desarrollo y mantenimiento | Ejecutar casos de prueba                   |

| Validar con usuarios   | Validación               | Gestión de proyectos       | Comprobar utilidad                         |

| Controlar cambios      | Gestión de configuración | Gestión de proyectos       | Registrar modificaciones                   |

| Analizar riesgos       | Gestión de riesgos       | Gestión de proyectos       | Identificar problemas antes del desarrollo |



\---



\# 8. Historias de usuario evaluadas



El análisis de calidad se realizará sobre las seis historias de usuario principales del proyecto:



| ID    | Historia de usuario              | Prioridad |

| ----- | -------------------------------- | --------- |

| HU-01 | Consultar palabras y expresiones | Alta      |

| HU-02 | Escuchar pronunciaciones         | Alta      |

| HU-03 | Aportar conocimiento             | Media     |

| HU-04 | Consultar memoria cultural       | Media     |

| HU-05 | Validar contenido                | Alta      |

| HU-06 | Escuchar pronunciaciones         | Media     |



Estas historias constituyen la unidad principal para el análisis de prevención, corrección y costo de calidad.



\---



\# 9. Costo de calidad



Para este proyecto se utilizará una clasificación simplificada:



\### Costos de prevención



Son las horas utilizadas para evitar que aparezcan errores.



Ejemplos:



\* análisis de requisitos;

\* revisión de historias;

\* diseño de criterios de aceptación;

\* revisión mediante IA;

\* planificación de pruebas.



\### Costos de evaluación



Son las horas utilizadas para detectar problemas.



Ejemplos:



\* pruebas funcionales;

\* pruebas de usabilidad;

\* revisión de contenido;

\* pruebas de conectividad;

\* inspección de código.



\### Costos de corrección



Son las horas utilizadas para resolver errores encontrados después de la implementación.



Ejemplos:



\* corregir errores de programación;

\* modificar una interfaz;

\* optimizar audio;

\* corregir criterios;

\* modificar contenido.



\---



\# 10. Indicador j: prevención contra corrección



Para medir la relación entre prevención y corrección se utilizará:



\*\*j = Horas de prevención / Horas de corrección\*\*



Interpretación:



\* \*\*j > 1:\*\* existe mayor esfuerzo preventivo que correctivo.

\* \*\*j = 1:\*\* el esfuerzo preventivo y correctivo es equivalente.

\* \*\*j < 1:\*\* existe mayor esfuerzo correctivo que preventivo.



Las horas son una estimación académica para comparar el esfuerzo requerido por cada historia de usuario. No representan una factura comercial.



Para calcular el costo se utiliza un valor interno de referencia de:



\*\*$150 MXN por hora de trabajo\*\*



\---



\# 11. Cálculo de j por historia de usuario



| HU        | Prevención (h) | Evaluación (h) | Corrección (h) | j = Prevención/Corr. | Costo prevención | Costo evaluación | Costo corrección | Costo total |

| --------- | -------------: | -------------: | -------------: | -------------------: | ---------------: | ---------------: | ---------------: | ----------: |

| HU-01     |              4 |              2 |              3 |                 1.33 |             $600 |             $300 |             $450 |      $1,350 |

| HU-02     |              5 |              3 |              5 |                 1.00 |             $750 |             $450 |             $750 |      $1,950 |

| HU-03     |              6 |              3 |              8 |                 0.75 |             $900 |             $450 |           $1,200 |      $2,550 |

| HU-04     |              6 |              3 |              7 |                 0.86 |             $900 |             $450 |           $1,050 |      $2,400 |

| HU-05     |              5 |              3 |              6 |                 0.83 |             $750 |             $450 |             $900 |      $2,100 |

| HU-06     |              4 |              3 |              5 |                 0.80 |             $600 |             $450 |             $750 |      $1,800 |

| \*\*Total\*\* |         \*\*30\*\* |         \*\*17\*\* |         \*\*34\*\* |             \*\*0.88\*\* |       \*\*$4,500\*\* |       \*\*$2,550\*\* |       \*\*$5,100\*\* | \*\*$12,150\*\* |



\### Interpretación



El indicador global es:



\*\*j = 30 / 34 = 0.88\*\*



Esto significa que, en la estimación inicial, el proyecto dedica menos horas a prevención que a corrección.



Por lo tanto, existe una oportunidad clara de mejorar la calidad mediante mayor inversión preventiva.



El objetivo para las siguientes iteraciones será elevar progresivamente el indicador hacia:



\*\*j ≥ 1.00\*\*



Esto significa que se buscará invertir al menos una hora de prevención por cada hora estimada de corrección.



\---



\# 12. Análisis individual de las historias



\## HU-01 – Consultar palabras y expresiones



\### Riesgos



\* búsqueda poco clara;

\* resultados incompletos;

\* errores ortográficos;

\* tiempos de respuesta elevados.



\### Prevención



\* definir criterios de búsqueda;

\* revisar estructura de datos;

\* crear casos de prueba.



\### Evaluación



\* buscar palabras existentes;

\* buscar palabras inexistentes;

\* probar diferentes combinaciones.



\### Corrección



Se estiman 3 horas debido a posibles ajustes en búsqueda, presentación y datos.



\### j



\*\*j = 4 / 3 = 1.33\*\*



La prevención es superior a la corrección estimada.



\---



\# 13. HU-02 – Escuchar pronunciaciones



\### Riesgos



\* archivos de audio demasiado grandes;

\* reproducción lenta;

\* formato incompatible;

\* interrupciones por conectividad.



\### Prevención



\* utilizar formatos optimizados;

\* comprimir audio;

\* establecer tamaño máximo;

\* diseñar carga bajo demanda.



\### Evaluación



\* probar diferentes dispositivos;

\* probar conexiones lentas;

\* comprobar reproducción y pausa.



\### Corrección



Se estiman 5 horas debido a la complejidad adicional del contenido multimedia.



\### j



\*\*j = 5 / 5 = 1.00\*\*



La prevención y la corrección tienen el mismo esfuerzo estimado.



\---



\# 14. HU-03 – Aportar conocimiento



\### Riesgos



\* información incorrecta;

\* formularios difíciles de utilizar;

\* datos incompletos;

\* aportaciones sin validación.



\### Prevención



\* definir campos obligatorios;

\* validar entradas;

\* establecer reglas de contenido;

\* definir flujo de revisión.



\### Evaluación



\* probar datos completos;

\* probar datos incompletos;

\* probar entradas inválidas.



\### Corrección



Se estiman 8 horas porque los errores pueden involucrar interfaz, validación y almacenamiento.



\### j



\*\*j = 6 / 8 = 0.75\*\*



Existe mayor esfuerzo correctivo que preventivo.



\---



\# 15. HU-04 – Consultar memoria cultural



\### Riesgos



\* información extensa;

\* navegación complicada;

\* imágenes pesadas;

\* dificultad de consulta con Internet lento.



\### Prevención



\* organizar la información por categorías;

\* optimizar imágenes;

\* utilizar contenido ligero;

\* definir navegación sencilla.



\### Evaluación



\* probar navegación;

\* revisar tiempos de carga;

\* comprobar visualización en dispositivos móviles.



\### Corrección



Se estiman 7 horas.



\### j



\*\*j = 6 / 7 = 0.86\*\*



Se requiere aumentar las actividades preventivas.



\---



\# 16. HU-05 – Validar contenido



\### Riesgos



\* publicación de información incorrecta;

\* ausencia de responsable;

\* falta de trazabilidad;

\* aprobación accidental.



\### Prevención



\* definir roles;

\* establecer estados;

\* registrar cambios;

\* establecer criterios de aprobación.



\### Evaluación



\* probar aprobación;

\* probar rechazo;

\* comprobar historial.



\### Corrección



Se estiman 6 horas.



\### j



\*\*j = 5 / 6 = 0.83\*\*



Existe oportunidad para aumentar la prevención.



\---



\# 17. HU-06 – Escuchar pronunciaciones



\### Riesgos



\* duplicidad con contenido de audio;

\* reproducción inconsistente;

\* archivos demasiado pesados;

\* dificultades de acceso desde dispositivos móviles.



\### Prevención



\* reutilizar componentes;

\* definir estándares de audio;

\* optimizar archivos;

\* establecer criterios de compatibilidad.



\### Evaluación



\* probar reproducción;

\* probar pausa;

\* probar dispositivos diferentes;

\* probar conexión lenta.



\### Corrección



Se estiman 5 horas.



\### j



\*\*j = 4 / 5 = 0.80\*\*



El esfuerzo preventivo debe incrementarse.



\---



\# 18. Adaptación al contexto de la Mixteca



La calidad del software debe evaluarse considerando las condiciones reales en las que podría utilizarse.



No se puede asumir que todos los usuarios tendrán:



\* Internet de alta velocidad;

\* equipos modernos;

\* teléfonos con gran capacidad de almacenamiento;

\* conexión permanente;

\* conocimientos técnicos avanzados.



Por esta razón, el plan considera:



\## 18.1 Conectividad



Las pruebas deben incluir conexiones lentas e intermitentes.



\## 18.2 Dispositivos



Se deben realizar pruebas en teléfonos y computadoras con diferentes capacidades.



\## 18.3 Contenido multimedia



Los archivos de audio deben mantenerse optimizados para evitar consumo innecesario de datos.



\## 18.4 Interfaz



La interfaz debe utilizar lenguaje claro, navegación sencilla y elementos visuales fáciles de identificar.



\## 18.5 Disponibilidad



Las funciones principales deben degradar de forma controlada cuando la conexión no sea estable.



\## 18.6 Cultura y contenido



La información comunitaria debe tener mecanismos de revisión para evitar modificaciones o publicaciones sin autorización.



\---



\# 19. Métricas de calidad



| Métrica                   | Fórmula                                          | Meta   |

| ------------------------- | ------------------------------------------------ | ------ |

| Cumplimiento de criterios | criterios cumplidos / criterios totales × 100    | ≥ 95 % |

| Cobertura de pruebas      | casos ejecutados / casos planeados × 100         | ≥ 90 % |

| Correcciones              | defectos corregidos / defectos encontrados × 100 | ≥ 95 % |

| Contenido validado        | contenido validado / contenido publicado × 100   | 100 %  |

| Historias aceptadas       | HU aceptadas / HU terminadas × 100               | ≥      |



