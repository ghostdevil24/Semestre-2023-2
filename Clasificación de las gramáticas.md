---
share: true
folder: LENGUAJES FORMALES Y AUTOMATAS
---
## Regulares (tipo 3)
Para los lenguajes tipo 3 generados por gramáticas regulares
son:
- lineal por la derecha (V$\rightarrow$$\beta$, V$\rightarrow$$\beta$W)
- lineal por la izquierda (V$\rightarrow$$\beta$, V$\rightarrow$W$\beta$)
Donde V y W son variables y $\beta$ pertenece al $\sum^*$ 
## Libres de contexto (tipo 2)
Las reglas son de la forma:
X$\rightarrow$$\beta$
donde B es una cadena de terminales y/o variables o bien la cadena vacia
Ej:
S$\rightarrow$ (S)S| $\lambda$
## Sensibles al contexto (tipo 1) 
$\alpha_1$V$\alpha_2$$\rightarrow$$\beta$
donde $\alpha_1$,$\alpha_2$ son una combinación de terminales y/o variables o $\lambda$
y ademas |$\alpha_1$V$\alpha_2$|<=|$\beta$|
## Gramáticas sin restricciones (tipo 0)
Las reglas son de la forma $\alpha_1$V$\alpha_2$$\rightarrow$$\beta$  son una combinación de terminales y/o variables  $\lambda$

