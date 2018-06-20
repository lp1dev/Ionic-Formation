# Trivia App

Maintenant que nous avons vue la théorie par rapport à l'utilisation du Framework Ionic,
il est temps de passer à la pratique !

Le projet que vous allez réaliser est une application de quizz, permettant aux utilisateurs de répondre à des question,
chaque bonne réponse trouvée ajoutera 10 points à son score et chaque réponse fausse retirera 10 points à celui-ci.

Une partie est composée de 20 questions, auxquelles il faut répondre le plus rapidement possible.

## Communication avec des APIs

Les questions doivent être récupérées sur https://opentdb.com/api_config.php.
 
À la fin de la partie, le score et le temps de la partie doivent pouvoir (soit automatiquement, soit au choix de l'utilisateur) être partagés sur le leaderboard global contenant l'ensemble des scores des joueurs identifiés par leur nickname.
Ce leaderboard est accessible sur http://leaderboard.lp1.eu.

À chaque nom d'utilisateur devra de base être associé un avatar différent, vous pouvez utiliser http://avatars.adorable.io/ pour générer des avatars. Il devra également être possible d'uploader son propre avatar directement depuis la gallerie de son appareil.

## Fonctionnalités Obligatoires

Il est nécessaire de pouvoir enregistrer son nom d'utilisateur (ou nickname) dans l'application.

Celui-ci doit être conservé au redémarrage de l'application.

Il doit également être possible d'ajouter un avatar depuis la gallerie de l'appareil mobile.
Dans le cas où aucun avatar n'aurait été choisi, celui-ci doit être remplacé par un avatar pseudo-aléatoire.

Vous pouvez réaliser autant d'écrans que vous jugez nécessaire **tant que votre application est simple à utiliser**.

Les questions seront affichées à l'écran une par une, et les points, ainsi que le temps affichés et mis à jour en temps réel sur l'affichage.

Il doit également être possible de jouer en mode "hors-ligne" au jeu sur un nombre plus limité de questionn.
Le score et le temps, en fin de partie doit être sauvegardé malgré l'abscence de connexion et envoyé au retour de celle-ci.

## Critères de notation

En premier lieu, la présence et la qualité de l'implémentation des fonctionnalités sera prise en compte.

L'UI doit être simple à utiliser et cohérente visuellement, les différentes vues que vous réaliserez se doivent également d'être fonctionnelles quelle que soit le type d'appareil/la taille d'écran utilisée.

L'architecture des fichiers et du code de votre projet devra, même si elle ne doit pas coller parfaitement à un modèle architectural être claire et représenter les fonctionnalités et leurs relations au sein de votre projet.

La présence de tests et leur pertinence seront également comptabilisés.

## Bonus Possibles

En bonus, une fois que vous avez terminé l'ensemble des autres fonctionnalités vous pouvez ajouter de la lecture en text-to-speech des questions.

Il est également possible de vous interfacer avec d'autres APIs si vous avez des idées de nouvelles fonctionnalités.

