# Algèbre linéaire

Fabrice Mahi  
Batiment 22 - p116  
fabrice.mahi@univ-rennes1.fr

---

## <u>Rappels de logique et de raisonnement mathématiques</u>

### **Exercice** : 
Négation de $\exists!x\in E\ |\ P(x)$ :   
$(\forall x\in E, \neg P(x))\vee(\exists x\in E, \exists y\in E\ |\ > x\ne y)\ \wedge (P(x) \wedge P(y))$

### **Exemple 1.3** :

On émet l'hypothèse que les membres de A sont racines du polynome de B.
$$
\begin{split}
    &(x+1)(x-\frac12)(x-2)(x-5)\n
    &(x^2-\frac x2+x-\frac12)(x^2-5x-2x+10)\n
    &(x^2+\frac x2 -\frac12)(x^2-7x+10)\n
    &x^4-7x^3+10x^2+\frac{x^3}2-\frac72x^2+5x-\frac{x^2}2+\frac72x-5\n
    &x^4-\frac{13}{2}x^3-6x^2+\frac{17}2x-5
\end{split}
$$

### **Exemple 1.4** : 

Pour m : $n^2$ pair $\rightarrow$ n pair  
on a m : $\neg(n\text{ pair}) \rightarrow \neg(n^2\text{ pair})$  
$\phantom{on a m : }$ n impaire $\rightarrow$ $n^2$ impair  
$\exists k\in \N, n=2k+1\rightarrow n^2=4k^2+1=2(2k^2+2k)+1$  
$\quad\quad=2m+1;m\in\N$  
$\Rightarrow$ $n^2$ est impair

### **Exemple 1.5** : 

On suppose que $\sqrt2 = \frac pq$ avec $p,q\in\N^*$ et p et q premiers entre eux  
$\Rightarrow 2 = \frac{p^2}{q^2}$  
$\Leftrightarrow p^2=2q^2$  
$p^2$ pair $\Rightarrow$ p pair $\Rightarrow \exists n\in\N,p=2m$  
$\Rightarrow 2q^2=4m^2 \Rightarrow q^2=2m^2\Rightarrow q$ pair  
$\Rightarrow$ p et q ont 2 en diviseur commun

### **Exemple 1.6** : 
Pour m : $n^2$ pair $\Rightarrow n$ pair  
On suppose que $n^2$ pair et $n$ impair  
$n=2p+1 \Rightarrow n^2=2(2p^2+2p)+1$  
$\quad\quad=2k+1\Rightarrow n^2$ impair

### **Exemple 1.7** : 
$$
\begin{split}
    &\forall n\in\N,\sum_{i=0}^{n}i=\frac{n(n+1)}{2}\n
    &\text{Init : } n = 0, \sum_{i=0}^{0}0=0=\frac{0(0+1)}{2}\n
    &\text{Hyp : } k\in\N, \sum_{i=0}^{k}i=\frac{k(k+1)}{2}\n
    &\text{Conc : Pour } k+1 \sum_{i=0}^{k+1}i\n
    &=\sum_{i=0}^{k}i+k+1\n
    &=\frac{k(k+1)}{2}+(k+1)\n
    &=(k+1)*(\frac k2 + 1)\n
    &=(k+1)*\frac{(k+1)+1}{2} 
\end{split}
$$

### **Exemple 1.8** : 

Prenons la fonction $f(x)=x+1$  
$f(1) = 2$ et $f(-1) = 0$  
$f(1) \neq f(-1)$ et $f(1) \neq -f(1)$ donc f n'est ni paire ni impaire.  
Ainsi l'assertion est fausse.

### **Exercice** :

"L'application f de E vers F n'est pas une injection"
équivaut à   
$\exist (x,x')\ |\ (x\neq x')\wedge(f(x)=f(x'))$
