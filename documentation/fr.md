<!-- ELUCENIA technical documentation · escala-de-katz · fr · no clinical/professional/rights approval -->

# Indice de Katz (activités de base de la vie quotidienne)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/escala-de-katz)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Bain (autonome : se lave seul ou n’a besoin d’aide que pour une partie du corps)

`banho`

- `0` — Dépendant
- `1` — Indépendant

### Habillage (autonome : prend ses vêtements et s’habille sans aide, sauf pour lacer les chaussures)

`vestir`

- `0` — Dépendant
- `1` — Indépendant

### Toilette (autonome : va aux toilettes, assure son hygiène et ajuste ses vêtements sans aide)

`higiene`

- `0` — Dépendant
- `1` — Indépendant

### Transfert (autonome : s’allonge et se relève du lit et d’un siège sans aide)

`transf`

- `0` — Dépendant
- `1` — Indépendant

### Continence (autonome : contrôle complet des urines et des selles)

`contin`

- `0` — Dépendant
- `1` — Indépendant

### Alimentation (autonome : porte les aliments de l’assiette à la bouche sans aide)

`alim`

- `0` — Dépendant
- `1` — Indépendant

## Édition de la méthode

Katz ADL binaire : 6 activités, total 0–6 ; formulaire HIGN 2019, légèrement adapté de Katz et al. 1970 ; sans les catégories A–G de 1963

## Formule documentée

1 point par activité autonome (sans surveillance, consigne ni aide d’autrui) : bain, habillage, toilettes, transfert, continence, alimentation. Total 0–6.

## Limites et population

Enregistrez la version de l’indice et les définitions d’indépendance pour chaque activité. L’adaptation brésilienne de 2008 a été étudiée pour l’équivalence culturelle et la fiabilité ; cela ne certifie pas cette implémentation binaire ni ses nouvelles traductions. Le total local 0–6 n’est pas la classification historique A–G. La somme binaire de 6 activités a été vérifiée selon le formulaire HIGN de 2019, qui se déclare légèrement adapté de Katz et al. 1970. Cette source n’est pas la classification A–G de 1963 et ne certifie ni l’adaptation brésilienne de 2008 ni les traductions rédigées actuellement. Les exceptions à l’indépendance et la finalité d’évaluation des activités de base chez les personnes âgées doivent suivre le formulaire correspondant.

## Références

- [Katz S et al. Studies of illness in the aged. The index of ADL: a standardized measure of biological and psychosocial function. JAMA, 1963.](https://doi.org/10.1001/jama.1963.03060120024016)

- [Lino VTS et al. Adaptação transcultural da Escala de Independência em Atividades da Vida Diária (Escala de Katz). Cad Saude Publica, 2008.](https://doi.org/10.1590/S0102-311X2008000100010)

- [McCabe D. Katz Index of Independence in Activities of Daily Living. HIGN/NYU, Issue 2, revised 2019; slightly adapted from Katz et al. 1970.](https://hign.org/sites/default/files/2020-06/Try_This_General_Assessment_2.pdf)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
