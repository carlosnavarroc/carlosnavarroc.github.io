---
title: 'Cómo entender el cambio de orden en integrales dobles (dxdy ↔ dydx)'
date: 2026-05-06
permalink: /posts/2026/05/06/cambio-orden-integrales-dobles/
tags:
  - Integrales Dobles
  - Calculo Multivariable
  - Visualizacion
excerpt: 'Explicación visual del cambio de orden de integración para facilitar la comprensión de regiones en el plano.'
---
<div style="text-align: justify;">
Este es un resumen pensado para ayudar a entender el cambio de orden en integrales dobles de forma visual. La idea es que <strong>no cambia la región</strong>, solo cambia la forma en que la recorremos.
</div>  
<br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/5eaedfb9-86eb-4bff-b8f6-9493ea30d82b" alt="Ejemplo rectangulo">
</p>
<p align="center">
  <em>Figura 1: Región rectangular.</em>
</p>
<br>

<div style="text-align: justify;">
En este primer caso, la región es un rectángulo. No importa si se recorre primero en vertical o en horizontal: el resultado es el mismo. Este caso sirve para entender la idea base.
</div> 
<br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/97662591-c57a-43ff-b861-1cf7682a65ef" alt="Ejemplo triangulo">
</p>
<p align="center">
  <em>Figura 2: Región triangular.</em>
</p>
<br>

<div style="text-align: justify;">
La región ya no es rectangular, sino un triángulo.  Si integras en un orden, estás “barriendo” la región con líneas horizontales.  Si cambias el orden, ahora la recorres con líneas verticales.
</div>
<br>

<div style="text-align: justify;">
<strong>Es decir:</strong>
<ul>
<li>No cambia la región.</li>
<li>No cambia el área.</li>
<li>Solo cambia cómo se describe.</li>
</ul>
</div>
<br>

<div style="text-align: justify;">
Si esto cuesta, no es porque no se entienda matemática. Este tema requiere práctica visual. Intenta siempre dibujar la región antes de hacer cualquier cambio.
</div>
<br>

<div style="text-align: justify;">
Ahora viene lo importante. Considera una integral como esta:
</div>

<p align="center">
∫₀¹ ∫ᵧ¹ e^(x²) dx dy
</p>

<div style="text-align: justify;">
Esta integral <strong>no se puede resolver directamente</strong> porque la función e^(x²) no tiene primitiva simple en x.
</div>
<br>

<div style="text-align: justify;">
Entonces hacemos el cambio de orden:
</div>

<p align="center">
∫₀¹ ∫₀ˣ e^(x²) dy dx
</p>

<br>

<div style="text-align: justify;">
Ahora sí se puede resolver, porque la función no depende de y:
</div>

<p align="center">
∫₀¹ x·e^(x²) dx
</p>

<br>

<div style="text-align: justify;">
Y esta integral se resuelve con sustitución:
</div>

<p align="center">
u = x²  →  du = 2x dx
</p>

<p align="center">
Resultado: (1/2)(e − 1)
</p>

<br>

<div style="text-align: justify;">
Exito en la solemne.
</div>
