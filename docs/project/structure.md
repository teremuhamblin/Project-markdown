📄 structure.md

`markdown

Structure du projet

Ce document décrit l’architecture complète du projet.  
Il sert de référence pour comprendre l’organisation des dossiers, la logique de séparation des contenus et les conventions utilisées.

---

1. Objectifs de la structure
- Organiser le projet de manière claire et évolutive.
- Faciliter la navigation pour les contributeurs.
- Séparer proprement les responsabilités (documentation, assets, templates…).
- Garantir une cohérence entre tous les fichiers Markdown.

---

2. Structure générale du projet

```text
project-markdown/
│
├── README.md
├── PLAN.md
├── STYLEGUIDE.md
├── EXEMPLE.md
├── TEMPLATE.md
├── CHANGELOG.md
├── CONTRIBUTING.md
├── CODEOFCONDUCT.md
├── SECURITY.md
├── LICENSE
│
├── docs/
│   ├── README.md
│   ├── writing/
│   │   ├── README.md
│   │   ├── rules.md
│   │   └── exemples.md
│   │
│   ├── project/
│   │   ├── README.md
│   │   ├── structure.md
│   │   └── workflow.md
│   │
│   └── templates/
│       ├── README.md
│       └── document-template.md
│
└── assets/
    ├── README.md
    └── images/
```

---

3. Description des dossiers

📁 Racine du projet
Contient les fichiers essentiels :
- README.md — présentation générale du projet  
- PLAN.md — plan global ou sommaire  
- STYLEGUIDE.md — règles de style  
- TEMPLATE.md — modèle de base  
- CHANGELOG.md — historique des versions  
- CONTRIBUTING.md — règles pour contribuer  
- SECURITY.md — politique de sécurité  
- LICENSE — licence du projet  

Ces fichiers servent de base pour comprendre, utiliser et maintenir le projet.

---

📁 docs/
Dossier principal de documentation avancée.  
Il regroupe tout ce qui concerne l’écriture, la structure du projet et les modèles.

---

📁 docs/writing/
Contient les règles d’écriture et les exemples :
- rules.md — règles officielles  
- exemples.md — exemples concrets  
- README.md — présentation du dossier  

---

📁 docs/project/
Dossier dédié à la documentation interne du projet :
- structure.md — architecture du projet  
- workflow.md — workflow, processus, bonnes pratiques  
- README.md — introduction  

---

📁 docs/templates/
Contient les modèles réutilisables :
- document-template.md — modèle standard  
- README.md — description  

---

📁 assets/
Ressources visuelles :
- images, captures, illustrations  
- fichiers statiques  

---

4. Principes de structuration
- Séparation claire entre contenu, documentation, templates et assets.
- Tous les fichiers doivent être nommés en minuscules, avec des tirets.
- Chaque dossier doit contenir un README.md expliquant son rôle.
- Les fichiers doivent être courts, cohérents et faciles à maintenir.

---

5. Évolution de la structure
- Ajouter un dossier uniquement si nécessaire.
- Documenter toute modification dans CHANGELOG.md.
- Garder la structure simple, stable et compréhensible.
`

---


