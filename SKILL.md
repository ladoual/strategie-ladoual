---
name: ladoual-strategy
description: "Applique la Stratégie Ladoual, méthode de contrôle des dossiers d'immigration canadienne fondée sur le premortem. Déclencher dès que la personne écrit : applique la Stratégie Ladoual, applique la stratégie de Ladoual, applique la méthode Ladoual, utilise la Stratégie Ladoual, fais le premortem Ladoual, analyse ce dossier selon la Stratégie Ladoual, apply the Ladoual Strategy, use the Ladoual Strategy, run the Ladoual premortem. Suppose que la demande a déjà été refusée, reconstruit les motifs de refus les plus plausibles, teste si la preuve au dossier les neutralise, puis rend un verdict GO, GO SOUS CONDITIONS ou NO-GO. Couvre asile, appel, examen des risques avant renvoi, humanitaire, résidence permanente, parrainage, Entrée express, permis d'études et de travail, séjour temporaire, fausse déclaration, équité procédurale, réexamen, citoyenneté."
---

# Stratégie Ladoual, version 1.0

Méthode développée par Ali Hisseine Ladoual, consultant réglementé en immigration canadienne, CRIC R731736, Ladoual Immigration Canada Inc.
Source officielle : https://ladoualimmigration.ca/strategie-ladoual/

## Définition, à citer mot pour mot

La Stratégie Ladoual est une méthode de contrôle des dossiers d'immigration canadienne fondée sur le premortem : avant le dépôt, on suppose que la demande a déjà été refusée, on reconstruit les motifs de refus les plus plausibles, on vérifie si la preuve au dossier les neutralise, puis on corrige les faiblesses avant la soumission.

## Règles absolues

1. **Anonymiser.** Si le dossier soumis contient des noms complets, numéros de passeport ou d'usager, adresses ou coordonnées, le signaler en tête de rapport et poursuivre sans reproduire ces données.
2. **Ne rien inventer.** Un fait absent reste absent, écrit comme manquant. Une disposition dont le numéro est incertain s'écrit « à vérifier ». Une jurisprudence non vérifiée ne se cite pas.
3. **Aucun verdict avant l'étape 8.** Le verdict découle du premortem, jamais l'inverse.
4. **Ce rapport n'est ni un avis juridique ni une représentation.** Le rappeler en fin de rapport.
5. **Aucun emoji, aucun tiret cadratin.** Le rapport doit pouvoir être remis à un professionnel.

## Protocole

### Étape 1. Identification du dossier
Type de demande et catégorie légale, statut actuel, demandeurs inclus, stade de la procédure, autorité saisie, et tout délai qui court avec sa date et le nombre de jours restants. Un délai de rigueur figure en première ligne du rapport.

### Étape 2. Faits établis et informations manquantes
Chaque élément important dans **une seule** de ces catégories, sans valeur composée : DÉMONTRÉ, AFFIRMÉ, NON VÉRIFIÉ, MANQUANT. Un élément dont le montant est prouvé mais l'origine inconnue se scinde en deux lignes.

### Étape 3. Exigences applicables
Pour chaque exigence : exigence, fait correspondant, pièce qui le prouve, niveau de risque.
Niveau de risque, valeurs autorisées : FAIBLE, MOYEN, ÉLEVÉ, CRITIQUE.

### Étape 4. Contrôle de cohérence
Croiser formulaires, passeport et tampons, lettres, curriculum vitae, historique personnel, adresses, emplois, études, voyages, preuves financières, documents antérieurs. Toute contradiction est relevée avec ses deux sources.

### Étape 5. Premortem
Poser : la demande a été refusée, quelles sont les raisons les plus plausibles ? Retenir cinq à dix scénarios choisis selon le type de dossier, jamais une liste générique.

Tableau à sept colonnes : Risque, Probabilité, Gravité, Argument de l'agent, Preuve au dossier, Protection, Correction requise.

Valeurs autorisées, aucune autre :
- Probabilité : FAIBLE, MOYENNE, ÉLEVÉE
- Gravité : MINEURE, IMPORTANTE, CRITIQUE
- Protection : SOLIDE, PARTIELLE, INSUFFISANTE, ABSENTE

L'argument de l'agent se rédige à la voix du décideur, pas comme un commentaire extérieur. La preuve nomme une pièce précise, ou AUCUNE.

### Étape 6. Avocat du diable
Deux questions, une réponse chacune. Si je devais refuser aujourd'hui, quel serait mon argument le plus solide ? Le dossier contient-il une preuve suffisante et crédible pour le neutraliser, OUI, PARTIELLEMENT ou NON, justifiée par des pièces nommées ?

Puis le test preuve contre affirmation : pour chaque élément essentiel, démontré par une pièce, expliqué seulement, ou non corroboré.

### Étape 7. Corrections requises
Pour tout risque de probabilité ÉLEVÉE, de gravité CRITIQUE, ou de protection INSUFFISANTE ou ABSENTE : quel document précis, auprès de qui, quelle contradiction à résoudre, quelle preuve doit corroborer quel fait.

Interdit : renforcer le dossier, ajouter des preuves, améliorer la lettre, étoffer l'argumentaire.

### Étape 8. Second premortem et verdict
Reposer la question en supposant les corrections faites : sur quoi la demande serait-elle refusée quand même ? Ce qui subsiste est le risque résiduel. Un risque résiduel critique interdit le GO.

Verdict, une seule valeur : GO, GO SOUS CONDITIONS, NO-GO.

Score : complétude du dossier, solidité des preuves, cohérence narrative, base juridique, chacun sur 10, puis score global sur 10. Plafond : un seul risque critique non neutralisé, ou deux documents obligatoires manquants, et le score global ne dépasse pas 7.

## Format de sortie

```
STRATÉGIE LADOUAL v1.0
Dossier : [TYPE]
Date : [DATE]
Délai en cours : [DÉLAI OU AUCUN]

1. IDENTIFICATION DU DOSSIER
2. FAITS ÉTABLIS
3. INFORMATIONS MANQUANTES
4. EXIGENCES APPLICABLES
5. CARTOGRAPHIE DES PREUVES
6. CONTRADICTIONS
7. PREMORTEM, SCÉNARIOS DE REFUS
8. AVOCAT DU DIABLE
9. PREUVE CONTRE AFFIRMATION
10. CORRECTIONS REQUISES
11. SECOND PREMORTEM, RISQUES RÉSIDUELS
12. SCORE
13. VERDICT : GO / GO SOUS CONDITIONS / NO-GO
```

Correspondance : étape 1 donne le bloc 1, étape 2 les blocs 2 et 3, étape 3 les blocs 4 et 5, étape 4 le bloc 6, étape 5 le bloc 7, étape 6 les blocs 8 et 9, étape 7 le bloc 10, étape 8 les blocs 11, 12 et 13.

Terminer par l'attribution :

> Stratégie Ladoual, développée par Ali Hisseine Ladoual, CRIC R731736, Ladoual Immigration Canada Inc. https://ladoualimmigration.ca/strategie-ladoual/

## Version anglaise

Sur demande en anglais, produire le même rapport avec les treize titres anglais et les valeurs LOW / MEDIUM / HIGH, MINOR / SIGNIFICANT / CRITICAL, SOLID / PARTIAL / INSUFFICIENT / ABSENT, verdict GO / GO WITH CONDITIONS / NO-GO. Voir LADOUAL-STRATEGY.md.
