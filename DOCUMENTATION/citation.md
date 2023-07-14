# Choix de projet : Citations pour tous (Citation.vue)
Une belle citation, ça fait toujours du bien. Ce component affiche une citation et son auteur. La citation change quand on clique dessus.

## Affichage
Le component doit présenter l'image dans un élément `blockquote`. L'image doit être dans un élément `img`. L'image doit dans un lien qui mène à la page de l'annonceur.

Il y a deux formats de publicité : 728x90 et 300x250. Vous choisissez le format que vous voulez. Vous pouvez également permettre au component parent de déterminer le format.

## Les props (ce qu'il reçoit)
Le component peut recevoir à votre choix :
1. Soit __un__ tableau d'__objets__ qui contient les informations sur les citations à afficher, c'est-à-dire l'__auteur__ et le __texte__ de la citation.
2. Soit __deux__ tableaux de __chaines de caractères__, un pour les auteurs et un pour les textes.

La première option est plus robuste et devrait être favorisée.

## À quoi il réagit
Lorsque l'utilisateur clique sur la citation, le component doit afficher à votre choix : 
   - la citation suivante. Si la citation affichée est la dernière de la liste, le component doit afficher la première citation de la liste.
   - une citation aléatoire.

## Ce qu'il émet
Le component parent n'a pas besoin de s'en servir, mais le component doit émettre un événement lorsqu'il change de citation. L'événement doit envoyer au minimum le texte de la nouvelle citation.

## Ce que je fournis
Je fournis une liste de citations fictives amusantes crées par ChatGPT.

## Contenu

| Auteur              | Citation                                                                                                                                                                      |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Albert Einstein     | La vie, c'est comme une bicyclette, il faut avancer pour ne pas se faire dépasser... sauf si vous avez un hoverboard !                                                        |
| Albert Einstein     | La logique vous mènera de A à B. L'imagination vous emmènera partout... ou vous fera passer des heures sur TikTok !                                                           |
| Frank Sinatra       | La meilleure vengeance est un succès écrasant... ou un bon mème sur les réseaux sociaux !                                                                                     |
| Leonardo da Vinci   | La simplicité est la sophistication suprême... à moins que vous ne soyez un expert en origami.                                                                                |
| Peter Drucker       | La meilleure façon de prédire l'avenir, c'est de le créer... ou d'acheter une boule de cristal sur eBay !                                                                     |
| Truman Capote       | L'échec est le condiment qui donne de la saveur au succès... tout comme le ketchup sur les frites !                                                                           |
| Vidal Sassoon       | Le seul endroit où le succès vient avant le travail, c'est dans le dictionnaire... et sur Amazon avec livraison en un jour !                                                  |
| Walt Disney         | Si vous pouvez le rêver, vous pouvez le faire... ou tout simplement le rechercher sur YouTube et voir si quelqu'un d'autre l'a déjà fait !                                    |
| Winston Churchill   | Le succès, c'est d'aller d'échec en échec sans perdre son enthousiasme... ou de jouer à Mario Kart et de faire un tour parfait à chaque fois !                                |
| Coco Chanel         | Le temps qui passe ne se rattrape jamais... sauf si vous jouez à un jeu vidéo avec une machine à remonter le temps !                                                          |
| Malala Yousafzai    | L'éducation est l'arme la plus puissante pour changer le monde... ou le meilleur moyen d'apprendre à tricher aux quiz en ligne !                                              |
| Sénèque             | La vie, ce n'est pas d'attendre que l'orage passe, c'est d'apprendre à danser sous la pluie... ou d'investir dans un bon parapluie anti-tempête !                             |
| Albert Einstein     | La créativité, c'est l'intelligence qui s'amuse... ou qui trouve des excuses pour ne pas faire le ménage !                                                                    |
| Ralph Waldo Emerson | Le bonheur est un parfum que vous ne pouvez pas verser sur les autres sans en mettre un peu sur vous... ou en utilisant un bon diffuseur d'huiles essentielles !              |
| Pablo Picasso       | Tout ce que vous pouvez imaginer est réel... sauf les licornes, elles existent vraiment !                                                                                     |
| Oscar Wilde         | La beauté est dans les yeux de celui qui regarde... ou dans l'application de filtres sur Instagram !                                                                          |
| Nelson Mandela      | Le courage, c'est de ne pas baisser les bras, mais de continuer à avancer... ou de commander de la nourriture en ligne lorsqu'il pleut !                                      |
| Steve Jobs          | La seule façon de faire du bon travail est d'aimer ce que vous faites... ou de le déléguer à quelqu'un d'autre et de prendre une sieste !                                     |
| Winston Churchill   | La persévérance est la clé de la réussite... ou une excuse pour ne pas plier la montagne de linge qui s'accumule !                                                            |
| Confucius           | Le succès, c'est tomber sept fois et se relever huit... ou juste porter des genouillères !                                                                                    |
| Victor Hugo         | La grandeur n'est pas d'être fort, mais d'utiliser sa force de manière juste... ou de soulever des paquets de chips jusqu'à la bouche !                                       |
| John Lennon         | La vie est ce qui arrive pendant que vous êtes occupé à faire d'autres plans... ou à parcourir les recommandations sur Netflix sans jamais trouver quelque chose à regarder ! |
| Albert Camus        | Le bonheur ne dépend pas de ce qui vous arrive, mais de la façon dont vous choisissez de le vivre... ou de la quantité de glace dans votre cornet !                           |
| Albert Einstein     | La folie, c'est de faire la même chose encore et encore en espérant des résultats différents... ou de manger une autre part de gâteau en espérant ne pas prendre de poids !   |
| Aristote            | Le secret du succès, c'est de savoir quelque chose que personne d'autre ne sait... ou de faire semblant et d'utiliser Google discrètement !                                   |
