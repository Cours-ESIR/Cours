# Les listes

Une liste est une suite de variables séparé par des virgules.
Celle-ci peut être peut être utilisé pour avoir plein de variables en une seule.

Illustration :

```python
# il est plus judicieux de faire

mots = ["il","fait","beau"]

# que

mot0 = "il"
mot1 = "fait"
mot2 = "beau"
```

Les listes sont souvent utilisés pour faire des boucles.

Remarque: Comme les listes sont ordonnées, on attribue un numéro d’ordre à chacune des valeurs de la liste en commençant à 0 : on appelle ce numéro l’ “index”

Illustration : 

```python
list  = [ "p" , "y" , "t" , "h" , "o" , "n" ]

list[0] # p
list[1] # y
list[2] # t
list[3] # h
list[4] # o
list[5] # n

```


Comment les générées:

```python
liste0 = [] # pour créer une liste vide

liste1 = ["mot", 1, 1.0, True] # pour créer une liste avec des valeurs

liste2 = range(10) # pour créer une liste de 0 à 9

liste3 = range(1, 10, 2) # pour créer une liste de 1 à 9 de deux en deux => [1, 3, 5, 7, 9]
```

Comment interagir avec:

```python
liste0 = [7]
liste0.append(5) # on ajoute 5 à la fin de la liste => liste0 = [7, 5]

liste1 = [7, 5]
print( liste1[0] ) #affiche la valeur au rang 0 de la liste1, ici c'est 7

liste2 = [7, 5]
liste2[1] = 3 # change la valeur au rang 1 de la liste2 par 3, ici c'est 5 qui est remplacé par 3 => liste2 = [7, 3]
```
