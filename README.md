# ScanFry — site public

Site statique de l'application iPhone **ScanFry** : présentation, assistance et
politique de confidentialité, en français (racine) et en anglais (`en/`).

- HTML et CSS uniquement, sans JavaScript ni outil de construction
- chemins relatifs : fonctionne sous `https://nsabatier.github.io/ScanFrySite/`
  comme sur un domaine personnalisé
- clair et sombre selon le réglage de l'appareil

## Adresses à renseigner dans App Store Connect

| Champ | Français | Anglais |
| --- | --- | --- |
| Support URL | `…/support.html` | `…/en/support.html` |
| Privacy Policy URL | `…/privacy.html` | `…/en/privacy.html` |
| Marketing URL | `…/` | `…/en/` |

## À mettre à jour

- **Sortie sur l'App Store** : remplacer « Bientôt sur l'App Store » par le lien
  `https://apps.apple.com/app/id6802007920` dans `index.html` et `en/index.html`.
- **Confidentialité** : relire `privacy.html` à chaque version de l'app ; le texte
  source est dans `AppStore/<version>/metadata/*/privacy.md` du projet iOS.
- **Domaine Hover** : suivre `AppStore/1.0.0/WEBSITE_HANDOFF.md` du projet iOS,
  ajouter un fichier `CNAME`, puis changer les adresses dans App Store Connect.
