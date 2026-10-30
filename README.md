# Accidents routiers en France en 2018

Ce projet utilise Python pour étudier les accidents routiers en France en 2018. Il cherche à comprendre comment la météo, l’heure de la journée et le type d’usager sont liés à la gravité des blessures.

## Questions étudiées

- Les blessures sont-elles plus graves lorsqu’il y a du brouillard ou de la pluie ?
- À quelles heures les blessures sont-elles les plus graves ?
- Les piétons sont-ils plus vulnérables que les conducteurs et les passagers ?
- Comment ces différences évoluent-elles selon la météo ?

Les résultats sont présentés sous forme de graphiques dans le notebook Jupyter, le fichier qui contient le code Python et ses résultats.

## Source des données

Les données proviennent de la base officielle des accidents corporels de la circulation routière de l’**ONISR** (Observatoire national interministériel de la sécurité routière), pour l’année **2018**.

Les quatre fichiers CSV décrivent :

- **Les caractéristiques** : date, heure et conditions météorologiques de l’accident.
- **Les lieux** : informations sur la route et le lieu de l’accident.
- **Les usagers** : personnes impliquées, catégorie d’usager et gravité des blessures.
- **Les véhicules** : véhicules impliqués dans l’accident.

Le PDF inclus explique les variables de la base ONISR.

## Fichiers du projet

- `Data final project code.ipynb` : code de l’analyse et graphiques.
- `ACC-caracteristiques-2018.csv`
- `ACC-lieux-2018.csv`
- `ACC-usagers-2018.csv`
- `ACC-vehicules-2018.csv`
- `ACC-description-des-bases-de-donnees-onisr-annees-2005-a-2018.pdf` : documentation des données.
- `requirements.txt` : bibliothèques Python nécessaires.

## Lancer le projet

1. Télécharger le dépôt et installer Python.
2. Ouvrir un terminal dans le dossier téléchargé et installer les bibliothèques :

   ```sh
   pip install -r requirements.txt
   ```

3. Démarrer Jupyter :

   ```sh
   jupyter notebook
   ```

4. Ouvrir `Data final project code.ipynb` et exécuter les cellules dans l’ordre. Garder les fichiers CSV dans le même dossier que le notebook.

## Lire les résultats

Dans cette analyse, une blessure grave correspond à une personne tuée ou hospitalisée. Les pourcentages portent sur les personnes impliquées dans les accidents recensés.

L’analyse montre des liens entre les conditions de l’accident et la gravité des blessures. Elle ne suffit pas, à elle seule, à prouver qu’un facteur est la cause de ces blessures.
