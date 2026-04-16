📄 exercices-complet.md
> Exercices + Corrigés (Niveaux 1, 2, 3)

`markdown

Exercices Markdown — Complet (Niveaux 1, 2, 3)

Ce document regroupe l’ensemble des exercices et corrigés pour pratiquer le Markdown du niveau débutant au niveau avancé.

---

📚 Sommaire

- Niveau 1 — Exercices
- Niveau 1 — Corrigés
- Niveau 2 — Exercices
- Niveau 2 — Corrigés
- Niveau 3 — Exercices
- Niveau 3 — Corrigés

---

Niveau 1 — Exercices

Exercice 1 : Titres
Créer un document contenant :
- un titre principal
- deux sous-titres
- un paragraphe sous chaque sous-titre

---

Exercice 2 : Listes
Créer :
- une liste à puces de 4 éléments
- une liste numérotée de 3 étapes
- une liste avec cases à cocher

---

Exercice 3 : Liens
Ajouter :
- un lien vers un site externe
- un lien interne vers un fichier de votre projet

---

Exercice 4 : Images
Insérer une image avec :
- un texte alternatif
- un chemin relatif

---

Exercice 5 : Code
Ajouter :
- un code inline
- un bloc de code simple

---

Niveau 1 — Corrigés

Exercice 1 : Titres

`

Mon Document

Partie 1
Voici un paragraphe.

Partie 2
Voici un autre paragraphe.
`

---

Exercice 2 : Listes

`
- Élément 1
- Élément 2
- Élément 3
- Élément 4

1. Étape 1
2. Étape 2
3. Étape 3

- [ ] À faire
- [x] Terminé
`

---

Exercice 3 : Liens

`
Lien externe
[Il semble que le résultat n’était pas sûr à afficher. Changeons un peu et essayons autre chose !]
`

---

Exercice 4 : Images

`
[Il semble que le résultat n’était pas sûr à afficher. Changeons un peu et essayons autre chose !]
`

---

Exercice 5 : Code

`
Utilisez la commande npm install.

`bash
echo "Hello"
`
`

---

Niveau 2 — Exercices

Exercice 1 : Tableaux
Créer un tableau avec :
- 3 colonnes
- 4 lignes
- alignement centré sur la colonne du milieu

---

Exercice 2 : Citations avancées
Créer une citation contenant :
- une liste
- un bloc de code

---

Exercice 3 : Blocs de code
Créer un bloc de code :
- avec un langage spécifié
- contenant un commentaire

---

Exercice 4 : Mise en page
Créer un document contenant :
- un titre
- un paragraphe avec un saut de ligne forcé
- une liste
- un bloc de code

---

Exercice 5 : Liens internes
Créer un sommaire interne avec des liens vers 3 sections.

---

Niveau 2 — Corrigés

Exercice 1 : Tableaux

`
| Nom  | Âge | Ville |
|:----:|:---:|------:|
| Ana  | 22  | Paris |
| Leo  | 31  | Lyon  |
| Mia  | 27  | Nice  |
| Tom  | 29  | Brest |
`

---

Exercice 2 : Citations avancées

`
> Liste :
> - Élément
> - Élément
> `
> console.log("Hello");
> `
`

---

Exercice 3 : Blocs de code

markdown
`python

Fonction simple
def hello():
    print("Hello")
`


---

Exercice 4 : Mise en page

`

Exemple

Voici une phrase.  
Voici une autre phrase.

- Item 1
- Item 2

`bash
echo "Test"
`
`

---

Exercice 5 : Liens internes

`

Sommaire
- Section 1
- Section 2
- Section 3

Section 1
...

Section 2
...

Section 3
...
`

---

Niveau 3 — Exercices

Exercice 1 : Document complet
Créer un document contenant :
- un sommaire
- 4 sections
- un tableau avancé
- un bloc de code annoté
- une admonition (NOTE ou WARNING)
- une image centrée

---

Exercice 2 : Documentation technique
Documenter une API simple avec :
- un endpoint
- une réponse JSON
- un exemple d’appel

---

Exercice 3 : Modularisation
Créer :
- un fichier principal
- deux sous-fichiers
- des liens internes entre eux

---

Exercice 4 : Template GitHub
Créer un template d’issue contenant :
- un titre
- des sections
- des cases à cocher

---

Exercice 5 : Workflow d’écriture
Créer un guide expliquant :
- comment créer un fichier
- comment le structurer
- comment le valider
- comment mettre à jour le changelog

---

Niveau 3 — Corrigés

Exercice 1 : Document complet

`

Mon Document Avancé

Sommaire
- Introduction
- Données
- Code
- Conclusion

Introduction
Texte ici.

Données
| Nom | Score | Rang |
|:---|:-----:|-----:|
| Ana |  92   |   1  |
| Leo |  88   |   2  |

Code
> [!NOTE]
> Exemple de code annoté.

`js
// Fonction principale
function run() {
  console.log("OK");
}
`

<p align="center">
  <img src="../assets/images/logo.png" width="200">
</p>

Conclusion
Fin du document.
`

---

Exercice 2 : Documentation API

`

GET /users/{id}

Retourne les informations d’un utilisateur.

Réponse :

`json
{
  "id": 1,
  "name": "Alice"
}
`

Exemple d’appel :

`bash
curl https://api.exemple.com/users/1
`
`

---

Exercice 3 : Modularisation

`
Voir le fichier partie-2.md pour la suite.
`

---

Exercice 4 : Template GitHub

`

Rapport de bug

Description
Décrivez le problème.

Étapes pour reproduire
1. Étape
2. Étape

Checklist
- [ ] Bug reproductible
- [ ] Informations complètes
`

---

Exercice 5 : Workflow d’écriture

`

Workflow d’écriture

1. Dupliquer TEMPLATE.md
2. Renommer le fichier
3. Structurer avec titres et sections
4. Ajouter exemples, code, tableaux
5. Vérifier cohérence et style
6. Mettre à jour CHANGELOG.md
`

---

Fin du document
`

---
