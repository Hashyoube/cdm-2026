[Uploading README.md…]()
# Coupe du Monde 2026 · Horaires Bangkok

Suivi interactif de la CDM 2026 à l'heure de Bangkok : calendrier des 104 matchs, scores, classements des 12 groupes, buteurs et passeurs. Mise à jour automatique des scores une fois le site en ligne.

---

## Mettre en ligne sur GitHub Pages (≈ 2 min)

> Important : il faut le **mettre en ligne** pour que la mise à jour auto fonctionne.
> Ouvert en double-clic depuis l'ordinateur (`file://`), le navigateur **bloque** les appels réseau → le fichier reste figé sur l'instantané. En ligne (`https://…`), ça marche.

### Méthode simple (sans Git, glisser-déposer)
1. Va sur **github.com** → bouton **New** (nouveau dépôt).
2. Nom du dépôt : `cdm2026` (ou ce que tu veux). Coche **Public**. **Create repository**.
3. Sur la page du dépôt : **Add file → Upload files**.
4. Glisse le fichier **`index.html`** dedans. **Commit changes**.
5. Onglet **Settings → Pages**.
6. Sous **Build and deployment → Source**, choisis **Deploy from a branch**.
7. Branch : **main** / dossier : **/(root)**. **Save**.
8. Attends ~1 min. Ton site est en ligne à :
   **`https://hashyoube.github.io/cdm2026/`**

C'est la même logique que ton baby-tracker.

---

## Mise à jour en direct

- **Scores + classements** : se rafraîchissent tout seuls (toutes les 60 s) via une source gratuite **sans clé**, dès que le site est en ligne. La pastille en haut passe de ⚪ à 🟢 EN DIRECT.
- **Passeurs décisifs en direct** : nécessite une clé **API-Football** (gratuite).
  1. `dashboard.api-football.com` → connexion.
  2. La clé est en **haut à droite** (survole pour la révéler) ou via **Account → My Access**.
  3. Dans le site : bouton **⚙️**, colle la clé. Elle reste **dans ton navigateur** (localStorage), elle n'est envoyée qu'à API-Football.

### Si la pastille reste 🔴 / ⚪ après mise en ligne
La source gratuite peut ne pas couvrir tous les matchs. Dans ce cas, ajoute ta clé API-Football (étape ci-dessus) : c'est la voie la plus fiable, et elle débloque aussi les passeurs.

---

## Notes
- Heures en fuseau **Bangkok** (UTC+7 = heure française + 5 h).
- L'instantané intégré est à jour au **17 juin 2026** ; il sert de secours si le live ne répond pas.
- Fichier unique, aucune dépendance à installer.
