# Hackaviz-2024: Les épreuves des Jeux Olympiques et Paralympiques de Paris 2024

![](images/clipboard-1507555475.png)

Nous vous proposons cette année un jeu de données sur les épreuves des Jeux de Paris 2024.\
Le jeu de donnée principal est agrémenté d'un jeu subsidiaire sur les lieux de restauration à proximité des épreuves.

Retrouvez les règles et les modes d’évaluation sur la page des règles de l’Hackaviz de l’association Toulouse DataViz (TDV).

N’hésitez pas à nous contacter sur le discord du Toulouse DataViz pour discuter entre participants, si vous avez besoin d’aide à propos des données ou pour rapporter des erreurs dans le jeu de données.

Bonne chance !

## Format des données

Chaque jeu de donnée est disponible dans plusieurs formats à votre convenance:\
- parquet

 - xlsx

 - csv

## Description des données

Le jeu de données `paris_2024` contient chacune des sessions programmées aux jeux 2024

| Nom de colonne      | Description                                                                                        | Exemple                           |
|------------------|------------------------------------|------------------|
| Jeux                | Jeux Olympiques ou Paralympique                                                                    | Paralympiques                     |
| Discipline          | La discipline olympique                                                                            | Para Taekwondo                    |
| Épreuve             | description de l'épreuve                                                                           | K44 +80 kg                        |
| Phase               | phase de l'épreuve                                                                                 | Matchs pour la médaille de bronze |
| Genre               | épreuve Mixte, Femmes ou Hommes                                                                    | Femmes                            |
| Début               | date et heure de démarrage de l'épreuve                                                            | 2024-08-09 18:15:00.00            |
| Fin                 | date et heure de fin de l'épreuve                                                                  | 2024-08-09 22:00:00.00            |
| Lieu                | le site ou le stade de l'épreuve                                                                   | Arena Champ-de-Mars               |
| Session             | le code de la session pour acheter vos billets                                                     | PTKW06                            |
| latitude            | la latitude géographique du `Lieu`                                                                 | 48.866                            |
| longitude           | la latitude géographique du `Lieu`                                                                 | 2.3124                            |
| ville               | la ville accueillant l'épreuve et son code de département                                          | Paris (75)                        |
| capacité            | la capacité d'accueil du public du `Lieu`                                                          | 3349                              |
| Enjeu               | l'enjeu de l'épreuve, parmi Cérémonie, Médailles ou Qualifications.                                | Qualifications                    |
| Catégorie_First     | Le prix des places pour la catégorie "First" (€).                                                  | 100                               |
| Catégorie_A         | Le prix des places pour la catégorie A (€).                                                        | 80                                |
| Catégorie_B         | Le prix des places pour la catégorie B (€).                                                        | 65                                |
| Catégorie_C         | Le prix des places pour la catégorie C (€).                                                        | 50                                |
| Catégorie_D         | Le prix des places pour la catégorie D (€).                                                        | 35                                |
| Catégorie_E+        | Le prix des places pour la catégorie E+ (€).                                                       | 250                               |
| Catégorie_E         | Le prix des places pour la catégorie E (€).                                                        | 90                                |
| Catégorie_First_PFR | Le prix des places pour la catégorie "First" des publics en fauteuil roulant et accompagnants (€). | 55                                |
| Catégorie_A_PFR     | Le prix des places pour la catégorie A des publics en fauteuil roulant et accompagnants (€).       | 25                                |
| Catégorie_B_PFR     | Le prix des places pour la catégorie B des publics en fauteuil roulant et accompagnants (€).       | 15                                |

: Dictionnaire de donnée de \`Paris_2024\`
