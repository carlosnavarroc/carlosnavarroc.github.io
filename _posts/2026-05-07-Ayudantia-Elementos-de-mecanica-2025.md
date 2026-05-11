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

<img width="665" height="352" alt="image" src="https://github.com/user-attachments/assets/db7885fc-4d7f-470e-a8c4-181841886dba" />


### Se pide

1. Reacción vertical en A.
2. Reacción vertical en B.

---

## Ejercicio 2 — Equilibrio del cuerpo rígido

### Enunciado

Una ménsula articulada en A sostiene una carga inclinada de 10 kN aplicada en el extremo libre B formando 30° respecto de la horizontal.

<img width="711" height="318" alt="image" src="https://github.com/user-attachments/assets/f8dfe2dc-ee84-416b-827b-128cc8e31f6c" />


### Se pide

1. Componentes horizontal y vertical.
2. Reacciones en A.

---

## Ejercicio 3 — Esfuerzo normal

### Enunciado

Una barra de acero de diámetro 25 mm está sometida a una carga axial de tracción de 120 kN.

<img width="741" height="222" alt="image" src="https://github.com/user-attachments/assets/233f8581-0b72-4f44-9622-24f3891cdc1a" />


### Se pide

Determinar el esfuerzo normal promedio.

---

## Ejercicio 4 — Esfuerzo normal y deformación con equilibrio

### Enunciado

Una barra de aluminio está empotrada en el extremo A y sometida a dos cargas axiales como se muestra:

- En el punto B actúa una fuerza de $20\,kN$ hacia la derecha.
- En el extremo C actúa una fuerza de $60\,kN$ hacia la izquierda.

La barra posee:

- longitud total de $2\,m$,
- área transversal de $500\,mm^2$.

Considere:

$$
E = 70\,GPa
$$

<img width="1774" height="887" alt="image" src="https://github.com/user-attachments/assets/688981a8-93a9-435f-aee9-653a482930ae" />


### Se pide

1. Determinar la reacción axial en A.
2. Determinar la fuerza interna en la barra.
3. Determinar el esfuerzo normal.
4. Determinar la deformación unitaria.
5. Determinar el alargamiento total.

---

## Ejercicio 5 — Torsión

### Enunciado

Un eje circular macizo de acero de diámetro 40 mm transmite un torque de 1.5 kN·m.

<img width="680" height="204" alt="image" src="https://github.com/user-attachments/assets/f9f5feda-ad43-4ba3-8bb0-5b1554fd85ea" />


### Se pide

Determinar el esfuerzo cortante máximo.

---

## Ejercicio 6 — Torsión y ángulo de giro

### Enunciado

Un eje circular macizo de acero tiene longitud de 2.5 m y diámetro de 50 mm.

<img width="782" height="225" alt="image" src="https://github.com/user-attachments/assets/ecab5d4b-7e04-496e-ba10-9538e27e5d1f" />

Considere:

$$
G = 80\,GPa
$$

### Se pide

1. Esfuerzo cortante máximo.
2. Ángulo de torsión.

<br>

<img width="1309" height="140" alt="image" src="https://github.com/user-attachments/assets/8eae1a37-8ce4-4aa1-be04-1554e14d3632" />

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

### Paso 1: Diagrama de cuerpo libre

Se considera la barra completa en equilibrio axial.

Fuerzas actuando:

- Reacción axial $A_x$
- Fuerza de $20\,kN$ hacia la derecha
- Fuerza de $60\,kN$ hacia la izquierda

---

### Paso 2: Ecuación de equilibrio

Aplicando equilibrio en el eje horizontal:

$$
\sum F_x = 0
$$

$$
A_x + 20 - 60 = 0
$$

$$
A_x = 40\,kN
$$

---

### Paso 3: Fuerza interna axial

La fuerza interna en la barra es:

$$
P = 40\,kN
$$

Convirtiendo:

$$
P = 40000\,N
$$

---

### Paso 4: Conversión del área

$$
A = 500\,mm^2
$$

$$
A = 5\times10^{-4}\,m^2
$$

---

### Paso 5: Esfuerzo normal

Aplicando:

$$
\sigma = \frac{P}{A}
$$

$$
\sigma = \frac{40000}{5\times10^{-4}}
$$

$$
\sigma = 80\times10^6\,Pa
$$

$$
\sigma = 80\,MPa
$$

---

### Paso 6: Deformación unitaria

Usando Ley de Hooke:

