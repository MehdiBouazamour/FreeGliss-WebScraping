# Objectif

L'objectif de ce cas était de scraper toutes les informations possibles concernant les produits "Skis" sur le site internet FreeGliss. Ensuite, faire une visualiation sur PowerBi des résultats pour avoir une vue d'ensemble des produits proposés, les marques, les prix, etc...

Vous retrouverez deux fichiers python :

Freegliss : Un script python qui se charge du scraping des informations de chaque ski

Bot scrap : L'objectif est de développer un bot capable d'automatiser la recherche des stocks de chaque modèle de ski disponible. Le bot simule le processus d'ajout de ski au panier jusqu'à ce qu'un message indique que le produit n'est plus en stock. Ensuite, il comptabilise le nombre d'ajouts effectués pour estimer la disponibilité du produit. Une particularité importante est que chaque modèle de ski est disponible dans différentes catégories (représentant l'état du ski) et dans plusieurs tailles. Par conséquent, le bot doit effectuer ce processus de comptage pour chaque modèle de ski, pour chaque catégorie et pour chaque taille disponible.

Et enfin vous retrouverez des images du Dashboard PowerBi avec ses différents onglets.



# Contexte

Olist aimerait désormais augmenter son offre sur le segment du sport, en incitant des marketplaces d'articles de sport à rejoindre la plateforme. 
Pour affiner sa stratégie vis-à-vis de ce type de vendeurs, Olist a besoin d'analyser leur offre et leur positionnement, pour mieux connaitre le marché sur lequel ils évoluent.
En particulier, les Sales d'Olist s'intéressent à FreeGlisse, une plateforme de vente en ligne de matériel de ski d'occasion. Leur ojectif est d'emmagasiner le plus d’informations possibles à partir de ce que FreeGlisse affiche sur son site web.


# Instructions

Olist voudrait se concentrer dans un premier temps sur le segment des skis. Les informations à étudier incluent : le nombre d'annonces sur les skis, les prix pratiqués, la répartition de l’offre entre les différentes sous-catégories, eventuellement la profondeur des stocks (= le nombre de produits disponibles, ou le nombre de tailles disponibles par produit), et tout ce que je pense qui serait intéressant pour analyser le positionnement marché de FreeGlisse.
Ces informations seraient d’autant plus intéressantes si elles étaient étudiées par type de ski (indiqué dans la Fiche Technique de chaque ski). N'hésitez pas à effectuer les regroupements qui vous semblent pertinents, à faire des analyses quantitatives et qualitatives, en utilisant pandas et en faisant de beaux graphiques. Pour les graphiques, j'utiliserai PowerBI.
Côté technique, 2 compétences pourront être mises en oeuvre: le crawling entre les différentes pages du site, pour observer l’ensemble des offres de skis d’occasion, et le scraping des pages individuelles, avec différentes infos à aller chercher.
Pour finir, l'objectif de ce cas est aussi de tirer de ces analyses des insights business, en particulier des conclusions sur le positionnement commercial de FreeGlisse et les spécificités qu'il pourrait apporter à Olist.
