---
title: 'Arquitecturas cognitivas autoaprendidas para la comprensión de escenas: causalidad, visión y memoria'
date: 2026-01-20
permalink: /posts/2026/01/20/arquitectura-cognitiva-causalidad-principe/
tags:
  - Inteligencia Artificial
  - Neurociencia Computacional
  - Aprendizaje Auto-supervisado
  - Causalidad
  - Reinforcement Learning
  - Arquitecturas Cognitivas
excerpt: 'Reflexiones a partir de la charla del Prof. José C. Príncipe sobre una arquitectura cognitiva inspirada en la visión humana, orientada a la comprensión autónoma de escenas mediante memoria, atención y aprendizaje causal.'
---
<div style="text-align: justify;">
Durante esta semana tuve la oportunidad de asistir a la charla <em>“A Self-Learning Cognitive Architecture for Scene Understanding Using Causality”</em>, dictada por el <strong>Prof. José C. Príncipe</strong>, Distinguished Professor of Electrical and Computer Engineering de la <strong>University of Florida</strong>, IEEE Fellow y director del <strong>Computational NeuroEngineering Lab (CNEL)</strong>. La presentación abordó uno de los desafíos más profundos de la inteligencia artificial: cómo construir sistemas capaces de <strong>comprender escenas visuales complejas de manera autónoma</strong>, sin depender de grandes volúmenes de datos etiquetados.
</div>
<br>

<div style="text-align: justify;">
La propuesta se distancia de los enfoques dominantes basados exclusivamente en aprendizaje supervisado. En su lugar, plantea una <strong>arquitectura cognitiva inspirada en el sistema visual humano</strong>, integrando principios de neurociencia, modelos dinámicos, memoria, atención visual, causalidad y aprendizaje por refuerzo. El objetivo no es solo reconocer patrones, sino <strong>representar el mundo en términos de objetos y sus relaciones</strong>.
</div>
<br>

<div style="text-align: justify;">
Uno de los mensajes centrales es que la <strong>visión autónoma</strong> sigue estando fuera del alcance de los paradigmas actuales. Aunque las redes profundas han demostrado un alto desempeño en tareas específicas, su dependencia de etiquetas y su limitada capacidad de generalización dificultan su aplicación en entornos abiertos y dinámicos. En este contexto, comprender el rol de la <strong>experiencia almacenada</strong> resulta clave.
</div>
<br>

<br>
<p align="center">
<img src="/files/20260120_120000.jpg" alt="Figura 1: Collage de la charla del profesor José C. Príncipe" style="max-width:100%; height:auto;">
</p>
<p align="center">
<em>Figura 1: Collage de la charla del profesor José C. Príncipe.</em>
</p>
<br>

<div style="text-align: justify;">
En la vía ventral de la arquitectura, el procesamiento sensorial se modela mediante un <strong>sistema dinámico jerárquico con entradas causales desconocidas</strong>, basado en modelos de espacio de estados. Las observaciones representan la señal sensorial, los <strong>estados ocultos</strong> codifican la historia interna y las <strong>causas latentes</strong> capturan la estructura espacial del entorno. A través de priors bayesianos empíricos, las capas superiores intentan predecir las causas de las capas inferiores, siguiendo principios de <strong>codificación predictiva</strong>.
</div>
<br>

<div style="text-align: justify;">
La arquitectura es <strong>multicapa y homogénea</strong>, con distintos niveles espaciales y temporales generados mediante <em>pooling</em>. El aprendizaje se realiza de forma voraz, capa por capa, permitiendo la auto-organización progresiva de representaciones e invariancias similares a los campos receptivos observados en sistemas biológicos.
</div>
<br>

<div style="text-align: justify;">
Un componente clave es la incorporación explícita de <strong>visión foveada</strong>, inspirada en los movimientos sacádicos del sistema visual humano. Cada sacada inicia un ciclo de percepción en el que se adquiere información, se procesa y se decide el siguiente foco de atención. Este mecanismo se aproxima mediante una cámara plenóptica (Lytro) y un enfoque de <strong>saliencia anidada</strong> que permite localizar y refinar regiones de interés.
</div>
<br>

