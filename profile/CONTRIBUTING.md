# Contribution à RUDI

Tout d'abord, merci de prendre le temps de contribuer ! ❤️

Tous types de contributions sont encouragés et valorisés. Consultez la [Table des matières](#table-des-matières) pour découvrir les différentes façons d'aider et les détails sur la façon dont ce projet les gère. Veuillez vous assurer de lire la section pertinente avant de faire votre contribution. Cela facilitera la tâche des responsables du projet et rendra l'expérience plus fluide pour tous les participants. La communauté attend avec impatience vos contributions. 🎉

> Si vous aimez le projet mais que vous n'avez tout simplement pas le temps de contribuer, aucun souci. Il existe d'autres moyens faciles de soutenir le projet et de montrer votre appréciation, par exemple :
> - Ajoutez une étoile au projet
> - Parlez de RUDI autour de vous
> - Mentionnez le projet dans le readme de votre projet

## Liens externes et internes utiles

- [J'ai une question](#jai-une-question)
- [Contributions techniques](#contributions-techniques)
  - [Signalement de bugs](#signaler-des-bugs)
  - [Guides de style](#guides-de-style)
  - [Messages de commit](#messages-de-commit)
- [Contributions non-techniques](#contributions-non-techniques)
  - [Propositions d'améliorations](#propositions-daméliorations)
  - [Votre première contribution de code](#votre-première-contribution-de-code)
  - [Amélioration de la documentation](#amélioration-de-la-documentation)
  - [Traductions](#traductions)


## J'ai une question

> Si vous avez une question, nous supposons que vous avez lu la [section dédiée](https://github.com/orgs/Rudi-pages-WIP/discussions/categories/questions-et-r%C3%A9ponses).

Avant de poser une question, il est préférable de rechercher des [questions et réponses](https://github.com/orgs/Rudi-pages-WIP/discussions/categories/questions-et-r%C3%A9ponses) existantes qui pourraient vous aider. Si vous avez trouvé une question liée mais vous avez encore besoin de clarification, vous pouvez poser votre question dans les commentaires de la discussion. 

Si vous avez toujours besoin de poser une question et d'obtenir des éclaircissements, nous vous recommandons ce qui suit :
- Ouvrez une [discussion dans la section Questions et Réponses](https://github.com/orgs/Rudi-pages-WIP/discussions/categories/questions-et-r%C3%A9ponses).
- Fournissez autant de contexte que possible sur ce que vous rencontrez.
- Fournissez les versions du projet et de la plateforme (nodejs, npm, etc.), en fonction de ce qui semble pertinent.

## Contributions techniques

### Signaler des bugs

#### Avant de soumettre un rapport de bug

Un bon rapport de bug ne doit pas laisser les autres vous courir après pour plus d'informations. Par conséquent, nous vous demandons d'enquêter soigneusement, de recueillir des informations et de décrire le problème en détail dans votre rapport. Veuillez compléter les étapes suivantes à l'avance pour nous aider à corriger tout bug potentiel le plus rapidement possible.

- Assurez-vous d'utiliser la dernière version.
- Déterminez si votre bug est vraiment un bug et non une erreur de votre côté, par exemple en utilisant des composants/versions d'environnement incompatibles (Assurez-vous d'avoir lu la [documentation](). Si vous cherchez de l'aide, vous pouvez consulter [cette section](https://github.com/orgs/Rudi-pages-WIP/discussions/categories/questions-et-r%C3%A9ponses)).
- Pour voir si d'autres utilisateurs ont rencontré (et éventuellement déjà résolu) le même problème que vous rencontrez, vérifiez s'il n'y a pas déjà un rapport de bug existant pour votre bug ou erreur dans le [bug tracker](issues?q=label%3Abug).
- Collectez des informations sur le bug :
  - Stack trace
  - OS, Plateforme et Version (Windows, Linux, macOS, x86, ARM)
  - Version de l'interpréteur, du compilateur, du SDK, de l'environnement d'exécution, du gestionnaire de packages, selon ce qui semble pertinent.
  - Éventuellement votre entrée et la sortie
  - Pouvez-vous reproduire de manière fiable le problème ? Et pouvez-vous aussi le reproduire avec des versions plus anciennes ?

#### Comment soumettre un bon rapport de bug ?

> Vous ne devez jamais signaler de problèmes liés à la sécurité, de vulnérabilités ou de bugs contenant des informations sensibles sur le bug tracker ou ailleurs en public. Au lieu de cela, les bugs sensibles doivent être envoyés par email à produit@rudi.bzh.

Nous utilisons les issues GitHub pour suivre les bugs et les erreurs. Si vous rencontrez un problème avec le projet :

- Ouvrez une [Issue](/issues/new). (Puisque nous ne pouvons pas être sûrs à ce stade s'il s'agit d'un bug ou non, nous vous demandons de ne pas encore parler de bug et de ne pas étiqueter l'issue.)
- Expliquez le comportement que vous attendiez et le comportement réel.
- Veuillez fournir autant de contexte que possible et décrire les *étapes de reproduction* que quelqu'un d'autre peut suivre pour recréer le problème par lui-même. Cela inclut généralement votre code. Pour de bons rapports de bug, vous devez isoler le problème et créer un cas de test réduit.
- Fournissez les informations que vous avez collectées dans la section précédente.

Une fois que c'est déposé :

- L'équipe du projet étiquettera l'issue en conséquence.
- Un membre de l'équipe essaiera de reproduire le problème avec les étapes que vous avez fournies. S'il n'y a pas d'étapes de reproduction ou pas de moyen évident de reproduire le problème, l'équipe vous demandera ces étapes et marquera l'issue comme `needs-repro`. Les bugs avec l'étiquette `needs-repro` ne seront pas traités tant qu'ils ne sont pas reproduits.
- Si l'équipe est capable de reproduire le problème, il sera marqué `needs-fix`, ainsi que possiblement d'autres étiquettes (comme `critical`), et l'issue sera laissée pour être [implémentée par quelqu'un](#votre-première-contribution-de-code).

### Votre première contribution de code
<!-- TODO
include Setup of env, IDE and typical getting started instructions?

-->
### Guides de style
#### Messages de commit

Chaque message de commit doit être structuré de la manière suivante :

1. **Ligne d'en-tête** : Une ligne résumant les changements (50 caractères maximum).
2. **Ligne vide** : Une ligne vide pour séparer l'en-tête du corps.
3. **Corps du message** : Description détaillée des changements (72 caractères par ligne maximum).
4. **Pied de page** : Informations supplémentaires comme les numéros d'issue, les remerciements, etc.

##### Ligne d'en-tête

- Utilisez l'impératif présent : "Ajoute", "Corrige", "Supprime", etc.
- Soyez bref et précis (50 caractères maximum).
- Utilisez une majuscule au début de la phrase.
- Ne terminez pas par un point.

###### Exemples

- `Ajoute la fonctionnalité de connexion`
- `Corrige le bug de l'affichage des images`
- `Supprime les fichiers obsolètes`

##### Corps du message

- Fournissez un contexte sur la raison du changement.
- Expliquez ce qui a été changé et pourquoi.
- Utilisez des phrases complètes.
- Limitez chaque ligne à 72 caractères pour une meilleure lisibilité.
- Séparez les différents points avec des lignes vides pour plus de clarté.

###### Exemples

```
Ajoute la fonctionnalité de connexion

Cette fonctionnalité permet aux utilisateurs de se connecter à leur
compte en utilisant leur adresse email et leur mot de passe. Elle
inclut la vérification des informations d'identification et la gestion
des sessions utilisateur.

- Ajoute la page de connexion
- Implémente la logique de vérification des identifiants
- Ajoute les tests unitaires pour la connexion

Issue: #123
```

##### Pied de page

- Utilisez le pied de page pour référencer les issues liées.
- Mentionnez les personnes ou les équipes qui ont contribué ou aidé, si nécessaire.
- Utilisez les préfixes `Issue:` ou `Fixes:` pour indiquer les issues associées.

###### Exemples

- `Issue: #123`
- `Fixes: #456`
- `Merci à @nom_utilisateur pour l'aide sur ce commit`

##### Bonnes pratiques

- **Commits atomiques** : Faites des commits petits et spécifiques à une seule fonctionnalité ou correction de bug.
- **Messages significatifs** : Évitez les messages vagues comme "Mise à jour" ou "Correction de bug". Soyez précis sur ce qui a été fait.
- **Consistance** : Maintenez une structure et un style cohérents pour tous les messages de commit.

## Contributions non-techniques

### Suggérer des améliorations

Cette section vous guide à travers la soumission d'une suggestion d'amélioration pour RUDI, **y compris des fonctionnalités complètement nouvelles et des améliorations mineures des fonctionnalités existantes**. Suivre ces directives aidera l'équipe produit à mieux comprendre votre suggestion et à trouver des suggestions connexes.

#### Avant de soumettre une amélioration

- Assurez-vous d'utiliser la dernière version.
- Lisez attentivement la [documentation]() et découvrez si la fonctionnalité n'est pas déjà couverte, peut-être par une configuration individuelle.
- Effectuez une [recherche](https://github.com/orgs/Rudi-pages-WIP/discussions/categories/id%C3%A9es) pour voir si l'amélioration n'a pas déjà été suggérée. Si c'est le cas, ajoutez un commentaire à l'issue existante au lieu d'en ouvrir une nouvelle.
- Déterminez si votre idée correspond à la portée et aux objectifs du projet. Il vous appartient de convaincre les développeurs du projet des mérites de cette fonctionnalité. Gardez à l'esprit que nous voulons des fonctionnalités utiles à la majorité de nos utilisateurs et non seulement à une petite partie. Si vous ciblez juste une minorité d'utilisateurs, envisagez d'écrire une bibliothèque complémentaire/plugin.

#### Comment soumettre une bonne suggestion d'amélioration ?

Les suggestions d'amélioration sont suivies sous forme de [template d'idée](https://github.com/orgs/Rudi-pages-WIP/discussions/categories/id%C3%A9es).

- Utilisez un **titre clair et descriptif** pour l'issue afin d'identifier la suggestion.
- Fournissez une **description étape par étape de l'amélioration suggérée** avec autant de détails que possible.
- **Décrivez le comportement actuel** et **expliquez le comportement que vous vous attendiez à voir à la place** et pourquoi. À ce stade, vous pouvez également indiquer quelles alternatives ne fonctionnent pas pour vous.
- Vous pouvez **inclure des captures d'écran et des GIFs animés** qui vous aident à démontrer les étapes ou à indiquer la partie à laquelle la suggestion est liée. Vous pouvez utiliser [cet outil](https://www.cockos.com/licecap/) pour enregistrer des GIFs sur macOS et Windows, et [cet outil](https://github.com/colinkeenan/silentcast) ou [cet outil](https://github.com/GNOME/byzanz) sur Linux.
- **Expliquez pourquoi cette amélioration serait utile** à la plupart des utilisateurs de RUDI. Vous pouvez également souligner d'autres projets qui l'ont mieux résolu et qui pourraient servir d'inspiration.

### Améliorer la documentation
<!-- TODO
Updating, improving and correcting the documentation

-->

### Traduire RUDI



