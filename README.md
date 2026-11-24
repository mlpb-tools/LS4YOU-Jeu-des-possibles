# LS4YOU · Le jeu des possibles

Jeu en ligne : https://mlpb-tools.github.io/LS4YOU-Jeu-des-possibles/

## Comment ça marche

- `export-epoc.zip` : l'export web d'ePoc Editor. Il contient le contenu du jeu (`assets/demo/epocs/LS4YOU-JDP/content.json`) et ses images.
- `app/index.html` : l'habillage LS4YOU. Il lit directement le contenu ePoc et l'affiche avec l'univers visuel du projet.
- À chaque mise à jour de `export-epoc.zip` ou de `app/`, GitHub publie le site automatiquement.
- Le lecteur ePoc d'origine reste accessible en secours : `…/LS4YOU-Jeu-des-possibles/epoc.html`.

## Modifier le contenu

1. Modifier les situations dans ePoc Editor (identifiant de l'ePoc : `LS4YOU-JDP`).
2. Exporter la version web et remplacer `export-epoc.zip` dans ce dépôt.
3. L'habillage s'applique tout seul.

Pour que l'habillage reconnaisse une situation, garder la même structure dans l'éditeur : pour chaque situation, les pages `situation`, `Que faire ?`, `Quelle Life Skill ?`, `À toi de jouer` et `On essaie`.

Projet Life Skills 4 Youth (LS4YOU) — n° 2023-2-FR02-KA220-YOU-000175417. Financé par l'Union européenne.
