# Projet_Catherine_Christelle
Projet réalisé dans le cadre du cours de python 

## Contexte et justificatif
Alors que la population française est à très grande majorité urbanisée, les problèmes d’aménagements urbains et de mobilité urbaine ont pris une place de plus en plus importante dans les débats politiques et la recherche scientifique. Avec près de 80 % de sa population habitant en ville, la France illustre les enjeux et les défis qui accompagnent les questions de mobilité urbaine : qualité de vie, durabilité environnementale, santé publique autour des enjeux de pollution, etc. Autant d’éléments qui contribuent au bien-être général de la pollution. Dans le contexte de la forte pollution et des problèmes de congestion urbaine dans les métropoles françaises, les vélos ont fait l’objet de nombreuses politiques publiques visant à développer leur usage : aide à l’achat de vélo, développement de stations en libre-service, construction de pistes cyclables, etc. En effet, la généralisation de la pratique du vélo représente une solution potentielle à un certain nombre de ces enjeux. Dans ce contexte, notre recherche explore la répartition géographique des aménagements et des stations ‘vélib’ en île de France ainsi que leurs déterminants. La région Île-de-France a mis en œuvre une politique significative de stations de vélos en libre-service, et nous cherchons à expliquer les critères de développer des aménagements cyclables dans l'optique d'évaluer sa pertinence par rapport aux besoins de la population.

## Énoncé du problème :
Alors que l'adoption du vélo comme mode de transport urbain durable est en hausse, il existe un besoin de comprendre les déterminants de la distribution et de l'accessibilité des aménagements cyclables, en particulier dans le contexte des bornes Vélib'et de la densité des pistes cyclables en île de France et des facteurs sociodémographiques. Notre recherche vise à répondre aux questions clés suivantes :
1. La répartition spatiale des bornes Vélib' :
    * Quelle est la répartition spatiale des stations Vélib' en IDF ?       
    * Existe-t-il des facteurs discernables qui influencent l'emplacement des bornes Vélib' dans les différents quartiers de la ville ?
2.  Analyse régionale de la densité des pistes cyclables :
    * Comment la densité des pistes cyclables varie-t-elle dans les différentes commune de la région ?
    * Existe-t-il des corrélations entre la densité des pistes cyclables et les caractéristiques urbaines ou les facteurs sociodémographiques ?
    * Existe-t-il une corrélation entre la densité des pistes cyclables et répartition spatiale des vélib ?
3. Déterminants des équipements de mobilité urbaine :
    * Quels sont les indicateurs sociodémographiques qui contribuent au développement et à l'utilisation des infrastructures cyclables dans les zones urbaines ?
  
## Structure du projet :

**main.ipynb** : notebook permettant de faire tourner l'entierté du projet en utilisant successivement les notebooks 1, 2 et 3.

**0_dep.ipynb** : notebook supplémentaire permettant de télécharger les modules moins courants que nous utilisons.

**1_base.ipynb** : création de la base d'étude à partir de bases de données du ministère des transports, de l'insee et de la région Ile de France.

**2_desc.ipynb** : analyses descriptives et spatiales sur la base d'étude.

**3_model.ipynb :** modélisation économétrique sur la base d'étude.

## Les différentes bases de données :

https://smartregionidf.opendatasoft.com/explore/dataset/velib-disponibilite-en-temps-reel/export/?disjunctive.name&disjunctive.is_installed&disjunctive.is_renting&disjunctive.is_returning&disjunctive.nom_arrondissement_communes : velib’

https://transport.data.gouv.fr/datasets/amenagements-cyclables-france-metropolitaine/#community-resources : base de données contient l’ensemble des aménagements cyclables de France métropolitaine numérisés dans OpenStreetMap et traités par Geovelo afin de les restituer selon le schéma national des aménagements cyclables.

https://www.data.gouv.fr/fr/datasets/bases-de-donnees-annuelles-des-accidents-corporels-de-la-circulation-routiere-annees-de-2005-a-2022/ : bases de données annuelles des accidents corporelles de la circulation routière (2005 à 2022)

https://www.insee.fr/fr/statistiques/2521169#consulter : base du comparateur des territoires de l'insee
