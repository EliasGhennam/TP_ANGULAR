Notes de l'avancement TP ANGULAR :

TODO 1, TODO 3 & TODO 4 :

Le problématique rencontré est l'usage d'un href, qui fonctionnerait sur d'autres framework mais n'est pas fonctionnel avec le framework Angular pour réaliser des navigations. Il faut faire l'usage de la directive "routerLink" pour réaliser cette tâche en Angular.En parallèle, il faut également faire attention au routage réaliser au préalable dans app.routes.ts et correctement réalisé l'importation de RouterModule dans AppModule.

Les concepts Angular utilisées dans cette partie sont l'usage des bon routing RouterLink et RouterOutlet. La configuration des routes avec le provideRouter, la gestion du fallback avec { path:'**', redirectTo: ''}

TODO 2 :

Installer un pipe, en l'occurence CapitalizeFirst :
	"ng generate pipe capitalizeFirst"
Cela nous créer deux éléments : "nom-de-notre-pipe.spec.ts" et "nom-de-notre-pipe.ts".
On modifie par la suite le contenu de notre Pipe pour le faire correspondre à la logique souhaité, dans le cas échéant, le premier mot en majuscule avec words.toUpperCase et le reste en minuscule avec restWords = words [...] word.toLowerCase.

Les concepts Angular présent ici sont l'importation et l'usage correct de standalone: true, l'usage d'un @Pipe, personnalisé avec PipeTransform, les directives Angular qui prédominent le HTML classique -> routerLink, routerOutlet. La gestion des imports: [...].


TODO 5 :

L'affichage d'un component avec l'adaptation de sa route avec la spécification de l'identifiant de l'élément ("id"). En faisant une recherche avec localhost:4200/books/3 on tombe bien sur un livre et son contenu lorsque la route est correctement rétabli.

Les concepts Angular étudié sont le routing par id, l'usage de RouterOutlet pour un affichage fonctionnel des pages, la bonne configuration visuelle de chargement de notre site: "standalone: true".

TODO 6 & 7 :

Création de formulaire spécifique et validation conditionnel. Pour faire fonctionner correctement notre form, il fallait créer un reactive form depuis le add-book.component.ts.
Par la suite il fallait bien incrémenter le code présent dans le html pour faire fonctionner la validation ainsi que le message d'erreur lorsque les conditions ne sont pas remplis.

Les concepts Angular présent dans ces TODO sont les FormGroup (éléments de formulaires), les formControlName (La liaison des champs), et l'usage de *ngIf (Pour réaliser le conditionnel).

TODO 8 :

Création d'un moyen de retourner à la page précédente lors de l'usage de la fonction "goBack", dans le cas échéant, utilisés dans book-detail.component.html

Concepts clés : L'usage de l'évenement (click) sur le template, l'usage et la configuration de la navigation avec Router.

TODO 9 :

Ajout d'une condition pour l'affichage de book pour résoudre le problème d'affichage avant l'initialisation de l'objet book. Avec *ngIf="book", l'affichage ne se fait qu'une fois l'objet chargé.

Concepts Angular :

Usage de la directive *ngIf, gestion des données asynchrones.

TODO 10 :

Dans ce TODO, l'objectif était d'appliquer une directive personnalisé à un champ, dans le cas échéant le <h1> de notre book detail component. Il fallait donc à la fois modifier le contenu de highlight.directive.ts, l'importer correctement ainsi que l'appeler dans notre html.

Les concepts clés Angular : usage de directives personnalisés : @Directive, manipulation du DOM avec Renderer2.

TODO 11 :








