# Profils sociaux des secteurs de collège de la métropole de Lille

*Ce répertoire détaille les traitements réalisés en python sur les fichiers détail du recensement de 2019, afin de déterminer le profils social des parents d'élèves résidant dans chaque secteur de collège. Il s'applique ici aux secteurs de collèges tels qu'ils sont définis en 2022 par le Département du Nord, pour les collèges de la métropole de Lille. Ce travail a été réalisé dans le cadre d'une enquête pour le média d'investigation locale Médiacités.*

Pour comprendre les origines sociales des collégiens de la métropole lilloise sans utiliser les données personnelles détenues par les rectorats, j’ai utilisé les données ouvertes de l’Insee. Certaines d’entre elles permettent de répondre assez précisément à cette question : Qui sont les parents installés dans le secteur géographique attribué à chaque collège public ? 

Les fichiers détail du recensement de la population de 2019  permettent de connaître, logement par logement, la composition sociale de plus de 25 millions de foyers en France.

Dans les 520 iris de la métropole de Lille, on peut ainsi identifier 48 000 logements dans lesquels vivent près de 75 000 enfants âgés de 6 à 15 ans. Cette tranche d’âge, imposée par les données de l’Insee, correspond à l’ensemble des enfants en âge d’aller au collège au moment du recensement, auxquels s’ajoutent les écoliers qui entreront en sixième d’ici 2024.

J’ai ensuite calculé un profil social moyen de l’ensemble de ces familles à l’échelle de la métropole.  Il s’agit ensuite de voir à quel point le profil social des parents qui résident dans le secteur d’un collège diffère du profil moyen.

Chaque secteur attribué à un collège comprend plus iris. On peut alors déterminer un profil social détaillé de ces secteurs. Dans les cas où un quartier est partagé entre deux secteurs de collèges, on opère une redistribution des données selon la densité de population par carré de 200m (données de 2017).

Les fichiers de l’Insee que nous avons utilisés ont aussi leurs limites : ils ne permettent pas de connaître la profession des parents ou leur niveau de vie. D’autre part, le niveau de diplôme indiqué ne concerne que la “personne de référence” du ménage. Or, ici, lorsque la famille est constituée d’un couple, c’est l’homme qui constitue la “référence” dans 73% des cas.

Et puis, évidemment, les statistiques de l’Insee ne permettent pas de dire si les enfants sont effectivement scolarisés dans le collège public correspondant au secteur. Les parents peuvent faire le choix d’inscrire leur enfant dans un établissement privé, demander une dérogation voire déclarer une autre adresse pour obtenir une place dans un collège voisin. 


**SOURCES**

- Carte scolaire des collèges publics du Nord (Département du Nord): https://services.lenord.fr/trouver-mon-college-de-secteur / https://geonord-lenord.opendata.arcgis.com/pages/telechargement 

- Données par iris du recensement de la population de 2019 (INSEE). Fichiers détail "Logements ordinaires" (permet d'isoler les foyers avec enfants de 6 à 15 ans) : https://www.insee.fr/fr/statistiques/6544344?sommaire=6456104 
