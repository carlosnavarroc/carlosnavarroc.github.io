---
title: 'Presentaciones de proyectos: Big Data y Cloud Computing'
date: 2026-07-03
permalink: /posts/2026/07/03/presentaciones-proyectos-big-data-cloud-computing/
tags:
  - Big Data
  - Cloud Computing
  - Data Engineering
  - Lakehouse
  - Google Cloud Platform
  - Amazon Web Services
  - Data Governance
  - Magíster en Data Science
  - Universidad del Desarrollo
excerpt: 'Como integrante del comité de expertos del curso Big Data y Cloud Computing del Magíster en Data Science de la UDD, participé en la evaluación de proyectos centrados en arquitecturas modernas de datos, Lakehouse, seguridad y gobernanza.'
---

<div style="text-align: justify;">
Hoy tuve la oportunidad de participar como integrante del <strong>comité de expertos</strong> en la presentación de los proyectos finales del curso <strong>MDSC3S141-1 Big Data y Cloud Computing</strong>, impartido por el <strong>Dr. Luis Castillo Faune</strong> en el <strong>Magíster en Data Science</strong> de la <strong>Universidad del Desarrollo (UDD)</strong>.
</div>

<br>

<div style="text-align: justify;">
Fue especialmente grato reencontrarme con este mismo grupo de estudiantes, quienes hace algunos meses presentaron sus proyectos del curso de <strong>Deep Learning</strong>. En esa oportunidad, el foco estuvo en el desarrollo y evaluación de modelos de aprendizaje profundo para resolver problemas reales. Quienes tengan interés pueden revisar esa experiencia en la entrada <a href="https://carlosnavarroc.github.io/posts/2026/04/18/presentaciones-proyectos-deep-learning/">Presentaciones de proyectos: aplicaciones reales de Deep Learning</a>.
</div>

<br>

<div style="text-align: justify;">
En esta ocasión, el énfasis fue diferente. Más que en el desarrollo de modelos analíticos, las presentaciones estuvieron centradas en el diseño de <strong>plataformas modernas de datos</strong>, considerando aspectos de <strong>ingesta</strong>, <strong>procesamiento distribuido</strong>, <strong>arquitecturas Lakehouse</strong>, <strong>gobernanza</strong>, <strong>seguridad</strong> y <strong>despliegue en la nube</strong>.
</div>

<br>

<div style="text-align: justify;">
Uno de los aspectos más interesantes de la jornada fue observar cómo los equipos justificaban sus decisiones arquitectónicas para resolver problemas de negocio reales. Más allá de la implementación técnica, la discusión se centró en la escalabilidad de las soluciones, la mantenibilidad de los pipelines, la calidad de los datos y los mecanismos de gobernanza necesarios para operar plataformas analíticas en ambientes productivos.
</div>

<br>

<div style="text-align: justify;">
El <strong>Grupo 1</strong> presentó una <strong>Plataforma Big Data para analítica omnicanal en retail</strong>, cuyo objetivo fue integrar información proveniente de <strong>cuatro silos de datos</strong> para habilitar procesos analíticos con tiempos de respuesta de segundos. La propuesta se basó en una arquitectura <strong>Medallion sobre Google Cloud Platform</strong>, utilizando <strong>Delta Lake sobre Apache Parquet</strong> y <strong>Cloud Composer</strong> para la orquestación de procesos. Durante la evaluación discutimos decisiones arquitectónicas como la frecuencia de ejecución de los procesos batch, el impacto de una falla en el pipeline nocturno y los mecanismos de recuperación ante errores, además de aspectos relacionados con la gobernanza activa de los datos. El equipo estuvo integrado por <strong>Claudio Ballerini</strong>, <strong>Juan José Torres</strong>, <strong>Cristian Vargas</strong> y <strong>Christian Vásquez</strong>.
</div>

<br>

<div style="text-align: justify;">
El <strong>Grupo 2</strong> presentó una <strong>Plataforma Analítica de Rentabilidad para Aerolíneas</strong>, basada en una <strong>arquitectura Lakehouse sobre Google Cloud Platform</strong> utilizando el enfoque <strong>Medallion</strong>. El proyecto incorporó componentes orientados a la <strong>predicción de riesgo operacional</strong> y justificó la elección de un procesamiento <strong>batch</strong> frente a una arquitectura <strong>streaming</strong>, considerando los requerimientos del caso de negocio. Además, el equipo situó el desarrollo en un nivel de madurez tecnológica <strong>TRL 6</strong>, lo que permitió discutir el grado de preparación de la solución para entornos cercanos a producción. El equipo estuvo conformado por <strong>Camila Figueroa Muñoz</strong>, <strong>Diego Morales Valenzuela</strong> y <strong>María Vásquez Tapia</strong>.
</div>

