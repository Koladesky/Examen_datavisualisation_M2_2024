# Etablissements de santé et médecins généraliste 
 
![image](https://www.usine-digitale.fr/mediatheque/2/9/0/001212092_896x598_c.jpg) 
## Sommaire
1. [Introduction](#introduction)
2. [Collecte des données](#collectedesdonnes)
3. [Cartographie des Établissements de Santé en France : Disparités Régionales](CartographiedesetablissementsdeSanteenFrance:disparitesregionales)
4. [Paysage des Médecins Libéraux Français : Une Vue par Département](PaysagedesMedecinsLibérauxFrançais:unevuepardepartement)
5. [Comparatif des Ressources en Santé : Établissements et Médecins par Département](ComparatifdesRessourcesenSanté:etablissementsetmedecinspardepartement)
6. [Conclusion](#conclusion)




## 1.Introduction
En quête de compréhension approfondie des dynamiques du secteur de la santé en France, nous plongeons dans une analyse détaillée d'un jeu de données qui cartographie le paysage sanitaire du pays. Ce dataset, riche et informatif, englobe une variété de paramètres clés, notamment, le nombre d'établissements de santé, les effectifs de médecins libéraux, ainsi que les données démographiques de la population. Notre objectif est de déchiffrer et de visualiser ces informations pour en extraire des tendances, des corrélations et des aperçus qui pourraient non seulement éclairer les professionnels de la santé et les décideurs politiques, mais aussi sensibiliser le grand public aux réalités actuelles du système de santé français. En utilisant des techniques de visualisation de données avancées, nous cherchons à mettre en lumière les disparités régionales, les défis en matière de disponibilité des soins de santé, et les opportunités d'amélioration du système pour une couverture sanitaire plus équitable et efficace. Cette analyse s'efforce ainsi de jeter les bases d'une discussion éclairée sur l'état actuel et le futur de la santé en France.

## 2. Collecte des données

>[corpus constitué à partir de cette source]( https://www.sanitaire-social.com/annuaire-etablissements-de-sante/etablissement-de-sante)
**Ce corpus est constitué manuellement à partir des données récupérées sur cette page**
Dans ce fichier se trouve la liste des établissements de santé
>[Corpus sur l'effectif](https://explore.data.gouv.fr/fr/tableau?url=https%3A%2F%2Fwww.data.gouv.fr%2Ffr%2Fdatasets%2Fr%2F34869c69-188e-48ca-8242-70161aebab47&annee__less=2022&annee__greater=2021&libelle_type_exercice_liberal__exact=lib%C3%A9ral+exclusif&profession_sante__exact=M%C3%A9decins+g%C3%A9n%C3%A9ralistes+%C3%A0+expertise+particuli%C3%A8re+%28MEP%29)


## 3. Cartographie des Établissements de Santé en France : Disparités Régionales

>[fichier_visualisation1](https://github.com/Koladesky/Examen_datavisualisation_M2_2024/blob/main/Etablissemments-sante.csv)

<div class="flourish-embed flourish-hierarchy" data-src="visualisation/16644482"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
  Cette graphique, illustre la répartition des établissements de santé par département en France. Chaque bulle représente un département, avec sa taille proportionnelle au nombre d'établissements de santé qu'il contient. Les couleurs variées facilitent la distinction entre les départements, bien qu'elles ne semblent pas suivre une légende spécifique ou représenter des catégories distinctes.
 L'analyse révèle des disparités significatives entre les départements. Par exemple, on observe que le département du Nord (93) se distingue par le plus grand nombre d'établissements, suivi de près par Paris (74) et le Rhône (71). Ces trois départements, caractérisés par des bulles particulièrement volumineuses, suggèrent une concentration élevée d'établissements de santé, ce qui pourrait refléter une densité de population plus élevée et ou un pôle urbain majeur avec des besoins en soins de santé plus importants.
D'autre part, certains départements comme la Creuse, la Lozère et les Hautes-Alpes, représentés par de petites bulles, indiquent un nombre plus restreint d'établissements de santé. Cette situation pourrait soulever des questions d'accessibilité et de couverture sanitaire pour les populations résidant dans ces zones moins densément peuplées ou plus rurales.
Il est important de noter que la taille des bulles ne reflète pas nécessairement la qualité ou la gamme de services de santé disponibles, mais simplement le nombre d'établissements.

## 4. Paysage des Médecins Libéraux Français : Une Vue par Département
>[fichier_visualisation2](https://github.com/Koladesky/Examen_datavisualisation_M2_2024/blob/main/Etablissemments-sante.csv)
<div class="flourish-embed flourish-hierarchy" data-src="visualisation/16645039"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
 Cette deuxième visualisation représente les effectifs de médecins libéraux par département en France en 2021. 
 Chaque bloc de couleur représente un département spécifique et sa taille est proportionnelle au nombre de médecins libéraux qu'il compte.
D'emblée, on remarque que Paris se distingue nettement avec le plus grand bloc, indiquant le plus grand nombre de médecins libéraux (364), ce qui n'est pas surprenant compte tenu de sa population dense et de son statut de centre urbain majeur avec une forte concentration de services et de ressources. La Gironde et le Var suivent, avec respectivement 138 et 135 médecins libéraux, suggérant également une bonne disponibilité des soins médicaux dans ces départements.
La diversité des couleurs aide à distinguer les différentes zones, mais il faut de noter que les couleurs ne semblent pas correspondre à une échelle particulière ou à une autre variable. Le choix des couleurs est destiné à différencier visuellement chaque département.




## 5. Comparatif des Ressources en Santé : Établissements et Médecins par Département
>[fichier_visualisation3](https://github.com/Koladesky/Examen_datavisualisation_M2_2024/blob/main/Etablissemments-sante.csv)
<div class="flourish-embed flourish-chart" data-src="visualisation/16646289"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
 Cette visualisation met en parallèle le nombre d'établissements de santé (représenté par des points et une ligne verte) et le nombre de médecins libéraux (représenté par des points et une ligne orange) pour chaque département en France.
Il s’agit de comparer les deux variables différentes mais liées pour observer leur relation à travers différents départements. Les pics dans les données des médecins libéraux, qui sont beaucoup plus marqués que ceux pour les établissements de santé, indiquent des départements où il y a un nombre particulièrement élevé de médecins. Cependant, un pic très haut, comme celui observé pour Paris, suggère une concentration exceptionnelle de médecins libéraux qui n'est pas nécessairement proportionnelle à la taille de la population ou au nombre d'établissements de santé.

## 6. Conclusion 
Ces visualisations conjointes dressent le portrait d'une distribution des soins de santé en France qui est aussi riche que complexe. Elles mettent en exergue l'importance d'une stratégie de santé publique bien pensée, visant à équilibrer les ressources entre les régions et à garantir que l'accès aux soins ne soit pas uniquement une fonction de la densité démographique ou de la centralisation urbaine. Pour les décideurs, l'enjeu est de taille : il s'agit de réaligner les ressources pour répondre aux besoins de tous les citoyens, en assurant une distribution équitable des professionnels de santé et des infrastructures médicales à travers le pays.
