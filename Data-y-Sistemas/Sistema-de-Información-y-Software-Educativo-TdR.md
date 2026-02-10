# Sistema de Información y Software Educativo – Términos de Referencia (TdR)

## Objetivo del Proyecto

Definir el conjunto de sistemas de información y software necesarios para operar el nuevo modelo educativo diseñado por Reingeniería Educativa (ReEdu), asegurando que dichos sistemas:

* soporten integralmente los procesos educativos definidos,
* estén alineados con la arquitectura de TI aprobada,
* sean viables técnica, económica y operativamente,
* prioricen soluciones abiertas, reutilizables y sostenibles,
* puedan implementarse progresivamente en instituciones educativas del Perú.
* El resultado será una definición clara y priorizada de qué software debe:
  * desarrollarse,
  * adaptarse,
  * integrarse,
  * o adquirirse.

### Alcance

El proyecto incluye, pero no se limita a:

* Identificar y documentar los sistemas de información requeridos para soportar el modelo educativo ReEdu.
* Definir el alcance funcional de cada sistema.
* Establecer la clasificación de cada componente de software:
  * desarrollar,
  * adaptar,
  * integrar,
  * adquirir (preferentemente open source).
* Definir la interacción entre sistemas (integraciones, flujos de datos, APIs).
* Definir los requerimientos no funcionales:
  * seguridad,
  * privacidad,
  * disponibilidad,
  * desempeño,
  * escalabilidad,
  * usabilidad.
* Establecer criterios de priorización y secuenciación de implementación.
* Definir lineamientos para la evolución y mantenimiento del software.
* Documentar y publicar todo el trabajo bajo licencias MIT o CC BY 4.0.

#### Fuera de Alcance

* Desarrollo o implementación del software.
* Contratación de proveedores tecnológicos.
* Operación productiva de los sistemas.
* Soporte técnico continuo.

### Entregables

* Mapa de Sistemas de Información, alineado a los procesos educativos.
* Catálogo de Sistemas y Componentes de Software, incluyendo:
  * propósito,
  * usuarios,
  * alcance funcional.
* Especificación funcional de alto nivel por sistema.
* Matriz de decisión “Build / Adapt / Buy / Integrate”.
* Modelo de interacción entre sistemas (integraciones y flujos).
* Requerimientos no funcionales consolidados.
* Priorización de implementación (MVP, Fase 2, Fase 3).
* Estimación referencial de esfuerzo y costos.
* Repositorio abierto con toda la documentación generada.

## Enfoque Metodológico

* Derivación directa desde:
  * procesos educativos,
  * arquitectura TI aprobada.
* Diseño usuario-céntrico (docentes, estudiantes, gestores).
* Enfoque MVP + iterativo.
* Preferencia por:
  * software open source,
  * estándares abiertos,
  * arquitectura modular.
* Documentación clara, reutilizable y neutral respecto a proveedores.

## Sistemas de Información a Considerar (referencial)

> La lista final se definirá durante el proyecto.

* Núcleo Educativo
  * Sistema de Gestión Académica
  * Sistema de Gestión Curricular y Contenidos
  * Sistema de Evaluación y Seguimiento del Estudiante
  * Plataforma de Aprendizaje (LMS / LXP)
* Gestión y Soporte
  * Gestión de Docentes y Talento Educativo
  * Gestión de Padres / Tutores
  * Gestión Administrativa y Registros
  * Gestión de Bienestar y Seguridad
* Analítica y Mejora Continua
  * Sistema de Monitoreo de Desempeño Educativo
  * Analítica y Reportes
  * Gestión de Indicadores (KPIs)
* Transversales
  * Gestión de Identidad y Accesos
  * Integración y APIs
  * Seguridad y Cumplimiento

## Roles y Responsabilidades

* Gerente del Proyecto: coordinación y ejecución.
* Ejecutivo del Proyecto: aprobación de entregables y stage gates.
* Gerente de TI: responsable técnico del diseño.
* Gerente de Procesos e Innovación: alineamiento funcional.
* Experto en Educación: validación pedagógica.
* Sounding Board de Sistemas: evaluación de usabilidad, viabilidad y sostenibilidad.
* Gerente de Finanzas: evaluación de costos y sostenibilidad económica.

## Plan de Recursos, Calidad, Finanzas y Gobierno

* Trabajo estructurado en co-locations de expertos.
* Uso de stage gates para:
  * validación del mapa de sistemas,
  * aprobación de especificaciones funcionales,
  * aprobación de priorización.
* Evaluación de calidad basada en:
  * trazabilidad proceso → sistema,
  * simplicidad y reutilización,
  * costo total de propiedad.
* El esfuerzo podrá ser valorizado, remunerado o donado.

## Decomposición y Programación del Trabajo (referencial)

| Fase                                              | Personas    | Duración          | Esfuerzo     | Costo (US$) | Gastos de co-locación (US$) |
| ------------------------------------------------- |:-----------:|:-----------------:|:------------:|:-----------:|:---------------------------:|
| Alineamiento con procesos y arquitectura          | 4 – 6       | 3 semanas         | 100 hh       | 5,500       | 1,000                       |
| Identificación y mapa de sistemas                 | 6 – 8       | 4 semanas         | 200 hh       | 11,000      | 3,000                       |
| Definición funcional de sistemas                  | 8 – 12      | 10 – 16 semanas   | 1,000 hh     | 55,000      | 20,000                      |
| Análisis build/buy/adapt                          | 4 – 6       | 4 semanas         | 160 hh       | 8,800       | -                           |
| Priorización y roadmap                            | 4 – 6       | 3 semanas         | 120 hh       | 6,600       | -                           |
| Validación y stage gates                          | 6 – 8       | 2 semanas         | 100 hh       | 5,500       | -                           |
| Input de expertos de procesos durante el proyecto | 2 - 4       | 20 - 30 semanas   | 500 hh       | 27,500      | -                           |
| **Total**                                         | **15 - 25** | **30-40 semanas** | **2,180 hh** | **119,900** | **24,000**                  |

## Principales Incidencias y Riesgos

| Incidencia/Riesgo | Descripción                                                                         | Calificación | Mitigación                           |
|:-----------------:| ----------------------------------------------------------------------------------- |:------------:| ------------------------------------ |
| Riesto            | Definición excesivamente ambiciosa                                                  | Alto         | MVP + fases                          |
| Riesgo            | Dependencia tecnológica                                                             | Medio        | Estándares abiertos                  |
| Riesgo            | Baja adopción por usuarios                                                          | Alto         | Co-diseño                            |
| Riesgo            | Limitaciones de conectividad                                                        | Medio        | Diseño offline/híbrido               |
| Riesgo            | Falta de conocimiento previo de proyecto de esta magnitud en el equipo del proyecto | Alto         | Conseguir SMEs en el exterior        |
| Riesgo            | Estimación inicial de recursos podría estar lejos de la realidad                    | Alto         | Revisión y ajuste en cada stage gate |

## Supuestos y Limitaciones

* La arquitectura de TI está aprobada.
* Los procesos educativos están definidos.
* El costo promedio de hh se estima en US$ 55.
* El diseño deberá ser aplicable a contextos con recursos limitados.
* Existen aplicaciones en el mercado que cubren al menos 80% de las funcionalidades requeridas
* Se cuenta con infraestructura aaS para hacer prototipos que se requieran
* Se tendrá acceso a especialistas de las diferentes aplicaciones a incorporar en el diseño

## Resultado Esperado

* Un modelo claro, priorizado y ejecutable de sistemas y software educativo, que permita a ReEdu y a terceros implementar el nuevo modelo educativo de forma progresiva, abierta y sostenible.
