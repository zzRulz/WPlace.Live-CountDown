# Wplace – Calculateur de recharge de pixels

Site statique (un seul `index.html`) pour estimer le **temps restant**, l’**heure de recharge complète** et afficher un **compte à rebours** pour wplace.

## Fonctionnalités
- **Bouton Start** : le timer démarre seulement quand tu veux.
- **Multi‑comptes par onglets** : indicateur vert (plein) / rouge clignotant (pas plein), et le compteur `x/y` progresse virtuellement jusqu’à `y`.
- **Persistance** : paramètres et heure cible (`fullAt`) sont stockés par compte (localStorage). Le timer reprend après F5.
- Aucune dépendance.

## Déploiement GitHub Pages
1. Crée un dépôt public (ex. `wplace-pixels`).
2. Ajoute ce `index.html` (et ce `README.md` si tu veux).
3. Va dans **Settings → Pages**.
4. **Build and deployment** : *Deploy from a branch* → Branch `main`, dossier `/ (root)`.
5. Clique **Save**. Ton site sera accessible sous `https://<user>.github.io/<repo>/`.

## Astuces
- Tu peux créer/renommer/supprimer des comptes (onglets) selon tes profils wplace.
- Le statut d’un onglet se met à jour en direct pendant que le timer tourne.