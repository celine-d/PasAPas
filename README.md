# PasAPas
Pas A Pas 
(Projet de Data Visualization MOS5.5)
</br> Sandrine DUPREZ, Céline DUPLAY, Léa GAUTILLOT


## Idée projet et problématique

* Nous souhaiterions étudier les données sur la santé et les déplacements que nous pouvons retrouver sur nos téléphones comme le nombre de pas ou encore les distances parcourues afin de mettre en évidence plusieurs comportements : journée type travail / week-end / vacances/ saisons. 

* Nous pourrions ainsi essayer d’identifier s’il est possible de repérer un schéma ou si, au contraire, il n’est pas possible de mettre en avant un comportement régulier. 

## Données personnelles dont nous aurons besoin

* Nombre de pas au quotidien
* Distances parcourues

## Questions auxquelles nous souhaitons répondre

* Peut-on, à l’aide du nombre de pas par heure, mettre en évidence certains types de comportements ? (travail, week-end, vacances)
* Si oui, quelles sont les caractéristiques de ces comportements ? 
* Le sujet étudié marche-t-il “assez” par jour ? (contextualisation des données)
* La saison a-t-elle une influence sur la marche ? (faible température, forte température)

## Comment les collecter ? 

Extraction depuis les applications mobiles (santé sur IOS) : fichiers xml récupérés et fichier csv via l’application QS Access.


## Quels sont les risques pour la collecte/visualisation ? (règles, éthique etc)

* Sans être un risque, l’un des enjeux sous-jacent est celui de la santé
* Données liées à la santé donc potentiellement sensibles, privées/ à caractère personnel → anonymisation des données
* Sécurité d’accès des données : qui peut y avoir accès ?
* Niveau de précision des outils de mesures non connu 
        
    
 ## Premières visualisations 
 
 * Sur tableau :
        https://public.tableau.com/views/HealthData_22/Comparaisonavecrecommandations?:embed=y&:display_count=yes&publish=yes
        
 * Sur d3 : 
        https://bl.ocks.org/celine-d/ed0134c25cde81f3295a126c1e5f74ce/4539862c4f31c9d29b9c5fa36d5522ecbaceec63
        https://bl.ocks.org/lgautill/aad8bb2ad61124e0134753073fb392c6/882852a7da76896e025d876d180c902f055bd561
  
 ## Visualisations 
 
 * Liens :
 
 Scatterplot : contextualisation des données en calories brûlées et exercices
 
 https://bl.ocks.org/lgautill/eb7ab63ab7ca6e039bfb407d923e1de5/9ca04173f9369028abc5596cea394ccb8b292b4b 
 
 Barchart : contextualisation des données en distances parcourues
 
 https://bl.ocks.org/lgautill/11c29ff7ec20da675782c9a3f757b4d1/0356a8e1482453b128c61c2e6fe65933a90a2182
 
 Boxplot : 
 
 Treemap :
 
 * Descriptions des visualisations et de leurs caractéristiques :
 
 <b>Scatterplot : contextualisation des données en calories brûlées et exercices</b>
 
 Cette visualisation représente le nombre de pas effectués en fonction de la date. 
 Tout d'abord, en haut, il est possible de cocher les années que l'utilisateur souhaite voir apparaître. Ici, sur l'exemple, ce sont 2017 et 2018.
  <img src="Scatterplot1.png" alt="" width=600 height=300>
  
  Cette visualisation permet surtout de contextualiser les données. En premier, après "nombre de pas :", l'utilisateur peut cocher le nombre de pas référence qu'il souhaite. Ainsi, les points changent de couleur et sont en rouge si le nombre de pas est inférieur à la référence cochée et en vert s'il est supérieur. Ici, sur l'exemple le nombre de pas coché est de 7 500 pas correspondant à une personne modérément active. 
  <img src="Scatterplot2.png" alt="" width=600 height=300>
  
  Enfin, la visualisation permet également de choisir une référence. Cette référence peut être de deux types calorique : nombre de Big Mac ou de Coca-Cola éliminés ou sportive : nombre de minutes de boxe ou de nage lente réalisées. Les points apparaissent alors plus ou moins important en fonction du résultat. En passant la souris sur les points, des informations supplémentaires s'affichent. Ici, on peut voir la référence en canettes de Coca-Cola et que le 7 Juin 2018, la personne a effectué 30 060 pas (ce qui est bien supérieur à 7 500 pas donc en vert) et éliminé 7,6 canettes de Coca-Cola. 
  <img src="Scatterplot3.png" alt="" width=600 height=300>
  
 <b>Barchart : contextualisation des données en distances parcourues</b>
  
  <img src="Barchart1.png" alt="" width=600 height=300>
  <img src="Barchart2.png" alt="" width=600 height=300>
  <img src="Barchart3.png" alt="" width=600 height=300>
  
  
 * Notre site:
 https://celine-d.github.io/PasAPas/
        
        
 ## Crédits
 
 Contenu Bootstrap
 <br> Cours de visualisation 2018 : https://github.com/LyonDataViz/MOS5.5-Dataviz
 <br> Références de marche: http://www.fitmania.fr/10-000-pas-par-jour-pour-rester-en-forme/  <br> https://www.sciencepresse.qc.ca/actualite/detecteur-rumeurs/2017/09/20/marcher-10-000-jour-pour-tenir-forme-vrai
