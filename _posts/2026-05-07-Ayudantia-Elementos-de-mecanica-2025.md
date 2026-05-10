---
title: 'Ayudantía 2 Elementos de Mecánica — Resistencia de Materiales'
date: 2026-05-07
permalink: /posts/2026/05/07/ayudantia-resistencia-materiales-beer-johnston/
tags:
  - Resistencia de Materiales
  - Mecánica
  - Beer and Johnston
  - Ingeniería Mecánica
  - Ingeniería Civil
  - Ayudantías
excerpt: 'Guía universitaria de Resistencia de Materiales basada en Beer & Johnston, enfocada en equilibrio del cuerpo rígido, esfuerzos normales y torsión.'
---

<div style="text-align: justify;">

En esta ayudantía se desarrollan conceptos fundamentales de Resistencia de Materiales basados en el texto <strong>“Mecánica de Materiales – Beer & Johnston”</strong>. 

El objetivo principal es reforzar contenidos esenciales relacionados con:

<ul>
<li>Equilibrio del cuerpo rígido</li>
<li>Esfuerzos normales</li>
<li>Torsión</li>
<li>Diagramas de cuerpo libre</li>
<li>Sumatoria de fuerzas y momentos</li>
<li>Descomposición de fuerzas inclinadas</li>
</ul>

La guía está organizada de manera progresiva, comenzando con ejercicios básicos de equilibrio antes de integrar cálculo de esfuerzos y torsión.

</div>

<br>

# 1. Resumen Teórico

## Equilibrio del cuerpo rígido

<div style="text-align: justify;">

Un cuerpo rígido se encuentra en equilibrio cuando la suma de todas las fuerzas y momentos que actúan sobre él es igual a cero.

</div>

### Ecuaciones de equilibrio

$$
\sum F_x = 0
$$

$$
\sum F_y = 0
$$

$$
\sum M = 0
$$

### Convención de signos

- Fuerzas hacia la derecha: positivas.
- Fuerzas hacia arriba: positivas.
- Momentos antihorarios: positivos.
- Momentos horarios: negativos.

### Errores frecuentes

- No dibujar correctamente el diagrama de cuerpo libre.
- Omitir reacciones en apoyos.
- Confundir signos de momentos.
- Descomponer incorrectamente fuerzas inclinadas.

---

## Esfuerzo normal

El esfuerzo normal representa la intensidad de fuerza distribuida sobre una sección transversal.

$$
\sigma = \frac{P}{A}
$$

Donde:

- $\sigma$: esfuerzo normal
- $P$: carga axial
- $A$: área transversal

### Interpretación física

- Tracción → esfuerzo positivo.
- Compresión → esfuerzo negativo.

---

## Deformación unitaria

$$
\varepsilon = \frac{\delta}{L}
$$

Donde:

- $\varepsilon$: deformación unitaria
- $\delta$: deformación longitudinal
- $L$: longitud original

---

## Ley de Hooke

$$
\sigma = E\varepsilon
$$

Donde:

- $E$: módulo de elasticidad
- $\sigma$: esfuerzo normal
- $\varepsilon$: deformación unitaria

---

## Torsión

La torsión aparece cuando un eje está sometido a momentos torsores.

### Esfuerzo cortante máximo

$$
\tau = \frac{Tc}{J}
$$

### Ángulo de torsión

$$
\phi = \frac{TL}{JG}
$$

### Momento polar para eje circular macizo

$$
J = \frac{\pi d^4}{32}
$$

<hr>

# 2. Formulario Resumen

| Tema | Fórmula |
|---|---|
| Equilibrio horizontal | $\sum F_x = 0$ |
| Equilibrio vertical | $\sum F_y = 0$ |
| Equilibrio de momentos | $\sum M = 0$ |
| Esfuerzo normal | $\sigma = \frac{P}{A}$ |
| Deformación unitaria | $\varepsilon = \frac{\delta}{L}$ |
| Ley de Hooke | $\sigma = E\varepsilon$ |
| Esfuerzo por torsión | $\tau = \frac{Tc}{J}$ |
| Ángulo de torsión | $\phi = \frac{TL}{JG}$ |
| Momento polar | $J = \frac{\pi d^4}{32}$ |

<hr>


# 3. Ejercicios

## Ejercicio 1 — Equilibrio del cuerpo rígido

### Enunciado

Una viga horizontal de 6 m de longitud está simplemente apoyada en A y B. Sobre ella actúa una carga puntual vertical de 8 kN ubicada a 2 m del apoyo A.

### Se pide

1. Reacción vertical en A.
2. Reacción vertical en B.

---

## Ejercicio 2 — Equilibrio del cuerpo rígido

### Enunciado

Una ménsula articulada en A sostiene una carga inclinada de 10 kN aplicada en el extremo libre B formando 30° respecto de la horizontal.

### Se pide

