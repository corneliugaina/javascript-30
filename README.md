# javascript-30

[30 Day Vanilla JS Coding Challenge](https://javascript30.com)  
No Frameworks × No Compilers × No Libraries × No Boilerplate

[wesbos repository - JavaScript30](https://github.com/wesbos/JavaScript30)

Marathon de 30 mini-projets en JavaScript pur.  
L'auteur du challenge veut qu'on prenne l'habitude de saisir chaque temps libre possible pour faire une tache ici ou la. Donc, pas necessairement rusher tout d'un coup.  

Chacun a une methode differente d'apprendre, c'est a soi de voir ce qui fonctionne le mieux (cela nous aidera le mieux) :  

- on peut visionner la video d'un coup puis faire le projet directement,
- on peut voir la video par petits bouts avec du recul,
- on peut voir des extraits et coder tout seul la suite lorsqu'on a compris,
- enfin, on peut faire du mimetisme, bout par bout, en codant en meme temps que l'auteur (recommande)

Il y a differentes manieres d'accomplir les mini-projets. C'est normal d'essayer autrement.  

## 1 - JavaScript Drum Kit (fin 25 mars 2019)

Realiser une batterie virtuelle sur une page HTML... en JavaScript. Chaque touche est associee a un son et le declenchement d'evenements par des scripts lance le son correspondant.  
Sur un clavier, chaque touche a un keycode (1 a 3 chiffres) pouvant etre utilises pour l'appel d'une fonction ou d'un evenement.  
Pour cet exercice, il a fallu creer une fonction sur l'objet Window, et qui etait appelle selon la touche selectionnee sur le clavier QWERTY (A - L).  
Chaque touche/son ainsi joue est accompagne d'une transition CSS, mettant en subrillance le bouton. Apres la transition, le bouton revenait a l'etat initial.  
Le plus difficile etait de comprendre comment articuler la fonction qui appellait le son et l'animation visuelle du bouton (transition).  

CSS: 
transform,
transition,

JS: 
addEventListener,
querySelector,
keycodes,
audio.play(),
forEach

## 2 - Javascript / CSS Clock ( fin 28 mai 2019) 

Réaliser une horloge en JS/CSS avec les aiguilles - seconde/minute/heure - qui bougent sur un axe.

CSS : 
transition, 
transition-timing-function, 
transform, 
cubic-bezier.

JS: 
function setDate(), 
querySelector, 
playing with time + degrees, 
template litteral, 
setInterval, 

## 3 Update CSS with Javascript

Nommer et appliquer des variables sur des propriétés CSS. Ici l'exercice des de construire des slides pour modifier des propriétés manuellement sur le navigateur. 

CSS: 
filter, 
blur, 
spacing.

JS: 
QuerySelectorAll, 
setProperty, 
forEach, 
addEventListener.

## 4 Array Cardio Day 1

Workout sur les Array (tableaux) en javascript, travail seulement sur la console donc. 

CSS: /

JS: 
.filter(), 
.map(), 
.sort(), 
.reduce(),

## 5 Flex Panel Gallery

Une gallerie de panneaux disposés en flex, qui s'étendent au clic. Intéressant pour une implémentation dans un site avec disposition de contenus.

CSS:
flex,
transform (translateY),
nth-child,


JS:
toggle
(querySelector, forEach, event listener,...)


## 6 Ajax Type Ahead 

Barre pour recherche parmi 1000 plus grandes villes américaines (avec leur Etat et population). Difficulté à comprendre; revoir les fonctions, DOM, ajax, fetch et les expressions régulières. 

CSS: 

JS: .map , querySelector, eventListener, .replace, ${template litterals}, .filter, RegEx.
