# Theorie der Mathematik Matura

[TOC]

## Einheiten umrechnen

Ist in der Formelsammlung zu finden:

![image-20200510210452459](C:\Users\Stefan\AppData\Roaming\Typora\typora-user-images\image-20200510210452459.png)

**Beispiele:**

cm in km:	  /10^5
MW in GW:	/10^3
hl in dl:		  *10^3
dm in um:	 *10^5

cm^2 in km^2:	/(10^5)^2
mm^3 in dm^3:  /(10^2)^3
km^2 in m^2: 	*(10^3)^2

### Weitere Umrechnungen:

km/h in m/s:	*3.6
m/s in km/h:	/3.6

1 Liter = 1 dm^3
1 ml = 1 cm^3
1 cl = 10 cm^3

## Prozent rechnen

p Prozent eines Wertes x berechnen:
$$
x*\frac{p}{100}
$$
p Prozent zu einem Wert x hinzufügen:
$$
x*(1+\frac{p}{100})
$$
p Prozent von einem Wert x abziehen:
$$
x*(1-\frac{p}{100})
$$
Prozentuellen Anteil an der Gesamtheit berechnen:
$$
\frac{Anteil}{Gesamtheit}
$$
Prozentuelle Veränderung zwischen einem neuen und einem alten Wert berechnen:
$$
\frac{Neu-Alt}{Alt}
$$

## Trigonometrie im rechtwinkligen Dreieck

$$
k = \frac{p}{100} => \frac{Gegenkathete}{Ankathete} = tan(\alpha)
$$

Steigungswinkel gegeben => Wir wollen die Steigung wissen => tan(a)
Steigungswinkel berechnen:
$$
\alpha = arctan(k) = arctan(\frac{p}{100})
$$
Unterschied Höhenwinkel, Tiefenwinkel:

<img src="C:\Users\Stefan\AppData\Roaming\Typora\typora-user-images\image-20200512102410435.png" alt="image-20200512102410435" style="zoom:50%;" />

## Vektoren in R2

**Skalarprodukt**: Wenn das Ergebnis gleich 0 ist, wissen wir, dass die beiden Vektoren normal aufeinander stehen, also ein rechter Winkel zwischen den beiden Vektoren existiert.

Wenn das Ergebnis nicht 0 ist, stehen die beiden Vektoren nicht normal aufeinander (also gibt es keinen rechten Winkel).

## Änderungsmaße

Differenzenquotient: Sekante (durchschnittliche Steigung zwischen 2 Punkten)
Differenzialquotient: Tangente (momentane Steigung eines Punktes)

<img src="C:\Users\Stefan\AppData\Roaming\Typora\typora-user-images\image-20200512110306411.png" alt="image-20200512110306411" style="zoom:33%;" />

Hier nochmal zur Erklärung:
Tangente: Berührt den Graphen nur an einem Punkt
Sekante: Schneidet den Graphen in zwei Punkten
Passante: Weder berührt noch schneidet den Graphen

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/58/SekTangPass.svg/1920px-SekTangPass.svg.png" alt="img" style="zoom:33%;" />

## Quadratische Funktion

$$
f(x) = a*x^2+b*x+c
$$

<img src="C:\Users\Stefan\AppData\Roaming\Typora\typora-user-images\image-20200512133150834.png" alt="image-20200512133150834" style="zoom:33%;" />

Diskriminante: Wie viele Lösungen kann eine quadratische Gleichung haben?

<img src="C:\Users\Stefan\AppData\Roaming\Typora\typora-user-images\image-20200512133952975.png" alt="image-20200512133952975" style="zoom:33%;" />

<img src="C:\Users\Stefan\AppData\Roaming\Typora\typora-user-images\image-20200512134228154.png" alt="image-20200512134228154" style="zoom:33%;" />

## Polynomfunktion

Der Grad einer Polynomfunktion gibt an, wie viele reele Lösungen dieser Funktion maximal haben kann.

Polynomfunktionen geraden Grades können auch gar keine reele Lösung besitzen.

Polynomfunktionen ungeraden Grades müssen mind. eine reele Lösung haben.



![image-20200512134413619](C:\Users\Stefan\AppData\Roaming\Typora\typora-user-images\image-20200512134413619.png)

Bedeutet:

<img src="C:\Users\Stefan\AppData\Roaming\Typora\typora-user-images\image-20200512134926045.png" alt="image-20200512134926045" style="zoom: 50%;" />

Extremstellen berechnen: Erste Ableitung 0 setzen.
Wendestellen berechnen: Zweite Ableitung 0 setzen.

## Differentialrechnung

<img src="C:\Users\Stefan\AppData\Roaming\Typora\typora-user-images\image-20200512135733604.png" alt="image-20200512135733604" style="zoom: 33%;" />

F(x) ist die Stammfunktion von f(x)
f(x) ist die Stammfunktion von f'(x)
f'(x) ist die Stammfunktion von f''(x)

<img src="C:\Users\Stefan\AppData\Roaming\Typora\typora-user-images\image-20200512140647825.png" alt="image-20200512140647825" style="zoom: 33%;" />

