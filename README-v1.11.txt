Mode d'emploi :
Télécharger le fichier html sur le PC et l'ouvrir.



Fonctionnalités ajoutées (changelog) : 
v1.6 : 
	-La durée des phases est exprimée en mois et peut inclure des fractions
	-Export et import du planning au format JSON
v1.7 : Modification des noms des jalons possibles
v1.8 : Masquage des phases ou des jalons si on ne renseigne pas de nom
v1.9 : Ajout d'un bouton copier dans le presse papier pour faciliter la copie vers Powerpoint
v1.10 : 
	-Ajout d'une option pour afficher la date du jour sur le planning 
	-Ajout d'une fonction de rétrocompatibilité de l'import/export (un export de la v1.9 pourra être importé sur v1.10)
v1.11 : 
	-Ajout de la gestion des jalons (possibilités de gérer ses jalons intermédiaires)
	-Rétrocompatibilité testée avec la v1.10
	-Simplification de l'interface (boutons, ergonomie, champs grisés et infobulles)


=================DESCRIPTION DES FONCTIONNALITES===============================
1. Champs date du jour

    Date du jour : permet de définir et afficher un repère visuel sur le planning à une date spécifique, initialisé par défaut à la date actuelle, avec la possibilité de le modifier ou de le vider pour ajuster ou supprimer le repère.

2. Gestion des phases

    Ajouter une phase : Cliquez sur le bouton "Ajouter une phase" pour insérer une nouvelle phase dans votre plan. Vous pouvez personnaliser le nom et la durée de chaque phase.
    Modifier une phase : Vous pouvez modifier le nom ou la durée d'une phase en éditant directement les champs correspondants.
    Réorganiser les phases : Utilisez les boutons fléchés pour déplacer une phase vers le haut ou vers le bas dans l'ordre.
    Supprimer une phase : Cliquez sur le bouton "Supprimer" pour retirer une phase du plan.
	
    A NOTER : la durée des phases est exprimée en mois et peut inclure des fractions (ex. 1.5 pour un mois et demi). En utilisant l’ascenseur on peut rapidement modifier la durée d’une phase en l’allongeant ou en la réduisant d’un pas de 0,5 mois. Si on veut être encore plus fin, on peut aussi saisir directement dans le champ « durée » une fraction différente : ex : 0.25 pour une semaine, 0.33 pour 10 jours, 0.033 x le nb de jours pour une durée encore plus précise…)

3. Gestion des jalons

    Nom et date de Jalon initial : Utilisez ces champs pour définir le nom et la date de début de votre projet. La date de début est cruciale car elle est utilisée pour calculer automatiquement les dates des phases suivantes.
    Nom et date de fin calculée Jalon final : Ces champs affichent le nom et la date de fin calculée pour le projet. La date de fin est automatiquement mise à jour en fonction des phases ajoutées au projet.
    Vous pouvez ajouter/supprimer des jalons intermédiaires

4. Génération du planning

    Générer le planning : Après avoir défini vos phases, cliquez sur "Générer le planning" pour créer une représentation visuelle de votre projet dans le graphique. Le graphique montre la durée de chaque phase ainsi que les jalons importants. A noter que la plupart des navigateurs ajustant automatiquement le planning, ce bouton sera sans effet le cas échéant.

5. Exporter et importer le planning

    Exporter le planning : Cliquez sur le bouton "Exporter le planning" pour sauvegarder votre plan actuel sous forme de fichier JSON. Ce fichier peut être utilisé pour sauvegarder votre travail ou le partager avec d'autres personnes.
    Importer le planning : Utilisez le bouton "Importer le planning" pour charger un fichier JSON précédemment exporté. Cela vous permet de restaurer un plan sauvegardé ou de commencer à travailler sur un planning existant.

6. Copier le planning dans le presse-papier

    Copier dans le presse-papier : Cliquez sur le bouton "Copier dans le presse-papier" pour capturer une image du planning actuel. Un message de confirmation s'affichera brièvement pour indiquer que l'image est prête à être collée dans d'autres applications, comme PowerPoint.

7.Informations complémentaires

    Assurez vous que votre navigateur prend en charge l'API de presse-papiers et l'élément <canvas> pour utiliser pleinement les fonctionnalités de cette application.
    Application testée sur Firefox/Chrome/Edge
==================================================
