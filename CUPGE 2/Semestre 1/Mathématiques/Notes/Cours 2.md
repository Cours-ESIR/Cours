## Rappels de géométrie dans le plan et dans l'espace

### **Exemple 2.4**


|                 | colinéaire | orthogonaux | base |
|:---------------:|:----------:|:-----------:|:----:|
|$(\vec u,\vec v)$|❌|❌|✅|
|$(\vec u,\vec w)$|✅|❌|❌|
|$(\vec u,\vec i)$|❌|❌|✅|
|$(\vec i,\vec j)$|❌|✅|✅|
|$(\vec v,\vec w)$|❌|❌|✅|

---

### **Exemple 2.10**

doite affine passant par A $\binom{1}{2}$ et de vecteur directeur $\vec u = 3\vec i +2\vec j$.  
équation affine : $y=\frac23x$  
équation paramétrique :  
$$ \embrace{&x = 3t+1\\ &y =2t+2}{\{}{.} $$

Droite affine $y=2x+1$.  
Elle passe par le point B $\binom13$.  
vecteur directeur : $2\vec i + \vec j$  
équation paramétrique :
$$ \embrace{&x = 2t+1\\ &y =t+3}{\{}{.} $$

---

### **Exemple 2.13**

$\vec u = 3\vec i + 2\vec j$  
$\vec v = 2\vec i + 3\vec j$  
$\vec w = 6\vec i + 4\vec j$

$$
\begin{split}
\vec u_{\vec i} = \frac{\vec u *\vec i}{||\vec i||^2}=3\vec i\n
\vec u_{\vec j} = \frac{\vec u *\vec j}{||\vec j||^2}=2\vec j
\end{split}\n
\vec u_{\vec v} = \frac{\vec u * \vec v}{||\vec v||^2}*\vec v
$$
<!-- Ajouter u sur v et u sur w -->

---

### **Exemple 2.22**

$(\vec u,\vec v,\vec w)$ Non car $\vec w = 2*\vec u$  
$(\vec u,\vec v,\vec k)$ Oui  
$(\vec i,\vec j,\vec v)$ Non car $\vec v = k\vec i + k'\vec j$  
$(\vec i,\vec j,\vec w)$ Oui

$\vec u = 3\vec i +2\vec j+\vec k$  
$\vec v = 2\vec i + 3\vec j$  
$\rightarrow \vec v-2\vec i =3\vec j$  
$\Rightarrow\vec j = \frac13\vec v-\frac23\vec i$

---

### **Exemple 2.25**

droite de vecteur directeur $\vec u=3\vec i +2\vec j$  
équations linéaires :
$$ \embrace{&2x-3y=0\\&z=0}{\{}{.} $$
équations paramétriques :
$$ \embrace{&x(t)=3t\\ &y(t)=2t\\ &z(t)=0}{\{}{.} $$

<!-- faire la partie 2 de l'exemple -->

---

### **Exemple 2.27**
Soit la droite affine passant par $A(1,2,3)$ de vecteur directeur $\vec u=3\vec i+2\vec j$  
équations linéaires :
$$ \embrace{&2x-3y=-4\\&z=3}{\{}{.} $$
équations paramétriques : 
$$
\embrace{&x(t)=3t+1\\&y(t)=2t+2\\&z(t)=3}{(}{)}
$$
---

Soit la droite affine d'équations $y=2x+1$ et $z=x+y+1$.
Un point est $B(0,1,2)$  
Un autre est $C(1,3,5)$  
D'où le vecteur unitaire $\vec u = (1-0)\vec i+(3-1)\vec j+(5-2)\vec k = \vec i+2\vec j+3\vec k$.

---

### **Exemple 2.30**

Soit les vecteurs :  
$\vec u =3\vec i+2\vec j+\vec k$  
$\vec v =2\vec i+3\vec j$  
$\vec w =6\vec i+4\vec j+2\vec k$  
On a les projetés orthogonaux suivants :  
$\vec u_{\vec i} = 3\vec i$ ; $\vec u_{\vec j} = 2\vec j$ ;  
$\vec u_{\vec v} = \frac{6+6+0}{4+9}\vec v=\frac{12}{13}\vec v$ ;  
$\vec u_{\vec w} = \frac{18+8+2}{36+16+4}\vec w=\frac{1}{2}\vec w$  

Soit le point $A(1,2,3)_Q$, $\vec{OH}=\vec i$ donc $H(1,0,0)_Q$  

$$
\embrace{&y=x-2\\&x+y+z=1}{\{}{.}\quad\embrace{&H\in D\\&\vec{AH \perp \vec v}}{.}{.}\quad\embrace{&y_h=x_h-2\\&x_h+y_h+z_h=1}{\{}{.}
$$

$x_h+x_h-2+z_h=1\Leftrightarrow z_h=3-2x_h=3-\frac53=\frac43$  
$\vec{AH}\perp\vec v\Leftrightarrow(x_h-1)+(y_h-2)-2(z_h-3)=6$  
$\quad\Rightarrow(x_h-1)+(x_h-4)-2(z-2x_h-3)=0$  
$\quad\Rightarrow x_h = \frac56$

---

### **Exemple 2.33**

Soit les vecteurs  
$\vec u=3\vec i+2\vec j\in P$  
$\vec k\in P$  
On a  
$x(t,s)=3t$  
$y(t,s)=2t$  
$z(t,s)=s$ avec $t,s\in\R^2$  

$ax+by+cz=0$  
$\vec u\in P\rightarrow 3a+2b=0\Rightarrow b=-\frac32b$  
$\vec k\in P\rightarrow c=0$  
$ax-\frac32ay=0\Leftrightarrow a(2x-3y)=0$  
$a\neq0$ donc $P:2x-3y=0$

---

Soit les vecteurs  
$\vec u=2\vec i+3\vec j+\vec k\in P$  
$\vec v =\vec i+\vec j+\vec k\in P$  
On a  
$x(t,s)=2t+s$  
$y(t,s)=3t+s$  
$z(t,s)=t+s$

$ax+by+cz=0$  
$\vec u\in P\rightarrow 2a+3b+c=0\Rightarrow c=-2a-3b$  
$\vec v\in P\rightarrow a+b+c=0\Rightarrow -a-2b=0\Rightarrow b=-\frac12a$  
$ax-\frac12ay+(-2a+\frac32a)z=0\Rightarrow a(x-\frac12y-\frac12z)=0$  
$a\neq0$ donc $P:x-\frac12y-\frac12z=0$

---

Soit le plan vectoriel d'équation $y=2x$  
$2x+1y+0z=0$  
On peut donc prendre les vecteurs  
$\vec u=(1,2,0)_B$ et $\vec v=(0,0,1)_B$  
ON a alors les équation paramétrique suivantes :  
$x(t,s)=t+s$  
$y(t,s)=2t$  
$z(t,s)=s$  

---

### Exemple **2.35**

Soit le plan P passant par le point $A=(1,2,3)_B$.  
Soit ses vecteur directeurs $\vec u=3\vec i +2\vec j$ et $\vec v =\vec i+\vec j$.  
Une forme de ses équations paramétrique est :  
$x(t,s)=3t+s+1$  
$y(t,s)=2t+s+2$  
$z(t,s)=3$  
On cherche t et s en via les deux premières équations  
$x-y=t-1\Rightarrow t=x-y+1$  
$s=y-2-2*(x-y+1)$  
$s=3y-4-2x$  
Et on injecte les valeurs trouvées dans la troisieme equation    
et $z=z$  

---

Soit le plan P d'équation $2x+y+z-2=0$
On peut y placer les points $A(1,0,0)_R$ ou $B(1,2,-2)_R$.  
On peut trouver les vecteur directeurs satistant $2x+y+z=0$  
$\vec u=(1,0,-2)_B$ et $\vec v(1,-2,0)_B$  
Une forme de ses équations paramétriques est :   
$x(t,s)=1+t+s$  
$y(t,s)=-2s$  
$z(t,s)=-2t$, avec $t,s\in\R^2$

---

### Exemple **2.38**

Soit le vecteur  
$\vec u\phantom{_{\vec i,\vec j}} = 3\vec i+2\vec j+\vec k$  
On peut avoir les projetés orthogonaux suivants :  
$\vec u_{\vec i,\vec j}=3\vec i+2\vec j$  
$\vec u_{\vec i,\vec k}=3\vec i+\vec k$  
Soit le point $A(1,2,3)$ 

--- 

On peut avoir l es projetés orthogonaux suivants :  
$A_{(0;\vec i;\vec u)}$ :  
$P:x+y+z-1=0$  
$\lambda=\frac{1+2+3-1}{1^2+1^2+1^2}=\frac53$  
$x_A=1-\frac53=-\frac23$  
$y_A=2-\frac53=\frac13$  
$z_A=3-\frac53=\frac43$
<!-- wtf?-->