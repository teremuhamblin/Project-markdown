📄 avance.md
> Cours Markdown Avancé

`markdown

Markdown Avancé

Ce module explore les fonctionnalités avancées du Markdown, les extensions les plus utilisées, les bonnes pratiques professionnelles et les usages dans des environnements techniques (GitHub, documentation, wikis, automatisation).

Il s’adresse à ceux qui maîtrisent déjà les niveaux bases et intermédiaire.

---

1. Extensions du Markdown

Le Markdown standard est volontairement minimaliste.  
De nombreuses plateformes ajoutent leurs propres extensions.

1.1 GitHub Flavored Markdown (GFM)

GitHub ajoute :

- tableaux améliorés
- cases à cocher
- blocs de code enrichis
- mentions (@user)
- références automatiques (#123)
- emojis (:smile:)
- blocs spéciaux ([!NOTE], [!WARNING])

Exemple :

`
> [!NOTE]
> Ceci est une note GitHub.
`

---

1.2 Markdown + HTML

Le Markdown accepte du HTML pour les besoins avancés :

`
<p align="center">
  <img src="../assets/images/logo.png" width="200">
</p>
`

Usage typique :
- centrer une image
- redimensionner un élément
- créer des colonnes
- styliser un texte

---

1.3 Extensions type documentation (MkDocs, Obsidian, etc.)

Certaines plateformes ajoutent :

- onglets
- admonitions
- blocs interactifs
- notes latérales
- références croisées automatiques

Exemple (MkDocs) :

`
!!! warning
    Ceci est un avertissement.
`

---

2. Structuration avancée d’un document

Un document avancé doit être :

- hiérarchisé
- navigable
- modulaire
- cohérent
- lisible même brut

2.1 Sommaire automatique

GitHub génère un sommaire via les titres.  
Mais on peut aussi créer un sommaire manuel :

`

Sommaire
- Introduction
- Méthodes
- Conclusion
`

---

2.2 Sections longues et modularisation

Pour les documents volumineux :

- découper en plusieurs fichiers
- créer un index
- utiliser des liens internes

Exemple :

`
Voir la suite dans [Il semble que le résultat n’était pas sûr à afficher. Changeons un peu et essayons autre chose !].
`

---

3. Documentation technique en Markdown

Markdown est utilisé pour :

- documenter des API
- écrire des guides d’installation
- rédiger des workflows
- créer des tutoriels
- structurer des projets GitHub

3.1 Documentation API (exemple)

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
`

---

3.2 Documentation d’installation

`

Installation

`bash
git clone https://github.com/monprojet
cd monprojet
npm install
`
`

---

4. Blocs avancés pour GitHub

4.1 Badges

`
https://img.shields.io/badge/build-passing-brightgreen
`

4.2 Références automatiques

- Issue : #42
- Pull request : #108
- Commit : @abc123

---

5. Automatisation et Markdown

5.1 Génération automatique

Certains outils génèrent du Markdown :

- scripts Python
- générateurs de documentation
- CI/CD (GitHub Actions)

Exemple d’un script qui génère un README :

`
python generate_readme.py
`

---

5.2 Templates dynamiques

GitHub permet d’utiliser des templates pour :

- issues
- pull requests
- discussions

Exemple :

`
.github/ISSUETEMPLATE/bugreport.md
`

---

6. Bonnes pratiques avancées

6.1 Cohérence stricte

- titres hiérarchiques
- style uniforme
- même structure dans tous les fichiers
- même conventions de nommage

6.2 Documents courts et modulaires

- un fichier = un sujet
- éviter les fichiers de 500 lignes
- préférer les liens internes

6.3 Accessibilité

- textes alternatifs pour les images
- éviter les couleurs seules pour transmettre une info
- privilégier la lisibilité

6.4 Compatibilité

Tester le rendu sur :
- GitHub
- éditeur local
- générateur de documentation

---

7. Exercices avancés

1. Créer un document complet avec :
   - sommaire
   - sections modulaires
   - tableaux avancés
   - blocs de code annotés
   - admonitions

2. Documenter une API simple en Markdown.

3. Créer un template d’issue GitHub.

4. Réécrire un document long en plusieurs fichiers reliés.

---

Conclusion

Le niveau avancé transforme Markdown en un véritable outil professionnel.  
Il permet de produire des documents robustes, modulaires, maintenables et adaptés aux environnements techniques modernes.

Ce module conclut la formation Markdown et ouvre la voie à des usages experts : documentation, templates, automatisation, workflows GitHub.

`

---
