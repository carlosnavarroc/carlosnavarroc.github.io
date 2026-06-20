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

<img width="993" height="215" alt="image" src="https://github.com/user-attachments/assets/b7e9b6bf-58dc-4f9d-9b2e-1487705a9a7b" />


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

<img width="996" height="194" alt="image" src="https://github.com/user-attachments/assets/85a969af-7b34-4e83-9ebc-846164f32afe" />


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

<img width="989" height="244" alt="image" src="https://github.com/user-attachments/assets/0b22626d-6d40-4ba8-89df-f23183b87592" />

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

<img width="998" height="280" alt="image" src="https://github.com/user-attachments/assets/005bd848-853c-4b21-9e26-4e709b70b7e1" />

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

<img width="995" height="241" alt="image" src="https://github.com/user-attachments/assets/65dc2557-7680-4880-8efb-a031b4713cf8" />

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

<img width="807" height="269" alt="image" src="https://github.com/user-attachments/assets/28d89103-c414-4a61-a1f1-169c8468c43a" />

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


---

<br>

# 6. Problemas Desafiantes

Los siguientes problemas integran conceptos de estado plano de esfuerzos, círculo de Mohr y teoría de falla. Su nivel de dificultad es similar al esperado en una evaluación final de Resistencia de Materiales.

---

## Problema 7 — Transformación de esfuerzos

### Enunciado

Un elemento está sometido al siguiente estado plano de esfuerzos:

$$
\sigma_x=140\,MPa
$$

$$
\sigma_y=40\,MPa
$$

$$
\tau_{xy}=60\,MPa
$$

Determine:

1. Los esfuerzos sobre un plano girado 25° en sentido antihorario.
2. Los esfuerzos principales.
3. El esfuerzo cortante máximo.

<img width="981" height="316" alt="image" src="https://github.com/user-attachments/assets/2fc2e714-508c-43fe-9989-9ee2252e792d" />

---

## Solución Problema 7

### Centro del círculo de Mohr

$$ C= \frac{\sigma_x+\sigma_y}{2} = \frac{140+40}{2} = 90\,MPa $$

---

### Radio

$$ R= \sqrt{ \left( \frac{140-40}{2} \right)^2 + 60^2 } $$

$$ R= \sqrt{50^2+60^2} = 78.10\,MPa $$ 

---

### Esfuerzos principales

$$ \sigma_1=C+R $$

$$ \sigma_1= 90+78.10 = 168.10\,MPa $$

$$ \sigma_2=C-R $$

$$ \sigma_2= 90-78.10 = 11.90\,MPa $$

---

### Cortante máximo

$$ \tau_{max}=R $$

$$ \tau_{max} = 78.10\,MPa $$

---

### Orientación solicitada

$$ \theta=25^\circ \qquad 2\theta=50^\circ $$

Transformación de esfuerzos:

