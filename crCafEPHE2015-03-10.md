# CR Caf’EPHE 10 mars 2015

## Programme

- (P1) Méthodologies d’acquisition numérique et modélisation appliquée aux arts et à l’archéologie (Dominique Lauvernier)
- (P2) Vers une table ronde interdisciplinaire sur les projets estudiantins impliquant les HN à l’EPHE ? (débat)
- (P3) La contribution de XML-TEI dans la pérennisation des corpus (E.Chateau)
 

## Méthodologies d’acquisition numérique et de modélisation appliquées à l’histoire de l’art et à l’archéologie

### Introduction

Reconstitution des espaces scéniques de la cour de France. Humanités numériques appliquées aux arts du spectacle. Membre d’un groupe de recherche international sur le théâtre. Travail également sur la patrimoine de la danse indienne.

Comme tout spécialiste des mondes classiques, approche pluri-disciplinaire.
Utilisation régulière des outils 2D et 3D.

### Présentation générale

Revue des outils disponibles.
- Plate-forme : Windows essentiellement, Linux, mais oublier Mac.
- Scan 3D : bricolage possible ; instruments professionnels et logiciels
- Motion capture : matériel professionnel
- Modélisation 3D : Snapshot, Blender libre, utilisation gratuite pour l’enseignement de Autodesk, logiciels dédiés pour la 3D
- Réalité virtuelle : quelques logiciels libres issus des jeux vidéos ; souvent difficiles et payants. Pour l’architecture, Autodesk Navisworks
- Montage vidéo : pas de logiciels libres.

### Scan laser 3D

Outil conçu pour mesurer différents points sur un objet tridimensionnel, qui peut être un simple interfact, jusqu’à un bâtiment voire un terrain.

ex : Tablettes cunéiformes, Forma Urbis, Michelangelo, Ankor

Projet Michelangelo Stanford

c. 1990, Stanford PLY un des formats mis au point dans le cadre de ce travail 

Interrompu faute de financement. Dispositif lourd installé pour pouvoir placer un pointeur laser tout au long de la statue. On obtient une image en nuage de points. C’est une représentation spatiale très particulière qui est le plus souvent associée à des photos : on associe un point du nuage de point à une couleur tirée de la photographie.

Exemple de St Matthew, résolution 1/10e de mm. 
Fichier de points qui peut être transformé en un maillage. Finesse des points qui donne une précision de ce qui a été acquis au moyen de cette technique.

Ce travail peut être effectué sur des tablettes sur lesquelles était représenté le plan de Rome, ou des manuscrits pour en acquérir le relief.

Forma Urbis, plan de Rome d’un des forums impériaux gravé. Les modèles de cet objet sont mis en ligne sur le site de l’université de Stanford.
- version filaire
- version surfacée
- possibilité de restitutions volumétriques avec ombrage

Travail d’acquisition de tablettes cunéïformes avec un système d’acquisition par laser. Logiciel dédié pour la reconnaissance des caractères cunéïformes et d’assemblage des fragments.

Acquisition qui peut également être réalisée avec les moyens du pauvre. C’est par exemple le cas de ce qui a été effectué par une équipe d’archéologues en Ardèche. Ils ont ainsi mis en place un protocole consistant à mettre au sol des repères. Envoi d’un cerf-volant pour acquérir la Photo avec un GPS, ce qui leur permet de récupérer un nuage de points qui va permettre la mise au point d’une image.

Protocole complexe qui implique un certain nombre filtrages. Plaquage en courbe d’orthophotographie.

### Motion Capture

En matière de visualisation tridimentionnelle, il est également possible de capter les mouvements. Ces techniques sont notamment mises en œuvre pour l’étude des mouvements sportifs ou de la danse. Acquisition par des capteurs, puis restitution sur un modèle 3D du squelette humain. Cela peut aussi être transposé avec un avatar virtuel.


### Modélisation 3D qui peut s’appliquer à tout type de sources

