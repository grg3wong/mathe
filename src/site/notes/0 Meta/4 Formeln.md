---
{"dg-publish":true,"permalink":"/0 Meta/4 Formeln/"}
---

### Binomische Formeln
- $(a+b)^2=a^2+2ab+b^2$
{ #binom1}

- $(a-b)^2=a^2-2ab+b^2$
{ #binom2}

- $(a+b) \cdot (a-b)=a^2-b^2$
{ #binom3}

- $(a+b)^3=a^3+3a^2b+3ab^2+b^3$
{ #binom4}

- $(a+b)^4=a^4+4a^3b+6a^2b^2+4ab^3+b^4$
{ #binom5}

## Beschreibende Statistik
##### Arithmetisches Mittel
$\bar{x}=\frac{\sum_ \limits{i=1}^{n} x_i}{n}$
##### Geometrisches Mottel
$q= \sqrt[n]{\prod\limits_{i=1}^{n}{x_i}}=\sqrt[n]{x_1\cdot x_2\cdot...\cdot x_n}$
##### Harmonisches Mittel
$h = \frac{1}{\sum \limits_{i=1}^{n}\frac{1}{x_i}} = \frac{1}{\frac{1}{x_1}+\frac{1}{x_2}+...+\frac{1}{x_n}}$
##### Median
$\tilde x = x_{\frac{n+1}{2}}$ bei geradem n
$\tilde x = \frac{x_{\frac{n}{2}}+x_{\frac{n+1}{2}}}{2}$ bei ungeradem n
#### Summenregeln
$\sum \limits_{i=1}^{n} c \cdot a_i = c \cdot \sum \limits_{i=1}^{n} a_i$
$\sum \limits_{i=1}^{n} (a_i+b_i) = \sum \limits_{i=1}^{n} a_i + \sum \limits_{i=1}^{n} b_i$

#### empirische Varianz
$s²=\frac{(x_1-\bar{x})^2+(x_2-\bar{x})^2+...+(x_n-\bar{x})^2}{n}= \frac{1}{n}\sum_\limits{i=1}^{n}(x_i-\bar{x})^2$ 
#### empirische Standardabweichung
$s=\sqrt{\frac{(x_1-\bar{x})^2+(x_2-\bar{x})^2+...+(x_n-\bar{x})^2}{n}}$
#### Verschiebungssatz für die empirische Varianz
$s²=\frac{x_1^2+x_2^2+...+x_n^2}{n}-\bar{x}²=\frac{1}{n} \cdot \sum_\limits{i=1}^{n}x_i^2-\bar{x}²$
#### Kovarianz
$s_{xy}=\frac{(x_1-\bar x) \cdot (y_1-\bar y)+(x_2-\bar x) \cdot (y_2-\bar y)+...+(x_n-\bar x) \cdot (y_n-\bar y)}{n}=\frac{1}{n} \sum \limits_{i=1}^{n}(x_i-\bar x) \cdot (y_i-\bar y)$
#### Verschiebungssatz für die empirische Covarianz
$s_{xy}=\frac{1}{n} \sum \limits_{i=1}^{n}(x_i \cdot y_i) -\bar x \cdot \bar y$
#### Pearson’scher Korrelationkoeffizient
$r_{xy}=\frac{s_{xy}}{s_x \cdot s_y}$
#### Regressionsgerade, Trendlinie
$k = \frac{s_{xy}}{s^2_x}$
$d = \bar y - k \cdot \bar x$
## Differentialrechnung
#### Differenzenquotient
$\frac{f(x+\Delta{x})-f(x)}{\Delta{x}}$
#### Differentialquotient
$f'(x) = \underset{\Delta{x} \rightarrow 0}\lim \frac{f(x+\Delta{x})-f(x)}{\Delta{x}} = k$
##### Ableitung von konstanten Funktionen
$f'(x)=0$ mit $f(x) = c$ mit $c \in \Bbb R$
##### Ableitung mit additiver Konstante
$(f(x) + c)’   = f’(x)$
##### Ableitung mit multiplikativer Konstante
$f'(x)=c \cdot f'(x)$ mit $f(x) = c \cdot x^n$
##### Ableitung von Polynomen
$f'(x) = g'(x)+h'(x)$ mit $f(x)=g(x)+h(x)$
##### Ableitung von Potenzfunktion mit Faktor
$f'(x)=c \cdot g'(x)$ mit $f(x)=c \cdot g(x)$
##### Ableitung von rationaler Funktion
$f'(x)=\frac{-1}{x^2}$ mit $f(x)=\frac{1}{x}$
##### Ableitung der Quadratwurzel
$f'(x)=\frac{1}{2 \cdot \sqrt x}$ mit $f(x)=\sqrt x$
##### Produktregel 
$f'(x)=u' \cdot v+u \cdot v'$ mit $f(x)=u \cdot v$
##### Quotientenregel 
$f'(x)=\frac{u' \cdot v-u \cdot v'}{v^2}$ mit $f(x)=\frac{u}{v}$
##### Kettenregel
$f'(x)=g'(h(x)) \cdot h'(x)$ mit $f(x)=g(h(x))$
##### Exponentialfunktion
$f'(x)=ln(a) \cdot a^x$ mit $f(x)=a^x$
##### Logarithmusfunktion
$f'(x)=\frac{1}{x}$ mit $f(x)=ln(x)$
$f'(x)=\frac{1}{ln(a)} \cdot \frac{1}{x}$
##### Winkelfunktionen
$sin'(x)=cos(x)$
$cos'(x)=-sin(x)$
$tan'(x)=\frac{1}{cos^2(x)}=1+tan^2(x)$