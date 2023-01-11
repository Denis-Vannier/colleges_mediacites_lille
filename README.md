# Profils sociaux des secteurs de collège de la métropole de Lille

**Ce répertoire contient les traitements réalisés sur les fichiers détail du recensement de 2019, afin de déterminer le profils social des parents d'élèves résidant dans chaque secteur de collège. Il est appliqué ici aux collèges de la métropole de Lille, dans le cadre d'une enquête co-écrite avec Matthieu Slisse pour Médiacités.**


<img src="https://github.com/Denis-Vannier/colleges_mediacites_lille/blob/main/CARTE_PROFILS_SOC_IRIS_2019_LILLE.png" width="800" />

Pour comprendre les origines sociales des collégiens de la métropole lilloise sans utiliser les données personnelles détenues par les rectorats, nous avons utilisé les données ouvertes de l’Insee. Certaines d’entre elles permettent de répondre assez précisément à cette question : Qui sont les parents installés dans le secteur géographique attribué à chaque collège public ? 

Les fichiers détail du recensement de la population de 2019  permettent de connaître, logement par logement, la composition sociale de plus de 25 millions de foyers en France. Dans les 520 iris de la métropole de Lille, on peut ainsi identifier 48 000 logements dans lesquels vivent près de 75 000 enfants âgés de 6 à 15 ans. Cette tranche d’âge, imposée par les données de l’Insee, correspond à l’ensemble des enfants en âge d’aller au collège au moment du recensement, auxquels s’ajoutent les écoliers qui entreront en sixième d’ici 2024.

Chaque secteur attribué à un collège comprend plusieurs iris. On peut alors déterminer un profil social détaillé de ces secteurs. Dans les cas où un quartier est partagé entre deux secteurs de collèges, on opère une redistribution des données selon la densité de population par carré de 200m (données de 2017). Nous avons ensuite calculé l'écart entre le profil social des parents qui résident dans le secteur d’un collège avec celui de l’ensemble de ces familles à l’échelle de la métropole.

Les fichiers de l’Insee que nous avons utilisés ont leurs limites : ils ne permettent pas de connaître la profession des parents ou leur niveau de vie (ils sont disponibles uniquemennt en valeurs relatives, ce qui ne permet pas des redistributions entre plusieurs iris). D’autre part, le niveau de diplôme indiqué ne concerne que la “personne de référence” du ménage. Or, ici, lorsque la famille est constituée d’un couple, c’est l’homme qui constitue la “référence” dans 73% des cas.

Et puis, évidemment, les statistiques de l’Insee ne permettent pas de dire si les enfants sont effectivement scolarisés dans le collège public correspondant au secteur. Les parents peuvent faire le choix d’inscrire leur enfant dans un établissement privé, demander une dérogation voire déclarer une autre adresse pour obtenir une place dans un collège voisin. 

Malgré tout, cette approche permet d'imaginer des redécoupages de secteurs entre des collèges voisins dont les IPS sont très différents, afin d'améliorer la mixité des deux collèges. Nous avons tenté cette expérience avec les données des secteurs de collèges Mendès France et Jules Verne, à Tourcoing. Le redécoupage que nous proposons a été obtenu par tatonnements, en changeant des iris entiers de secteurs puis en recalculant les profils sociaux, jusqu'à obtenir des chiffres similaires. Voici le résultat, tel qu'il a été publié dans Médiacités.

<img src="https://raw.githubusercontent.com/Denis-Vannier/colleges_mediacites_lille/main/COMPAR%20MENDES_JULESVERNE_V2.png?token=GHSAT0AAAAAAB5KGHT6SNB4WNPCXQPKESDCY56QIPQ" width="800" />
<img src="https://raw.githubusercontent.com/Denis-Vannier/colleges_mediacites_lille/main/REDECOUPAGE_COLL_MENDES_VERNE.png?token=GHSAT0AAAAAAB5KGHT664YSAXNWBZJSH7ECY56QKCQ" width="800" />





**SOURCES**

- Carte scolaire des collèges publics du Nord (Département du Nord): https://services.lenord.fr/trouver-mon-college-de-secteur / https://geonord-lenord.opendata.arcgis.com/pages/telechargement 

- Données par iris du recensement de la population de 2019 (INSEE). Fichiers détail "Logements ordinaires" (permet d'isoler les foyers avec enfants de 6 à 15 ans) : https://www.insee.fr/fr/statistiques/6544344?sommaire=6456104 
