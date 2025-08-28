## Jeu de la Vie
Un petit simulateur du [Jeu de Conway](https://fr.wikipedia.org/wiki/Jeu_de_la_vie) codé en Java.

## Technologies

- Java SDK 21.
- [JavaFX 21.0.3](https://openjfx.io/) - pour l'interface graphique.
- [Maven 3.9.6](https://maven.apache.org) - comme modèle.

## Commencer
D'abord, cette application utilise ce [plugin Maven](https://github.com/openjfx/javafx-maven-plugin) pour gérer tout ce qui concerne JavaFX :

- **NOTE :** Je recommande d'utiliser **IntelliJ IDE** au cas où vous auriez des problèmes pour télécharger toutes les dépendances avec **Eclipse IDE**.
- Installez les dépendances Maven.
- Utilisez `mvn clean javafx:run` pour exécuter en localhost.
- Utilisez `mvn clean javafx:jlink` pour générer un exécutable dans le dossier `/target` (lisez la documentation du plugin si vous n'êtes pas sûr).

## Comment jouer ?
- Utilisez le clic gauche pour placer une cellule verte (vivante), vous pouvez utiliser des motifs de [Wikipedia](https://fr.wikipedia.org/wiki/Jeu_de_la_vie).
- Une fois que vous pensez que c'est prêt, appuyez simplement sur le bouton "Démarrer le jeu" pour générer les motifs.

## Références
- [Documentation officielle JavaFX](https://openjfx.io/openjfx-docs/)
- [Motifs épiques dans le jeu de Conway](https://www.youtube.com/watch?v=C2vgICfQawE)
- [Exécuter une app JavaFX avec le plugin Maven](https://github.com/openjfx/javafx-maven-plugin?tab=readme-ov-file#javafxrun-options)
- [Créer un fichier exécutable avec le plugin Maven](https://github.com/openjfx/javafx-maven-plugin?tab=readme-ov-file#javafxjlink-options)
