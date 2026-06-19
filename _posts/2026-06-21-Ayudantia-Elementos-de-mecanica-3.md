---
title: 'Ayudantía 3 Elementos de Mecánica — Círculo de Mohr y Teoría de Falla de Von Mises'
date: 2026-06-21
permalink: /posts/2026/06/01/ayudantia-circulo-mohr-von-mises/
tags:
  - Resistencia de Materiales
  - Mecánica
  - Beer and Johnston
  - Círculo de Mohr
  - Von Mises
  - Ingeniería Mecánica
  - Ingeniería Civil
  - Ayudantías
excerpt: 'Guía universitaria de Resistencia de Materiales enfocada en estado plano de esfuerzos, círculo de Mohr y teoría de falla de Von Mises.'
---

<div style="text-align: justify;">

En esta ayudantía se desarrollan conceptos fundamentales asociados al análisis de esfuerzos en dos dimensiones, basados en los contenidos de Resistencia de Materiales y Mecánica de Materiales.

El objetivo principal es reforzar contenidos relacionados con:

<ul>
<li>Estado plano de esfuerzos</li>
<li>Esfuerzos principales</li>
<li>Esfuerzo cortante máximo</li>
<li>Círculo de Mohr en 2D</li>
<li>Orientación de planos principales</li>
<li>Teoría de falla de Von Mises</li>
<li>Integración de esfuerzos normales y cortantes</li>
</ul>

</div>

<br>

# 1. Resumen Teórico

## Estado plano de esfuerzos

Un estado plano de esfuerzos queda definido por:

$$
\sigma_x
$$

$$
\sigma_y
$$

$$
\tau_{xy}
$$

donde:

- $\sigma_x$: esfuerzo normal en dirección x.
- $\sigma_y$: esfuerzo normal en dirección y.
- $\tau_{xy}$: esfuerzo cortante.

---

## Esfuerzos principales

$$
\sigma_{1,2}=\frac{\sigma_x+\sigma_y}{2}\pm\sqrt{\left(\frac{\sigma_x-\sigma_y}{2}\right)^2+\tau_{xy}^2}
$$

---

## Esfuerzo cortante máximo

$$ \tau_{max} = \sqrt{ \left( \frac{\sigma_x-\sigma_y}{2} \right)^2 + \tau_{xy}^2 } $$

---

## Orientación de los planos principales

$$ \tan(2\theta_p) = \frac{2\tau_{xy}} {\sigma_x-\sigma_y} $$ 

---

## Centro del círculo de Mohr

$$ C= \frac{\sigma_x+\sigma_y}{2} $$

---

## Radio del círculo de Mohr

$$ R= \sqrt{ \left( \frac{\sigma_x-\sigma_y}{2} \right)^2 + \tau_{xy}^2 }
$$

---

## Teoría de Von Mises

$$ \sigma_{VM} = \sqrt{ \sigma_x^2 - \sigma_x\sigma_y + \sigma_y^2 + 3\tau_{xy}^2 } $$

---

## Factor de seguridad

$$ n= \frac{\sigma_Y} {\sigma_{VM}} $$

---

<br>

# 2. Formulario Resumen

| Tema | Fórmula |
|---|---|
| Centro de Mohr | $C=\frac{\sigma_x+\sigma_y}{2}$ |
| Radio de Mohr | $R=\sqrt{\left(\frac{\sigma_x-\sigma_y}{2}\right)^2+\tau_{xy}^2}$ |
| Esfuerzo principal mayor | $\sigma_1=C+R$ |
| Esfuerzo principal menor | $\sigma_2=C-R$ |
| Cortante máximo | $\tau_{max}=R$ |
| Orientación principal | $\tan(2\theta_p)=\frac{2\tau_{xy}}{\sigma_x-\sigma_y}$ |
| Von Mises | $\sigma_{VM}=\sqrt{\sigma_x^2-\sigma_x\sigma_y+\sigma_y^2+3\tau_{xy}^2}$ |
| Factor de seguridad | $n=\frac{\sigma_Y}{\sigma_{VM}}$ |

<br>

# 3. Ejercicios

## Ejercicio 1 — Repaso de esfuerzo normal y deformación

### Enunciado

Una barra de acero de longitud 2.5 m y diámetro 20 mm está sometida a una carga axial de tracción de 80 kN.

Considere:

$$ E=200\,GPa $$

### Se pide

1. Esfuerzo normal.
2. Deformación unitaria.
3. Alargamiento.

---

## Solución Ejercicio 1

### Área transversal

$$ A= \frac{\pi d^2}{4} $$ 

$$ A= \frac{\pi(20)^2}{4} = 314.16\,mm^2 $$

### Esfuerzo normal

$$ \sigma= \frac{P}{A} $$

$$ \sigma= \frac{80000}{314.16} = 254.65\,MPa $$

### Deformación unitaria

$$ \varepsilon= \frac{\sigma}{E} $$

$$ \varepsilon= \frac{254.65\times10^6} {200\times10^9} =  1.27\times10^{-3} $$

### Alargamiento

$$ \delta= \varepsilon L $$  

$$ \delta= (1.27\times10^{-3})(2.5) = 3.18\,mm $$

