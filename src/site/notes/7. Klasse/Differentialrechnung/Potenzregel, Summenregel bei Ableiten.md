---
{"dg-publish":true,"permalink":"/7-klasse/differentialrechnung/potenzregel-summenregel-bei-ableiten/","tags":["F/F7/F705",7],"dg-note-properties":{"tags":["F/F7/F705",7]}}
---

Ich kann einfache Regeln des Differenzierens anwenden (Potenzregel, Summenregel).

siehe auch:
___
#### y = x²
```
y         =  x²
y + dy    = (x+dx)²
y + dy    =  x²+2x•dx+(dx)²
y + dy    =  x²+2x•dx
    dy    =     2x•dx
    dy/dx =     2x 
```
Änderungsrate von y bei Änderung von x ist 2x.
#### y = x² alternativ
```
f’(x) =        lim [f(tx)-f(x)]/[tx-x] = 
               t→1                        
      =        lim [(tx)² -x²  ]/[tx-x] =
      =        lim [ t²x² -x²  ]/x[t-1] =
      = x²/x • lim [ t²   -1   ]/ [t-1] =
      = x    • lim [(t+1)•(t-1)]/ [t-1] =
      = x    • lim [(t+1)      ]        = 2x
               t→1
```
#### y = x³
```
y         =  x³
y + dy    = (x+dx)³
y + dy    =  x³+3x²•dx+3x(dx)²+(dx)³
y + dy    =  x³+3x²•dx
    dy    =     3x²•dx
    dy/dx =     3x² 
```
#### y = x³ alternativ
```
f’(x) =         lim [f(tx)    -f(x)]/[tx-x] = 
                t→1                        
      =         lim [(tx)³    -x³  ]/[tx-x] =
      =         lim [ t³x³    -x³  ]/x[t-1] =
      = x³/x  • lim [ t³      -1   ]/ [t-1] =
      = x²    • lim [(t²+t+1)•(t-1)]/ [t-1] =
      = x²    • lim [(t²+t+1)      ]        = 3x²
```
#### xⁿ alternativ
```
f’(x) =         lim [f(tx)        -f(x)]/[tx-x] = 
                 t→1                        
      =         lim [(tx)ⁿ        -xⁿ  ]/[tx-x] =
      =         lim [ tⁿxⁿ        -xⁿ  ]/x[t-1] =
      = xⁿ/x  • lim [ tⁿ          -1   ]/ [t-1] =
      = xⁿ⁻¹  • lim [(tⁿ⁻¹+…+t+1)•(t-1)]/ [t-1] =
      = xⁿ⁻¹  • lim [(tⁿ⁻¹+…+t+1)      ]        = n•xⁿ⁻¹
                t→1 

```
#### y = √x
```
f’(x) =         lim [f(tx)-f(x)]/[tx-x] = 
                t→1                        
      =         lim [√(tx) - √x]/[tx-x]    =
      =         lim [√t•√x - √x]/x[t-1]    =
      = √x/x  • lim [√t    - 1 ]/ [t-1]    =      u=√t  u²=t
      = 1/√x  • lim [u     - 1 ]/[u²-1]    =
                u→1 
      = 1/√x  • lim [u     - 1 ]/[u+1][u-1] =
      = 1/√x  • lim            1/[u+1]      = 1/[2√x]
                u→1 
```
#### y = 1/x
```
f’(x) =         lim [f(tx)   - f(x)]  / [tx-x] = 
                t→1                        
      =         lim [(tx)⁻¹  - x⁻¹ ]  / [tx-x] =
      =         lim [ t⁻¹x⁻¹ - x⁻¹ ]  / x[t-1] =
      = x⁻¹/x • lim [ t⁻¹     -1   ]•t/  [t-1]•t =
      = x⁻²   • lim [ 1       -t   ]  /  [t-1]•t =
      = x⁻²   • lim               -1  /        t = -1/x²
                t→1 
```
#### ln(x)
```
f’(x) =         lim [f(tx)   - f(x)]  / [tx-x] = 
                t→1                        
      =         lim [(tx)⁻¹  - x⁻¹ ]  / [tx-x] =
      =         lim [ t⁻¹x⁻¹ - x⁻¹ ]  / x[t-1] =
      = x⁻¹/x • lim [ t⁻¹     -1   ]•t/  [t-1]•t =
      = x⁻²   • lim [ 1       -t   ]  /  [t-1]•t =
      = x⁻²   • lim               -1  /        t = -1/x²
                t→1 
```