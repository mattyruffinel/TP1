# TP1

<!--- Changer la date de remise en modifiant le URL--->
#### :alarm_clock: [Date de remise](https://www.timeanddate.com/countdown/generic?iso=20210131T2359&p0=165&msg=Remise&font=cursive&csz=1#)

## Objectif

Ce TP à pour objectif de vous introduire à l'algorithmie avec le langage de programmation python.
Celui-ci est composé de 5 exercices différent et vous devez compléter le code à chaque fois que vous voyez l'indicateur "TODO".

## Consignes à respecter

Tout d'abord, assurez-vous d'avoir lu le fichier instruction.md et d'avoir télécharger le fichier main.py que vous devrez completer.
Pour ce TP certaines contraintes sont a respectés:
- Vous ne pouvez pas importer d'autre librairies
- Il est interdit de manipuler des chaines de caractère.
- Il est interdit d'utiliser les structures de répetitions(for, while, etc.) 

## Exercice 1:
Dans cet exercice vous devez calculer l'énergie cinetique d'une voiture. Le programme commence en demandant à l'utilisateur de saisir la masse et la vitesse de la voiture, il suffit de compléter la fonction "calculerEnergie".
```python
    def calculerEnergie(masse,vitesse):
        # TODO convertir la vitesse en metre par seconde, assigner la valeur à la variable "vitesse"
        vitesse=
        
        # TODO calculer l'energie cinetique, assigner la valeur à la variable "energieCinetique"
        energieCinetique=
        
        return energieCinetique
```

## Exercice 2:
Dans cet exercice vous devez résoudre une equation quadratique de la forme $A$. Le programme commence en demandant à l'utilisateur de saisir la masse et la vitesse de la voiture, il suffit de compléter la fonction "calculerEnergie".
<img src="https://render.githubusercontent.com/render/math?math=e^{i \pi} = -1">
```python
    def calculerEnergie(masse,vitesse):
        # TODO convertir la vitesse en metre par seconde, assigner la valeur à la variable "vitesse"
        vitesse=
        
        # TODO calculer l'energie cinetique, assigner la valeur à la variable "energieCinetique"
        energieCinetique=
        
        return energieCinetique
```
Exemple

print(capitaliser_pays('antigua ANd barbuda'))

Antigua and Barbuda
À compléter

Vous devez compléter la fonction suivante du fichier exercice.py.

def capitaliser_pays(nom):
    #TODO completer la fonction
    return nom

Connaissances utiles
Changement de casse

chaine = "Hello, World!"
print(chaine.upper())
print(chaine.lower())
print(chaine.capitalize())
print(chaine.swapcase())

HELLO, WORLD!
hello, world!
Hello, world!
hELLO, wORLD!
Remplacement de sous-chaîne (substring)

print(chaine.replace('Hello', 'Bonjour'))

Bonjour, World!
Trouver une sous-chaîne ou un charactère

# retourne le premier indice trouvé
print(chaine.find('o'))
print(chaine.find('World'))

4
7
