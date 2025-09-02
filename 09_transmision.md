---
title: "9. Transmisión de potencia"
autor: "José Juarez"
version: "05/08/25"
---

<span hidden>Local path of the file: "H:/cfr/mec3/"</span>
<span hidden>Local path of images: "H:/cfr/mec3/_i/"</span>

<span hidden>Image</span>
   <center>![](https://brr.mx/wp-content/uploads/2022/10/10-tips-en-transmision-de-potencia.jpg){width=400px}</center>
   <center><span class="grey3 size70">Las ruedas dentadas (engranajes) son muy usadas en la transmisión de potencia - Fuente: brr.mx</span></center>

<br><br>


## ¿Qué es la transmisión?

La **transmisión** es el conjunto de elementos mecánicos que **transfieren el movimiento** del motor a las ruedas.

- El motor gira rápido, pero con poca fuerza.
- Las ruedas necesitan girar más lento, pero con mucha fuerza.

Entonces la transmisión:

* **Reduce la velocidad de giro**.
* **Aumenta el torque (fuerza)**.
* **Permite cambiar de marcha** según la necesidad (arranque, subida, velocidad, etc.).


<br><br>


## Componentes principales de la transmisión

Vamos a explicar los principales elementos que la componen:

| Componente                        | Función                                                                              |
| --------------------------------- | ------------------------------------------------------------------------------------ |
| **Motor**                         | Genera el movimiento (gira a altas RPM).                                             |
| **Embrague**                      | Conecta y desconecta el motor de la caja de cambios. Permite arrancar sin sacudidas. |
| **Caja de cambios**               | Modifica la relación entre velocidad y fuerza (conjunto de engranajes).              |
| **Árbol de transmisión / cardán** | Transmite el movimiento a los ejes de las ruedas, sobre todo en vehículos largos.                  |
| **Diferencial**                   | Permite que las ruedas giren a distinta velocidad (en curvas).                       |
| **Ejes y ruedas**                 | Reciben el torque y se mueven.                                                       |
<br><br>

## Actividad 1 

(Supuestamente hecha en clase)

Dibuja un esquema de la transmisión de un tractor u otro vehículo y pon nombre a las partes. Te puede servir de orientación el dibujo de abajo.

Debes señalar en el dibujo:

1. Motor
2. Embrague
3. Caja de cambios
4. Árbol de transmisión
5. Diferencial
6. Ruedas

<span hidden>Image</span>
   <center>![](https://agrodesguaces.com/img/cms/esquematractor%20(1).JPG){width=400px}</center>
   <center><span class="grey3 size70">Fuente: agrodesguaces.com</span></center>

<br><br>

## Relación de Transmisión: principio de reducción

<span hidden>Image</span>
   <center>![](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjBBwlG1hmvm1woiAoxaJILpCMtKLZmOUxMXVf6xmRW9Iin8sv5Vr6W7UeROjiT_IpnRo_3kcxsMKH9NLmGm2-t9inzPZy29m7hu777UiHmkCI3CgzCjKMcmUht9bi0K_fSyAOMSeh77Ck/s320/Sin+t%25C3%25ADtulo10.jpg){width=400px}</center>
   <center><span class="grey3 size70">Fuente: agrodesguaces.com</span></center>

### ¿Qué es la relación de transmisión?

Es cuánto gira un engranaje respecto a otro.
Se la suele nombrar con la letra **"i"** y se calcula como:

$$
\text{Relación de Transmisión (i)} = \frac{\text{número de dientes del engranaje conducido (Z2)}}{\text{número de dientes del engranaje conductor (Z1)}}
$$

### Ejemplo de reducción simple

Para averiguar la relación de transmisión en:

* Engranaje A (conductor): Z1 = 20 dientes
* Engranaje B (conducido): Z2 = 60 dientes

hay que aplicar: 

$i = \frac{60}{20} = 3$

Y significa que:

* El engranaje B gira **3 veces más lento** que el A.
* Pero con **3 veces más fuerza (torque)**.

<br><br>

## Otro modo de calcular la relación de transmisión **"i"**

En vez de usar las cantidades de dientes se puede usar las velocidades (rpm) en los distintos ejes (conductor y conducido). Las velocidades se suelen nombrar con la letra **"n"**: 

$$
\text{Relación de Transmisión (i)} = \frac{\text{Velocidad del eje conductor (n1)}}{\text{Velocidad del eje conducido (n2)}}
$$

### Importante:

* **Eje conductor (n1)**: el que transmite el movimiento (por ejemplo, el motor).
* **Eje conducido (n2)**: el que recibe el movimiento (por ejemplo, las ruedas).

<br><br>

## Actividad 2

Aplica una fórmula adecuada para calcular la relación de transmisión suponiendo que:

* El motor (eje conductor) gira a **2400 RPM**.
* El eje de salida de la caja de cambios (eje conducido) gira a **600 RPM**.

<br><br>

## Actividad 3

Suponga que en un tractor:

* El motor gira a 2400 RPM.
* La caja reduce con una relación de 1:4 en primera. Quiere decir que reduce 4 veces la velocidad y que **i = 4**. 

¿A que velocidad en rpm gira la rueda?

<div hidden>
$n2 = \frac{2400}{4} = 600 \text{ rpm}$

Entonces, a la salida de la caja, el eje gira a 600 RPM, pero con mucho más torque, ideal para **trabajar con carga o en el campo**.
</div>


<br><br>


## Actividad 4

Resolver los siguientes ejercicios

Puede servirte este [video](https://www.youtube.com/watch?v=QpF2JPwRkI8) u otro que tu busques para repasar este tema.

* **1)** Dados dos engranajes donde Z1 = 20 y Z2 = 60, calcular la relación de transmisión.

* **2)** Si el motor gira a 3000 RPM y hay una reducción 3:1, ¿a cuántas RPM gira el eje de las ruedas?

<div hidden>
  $$
  \frac{3000}{3} = 1000, \quad \frac{1000}{2} = 500 \text{ RPM}
  $$
</div>

* **3)** Contesta brevemente esta pregunta: ¿Por qué no se conecta el motor directamente a las ruedas?


