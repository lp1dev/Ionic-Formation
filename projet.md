# Trivia App

Maintenant que nous avons vue la théorie par rapport à l'utilisation du Framework Ionic,
il est temps de passer à la pratique !

Le projet que vous allez réaliser est une application de quizz, permettant aux utilisateurs de répondre à des question,
chaque bonne réponse trouvée ajoutera 10 points à son score et chaque réponse fausse retirera 10 points à celui-ci.

## Communication avec des APIs

Les questions doivent être récupérées sur https://opentdb.com/api_config.php.
    
Ce score doit pouvoir (soit automatiquement, soit au choix de l'utilisateur) être partagé sur le leaderboard global contenant l'ensemble des scores des joueurs identifiés par leur nickname.
Ce leaderboard est accessible sur leaderboard.lp1.eu.

À chaque nom d'utilisateur sera associé un avatar, vous pouvez si vous le souhaitez utiliser http://avatars.adorable.io/ pour générer des avatars de base. Il devra également être possible d'uploader son propre avatar directement depuis la gallerie.

## Fonctionnalités Obligatoires

Il est nécessaire de pouvoir enregistrer son nom d'utilisateur ou nickname dans l'application.
Celui-ci doit être conservé au redémarrage de l'appareil.

Il doit également être possible d'ajouter un avatar depuis la gallerie de l'appareil mobile.
Dans le cas où aucun avatar n'aurait été choisi, celui-ci sera remplacé par un avatar aléatoire.

Vous pouvez réaliser autant d'écrans que vous jugez nécessaire.
                
Les questions seront affichées à l'écran une par une, et les points affichés et mis à jour en temps réel

Il doit également être possible de jouer en mode "hors-ligne" au jeu sur un nombre plus limité de questions.
Le score doit être sauvegardé malgré l'abscence de connexion.

## Bonus Possibles

En bonus, une fois que vous avez terminé l'ensemble des autres fonctionnalités vous pouvez ajouter de la lecture en text-to-speech des questions.

Il est également possible de vous interfacer avec d'autres APIs si vous avez des idées de nouvelles fonctionnalités.