$$
\varepsilon = \frac{\sigma}{E}
$$

$$
\varepsilon = \frac{80\times10^6}{70\times10^9}
$$

$$
\varepsilon = 1.14\times10^{-3}
$$

---

### Paso 7: Alargamiento total

Aplicando:

$$
\delta = \varepsilon L
$$

$$
\delta = (1.14\times10^{-3})(2)
$$

$$
\delta = 2.29\times10^{-3}\,m
$$

$$
\delta = 2.29\,mm
$$

---

### Resultados finales

$$
\boxed{A_x = 40\,kN}
$$

$$
\boxed{\sigma = 80\,MPa}
$$

$$
\boxed{\varepsilon = 1.14\times10^{-3}}
$$

$$
\boxed{\delta = 2.29\,mm}
$$

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
---

# 6. Problemas Complementarios 

## Problema 7 — Deformación de una varilla de acero

### Enunciado

Determine la deformación total de la varilla de acero mostrada en la figura bajo las cargas axiales indicadas.

Considere:

$$
E = 29\times10^6\,psi
$$

<img width="429" height="187" alt="image" src="https://github.com/user-attachments/assets/5e4cd497-d5b5-407e-bc9f-e056b46c2600" />

### Se pide

1. Determinar el esfuerzo normal en cada tramo.
2. Determinar la deformación de cada segmento.
3. Determinar la deformación total de la varilla.

### Sugerencias metodológicas

- Realizar el diagrama de cuerpo libre.
- Determinar la fuerza interna en cada tramo.
- Aplicar:

$$
\delta = \frac{PL}{AE}
$$

- Mantener consistencia de unidades.

---

## Problema 8 — Barra rígida soportada por dos eslabones

### Enunciado

La barra rígida BDE se encuentra soportada por dos eslabones verticales AB y CD.

- El eslabón AB es de aluminio:

$$
E_{Al} = 70\,GPa
$$

$$
A_{Al} = 500\,mm^2
$$

- El eslabón CD es de acero:

$$
E_{Ac} = 200\,GPa
$$

$$
A_{Ac} = 600\,mm^2
$$

Sobre la barra actúa una carga vertical de:

$$
P = 30\,kN
$$

<img width="383" height="311" alt="image" src="https://github.com/user-attachments/assets/2a91adac-47d8-43f2-b6b9-de961ab90420" />



### Se pide

1. Determinar la deflexión en B.
2. Determinar la deflexión en D.
3. Determinar la deflexión en E.

### Sugerencias metodológicas

- Resolver primero el equilibrio de la barra rígida.
- Determinar las fuerzas en los eslabones.
- Aplicar deformación axial:

$$
\delta = \frac{PL}{AE}
$$

- Utilizar compatibilidad geométrica.

---

## Problema 9 — Cable sometido a carga axial

### Enunciado

El cable BC de diámetro:

$$
d = 4\,mm
$$

está fabricado de acero con:

$$
E = 200\,GPa
$$

Se sabe que:

- el esfuerzo normal máximo no debe exceder:

$$
\sigma_{adm} = 190\,MPa
$$

- la elongación máxima permitida es:

$$
\delta_{max} = 6\,mm
$$

<img width="319" height="265" alt="image" src="https://github.com/user-attachments/assets/be9fada1-fdfd-4658-96a3-a8765f93908a" />

### Se pide

Determinar la carga máxima $P$ que puede aplicarse al sistema.

### Sugerencias metodológicas

- Evaluar primero la condición de esfuerzo admisible:

$$
\sigma = \frac{P}{A}
$$

- Evaluar luego la condición de deformación:

$$
\delta = \frac{PL}{AE}
$$

- Comparar ambos resultados.
- Seleccionar la carga permisible más pequeña.

---

## Problema 10 — Probeta compuesta de acero

### Enunciado

La probeta mostrada está compuesta por:

- una varilla cilíndrica de acero de diámetro:

$$
d = 1\,in
$$

- dos soportes de diámetro exterior:

$$
d_o = 1.5\,in
$$

Considere:

$$
E = 29\times10^6\,psi
$$

Se sabe que la deformación total es:

$$
\delta = 0.002\,in
$$

<img width="437" height="313" alt="image" src="https://github.com/user-attachments/assets/5776c570-7588-424f-b77d-53c0a93963c8" />


### Se pide

1. Determinar la carga axial $P$.
2. Determinar la deformación correspondiente de la porción central BC.

