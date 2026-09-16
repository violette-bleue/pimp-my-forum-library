# pimp-my-forum-library
Bibliothèques de thèmes

## feuille de route / structure prévue

```
Themes/
  <nom du thème>/
    infos.json        (crédits, description)
    templates/         (un dossier par catégorie, comme un dossier local)
    js/                 (codes JS obligatoires au thème)
    css/                (à venir)

Scripts/
  <nom du script>/
    infos.json
    ...                  
```

`Themes/<thème>/infos.json` : pour stocker les infos sur le thème et saon createurice

```json
{
  "creator": "...",
  "name": "...",
  "description": "...",
  "site": "...",
  "readme": "..."
}
```