Peut notamment être appliquée à des anastyloses numériques. Par exemple, reconstitution du temple d’Ankor. Construit sur du sable. Démontage du temple = 300 000 pierres. Perte de la documentation avec la guerre. Complexité telle que l’informatique n’y suffisait pas. Mais reconstitution d’un modèle 3D.

Réalité virtuelle, exemple de reconstitution de la Rome antique.  Réalité virtuelle qui consiste à pouvoir visiter des lieux. Filme l’écran et l’orateur. cf. Plan de Rome, Université de Caen.

Réalité augmentée, Cluny Ecclesia Major, équipe des Arts et métiers qui a conduit un immense travail de reconstitution de l’immense abbaye de Cluny. Lors de la visite peut voir le modèle 3D sur écran.

Des bases de données
TACE (2D) sur les théâtres d’Europe cenrtale
Theatre Finder (3D) prévue
Stanford Forma Urbis (2D et 3D) exemplaire car dispose de la documentation, des modèles et des clichés. Plus de 1000 fragments en ligne.

### Exemple de ma démarche

Travaille sur la reconstitution des espaces intérieurs de la cour de France. 17e au 19e siècle. 

- Utilisation des techniqeus de modélisation, part des plans survivants (rasterisation) dont fait sortir des formes en 3D (extrude).
- Navigation en temps réel.
- Intégration d’un film sur fond vert.
- Possibilités d’utilisations pédagogique

Exemple de mise en œuvre sur un plan de Levau. Extrude les formes puis reconstitue le bâtiment.

Autre exemple sur un projet de théâtre type de Pozzo. Se déplaçant à l’intérieur, s’aperçoit que son modèle est parfait. Une connaissance extrêmement précise des arts de la scène que peut montrer.
Modélisation réalisée à partir d’une simple élévation et d’un plan.

Autre exemple cour de Florence. Document récemment identifié et qui permet de reconstituter sans doute la technique de la scène. Permis de reconstituer le dispositif scénique, interface au-dessous pour logiciel temps réel.

Autre exemple, technique d’anastylose numérique.

Exemple de musée où réunit des objets de provenances diverses.

Jeux pédagogiques où il s’agit de remettre les décors aux bons endroits.

Passage à l’inclusion de danseurs dans le modèle 3D.

### Questions et échanges autour d’exemples

Question du rendu

Interprétation architecturale
 
L’EPHE a acquis un scan 3D, on pourra numériser des objets jusqu’à 50 cm.

Merci de nous avoir fait cette présentation. Démarche intéressante pour laquelle s’aperçoit bien de toutes les compétences nécessaires pour arriver à mettre en œuvre ce genre de reconstitutions. Qu’est-ce que ces approches ont pu apporter pour réviser l’analyse des plans ?

Exemple de projet pour lesquels dispose de plans précis. Mais ne fait pas toujours le lien entre la réalité de l’aménagement et les vues. Par exemple s’aperçoit que triphorium profond mais ne ménage probablement pas d’espace pour le public.

Analyse qui permet de bien visualiser les flux d’entrée et de sortie. Plutôt un outil de visualisation qui me sert de feuille de dessin, d’outil d’interprétation. Souvent un modèle très brut, mais qui suffit pour percevoir si le projet fonctionnait du point de vue des arts de la scène.

Une démarche très proche de ce que font les archéologues. Cette question posée. Savoir si l’analyse architecturale sans aller dans la reconstitution 3D ne peut pas nous apporter la même chose, ou plus. Par certains calculs de perspective, par un plan peut parvenir à la même reconstitution. 

Mais ne dispose pas alors de tous les angles. Il y a des choses que l’on croit voir, mais que l’on ne voit pas. Rapport entre les élévations avec la galerie en vis à vis.
Il y a également une dimension temporelle qui se dégage des données, par exemple pour la navigation en temps réel, une partition qui se dégage. Un outil qui comme la maquette construite permet un certain nombre de choses. Mais différent.