### Sugerencias metodológicas

- Dividir la probeta en segmentos.
- Determinar el área de cada tramo.
- Aplicar superposición de deformaciones:

$$
\delta_{total} = \sum \frac{PL}{AE}
$$

- Mantener consistencia de unidades en pulgadas y psi.

---

## Problema 11 — Eje cilíndrico hueco sometido a torsión

### Enunciado

Un eje cilíndrico hueco de acero posee:

- longitud:

$$
L = 1.5\,m
$$

- diámetro interior:

$$
d_i = 40\,mm
$$

- diámetro exterior:

$$
d_o = 60\,mm
$$

<img width="485" height="305" alt="image" src="https://github.com/user-attachments/assets/16008785-640f-46a7-a827-79e8e8a209c6" />


### Se pide

1. Determinar el máximo torque que puede aplicarse al eje si el esfuerzo cortante no debe exceder:

$$
\tau_{adm} = 120\,MPa
$$

2. Determinar el valor mínimo correspondiente del esfuerzo cortante en el eje.

### Sugerencias metodológicas

- Calcular el momento polar de inercia para sección circular hueca:

$$
J = \frac{\pi}{32}\left(d_o^4-d_i^4\right)
$$

- Aplicar la ecuación de torsión:

$$
\tau = \frac{Tc}{J}
$$

- El esfuerzo cortante máximo ocurre en el radio exterior.
- El esfuerzo cortante mínimo ocurre en el radio interior.

---

## Problema 12 — Sistema de ejes sometidos a torsión

### Enunciado

El eje BC es hueco y posee:

- diámetro interior:

$$
d_i = 90\,mm
$$

- diámetro exterior:

$$
d_o = 120\,mm
$$

Los ejes AB y CD son macizos y poseen diámetro:

$$
d
$$

El sistema está sometido al torque mostrado en la figura.
<img width="400" height="433" alt="image" src="https://github.com/user-attachments/assets/caa4492c-2fb4-4a2b-9004-fca4be70ae03" />




### Se pide

1. Determinar los esfuerzos cortantes máximo y mínimo en el eje BC.
2. Determinar el diámetro requerido $d$ en los ejes AB y CD si el esfuerzo cortante permisible es:

$$
\tau_{adm} = 65\,MPa
$$

### Sugerencias metodológicas

- Calcular el momento polar para el eje hueco:

$$
J = \frac{\pi}{32}\left(d_o^4-d_i^4\right)
$$

- Determinar los esfuerzos máximo y mínimo usando:

$$
\tau = \frac{Tc}{J}
$$

- Para los ejes sólidos AB y CD utilizar:

$$
J = \frac{\pi d^4}{32}
$$

- Despejar el diámetro requerido a partir del esfuerzo permisible.

# 7. Soluciones — Problemas Complementarios

---

# Solución Problema 7 — Deformación de una varilla escalonada

## Datos

- Área tramo AB:

$$
A_{AB}=0.9\,in^2
$$

- Área tramo CD:

$$
A_{CD}=0.3\,in^2
$$

- Longitudes:

$$
L_{AB}=12\,in
$$

$$
L_{BC}=12\,in
$$

$$
L_{CD}=16\,in
$$

- Módulo de elasticidad:

$$
E=29\times10^6\,psi
$$

---

## Fuerzas internas

### Tramo AB

$$
P_{AB}=60\,kips
$$

### Tramo BC

$$
P_{BC}=-15\,kips
$$

(compresión)

### Tramo CD

$$
P_{CD}=30\,kips
$$

---

## Deformación de cada tramo

Aplicando:

$$
\delta=\frac{PL}{AE}
$$

---

### Tramo AB

$$
\delta_{AB}=
\frac{(60\times10^3)(12)}
{(0.9)(29\times10^6)}
$$

$$
\delta_{AB}=0.0276\,in
$$

---

### Tramo BC

$$
\delta_{BC}=
\frac{(-15\times10^3)(12)}
{(0.9)(29\times10^6)}
$$

$$
\delta_{BC}=-0.0069\,in
$$

---

### Tramo CD

$$
\delta_{CD}=
\frac{(30\times10^3)(16)}
{(0.3)(29\times10^6)}
$$

$$
\delta_{CD}=0.0552\,in
$$

---

## Deformación total

$$
\delta_T=
0.0276-0.0069+0.0552
$$

$$
\boxed{
\delta_T=0.0759\,in
}
$$

---

