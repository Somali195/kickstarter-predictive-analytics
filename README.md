# kickstarter-predictive-analytics

Réalisé dans le cadre de la formation Data Analyst, au sein de l’organisme DataScientest (https://datascientest.com/).

## Description du Projet

Kickstarter est une plate-forme américaine de financement participatif créée en 2009, à destination des particuliers. Plus de 550 000 projets ont déjà été lancés sur cette plate-forme, dont environ 40% ont été intégralement financés, grâce à l’aide de contributeurs.

L’objectif du projet est d’**établir des modèles prédictifs permettant de déterminer quel sera le statut final (échec ou réussite) de campagnes de financement participatif**, lancées par des utilisateurs sur cette plate-forme.

Cette étude permet en outre d’identifier **les conditions de réussite d’une campagne de financement**, ce qui s’avère utile à la fois pour les créateurs de projets, et aussi pour la plate-forme Kickstarter :
- les créateurs de projets peuvent maximiser leurs chances de réussite en jouant sur certains paramètres précis pour leur(s) campagne(s),
- pour Kickstarter, il est utile d’identifier les projets ayant de fortes chances de réussite car l’entreprise perçoit une commission sur les montants collectés en cas de campagnes intégralement financées. 
En identifiant en amont les projets ayant de grandes chances de réussite, la plate-forme peut par exemple améliorer la visibilité de ces derniers et booster leur succès (et donc augmenter sa propre rémunération).

## Données

Les données utilisées proviennent de **Kaggle** (lien).

Le dataset recense des données sur des campagnes de financement participatif lancées entre 2009 et 2020. 

Les variables du dataset sont les suivantes :

id : 			Identifiant de la campagne de financement  
name :			Nom de la campagne  
currency : 		Devise des sommes collectées   
launched_at : 		Date de lancement de la campagne  
backers_count : 	Nombre de contributeurs  
blurb : 			Slogan de la campagne  
country :		Pays de lancement de la campagne  
deadline : 		Date de clôture de la campagne  
slug : 			Texte qui apparait dans le navigateur lorsque l'on affiche la page web de la campagne  
status : 			Statut final de la campagne  
usd_pledged : 		Montant collecté (en USD)  
sub_category : 		Catégorie principale de la campagne  
main_category : 	Sous-catégorie de la campagne  
creator_id : 		Identifiant du créateur de la campagne  
blurb_length : 		Longueur du slogan (en nombre de lettres)  
goal_usd : 		Objectif à atteindre de la campagne (en USD)  
city : 			Ville de lancement de la campagne  
duration :		Durée de la campagne (en nombre de jours)  
