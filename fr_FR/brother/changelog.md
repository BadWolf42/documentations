## 2024-09-27 (v12 - Stable & Beta)
- Correction d'un bug qui rechargeait les infos de l'imprimante à chaque chargement du dashboard
- Correction d'une erreur PHP s'il manquait une commande ou sa valeur
- Ajout de la commande "Dernier allumage"
- Ajout d'une infobulle avec plus d'informations (demande de *mich0111*)
- Mise à jour de la bibliothèque Python brother 4.3.0 -> 4.3.1

## 2024-09-08 (v11)
- Correction des remontées du démon (Modèle, S/N & Firmware manquaient, merci *sodaveli*)
- Ajout du [workflow de traduction automatique](https://github.com/Mips2648/plugins-translations) (merci *Mips*)
- Ajout d'infobulles sur le graphique du widget

## 2024-09-07 (v10)
- Ajout du support de Debian 12
- Refonte des dépendances à l'aide de NebzHB/dependance.lib et Mips2648/pyenv.lib
- Mise à jour des requêtes de bibliothèque Python 2.31.0 -> 2.32.3
- Mise à jour de la bibliothèque Python brother 1.0.2 -> 4.3.0
- Correction de l'URL du CHangelog beta
- Correction de la casse de la valeur de la commande status

## 2024-03-18 (v9)
- Correction d'un bug d'affichage des commandes d'un équipement (merci *echo*)
- Correction d'un bug si les dépendances ne sont pas installée et qu'il y a un refresh (merci *echo*)
- Correction d'un bug d'alignement des champs sur la page d'un équipement

## 2024-03-17 (v8)
- Passage de la dernière beta en stable

## 2024-03-03 (v8)
- Suppression de jQuery là où c'est possible
- Ajout du Workflow Todo to Issue
- Amélioration des logs (moins verbeux et plus claires)

## 2023-11-26 (v7)
- Externalisation de la documentation et du changelog

## 2023-10-01 (v6)
- Passage de la dernière beta en stable

## 2023-09-29 (v6)
- Correction d'un [problème avec le packet pyasn1](https://community.jeedom.com/t/107671) (en utilisant un venv Python3)
- Correction du niveau de certains journaux (trop verbeux)

## 2023-05-14 (v5)
- Correction de problèmes avec le widget sur Jeedom 4.4

## 2023-04-30 (v4)
- **Le widget sur le Dashboard est maintenant mis à jour lors du changement d'une valeur**
- **Changement du logo, en utilisant du jaune au lieu du bleu foncé**
- **Le support de la version minimale est désormais Jeedom 4.3**
- Ajouter Luna comme matériel pris en charge
- Ajouter le numéro de version dans info.json
- Nettoyage des scripts d'installation, de mise à jour et de migration
- Inclusion du changelog et de la documentation bêta dans info.json
- Mise à jour de l'onglet Commandes des équipements dans le style de Jeedom 4.3
- Correction l'objet "Aucun" manquait sur l'onglet Équipement des équipements
- Correction de la PHP Notice lorsque l'imprimante est allumée
- Correction typographique

## 2023-02-27
- Mise à jour de l'onglet Commandes des équipements dans le style de Jeedom 4.3
- Correction l'objet "Aucun" manquait sur l'onglet Équipement des équipements
- Correction de la PHP Notice lorsque l'imprimante est allumée
- Correction typographique

## 2023-02-20
- **Reprise du plugin par BadWolf**
- Modification du fonctionnement du rafraichissement : un callback est utilisé pour éviter de créer un cron
- Renommage de la branche "master" en "stable", merci à ceux qui utilisent Github au lieu du Market de changer de branche
- Ajout de statistiques d'utilisation
- Indentation/nettoyage du code

## 2023-02-14
- **Reprise du plugin par BadWolf**
- Ajout de statistiques d'utilisation
- Indentation/nettoyage du code

## 2022-03-04
- Correction typographique dans les logs
- Droits sudo inutiles retirés
- Rafraichissement manuel dans un cron pour éviter les bloquages de la UI
- Compatibilité avec les graphiques en fond de widget

## 2022-02-18
- Correction sur le calcul des dernières impressions

## 2022-02-12
- Première version stable

## 2022-02-11
- Niveau de logging du package python aligné avec la config Jeedom
- Les items de la jauge sont maintenant cliquables pour accéder à l'historique
- Fond gris sur la jauge pour une meilleur visibilité du niveau d'encre noire

## 2022-02-10
- Choix du type d'imprimante (couleur, noir & blanc)
- Widget plus petit avec infos de status et du nombre de pages
- Widget réactif aux commandes invisibles

## 2022-02-07
- Ajout logs
- Nouvelle commande pour le nombre de pages imprimées dans la dernière heure

## 2022-02-06
- Première version (beta)