### Resultado

$$ \boxed{\sigma=254.65\,MPa} $$

$$ \boxed{\delta=3.18\,mm} $$

---

## Ejercicio 2 — Repaso de torsión

### Enunciado

Un eje macizo de acero de diámetro 50 mm transmite un torque de 2 kN·m.

Considere:

$$ G=80\,GPa $$

$$ L=2\,m $$

### Se pide

1. Esfuerzo cortante máximo.
2. Ángulo de torsión.

---

## Solución Ejercicio 2

### Momento polar

$$ J= \frac{\pi d^4}{32} $$

$$ J= 6.14\times10^{-7}\,m^4 $$

### Esfuerzo cortante máximo

$$ \tau= \frac{Tc}{J} $$

$$ \tau= \frac{(2000)(0.025)} {6.14\times10^{-7}} = 81.4\,MPa $$

### Ángulo de torsión

$$ \phi= \frac{TL}{JG} $$

$$ \phi= \frac{(2000)(2)} {(6.14\times10^{-7})(80\times10^9)} = 0.0814\,rad $$ 

$$ \phi= 4.66^\circ $$

### Resultado

$$ \boxed{\tau_{max}=81.4\,MPa} $$

$$ \boxed{\phi=4.66^\circ} $$

---

## Ejercicio 3 — Esfuerzos principales

### Enunciado

Un elemento está sometido al siguiente estado plano de esfuerzos:

$$ \sigma_x=80\,MPa $$

$$ \sigma_y=20\,MPa $$

$$ \tau_{xy}=30\,MPa $$
 
### Se pide

1. Centro del círculo de Mohr.
2. Radio del círculo.
3. Esfuerzos principales.

---

## Solución Ejercicio 3

### Centro

$$ C= \frac{\sigma_x+\sigma_y}{2} $$

$$ C= \frac{80+20}{2} = 50\,MPa $$
 
### Radio

$$ R= \sqrt{ \left( \frac{80-20}{2} \right)^2 + 30^2 } $$

$$ R= 42.43\,MPa $$ 

### Esfuerzo principal mayor

$$ \sigma_1=C+R $$

$$ \sigma_1= 50+42.43 = 92.43\,MPa $$

### Esfuerzo principal menor

$$ \sigma_2=C-R $$

$$ \sigma_2= 50-42.43 = 7.57\,MPa $$

### Resultados

$$ \boxed{\sigma_1=92.43\,MPa} $$

$$ \boxed{\sigma_2=7.57\,MPa} $$

## Ejercicio 4 — Círculo de Mohr completo

### Enunciado

Un elemento está sometido al siguiente estado plano de esfuerzos:

$$ \sigma_x=120\,MPa $$

$$ \sigma_y=-40\,MPa $$

$$ \tau_{xy}=50\,MPa $$

### Se pide

1. Centro del círculo de Mohr.
2. Radio del círculo.
3. Esfuerzos principales.
4. Esfuerzo cortante máximo.
5. Orientación de los planos principales.

---

## Solución Ejercicio 4

### Centro del círculo

$$ C= \frac{\sigma_x+\sigma_y}{2} $$
$$ C= \frac{120-40}{2} = 40\,MPa $$

---

### Radio 
$$ R= \sqrt{ \left( \frac{120-(-40)}{2} \right)^2 + 50^2 }$$

$$ R= \sqrt{ 80^2+50^2 } $$

$$ R= 94.34\,MPa $$ 

---

### Esfuerzo principal mayor

$$ \sigma_1= C+R $$

$$ \sigma_1= 40+94.34 = 134.34\,MPa $$

---

### Esfuerzo principal menor

$$ \sigma_2= C-R $$  
$$ \sigma_2= 40-94.34 = -54.34\,MPa $$

---

### Esfuerzo cortante máximo

$$ \tau_{max}=R $$
$$ \tau_{max} = 94.34\,MPa $$

---

### Orientación principal
$$ \tan(2\theta_p) = \frac{2\tau_{xy}} {\sigma_x-\sigma_y} $$
$$ \tan(2\theta_p) = \frac{100}{160} $$
$$ 2\theta_p= 32.0^\circ $$

$$ \theta_p= 16.0^\circ $$

---

### Resultados

$$ \boxed{ \sigma_1=134.34\,MPa } $$
$$ \boxed{ \sigma_2=-54.34\,MPa } $$

$$ \boxed{ \tau_{max}=94.34\,MPa } $$ 
$$ \boxed{ \theta_p=16.0^\circ } $$
---

## Ejercicio 5 — Teoría de falla de Von Mises

### Enunciado

Un elemento de acero está sometido a:

$$
\sigma_x=100\,MPa
$$

$$
\sigma_y=30\,MPa
$$

$$
\tau_{xy}=40\,MPa
$$

El límite de fluencia del material es:

$$
\sigma_Y=250\,MPa
$$

### Se pide

1. Esfuerzo equivalente de Von Mises.
2. Factor de seguridad.
3. Determinar si existe fluencia.

---

## Solución Ejercicio 5

### Esfuerzo equivalente de Von Mises

