# Zeitgeist - Musiques Incongrues

Page de visualisation du Zeitgeist (tendances) de la plateforme Musiques Incongrues.

## Déploiement

Ce projet est configuré pour être déployé automatiquement sur GitHub Pages via GitHub Actions.

### Configuration requise

1. Aller dans **Settings** > **Pages** du repository
2. Sous **Build and deployment**, sélectionner **GitHub Actions** comme source
3. Configurer le domaine personnalisé : `journananal.musiques-incongrues.net`
4. Pousser sur la branche `main` pour déclencher le déploiement

**URL du site :** https://journananal.musiques-incongrues.net

## Fichiers

- `index.html` - Page principale du Zeitgeist
- `config.html` - Formulaire de configuration
- `zeitgeist-config-workflow.json` - Workflow n8n pour la configuration

## Paramètres URL

La page `index.html` accepte les paramètres suivants :

| Paramètre | Description | Défaut |
|-----------|-------------|--------|
| `num` | Nombre de périodes | 1 |
| `unit` | Unité de temps (days/weeks/months) | weeks |
| `limit` | Limite d'éléments | 50 |
| `collection_labels` | Collection pour les labels | gargamelle |
| `collection_radios` | Collection pour les radios | discutons |
| `collection_artists` | Collection pour les artistes | sonsoftheananas |
| `collection_contributors` | Collection pour les contributeurs | millemilliards |
| `collection_newcomers` | Collection pour les nouveaux | amour |

## Licence

MIT