<br><br>


**(En el aula)**

## Actividad 5

Suponga que en un tractor:

* El motor gira a 3500 RPM.
* La caja reduce con una relación de 1:3 en primera. 

¿A que velocidad en rpm gira la rueda?


<br><br>


## Actividad 6

Busque información y trate de dibujar esquemáticamente un diferencial. Escriba en pocos renglones para que sirve.


<br><br>


<div class="grey3 size70">

---

**Algunas soluciones para autocorregirte**

### Actividad 2

$\text{Relación de Transmisión (i)} = \frac{\text{n1}}{\text{n2}} = \frac{2400 rpm}{600rpm}$ = **4**

### Actividad 3

Como $\text{Relación de Transmisión (i)} = \frac{\text{n1}}{\text{n2}}$

Queda: $4 = \frac{2400rpm}{n2}$

Despejando x queda: $n2 = \frac{2400rpm}{4}$ **=600 rpm**

Entonces, a la salida de la caja, el eje gira a 600 RPM, pero con mucho más torque, ideal para **trabajar con carga o en el campo**.


<!-- HTML style definitions -->
<style>
/* Colors */
.grey1 {color: #b3b3b3;} /* my light-grey */
.grey2 {color: #999999;} /* my middle-grey */
.grey3 {color: #808080;} /* my dark-grey */
.blue1 {color: #6495ed;} /* nvim blue */
.blue2 {color: #276cdf;} /* Andrew Ng Blue */
.sky1 {color: #7dbed8;} /* nvim sky */
.sky2 {color: #27a2db;}   /* my sky */
.green {color: #81b524;} /* my green */
.red1 {color: #ec5469;} /* my coral-red */
.red2 {color: #f44336;} /* my red */
.rose {color: #ec9998:} /* nvim rose */
.gold {color: #df9d43;} /* Andrew Ng gold */
.orange1 {color: #fda556;} /* nvim orange */
.orange2 {color: #ff9505;} /*Andrew Ng orange */
.purple1 {color: #ff40ff;} /* Andrew Ng purple */
.purple2 {color: #d164d7;} /* Andrew Ng purple */
/* Font Size */
.size90 {font-size: 0.9em;}
.size85 {font-size: 0.85em;}
.size80 {font-size: 0.8em;}
.size70 {font-size: 0.7em;}
/* Document General Font Size */
body {font-size: 1.3em;}
</style>
<!-- Use <span> inline and <div> with several lines --->
