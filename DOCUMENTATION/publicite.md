### Choix de projet : Pub à gogo (Publicite.vue)
Afficher une publicité, c'est payant. Ce component affiche une publicité aléatoire parmi une liste de publicités. Après un certain temps, la publicité change. 

![Exemple de publicité](publicite.png)

> ATTENTION! Les bloqueurs de publicité peuvent bloquer votre component. Vous devrez le désactiver.

#### Affichage
Le component doit présenter l'image dans un élément `div`. L'image doit être dans un élément `img`. L'image doit dans un lien qui mène à la page de l'annonceur.

Il y a deux formats de publicité : 728x90 et 300x250. Vous choisissez le format que vous voulez. Vous pouvez également permettre au component parent de déterminer le format.

#### Les props (ce qu'il reçoit)
Le component peut recevoir à votre choix :
1. Soit __un__ tableau d'__objets__ qui contient les informations sur les publicités à afficher, c'est-à-dire le `src` de l'image et le `href` du lien.
2. Soit __deux__ tableaux de __chaines de caractères__, un pour les `src` et un pour les `href`.

La première option est plus robuste et devrait être favorisée.

#### À quoi il réagit
À interval régulier, le component doit afficher une nouvelle publicité aléatoire.

#### Ce qu'il émet
Le component parent n'a pas besoin de s'en servir, mais le component doit émettre un événement lorsqu'il change de publicité. L'événement doit envoyer au minimum le `href` de la nouvelle publicité.

#### Ce que je fournis
Je fournis une liste d'images et d'adresses.

# Le contenu

| src pour l'image            | href pour le lien                                                             |
| --------------------------- | ----------------------------------------------------------------------------- |
| adventuregetaway.webp       | https://adventuregetaway.com/tours/summer2023/index.html                      |
| deliciousbitescooking.webp  | https://deliciousbitescooking.com/recipes/maincourses/italian/pasta.html      |
| petparadiseworld.webp       | https://petparadiseworld.com/petcare/dogbreeds/goldenretriever.html           |
| dreamvacationspot.webp      | https://dreamvacationspot.com/destinations/caribbean/beachresorts/index.html  |
| fitnessrevolutiongym.webp   | https://fitnessrevolutiongym.com/programs/workouts/cardio/intense/index.html  |
| techwizardpro.webp          | https://techwizardpro.com/productreviews/latestgadgets/2023/index.html        |
| homeimprovementmasters.webp | https://homeimprovementmasters.com/ideas/interiordesign/livingroom/index.html |
| gamingfantasyland.webp      | https://gamingfantasyland.com/games/rpg/fantasy/quests.html                   |
| bookwormparadise.webp       | https://bookwormparadise.com/genres/fiction/mystery/novels.html               |
| musicmelodies.webp          | https://musicmelodies.com/artists/genres/pop/songs/index.html                 |
| traveldiscoveries.webp      | https://traveldiscoveries.com/destinations/europe/italy/cities/rome.html      |
| homecookingdelights.webp    | https://homecookingdelights.com/recipes/desserts/chocolate/cake.html          |
| mindfulmeditations.webp     | https://mindfulmeditations.com/practices/meditation/mindfulness/benefits.html |
