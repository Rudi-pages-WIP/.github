<br>
<p align="center">
  <a href="https://rudi.rennesmetropole.fr/">
  <img src="https://blog.rudi.bzh/wp-content/uploads/2020/11/logo_bleu_orange.svg" width=100px alt="Rudi logo" />  </a>
</p>

<h2 align="center" >Plateforme de partage de données à l'échelle locale</h3>
<p align="center">Open source, sécurisée, conçue pour les données ouvertes et à accès restreint.</p>

<p align="center"><a href="https://rudi.rennesmetropole.fr/">🌐 Instance de Rennes Métropole</a> · <a href="doc.rudi.bzh">📚 Documentation</a> ·  <a href="https://blog.rudi.bzh/">📰 Blog</a><p>
<div align="center">
  <a href="https://indd.adobe.com/view/publication/a4f45cc2-760c-4cad-a6e8-139236ace5c0/n7s8/publication-web-resources/pdf/expo_rudi_web.pdf" 
     aria-label="Cliquez pour voir la publication complète en PDF"
     title="Publication PDF">
    <img 
      src="https://github.com/user-attachments/assets/7a967526-9fcb-4bf7-8ead-b1b5b7494d7b" 
      alt="Aperçu de la publication montrant la mise en page du document" 
      width="800"
    />
  </a>
</div>
<div align="center">
  <sub>
    <i>Cliquez sur l'image ci-dessus pour consulter le document PDF complet (s'ouvre dans un nouvel onglet)</i>
  </sub>
</div>

<br>


Nous voulons permettre aux acteurs locaux de partager facilement et en toute sécurité leurs données tout en en gardant la maîtrise et d’accéder en un même point à de nombreuses données du territoire, pour permettre la création et l’amélioration de services numériques basés sur une gestion responsable et éthique des données.

<br>


## Essayer Rudi 
Vous pouvez voir à quoi ressemble une plateforme de Rudi sur la plateforme de <a href="https://rudi.rennesmetropole.fr/">Rennes Métropole</a>

Vous pouvez aussi lancer Rudi en local en 4 commandes :

```
git clone https://github.com/rudi-plateform/rudi-oob.git
cd rudi-oob
git lfs pull
docker compose -f .\docker-compose-magnolia.yml -f .\docker-compose-rudi.yml -f .\docker-compose-dataverse.yml -f .\docker-compose-network.yml --profile "*" up -d
```

[En savoir plus sur Rudi Out of the Box](https://github.com/rudi-platform/rudi-out-of-the-box)

<br>

## Pourquoi choisir Rudi ?

Nous savons qu'il y a beaucoup de logiciels de gestion de données. Alors pourquoi Rudi ?

#### 🔒 Pour les producteurs de données
*Partager leurs données en toute sécurité et en garder la maîtrise*

- Chaque producteur dispose d'un espace (nœud producteur) pour publier ses données dans le catalogue Rudi
- Rudi est une fédération décentralisée : les données restent chez chaque producteur
- Les « données en accès restreint » sont accessibles selon des conditions définies par le producteur
- Pour y accéder, un réutilisateur doit :
  - Décrire son projet dans Rudi
  - Envoyer une demande au producteur qui peut l'accepter ou la refuser

#### 📊 Pour les réutilisateurs de données
*Accéder facilement aux données du territoire pour créer des services*

- Un accès facilité à la donnée territoriale via un méta-catalogue
- Description des données (métadonnées) accessible à tous dans un catalogue central

#### 🎨 Pour les habitants et usagers
*Bénéficier de services numériques basés sur une gestion responsable et éthique des données*

- Fonctionnalités pour connaître et agir sur ses données personnelles détenues par les producteurs
- Système de consentement pour autoriser l'utilisation des données par un tiers
- Bénéfices :
  - Création de services personnalisés
  - Réalisation d'études et analyses plus précises
  - Alimentation d'observatoires

<br>


<br>

## Repositories

### [Rudi Portal 🧑‍💻](https://github.com/Rudi-pages-WIP/Rudi-Portal)

Le portail principal de RUDI est une application web permettant aux utilisateurs de :

- **Explorer le catalogue** : Accéder à une vaste collection de jeux de données.
- **Publier et consulter les réutilisations** : Partager et examiner comment les données sont réutilisées.
- **Formuler des demandes d'accès spécifiques** : Faire des demandes d'accès à des données non ouvertes.
- **Fonctionnalités self-data** : Offrir des outils et fonctionnalités permettant aux utilisateurs de gérer directement leurs données personnelles.

### [Rudi Producer Node 🔨](https://github.com/Rudi-pages-WIP/Rudi-Producer-Node)

L'application dédiée aux producteurs de données leur permet de :

- **Décrire leurs jeux de données** : Fournir des descriptions détaillées pour chaque ensemble de données.
- **Stocker les jeux de données** : Si besoin, permettre le stockage des jeux de données.
- **Fixer les conditions d’accès** : Définir des conditions spécifiques pour l'accès aux données.
- **Publier les métadonnées sur le portail** : Rendre les métadonnées accessibles via le portail principal.

> **Note**: Pour des guides d'utilisation détaillés, des tutoriels, un glossaire, des spécifications techniques et des bonnes pratiques, consultez notre [Rudi Documentation 📑](https://github.com/Rudi-pages-WIP/Rudi-Documentation). Vous pouvez aussi retrouver la documentation déjà hébergée via ce [lien](https://doc.rudi.bzh).

## Installation

Pour installer Rudi, veuillez vous référer au [guide d'installation du Portail Rudi](https://github.com/Rudi-pages-WIP/Rudi-Portal/blob/main/INSTALL.md) et au [guide d'installation du Nœud Producteur](https://github.com/Rudi-pages-WIP/Rudi-Producer-Node/blob/main/INSTALL.md).

## Feuille de route

Découvrez notre [feuille de route](https://github.com/orgs/Rudi-pages-WIP/projects/1) pour avoir un aperçu des fonctionnalités à venir et des améliorations prévues pour Rudi.

## Contribuer à Rudi

Nous accueillons et encourageons les contributions de la communauté. Voici comment vous pouvez participer :

- [Signaler un bug ou proposer une nouvelle fonctionnalité](https://github.com/Rudi-pages-WIP/Rudi-Producer-Node/issues)
- Résoudre des budgs (rdv sur la page issues) et développer de nouvelles fonctionnalités (quand l'équipe produit accepte votre proposition, vous pouvez aussi la développer et soumettre une PR)
- [Participer aux discussions de la communauté](https://github.com/orgs/Rudi-pages-WIP/discussions)
- [Poser des questions et répondre aux questions des autres](https://github.com/orgs/Rudi-pages-WIP/discussions/categories/questions-et-r%C3%A9ponses)

Avant de contribuer, veuillez consulter notre [guide de contribution](CONTRIBUTING.md) et notre [code de conduite]([CODE_OF_CONDUCT.md](https://github.com/Rudi-pages-WIP/.github/blob/main/CODE_OF_CONDUCT.md)).

## Licence

Rudi est un projet open-source sous licence [EUPL 1.2](LICENCE.md).

## Contacts

Pour contacter les créeateurs du projet chez Rennes Métropole, n'hésitez pas à nous contacter à l'adresse [contact@rudi.bzh](mailto:contact@rudi.bzh).

Suivez-nous sur [LinkedIn](https://www.linkedin.com/company/portail-rudi/about/) pour les dernières actualités et mises à jour du projet.

Rejoignez-nous dans cette aventure passionnante vers une gestion plus intelligente, collaborative et responsable des données territoriales avec Rudi !
