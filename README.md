# ScanFry — site public

Site statique de l'application iPhone **ScanFry** : présentation, assistance et
politique de confidentialité, en français (racine) et en anglais (`en/`).

- HTML et CSS uniquement, sans JavaScript ni outil de construction
- publié sur https://scanfry.com/ ; chemins relatifs, donc aussi lisible
  en local en ouvrant `index.html`
- clair et sombre selon le réglage de l'appareil

## Adresses à renseigner dans App Store Connect

| Champ | Français | Anglais |
| --- | --- | --- |
| Support URL | `https://scanfry.com/support.html` | `https://scanfry.com/en/support.html` |
| Privacy Policy URL | `https://scanfry.com/privacy.html` | `https://scanfry.com/en/privacy.html` |
| Marketing URL | `https://scanfry.com/` | `https://scanfry.com/en/` |

## À mettre à jour

- **Sortie sur l'App Store** : remplacer « Bientôt sur l'App Store » par le lien
  `https://apps.apple.com/app/id6802007920` dans `index.html` et `en/index.html`.
- **Confidentialité** : relire `privacy.html` à chaque version de l'app ; le texte
  source est dans `AppStore/<version>/metadata/*/privacy.md` du projet iOS.
- **Domaine** : `scanfry.com` (Hover), fichier `CNAME` à conserver. Configuration DNS :
  voir `AppStore/1.0.0/WEBSITE_HANDOFF.md` du projet iOS.
