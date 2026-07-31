# Prisme Digital

**Studio web — sites vitrines, espaces membres et outils de gestion.**
Los Santos, San Andreas.

🔗 **Site en ligne :** https://poloveni.github.io/Prisme-Digital-FlashbackFA/

---

## À propos du projet

Ce dépôt contient l'intégralité du code source du site vitrine de Prisme Digital, entreprise de développement web opérant sur le serveur FlashbackFA. Il est public et le restera : la transparence sur le code fait partie des engagements pris auprès de FlashbackFA et de chaque client.

### Contenu du site

Le site reprend l'architecture d'information d'une agence web : présentation, direction, offre, méthode, adresse, communauté.

| Section | Rôle |
|---|---|
| Héro | Promesse principale et deux appels à l'action |
| Indicateurs | Plateformes en production, heures d'expérience, disponibilité |
| À propos | Trois engagements, l'histoire du studio, notre position |
| Direction | Les deux patrons, leurs rôles et leurs créneaux |
| Services | Six domaines d'intervention — tarif sur demande |
| Méthode | Les quatre étapes d'un projet, du brief au suivi |
| Nous trouver | Adresse, horaires, conditions d'accueil |
| Communauté | Le serveur Discord, point d'entrée de tous les échanges |
| Pied de page | Navigation, mentions légales, cadre du projet |

---

## Choix techniques

Le site est un **document HTML unique et autonome**, sans framework ni étape de compilation.

| Élément | Choix | Raison |
|---|---|---|
| Structure | HTML5 sémantique | Accessibilité et référencement |
| Style | CSS3 natif, variables CSS | Aucune dépendance, chargement instantané |
| Interactivité | JavaScript vanilla (ES5) | Compatible avec tous les navigateurs, aucun build |
| Typographie | Space Grotesk + Inter | Repli automatique sur les polices système |
| Animations | Canvas 2D + IntersectionObserver | Désactivées si `prefers-reduced-motion` |
| Images | Encodées en base64 dans le document | Un seul fichier à déployer, aucun lien externe à casser |

**Pourquoi un fichier unique ?** Le site est destiné à être hébergé sur une infrastructure tierce, sans accès administrateur du développeur. Un livrable sans dépendance, sans runtime et sans build garantit un déploiement par simple copie de fichier, et une maintenance possible par n'importe qui.

### Points d'attention

- Aucune donnée personnelle n'est collectée ni stockée
- Aucun cookie, aucun traceur, aucun appel réseau hors chargement des polices
- Navigation clavier complète et attributs ARIA sur les composants interactifs
- Interface responsive testée de 320 px à 2560 px de large

---

## Installation

Aucune. Le site fonctionne en ouvrant `index.html` dans un navigateur.

Pour un hébergement, il suffit de déposer `index.html` à la racine du serveur web.

```
Prisme-Digital-FlashbackFA/
├── index.html    ← le site complet
└── README.md
```

---

## Identité

| Élément | Valeur |
|---|---|
| Nom | Prisme Digital |
| Signature | Studio web |
| Fondateur | Javier Silva |
| Couleur principale | `#F23BA0` (magenta) |
| Couleur secondaire | `#25D5EC` (cyan) |
| Fond | `#07080C` |

Le prisme décompose la lumière en spectre : c'est l'origine du dégradé magenta → cyan utilisé sur l'ensemble de l'identité.

---

## Licence et propriété

Ce projet est développé dans le cadre du serveur de jeu de rôle FlashbackFA. Les sites réalisés pour le serveur et son administration deviennent la propriété de FlashbackFA, code source inclus, conformément aux conditions convenues avec l'équipe de gestion.

---

*Projet fictif réalisé dans un cadre de jeu de rôle. Les entreprises, montants et lieux mentionnés n'ont aucune existence réelle.*
