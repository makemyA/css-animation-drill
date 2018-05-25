# Aide mémoire sur les animations

name: the animation’s name
duration: how long the transition lasts
timing-function: how the intermediate states are calculated
delay: to start the animation after a certain amount of time
iteration-count: how many times the animation should be performed
direction: if the animation should be reversed or not
fill-mode: what styles are applied before the animation starts and after it ends

**Important:**

Si on veut faire une loop: Toujours revenir à la position initiale dans le keyframes.
Donc, 0% = 100%

Delay= temps avant de lancer l'animation


# Etapes

1. Créer div dans html




1. Créer le style de notre div en css

```html
div {
    width: 100px;
    height: 50px;
    background-color: red;
    font-weight: bold;
    position: **relative**
    animation-name:
    ```
1. Composer le keyframe de notre animation