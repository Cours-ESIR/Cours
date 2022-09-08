# Les fonctions

Une fonction est un bout de programme qui ne se lance que lorsqu’on l’appelle.

Elle peut être pratique à utiliser lorsqu’on effectue plusieurs fois la même suite d’opérations car on peut simplifier le code et le rendre plus lisible.

Formule Générale : def nom_de_la_fonction (<"var1">,<"var2">,...)

Remarque : les <"var1">,<"var2">, … sont des variables que l’on peut être amené à utiliser dans la fonction.

Evidemment elles sont facultative si votre fonction n’a pas besoin de variables.

Pour appeler la fonction on écrit :

nom_de_la_fonction (<"var1">,<"var2">,...)

```python
def multiplication( chiffre1 , chiffre2 ):
  return chiffre1 * chiffre2

def retourne_yes():
  return "yes"

# return retourne juste la valeur, il ne l'affiche pas
# pour l'afficher on fera : print( retourne_yes )
# on peut également l'attribué à une variable : a = retourne_yes
```

Quelques fonctions pratiques

```python
print(valeur) # affiche la valeur dans la console
```
