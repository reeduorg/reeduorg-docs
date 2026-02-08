# Arquitectura de Tecnología de Información (TI) – Términos de Referencia (TdR)

## Objetivo del Proyecto

Diseñar y documentar la arquitectura integral de Tecnología de Información que soporte los procesos educativos definidos por Reingeniería Educativa (ReEdu), asegurando que dicha arquitectura sea:

* alineada con los objetivos educativos y sociales del proyecto,
* modular, escalable y evolutiva,
* económicamente sostenible,
* interoperable y basada en estándares abiertos,
* publicable bajo licencias de acceso abierto compatibles con MIT o CC BY 4.0.
  La arquitectura servirá como base para la implementación del sistema educativo y de gestión que soporta el modelo educativo de ReEdu en diversos centros educativos en todo el Perú.

## Alcance

El proyecto de Arquitectura de TI incluye, pero no se limita a:

* Diseñar la arquitectura empresarial de TI, alineada a los procesos educativos definidos por ReEdu.
* Definir la arquitectura lógica y física de los sistemas de información.
* Definir la arquitectura de datos, incluyendo modelos conceptuales y principios de gobierno de datos.
* Definir la arquitectura de aplicaciones, identificando:
  * sistemas núcleo,
  * componentes reutilizables,
  * integraciones,
  * posibles soluciones existentes (open source / comerciales).
* Definir la arquitectura tecnológica, incluyendo:
  * infraestructura,
  * cloud vs on-premise,
  * conectividad,
  * seguridad,
  * continuidad y respaldo.
* Establecer principios de interoperabilidad, seguridad, privacidad y protección de datos, alineados a la normativa peruana.
* Definir mecanismos para la evolución continua de la arquitectura.
* Documentar todas las decisiones arquitectónicas y sus racionales.
* Publicar toda la documentación generada bajo licencias abiertas MIT o CC BY 4.0.
* La arquitectura deberá ser aplicable a contextos urbanos y rurales.

### Fuera de Alcance

* Desarrollo de software o adquisición de infraestructura.
* Implementación en instituciones educativas.
* Operación y soporte productivo de sistemas.
* Definición de políticas públicas o regulación.

## Entregables

* Principios de Arquitectura de TI (alineados a la misión de ReEdu).
* Mapa de Capacidades Digitales, vinculado a los procesos educativos.
* Arquitectura Empresarial de TI (nivel 0–1).
* Arquitectura de Aplicaciones:
  * catálogo de aplicaciones,
  * diagramas de interacción,
  * estándares de integración (APIs, eventos, etc.).
* Arquitectura de Datos:
  * modelos conceptuales,
  * lineamientos de calidad, seguridad y gobierno de datos.
* Arquitectura Tecnológica:
  * infraestructura de referencia,
  * lineamientos de despliegue,
  * seguridad y continuidad.
* Roadmap de implementación tecnológica, por fases.
* Criterios de evaluación tecnológica para futuras adquisiciones o desarrollos.
* Repositorio abierto con toda la documentación, diagramas y artefactos.

## Estándares y Lineamientos Metodológicos

* Marco de referencia: TOGAF (adaptado) o equivalente liviano.
* Modelado:
  * ArchiMate (cuando aplique),
  * diagramas de arquitectura lógica y física.
* Principios:
  * Open by default
  * API-first
  * Modularidad y desacoplamiento
  * Seguridad y privacidad desde el diseño
* Uso preferente de:
  * estándares abiertos,
  * software open source cuando sea viable.

## Roles y Responsabilidades

* Gerente del Proyecto: coordinación general y ejecución.
* Ejecutivo del Proyecto: aprobación de TdR, entregables y stage gates.
* Gerente de TI: dueño del diseño de la arquitectura.
* Gerente de Procesos e Innovación: asegurar alineamiento con procesos educativos.
* Experto en Educación: validar adecuación pedagógica de las soluciones.
* Gerente de Finanzas y RRHH: control de recursos y transparencia.
* Sounding Board de TI: comité de expertos en arquitectura, seguridad y sistemas educativos, responsable de evaluar calidad, viabilidad y sostenibilidad.

## Plan de Recursos, Calidad, Finanzas y Gobierno

* Trabajo estructurado en co-locations de expertos senior.
* Uso de stage gates para aprobar:
  * arquitectura de alto nivel,
  * arquitecturas de dominio,
  * roadmap.
* Evaluación de calidad basada en:
  * alineamiento con procesos,
  * simplicidad,
  * escalabilidad,
  * costo total de propiedad.
* El trabajo podrá ser valorizado, remunerado o donado.

## Decomposición y Programación del Trabajo (referencial)

| Fase                                               | Personas  | Duración          | Esfuerzo     | Costo (US$) | Gastos de co-locacion (US$) |
| -------------------------------------------------- |:---------:|:-----------------:|:------------:|:-----------:|:---------------------------:|
| Alineamiento con procesos educativos               | 4–6       | 4 semanas         | 120 hh       | 8,400       | 2,000                       |
| Definición de principios y arquitectura alto nivel | 6–8       | 2–3 semanas       | 200 hh       | 14,000      | 3,000                       |
| Arquitecturas de dominio (apps, datos, tecnología) | 8–12      | 12–20 semanas     | 1,200 hh     | 84,000      | 20,000                      |
| Roadmap y criterios de adopción                    | 4–6       | 4 semanas         | 160 hh       | 11,200      | 4,000                       |
| Validación por expertos y stage gates              | 6–8       | 2 semanas         | 120 hh       | 8,400       | -                           |
| **Total**                                          | **15-20** | **30-40 semanas** | **1,800 hh** | **126,000** | **29,000**                  |

## Principales Incidencias y Riesgos

| Incidencia/Riesgo | Descripción                                           | Calificación | Mitigación           |
|:-----------------:| ----------------------------------------------------- |:------------:| -------------------- |
| Riesgo            | Arquitectura excesivamente compleja, dificil adopción | Alto         | Enfoque MVP          |
| Riesgo            | Dependencia de proveedores, lock-in tecnológico       | Medio        | Estándares abiertos  |
| Riesgo            | Limitaciones de conectividad, brecha digital          | Medio        | Arquitectura híbrida |

## Supuestos y Limitaciones

* Existirá un modelo de procesos educativos previamente definido.
* Existen elementos de arquitectura opern source satisfactorios para cumplir el diseño
* Se tendrá acceso a SMEs para consultas de temas puntuales sin conocimiento local
* El costo promedio de hh se estima en US$ 70.

## Resultado Esperado

* Un modelo de arquitectura TI de referencia para la educación escolar en el Perú, abierto, replicable y sostenible, que sirva como base para la transformación digital del sistema educativo.
