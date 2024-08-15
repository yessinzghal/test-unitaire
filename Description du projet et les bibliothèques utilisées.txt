L'application Python développée automatise le processus de tests unitaires pour des fichiers de code source en C. 
Elle exécute les tests sur ces fichiers .c, génère des rapports de couverture et de synthèse, 
et produit un fichier Excel avec les résultats des tests.

Fonctionnalités de l'application :

1.Automatisation des Tests Unitaires : Exécution des tests sur les fichiers de
  code source en utilisant des outils de test appropriés.

2.Création de Rapports de Couverture : Analyse des résultats pour générer un rapport
  de couverture qui indique le pourcentage de code testé.

3.Création d'un Rapport de Synthèse : Compilation des résultats des tests
  et des couvertures pour créer un rapport global.

4.Génération de Fichier Excel : Création d'un fichier Excel contenant 
  les données des fichiers testés avec les pourcentages de tests.


Importations utilisées :

  •datetime : Module fournissant des classes pour manipuler les dates et les heures.

  •os : Fonctionnalités liées au système d'exploitation en Python.

  •subprocess : Utilisé pour exécuter des commandes système, telles que celles de LDRA.

  •openpyxl : Permet de manipuler des fichiers Excel.

  •bs4 : Conçu pour travailler avec des documents HTML.

  •shutil : Utilisé pour des opérations de haut niveau sur les fichiers et les collections de fichiers.

  •pandas : Utile pour extraire et organiser les données des fichiers HTML avant de les écrire dans un fichier Excel.

  •Tkinter : Utilisé pour créer des interfaces graphiques permettant à l'utilisateur de sélectionner un répertoire.
