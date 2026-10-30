# Accidents routiers en France — ONISR 2018

Projet d’analyse des liens entre conditions météorologiques, heure, catégorie d’usager et gravité des blessures.

## Contenu

- `Data final project code.ipynb` : notebook d’analyse et graphiques.
- Quatre fichiers CSV ONISR 2018 : caractéristiques, lieux, usagers et véhicules.
- PDF de description des bases ONISR 2005–2018.

## Exécution

Installer Python et les dépendances :

```sh
pip install -r requirements.txt
jupyter notebook
```

Ouvrir le notebook et exécuter les cellules depuis ce dossier, afin de conserver les chemins relatifs vers les CSV.

## Méthode et limites

Le notebook fusionne les caractéristiques des accidents avec les usagers et les lieux. Il définit comme graves les modalités 2 et 3 de `grav`, puis compare les proportions selon la météo, l’heure et la catégorie d’usager.

Les lignes analysées correspondent aux usagers après fusion : les taux doivent être interprétés au niveau des usagers, et non comme une proportion d’accidents distincts. Les résultats sont descriptifs et ne démontrent pas une causalité ni un risque par trajet.

## Provenance

Fichiers repris de l’archive fournie `final project (2).zip`. Ce dépôt ne définit pas de nouvelle licence pour ces fichiers ; consulter les conditions de la source ONISR avant redistribution.
