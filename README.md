# PASSERELLES / 2027

**Un démonstrateur indépendant de cartographie des compétences et de mobilité interne.**

## L'idée

Les compétences d'une organisation ne se résument pas à des fiches de poste. Ce prototype permet de **visualiser les écarts collectifs**, **explorer les passerelles métiers** et **préparer une note stratégique**.

Ce projet est une preuve de concept de GPEEC et d'aide à la décision pour les **trois versants de la fonction publique** : État, territoriale et hospitalière.

## Découvrir en trois minutes

1. Ouvrir `index.html` dans un navigateur moderne. Aucune installation nécessaire.
2. Choisir le versant et l'horizon 2027, 2028 ou 2030.
3. Consulter les écarts dans **Vue d'ensemble** et la **Matrice des compétences**.
4. Tester le cas **Gestionnaire administratif → Assistante / assistant de direction** via le bouton de découverte.
5. Modifier les niveaux de la matrice ; les indicateurs se recalculent.
6. Exporter un CSV, enregistrer le JSON ou générer une **note stratégique** imprimable en PDF.

## Contenu du kit

- `index.html` — application autonome HTML/CSS/JavaScript.
- `EXEMPLE_MATRICE_2027.csv` — matrice fictive de 72 lignes, lisible dans Excel et LibreOffice.
- `EXEMPLE_DONNEES_2027.json` — jeu de données compatible avec l'import du prototype.
- `README.md` — guide, précautions et mise en ligne.

## Mise en ligne sur GitHub Pages

Créer un nouveau dépôt public, déposer `index.html`, les deux fichiers de données et le kit ZIP (à créer à part si souhaité), puis activer **Settings → Pages → Deploy from a branch → main / root**. L'URL sera sous la forme `https://utilisateur.github.io/nom-du-depot/`. Sur la version en ligne, le bouton « Télécharger le kit complet » fonctionne si le fichier `PASSERELLES_2027_Kit.zip` est lui aussi déposé à la racine.

## Ce que le modèle mesure (et ce qu'il ne mesure pas)

Les niveaux actuels et cibles vont de 0 à 5. L'écart collectif est la différence positive cible − actuel, pondérée par des effectifs entièrement fictifs. La couverture est un ratio indicatif de niveaux agrégés. Les simulations de formation/mobilité/transmission appliquent des coefficients arbitraires : **elles n'ont aucune valeur de prévision**. Les indices de passerelles portent sur des archétypes métiers fictifs, **jamais sur l'aptitude ou la performance de personnes**.

## Précautions

- Toutes les données livrées sont inventées.
- Ne jamais intégrer de données individuelles, nominatives ou confidentielles à un dépôt public.
- Ce projet ne contient ni outil de recrutement automatisé ni prise de décision RH.
- Une utilisation institutionnelle exigerait la participation des équipes métiers, de la DRH, du DPO, de la DSI et des représentants compétents, ainsi qu'une analyse juridique et organisationnelle.
- Projet **indépendant**, sans affiliation à un ministère, une collectivité ou un établissement public.

**PASSERELLES 2027 · version 2.0 · Démonstration méthodologique**
