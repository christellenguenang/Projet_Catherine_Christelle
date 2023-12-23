# Projet_Catherine_Christelle
Projet réalisé dans le cadre du cours de python 

## Contexte et justificatif
Alors que la population française est à très grande majorité urbanisée, les problèmes d’aménagements urbains et de mobilité urbaine ont pris une place de plus en plus importante dans les débats politiques et la recherche scientifique. Avec près de 80 % de sa population habitant en ville, la France illustre les enjeux et les défis qui accompagnent les questions de mobilité urbaine : qualité de vie, durabilité environnementale, santé publique autour des enjeux de pollution, etc. Autant d’éléments qui contribuent au bien-être général de la pollution. Dans le contexte de la forte pollution et des problèmes de congestion urbaine dans les métropoles françaises, les vélos ont fait l’objet de nombreuses politiques publiques visant à développer leur usage : aide à l’achat de vélo, développement de stations en libre-service, construction de pistes cyclables, etc. En effet, la généralisation de la pratique du vélo représente une solution potentielle à un certain nombre de ces enjeux. Dans ce contexte, notre recherche explore la répartition géographique des aménagements et des stations ‘vélib’ en île de France ainsi que leurs déterminants. La région Île-de-France a mis en œuvre une politique significative de stations de vélos en libre-service, et nous comparerons ce réseau à d'autres infrastructures de mobilité urbaine, telles que les bus, afin d'évaluer sa pertinence par rapport aux besoins de la population.

## Focus sur l’Ile-de-France
Le système de vélos en libre-service Vélib' est devenu une partie intégrante de la mobilité urbaine parisienneet dans toute la France en général, offrant aux citoyens et aux visiteurs un mode de transport alternatif et respectueux de l'environnement. En examinant les emplacements et les caractéristiques des stations Vélib' en île de France, nous cherchons à comprendre la distribution spatiale de ces installations et les facteurs qui influencent leur emplacement dans les différentes communes de la région.
Simultanément, nous étendons notre analyse à un champ plus large, en considérant la densité des pistes cyclables à travers la France. Comprendre les variations de la densité des pistes cyclables nous permet d'évaluer l'infrastructure cyclable au niveau national, offrant ainsi une perspective globale sur l'état des équipements de mobilité urbaine. Pour compléter ces ensembles de données spatiales, nous incorporons des indicateurs sociodémographiques, afin d'identifier les déterminants qui influencent le développement et l'utilisation des infrastructures cyclables.

## Énoncé du problème :
Alors que l'adoption du vélo comme mode de transport urbain durable est en hausse, il existe un besoin de comprendre les déterminants de la distribution et de l'accessibilité des aménagements cyclables, en particulier dans le contexte des bornes Vélib'et de la densité des pistes cyclables en île de France et des facteurs sociodémographiques. Notre recherche vise à répondre aux questions clés suivantes :
1. La répartition spatiale des bornes Vélib' :
    * Quelle est la répartition spatiale des stations Vélib' en IDF ?       
    * Existe-t-il des facteurs discernables qui influencent l'emplacement des bornes Vélib' dans les différents quartiers de la ville 
2.  Analyse nationale de la densité des pistes cyclables :
    * Comment la densité des pistes cyclables varie-t-elle dans les différentes commune de la région ?
    * Existe-t-il des corrélations entre la densité des pistes cyclables et les caractéristiques urbaines ou les facteurs sociodémographiques ?
    * Existe-t-il une corrélation entre la densité des pistes cyclables et répartition spatiale des vélib ?
3. Déterminants des équipements de mobilité urbaine :
    * Quels sont les indicateurs sociodémographiques qui contribuent au développement et à l'utilisation des infrastructures cyclables dans les zones urbaines ?

Les différentes bases de données :

https://smartregionidf.opendatasoft.com/explore/dataset/velib-disponibilite-en-temps-reel/export/?disjunctive.name&disjunctive.is_installed&disjunctive.is_renting&disjunctive.is_returning&disjunctive.nom_arrondissement_communes : velib’


https://www.velib-metropole.fr/donnees-open-data-gbfs-du-service-velib-metropole : ensemble des données disponibles sur l’api vélib


https://www.data.gouv.fr/fr/reuses/terravisu-densite-damenagements-cyclables/ : densité d’aménagements cyclables / communes


https://transport.data.gouv.fr/datasets/amenagements-cyclables-france-metropolitaine/#community-resources : base de données contient l’ensemble des aménagements cyclables de France métropolitaine numérisés dans OpenStreetMap et traités par Geovelo afin de les restituer selon le schéma national des aménagements cyclables.


https://www.data.gouv.fr/fr/reuses/terravisu-cyclotourisme/ : cyclotourisme (cartographies des grands itinéraires cyclables)


https://prim.iledefrance-mobilites.fr/fr/jeux-de-donnees/amenagements-bus-en-ile-de-france : aménagements bus IDF pour comparer avec les pistes cyclables (csv ou json)

bases sociodémographiques (Github)

Potentielles pistes supplémentaires :

https://www.data.gouv.fr/fr/datasets/bases-de-donnees-annuelles-des-accidents-corporels-de-la-circulation-routiere-annees-de-2005-a-2022/ : bases de données annuelles des accidents corporelles de la circulation routière (2005 à 2022)

