# Calculabilité et Complexité

Cette organisation contient les ressources et projets liés au cours **Calculabilité et Complexité** de Nantes Université.

## Description du module

Ce cours est destiné à des étudiants de L3 en Informatique ou Mathématiques, ainsi qu'à toute personne s'intéressant aux fondements théoriques de la logique, de l'informatique et des mathématiques.

Le responsable du module est Matthieu Perrin.

Les volumes horaires dédiés à ce cours à Nantes Université (séances de 1h20) sont les suivants :
- Cours magistraux : 20h
- Travaux dirigés : 20h

### Contenu
- Monoïde des mots
- Langages rationnels
  - Expressions régulières
  - Automate fini
  - Langage reconnu par un automate fini
  - Déterminisation et minimisation d'un automate fini
  - Lemme d’Arden
  - Lemme de l’Étoile
- Langages algébriques
  - Grammaire algébrique
  - Arbre de dérivation
  - Automates à pile
- Hiérarchie de Chomsky
  - Classification des grammaires
  - Algorithmes de reconnaissance pour les grammaires de type 1 et 2
- Analyse lexicale et syntaxique
  - TP de flex et bison
- Machines de Turing
  - Langage décidé et accepté; Langages récursivement énumérables
  - Encodage des machines de Turing; Machine de Turing universelle
  - Machine de Turing déterministe
- Calculabilité
  - Existence de fonctions non-calculables par dénombrabilité
  - Problème de l'arrêt
  - Problèmes indécidables
  - Réductions entre problèmes
  - Théorème de Rice
  - Équivalence entre modèles de calcul; Thèse de Church-Turing
- Complexité (10h)
  - Classes de complexité P et NP
  - Problème SAT; Théorème de Cook
  - Problèmes NP-durs et NP-complets

### Résultats d'apprentissage
À la fin de ce cours, un étudiant doit être capable de :
- Utiliser les logiciels flex et bison
- Écrire une expression rationnelle
- Résoudre un système d'équations linéaires à droite
- Déterminer si un mot donné est reconnu par un automate fini ou un automate à pile
- Déterminer la classe d'une grammaire formelle dans la hiérarchie de Chomsky
- Savoir si un mot est engendré par une grammaire rationnelle, algébrique ou contextuelle
- Minimaliser et déterminiser un automate fini
- Transformer une grammaire rationnelle en une expression rationnelle ou en un automate fini et inversement
- Comprendre les fondements de la théorie de la calculabilité
  -  Équivalence entre les modèles de calcul (machines de Turing et fonctions calculables)
  -  Comment ils peuvent être utilisés pour décrire la notion de calculabilité et les problèmes indécidables.
- Modéliser des algorithmes simples sous la forme d'une machine de Turing.
- Décrire les classes de complexité P et NP et reconnaître des problèmes NP-complets.
- Appliquer les techniques de réduction de problèmes pour montrer que certains problèmes sont indécidables et pour établir des propriétés des problèmes indécidables.
- Appliquer les techniques de réduction pour montrer que certains problèmes sont NP-durs.

### Bibliographie
- K. D. Cooper & L. Torczon. **Engineering a compiler** – 2nd Ed., Morgan Kaufmann 2013
- P. Wolper. **Introduction à la calculabilité** – 3nd Ed., Dunod 2006
- O. Carton. **Langages Formels – Calculabilité et complexité**, Vuibert 2008

## Dépôts principaux
- [**CM**](https://github.com/CalculabiliteEtComplexite/CM) — Slides de cours.
  - [Slides](https://CalculabiliteEtComplexite.github.io/CM/slides.pdf): version PDF avec animations
  - [Handout](https://CalculabiliteEtComplexite.github.io/CM/handout.pdf): version PDF sans animation
- [**TD**](https://github.com/CalculabiliteEtComplexite/TD) — Énoncés et corrections de TD.
  - Dépôt privé accessible aux enseignants sur demande

## Cours lié
Ce cours a été conçus comme la deuxième partie d'un cours sur les fondements de la calculabilité en informatique théorique. 
Il est précédé par un cours de [Langages et Automates](https://github.com/LangagesEtAutomates) en L2, dédié aux langages rationnels et algébriques. 

## Licence
Sauf mention contraire, les contenus sont sous licence
- [Creative Commons Attribution - ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/) pour les sources LaTeX.
