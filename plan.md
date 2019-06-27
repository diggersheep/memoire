

# Plan mémoire

## Intro
+ évoquer rapidement en 3-4 lignes TBS
	* écrire du contenu pour écrire du contenu ne m'intéresse pas
+ principalement travaillé à la DNUM

## Présentation entreprise
classique prés de l'entreprise au travers d'un organigramme, de son explication, et quelque blabla autour de l'entreprise.

## Présentation iTop
### ¿Kesako?
- explication de ce qu'est iTop (CMDB)

### Objectifs

* Objectif principal -> enrichissement fonctionnalité de la CMDB + dév/mise_place/support mod Ticket
* avoir une CMDB
* Module de ticketing
* Échange avec autres app (ex: HUB ticket)
* Portail utilisateur

### Techno:
* core: PHP / XML / JS
* interactions: AMQP(via rabbit) / Python-Celery
* HUB: Python / postgres
* Déploiement continu: Ansible
* Bugs tracker: Sentry

### Explication cycle dév:
* Dev -> local -> pour nous
* Test -> équipe dev -> pour tests
* PPRD -> dév + ProductOwner
* Prod -> Clients

## Rappel missions M1
### POC rabbitMQ et Celery
- dév sur rabbit et Celery
- travail préliminaire sur
### Externalisation communication
- communications via rabbit + S3

### Déploiement continu 
- Dévcouverte Ansible
- POC Ansible sur la gestion de multi releases + rollback

## Transition M1/M2:
+ rôle de mentor et de tuteur intermédiaires pour Adam (stagiaire et peut-être apprenti)
+ début de dév sur le module ticket de la CMDB



## Missions M2

### Externalisation des communications
- Mise en production des communications
- Amélioration via la mise en place d'un cycle de vie

### Projet RT2iTop

(recueil du besoin (préliminaire, pas nous))
#### besoins
- renouvellement outil ticket (RT3 vieillissant)
- création de liens entre les tickets et les objets de la CMDB
	- relation
	- mise en évidence de pb, etc
- besoins par la suite:
	- synchro tickets entre itop et le reste du monde

#### Méthodologie de projet
##### SCRUM
- sprint 2 semaine
- retour user (via sprint review)
- formation utilisateur pour avoir des retour + améliorations
- Garanties contractuelles post mise en prod (support/amélioration)
	

#### Grands axes (j'ai pas encore de nom)
##### Module ticket
un des deux modules principaux
+ signature
+ période de vacances et jour fériés
+ Habilitation ticket
	* JS
	* Champ

##### Module portal utilisateur
un des deux modules principaux
+ Datamodel diff
+ Adaptation charte graphique unistra (ergonomie)
+ etc ...

##### Modules secondaires
- email automation (Modification d'un module préexistant)
	+ redirection vers équipe
	+ création de contacts
		- Demandeurs / Copie inconnu
- email repy
- precanned reply
- archive
- (+) tests de modules en tout genre dans le cadre de l'amélioration continue de la CMDB


##### Projet Hub de tickets
* Explication besoins
* objectifs:
	- Synchro tickets dff appli et diff instances
	- Création de tickets from scratch (besoins)
	- etc ...
* techno
  - python / Celery / Postgres

##### JRES
* ¿kesako?
	- Journées Réseau de l'Enseignement de la recherche
	- prés sur des trucs en réseau et interconnexions
* Réalisation article
* Réalisation présentation

##### Sentry
- besoin:
	- tracker les bugs car la iTop ne permet pas de mettre en place des TU
	- identifier la source des bugs rapidement


## Recul sur les deux années
### Aspect tech

Parler de l'aspect complet de l’apprentissage à la DNUM
- outils versionning
- cycle de vie des sources
- message broker
- framework (django/Vue.js)
- tests u + fonctionnels


### vie de l'entreprise
- reprise de ce qui a été dit l'an passé
- cohésion
- culture universitaire



## Conclusion

- évolution: stagiaire -> Apprenti -> Contractuel
- rappeler que DNUM == apprentissage complet et transverse
- et je ne sais pas encore, mais il faut une conclusion qui punch pour donner une bonne dernière impression
