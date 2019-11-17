# Dùralas

[Dùralas][1] est un forum français de rôle-play dans un univers médiéval-fantastique. 
Le principe est d'écrire des récits mettant en scène son propre personne afin d'interagir avec d'autres joueurs.

## Fiches de combat

En tant que forum RPG, Dùralas gère des fiches de personnage dont les caractéristiques permettent d'organiser des combats. 
Celle-ci se fait à travers des fiches de combat récapitulatives au tour par tour.

Les membres peuvent rédiger ces fiches afin d'aider les administrateurs dans leur travail. 
Or s'ils veulent respecter les modèles bien stylisés, ils doivent utiliser du html et du css, un point pas forcément très accessible pour tous.

# Génération de fiche

Ce projet se présente sous la forme d'un formulaire HTML (stylisé par bootstrap) demandant les informations clefs d'un combat :

* Caractéristiques : vitalité, vitesse et dégâts.
* Capacités spéciales : effets ainsi que les decks et les partitions (pour les classes concernées).
* Les informations pour chaque participant du combat (alliés comme ennemis).

Une fois ces informations renseignées, le formulaire les utilise pour générer le contenu HTML utilisé pour réaliser les fiches de combat.
Ce contenu est à copier/coller afin d'indiquer le code complet de la fiche de combat.

## Fonctionnalités attendues

Plusieurs fonctionnalités sont attendues afin de réaliser un utilitaire de génération complet.
Certains points sont compliqués à gérer (les modifications de statistiques des différents effets, notamment).
L'utilitaire sera incomplet, mais d'une grande aide !

- [ ] Ajouter les capacités spéciales.
  - [ ] Marquer une capacité spéciale comme **Bloquée**, **Utilisée**, **Active** ou encore **Inactive**.
  - [ ] Ajouter les decks et les partitions.
  - [ ] Marquer la lame du deck.
  - [ ] Marquer le rechargement des partitions.
- [ ] Générer la fiche de plusieurs individus.
- [ ] Générer la fiche de plusieurs équipes.
- [ ] Exporter/Importer sous forme JSON les informations de chaque individu.
  - [ ] Ajouter cet export dans le bestiaire.

[1]: http://www.lemondededuralas.org/
