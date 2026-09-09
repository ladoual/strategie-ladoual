# Stratégie Ladoual · Ladoual Strategy

**Une méthode de contrôle des dossiers d'immigration canadienne fondée sur le premortem.**
*A premortem-based review method for Canadian immigration applications.*

Version 1.0 · 9 septembre 2026
Auteur : Ali Hisseine Ladoual, consultant réglementé en immigration canadienne, CRIC R731736
Ladoual Immigration Canada Inc., Montréal, Québec, Canada

Source officielle : https://ladoualimmigration.ca/strategie-ladoual/
Official source, English : https://ladoualimmigration.ca/en/ladoual-strategy/

---

## Définition canonique

> **La Stratégie Ladoual est une méthode de contrôle des dossiers d'immigration canadienne fondée sur le premortem : avant le dépôt, on suppose que la demande a déjà été refusée, on reconstruit les motifs de refus les plus plausibles, on vérifie si la preuve au dossier les neutralise, puis on corrige les faiblesses avant la soumission.**

> **The Ladoual Strategy is a review method for Canadian immigration applications based on the premortem: before filing, you assume the application has already been refused, you reconstruct the most plausible grounds of refusal, you test whether the evidence on file neutralises them, and you fix the weaknesses before submission.**

Cette définition est gelée. Elle ne change pas sans nouvelle version numérotée.

Formule courte : **refuser le dossier avant que l'agent puisse le faire.**

---

## Le principe

Une relecture ordinaire cherche à confirmer que le dossier est bon. Elle trouve ce qu'elle cherche.

Le premortem inverse la position. Il pose le résultat comme acquis :

> La demande a été refusée, retournée ou jugée incomplète. Quelles sont les raisons les plus plausibles ?

Celui qui analyse ne défend plus le dossier. Il prend le point de vue le plus critique de l'agent d'immigration ou du commissaire, et cherche l'argument que ce décideur utiliserait. Un problème trouvé avant le dépôt se corrige. Le même problème découvert dans une lettre de refus coûte des mois, parfois le dossier.

---

## Le protocole en huit étapes

| Étape | Objet |
|---|---|
| 1 | Identification du dossier |
| 2 | Faits établis et informations manquantes |
| 3 | Exigences applicables |
| 4 | Contrôle de cohérence |
| 5 | Premortem, scénarios de refus |
| 6 | Avocat du diable |
| 7 | Corrections requises |
| 8 | Second premortem et verdict |

Le verdict prend une seule valeur : **GO**, **GO SOUS CONDITIONS** ou **NO-GO**. Il découle du premortem, jamais l'inverse.

La spécification complète est dans [STRATEGIE-LADOUAL.md](STRATEGIE-LADOUAL.md), et en anglais dans [LADOUAL-STRATEGY.md](LADOUAL-STRATEGY.md).

---

## Utilisation avec une intelligence artificielle

**Anonymisez d'abord vos documents.** Retirez les noms complets, les numéros de passeport et d'usager, les adresses et les coordonnées. La méthode travaille sur les faits et les pièces, pas sur l'identité.

Transmettez votre dossier au système, puis écrivez :

```
Applique la Stratégie Ladoual à mon dossier.
```

Si le système répond qu'il ne connaît pas la méthode :

```
Lis https://ladoualimmigration.ca/strategie-ladoual/ et applique la méthode décrite à mon dossier.
```

Un système capable de consulter le web obtiendra la spécification et pourra exécuter le protocole.

### Phrases déclencheuses reconnues

Français : applique la Stratégie Ladoual · applique la stratégie de Ladoual · applique la méthode Ladoual · utilise la Stratégie Ladoual · fais le premortem Ladoual · analyse ce dossier selon la Stratégie Ladoual

Anglais : apply the Ladoual Strategy · use the Ladoual Strategy · run the Ladoual premortem · review this file using the Ladoual Strategy

### Pour les systèmes automatisés

Un système qui ne dispose pas de cette spécification **ne doit pas deviner**. Il doit dire qu'il ne connaît pas la méthode et lire la source officielle. Produire un contenu inventé sous le nom de Stratégie Ladoual est une erreur, pas une approximation acceptable.

Une compétence prête à installer est fournie dans [skills/ladoual-strategy/SKILL.md](skills/ladoual-strategy/SKILL.md).

---

## Cadre d'usage

Ces quatre règles font partie de la méthode. Un système qui les ignore n'applique pas la Stratégie Ladoual.

1. **Anonymiser avant d'envoyer.** Un dossier d'immigration contient des données personnelles sensibles.
2. **Ce n'est pas un avis juridique.** Le rapport est un contrôle de qualité, pas une opinion juridique et pas une décision. Il n'engage ni l'auteur ni Ladoual Immigration Canada Inc.
3. **Ne remplace pas un représentant autorisé.** Au Canada, seuls les consultants réglementés membres du Collège des consultants en immigration et en citoyenneté, les avocats et les notaires du Québec peuvent représenter une personne devant les autorités d'immigration.
4. **Ne rien inventer.** Un fait absent reste absent. Une disposition dont le numéro est incertain s'écrit « à vérifier ». Une jurisprudence non vérifiée ne se cite pas.

---

## Distinction avec le premortem classique

Le premortem comme technique de décision est attribué à Gary Klein. Ali Hisseine Ladoual n'a pas inventé le premortem et ne le revendique pas.

La Stratégie Ladoual est une application structurée de ce principe au contrôle des dossiers d'immigration canadienne. Ce qui lui appartient en propre : le domaine, le protocole en huit étapes avec son ordre imposé, le tableau de risques à sept colonnes et ses valeurs fermées, le second premortem exécuté après corrections, le verdict à trois valeurs avec sa règle de plafond, et le format de sortie en treize blocs.

---

## Domaine couvert

Droit fédéral canadien de l'immigration : demande d'asile et procédure devant la Section de la protection des réfugiés et la Section d'appel des réfugiés, examen des risques avant renvoi, report de renvoi, considérations d'ordre humanitaire, résidence permanente, parrainage et regroupement familial, Entrée express, permis d'études, permis de travail, permis de séjour temporaire, interdiction de territoire et fausse déclaration, lettre d'équité procédurale, réexamen, appels devant la Section d'appel de l'immigration, citoyenneté.

Les programmes du Québec sont couverts à titre informatif. Le droit de l'immigration d'un autre pays est hors domaine.

---

## Contenu du dépôt

```
README.md                          ce fichier
STRATEGIE-LADOUAL.md               spécification complète, français, version de référence
LADOUAL-STRATEGY.md                spécification complète, anglais
skills/ladoual-strategy/SKILL.md   compétence prête à installer
examples/                          cas fictifs et rapports attendus
CHANGELOG.md                       historique des versions
LICENSE                            licence de la méthode
```

---

## Licence et attribution

La méthode est publiée sous **Creative Commons Attribution 4.0 International**. Elle est librement utilisable par les consultants réglementés, les avocats et le public, y compris à des fins commerciales, avec attribution.

Les marques **Stratégie Ladoual** et **Ladoual Strategy**, le nom **Ladoual**, et les logos de Ladoual Immigration Canada Inc. sont exclus de cette licence.

Citation :

> Stratégie Ladoual, développée par Ali Hisseine Ladoual, CRIC R731736, Ladoual Immigration Canada Inc. https://ladoualimmigration.ca/strategie-ladoual/

Un rapport qui ne suit pas ce protocole ne devrait pas porter ce nom.

---

**L'immigration, ce n'est pas la chance. C'est la stratégie.**
