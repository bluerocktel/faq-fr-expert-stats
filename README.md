# FAQ Expert-Stats - Version Française

Ce dépôt contient le contenu Markdown pour générer automatiquement le site web de FAQ (Questions Fréquemment Posées) de la solution **Expert-Stats** développée par **CX-Engine Limited**.

🌐 **Site web public** : [https://expert-stats-faq-fr.cx-engine.com/](https://expert-stats-faq-fr.cx-engine.com/)

## À propos

Expert-Stats est une solution de statistiques avancées pour 3CX. Ce dépôt contient la documentation FAQ en français, organisée par catégories pour faciliter la navigation et la recherche d'informations.

## Structure du dépôt

```
faq-fr-expert-stats/
├── content/              # Articles FAQ en Markdown
│   ├── comptabilisation-*.md
│   ├── configuration-avancee-*.md
│   └── files-*.md
├── site.yaml            # Configuration du site (MkDocs)
└── README.md            # Ce fichier
```

## Catégories de contenu

Les articles FAQ sont organisés en plusieurs catégories :

- **Comptabilisation des Appels** : Questions sur la comptabilisation, les appels déclinés, transférés, et les sollicitations
- **Configuration Avancée** : Paramètres avancés, groupes, rapports détaillés
- **Files** : Gestion des files d'attente, durée d'attente, consolidation multi-files

## Format des articles

Chaque article Markdown suit une structure standard avec des métadonnées en frontmatter :

```yaml
---
category: Nom de la catégorie
category_slug: slug-de-la-categorie
slug: slug-de-l-article
sort_order: 1
---

# Titre de l'article

Contenu de l'article...
```

## Contribution

Ce dépôt est public et ouvert aux contributions. Pour proposer des améliorations ou ajouter de nouveaux articles :

1. Créez une branche pour vos modifications
2. Ajoutez ou modifiez les articles Markdown dans le dossier `content/`
3. Respectez la structure de nommage : `categorie-XXX-nom-article.md`
4. Soumettez une pull request

## Liens utiles

- **BlueRockTEL** : [https://bluerocktel.com](https://bluerocktel.com)
- **CX-Engine** : [https://cx-engine.com](https://cx-engine.com)

## Licence

© 2025 CX-Engine Limited. Tous droits réservés.
