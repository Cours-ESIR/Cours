# Electronique Analogique

professeur: Eric Pottier  
contact: eric.pottier@univ-rennes1.fr
___

## Chapitre 2 : Filtrage de signal

### I) Analyse des systèmes en régimes sinusoïdal

#### 1) Rappels

$\boxed{x(t) = A*cos(\omega t)} \longrightarrow$ SYSTÈME EON $\longrightarrow \boxed{y(t)}$

|                            | DOMAINE TEMPOREL          | DOMAINE FRÉQUENTIEL (DUAL)                    |
|:--------------------------:|:-------------------------:|:---------------------------------------------:|
| Méthode de résolution      | équations différentielles | équations polynomiales                        |
| expression de la tension   | $u(t)$                    | $\underline{U}(j\omega)$                      |
| expression de l'intensité  | $i(t)$                    | $\underline{I}(j\omega)$                      |
| expression de la puissance | $p(t)$                    | $\underline{P}(j\omega)$                      |
| _relation_                 | $x(t) = A\cos(\omega t)$  | $\underline{X}(j\omega) = A\ e^{\ j\omega t}$ |

Dans le système fréquentiel :

* on définit $\omega$ la pulsation du système étudié en $rad\ / sec$ :  
  $\omega = 2\pi*f = \frac{2\pi}{T}$
* les fonctions sont définies dans les complexes avec $j = \sqrt{-1}$
* la relation de transition vers le système temporel est $x(t) = \Re(\underline{X}(j\omega))$

##### Propriétés

$$
\begin{split}
    x(t) = A \cos(\omega t) &\Longleftrightarrow \underline{X}(j\omega) = A\ e^{\ j\omega t} \\
    \frac{d x(t)}{d t} = -A \omega \sin(\omega t) &\Longleftrightarrow \underline{X}(j\omega) = A\ e^{\ j(\omega t + \frac{\pi}{2})}
\end{split}
$$
