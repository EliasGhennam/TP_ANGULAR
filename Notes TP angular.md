Notes de l'avancement TP ANGULAR :

TODO 1, TODO 3 & TODO 4 :

Le problématique rencontré est l'usage d'un href, qui fonctionnerait sur d'autres framework mais n'est pas fonctionnel avec le framework Angular pour réaliser des navigations. Il faut faire l'usage de la directive "routerLink" pour réaliser cette tâche en Angular.En parallèle, il faut également faire attention au routage réaliser au préalable dans app.routes.ts et correctement réalisé l'importation de RouterModule dans AppModule.

TODO 2 :

Installer un pipe, en l'occurence CapitalizeFirst :
	"ng generate pipe capitalizeFirst"
Cela nous créer deux éléments : "nom-de-notre-pipe.spec.ts" et "nom-de-notre-pipe.ts".
On modifie par la suite le contenu de notre Pipe pour le faire correspondre à la logique souhaité, dans le cas échéant, le premier mot en majuscule avec words.toUpperCase et le resste en minuscule avec restWords = words [...] word.toLowerCase.


TODO 5 :

L'affichage d'un component avec l'adaptation de sa route avec la spécification de l'identifiant de l'élément ("id"). En faisant une recherche avec localhost:4200/books/3 on tombe bien sur un livre et son contenu lorsque la route est correctement rétabli.