# Solución Problema 8 — Barra rígida y eslabones

## Datos

- Carga:

$$
P=30\,kN
$$

- Distancias:

$$
BD=0.2\,m
$$

$$
DE=0.4\,m
$$

- Longitudes:

$$
L_{AB}=0.3\,m
$$

$$
L_{CD}=0.4\,m
$$

---

## Equilibrio de momentos respecto a B

$$
F_{CD}(0.2)-30(0.6)=0
$$

$$
F_{CD}=90\,kN
$$

---

## Equilibrio vertical

$$
F_{AB}+F_{CD}-30=0
$$

$$
F_{AB}=-60\,kN
$$

(compresión)

---

## Deflexión en B

$$
\delta_B=
\frac{PL}{AE}
$$

$$
\delta_B=
\frac{(60\times10^3)(0.3)}
{(500\times10^{-6})(70\times10^9)}
$$

$$
\boxed{
\delta_B=0.514\,mm
}
$$

---

## Deflexión en D

$$
\delta_D=
\frac{(90\times10^3)(0.4)}
{(600\times10^{-6})(200\times10^9)}
$$

$$
\boxed{
\delta_D=0.300\,mm
}
$$

---

## Deflexión en E

Usando compatibilidad geométrica y rotación de barra rígida:

La deflexión en B es negativa debido a que el eslabón AB está en compresión:

$$
\delta_B=-0.514\,mm
$$

La deflexión en D es positiva debido a que el eslabón CD está en tracción:

$$
\delta_D=0.300\,mm
$$

La separación entre B y D es:

$$
BD=0.2\,m=200\,mm
$$

Por lo tanto, la rotación de la barra rígida es:

$$
\theta=
\frac{
\delta_D-\delta_B
}{
200
}
$$

$$
\theta=
\frac{
0.300-(-0.514)
}{
200
}
$$

$$
\theta=0.00407\,rad
$$

---

La distancia entre D y E es:

$$
DE=0.4\,m=400\,mm
$$

Aplicando compatibilidad geométrica:

$$
\delta_E=
\delta_D+\theta(400)
$$

$$
\delta_E=
0.300+(0.00407)(400)
$$

$$
\boxed{
\delta_E=1.928\,mm
}
$$

---

# Solución Problema 9 — Cable sometido a carga axial

## Geometría del cable

Aplicando Pitágoras:

$$
BC=\sqrt{4^2+6^2}
$$

$$
BC=7.21\,m
$$

---

## Equilibrio de momentos respecto a A

Tomando momentos en A:

$$
\sum M_A=0
$$

La componente horizontal de la tensión del cable es:

$$
F_{BC,x}=
\left(
\frac{4}{7.21}
\right)
F_{BC}
$$

Aplicando equilibrio:

$$
(3.5)P-
(6)
\left(
\frac{4}{7.21}
\right)
F_{BC}=0
$$

Despejando:

$$
F_{BC}=1.05P
$$

---

## Área transversal del cable

$$
A=\frac{\pi d^2}{4}
$$

$$
A=
\frac{
\pi(4)^2
}{4}
$$

$$
A=4\pi\,mm^2
$$

---

# Condición de esfuerzo admisible

Aplicando:

$$
\sigma=
\frac{F}{A}
$$

$$
190\times10^6=
\frac{
1.05P
}{
4\pi\times10^{-6}
}
$$

Despejando:

$$
P=2.27\,kN
$$

---

## Resultado final

$$
\boxed{
P_{max}=2.27\,kN
}
$$

---
# Solución Problema 10 — Probeta escalonada

## Datos geométricos

### Tramos extremos AB y CD

$$
d=1.5\,in
$$

$$
L=2\,in
$$

---

### Tramo central BC

$$
d=1\,in
$$

$$
L=3\,in
$$

---

## Módulo de elasticidad

$$
E=29\times10^6\,psi
$$

---

# Deformación total

La deformación total es la suma de las deformaciones de cada tramo:

$$
\delta_T=
\delta_{AB}
+
\delta_{BC}
+
\delta_{CD}
$$

Como los extremos son idénticos:

$$
\delta_{AB}=\delta_{CD}
$$

Entonces:

$$
\delta_T=
2\delta_{AB}
+
\delta_{BC}
$$

Aplicando:

$$
\delta=
\frac{PL}{AE}
$$

---

## Sustituyendo áreas

Para los extremos:

$$
A_{AB}=
\pi(0.75)^2
$$

