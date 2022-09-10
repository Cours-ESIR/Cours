# Electronique Analogique

contact: franck.colombel@univ-rennes1.fr

2 séances TP 4h (logiciel PSpice)

Modalités d'évaluation:

- controle écrit
- 1 note de TP

___

## Chapitre I: Amplificateur opérationnel (AOP)

### 1 : Introduction

<u>Définition</u>: Un amplificateur opérationnel est un ampliificateur à grand gain réalisé à l'aide d'amplificateur différentiel.
On a donc 2 entrées.  
La tension de sortie $V_s$ est proportionelle à la différence entre 2 signaux d'entrée $V^+$ et $V^-$.  
La tension $V^+$ est la tension d'entrée non inverseuse alors qur la tension $V^-$ est la tension inverseuse.  

Pour symboliser un AOP on a 2 possibilités :

![schéma d'un AOP](../../../media/AOP.png)

Si on utilise un AOP en hautes fréquences, de nombreuses imperfections apparaissent:

- *Imperfections statiques* dues à la présence de générateurs de tension ou de courant.
- *Imperfections dynamiques* dues à la présence de condensateurs ou de bobines parasites.

### 2 : L'amplificateur opérationnel idéal

On peut écrire le signal de sortie de la manière suivante :  
$$
    V_s = A_{V_D}(V^+ - V^-) + A_{V_{MC}}(\frac{V^+ + V^-}{2}) \newline
    A_{V_D}:\text{correspond au gain différentiel}\newline
    A_{V_{MC}}:\text{correspond au gain de Mode Commun}
$$
Dans le cas de l'AOP idéal, $A_{V_D}$ est infini et $A_{V_{MC}} = 0$, soit $\epsilon = V^+ - V^- = 0\ (V)\Rightarrow V^+ = V^-$ **et** $i^+ = 0\ (A),\ i^- = 0\ (A)$ donc les impédences d'entrées sont infinies.  

![est-ce vraiment l'AOP idéale ?](../../../media/schéma1.png)

### 3 : Les 3 régimes de fonctionnement

Les 3 régimes de fonctionnement sont définis en fonction de la nature de rebouclage de la sortie sur l'entrée **et** de la nature des composants dans la <u>chaîne de rétroaction</u> *(le rebouclage)*.

#### 1) Le régime linéaire

Le régime linéaire se caractérise par:

- un rebouclage de la sortie sur l'entrée $\ominus$ .
- le bloc de contre réaction ne contient que des composants linéaires.
- $V_s$ est une fonction linéaire des signaux d'entrée.

<u>Exemple :</u>

<!-- ![pourquoi j'avais noté fonction linéaire ?](../../../media/schéma%202.png) -->

Calculons $V_s = f(V_e)$  

$$
    \embrace{
        V_e &= R_1 I\\
        V_s &= -R_2 I
    }{.}{)} \text{Loi d'Ohm} \\

    \text{Fonction d'amplification}:\ \boxed{\frac{V_s}{V_e} = \frac{-R_2}{R_1}}
$$

Calculons $V_s = f(V_e)$ **en faisant tendre $A_{V_D}$ vers l'infini*

![schéma AOP avec AVD](../../../media/schéma%202.png)

$$
    \embrace{
        V_e &= R_1 I - \epsilon \\
        V_s &= A_{V_D} \epsilon \\
        \epsilon &= -R_2I-V_D
    }{\{}{.}
$$

$$
    \embrace{
        V_e &= R_1 I - \frac{V_s}{A_{V_D}} \\
        \frac{V_s}{A_{V_D}}+V_s &= -R_2I
    }{\{}{.}
$$

$$
    \embrace{
        V_e = R_1I-\frac{V_s}{A_{V_D}} \\
        I = -\frac{V_s}{R_2}(1+\frac{1}{A_{V_D}})
    }{\{}{.} \\ \\

    V_e = -\frac{R_1}{R_2}V_s(1+\frac{1}{A_{V_D}}) - \frac{V_s}{A_{V_D}} \\
    V_e = V_s[-R_1]
$$

#### 2) régime non linéaire

Le régime non linéaire se caractérise par :

- le rebouclage se fait sur l'entrée $\oplus$ .
- l'AOP peut fonctionner en boucle ouverte (sans rebouclage).
- il n'existe pas d'expression litterale liant $V_s$ et $V_e$ .
- $V_s$ prend deux valeurs déterministes $\plusmn V_{sat}$ ($V_{sat})$ est très proche de la tension d'alimentation continue de l'AOP) .

<u>Exemple :</u>

![est-ce vraiment l'inverseur ?](../../../media/schéma%203.png)

<!-- Calculs de l'enfer -->

Tant que $V_e$ ( $=V^-$ ) est inférieur à $V^+(\frac{R_1}{R_1+R_2}V_{sat})$ la sortie du comparateur reste à $+ V_{sat}$  
Dès que $V_e$ ( $=V^-$ ) devient supérieure à $V^+ (\frac{R_1}{R_1+R_2}V_{sat})$ la sortie du comparateur bascule et passe à $- V_{sat}$  
$V^+$ s'écrit alors $V^+ = -\frac{R_1}{R_2+R_2}V_{sat}$  
Tant que $V_e$ est supérieure à $V^+(\frac{R_1}{R_1+R_2}V_{sat})$, $V_s$ reste à $-V_{sat}$  
Dès que $V_e$ devient inférieur à $V^+(\frac{R_1}{R_1+R_2}V_{sat})$, la sortie du comparateur bascule et $V_s$ passe à nouveau à $+ V_{sat}$

![graphe d'inversion](../../../media/schéma%204.png)