Bei der ersten Ableitung werden:

- Extremwerte und Sattelpunkte zu einer Nullstelle
- Wendestelle werden zu Extremwerten (Steigungen, wo ist die größte bzw. kleinste Steigung)
- Wenn f(x) steigend ist, ist f'(x) oberhalb der x-Achse
- Wenn f(x) fallend ist, ist f'(x) unterhalb der x-Achse
- Sobald f(x) negativ gekrümmt ist, muss f'(x) fallend sein
- Sobald f(x) positiv gekrümmt ist, muss f'(x) steigend sein

<img src="C:\Users\Stefan\AppData\Roaming\Typora\typora-user-images\image-20200512141141420.png" alt="image-20200512141141420" style="zoom:33%;" />

Bei der zweiten Ableitung werden:

- Wendestellen und Sattelpunkte zu einer Nullstelle
- Wenn f(x) positiv gekrümmt ist, ist f''(x) oberhalb der x-Achse
- Wenn f(x)  negativ gekrümmt ist, ist f''(x) unterhalb der x-Achse

Nullstellen berechnen: f(x) = 0

Extremstellen berechnen: 

- f'(x) = 0 => xE
- f''(xE) < 0 => Höchstpunkt (Maximum)
- f''(xE) = 0 => Sattelpunkt
- f''(xE) > 0 => Tiefpunkt (Minimum)

Wendestellen berechnen: f''(x) = 0

Steigungswinkel berechnen: alpha = arctan(f'(x))

## Integralrechnung

<img src="C:\Users\Stefan\AppData\Roaming\Typora\typora-user-images\image-20200512204905106.png" alt="image-20200512204905106" style="zoom:33%;" />
$$
\int_a^b f(x),\mathrm{d}x > 0
$$

$$
\int_b^c f(x),\mathrm{d}x < 0
$$

Immer von Nullstelle zu Nullstelle integrieren (und wenn der Graph negativ ist, dann in Betrag setzen)
$$
A = \int_a^b f(x),\mathrm{d}x-{\int_b^c f(x),\mathrm{d}x}
$$
<img src="C:\Users\Stefan\AppData\Roaming\Typora\typora-user-images\image-20200512205723673.png" alt="image-20200512205723673" style="zoom: 50%;" />
$$
A = \int_a^b (f(x)-g(x)),\mathrm{d}x+{\int_b^c (g(x)-f(x)),\mathrm{d}x}
$$
<img src="C:\Users\Stefan\AppData\Roaming\Typora\typora-user-images\image-20200512210044573.png" alt="image-20200512210044573" style="zoom:50%;" />
$$
A = \int_a^d f(x),\mathrm{d}x+{\int_b^c g(x),\mathrm{d}x}
$$


## Lineare Funktion

### Tangentengleichung ausrechnen:

In der Angabe steht eine Funktion und diese soll in t=0 eine Tangente ausrechnen:
Tangentengleichung => y=k*x+d

d: f(0) => geht mit subst
k: f'(0) => geht mit subst

### Interpolation Definition:

Darunter versteht man die Berechnung eines zusätzlichen Wertes im Bereich der vorhandenen Daten.

### Extrapolation Definition:

Darunter versteht man die Prognose für einen Wert, der außerhalb des vorhandenen Datenbereichs liegt.

### Methode der kleinsten Quadrate Definition:



### Lineare Funktion aus 2 Punkten berechnen

Lineare Funktion: y=k*x+d
P1(36.5|2)
P2(5|41)

gl1: 2 = k\*36.5+d
gl2: 41 = k\*5+d
\-------------------
solve([gl1,gl2]) => Werte für k und d

### Steigungswinkel berechnen

1) Erste Ableitung: f'(x)
2) Vom Ergebnis den arctan nehmen (in Maxima: atan)
3) Ergebnis * (180/%pi)



## Bewegungsaufgaben

SVA => s(t) (Weg/Strecke), v(t) (Geschwindigkeit), a(t) (Beschleunigung)

s(t) = integrate(v(t)) = integrate(integrate(a(t)))
s'(t) = v(t) = integrate(a(t))
s''(t) = v'(t) = a(t)

s = v*t => v = s/t

Durchschnittsgeschwindigkeit (Differenzenquotient der Wegfunktion):
$$
\bar{v}=\frac{s(t_{2})-s(t_{1})}{t_{2}-t_{1}}
$$
Durchschnittsbeschleunigung (Differenzenquotient der Geschwindigkeitsfunktion):
$$
\bar{a}=\frac{v(t_{2})-v(t_{1})}{t_{2}-t_{1}}
$$
Zurückgelegten Weg in einem bestimmten Zeitintervall:
$$
s = {\int_{t_{1}}^{t_{2}} v(t),\mathrm{d}t}
$$

## Normalverteilung

https://matheguru.com/stochastik/normalverteilung.html

![image-20200513095830953](C:\Users\Stefan\AppData\Roaming\Typora\typora-user-images\image-20200513095830953.png)