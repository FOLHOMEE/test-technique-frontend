# Test technique Folhomee

## Contexte

Le buts de ce test technique sont les suivants :

- Nous permettre de voir votre niveau technique
- Essayer de déterminer vos capacités concernant la résolution de problèmes
- Voir si vous pourriez vous intégrer au sein de notre équipe technique

Au cours de ce test technique, vous allez réaliser une application qui utilise l'API sirene du gouvernement

Il est important de respecter les consignes suivantes :

- Ne sautez pas un exercice, il faut respecter l'ordre
- Vous n'avez pas besoin d'utiliser un service extérieur pour les exercices
- Il est très facile de trouver des résolutions/solutions de ce test en ligne, aussi vous serez jugé sur votre capacité de structurer votre code

## Livrables

Les livrables minimum sont les suivants :

- Un repo github privé auquel vous aurez donné accès au CTO de Folhomee (username github : [milanito](https://github.com/milanito))
- Un ensemble de dossiers/fichiers selon une nomenclature claires
- Pour chacun des exercices, le temps que vous avez mis à le réaliser au travers d'un README que vous essayerez de détailler (le markdown est recommandé), de préférences individuellement pour chaque partie

Nous vous demanderons en plus de respecter les contraintes technique suivantes :

- Le code devra être écrit en javascript et tourner sur node LTS (v14 au moment de l'écriture de ce test)
- Le code devra respecter la coding style de l'entreprise, à savoir [standardjs](https://standardjs.com/)

Pour le reste, vous êtes libre de vos choix techniques quand il n'est pas explicitement dit dans l'exercice le choix à faire

## API

L'API à utiliser est l'API Sirene du gouvernement dont vous trouverez la documentation à cette adresse : [https://entreprise.data.gouv.fr/api_doc/sirene](https://entreprise.data.gouv.fr/api_doc/sirene)

## Exercices

Vous devez créer une application web qui regroupe les pages suivantes :

### Recherche

Vous devrez créer une page qui permet de rechercher une entreprise avec les données suivantes :

- Nom de l'entreprise
- SIREN de l'entreprise
- SIRET de l'entreprise

Vous êtes libre sur le design et le comportement de cette page. Vous pouvez vous inspirer de l'annuaire des entreprises : https://annuaire-entreprises.data.gouv.fr/

#### Bonus

Vous pouvez imaginer les bonus suivants :

- Autocomplete sur le nom, le SIREN ou le SIRET
- Nous impressionner avec n'importe quoi que vous trouverez pertinent

### Listing

Vous devrez créer une page qui permet de lister les entreprises qui correspondent à votre recherche.

Vous êtes libre sur le design et vous pouvez utiliser la page précédente pour afficher vos données

#### Bonus

Vous pouvez imaginer les bonus suivants :

- Affichage des entreprises sur une carte
- Nous impressionner avec n'importe quoi que vous trouverez pertinent

### Page d'une entreprise

Vous devrez créer une page qui regroupe les données d'une entreprise

Vous êtes libre sur le design

#### Bonus

Vous pouvez imaginer les bonus suivants :

- Comportement similaire à l'annuaire des entreprises
- Nous impressionner avec n'importe quoi que vous trouverez pertinent

## Bonus

Une fois l'intégralité des exercices précédents réalisés, vous pouvez réaliser les tâches suivantes en bonus :

- Proposer un hébergement en ligne pour les applications
- Mettre en place des tests unitaires et d'intégration
- Permettre un déploiement continue
- Nous impressionner avec n'importe quoi que vous trouverez pertinent