<br>

<div style="text-align: justify;">
El <strong>Grupo 3</strong> presentó un <strong>Pipeline Serverless para Detección de Fraude</strong>, orientado a la identificación de transacciones potencialmente fraudulentas en tiempo real. La solución procesa un histórico de aproximadamente <strong>15 millones de registros</strong> y un flujo incremental cercano a <strong>2 millones de transacciones diarias</strong>, utilizando una arquitectura <strong>serverless</strong> basada en el enfoque <strong>Medallion (Bronze, Silver y Gold)</strong>. Como caso de estudio, el equipo implementó una heurística para detectar usuarios con <strong>más de 12 transacciones diarias</strong>, incorporando además requisitos propios de una plataforma moderna de datos, como <strong>propiedades ACID</strong>, <strong>enmascaramiento de información sensible</strong> y <strong>consultas SQL interactivas</strong>. A diferencia de los proyectos anteriores, esta propuesta fue implementada sobre <strong>Amazon Web Services (AWS)</strong>, lo que permitió comparar distintas alternativas para el despliegue de arquitecturas de datos en la nube. El equipo estuvo integrado por <strong>Adrián Espinoza</strong> y <strong>Ricardo Castro</strong>.
</div>

<br>

<div style="text-align: justify;">
El <strong>Grupo 4</strong> presentó <strong>Gestión Territorial Inteligente: Arquitectura Big Data para Solicitudes Ciudadanas en la Municipalidad de El Monte</strong>. La propuesta estuvo basada en un patrón analítico <strong>Lakehouse Medallion</strong> con procesamiento <strong>batch incremental</strong>, utilizando archivos <strong>Parquet</strong> con compresión <strong>Snappy</strong> para optimizar el almacenamiento y las operaciones de lectura. El procesamiento se desarrolló mediante <strong>PySpark</strong>, aprovechando el paralelismo para enfrentar escenarios de mayor escala. Uno de los aspectos más interesantes fue la discusión sobre una <strong>arquitectura desacoplada</strong>, donde el almacenamiento y el motor de procesamiento evolucionan de manera independiente, permitiendo escalar capacidad y costos según las necesidades de la solución. Además, el diseño fue concebido para ser reproducible en un entorno local y preparado para un despliegue nativo sobre <strong>Google Cloud Platform</strong>. El equipo estuvo integrado por <strong>Dante Aguirre</strong>, <strong>Osvaldo Neira</strong>, <strong>Sofía Alanís</strong> y <strong>Jaime Sandoval</strong>.
</div>

<br>

<div style="text-align: justify;">
Una de las conclusiones más interesantes de la jornada fue comprobar que no existe una única arquitectura correcta para resolver un problema de datos. Los equipos tomaron decisiones distintas respecto al uso de procesamiento <strong>batch</strong> o <strong>streaming</strong>, la elección del proveedor de nube, la organización de los datos mediante arquitecturas <strong>Lakehouse</strong> y la incorporación de mecanismos de seguridad y gobernanza. Lo relevante fue que cada una de estas decisiones estuviera respaldada por argumentos técnicos y alineada con las necesidades del problema que buscaban resolver.
</div>

<br>

<div style="text-align: justify;">
Al comparar estas presentaciones con las realizadas anteriormente en el curso de <strong>Deep Learning</strong>, resulta evidente la evolución del programa. Si en aquella instancia el foco estaba en la selección y evaluación de modelos de aprendizaje automático, en esta oportunidad el desafío consistió en diseñar la infraestructura que permitirá llevar esos modelos a entornos productivos, considerando aspectos como escalabilidad, mantenibilidad, seguridad y gobernanza de los datos.
</div>

<br>

<div style="text-align: justify;">
Quiero felicitar al <strong>Dr. Luis Castillo Faune</strong> por el trabajo realizado durante el semestre y a todos los estudiantes por el nivel de sus proyectos y las discusiones técnicas generadas durante la jornada. Haber compartido con este mismo grupo tanto en el curso de <strong>Deep Learning</strong> como ahora en <strong>Big Data y Cloud Computing</strong> permitió apreciar cómo el énfasis pasó desde el desarrollo de modelos hacia el diseño de plataformas de datos capaces de soportarlos en escenarios reales. Este tipo de instancias demuestra que el diseño de estas plataformas va mucho más allá de seleccionar tecnologías: implica comprender los requerimientos del negocio, fundamentar las decisiones de arquitectura y construir soluciones que puedan evolucionar de manera segura, escalable y mantenible.
</div>
