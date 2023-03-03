

Objetivo General

* Conocer sobre los circuitos RCL y resonancia y filtros pasivos mediante la utilización del libro de Floyd "Principios de Circuitos Eléctricos"

Objetivo Específico

* Resumir los capitulos diecisiete y dieciocho del libro de Floyd "Principios de Circuitos Eléctricos", para que de esta forma se pueda comprender de una mejor manera los temas descritos.

* Aplicar los conocimientos adquiridos de circuitos RCL y resonancia y filtros pasivos para la resolcuión de los ejercicos propuestos por el libro de Floyd.

MARCO TEÓRICO

![image](https://user-images.githubusercontent.com/104911658/222803495-48e8dfe2-6067-49dd-92b0-2450226a1a96.png)

![image](https://user-images.githubusercontent.com/104911658/222803644-5c3ca79e-4291-4f72-adf8-1f85858293e2.png)

![image](https://user-images.githubusercontent.com/104911658/222803748-f9b5a046-7708-4500-ac8e-a2fa0d6e03a8.png)

![image](https://user-images.githubusercontent.com/104911658/222803802-ff6ce231-fe2c-4c35-a100-fe879e6a47b2.png)

![image](https://user-images.githubusercontent.com/104911658/222803896-38e435a2-50aa-4cf5-8d38-cceba937581d.png)

EJERCICIOS CAPITULO 17

1. Cierto circuito RLC en serie tiene los siguientes valores: R = 10ohm, C = 0.047uF, y L = 5mH. Determine la impedancia en forma polar. ¿Cuál es la reactancia neta? La frecuencia de la fuente es de 5 kHz.

R = 10 ohm
C = 0.047 uF => 4.7x10^-8 F
L = 5 mH => 0.005 H
f = 5 kHz => 5000 Hz

Xc = 1/2πfC
Xc = 1/2π(5000)(4.7x10^-8)
Xc = 677.255 ohm

XL = 2πfC
XL = 2π(5000)(0.005)
XL = 157.08 ohm

Xtot = |157.08 - 677.255|
Xtot = 520 ohm => Capacitiva

Z = √R^2 + Xtot^2 ∠ tan^-1 (Xtot/R)
Z = √(10)^2 + (250)^2 ∠ tan^-1 (250/10)
Z = 520 ∠ -88.90° ohm

3. Si en la figura 17-59 la frecuencia del voltaje de fuente se duplica a partir del valor que producen las reactancias indicadas, ¿cómo cambia la magnitud de la impedancia?

![image](https://user-images.githubusercontent.com/104911658/222804095-2e8fff60-32a8-4ec2-90c5-adf31b5b6c9e.png)

Xtot = |80 - 35|
Xtot = 45 ohm => Inductivo

Z = √R^2 + Xtot^2 ∠ tan^-1 (Xtot/R)
Z = √(47)^2 + (45)^2 ∠ tan^-1 (45/47)
Z = 65.07 ∠ 43.75° ohm

Respuesta

La impedancia se incrementa a 150 ohm

5. Para el circuito de la figura 17-59, determine Itot, VR, VL y VC en forma polar.

![image](https://user-images.githubusercontent.com/104911658/222804264-71ab46e3-92a6-4281-808d-b9ac667b9322.png)

Z = R + jXL - jXc Z = 47 + j80 -j35 Z = 47 + j45 ohm

Z = √R^2 + Xtot^2 ∠ tan^-1 (Xtot/R)
Z = √(47)^2 + (45)^2 ∠ tan^-1 (45/47)
Z = 65.07 ∠ 43.75° ohm

Itot = Vs/Z
Itot = (4 ∠ 0°)/(65.07 ∠ 43.75°)
Itot = 61.4 ∠ -43.75° mA

VR = IR
VR = (61.4 ∠ -43.75°)(47 ∠ 0°)
VR = 2.89 ∠ -43.75° V

VL = IXL
VL = (61.4 ∠ -43.75°)(80 ∠ 90°)
VL = 4.91 ∠ 46.25° V

Vc = IXc
Vc = (61.4 ∠ -43.75°)(35 ∠ -90°)
VL = 2.15 ∠ -134° V

7. Analice el circuito de la figura 17-60 para determinar lo siguiente (f = 25 kHz):

(a) Itot (b) Preal (c) Pr (d) Pa

![image](https://user-images.githubusercontent.com/104911658/222804355-dff1cba4-4e70-42fa-8685-796ca52978b4.png)

1/R = 1/220 + 1/390
RT = 140.656 ohm

LT = 0.5 + 1
LT = 1.5 mH => 0.0015 H

CT = 10000 + 1800
CT = 11800 pF => 1.18x10^-8 F

f = 25 kHz => 25000 Hz

Xc = 1/2πfC
Xc = 1/2π(25000)(1.18x10^-8)
Xc = 539.51 ohm

XL = 2πfC
XL = 2π(25000)(0.0015)
XL = 235.62 ohm

Xtot = |235.62 - 539.51|
Xtot = 303.9 ohm => Capacitiva

Z = √R^2 + Xtot^2 ∠ tan^-1 (Xtot/R)
Z = √(140.656)^2 + (303.9)^2 ∠ tan^-1 (303.9/140.656)
Z = 334.87 ∠ -65.2° ohm

Itot = Vs/Z
Itot = (12 ∠ 0°)/(334.87 ∠ -65.2°)
Itot = 35.8 ∠ 65.2° mA

Preal = I^2R
Preal = 181 mW

Pr = I^2 Xc
Pr = 390 mVAR

Pa = I^2 Z
Pa = 430 mVA

9. Para el circuito de la figura 17-61, ¿cuál es el voltaje a través de R en condición de resonancia?

![image](https://user-images.githubusercontent.com/104911658/222804474-bd280d23-a9cb-4bf5-bc31-44246cedef7c.png)

I = Vs/R
I = 12/22
I = 0.54 A

VR = IR
VR = (0.5454)(22)
VR = 12 V

11. Cierto circuito resonante dispuesto en serie tiene una corriente mínima de 50 mA y un VL de 100 V. El voltaje aplicado es de 10 V. ¿Cuál es el valor de Z? ¿Cuáles los valores de XL y XC?
I = 0.05 A
VL = 100 V
Vs = 10 V

VL = IXL
10 = 0.05(XL)
XL = 100/0.05
XL = Xc = 2000 ohm

I = Vs/Z
0.05 = 10/Z
Z = 200 ohm

13. Para la figura 17-62, ¿cuál es el valor de la corriente en los puntos de potencia media?

![image](https://user-images.githubusercontent.com/104911658/222804567-3500acdd-406e-4150-a260-c6673b5a2722.png)

I = Vs/R
I = 7.07/10
I = 707 mA

15. Diseñe un circuito en el cual las siguientes frecuencias resonantes en serie se puedan seleccionar con un conmutador:

(a) 500 kHz (b) 1000 kHz (c) 1500 kHz (d) 2000 kHz

![image](https://user-images.githubusercontent.com/104911658/222804649-d7610e57-a01e-4cb2-a792-a8b9535c3438.png)

17. ¿Es capacitivo o inductivo el circuito de la figura 17-63? Explique su respuesta.

![image](https://user-images.githubusercontent.com/104911658/222804712-eb67ac64-10b6-419d-af42-8a6425012481.png)

L = 15 mH => 0.015 H
C = 0.022 uF => 2.2x10^-8
f = 12000 Hz

Xc = 1/2πfC
Xc = 1/2π(12000)(2.2x10^-8)
Xc = 602.86 ohm

XL = 2πfC
XL = 2π(12000)(0.015)
XL = 1130.97 ohm

G = 1/(R ∠ 0°) G = 1/(5 ∠ 0°) G = 200 ∠ 0° uS

Bc = 1/(Xc ∠ -90°) Bc = 1/(602.86 ∠ -90°) Bc = 1.66 ∠ 90° uS

BL = 1/(XL ∠ 90°) BL = 1/(1130.97 ∠ 90°) BL = 0.884 ∠ -90° uS

Ytot = G + jBc - jBL Ytot = 200 + j1.66 - j0.884 Ytot = 200 uS - j0.776

Ytot = √G^2 + Btot^2 ∠ tan^-1 (Btot/G)
Ytot = √(200)^2 + (0.776)^2 ∠ tan^-1 (0.776/200)
Ytot = 200 ∠ -4.43° uS

El ángulo de fase de -4.43° indica un circuito levemente capacitivo.

19. Para el circuito de la figura 17-63, determine todas las corrientes y los voltajes en forma polar

![image](https://user-images.githubusercontent.com/104911658/222804827-2b343cac-65d4-46c5-bbfc-69ad4e23ca67.png)

L = 15 mH => 0.015 H
C = 0.022 uF => 2.2x10^-8
f = 12000 Hz

Xc = 1/2πfC
Xc = 1/2π(12000)(2.2x10^-8)
Xc = 602.86 ohm

XL = 2πfC
XL = 2π(12000)(0.015)
XL = 1130.97 ohm

VR = VL = Vc = 5 ∠ 0°

IR = Vs/R
IR = (5 ∠ 0°)/(100 ∠ 0°)
IR = 50 ∠ 0° mA

Ic = Vs/Xc
Ic = (5 ∠ 0°)/(602.86 ∠ -90°)
Ic = 8.29 ∠ 90° mA

IL = Vs/XL
IL = (5 ∠ 0°)/(1130.97 ∠ 90°)
IL = 4.42 ∠ 90° mA

Itot = IR + Ic + IL
Itot = 50 + j8.29 - j4.42
Itot = 50 mA + j3.87 mA

Itot = √IR^2 + (Ic - IL)^2 ∠ tan^-1 (IcL/IR)
Itot = √50^2 + (3.87)^2 ∠ tan^-1 (3.87/50)
Itot = 50.15 ∠ 4.43° mA

21. Cambie la frecuencia a 100 kHz en la figura 17-63 y repita el problema 19.

![image](https://user-images.githubusercontent.com/104911658/222804898-8d8ec4bc-f41c-4876-a561-fddc5cdcc753.png)

L = 15 mH => 0.015 H
C = 0.022 uF => 2.2x10^-8
f = 1000000 Hz

Xc = 1/2πfC
Xc = 1/2π(100000)(2.2x10^-8)
Xc = 72.34 ohm

XL = 2πfC
XL = 2π(100000)(0.015)
XL = 9424.78 ohm

VR = VL = Vc = 5 ∠ 0°

IR = Vs/R
IR = (5 ∠ 0°)/(100 ∠ 0°)
IR = 50 ∠ 0° mA

Ic = Vs/Xc
Ic = (5 ∠ 0°)/(72.34 ∠ -90°)
Ic = 69.11 ∠ 90° mA

IL = Vs/XL
IL = (5 ∠ 0°)/(9424.78 ∠ 90°)
IL = 0.53 ∠ 90° mA

Itot = IR + Ic + IL
Itot = 50 + j69.11 - j0.53
Itot = 50 mA + j68.58 mA

Itot = √IR^2 + (Ic - IL)^2 ∠ tan^-1 (IcL/IR)
Itot = √50^2 + (68.58)^2 ∠ tan^-1 (68.58/50)
Itot = 84.9 ∠ 53.9° mA

23. Determine Z en condición de resonancia y fr para el circuito tanque de la figura 17-64.

![image](https://user-images.githubusercontent.com/104911658/222804970-fa57af67-9b14-4b32-b794-56f66c4a535f.png)

R = 20 ohm
L = 50 mH => 0.05 H
C = 47 pF => 4.7x10^-11

fr = (√1 - Rw^2C/L)/2π√LC
fr = (√1 - (20)^2(4.7x10-11)/(0.05))/2π√(4.7x10-11)(0.05)
fr = 103821.21 Hz
fr = 104 kHz
Z = 53.5 Mohm

25. Determine Preal, Pr y Pa en el circuito de la figura 17-64 en condición de resonancia.

![image](https://user-images.githubusercontent.com/104911658/222805111-023358a3-0a17-413b-8d6e-8fafc12c4d14.png)

![image](https://user-images.githubusercontent.com/104911658/222805137-70d46f46-48c1-4ff3-9322-dbad795c5546.png)

27. Para cada circuito de la figura 17-65, determine el ángulo de fase entre el voltaje de fuente y la corriente total.

![image](https://user-images.githubusercontent.com/104911658/222805205-d3128bf0-7c43-4460-b8a1-65c0a5f08616.png)

para el circuito a:

![image](https://user-images.githubusercontent.com/104911658/222805274-1c12c73b-1b21-4431-8837-0d4f0187c98a.png)

para el circuito b:

![image](https://user-images.githubusercontent.com/104911658/222805356-ae521392-4994-4795-8974-498d27709cf2.png)

29. Convierta el circuito de la figura 17-66 a una forma equivalente dispuesta en serie.

![image](https://user-images.githubusercontent.com/104911658/222805462-643695eb-7785-46e3-a286-b424f9111425.png)

![image](https://user-images.githubusercontent.com/104911658/222805482-be686f73-008f-41ac-baa8-a1707feb0366.png)




