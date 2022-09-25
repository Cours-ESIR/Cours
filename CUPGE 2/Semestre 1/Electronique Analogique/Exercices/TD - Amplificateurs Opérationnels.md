# 1. Amplificateurs Opérationnels

## Exercice 1

> On pose les valeurs:
>
>
> - $E_1 = 9$V / $E_2 = 1$V
> - $R_1 = 10\Omega$ / $R_2 = 5\Omega$ / $R_3 = 10\Omega$ / $R = 10\Omega$

On cherche à déterminer $V_A$ en utilisant le théorème de Millman.  
On peut poser :

$$
    V_A = \frac{\sum\embrace{\frac{V_i}{R_i}}{(}{)}}{\sum\embrace{\frac{1}{R_i}}{(}{)}} = \frac{\frac{E_1}{R_1} + \frac{E_1}{R_2} + \frac{-E_2}{R_3}}{\frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3}} = \frac{26}{5} =\boxed{5.2\text{V}}
$$

On utilise ensuite la Loi d'Ohm :

$$
    V_A = U = R\ I \implies I = \frac{U}{R} = \frac{5.2}{10} = \boxed{0.52\text{A}}
$$

## Exercice 2 : Soustracteur

On cherche à déterminer $V^-$ grâce au théorème de Millman :

$$
    V^- = \frac{\frac{V_E}{R} + \frac{V_S}{R}}{\frac{1}{R} + \frac{1}{R}} = \frac{\frac{V_E + V_S}{R}}{\frac{2}{R}} = \boxed{\frac{V_E + V_S}{2}\text{V}}
$$

On cherche à déterminer $V^+$ grâce au théorème de Millman :

$$
    V^+ = \frac{\frac{E}{R}}{\frac{1}{R} + \frac{1}{R}} = \frac{E\ R}{2R} = \boxed{\frac{E}{2}\text{V}}
$$

On peut aussi utiliser le pont diviseur de tension :

$$
    V^+ = \frac{R}{\frac{2}{R}}*E = \boxed{\frac{E}{2}\text{V}}
$$

Comme on suppose l'AOP idéal on a $V^- = V^+$, d'où :

$$
    \frac{V_E + V_S}{2} = \frac{E}{2} \implies \boxed{V_S = E - V_E}
$$

## Exercice 3 : Additionneur (non inverseur)

On cherche à déterminer $V^-$ et $V^+$ grâce au théorème de Millman :

$$
    V^- = \frac{\frac{V_E}{R} + \frac{E}{R}}{\frac{2}{R}} = \boxed{\frac{V_E + E}{2}\text{V}}
$$

$$
    V^+ = \frac{\frac{V_S}{R}}{\frac{2}{R}} = \boxed{\frac{V_S}{2}\text{V}}
$$

Comme on suppose l'AOP idéal on a $V^- = V^+$, d'où :

$$
    \frac{V_E + E}{2} = \frac{V_S}{2} \implies \boxed{V_S = V_E + E}
$$
