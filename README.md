UNIVERSIDAD DE LAS FUERZAS ARMADAS "ESPE"

FUNDAMENTOS DE CIRCUITOS ELÉCTRICOS

TAREA Nº9

CARRERA: ING. EN ELECTRÓNICA Y AUTOMATIZACIÓN

DOCENTE: ING. DARWIN ALULEMA

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

Respuesta

El nuevo circuito tiene como resistencia 49.03kΩ

valor de inductancia de 17.44kH.

31. En la figura 17-67, ¿cuál es el ángulo de fase entre I2 y el voltaje de fuente?

![image](https://user-images.githubusercontent.com/104911658/222805586-909c9466-0eb2-4d68-b156-c933a7629f4e.png)

![image](https://user-images.githubusercontent.com/104911658/222805624-515f67db-0bb3-4110-aed4-826754afc75c.png)

33. Determine la corriente a través de cada componente mostrado en la figura 17-68. Encuentre el voltaje entre las terminales de cada componente.

![image](https://user-images.githubusercontent.com/104911658/222805663-64660f5f-a81f-4a50-9f29-abf5054f8703.png)

![image](https://user-images.githubusercontent.com/104911658/222805687-ac363934-95da-4a6a-9452-81551320fdc2.png)

35. Si el valor de C es de 0.22 µF, ¿cuál es la corriente a través de un resistor de 100 Ω conectado de a a b en la figura 17-69?

![image](https://user-images.githubusercontent.com/104911658/222805751-7b4ab77f-9214-4c5c-b01e-3094d67e3769.png)

Calcular la impedancia del conductor e inductor:

![image](https://user-images.githubusercontent.com/104911658/222805789-27dda3d4-2bbd-4d12-9dca-770f779a3e14.png)

Calcular la resistencia total:

![image](https://user-images.githubusercontent.com/104911658/222805838-90306ddc-269a-43dd-8565-1bdfbb7e7302.png)

![image](https://user-images.githubusercontent.com/104911658/222805864-19d3f5bc-c2a6-4ed5-9340-e1c9d7b3231f.png)

![image](https://user-images.githubusercontent.com/104911658/222805884-a791b76a-ab4c-464b-ae24-d1cc7f54f862.png)

37. Determine las frecuencias resonantes y el voltaje de salida en cada frecuencia mostrada en la figura 17-70.

![image](https://user-images.githubusercontent.com/104911658/222805948-4a819158-4ac2-4483-be47-8ee74a5c4faa.png)

![image](https://user-images.githubusercontent.com/104911658/222805972-95141b07-c9e1-442a-9b04-268c247cf589.png)

![image](https://user-images.githubusercontent.com/104911658/222806006-9085b400-e5ba-48ce-8c2d-7fc2991f14b0.png)

39. En condición de resonancia, XL = 2 kΩ y RW 25Ω en un circuito RLC en paralelo. La frecuencia resonante es de 5 kHz. Determine el ancho de banda.

Para la resolución del problema se tiene las siguientes formulas:

El factor Q:

![image](https://user-images.githubusercontent.com/104911658/222806091-7841c24f-32a2-457f-8dfa-1cdd401c8734.png)

Un valor alto de Q produce un ancho de banda más angosto. Un valor bajo de Q produce un ancho de banda más amplio. En la siguiente ecuación se establece una fórmula para el ancho de banda de un circuito resonante en función de Q:

![image](https://user-images.githubusercontent.com/104911658/222806142-54cc9235-5453-43a5-9c9f-1cf2f97942d0.png)

41. En cierto circuito RLC, la potencia en condición de resonancia es de 2.75 W. ¿Cuál es la potencia a la frecuencia crítica baja?

En condición de resonancia:

![image](https://user-images.githubusercontent.com/104911658/222806234-fd50237f-b022-4922-9c73-4252e623f74f.png)

![image](https://user-images.githubusercontent.com/104911658/222806277-dafcda2b-5a7a-44fd-8082-aad292774f28.png)

43. Cierto circuito resonante en paralelo tiene un factor Q de 50 y un AB de 400 Hz. Si Q se duplica, ¿cuál es el ancho de banda a la misma fr?
En la siguiente ecuación se establece una fórmula para el ancho de banda de un circuito resonante en función de Q:

![image](https://user-images.githubusercontent.com/104911658/222806359-572a7176-f340-439f-be84-32ddf73a2b02.png)

![image](https://user-images.githubusercontent.com/104911658/222806376-5768f8b2-9977-415d-bdf8-fc8776a7f2b0.png)

![image](https://user-images.githubusercontent.com/104911658/222806401-ede7bc4e-616d-4d03-9c7c-623d87fb9237.png)

EJERCICIOS DEL CAPITULO 18

1. En cierto filtro pasabajas, XC = 500 Ω y R = 2.2 kΩ. ¿Cuál es el voltaje de salida (Vsal) cuando la entrada es de 10 V rms?

![image](https://user-images.githubusercontent.com/104911658/222806556-ae92c670-6b27-47d1-a4d3-202f2e0fe6ae.png)

3. Determine el voltaje de salida (Vsal) de cada filtro mostrado en la figura 18-38 a la frecuencia especificada cuando Vent = 10 V

![image](https://user-images.githubusercontent.com/104911658/222806614-88b3e9fb-99aa-419a-8a25-3e567a49c556.png)

![image](https://user-images.githubusercontent.com/104911658/222806746-b5a6e6ab-0d1b-4c71-8579-047e3f43e6df.png)

![image](https://user-images.githubusercontent.com/104911658/222806767-1069b90b-e8b0-4751-9ac2-df5202df4023.png)

5. Para el filtro de la figura 18-39, calcule el valor de C requerido para cada una de las siguientes frecuencias críticas:

![image](https://user-images.githubusercontent.com/104911658/222806809-0984ebde-077a-4174-ac47-72f2317d6d2b.png)

c=1/2πRC

fc2πR=1/C

C= 1/(fc2πR)

Reemplazando valores

(a) 60 Hz

C= 1/(60Hz2π220Ω)

C= 0.000012057 F=12.1 μF

(b) 500 Hz

C= 1/(500Hz2π220Ω)

C= 0.000001447 F=1.45 μF

(c) 1 kHz

C= 1/(1000 Hz2π220Ω)

C= 0.000000723 F=0.72 μF

(d) 5 kHz

C= 1/(5000 Hz2π220Ω)

C= 0.000000145 F=0.145 μF

7. Trace una curva de Bode para cada una de las partes del problema 5.

![image](https://user-images.githubusercontent.com/104911658/222806891-202544bf-9961-4b6b-934f-b85f39cd4448.png)

![image](https://user-images.githubusercontent.com/104911658/222806920-20a0c1fa-c68e-4ea4-8e3d-0602ae548ae1.png)

![image](https://user-images.githubusercontent.com/104911658/222806944-fbc6ec27-0723-4c41-b590-66d38b040189.png)

![image](https://user-images.githubusercontent.com/104911658/222806972-05803352-b500-4d9e-b617-e86ac65f1bbe.png)

9. El voltaje de entrada a un filtro RC pasabajas es de 8 V rms. Determine el voltaje de salida a los siguientes niveles de dB:
20*log⁡(Vsalida/Ventrada)=dB

log⁡(Vsalida/(8 Vrms))=dB/20

Vsalida/(8 Vrms)=e^(dB/20)

Vsalida=8 Vrms* e^(dB/20)

Reemplazando valores

(a) -1 dB

Vsalida=8 Vrms* e^((-1)/20)

Vsalida=7.61 V

(b) -3 dB

Vsalida=8 Vrms* e^((-3)/20)

Vsalida=6.89 V

(c) -6 dB

Vsalida=8 Vrms* e^((-6)/20)

Vsalida=5.92 V

(d) -20 dB

Vsalida=8 Vrms* e^((-20)/20)

Vsalida=2.94 V

11. En un filtro pasaaltas, XC =500 Ω y R =2.2 kΩ. ¿Cuál es el voltaje de salida (Vsal) cuando Vent = 10 V rms?
Vsalida=(R/√(R^2+〖Xc〗^2 ))*Ventrada

Vsalida=(2200/√(2200^2+500^2 ))*10

Vsalida=9.75 Vrms

Desplazamiento de fase

φ=〖tan〗^(-1) (Xc/R)

φ=〖tan〗^(-1) (500/2200)

φ=12.80°

El voltaje

Vsalida=9.75∠12.8° V

13. Determine el voltaje de salida de cada filtro mostrado en la figura 18-41 a la frecuencia especificada cuando Vent = 10 V.

![image](https://user-images.githubusercontent.com/104911658/222807097-2bb1d37c-7a83-45c5-842a-5a9fc8851750.png)

Reactancia capacitiva

Xc=1/(2πfC)

Xc=1/(2π60Hz10μF)=265 Ω

Vsalida=(R/√(R^2+〖Xc〗^2 ))*Ventrada

Vsalida=(100/√(100^2+265^2 ))*10

Vsalida=3.53 Vrms

Desplazamiento de fase

φ=〖tan〗^(-1) (Xc/R)

φ=〖tan〗^(-1) (265/100)

φ=69.33°

El voltaje

Vsalida=3.53∠69.33° V

![image](https://user-images.githubusercontent.com/104911658/222807160-8272b222-07ee-4968-aca7-46e8138bd719.png)

Reactancia capacitiva

Xc=1/(2πfC)

Xc=1/(2π400Hz4.7μF)=84.6 Ω

Vsalida=(R/√(R^2+〖Xc〗^2 ))*Ventrada

Vsalida=(47/√(47^2+〖84.6〗^2 ))*10

Vsalida=4.85 Vrms

Desplazamiento de fase

φ=〖tan〗^(-1) (Xc/R)

φ=〖tan〗^(-1) (84.6/47)

φ=60.95°

El voltaje

Vsalida=4.85∠60.95° V

![image](https://user-images.githubusercontent.com/104911658/222807207-d8f54525-0b15-4a71-b7f1-25dff0323261.png)

Rw=2πf*L

Rw=2π1000 Hz*,005 H=31.42

Vsalida=(R/(R+Rw))*Ventrada

Vsalida=(330/(330+31.42))*10

Vsalida=9.47mVrms

Desplazamiento de fase

φ=〖tan〗^(-1) (Rw/R)

φ=〖tan〗^(-1) (3142/330)

φ=84°

El voltaje

Vsalida=9.4∠84° mV

15. Trace la curva de Bode para cada filtro mostrado en la figura 18-41.

![image](https://user-images.githubusercontent.com/104911658/222807288-b75e0b05-d84b-4ae8-9e6c-ed6dba905d72.png)

17. Determine la frecuencia central para cada filtro de la figura 18-43.

![image](https://user-images.githubusercontent.com/104911658/222807360-6b8c781e-0133-4bc2-aa62-b5d38f78c1ee.png)

fo=√(1-(〖Rw〗^2C/L))/(2π√(LC))

fo=√(1-(0^20.01μF/12mH))/(2π√(12mH0.01μF))

fo=14.5 kHz

![image](https://user-images.githubusercontent.com/104911658/222807396-c46b5dab-b182-4b7d-ae18-a4e71591160b.png)

fo=√(1-(〖Rw〗^2C/L))/(2π√(LC))

fo=√(1-(0^20.022μF/2mH))/(2π√(2mH0.022μF))

fo=24.0 kHz

19. ¿Cuáles son las frecuencias críticas alta y baja para cada filtro de la figura 18-43? Suponga que la respuesta es simétrica con respecto a f0.

![image](https://user-images.githubusercontent.com/104911658/222807474-7f181f58-99ea-4785-92a8-a3f015a68ed9.png)

fc=1/(2π*L/R)

fc=1/(2π*1H/680Ω)

fc=15.06 kHz

fc=1/(2πRC)

fc=1/(2π680Ω10μF)

fc=13.94 kHz

![image](https://user-images.githubusercontent.com/104911658/222807513-2f5aa31b-0243-4e2b-a5b2-4fb319acb48a.png)

fc=1/(2π*L/R)

fc=1/(2π*(2.5 μH)/(1 kΩ))

fc=25.3 kHz

fc=1/(2πRC)

fc=1/(2π1 kΩ25pF)

fc=22.7 kHz

21. Si la resistencia de devanado de las bobinas que aparecen en la figura 18-44 es de 4 Ω, ¿cuál es el voltaje de salida en condición de resonancia cuando Vent = 120 V?

![image](https://user-images.githubusercontent.com/104911658/222807564-ee610205-bb75-4c4d-9b98-7acb944c1077.png)

Vsalida=(R/(R+Rw))*Ventrada

Vsalida=(680/(680+4))*120V

Vsalida=119.29V

![image](https://user-images.githubusercontent.com/104911658/222807607-a277c656-5e7f-4812-8733-529ca11fb03e.png)

Vsalida=(R/(R+Rw))*Ventrada

Vsalida=(1000/(1000+4))*120V

Vsalida=119.52V

23. Diseñe un filtro pasabanda utilizando un circuito resonante paralelo que satisfaga las siguientes especificaciones: AB = 500 Hz; Q = 40; e IC(máx) =20 mA, VC(máx) =2.5 V. Entonces

el valor de la capaitancia es 0.064 uF

La inductancia debe ser de 989 uH

la frecuencia f= 20 kHz

25. Para cada filtro de la figura 18-47, determine la frecuencia central de la banda de rechazo

![image](https://user-images.githubusercontent.com/104911658/222807704-b68c29a1-5690-45f2-83f6-1bfbcf1ab6a9.png)

F0=sqrt(1-R^2*C/L)/2piSqrt(LC)

F0= sqrt(1-1000^26.8/0,5)/2piSqrt(0.56,8)

F0=318Hz

![image](https://user-images.githubusercontent.com/104911658/222807738-2bf2087f-fb12-4561-bcc2-4ef4cffd9600.png)

F0=sqrt(1-R^2*C/L)/2piSqrt(LC)

F0= sqrt(1-2200^247/10)/2piSqrt(1047)

F0=10,21Hz

27. Determine los valores de L1 y L2 en la figura 18-48 para dejar pasar una señal con frecuencia de 1200 kHz y rechazar una señal con frecuencia de 456 kHz.

![image](https://user-images.githubusercontent.com/104911658/222807808-9a0ae6ef-dd11-4ef0-b813-79a60109e536.png)

fo=√(1-(〖Rw〗^2C/L))/(2π√(LC))

Si Rw = 0 ohmios

fo=1/(2π√(L*C))

2πfo=1/√(LC)

√(2πfo)=1/(LC)

L=C/√(2π*fo )

Reemplazando datos

Fo = 1200 kHz

L=(0.22 μF)/√(2π*1200 kHz )

L=0.0025 μH

Fo = 456 kHz

L=(0.22 μF)/√(2π*456 kHz )

L=0.004 μH

VIDEO

https://youtu.be/Sk0PFGV5WDU

CONCLUSIONES

* Como conclusión, un circuito RLC en serie está formado por una resistencia, un inductor y un condensador. Las reactancias inductiva y capacitiva tienen efectos opuestos en el ángulo de fase del circuito, de modo que la reactancia global es menor que las reactancias individuales, pero como la resonancia es una situación en la que las reactancias capacitiva e inductiva son iguales, se anulan mutuamente, dando lugar a una impedancia puramente resistiva.

* Tambien, en un circuito en serie RLC, las tensiones entre los terminales del condensador y los terminales del inductor están siempre separadas 180°. Por lo tanto, VC y VL se restan entre sí, de modo que la suma de las tensiones en L y C es siempre menor que la tensión máxima individual entre los terminales de cualquiera de los componentes.

* Los filtros de pasaaltas permite que fluya señales de alta frecuencia y los filtros de pasabajas permite quefluya las señales de baja frecuencia.

* Los filtros de pasabanda permite que pasen las señales que se encuentran en un determinado intervalo de frecuencia si una frecuencia se pasa del intervalo es eliminada y los filtros de rechazabanda es lo opuesto a los filtros de pasabanda debido a que determina el intervalo de frecuencia donde las frecuencias son rechazadas.

* Dentro de las relaciones de corriente se tiene que en un circuito RLC dispuesto en paralelo, las corrientes que circulan por las ramas capacitiva e inductiva siempre están desfasadas en 180° entre sí (omitiendo cualquier resistencia de bobina).

BIBLIOGRAFÍA

* Floyd, T. (2007). Principios de circuitos eléctricos. PEARSON Educación. https://drive.google.com/file/d/15UCq2JrPEKKB8SwajlmtTcE07nMiowaK/view



