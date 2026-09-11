\# AUDITORÍA DE HISTORIAS DE USUARIO MEDIANTE INTELIGENCIA ARTIFICIAL



\## 1. Objetivo



La inteligencia artificial se utilizará como herramienta de apoyo para realizar una auditoría de calidad sobre las historias de usuario del proyecto.



La auditoría busca identificar:



\- ambigüedades;

\- requisitos incompletos;

\- criterios de aceptación no verificables;

\- riesgos;

\- casos de prueba faltantes;

\- métricas que puedan incorporarse;

\- problemas relacionados con conectividad;

\- problemas de usabilidad y accesibilidad.



La decisión final sobre aceptar o rechazar una recomendación corresponde al equipo de desarrollo.



\---



\# 2. Prompt avanzado de auditoría



El siguiente prompt fue diseñado específicamente para el proyecto:



```text

Actúa como auditor senior de calidad de software especializado en:



\- ingeniería de requisitos;

\- historias de usuario;

\- CMMI;

\- MoProSoft;

\- pruebas de software;

\- calidad de software;

\- accesibilidad;

\- sistemas comunitarios;

\- aplicaciones con conectividad limitada.



Analiza la siguiente historia de usuario:



\[PEGAR HISTORIA DE USUARIO]



Contexto del proyecto:



El sistema busca preservar y transmitir la lengua y memoria cultural

de una comunidad de la región Mixteca de Oaxaca.



Los usuarios pueden utilizar teléfonos móviles o computadoras con

diferentes capacidades y pueden tener conectividad limitada o

intermitente.



Realiza una auditoría completa y responde utilizando las siguientes

secciones:



1\. Evaluación de claridad de la historia.

2\. Ambigüedades detectadas.

3\. Requisitos incompletos.

4\. Criterios de aceptación faltantes.

5\. Riesgos funcionales.

6\. Riesgos de rendimiento.

7\. Riesgos relacionados con conectividad.

8\. Riesgos de usabilidad.

9\. Riesgos de accesibilidad.

10\. Riesgos relacionados con la integridad del contenido cultural.

11\. Casos de prueba recomendados.

12\. Datos de prueba necesarios.

13\. Métricas cuantificables.

14\. Actividades de prevención.

15\. Posibles actividades de evaluación.

16\. Posibles actividades de corrección.

17\. Relación con prácticas de CMMI.

18\. Relación con procesos de MoProSoft.

19\. Recomendaciones de mejora.

20\. Historia de usuario propuesta después de la auditoría.



Los criterios de aceptación propuestos deben ser medibles y verificables.



No inventes funcionalidades que no estén justificadas por la historia

o el contexto.



Distingue entre:



\- problema encontrado;

\- recomendación;

\- requisito necesario;

\- supuesto.



Finalmente asigna un nivel de riesgo:



BAJO / MEDIO / ALTO / CRÍTICO



y explica brevemente la razón.

