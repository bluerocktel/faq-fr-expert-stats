---
category: Statistiques de Files
category_slug: statistiques-files
slug: consolidation-appels-multi-files
sort_order: 2
---

# Qu'est ce que la consolidation des appels multi-files ?


## Sans consolidation des appels multi-files :

Par défaut, la consolidation des appels multi-files est **désactivée** : chaque appel est comptabilisé dans chacune des files d'attente qu'il atteint.

Dit autrement : chaque appel est comptabilisé **une fois par file**.

### Cas pratique (une file principale et une file de débordement) :

Un appel répondu dans la file de débordement sera compté deux fois : 

- non répondu dans la file principale,
- répondu dans la file de débordement.

Ce mode met en avant la **performance individuelle** de chaque file. C'est la **statistique la plus précise** pour analyser le **fonctionnement détaillé** de chaque file d'attente.


## Avec consolidation des appels multi-files :

Lorsque la consolidation des appels multi-files est **activée** : chaque appel est comptabilisé **une seule fois**, même s'il passe par plusieurs files d'attente.

Dit autrement : chaque appel est comptabilisé **une fois pour l'ensemble des files**.

### Cas pratique (une file principale et une file de débordement) : 

Un appel répondu dans la file de débordement sera compté **iune seule fois**, comme **répondu**.

Ce mode fournit une **vue consolidée** du volume réel d'appels entrants et de la **performance globale** des files sélectionnées. C'est la **statistique la plus fidèle** pour savoir combien d'appels sont réellement pris en charge.


## En définitive : 

Les deux modes ont leur intérêt propre, en fonction de ce que vous cherchez à analyser.
