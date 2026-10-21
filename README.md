# YouCode Events

Site web fictif présentant les événements de YouCode : ateliers, conférences, hackathons et rencontres avec des professionnels.

Projet réalisé en binôme dans le cadre de la formation YouCode (du 12 au 16 octobre 2026), pour progresser sur Git et GitHub en travaillant à plusieurs sur le même code.

---

## Équipe

| Membre | Rôle | Parties réalisées (page d'accueil) |
|---|---|---|
| **Achraf El Houari** | Développeur front-end | En-tête (logo, navigation, menu mobile), section héros, section « Prochains événements » |
| **Hind Gaougaou** | Développeuse front-end | Chiffres clés, « Explorer par catégorie », pied de page |

---

## Technologies utilisées

- HTML5 sémantique
- CSS3 : Flexbox et CSS Grid
- JavaScript : uniquement pour ouvrir et fermer le menu mobile
- Google Fonts (police *Inter*)
- Git et GitHub

---

## Structure du projet

```
youcode-events/
├── index.html
├── css/
│   └── style.css
├── assets/
│   ├── images/
│   └── icons/
└── README.md
```

---

## Page réalisée : Accueil (`index.html`)

La page d'accueil est composée des sections suivantes :

- **En-tête** : logo, navigation et menu hamburger qui s'ouvre et se ferme en JavaScript
- **Section héros** : badge de saison, titre, texte de présentation, deux boutons d'appel à l'action et visuel de calendrier
- **Prochains événements** : cartes avec catégorie, titre, date, lieu et lien vers le détail
- **Chiffres clés** : +40 événements par an, 25 intervenants, 1200 participants, 12 partenaires
- **Explorer par catégorie** : Ateliers, Conférences, Hackathons, Rencontres
- **Pied de page** : navigation, contact et mentions

---

## Lancer le site

Aucune installation n'est nécessaire.

1. Cloner le dépôt :
   ```bash
   git clone <url-du-depot>
   cd youcode-events
   ```
2. Ouvrir `index.html` dans un navigateur, ou utiliser l'extension **Live Server** de VS Code.

---

## Workflow Git

- Une branche par fonctionnalité : `feature/<sujet>`
- Fusion vers `develop` par Pull Request, relue par l'autre membre
- Commits au format `type: description` (`feat`, `fix`, `style`, `docs`)

Exemples :
```
feat: ajouter la section héros de la page d'accueil
style: ajuster les espacements des cartes d'événements
docs: ajouter le README
```

---

## Auteurs

- Achraf El Houari
- Hind Gaougaou

*Site fictif réalisé en formation à YouCode.*
