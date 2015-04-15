# Cr CafEPHE, 14 avril 2015


## GIS

Utilisation de QGIS, libre, d’un usage aisé car s’inspire des logiciels de dessin.
Pour la prise en main, didacticiel de Wikipédia pour la production cartographique sont très utiles.
Voir éducagri.

La clef d’un projet c’est donc les données. 
Des images géoréférencés. Plusieurs systèmes de coordonnées géographiques.
- WGS 84, World Geodetic System (1984), le plus courant.
- RGF 93, Réseau géodésique français (1993) mis au point par l’IGN

Un système décimal.
Données qui ont l’avantage de pouvoir s’adapter aux problématiques de projection. La surface terrestre n’étant par parfaitement régulière, correction nécessaire en projection.
Il faut choisir une projection la plus adaptée à l’objet représenté.

Deux types d’images :
- images vectorielles
- images matricielles (raster), dont le format fixé, TIFF, GIF, PNG
GéoTIFF qui permet d’intégrer des métadonnées de géoréférencement. Ainsi l’image peut s’adapter à la nouvelle projection.

Pour faire la projection, utiliser les latitudes et longitudes. En leur absence, utiliser les coordonnées des villes.
Plusieurs systèmes de projection sont disponibles pour travailler sur des vieilles cartes. On peut également produire son propre système utilisateur.

Bon exemple d’image GéoTIFF que peut récupérer. Fond de carte qui comprend toutes les coordonnées géographiques ainsi que le relief même si elles sont dissimulées dans le fichier. Ce fichier est produit à partir d’une captation satellitaire.

Le format de QGIS est Shapefile (.shp)
Une couche vecteur contient la combinaison d’un certain nombre de données.
- données attributiares .dbf
- index de géométrie .shx
- système de coordonnées .prj

Un shapefile va contenir des points, des couches, et des polygones.
Mais chaque type de géométrie possède un traitement particulier.

Natural earth
NOAA National Geophysical Data Center
Souvent des données libres de droit, surtout lors d’un usage personnel.

Deux possibilités de modifications
soit de manière spécifique au projet
soit en modifiant les données proprement dites.

Choix du tracé de lignes de niveaux
Possibilités pour simplifier la géométrie
Modalités pour fermer les lignes de niveau afin de proposer des colorisations.
L’outil de neuds permet de sélectionner un nœud et retirer un certain nombre de points manuellement.

Importation possible dans illustrator avec SVG.

Il est encore possible de créer des données. Créer nouvelle couche dans laquelle va pouvoir importer des points.


## Accessibilité

En principe, lorsque Matthieu a été recruté, l’EPHE était censée s’engager dans la rédaction d’un schéma directeur pour l’accessibilité dans l’établissement. Un exemple qui montre que quand on est en situation de handicap, on est très souvent en situation de colonisation mentale.

Moi en étant en situation de handicap, c’est un peu comme si j’apartenais à un monde qui n’est pas le mien. Lorsque suit des formation, je suis obligé de mon concentrer sur l’enseignement mais aussi de refaire le travail moi-même tout seul à partir du support de cours.
Si je remarque qu’il y a le plus souvent une bonne volonté, souvent on ne sait pas comment faire. Pour ma part, j’ai l’impression de bien voir, car toujours vu de la sorte. Je ne suis pas non plus certain de connaître tout ce qui se fait. En tous les cas, depuis que je découvre ce monde, constate que c’est un monde merveilleux car tout y est paramétrable. Cependant la configuration est souvent extrêmement compliquée. Le plus souvent pour les interfaces, obligé de réutiliser un outil comme zoomtext mais payant.

À chaque fois, un peu comme s’il fallait avec les enseignants assurer un pré-cours, ce qui est le plus souvent impossible. Une des solutions trouvées pour le moment consistait à demander le PDF du cours préalablement au cours afin de pouvoir suivre en même temps (ce qui est toujours moins difficile que d’essayer de lire ce qu’il y a au tableau. Suffit simplement de le savoir et de prolonger l’effort.

Difficultés qui s’explique en partie par le fait que la part des étudiants handicapés, 0,9% des étudiants scholarisés en parcours universitaires. 
Loi sur le handicap de 2004 qui considérait que la société qui n’était pas accessibles plutôt que les handicapés qui n’avaient pas des capacité. Exemple de campus de ce type Campus Saclay. Ne serait-ce que pour ce qui concerne les examens, et délais prolongés, souvent fallu se battre pour obtenir l’application des règles. En premier lieu les gens pensent que peu important et que ne fait pas partie de leurs priorités.

Comme campus hors les murs, fais ma place tout seul. En réalité, il n’y a rien d’instituée dans la manière. Politiques généralement définies pour l’universel. Ainsi si lorsque l’on est aveugle, ou paraplégique, ce ne sont pas les mêmes les mêmes choses qui doivent être mise en place. Nécessité faisant loi, c’est moi qui doit m’adapter au monde des autres ; c’est moi qui doit m’adapter à la norme. En France, les institutions sont très lourdes, souvent des hiérarchies, une personne qui s’occupe des personnes en situation de PMR mais puis-je m’adresser à elle. En principe on devrait en tous les cas être mieux renseigné que le reste des personnels.

Comment matérialiser une telle démarche ?
Une des idées possibles consisterait à ce qu’une fois par an, les personnes qui ne sont pas en situation de handicap, soient mises dans cette situation. Aveugle, en fauteuil. Jeu de rôle qui transforme profondément les perceptions.

Quelle perception des projets dans le domaine des DHs. Souvent, l’accessibilité la dernière roue du carrosse. 
Conception des projets.
Part d’improvisation dans l’enseignement.
Apprentissages compliqués. Langage informatique un langage par définition, mais pas de confrontation avec la correction. Lorsque amis travaillent sur cahiers, comment travailler avec les notes des étudiants (d’autant que souvent dans leur langue naturelle). Reste solutions en ligne. 

Souvent de la bidouille, car le plus souvent jamais prévu.
Doit devenir un automatisme que de rendre le savoir accessible à tous.
Prix DH Awards pour l’accessibilité
Voir pour le prix français.

Sans doute beaucoup à faire. Travailler sur les contrastes pour que chacun puisse avoir accès


Il a été proposé à Humanistica de créer un groupe de travail sur l’accessibilité web. L’issue du travail consisterait à produire un Livre blanc sur le sujet.
Seulement, pas que le web. Bandes sons sur YouTube, etc.
Popcorn time qui est un logiciel de streaming, le seul que connaisse où peut agrandir les titres à volonté.
Logiciels propriétaires que ne peut généralement pas retoucher. Toutefois pourraient prévoir trois tailles de polices. Dans mac, souris et contrôle qui permet de zoomer. Contraint de monter un dossier à la MDPH pour avoir un équipement qui permet de filmer les enseignements et de zoomer sur un tableau. (3 500 euros).

Les nouvelles technologies constituent de fait des béquilles utiles. Par exemple Zotero permet d’automatiser des opérations du quotidien qui font gagner du temps à tous, mais surtout à moi. M’évite d’avoir des surcharges de travail bête, qui me permette de faire un travail honnète sans trop de difficultés. 

Il faut aussi comprendre qu’il peut être difficile pour une personne en situation de handicap d’exprimer quels sont ses besoins. 
Pas toujours évident de savoir si peut se permettre de proposer son aide ou pas.