1. Componentes horizontal y vertical.
2. Reacciones en A.

---

## Ejercicio 3 — Esfuerzo normal

### Enunciado

Una barra de acero de diámetro 25 mm está sometida a una carga axial de tracción de 120 kN.

### Se pide

Determinar el esfuerzo normal promedio.

---

## Ejercicio 4 — Esfuerzo normal y deformación

### Enunciado

Una barra de aluminio de longitud 2 m y área transversal de 500 mm² soporta una carga axial de 40 kN.

Considere:

$$
E = 70\,GPa
$$

### Se pide

1. Esfuerzo normal.
2. Deformación unitaria.
3. Alargamiento total.

---

## Ejercicio 5 — Torsión

### Enunciado

Un eje circular macizo de acero de diámetro 40 mm transmite un torque de 1.5 kN·m.

### Se pide

Determinar el esfuerzo cortante máximo.

---

## Ejercicio 6 — Torsión y ángulo de giro

### Enunciado

Un eje circular macizo de acero tiene longitud de 2.5 m y diámetro de 50 mm.

Considere:

$$
G = 80\,GPa
$$

### Se pide

1. Esfuerzo cortante máximo.
2. Ángulo de torsión.

<br>

# 4. Soluciones

## Solución Ejercicio 1

### Sumatoria de momentos respecto a A

$$
B_y(6)-8(2)=0
$$

$$
B_y=2.67\,kN
$$

### Sumatoria de fuerzas verticales

$$
A_y+B_y-8=0
$$

$$
A_y=5.33\,kN
$$

### Resultados

$$
A_y=5.33\,kN
$$

$$
B_y=2.67\,kN
$$

---

## Solución Ejercicio 2

### Descomposición de fuerzas

$$
F_x=10\cos30^\circ=8.66\,kN
$$

$$
F_y=10\sin30^\circ=5\,kN
$$

### Equilibrio

$$
A_x=8.66\,kN
$$

$$
A_y=5\,kN
$$

---

## Solución Ejercicio 3

### Área transversal

$$
A=\frac{\pi d^2}{4}
$$

$$
A=490.87\,mm^2
$$

### Esfuerzo normal

$$
\sigma=\frac{120000}{490.87}
$$

$$
\sigma=244.46\,MPa
$$

### Resultado final

$$
\boxed{\sigma=244.46\,MPa}
$$

---

## Solución Ejercicio 4

### Esfuerzo normal

$$
\sigma=\frac{40000}{5\times10^{-4}}
$$

$$
\sigma=80\,MPa
$$

### Deformación unitaria

$$
\varepsilon=\frac{80\times10^6}{70\times10^9}
$$

$$
\varepsilon=1.14\times10^{-3}
$$

### Alargamiento

$$
\delta=(1.14\times10^{-3})(2)
$$

$$
\delta=2.29\,mm
$$

---

## Solución Ejercicio 5

### Momento polar

$$
J=\frac{\pi(0.04)^4}{32}
$$

$$
J=2.51\times10^{-7}\,m^4
$$

### Esfuerzo cortante máximo

$$
\tau=\frac{1500(0.02)}{2.51\times10^{-7}}
$$

$$
\tau=119\,MPa
$$

### Resultado final

$$
\boxed{\tau_{max}=119\,MPa}
$$

---

## Solución Ejercicio 6

### Momento polar

$$
J=\frac{\pi(0.05)^4}{32}
$$

$$
J=6.14\times10^{-7}\,m^4
$$

### Esfuerzo cortante máximo

$$
\tau=\frac{2000(0.025)}{6.14\times10^{-7}}
$$

$$
\tau=81.4\,MPa
$$

### Ángulo de torsión

$$
\phi=\frac{2000(2.5)}{(6.14\times10^{-7})(80\times10^9)}
$$

$$
\phi=0.1018\,rad
$$

$$
\phi=5.83^\circ
$$

<br>

# 5. Errores Frecuentes de los Estudiantes

## En equilibrio

- Omitir reacciones.
- Aplicar mal los signos.
- Confundir momentos positivos y negativos.
- No descomponer correctamente fuerzas inclinadas.

---

## En esfuerzos normales

- No convertir unidades.
- Calcular incorrectamente el área.
- Confundir tracción con compresión.

---

## En torsión

- Confundir torque con fuerza.
- Usar incorrectamente el momento polar.
- No convertir kN·m a N·m.

<br>

# Recomendaciones para pruebas

<div style="text-align: justify;">

<ul>
<li>Dibujar siempre el diagrama de cuerpo libre.</li>
<li>Ordenar el desarrollo algebraico.</li>
<li>Verificar unidades antes de reemplazar.</li>
<li>Encerrar resultados finales.</li>
<li>Mantener consistencia de signos.</li>
<li>Revisar si el resultado tiene sentido físico.</li>
</ul>

</div>
