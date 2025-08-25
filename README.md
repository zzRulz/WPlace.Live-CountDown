# Wplace – Recharge de pixels (Complet & Stable)

Version complète et stable :
- Multi‑comptes (onglets) + statut (vert = plein)
- **Start** (démarre) et **Stop/Reset** (pause et fige la progression)
- Reprise après F5 via `fullAt`
- Renommer/Supprimer via **modales intégrées**
- Aucune dépendance (un seul `index.html`)

## Déploiement (GitHub Pages)
1. Crée un dépôt public (ex. `wplace-pixels`).
2. Ajoute `index.html` (ce fichier) + optionnel `README.md`.
3. **Settings → Pages** : *Deploy from a branch* → `main` → `/ (root)` → **Save**.
4. Accède à `https://<user>.github.io/<repo>/`.

## Utilisation
1. Choisis un compte (onglet) ou crée-en un.
2. Renseigne **pixels actuels**, **capacité**, **régénération (s/pixel)**.
3. Clique **Start** pour lancer le calcul ; **Stop/Reset** met en pause.
4. Les valeurs sont conservées en localStorage.

## Remarques
- Le compteur `x/y` des onglets progresse virtuellement jusqu’au plein.
- Aucune donnée ne quitte ton navigateur.