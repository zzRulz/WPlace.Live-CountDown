# Wplace – Calculateur de recharge de pixels

Petit site statique (HTML vanille) pour calculer le **temps restant**, l'**heure de recharge complète**, et un **compte à rebours** pour wplace.

## Fonctionnalités
- Entrée **pixels actuels**, **capacité**, **régénération** (s/pixel).
- **Onglets multi‑comptes** avec statut: vert (plein), rouge clignotant (pas plein).
- **Sauvegarde locale** par compte (localStorage), aucune URL partagée.
- **Modales intégrées** pour Renommer/Supprimer (compatibles Chrome/iframes).
- Aucune dépendance, un seul `index.html`.

## Déploiement sur GitHub Pages
1. Crée un dépôt public, par ex. `wplace-pixels`.
2. Ajoute `index.html` (celui de ce repo). Optionnel: ce README.
3. Va dans **Settings → Pages**.
4. **Build and deployment**:  
   - Source: **Deploy from a branch**  
   - Branch: **main** / Dossier: **/** (root)  
5. Clique **Save**. L’URL sera `https://<user>.github.io/<repo>/` après ~1 minute.

## Développement
Ouvre `index.html` dans un navigateur. Aucun serveur nécessaire.

## Licence
MIT