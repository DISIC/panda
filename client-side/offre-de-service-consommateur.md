## Offre de service consommateur des données

Dans le cadre de la mise en oeuvre de ses missions de service public, l’administration produit et reçoit des documents administratifs. L’open data consiste à mettre à disposition les données contenues dans ces documents administratifs à tous afin de les réutiliser librement.

Ces données sont exposées sur la plateforme https://www.data.gouv.fr/ dans laquelle figure notamment les données issues du [Service Public de la donnée](https://www.data.gouv.fr/fr/reference), créé par l’Article 14 de la loi pour une République numérique qui vise à mettre à disposition, en vue de faciliter leur réutilisation, les jeux de données de référence qui présentent le plus fort impact économique et social. Il s’adresse principalement aux entreprises et aux administrations pour qui la disponibilité d’une donnée de qualité est critique. Les producteurs et les diffuseurs prennent des engagements auprès de ces utilisateurs.

D'autres données qu'elles concernent les particuliers ou les personnes morales sont confidentielles et ne sont délivrées qu'aux administrations légitimes.

L'accès à ces données nécessite une autorisation qui est  étudiée au regard de la réglementation en vigueur, notamment via Signup (décrit plus bas).

Par ailleurs, api.gouv.fr permet d'avoir accès à l'ensemble des APIs proposées par les administration pour en faciliter leur exploitation. 

### API.gouv.fr: le catalogue d'APIs des administrations

Ce catalogue d'APIs, facilite le décloisonnement des données détenues par l’administration, afin de dynamiser le développement et l’évolution rapide de nouveaux services publics. Des services développés par les administrations et par tous les innovateurs susceptibles d’utiliser cette nouvelle ressource. 

Les administrations déclarent elles-mêmes leurs APIs, pour peu qu’elles respectent un ensemble simple de conditions :

- disposer d’une description fonctionnelle claire et succincte de l'API à renseigner sur API.GOUV,
- proposer une documentation technique en ligne et claire,
- décrire une procédure en ligne pour demander l'accès à l'API si elle n'est pas totalement ouverte.

Principal critère d'acceptation de l’API : celle-ci doit pouvoir être testée en moins d'une journée et intégrée en moins d'une semaine.

Au delà des conditions exposées ci dessus, api.gouv.fr encourage un ensemble de bonnes pratiques. Comme celle de produire une documentation au format OPEN API, de fournir des exemples de services utilisant leurs API ou encore de proposer une page de statistiques démontrant la facilité d'utilisation pour l'API concernée : nombre de hits, mais surtout mesures sectorielles comme nombre de courses de taxi (le.taxi), nombre de candidatures simplifiées aux marchés publics (API Entreprise).

Les producteur d’API sont également invités à décrire simplement les modalités d'accès à leur API (CGU, licence..) et à simplifier au maximum l'enrôlement.

Les fournisseurs d’API sont responsables de l’exposition de leurs ressources. Ils définissent les conditions d’utilisation que devront respecter les consommateurs d’API. Les fournisseurs d’API référencés sur api.gouv.fr sont tous issus de la sphère publique : l’État ou ses représentants, collectivités, autorités administratives…

Les consommateurs d’API quant à eux prennent contact avec les fournisseurs pour consommer leurs ressources. Les consommateurs sont issus de la sphère publique ou de la sphère privée (associations, startup, éditeurs, entreprises, etc.). Dans le cas des API ouvertes, sans conditions, il n’est pas nécessaire de contacter le fournisseur avant de consommer les ressources.

### Découvrir l'offre en matière de données liées aux particuliers

#### Les données particulier

API Particulier, vise à permettre, par l’échange d’informations entre administrations, de Simplifier l’accomplissement des démarches administratives du public , lui évitant ainsi de fournir des informations ou pièces justificatives déjà détenues par une administration.

API Particulier permet d’avoir une source certifiée pour les données : il n’y a plus à aller les vérifier, elles viennent directement des impôts ou de la Caf par exemple. Les administrations peuvent automatiser des démarches et les agents passer plus de temps avec les familles qui en ont vraiment besoin, par exemple pour les cas qui ne rentrent pas forcément dans des cases.

