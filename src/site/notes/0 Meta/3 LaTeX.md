---
{"dg-publish":true,"permalink":"/0-meta/3-la-te-x/","dg-note-properties":{}}
---

[Wikipedia: Liste mathematischer Symbole](https://de.wikipedia.org/wiki/Liste_mathematischer_Symbole)
[MathJax: LaTeX Basic Tutorial](https://www.mathelounge.de/509545/mathjax-latex-basic-tutorial-und-referenz-deutsch)

Das Rendern von Zeichen kann man mit dem Backslash \\ verhindern:
```\ \$ \{ \_```
# Gleichung
a²+b² = c² ist reiner Text
~~~
$a²+b² = c²$
~~~
$$a²+b² = c²$$
# Potenzen
~~~
$x^4=1$
~~~
$$x^4=1$$
~~~
$x^m \cdot x^n =x^{m+n}$
~~~
$$x^m \cdot x^n =x^{m+n}$$
~~~
$x^{1/2} \cdot x^{1/2} =x^{1}$
~~~
$$x^{1/2} \cdot x^{1/2} =x^{1}$$

Quadratwurzel = ==sq==uare==r==oo==t==
~~~
$\sqrt{x} \cdot \sqrt{x} = x$
~~~
$$\sqrt{x} \cdot \sqrt{x} = x$$

Grad der Wurzel in der eckigen Klammer
~~~
$\sqrt[3]{8}=?$
~~~
$$\sqrt[3]{8}=?$$
# Brüche
==frac==tions
==`$\frac{Zähler}{Nenner}$`==
$$\frac{a}{b}:\frac{c}{d}=\frac{a \cdot d}{b \cdot c}$$
# Vektoren
## Vektoren als Array 
~~~
$\vec{v}=\begin{pmatrix}
-4 \\-3\\5\end{pmatrix}$
~~~
$$\vec{v}=\begin{pmatrix}-4 \\-3\\5\end{pmatrix}$$
## Vektoren als Array 
~~~
$\vec{v} = \left(\begin{array}{c} -4 \\ 3 \end{array}\right)$
~~~
$$\vec{v} = \left(\begin{array}{c} -4 \\ 3 \end{array}\right)$$
## Kreuzprodukt
~~~
$\times \otimes$
~~~
$$\times \otimes$$

# Summen
Summe der ersten 10 natürlichen Zahlen
~~~
$\sum_\limits{i=1}^{10}i$
~~~
$$\sum_\limits{i=1}^{10}i=1+2+3+...+9+10$$
==`i = \frac{n \cdot (n+1)}{2}$`==
$$\sum_\limits{i=1}^{n} i = \frac{n \cdot (n+1)}{2}$$
# Systeme
Leerzeichen mit Backslash vor dem Leerzeichen sichtbarmachen
~~~
$$|a| = \begin{cases}
    +a       & \text{ falls } a > 0 \\
    \ \ \ 0  & \text{ falls } a = 0 \\
    -a       & \text{ falls } a < 0
\end{cases}$$
~~~~
$$|a| = \begin{cases}
    +a     & \text{ falls } a > 0 \\
    \ \ 0  & \text{ falls } a = 0 \\
    -a     & \text{ falls } a < 0
\end{cases}$$

~~~
$$\begin{equation} \begin{aligned} 
2x_1 + 5x_2 - 13x_3 &= 1000 \\ 
3x_1 - 9x_2 + 3x_3 &= 0 \\ 
-5x_1 + 6x_2 + 8x_3 &= -600 
\end{aligned} \end{equation}$$
~~~
$$\begin{equation} \begin{aligned} 
2x_1 + 5x_2 - 13x_3 &= 1000 \\ 
3x_1 - 9x_2 + 3x_3 &= 0 \\ 
-5x_1 + 6x_2 + 8x_3 &= -600 
\end{aligned} \end{equation}$$
~~~
$$ \begin{array}{rcrcrcr} 
2x_1 & + & 5x_2 & - & 13x_3 & = & 1000 \\ 
3x_1 & - & 9x_2 & + & 3x_3 & = & 0 \\ 
-5x_1 & + & 6x_2 & + & 8x_3 & = & -600 
\end{array} $$
~~~
Spaltendefinition {rcrcrcr}: Das r (rechtsbündig) sorgt dafür, dass die Zahlen direkt an den Variablen kleben, während c (zentriert) die Rechenzeichen (+, -, =) sauber mittig ausrichtet.
$$ \begin{array}{rcrcrcr} 
2x_1 & + & 5x_2 & - & 13x_3 & = & 1000 \\ 
3x_1 & - & 9x_2 & + & 3x_3 & = & 0 \\ 
-5x_1 & + & 6x_2 & + & 8x_3 & = & -600 
\end{array} $$
$$\begin{align*}
    \begin{array}{lcr}
        \text{Erste Zahl}   & x         &  8 \\
        \text{Zweite Zahl}  & y         & 15 \\ \hline
        \text{Summe}        & x + y     & 23 \\
        \text{Differenz}    & x - y     & -7 \\
        \text{Produkt}      & x \cdot y & 120
    \end{array}
\end{align*}$$
```$$\begin{align*}
    \begin{array}{lcr}
        \text{Erste Zahl}   & x         &  8 \\
        \text{Zweite Zahl}  & y         & 15 \\ \hline
        \text{Summe}        & x + y     & 23 \\
        \text{Differenz}    & x - y     & -7 \\
        \text{Produkt}      & x \cdot y & 120
    \end{array}
\end{align*}$$
```

# Über- & Unterstreichungen
 
  ```$a^b+c_d, \dot{e}$```$$a^b+c_d, \dot{e}$$
~~~
$\hat{f}, \tilde{g}, \widehat{hij}, \bar{k}, \overline{lmn}, \vec{o}, \overrightarrow{vw}$
~~~

  $$\hat{f}, \tilde{g}, \widehat{hij}, \bar{k}, \overline{lmn}, \vec{o}, \overrightarrow{vw}$$
  ~~~
$\underbrace {x_1 + x_2}_{7} + \cdots +  \overbrace {x_{n -1} + x_n }^{7}$
  ~~~
$$\underbrace {x_1 + x_2}_{7} + \cdots +  \overbrace {x_{n -1} + x_n }^{7}$$
## Underset
```$E \underset{Einstein}{=} m \cdot c^2 \underset{Pythagoras}{=} m \cdot (a^2 + b^2)$```
$$E \underset{Einstein}{=} m \cdot c^2 \underset{Pythagoras}{=} m \cdot (a^2 + b^2)$$
# Klammern
$$\Biggl(\biggl(\Bigl(\bigl((x)\bigr)\Bigr)\biggr)\Biggr)$$
```$\Biggl(\biggl(\Bigl(\bigl((x)\bigr)\Bigr)\biggr)\Biggr)$```
# Binomialkoeffizient
$$\binom{n}{k} = \frac{n!}{(n - k)! \cdot k!}$$
```  $\binom{n}{k} = \frac{n!}{(n - k)! \cdot k!}$```

# Spezielle Funktionen
mit nicht kursivem Namen
$$\underset{x \to 0}{\lim} , \sin$$
```$\underset{x \to 0}{\lim} , \sin$```
## Produkte
$$q= \sqrt[n]{\prod\limits_{i=1}^{n}{x_i}}=\sqrt[n]{x_1\cdot x_2\cdot\ldots\cdot x_n}$$
```$q= \sqrt[n]{\prod\limits_{i=1}^{n}{x_i}}=\sqrt[n]{x_1\cdot x_2\cdot\ldots\cdot x_n}$```
# Zeichen
## Gleichheitszeichen
$$\approx \sim \simeq \cong \equiv \stackrel{\wedge}= \neq$$
```$\approx \sim \simeq \cong \equiv \stackrel{\wedge}= \neq$```
## Relationszeichen
$$\lt \gt \le \ge \gg$$
```$\lt \gt \le \ge \gg $```
## Mengen
$$\cup \cap \setminus \subset \subseteq \subsetneq \supset \in \notin$$
``` \emptyset \varnothing \infty \Bbb{C}\Bbb{R}\Bbb{I}\Bbb{Q}\Bbb{Z}\Bbb{N}```
$$\emptyset \varnothing \infty \Bbb{C}\Bbb{R}\Bbb{I}\Bbb{Q}\Bbb{Z}\Bbb{N}$$
```$\cup \cap \setminus \subset \subseteq \subsetneq \supset \in \notin ```
## logische Operatoren
$$\land \lor \lnot \forall \exists$$
```$\land \lor \lnot \forall \exists$```
## Pfeile
$$\to  \rightarrow \Rightarrow \implies \mapsto$$
```$\to  \rightarrow \Rightarrow \implies \mapsto```
$$\gets \leftarrow  \Leftarrow$$
```$\gets \leftarrow  \Leftarrow$```
$$\leftrightarrow \Leftrightarrow\longleftrightarrow \iff$$
```$\leftrightarrow \Leftrightarrow\longleftrightarrow$ \iff$```
##### Normal/orthogonal und parallel
$$\perp \parallel$$
```\perp \parallel```
## Abstände
$$\_ \, \_$$
	```$\,$``` 
	kleiner Abstand 
$$\_ \: \_$$
	```$\:$``` 
	mittlerer Abstand 
$$\_ \; \_$$
	```$\;$``` 
	  großer Abstand 
$$\_ \ \_$$
	```\+Leerzeichen``` 
	 Zwischenwortabstand 
$$\_ \quad \_$$
	```$\quad$``` 
	größerer Abstand (Breite von Buchstabe M) 
$$\_ \qquad \_$$
	```$\qquad$``` 
	noch größerer Abstand



$$2025 = \begin{cases}
[(2+0+2+5)\cdot(2-0-2-5)]^2\\
(20+25)^2\\
(\sum_\limits{i=1}^9 i)^2\\
\sum_\limits{i=1}^9 i^3
\end{cases}$$
