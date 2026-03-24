# Tombola RP — Arma 3

Application web de gestion de tombolas pour serveur Arma 3 RP.
**Aucune configuration requise.** Fonctionne immédiatement après déploiement sur GitHub Pages.

## Déploiement (5 minutes)

1. Créez un repo GitHub **public** (ex : `tombola-rp`)
2. Uploadez `index.html` et `admin.html` à la racine du repo
3. Allez dans **Settings → Pages → Branch: main / root** → cliquez **Save**
4. Votre site est en ligne sur `https://votre-pseudo.github.io/tombola-rp/`

## Utilisation

| Page | Rôle |
|---|---|
| `index.html` | Page publique affichée sur la TV / second écran |
| `admin.html` | Panneau admin — gérez la tombola depuis un autre onglet |

**Mot de passe admin par défaut : `admin1234`**
→ Changez-le dès la première connexion dans *Paramètres entreprise*.

## Fonctionnement de la synchronisation

Les deux pages se synchronisent automatiquement via `localStorage` du navigateur.
**Condition :** les deux onglets doivent être ouverts dans **le même navigateur** sur le même PC.

> Exemple : admin sur l'onglet 1, page publique sur l'onglet 2 projeté sur une TV via un câble HDMI.
