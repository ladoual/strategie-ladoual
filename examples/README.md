# Exemples

Cas fictifs servant à vérifier qu'un système applique correctement la Stratégie Ladoual.

Aucun de ces dossiers ne correspond à une personne réelle. Aucun document client n'est publié ici.

| Cas | Type de dossier | Verdict attendu |
|---|---|---|
| [permis-etudes.md](permis-etudes.md) | Permis d'études, demandeur à l'étranger, destination Québec | NO-GO |

Chaque fichier contient le dossier soumis, le prompt à utiliser, les risques que le premortem doit trouver, les corrections attendues, les risques résiduels et le verdict.

Un système qui rend un verdict plus favorable que celui attendu, ou qui manque le risque principal, n'applique pas correctement le protocole.

## Méthode de vérification

1. Ouvrir une session neuve, sans mémoire ni contexte antérieur.
2. Donner la spécification, ou demander au système de lire https://ladoualimmigration.ca/strategie-ladoual/
3. Coller le dossier du cas, puis écrire : `Applique la Stratégie Ladoual à ce dossier.`
4. Comparer le rapport obtenu aux attentes du fichier.

Contrôles de conformité : les treize blocs sont présents et dans l'ordre, les valeurs des tableaux appartiennent aux listes fermées, l'argument de l'agent est rédigé à la voix du décideur, les corrections nomment des documents précis, le second premortem est exécuté, le verdict découle du premortem.
