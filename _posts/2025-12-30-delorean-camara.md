---
title: 'DeloreanCamara: Superposición Fotográfica para Recrear el Pasado'
date: 2025-12-30
permalink: /posts/2025/12/30/delorean-camara/
tags:
  - Android
  - Kotlin
  - CameraX
  - Fotografía
  - Desarrollo Mobile
  - Experiencias Visuales
excerpt: 'Desarrollé una aplicación Android que permite superponer imágenes antiguas sobre la cámara en tiempo real y capturar una fotografía final alineada con precisión.'
---

<div style="text-align: justify;">
DeloreanCamara es un proyecto personal desarrollado en Android cuyo objetivo es explorar la relación entre pasado y presente a través de la fotografía. La aplicación permite cargar una imagen antigua desde la galería, superponerla sobre la vista en vivo de la cámara y ajustarla manualmente para recrear una escena lo más fiel posible al encuadre original.
</div>

<br>

<div style="text-align: justify;">
La idea surge a partir del interés por comparar registros históricos con el entorno actual, utilizando el propio dispositivo móvil como herramienta de alineación visual. Inspirado en el concepto de “volver al pasado”, el nombre DeloreanCamara hace referencia directa al vehículo de la saga Back to the Future, utilizado aquí como metáfora del viaje temporal a través de imágenes.
</div>

<br>


<div style="text-align: justify;">
La aplicación está desarrollada en Kotlin y utiliza la librería CameraX para mostrar la cámara en tiempo real. Sobre esta vista se puede cargar una imagen como overlay, la cual puede desplazarse, escalarse mediante gestos multitáctiles y ajustarse en opacidad utilizando un control deslizante. Estas herramientas permiten al usuario alinear visualmente la imagen histórica con el entorno actual antes de capturar la fotografía.
</div>

<br>

<div style="text-align: justify;">
Uno de los principales desafíos técnicos del proyecto fue asegurar que la imagen final guardada coincidiera exactamente con lo que se observa en pantalla. Esto implicó manejar correctamente las diferencias entre el encuadre mostrado por PreviewView y la imagen real capturada por la cámara, así como corregir la orientación mediante metadatos EXIF y mantener un aspect ratio consistente durante todo el flujo.
</div>

<br>

<div style="text-align: justify;">
Al tomar una fotografía, la aplicación genera dos archivos: la imagen original capturada por la cámara y una imagen combinada que incluye el overlay aplicado con las mismas transformaciones visuales utilizadas en la interfaz. Ambas se guardan directamente en la galería del dispositivo, permitiendo su uso posterior sin procesamiento adicional.
</div>

<br>


<p align="center">
  <img src="/files/2025_delorean_1979.jpg" alt="Figura 1a: Foto original de 1979. Figura 1b Foto actualizada obtenida con la app. Figura 1c: Montaje obtenido con la app" style="max-width:100%; height:auto;">
</p>

<br>

<div style="text-align: justify;">
DeloreanCamara funciona como un ejercicio práctico de composición gráfica, manejo de bitmaps y control preciso de transformaciones visuales en Android. Más allá de su uso funcional, el proyecto sirve como base para futuras exploraciones en fotografía comparativa, documentación histórica, o incluso aplicaciones relacionadas con realidad aumentada.
</div>

<br>

<div style="text-align: justify;">
El código fuente del proyecto está disponible públicamente y documenta el proceso completo de captura, transformación y guardado de imágenes, así como los problemas comunes que aparecen al trabajar con cámaras móviles y overlays gráficos.
</div>

<br>

<div style="text-align: justify;">
Repositorio del proyecto:
<a href="https://github.com/carlosnavarroc/DeloreanCamara" target="_blank">
https://github.com/carlosnavarroc/DeloreanCamara
</a>
</div>