$$
\sigma_{VM}
=
\sqrt{
\sigma_x^2
-\sigma_x\sigma_y
+\sigma_y^2
+
3\tau_{xy}^2
}
$$

Sustituyendo:

$$
\sigma_{VM}
=
\sqrt{
100^2
-(100)(30)
+30^2
+3(40)^2
}
$$

$$
\sigma_{VM}
=
\sqrt{
10000
-3000
+900
+4800
}
$$

$$
\sigma_{VM}
=
\sqrt{
12700
}
$$

$$
\sigma_{VM}
=
112.69\,MPa
$$

---

### Factor de seguridad

$$
n=
\frac{\sigma_Y}
{\sigma_{VM}}
$$

$$
n=
\frac{250}
{112.69}
$$

$$
n=2.22
$$

---

### Verificación de falla

Como:

$$
\sigma_{VM}
<
\sigma_Y
$$

entonces:

$$
112.69<250
$$

El material trabaja de forma segura.

---

### Resultados

$$
\boxed{
\sigma_{VM}=112.69\,MPa
}
$$

$$
\boxed{
n=2.22
}
$$

No existe fluencia.

---

## Ejercicio 6 — Problema Integrador

### Enunciado

Un eje macizo de acero está sometido simultáneamente a:

- Carga axial:

$$
P=120\,kN
$$

- Torque:

$$
T=2\,kN\cdot m
$$

Diámetro:

$$
d=40\,mm
$$

Límite de fluencia:

$$
\sigma_Y=250\,MPa
$$

### Se pide

1. Esfuerzo normal.
2. Esfuerzo cortante.
3. Esfuerzos principales.
4. Esfuerzo equivalente de Von Mises.
5. Factor de seguridad.

---

## Solución Ejercicio 6

### Área transversal

$$
A=
\frac{\pi d^2}{4}
$$

$$
A=
\frac{\pi(40)^2}{4}
=
1256.64\,mm^2
$$

---

### Esfuerzo normal

$$
\sigma=
\frac{P}{A}
$$

$$
\sigma=
\frac{120000}
{1256.64}
=
95.49\,MPa
$$

---

### Momento polar

$$
J=
\frac{\pi d^4}{32}
$$

$$
J=
2.51\times10^5\,mm^4
$$

---

### Esfuerzo cortante

$$
\tau=
\frac{Tc}{J}
$$

$$
\tau=
\frac{
(2\times10^6)(20)
}
{
2.51\times10^5
}
$$

$$
\tau=
159.2\,MPa
$$

---

### Esfuerzos principales

Como:

$$
\sigma_x=95.49\,MPa
$$

$$
\sigma_y=0
$$

$$
\tau_{xy}=159.2\,MPa
$$

Centro:

$$
C=
\frac{95.49}{2}
=
47.75\,MPa
$$

Radio:

$$
R=
\sqrt{
47.75^2
+
159.2^2
}
=
166.2\,MPa
$$

---

### Esfuerzos principales

$$
\sigma_1=
47.75+166.2
=
213.95\,MPa
$$

$$
\sigma_2=
47.75-166.2
=
-118.45\,MPa
$$

---

### Von Mises

$$
\sigma_{VM}
=
\sqrt{
95.49^2
+
3(159.2)^2
}
$$

$$
\sigma_{VM}
=
291.9\,MPa
$$

---

### Factor de seguridad

$$
n=
\frac{250}
{291.9}
$$

$$
n=0.86
$$

---

### Interpretación

Como:

$$
n<1
$$

el eje falla por fluencia.

---

### Resultados

$$
\boxed{
\sigma=95.49\,MPa
}
$$

$$
\boxed{
\tau=159.2\,MPa
}
$$

$$
\boxed{
\sigma_1=213.95\,MPa
}
$$

$$
\boxed{
\sigma_2=-118.45\,MPa
}
$$

$$
\boxed{
\sigma_{VM}=291.9\,MPa
}
$$

$$
\boxed{
n=0.86
}
$$

---

# 5. Errores Frecuentes de los Estudiantes

## En Círculo de Mohr

- Confundir centro con radio.
- Utilizar signos incorrectos para el esfuerzo cortante.
- Intercambiar esfuerzos principales.

---

## En Von Mises

- Olvidar el término:

$$
-\sigma_x\sigma_y
$$

- Utilizar resistencia última en lugar de límite de fluencia.

---

## En problemas combinados

- Mezclar unidades de MPa y Pa.
- No convertir N·m a N·mm.
- Utilizar radios en lugar de diámetros incorrectamente.

---

# Recomendaciones para el Examen

<div style="text-align: justify;">

<ul>
<li>Dibujar siempre el elemento diferencial.</li>
<li>Identificar claramente los esfuerzos normales y cortantes.</li>
<li>Calcular primero centro y radio del círculo de Mohr.</li>
<li>Verificar que $\sigma_1>\sigma_2$.</li>
<li>Comprobar unidades antes de reemplazar valores.</li>
<li>Evaluar siempre el criterio de Von Mises cuando se solicite verificar falla.</li>
<li>Encerrar los resultados finales.</li>
</ul>

</div>

<br>
$$

---
