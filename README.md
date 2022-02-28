# TP2-Android (Capteurs)
###### Par Sanchez Martin.

#### 1.1 Introduction
Ce TP a pour but de se familiariser avec les capteurs d'un téléphone android.
Il a été testé sur mon téléphone personnel: écran 1080*1920.
Aucun schéma UML n'est fourni car la modélisation est triviale.
Lien du dépot: https://github.com/MartinSanchezIut/Tp2-Android-Capteurs

#### Exo 1:
Ce premier exo vous affiche dans une scrollview l'ensemble des capteurs disponibles sur votre téléphone.

#### Exo 2:
Celui-ci vous affiche les capteurs manquants. Pour cela il teste chaque capteur, en cas d'abscence il vous le signale.

#### Exo 3: Accéléromètre
Ici on utilise l'accéléromètre pour mesurer le déplacement du téléphone.
On découpe la plage des valeurs du capteur en 3 zones :
- Vert -> Le téléphone se déplace lentement.
- Jaune -> Il se déplace à une vitesse modérée.
- Rouge -> Il se déplace rapidement.

La couleur de l'écran change en fonction de la vitesse de déplacement du téléphone.
A noter que la plage du capteur a été divisé par 2, pour permetre des tests plus faciles.

#### Exo 4: Accéléromètre
Sur cet exo, on se sert de l'accéléromètre pour définir l'orientation du téléphone.
Les 3 valeurs d'orientation (x, y, z) sont affichés a l'écran ainsi qu'une fleche montrant l'orientation du téléphone.
Cette fleche disparaît lorsque le téléphone est posé à l'horizontale.

#### Exo 5: Accéléromètre
Sur cet exo, on se sert (encore) de l'accéléromètre pour détecter une agitation du téléphone.
Cette agitation déclenche le flash.
Nous avons besoin de la permission pour la caméra.

#### Exo 6: Proximité
Pour cet exercice nous utilisons le capteur de proximité du téléphone pour afficher si il est loin ou non d'un objet.
Si aucun objet n'est détecté par le capteur on affiche 'LOIN' à l'écran.
Si un objet est detecté on affiche 'Proche'.

#### Exo 7: Localisation
Pour cet exercice on utilise la fonction 'Localisation' du téléphone.
Nous avons besoin de la permission d'utiliser la localisation et internet.
Ici on affiche simplement la latitude et la longitude a l'écran.