<div style="text-align: justify;">
Cuando los datos disponibles son limitados, la arquitectura incorpora <strong>atención top-down</strong> mediante aprendizaje por transferencia, utilizando redes profundas como VGG16 entrenadas en ImageNet para generar mapas de saliencia semántica. La combinación de atención bottom-up y top-down mejora la exploración visual del entorno.
</div>
<br>

<div style="text-align: justify;">
Uno de los aportes conceptuales más relevantes es la introducción de una <strong>memoria de trabajo interna</strong>, denominada <em>Canvas</em>, que almacena objetos detectados y sus posiciones. Esta representación interna permite superar las limitaciones del aprendizaje por refuerzo directo desde píxeles, observado por ejemplo en experimentos tempranos con <em>Super Mario Bros</em>.
</div>
<br>

<div style="text-align: justify;">
Al incorporar el Canvas, el agente puede <strong>focalizar el aprendizaje por refuerzo en los objetos relevantes</strong>, acelerando el entrenamiento y mejorando la transferencia entre tareas, al operar sobre representaciones estructuradas en lugar de estados visuales de alta dimensionalidad.
</div>
<br>

<div style="text-align: justify;">
Para determinar qué objetos son relevantes, la arquitectura introduce explícitamente el <strong>aprendizaje basado en causalidad</strong>. En lugar de utilizar información mutua, se emplea el concepto de <strong>información dirigida</strong>, siguiendo los trabajos de Wiener, Granger y Massey, con el fin de estimar la dirección del flujo causal entre las trayectorias de los objetos y las señales de recompensa.
</div>
<br>

<div style="text-align: justify;">
El trabajo presenta además un <strong>estimador no paramétrico de información dirigida</strong> basado en la entropía de Rényi. Experimentos en distintos entornos muestran que la arquitectura identifica eficazmente los objetos relevantes, superando a métodos de <em>deep reinforcement learning</em> en velocidad de entrenamiento y desempeño en transferencia.
</div>
<br>

<div style="text-align: justify;">
A modo de cierre, la charla del Prof. Príncipe refuerza la idea de que avanzar hacia sistemas de visión verdaderamente autónomos requiere <strong>integrar principios biológicos en el diseño de arquitecturas artificiales</strong>. La combinación de codificación predictiva, memoria, atención, causalidad y aprendizaje por refuerzo ofrece un camino prometedor, aunque aún con desafíos abiertos.
</div>
<br>

<div style="text-align: justify;">
Entre estos desafíos se encuentran la <strong>extracción de eventos a partir del flujo temporal continuo</strong>, el desarrollo de nuevas arquitecturas de memoria y la necesidad de métodos de aprendizaje por refuerzo más eficientes para operar en tiempo real. Aun así, este enfoque sugiere que comprender el mundo, y no solo reconocer patrones, es una meta alcanzable cuando la ingeniería se nutre profundamente de la neurociencia.
</div>
<br>

<div style="text-align: justify;">
Para quienes deseen profundizar en los fundamentos teóricos y experimentales de esta arquitectura cognitiva, el artículo completo del <strong>Prof. José C. Príncipe</strong> y colaboradores se encuentra disponible en la revista <em>Neural Networks</em> y puede consultarse en el siguiente enlace:
<a href="https://www.sciencedirect.com/science/article/pii/S0893608022000703#aep-article-footnote-id1" target="_blank">https://www.sciencedirect.com/science/article/pii/S0893608022000703</a>. Finalmente, agradezco al <strong>Departamento de Ingeniería Eléctrica</strong> y al <strong>profesor Pablo Estévez</strong> por la invitación y por facilitar este valioso espacio de encuentro académico y reflexión interdisciplinaria.
</div>

