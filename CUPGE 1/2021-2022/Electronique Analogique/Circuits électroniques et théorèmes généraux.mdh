# 1 : Circuits électroniques et théorèmes généraux

# 1.1 : Généralités

circuit électrique :

**// Schéma**

> **Une branche** est une partie d'un circuit ou passe un courant identique

> **Un noeud** est un point de jonction de plusieurs branches

### 1.1.1 : Tensions et courant

| Nom       | Symbole | Unité     |
| :-------: | :-----: | :-------: |
| Intensité | I       | Ampère (A)|
| Potentiel | U       | Volt (V)  |
| Tension   | U       | Volt (V)  |

> on peut assimiler le courant au débit d'une rivière et la tension à la largeur d'une rivière

**// Schéma**

Exemple

**// Schéma**

### 1.1.2 : Associations de générateurs

En parallèlle = En dérivation

// Schéma

$$

U_{AB} = V_A - V_B
\\ \ \\
U_{BC} = V_B - V_C
\\ \ \\
U_{AC} = V_A - V_C
\\ \ \\
U_{AC} = V_A - V_B + V_B - V_C
\\ \ \\
U_{AC} = U_{AB} + U_{BC}
\\ \ \\
U_{AC} = 15.3 V

$$

// schémas

### 1.1.3 : Générateurs

Symboles 

générateur de tension continue

// Symboles

générateur de tension sinusoïdale

// Symboles

généralité de tension carré

// Symboles

générateur de courant continu

// Symboles

### 1.1.4 : Dipôles passifs

| Nom          | Symbole   | Unité          | Grandeur  |
|--------------|-----------|----------------|-----------|
| résistance   | // schéma | Résistance (R) | Ohm (Ω)   |
| bobine       | // schéma | Inductance (L) | Henry (H) |
| condensateur | // schéma | Capacité (C)   | Farad (F) |

### 1.1.5 : Loi d'Ohm

Lien courant/tension dans un Dipôles

Résistance // schéma

> **Loi d'Ohm**
> 
> $ U_R = R × I_R $
> 
> $ u(t) = R × i_R(t) $

Autres lois pour L et C

> **Loi Capacité**
> 
> $ i_C(t) = C × \frac{\partial{u_C(t)}}{\partial{t}} $

// schéma

> **Loi Inductance**
> 
> $ u_L(t) = L × \frac{\partial{i_L(t)}}{\partial{t}} $

// schéma

Exemple 

// schéma

$$

e(t) = E × cos(2\pi f t)
\\ \ \\
i(t) = C × \frac{\partial{e(t)}}{\partial{t}} 
\\ \ \\
i(t) = C × E × (-2\pi f × sin(2\pi f t))

$$

||||
|--|--|--|
|E|Amplitude|Volt|
|F|Fréquence|Hertz|

## 1.2 : Lois de Kirchhoff

### 1.2.1 : Loi des noeud

//schéma

Au noeud A, la somme des courants qui rentre est égale à la somme des courants qui sortent

$$
I_1 + I_2 + I_3 = I_4 + I_5
$$

autre notation 

// schéma

$$

I_i > 0 \ \ \ \text{entrant}
\\ \ \\
I_i < 0 \ \ \ \text{sortant}
\\ \ \\
\sum_{i}I_i=0

$$

### 1.2.2 : Loi des mailles

exemples de circuits : 
// schéma

> **Maille**
> 
> boucle dans le circuit qui parcourt différentes branches

Maille 1 : $E,R_1,R_2$

Maille 2 : $R_2,R_3$

Maille 3 : $R_2,R_3$

> **Loi des mailles** 
>
> sur une maille : $\sum_{i}u_i=0$

Exemple : 

Maille 1 : $E-R_1I_1-R_2I_2=0$

Maille 2 : $R_2I_2-R_3I_3=0$ 

Maille 3 : $E-R_1I_1-R_3I_3=0$ 

## 1.3 : Association de résistances

### 1.3.1 : Résistance en série

// schéma

-> résistance équivalente

// schéma

$$

U_{R_I} = R_I × I
\\ \ \\
U = \sum_{i=1}^n u_{R_i} = \sum_{i=1}^n R_i × I
\\ \ \\
U =  I×\sum_{i=1}^n R_i = I×R_{eq}
\\ \ \\
R_{eq} = \sum_{i=1}^n R_i

$$

### 1.3.2 : Résitance en parallèlle

// schéma

$$

U_{R_i} = R_i × I_i = U

\\ \ \\

I = \sum_{i=1}^{n}I_i

\\ \ \\

$$

1)

$$

I_i = \frac{U}{R_i}

\\ \ \\

I = \sum_{i=1}^{n}\frac{U}{R_i} = U × \sum_{i=1}^{n}\frac{1}{R_i}

\\ \ \\

\frac{1}{R_{eq}} = \sum_{i=1}^{n}\frac{1}{R_i}

$$

Exemple : 

// schéma

$$

\frac{1}{R_{eq}}  = \frac{1}{1kΩ}  + \frac{1}{1kΩ} = \frac{2}{1kΩ}

\\ \ \\

R_{eq} = \frac{1}{2}kΩ = 500 Ω

$$