Question de la résolution. Possibilités de naviguer dans l’objet, possibilité de se mettre en situation réelle.

Pour les fouilles du proche-orient. Des reconstitutions 3D. Toute la question est celle du pourcentage de restitution et d’interprétation qui est inclue dans le projet. Effet de réalité. Absoluement magnifique, mais très vite ajoute l’idée de l’interprétation. La stratigraphie en archéologie déjà en elle-même une interprétation.

Toute numérisation du réel une modélisation, c’est-à-dire une interprétation. Les reconstitutions 3D avec navigation : si les données sont exactes, la visualisation est une simulation cinématographique avec objectifs cinématographiques. Implique donc nécessairement une déformation du réel qui répond à des objectifs d’aujourd’hui, même si le modèle est exact.

Exemple du forum. Image mentale que le temple de Jupiter qui domine la coline et Rome. Modèle 3D qui a suggéré que l’on s’était trompé. Nouvelle interprétation proposée de ce qui était compris comme un tabaluraium. Trois temples... Depuis le Forum, on ne voit donc pas le temple de Jupiter. Il est nécessaire de monter sur le toît d’une basilique pour voir le grand temple de Jupiter. Cela révise totalement notre image mentale constituée depuis la Renaissance. Ici grâce à la 3D que s’en est aperçu.

Ex. de travail sur les tablettes 3D.
Travail de segmentation avec des outils 3D. Repérage des caractères avec les outils, marquage des segments, supression des éléments inutiles pour simplifier le modèle et faciliter la navigation. Travail sur les écritures et définition de polygones 3D.

Ex. travail sur les frangements.
LS7 travail sur plusieurs fragments pour les regrouper en un seul bloc. Seulement des menus appropriés à la base de données.

Autodesk
Identifiants téléchargeables pour enseignant.
http://www.autodesk.fr/solutions/mac-compatible-software

Téléchargement d’un fichier de tablette dans 3DS Max
Il est possible de manipuler l’objet, de zoomer et se déplacer. Zoom qui présente le maillage : ce qui correspond à la transformation du nuage de point par rapport au rendu du laser. 

Possibilité de manipulations, de rendus photos avec détails, avec ombrage.

Exemple du plan de Rome de Stanford
Visualisation filaire, fait apparaître 18 Millions de polygones.


Question sur l’utilisation d’outils qui permettent à partir de plusieurs vues d’un même objet de reconstituer un modèle 3D. Quel apport.

Séminaire ephilologie, prise de mesure pour repérer l’écriture de chaque scribe. Est-ce que la mesure des profondeurs n’a pas un intérêt. Heidelberg, travaillent sur ce genre de choses. Reconnaissance automatique de cunéiformes.

Article sur les garigues : Images et modèles 3D en milieu naturel.
Estelle Ployon et al.
Acquisition et traitement...

Toujours conserver à l’esprit le rapport entre l’investissement temps / résultat. On peut facilement investir un temps important pour arriver à des résultats guère plus intéressants par d’autres moyens plus rapides.


## Débat sur l’organisation d’une table ronde interdisciplinaire sur ces sujets

L’occasion d’ouvrir à de nouveaux projets. Est-ce que cela vous intéresserait, de quelles manière aborder un tel projet.

Un projet sur lequel pourrait travailler pour une mise en place en 2016. Réfléchir à ce que pourrait être la contribution de l’EPHE à une telle table ronde.
D’abord savoir pour quel but. S’il s’agit d’ensuite donner des enseignements qui nous permettraient par la suite de développer des nouveaux types d’analyse. Bien sûr des formations. À quoi cela pourrait servir ?

On développe tous individuellement notre base de données sur notre corpus. Comment chacun pourrait échanger ses données par l’intermédiaire de bases de données ouvertes. Comment pouvoir faire cela, sans discussion ou échange sur les besoins de chacun.

 