$$ \sigma_{x'} = C+ \frac{\sigma_x-\sigma_y}{2} \cos(50^\circ) + \tau_{xy}\sin(50^\circ) $$

$$ \sigma_{x'} = 90+ 50(0.6428) + 60(0.7660) $$

$$ \sigma_{x'} = 168.11\,MPa $$

---

$$ \tau_{x'y'} = - 50(0.7660) + 60(0.6428) $$

$$ \tau_{x'y'} = 0.25\,MPa $$

---

### Resultados

$$ \boxed{\sigma_{x'}=168.11\,MPa} $$

$$ \boxed{\tau_{x'y'}=0.25\,MPa} $$

$$ \boxed{\sigma_1=168.10\,MPa} $$

$$ \boxed{\sigma_2=11.90\,MPa} $$

$$ \boxed{\tau_{max}=78.10\,MPa} $$

---

## Problema 8 — Diseño mediante Von Mises

### Enunciado

Un componente mecánico de acero está sometido al siguiente estado plano de esfuerzos:

$$ \sigma_x=180\,MPa $$

$$ \sigma_y=50\,MPa $$

$$ \tau_{xy}=75\,MPa $$

El material posee un límite de fluencia de:

$$ \sigma_Y=250\,MPa $$

Determine:

1. El esfuerzo equivalente de Von Mises.
2. El factor de seguridad.
3. Si el componente falla o no.

<img width="971" height="321" alt="image" src="https://github.com/user-attachments/assets/74035881-4d0a-4926-9e71-b9c2e2bfdfce" />

---

## Solución Problema 8

### Von Mises

$$ \sigma_{VM} = \sqrt{ \sigma_x^2 - \sigma_x\sigma_y + \sigma_y^2 + 3\tau_{xy}^2 } $$

$$ \sigma_{VM} = \sqrt{ 180^2 - 180(50) + 50^2 + 3(75)^2 } $$

$$ \sigma_{VM} = \sqrt{ 42775 } $$

$$ \sigma_{VM} = 206.82\,MPa $$

---

### Factor de seguridad

$$ n= \frac{\sigma_Y}{\sigma_{VM}} $$ 

$$ n= \frac{250}{206.82} = 1.21 $$

---

### Verificación

$$ 206.82<250 $$

No existe fluencia.

---

### Resultados

$$ \boxed{\sigma_{VM}=206.82\,MPa} $$

$$ \boxed{n=1.21} $$

El componente trabaja en condición segura.

---

## Problema 9 — Reconstrucción del círculo de Mohr

### Enunciado

Para un determinado elemento se sabe que los esfuerzos principales son:

$$
\sigma_1=220\,MPa
$$

$$
\sigma_2=-40\,MPa
$$

Determine:

1. Centro del círculo de Mohr.
2. Radio.
3. Esfuerzo cortante máximo.
4. Dibuje esquemáticamente el círculo de Mohr.

<img width="990" height="246" alt="image" src="https://github.com/user-attachments/assets/fdd8800a-9931-47d8-ac79-6bb1612e6cd2" />

---

## Solución Problema 9

### Centro

$$ C= \frac{\sigma_1+\sigma_2}{2} $$

$$ C= \frac{220-40}{2} = 90\,MPa $$

---

### Radio

$$ R= \frac{\sigma_1-\sigma_2}{2} $$

$$ R= \frac{220-(-40)}{2} = 130\,MPa $$

---

### Cortante máximo

$$ \tau_{max}=R $$

$$ \tau_{max} = 130\,MPa $$ 

---

### Resultados

$$ \boxed{C=90\,MPa} $$

$$ \boxed{R=130\,MPa} $$

$$ \boxed{\tau_{max}=130\,MPa} $$

---

## Problema 10 — Eje sometido a carga axial y torsión

### Enunciado

Un eje macizo de acero de diámetro

$$ d=45\,mm $$

está sometido simultáneamente a:

$$ P=150\,kN $$

$$ T=3\,kN\cdot m $$

Considere un límite de fluencia:

$$ \sigma_Y=250\,MPa $$

Determine:

1. Esfuerzo normal.
2. Esfuerzo cortante.
3. Esfuerzos principales.
4. Esfuerzo equivalente de Von Mises.
5. Factor de seguridad.

<img width="986" height="265" alt="image" src="https://github.com/user-attachments/assets/65e1f4fa-e699-498e-b0aa-db7793ea9aa2" />

---

## Solución Problema 10

### Área 

$$ A= \frac{\pi d^2}{4} $$

$$ A= 1590.43\,mm^2 $$

---

### Esfuerzo normal

$$ \sigma= \frac{150000}{1590.43} = 94.31\,MPa $$

---

### Momento polar

$$ J= \frac{\pi d^4}{32} $$

$$ J= 4.03\times10^5\,mm^4 $$

---

### Esfuerzo cortante

Usando:

$$ T=3\times10^6\,N\cdot mm $$

$$ c=22.5\,mm $$

$$ \tau= \frac{Tc}{J} $$

$$ \tau= 167.5\,MPa $$

---

### Esfuerzos principales

$$ C= \frac{94.31}{2} = 47.16\,MPa $$

$$ R= \sqrt{ 47.16^2+ 167.5^2 } = 174.0\,MPa $$

---

$$ \sigma_1= 47.16+174.0 = 221.16\,MPa $$

$$ \sigma_2= 47.16-174.0 =-126.84\,MPa $$

---

### Von Mises

$$ \sigma_{VM} = \sqrt{ 94.31^2+ 3(167.5)^2 } $$ 

$$ \sigma_{VM} = 306.5\,MPa $$ 

---

### Factor de seguridad

$$ n= \frac{250}{306.5} = 0.82 $$ 

---

### Resultados

$$ \boxed{\sigma=94.31\,MPa} $$

$$ \boxed{\tau=167.5\,MPa} $$

$$ \boxed{\sigma_1=221.16\,MPa} $$

$$ \boxed{\sigma_2=-126.84\,MPa} $$

$$ \boxed{\sigma_{VM}=306.5\,MPa} $$

$$ \boxed{n=0.82} $$

El eje falla por fluencia según Von Mises.

---
