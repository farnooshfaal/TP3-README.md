# TP3-README.md

Exportation et traitement des données :
1. Appliquez un écrivain dans FME pour exporter les couches d'entrée transformées (données sur le revenu, sections de recensement, quartiers dans un fichier de formes polygonal contenant le revenu moyen et les taux de vol criminel par secteur de recensement en 2019 et 2020.
2. Connectez-vous au compte ArcGIS Onllne de l'organisation via ArcGIS Pro - ajoutez un fichier de formes à la table des matières, partagez la couche de fichiers de formes en tant que service d'entités et chargez-la sur ArcGIS Online
3. Créer une nouvelle carte, tableau de bord, WebScene, WebExperience
4. Ajoutez des services d'entités à la carte Web et configurez les fenêtres contextuelles et les étiquettes, la symbologie.
5. Ajouter une carte Web au tableau de bord et configurer la matrice et les jauges de nuages de points, les indicateurs pour filtrer l'étendue de la carte
6. Ajoutez une couche d'entités hébergée du fichier de formes au WebScene et configurez la symbologie et les fenêtres contextuelles comme la carte Web
7. Ajoutez les éléments Web Scene, Web Map et Dashboard à WebExperience et configurez la mise en page


Utilisations du widget et objectif de l'expérience :

L'Utilisateur utilisera le tableau de bord pour répondre à ses questions concernant :
1. Les secteurs de recensement contenant les plus grands nombres de crimes en 2019 et 2020
2. Les secteurs de recensement avec les différences les plus grandes aux plus petites dans les crimes entre les deux années
3. Les courbes de tendance entre revenu moyen et taux de vol
4. Calcul de la moyenne de ces variables par le filtre spatial de l'étendue de la carte lorsque l'utilisateur parcourt les secteurs de recensement du quartier

Indicateurs du tableau de bord :

En haut à gauche - Permet à l'utilisateur de voir la progression du nombre de vols avec les valeurs croissantes du revenu moyen par secteurs de recensement dans l'étendue de la carte.
Le but de cet indicateur de tableau de bord est d'aider les utilisateurs à comprendre s'il existe une relation entre les revenus et le vol dans les zones affichées sur la carte. Si le graphique montre une tendance claire à l'augmentation du nombre de vols à mesure que le revenu moyen diminue, cela pourrait suggérer que la pauvreté et la criminalité sont corrélées dans la région.

![Picture4](https://user-images.githubusercontent.com/55294090/231183218-8ddeb07a-a853-44cc-a358-3c3c0092ea79.png)

En bas à gauche - Permet à l'utilisateur de voir le revenu moyen entre tous les secteurs de recensement dans l'étendue de la carte par rapport aux secteurs de recensement avec le revenu moyen le plus élevé. Le but de cet indicateur de tableau de bord est de fournir aux utilisateurs un aperçu rapide de la répartition des revenus dans la zone sélectionnée. En comparant le revenu moyen de tous les secteurs de recensement aux secteurs de recensement aux revenus les plus élevés, les utilisateurs peuvent avoir un aperçu de l'inégalité des revenus et des disparités économiques qui peuvent exister dans la région.

![Picture2](https://user-images.githubusercontent.com/55294090/231174129-6195803c-8584-45d9-8819-f7898a44d0a6.png)

En haut et en bas à droite - Jauges pour afficher les vols moyens pour les secteurs de recensement dans l'étendue de la vue du tableau de bord de l'utilisateur - compare entre 2019 et 2020.
L'objectif de ces indicateurs de tableau de bord est de fournir aux utilisateurs un aperçu rapide de l'évolution des taux de vol entre 2019 et 2020 au sein de la zone sélectionnée. Les jauges permettent aux utilisateurs de voir en un coup d'œil si les taux de vol ont augmenté, diminué ou sont restés relativement stables au fil du temps.

![Picture3](https://user-images.githubusercontent.com/55294090/231175975-cc89b981-5de7-439a-a5cf-053d6ce90bee.png)


Gadgets d'expérience :
Widget de carte montrant la scène Web visualisant les pistes de recensement en extrudant la valeur d'attribut (revenu moyen) pour montrer les proportions des différences de revenu moyen dans le quartier avec des blocs de recensement cliquables affichant des fenêtres contextuelles détaillant le revenu moyen et les vols des secteurs de recensement individuels en 2019 et 2020, respectivement.
Vous pouvez basculer entre la carte du revenu moyen 3d et la carte du rapport de différence de criminalité 2d et une animation entre les deux avec l'échange de légende peut également donner à l'utilisateur une meilleure idée spatiale des augmentations, des diminutions, des totaux et des moyennes de la criminalité tout en interagissant avec le cartes de tableau de bord, jauges et indicateurs.

Le plan et la composition de ce tableau de bord peuvent être pertinents pour les villes mondiales ayant des taux de criminalité et de revenu similaires, car il fournit un moyen complet et interactif d'explorer la relation entre ces deux variables. En utilisant une combinaison de cartes, de jauges et d'indicateurs, ce tableau de bord permet aux utilisateurs de comparer facilement les taux de vol entre différents secteurs de recensement et périodes, tout en fournissant des informations sur les facteurs socio-économiques qui peuvent être à l'origine de ces tendances.

En outre, le widget de carte de ce tableau de bord utilise un fond de carte vectoriel pour créer des contours et des images de fond de carte raster avec des données de recensement vectorielles transparentes, ce qui permet une représentation plus précise et détaillée du quartier. Cette approche peut être appliquée à d'autres villes mondiales présentant des caractéristiques similaires, fournissant un outil utile aux décideurs politiques, aux forces de l'ordre et aux dirigeants communautaires pour comprendre les schémas de criminalité et développer des interventions ciblées.
https://experience.arcgis.com/experience/f2bd59e3e05b4fae8ee8f686e85af04b
