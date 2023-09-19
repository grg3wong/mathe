---
{"dg-publish":true,"permalink":"/6. Klasse/Beschreibende Statistik, Wahrscheinlichkeit/Streuungsmaße, empirische Varianz und Standardabweichung/"}
---

#S605 #S6 #6kl
Ich kenne Streuungsmaße, empirische Varianz und empirische Standardabweichung und kann diese anwenden.

siehe auch:
___

|empirische Varianz | $s²=\frac{(x_1-\bar{x})^2+(x_2-\bar{x})^2+...+(x_n-\bar{x})^2}{n}= \frac{1}{n}\sum_\limits{i=1}^{n}(x_i-\bar{x})^2$ |
|---|---|
|empirische Standardabweichung | $s=\sqrt{\frac{(x_1-\bar{x})^2+(x_2-\bar{x})^2+...+(x_n-\bar{x})^2}{n}}$ |
|Verschiebungssatz für emp. Var.|$s²=\frac{x_1^2+x_2^2+...+x_n^2}{n}-\bar{x}²=\frac{1}{n} \cdot \sum_\limits{i=1}^{n}x_i^2-\bar{x}²$|

## Geogebra
1. Daten in Tabellenansicht übereinander eingeben (Punkt als Dezimaltrennzeichen)
2. Daten markieren, Rechtsklick, Erzeuge Liste
3. Befehle
	1. Mittelwert: ```Mittel(Datenliste)```
	2. Standardabweichung: ```stdevp(Datenliste)```
## Datenveränderungen
2 Listen:
- $x_1, x_2,..., x_n$ mit [arithm. Mittel](Zentralmaße (arithmetisches Mittel, Modus, Median)#arithmetisches Mittel) $\bar{x}$ und emp. Stabw. $s_x$
- $y_1, y_2,..., y_n$ mit  [arithm. Mittel](Zentralmaße (arithmetisches Mittel, Modus, Median)#arithmetisches Mittel)  $\bar{y}$ und emp. Stabw. $s_y$
### Verschiebung um c
Ist $y_i=x_i+c$ für alle i=1,...,n, dann ist $\bar{y} =\bar{x}+c$ und $s_y=s_x$.
![Pasted image 20230912093324.png|150](/img/user/0%20Meta/Bilder/Pasted%20image%2020230912093324.png)
### Vielfaches von c
Ist $y_i=c\cdot x_i$ für alle i=1,...,n, dann ist $\bar{y} =c\cdot \bar{x}$ und $s_y=c \cdot s_x$.
![Pasted image 20230912093353.png|150](/img/user/0%20Meta/Bilder/Pasted%20image%2020230912093353.png)
