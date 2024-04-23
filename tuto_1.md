# Tuto 1

## @showdialog

Crée un écran d'accueil pour un ton premier jeu vidéo!

## Étape 1

Ajoute le bloc ``||scene:définir l'image d'arrière-plan||`` (onglet ``||scene:Scène||``) dans le bloc ``||loops:au démarrage||``.

Choisis une image dans la galerie.

```blocks

scene.setBackgroundImage(mes_atouts.arriereplan)

```

## Étape 2

Ajoute le bloc ``||game:splash||`` (onglet ``||game:Jeu||``) sous le bloc ``||scene:définir l'image d'arrière-plan||``.

Écris le nom du jeu dans le bloc ``||game:splash||``. 

```blocks

scene.setBackgroundImage(mes_atouts.arriereplan)
game.splash("Le Refuge hanté")

```

## Étape 3

Ajoute le bloc ``||scene:démarrer effet sur l'écran||`` (onglet ``||scene:Scène||``) sous le bloc ``||game:splash||``.

Choisis un effet. 

Appuie sur le bouton ``||scene:+||`` et modifie la valeur ``||scene:500||`` par ``||scene:2000||``.

```blocks

scene.setBackgroundImage(mes_atouts.arriereplan)
game.splash("Le Refuge hanté!")
effects.blizzard.startScreenEffect(2000)

```

```package
mes_atouts=github:alex-kulcsar/mes_atouts
```