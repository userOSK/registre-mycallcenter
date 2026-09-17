\# Note au DPO : Registre MyCallCenter



1\. \*\*État du registre\*\* : 3 traitements sont actuellement recensés (OP-01, OP-02, OP-03).

2\. \*\*Durée de conservation (OP-01)\*\* : Fixée à 6 mois, conformément à la fiche de la CNIL sur l'écoute et l'enregistrement des appels sur le lieu de travail.

3\. \*\*Preuve de conformité\*\* : Le dépôt Git permet de répondre au principe d'accountability. La commande `git log` montre l'historique des fusions, et `git blame registre.csv` permet de prouver qui a déclaré ou modifié chaque ligne, et à quelle date.

4\. \*\*Limite identifiée\*\* : Le nom de l'auteur dans Git n'est qu'une simple variable texte modifiable par n'importe qui. Ce n'est pas infalsifiable. Pour garantir l'identité de l'auteur, il faudrait mettre en place des signatures cryptographiques.

