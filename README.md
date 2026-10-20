# Solar Dimension Pro

Classeur de pré-dimensionnement photovoltaïque conçu pour **LibreOffice Calc**. Le projet est publié pour recueillir des retours et des contributions afin de l'améliorer. Le classeur fourni conserve actuellement ses paramètres de référence Sénégal.

> **État : prototype en développement.** Ce classeur ne constitue pas une étude d'exécution ni une validation de conformité. Faites vérifier les résultats par un professionnel qualifié avant tout achat, installation ou mise en service.

## Télécharger et démarrer

1. Téléchargez [`Solar_Dimension_Pro.xlsx`](Solar_Dimension_Pro.xlsx) depuis ce dépôt.
2. Ouvrez-le avec LibreOffice Calc (une version récente est recommandée).
3. Commencez par l'onglet **Guide - première utilisation**, placé en dernier.
4. Suivez le parcours vers **Projet**, puis renseignez les charges et les hypothèses du site.
5. Consultez les résultats, alertes et hypothèses avant d'utiliser la nomenclature ou le rapport.

Le fichier est au format `.xlsx` et n'exige pas de macro. Le rendu et le recalcul doivent être vérifiés dans LibreOffice Calc avant usage opérationnel.

## Contenu actuel

Le classeur contient 12 onglets : Accueil, Projet, Charges, Climat, Catalogue PV, Catalogue stockage, Catalogue conversion, Câbles & protections, Calcul, BOM, Rapport et Guide - première utilisation.

Le catalogue livré compte actuellement :

| Famille | Références présentes |
| --- | ---: |
| Panneaux photovoltaïques | 47 |
| Batteries | 39 |
| Onduleurs | 37 |
| Régulateurs MPPT | 10 |
| Appareils de consommation courante | 100 |

Ces catalogues **n'atteignent pas encore** l'objectif de 100 à 150 références par famille demandé pour les panneaux, batteries et onduleurs. Les appareils courants forment un référentiel indicatif, pas une base exhaustive. Les références et caractéristiques doivent être confirmées sur les fiches fabricants; une donnée absente ne doit pas être devinée.

## Capacités et limites

Le prototype organise les entrées de projet et de consommation, les catalogues, les calculs, les contrôles, la nomenclature, le rapport et un guide utilisateur. Il vise les projets résidentiels, tertiaires et industriels.

Les calculs et la compatibilité des équipements doivent faire l'objet d'une revue technique indépendante. La couverture des puissances industrielles et multi-MW, les scénarios multi-champs et multi-banques, ainsi que les calculs de câblage/protection ne doivent pas être considérés comme validés sans cas d'essai documentés. Le fichier n'a pas été ouvert visuellement dans LibreOffice dans l'environnement de préparation; merci de signaler tout problème de présentation ou de recalcul avec la version de Calc utilisée.

## Contribuer

Les retours sont bienvenus : ouvrez une issue pour signaler un problème, proposer une amélioration ou demander une référence. Consultez [CONTRIBUTING.md](CONTRIBUTING.md) avant d'ajouter des spécifications de matériel.

Pour qu'une nouvelle référence soit utile et vérifiable, indiquez le fabricant, le modèle exact, le type d'appareil, les caractéristiques avec unités, une URL de fiche technique officielle, la date de consultation et les limites de compatibilité connues. N'inférez pas les valeurs manquantes.

## Licence

Le contenu original de ce dépôt est publié sous licence MIT (voir [LICENSE](LICENSE)). Les marques, noms de modèles et documents fabricants restent la propriété de leurs titulaires respectifs. Les spécifications sont référencées à des fins d'identification et doivent être vérifiées auprès des fabricants.

## Historique

Voir [CHANGELOG.md](CHANGELOG.md).