Para el tramo central:

$$
A_{BC}=
\pi(0.5)^2
$$

Entonces:

$$
0.002=
\frac{
P(3)
}{
\pi(0.5)^2(29\times10^6)
}
+
2
\frac{
P(2)
}{
\pi(0.75)^2(29\times10^6)
}
$$

---

## Resolviendo para \(P\)

$$
\boxed{
P=9534.38\,lb
}
$$

---

# Deformación del tramo BC

Aplicando:

$$
\delta_{BC}=
\frac{PL}{AE}
$$

$$
\delta_{BC}=
\frac{
(9534.38)(3)
}{
\pi(0.5)^2(29\times10^6)
}
$$

$$
\boxed{
\delta_{BC}=1.256\times10^{-3}\,in
}
$$

---

## Observación

Debido a que el tramo BC posee menor diámetro, presenta la mayor deformación axial del sistema.

---

# Solución Problema 11 — Eje hueco sometido a torsión

## Momento polar

$$
J=
\frac{\pi}{32}
(d_o^4-d_i^4)
$$

$$
J=
\frac{\pi}{32}
(60^4-40^4)
$$

$$
J=1.02\times10^6\,mm^4
$$

---

## Torque máximo

Aplicando:

$$
\tau=\frac{Tc}{J}
$$

Despejando:

$$
T=
\frac{\tau J}{c}
$$

$$
T=
\frac{
(120)(1.02\times10^6)
}
{30}
$$

$$
\boxed{
T_{max}=4.08\,kN\cdot m
}
$$

---

## Esfuerzo cortante mínimo

$$
\tau_{min}=
\tau_{max}
\left(
\frac{r_i}{r_o}
\right)
$$

$$
\tau_{min}=
120\left(
\frac{20}{30}
\right)
$$

$$
\boxed{
\tau_{min}=80\,MPa
}
$$

---

# Solución Problema 12 — Sistema de ejes sometidos a torsión

## Datos

### Eje hueco BC

$$
d_o=120\,mm
$$

$$
d_i=90\,mm
$$

---

## Torque aplicado

$$
T_{BC}=20\,kN\cdot m
$$

---

# a) Esfuerzos cortantes máximo y mínimo en el eje BC

## Momento polar del eje hueco

Aplicando:

$$
J=
\frac{\pi}{32}
\left(
d_o^4-d_i^4
\right)
$$

$$
J=
\frac{\pi}{32}
\left(
0.12^4-0.09^4
\right)
$$

$$
J=13.92\times10^{-6}\,m^4
$$

---

## Esfuerzo cortante máximo

El esfuerzo máximo ocurre en la superficie exterior:

$$
c_2=
\frac{120}{2}=60\,mm
$$

Aplicando:

$$
\tau=
\frac{Tc}{J}
$$

$$
\tau_{max}=
\frac{
(20\times10^3)(0.06)
}{
13.92\times10^{-6}
}
$$

$$
\boxed{
\tau_{max}=86.2\,MPa
}
$$

---

## Esfuerzo cortante mínimo

El esfuerzo mínimo ocurre en la superficie interior:

$$
c_1=
\frac{90}{2}=45\,mm
$$

Debido a que el esfuerzo cortante varía linealmente con el radio:

$$
\frac{
\tau_{min}
}{
\tau_{max}
}
=
\frac{
c_1
}{
c_2
}
$$

Entonces:

$$
\tau_{min}=
86.2
\left(
\frac{45}{60}
\right)
$$

$$
\boxed{
\tau_{min}=64.7\,MPa
}
$$

---

# b) Diámetro requerido para los ejes AB y CD

En ambos ejes:

$$
T=6\,kN\cdot m
$$

y el esfuerzo permisible es:

$$
\tau_{perm}=65\,MPa
$$

---

## Ecuación de torsión para eje macizo

Para un eje circular sólido:

$$
\tau=
\frac{Tc}{J}
$$

con:

$$
J=
\frac{\pi c^4}{2}
$$

Sustituyendo:

$$
65\times10^6=
\frac{
(6\times10^3)c
}{
\frac{\pi c^4}{2}
}
$$

---

## Resolviendo para \(c\)

$$
c^3=
58.8\times10^{-6}\,m^3
$$

$$
c=
38.9\times10^{-3}\,m
$$

---

## Diámetro requerido

$$
d=2c
$$

$$
\boxed{
d=77.8\,mm
}
$$

---


