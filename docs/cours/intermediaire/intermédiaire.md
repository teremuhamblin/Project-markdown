📄 intermediaire.md
> Cours Markdown Intermédiaire

`markdown

Markdown Intermédiaire

Ce module approfondit les fonctionnalités essentielles du Markdown pour produire des documents plus structurés, plus lisibles et plus professionnels.  
Il s’adresse à ceux qui maîtrisent déjà les bases (titres, listes, liens, images, code simple).

---

1. Tableaux

Les tableaux permettent d’organiser des données de manière lisible.

1.1 Syntaxe de base

`
| Colonne 1 | Colonne 2 |
|----------|-----------|
| Valeur A | Valeur B  |
| Valeur C | Valeur D  |
`

1.2 Alignement

`
| Gauche | Centre | Droite |
|:-------|:------:|-------:|
| a      | b      | c      |
`

- :--- → aligné à gauche  
- :---: → centré  
- ---: → aligné à droite  

---

2. Citations avancées

2.1 Citations imbriquées

`
> Niveau 1
>> Niveau 2
>>> Niveau 3
`

2.2 Citations + code + listes

`
> Exemple :
> - Élément
> - Élément
> `
> code ici
> `
`

---

3. Blocs de code avancés

3.1 Spécifier un langage

markdown
`python
def hello():
    print("Hello")
`


3.2 Ajouter une légende (selon les plateformes)

Certaines plateformes supportent :

`
`bash title="Installation"
npm install
`
`

3.3 Code long + commentaires

markdown
`js
// Fonction principale
function run() {
  console.log("OK");
}
`


---

4. Mise en page avancée

4.1 Sauts de ligne forcés

`
Texte ligne 1  
Texte ligne 2
`

Deux espaces en fin de ligne → saut de ligne.

---

4.2 Paragraphes espacés

`
Paragraphe 1.

Paragraphe 2.
`

---

4.3 Combiner titres + listes + code

Exemple :

`

Étape 1 : Installation

- Télécharger le fichier
- Exécuter :

`bash
install.sh
`
`

---

5. Liens avancés

5.1 Liens internes vers sections

`
Aller à la section Tableaux
`

5.2 Liens vers fichiers internes

`
[Il semble que le résultat n’était pas sûr à afficher. Changeons un peu et essayons autre chose !]
`

---

6. Images avancées

6.1 Redimensionnement (selon plateformes)

GitHub ne supporte pas nativement le redimensionnement, mais on peut utiliser du HTML :

`
<img src="../assets/images/logo.png" width="200">
`

6.2 Images centrées

`
<p align="center">
  <img src="../assets/images/logo.png" width="200">
</p>
`

---

7. Notes, avertissements et encadrés

Selon les plateformes (GitHub, MkDocs, Obsidian…), on peut utiliser :

Exemple GitHub (Markdown + HTML)

`
> Note : ceci est une note importante.
`

Exemple style documentation

`
> [!IMPORTANT]
> Ceci est un message important.
`

`
> [!WARNING]
> Attention à ce point.
`

---

8. Organisation avancée d’un document

Un document intermédiaire doit :

- avoir une structure claire  
- utiliser des titres cohérents  
- intégrer des tableaux pour les données  
- utiliser des citations pour les extraits  
- intégrer du code formaté  
- utiliser des liens internes pour naviguer  

---

9. Bonnes pratiques intermédiaires

- Préférer les tableaux pour les données structurées  
- Utiliser des citations pour mettre en avant des informations  
- Ajouter des blocs de code avec langage spécifié  
- Utiliser des liens internes pour améliorer la navigation  
- Aérer le texte (espaces, sauts de ligne)  
- Éviter les blocs trop longs  

---

10. Exercices intermédiaires

1. Créer un tableau avec 3 colonnes et 4 lignes.  
2. Ajouter une citation contenant une liste et un bloc de code.  
3. Créer un document avec :
   - un sommaire interne  
   - des liens vers des sections  
   - une image centrée  
4. Réécrire un document brut en version structurée intermédiaire.  

---

Conclusion

Le niveau intermédiaire permet de produire des documents plus professionnels, plus lisibles et mieux organisés.  
Il prépare au module avancé, qui introduit les extensions, les workflows d’écriture et les usages professionnels du Markdown.

`

---
