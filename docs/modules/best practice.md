📄 best-practices.md — Module Best Practices Markdown

`markdown

Best Practices Markdown

Ce module regroupe les meilleures pratiques pour écrire, structurer et maintenir des documents Markdown professionnels.  
Il s’adresse à toute personne souhaitant produire une documentation claire, durable et cohérente.

---

1. Structure et hiérarchie

1.1 Un seul titre principal
Chaque fichier doit commencer par un seul #.

1.2 Hiérarchie logique
`

Titre 1

Titre 2

Titre 3
`

1.3 Sections courtes
- 5 à 15 lignes par section
- découper si nécessaire

---

2. Lisibilité

2.1 Paragraphes courts
Un paragraphe = une idée.

2.2 Sauts de ligne
Utiliser deux espaces en fin de ligne pour un saut forcé.

2.3 Aération
- listes
- tableaux
- citations
- blocs de code

---

3. Liens internes et navigation

3.1 Sommaire
Toujours ajouter un sommaire pour les documents > 30 lignes.

3.2 Liens internes
`
Aller à la section
`

3.3 Modularisation
Un fichier = un sujet.

---

4. Images et ressources

4.1 Chemins relatifs
Toujours utiliser :
`
../assets/images/nom.png
`

4.2 Texte alternatif obligatoire
Pour l’accessibilité.

4.3 Centrage (si nécessaire)
`
<p align="center">
  <img src="..." width="200">
</p>
`

---

5. Code et exemples

5.1 Spécifier le langage
markdown
`bash
echo "Hello"
`


5.2 Commentaires dans le code
Toujours expliquer les étapes importantes.

---

6. Tableaux

6.1 Alignement
`
| Nom | Âge | Ville |
|:---|:---:|------:|
`

6.2 Taille raisonnable
Éviter les tableaux de 20 colonnes.

---

7. Style et cohérence

7.1 Style uniforme
- même type de titres
- même style de listes
- même conventions

7.2 Ton professionnel
Clair, direct, sans jargon inutile.

---

8. Maintenance

8.1 Mise à jour du changelog
Toujours mettre à jour CHANGELOG.md.

8.2 Vérification des liens
Tester régulièrement les liens internes.

8.3 Nettoyage
Supprimer les fichiers obsolètes.

---

Conclusion

Les bonnes pratiques garantissent une documentation lisible, durable et professionnelle.  
Elles sont essentielles dans les environnements collaboratifs et techniques.
`

---
