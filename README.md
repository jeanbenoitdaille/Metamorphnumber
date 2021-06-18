# Metamorphnumber
Afficher un nombre à l'intérieur d'une chaine de  caractères 
Python ne permet pas de concaténer un nombre avec une chaine de caractères , donc convertir nombre en chaine de caractère 
Là encore un exercice très simple pour ceux qui sont habitués à Python.

Dans Python, on ne peut pas concaténer des variables de différents types. Ainsi, si on essaie d'additionner une chaîne de caractères avec un nombre, on se retrouve avec une erreur :

    >>> nombre = 15
    >>> print("Le nombre est " + nombre)
    Traceback (most recent call last):
      File "<stdin>", line 1, in <module>
    TypeError: must be str, not int

L'erreur ci-dessus nous indique que le type de la variable 'nombre', pour être concaténé avec la chaîne de caractère 'Le nombre est ', doit être de type 'str' (chaîne de caractère) et non pas 'int' (nombre entier).

Pour remédier à ce problème, on convertit donc notre nombre 15, par la chaîne de caractère '15', grâce à la fonction str.
