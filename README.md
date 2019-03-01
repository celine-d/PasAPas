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
 
 * Descriptions des visualisations et caractéristiques :
 
 <b>Scatterplot : contextualisation des données en calories brûlées et exercices</b>
 
 Exemple en photo ci-dessous:
  <img src="Scatterplot1.png" alt="">
  <img src="Scatterplot2.png" alt="">
  <img src="Scatterplot3.png" alt="">
  
 Barchart : contextualisation des données en distances parcourues
  
 Exemple en photo ci-dessous:
  <img src="Barchart1.png" alt="">
  <img src="Barchart2.png" alt="">
  <img src="Barchart3.png" alt="">
  
  
 * Notre site:
 https://celine-d.github.io/PasAPas/
        
        
 ## Crédits
 
 Contenu Bootstrap
 <br> Cours de visualisation 2018 : https://github.com/LyonDataViz/MOS5.5-Dataviz
 <br> Références de marche: http://www.fitmania.fr/10-000-pas-par-jour-pour-rester-en-forme/  <br> https://www.sciencepresse.qc.ca/actualite/detecteur-rumeurs/2017/09/20/marcher-10-000-jour-pour-tenir-forme-vrai