![](https://blog.beta.gouv.fr/img/posts/2018-10-18-api-particulier-la-fin-des-justificatifs/schema-api-particulier.png)

Si vous souhaitez utiliser API Particulier dans votre ministère, votre mairie, votre collectivité ou bien encore votre hôpital, rendez-vous sur https://particulier.api.gouv.fr/.

Vos développeurs auront accès à la [documentation technique](https://api.gouv.fr/api/api-particulier.html#doc_tech) : à quelles informations ils peuvent avoir accès, ainsi que des données de test. 

**Les données actuellement disponibles à travers l'API Particulier sont les suivantes:**

*Informations issues de la Direction Générales des Finances Publiques (DGFIP):*

* Déclarants du foyer fiscal - Le foyer fiscal se compose du contribuable lui-même, du conjoint ou partenaire de Pacs
* Adresse connue au 1er janvier de l’année d’imposition (exemple au 1er janvier 2018 pour les revenus de 2017)
* Nombre de parts
* Revenu fiscal de référence
* Nombre de personnes à charge
* Situation familiale
* Montant des impots
* Revenu net avant correction
* Revenu imposable
* Revenu brut global
* Date de mise en recouvrement de l’avis d’impôt
* Date d’établissement

*Information issues de la Caisse Nationale d'Assurance Familiale:*

* Liste des allocataires
* Liste des enfants
* Adresse au format de la Poste
* Valeur du quotient familial
* Année et mois du quotient familial

Une fois ces premiers essais terminés, il vous suffit de faire une demande d’autorisation par l'intermédiaire du [formulaire à cet effet](https://auth.api.gouv.fr/users/). Cela nous permettra de vérifier que vous avez bien le droit d’avoir accès aux informations que vous demandez. Vous pourrez ensuite utiliser les API avec les données réelles. Cette demande d’autorisation se fait via notre outils Signup, qui permet de gérer la relation entre le fournisseur de données et le fournisseur de service. 

La DINSIC s’engage à ce que le Service soit accessible à 95% et la DINSIC s’engage à améliorer progressivement ce rendement. Les moniteurs de cette API sont disponibles publiquement: https://status.particulier.api.gouv.fr/

Pour plus d'information, merci de nous écrire à l'adresse suivante: contact@particulier.api.gouv.fr 

##### Cas d'usage

###### Cas d'usage 1 : Demande de bourse des collèges

Cette année, toutes les demandes des bourses au collège ont été dématérialisées grâce à API Particulier. Les revenus de la famille ont été directement récupérés au niveau des centres des impôts. En septembre 2018, nous avons eu 650 000 appels réussis ce qui correspond à autant de justificatifs qui ont été évités. C’est à nouveau un gain de temps pour les familles. Certains parents devaient prendre une demi journée de RTT pour déposer leur dossier, d’autres demander à leurs enfants de faire la queue pendant la récréation….
  
###### Cas d'usage 2
- Définition du scope autorisé
- un verbatim ?
- Liste des prestataires qui couvrent ce cas d'usage

##### Données délivrées
###### Données impots
###### Données Caf
##### Comment effectuer une demande d'accès
Les élements génériques demandés pour les API de la DINSIC
le fonctionnement détaillé selon l'API
Plus tard : demande d'API "franceConnectées" : des api qui necessitent d'avoir implémenter le "bouton franceconnect". expliquer le processus.

Renvoyer sur d'autres processus d'enrolement pour les API hors DINSIC (demander l'intervention d'autres ministeres - INSEE association...)

#### API DGFIP FC
#### FranceConnect : API de données d'identité
    - Données délivrées
    - effectuer une demande d'accès
#### COMEDEC
#### SIV ?


#### Demander une donnée manquante au catalogue
Formulaire de demande d'accès à une donnée qui n'existe pas au catalogue :
Champs du formulaire
- Organnisation
- Mail
- cas d'usage
- justification juridique
- données demandées

### Découvrir l'offre de données "personne morale"
Introduction avec open data (liste des API opendata personne morale ?) et les données délivrées dans ce cadre puis présentation de l'API entreprise!^!
#### API entreprise
##### Cas d'usage
###### Cas d'usage 1  : marchés publics  
- Définition du scope autorisé
- un verbatim ?
- lien vers liste des partenaires

###### Cas d'usage 2 : aides aux entreprises
- Définition du scope autorisé
- un verbatim ?
- Liste des prestataires qui couvrent ce cas d'usage + mail de contact pour figurer dans la liste

###### Autres cas d'usage


##### Catalogue des données de l'API entreprise
- Association
- Document association
- INSEE Entreprise
- INSEE Etablissement
- Bilans Entreprises BDF
- Exercice
- Extrait INPI
- Extrait RCS
- Liasse fiscale
- Attestation Fiscale
- Attestation Sociale
- Attestation AGEFIPH
- Cotisation MSA
- Carte Pro FNTP
- Certificat CNETP
- Certificat OPQIBI
- Certificat PROBTP
- Certificat Qualibat

##### Effectuer une demande d'accès
Les éléments génériques demandés Pour les API de la DINSIC
le fonctionnement détaillé selon l'API
Plus tard : demande d'API franceConnecter : expliquer le processus.

Renvoyer sur d'autres processus d'enrolement pour les API hors DINSIC (demander l'intervention d'autres ministeres - INSEE association...)

#### Demander une donnée manquante au catalogue des données personnes morales


#### APIs PISTE ?
#### APIs agriculture ?


#### Découvrir l'offre de données "personnes morale"
Introduction avec open data et les données délivrées dans ce cadre puis présentation de l'API entreprise
