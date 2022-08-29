# Python - cheatsheet

# Sommaire

1. [Créer une variable][head_1]
2. [Interagir avec l'utilisateur][head_2]
3. [Les conditions][head_3]
___

## Créer une variable

* Pour déclarer une varibale il suffit de lui donner un nom :
```python
nom_utilisateur
age_utilisateur
```

<!-- ajouter un lien sur le mot type vers une liste non exaustive des types en python -->
* On peut préciser le type de la variable (optionnel) :
```python
nom_utilisateur: str # cette varibale sera une chaine de caractères
age_utilisateur: int # cette variable sera un entier signé (positif ou négatif)
```

* Pour assigner une valeur on utilise l'opérateur d'affectation ( `=` ) :
```python
nom_utilisateur: str = "Jean"
age_utilisateur: int = 18
```

## Interagir avec l'ordinateur

* Pour demander à l'utilisateur d'écrire dans la console on utilise la fonction `input` :
```python
nom_utilisateur: str = input("Veuillez entrer votre nom : "")
```

* Dans le cas ou la valeur attendue n'est pas de type `str` il faudra la convertir *(on appelle cette opération un `cast`)* :
```python
age_utilisateur: int = int(input("Quel age avez-vous : "))
```

* De même on peut afficher des informations sur la console grâce à la fonction `print` :
```python
nom_utilisateur: str = "Jean"
print("Votre nom est", nom_utilisateur)
```

* Pour formater plus facilement la sortie on peut utiliser cette synaxe :
```python
nom_utilisateur: str = "Jean"
age_utilisateur: int = 18
print(F"Vous vous appellez {nom_utilisateur} et vous avez {age_utilisateur} ans !")
```

## Les conditions

* En python un condition est représenté sous la forme d'une valeur booléenne (`bool`)  
    Pour calculer une telle valeur on peut utiliser deux types de comparaisons: **logique** ou **mathématique** : 
```python
# valeur booléenne en python
je_suis_vrai: bool = True
je_suis_faux: bool = False

# comparaison logique

# le résultat est True
comparaison_ou: bool = je_suis_vrai or je_suis_faux
# le résultat est False
comparaison_et: bool = je_suis_vrai and je je_suis_faux

# comparaison mathématique

age_utilisateur: int = 18
# le résultat est False
mineur: bool = age_utilisateur < 18
# le résultat est True
majeur: bool = age_utilisateur >= 18

# vérifie l'égalité

# le résultat est True
a_juste_la_majorite: bool = age_utilisateur == 18
```
*_note_ : il est recommandé due à la représentation des nombres réel dans la mémoire de l'ordinateur d'évité de comparer l'égalité entre deux réels.*

* Pour écrire une condition on utilise le mot clé `if`,  
dans le cas où la condtion n'est pas vérifié nous pouvons utiliser le mot clé `else`,  
si on veut rajouter une couche de test il existe le mot clé `elif` :
```python
age_utilisateur: int = int(input("Quel est votre age : "))
if age_utilisateur < 18:
    print("Vous êtes mineur !")
elif age_utilisateur == 18:
    print("Vous venez d'avoir 18 ans !")
else:
    print("Vous êtes majeur")
```

[head_1]: cours-esir.github.io/#/lessons/CUPGE+1/Info/python+-+cheatsheet.md#Créer+une+variable
[head_2]: cours-esir.github.io/#/lessons/CUPGE+1/Info/python+-+cheatsheet.md#Interagir+avec+l'ordinateur
[head_3]: cours-esir.github.io/#/lessons/CUPGE+1/Info/python+-+cheatsheet.md#Les+conditions
