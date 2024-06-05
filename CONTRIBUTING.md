# Contribution à RUDI

Tout d'abord, merci de prendre le temps de contribuer ! ❤️

Tous types de contributions sont encouragés et valorisés. Consultez la [Table des matières](#table-des-matières) pour découvrir les différentes façons d'aider et les détails sur la façon dont ce projet les gère. Veuillez vous assurer de lire la section pertinente avant de faire votre contribution. Cela facilitera la tâche des responsables du projet et rendra l'expérience plus fluide pour tous les participants. La communauté attend avec impatience vos contributions. 🎉

> Si vous aimez le projet mais que vous n'avez tout simplement pas le temps de contribuer, aucun souci. Il existe d'autres moyens faciles de soutenir le projet et de montrer votre appréciation, par exemple :
> - Ajoutez une étoile au projet
> - Parlez de RUDI autour de vous
> - Mentionnez le projet dans le readme de votre projet

## Table des matières

- [J'ai une question](#jai-une-question)
- [Je veux contribuer](#je-veux-contribuer)
- [Signalement de bogues](#signalement-de-bogues)
- [Propositions d'améliorations](#propositions-daméliorations)
- [Votre première contribution de code](#votre-première-contribution-de-code)
- [Amélioration de la documentation](#amélioration-de-la-documentation)
- [Guides de style](#guides-de-style)
- [Messages de commit](#messages-de-commit)
- [Rejoindre l'équipe du projet](#rejoindre-léquipe-du-projet)

## J'ai une question

> Si vous avez une question, nous supposons que vous avez lu la [section dédiée](https://github.com/orgs/Rudi-pages-WIP/discussions/categories/questions-et-r%C3%A9ponses).

Avant de poser une question, il est préférable de rechercher des [questions et réponses](https://github.com/orgs/Rudi-pages-WIP/discussions/categories/questions-et-r%C3%A9ponses) existantes qui pourraient vous aider. Si vous avez trouvé une question liée mais vous avez encore besoin de clarification, vous pouvez poser votre question dans les commentaires de la discussion. 

Si vous avez toujours besoin de poser une question et d'obtenir des éclaircissements, nous vous recommandons ce qui suit :
- Ouvrez une [discussion dans la section Questions et Réponses](https://github.com/orgs/Rudi-pages-WIP/discussions/categories/questions-et-r%C3%A9ponses).
- Fournissez autant de contexte que possible sur ce que vous rencontrez.
- Fournissez les versions du projet et de la plateforme (nodejs, npm, etc.), en fonction de ce qui semble pertinent.

## Je veux contribuer

> ### Note légale importante
> Lorsque vous contribuez à ce projet, vous devez accepter que vous avez rédigé 100 % du contenu, que vous avez les droits nécessaires sur le contenu et que le contenu que vous contribuez peut être fourni sous la licence du projet.

### Signalement de bogues

#### Avant de soumettre un rapport de bogue

Un bon rapport de bogue ne devrait pas nécessiter que d'autres personnes vous demandent plus d'informations. Par conséquent, nous vous demandons d'enquêter soigneusement, de collecter des informations et de décrire le problème en détail dans votre rapport. Veuillez suivre les étapes suivantes à l'avance pour nous aider à corriger tout bogue potentiel le plus rapidement possible.

- Assurez-vous d'utiliser la dernière version.
- Déterminez si votre bogue est vraiment un bogue et non une erreur de votre part, par exemple en utilisant des composants/versions d'environnement incompatibles (Assurez-vous d'avoir lu la documentation technique pertinente. 
- Pour voir si d'autres utilisateurs ont rencontré (et éventuellement déjà résolu) le même problème que vous, vérifiez s'il existe déjà un rapport de bogue pour votre bogue ou votre erreur dans le [tracker de bogues](issues?q=label%3Abug).
- Collectez des informations sur le bogue :
- Stack trace
- OS, Plateforme et Version (Windows, Linux, macOS, x86, ARM)
- Version de l'interpréteur, du compilateur, du SDK, de l'environnement d'exécution, du gestionnaire de paquets, en fonction de ce qui semble pertinent.
- Pouvez-vous reproduire le problème de manière fiable ? Et pouvez-vous aussi le reproduire avec des versions plus anciennes ?

#### Comment soumettre un bon rapport de bogue ?

> Vous ne devez jamais signaler de problèmes liés à la sécurité, de vulnérabilités ou de bugs contenant des informations sensibles sur le tracker de bugs, ou ailleurs en public. Au lieu de cela, les bogues sensibles doivent être envoyés par e-mail à produit@rudi.bzh.

Nous utilisons les issues GitHub pour suivre les bugs et les erreurs. Si vous rencontrez un problème avec le projet :

- Ouvrez une [Issue](/issues/new). (Comme nous ne pouvons pas être sûrs à ce stade s'il s'agit d'un bogue ou non, nous vous demandons de ne pas parler d'un bogue pour l'instant et de ne pas étiqueter l'issue.)
- Expliquez le comportement que vous attendiez et le comportement réel.
- Veuillez fournir autant de contexte que possible et décrire les *étapes de reproduction* que quelqu'un d'autre peut suivre pour recréer le problème par lui-même. Pour de bons rapports de bogue, vous devez isoler le problème et créer un cas de test réduit.
- Fournissez les informations que vous avez collectées dans la section précédente.

Une fois l'issue créée :

- L'équipe du projet étiquettera l'issue en conséquence.
- Un membre de l'équipe tentera de reproduire le problème avec les étapes que vous avez fournies. S'il n'y a pas d'étapes de reproduction ou aucune manière évidente de reproduire le problème, l'équipe vous demandera ces étapes et marquera l'issue comme `needs-repro`. Les bugs avec l'étiquette `needs-repro` ne seront pas traités
