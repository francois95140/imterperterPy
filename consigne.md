# Sujet de projet

Interpréteur de mini Langage

## Informations pratiques :

  Les dates de la pré soutenance, et de la soutenance sont visibles sur myges.
  REMARQUE : Les discussions entre groupes de projet sont encouragées mais vous devez
  impérativement écrire vous-même le code. Le partage de code entrainera automatiquement un 0
  pour les deux parties.

### Sujet :

  L’objectif du projet est de concevoir un interpréteur pour un mini langage. Il est obligatoire de baser
  l’interprétation sur un arbre de syntaxe abstrait construit au cours de l’analyse syntaxique du
  « programme – input » donné en entrée.
  Libertés

- syntaxe de l’input : libre
- arbre de syntaxe abstrait : nommage des sommets libre et structure libre (ordre des fils d’un
  sommet, ordre pour la structure de bloc

## Spécifications de la version minimale (8/20) :

* [X] Votre interpréteur devra gérer les noms de variables à plusieurs caractères.

### Gérer les instructions suivantes :

* [X] affectation
* [X] affichage d’expressions numériques (pouvant contenir des variables numériques)
* [X] instructions conditionnelles : implémenter le si-alors-sinon/si-alors
* [X] structures itératives : implémenter le while et le for
* [X] Affichage de l’arbre de syntaxe (sur la console ou avec graphViz)

### Améliorations :

* [ ] Fonctions void
* [ ] Fonction return avec coupe circuit
* [X] Gérer les elif
* [ ] Scope
* [ ] Fonctions avec return et scope des variables et gestion de la pile d’exécution
* [ ] Les tableaux (suivant degré d’aboutissement : push, pop, len, printTab, init)
* [ ] la POO (suivant degré d’aboutissement)
* [ ] Gérer le passage des paramètres par référence et les pointeurs (suivant degré
  d’aboutissement)
* [ ] Coder une fonction eval ou exec (à la python)
* [ ] Optimiser l’interprétation de fonctions récursives terminales (sur la taille de la pile)
* [ ] Gérer les imports

### Petites ameliorations :

* [ ] Gestion des erreurs (variable non initialisée, …)
* [ ] Gérer la déclaration explicite des variables
* [ ] Gestion du type chaine de caractères (et extension d’autant de l’instruction d’affichage)
* [ ] Gestion des variables globales
* [ ] affectations multiples à la python : a, b = 2, 3
* [ ] comparaison multiples à la python : 1<2<3 (déconseillé)
* [ ] print multiples : print(x+2, « toto ») ;
* [X] incrémentation et affectation élargie : x++, x+=1
* [X] possibilités de mettre des commentaires dans le code (et génération automatique d’une docString)
* [ ] printString
* [X] input utilisateur
  Rendu :

- votre code (1 ou plusieurs fichiers)
- un fichier readme qui détaille
  o les fonctionnalités implémentées
  o les différents inputs associés aux fonctionnalités ci dessus
