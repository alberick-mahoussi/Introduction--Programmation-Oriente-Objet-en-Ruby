# Introduction--Programmation-Oriente-Objet-en-Ruby
Assure-toi d'avoir Ruby installé sur ton ordinateur pour pouvoir exécuter ces exercices. Si tu as des questions ou des difficultés avec un exercice particulier, n'hésite pas à demander de l'aide.

### Exercice 1 : Définir une classe
Imagine une application de gestion de bibliothèque. Crée une classe `Livre` avec les attributs `titre`, `auteur` et `annee_publication`.

### Exercice 2 : Méthodes de la classe
Ajoute à la classe `Livre` une méthode `afficher_details` qui affiche les détails du livre.

### Exercice 3 : Héritage
 Introduis une nouvelle classe `LivreAudio` qui hérite de la classe `Livre`. Ajoute un attribut `duree` à la classe `LivreAudio`.

### Exercice 4 : Polymorphisme
Implémente une méthode `afficher_details` pour la classe `LivreAudio` qui affiche les détails du livre audio, y compris la durée.

### Exercice 5 : Encapsulation
Modifie la classe `Livre` pour que les attributs soient privés. Ajoute des méthodes d'accès (getters et setters) appropriées.

### Exercice 6 : Méthode statique
 Ajoute une méthode statique à la classe `Livre` qui retourne le nombre total de livres créés.

### Exercice 7 : Modules
Introduis un module `Empruntable` avec une méthode `emprunter` dans la classe `Livre`. Ajoute cette fonctionnalité à la classe `Livre` et `LivreAudio`.

### Exercice 8 : Utilisation dans une application
 Crée quelques instances de `Livre` et `LivreAudio`. Utilise les méthodes définies dans les exercices précédents pour afficher des détails, emprunter un livre, etc.

### Exercice 9 : Application de Gestion de Bibliothèque
Utilise les classes `Livre` et `LivreAudio` que tu as créées pour construire une petite application de gestion de bibliothèque.

1. **Création de la bibliothèque :**
   - Initialise une liste vide `bibliotheque` dans laquelle tu stockeras tes livres.

2. **Ajout de livres :**
   - Crée quelques instances de `Livre` et `LivreAudio` et ajoute-les à la bibliothèque.

3. **Affichage des détails :**
   - Utilise la méthode `afficher_details` pour afficher les détails de chaque livre dans la bibliothèque.

4. **Emprunt de livres :**
   - Emprunte un livre en utilisant la méthode du module `Empruntable`. Affiche ensuite les détails du livre emprunté.

5. **Statistiques de la bibliothèque :**
   - Utilise la méthode statique que tu as créée pour afficher le nombre total de livres dans la bibliothèque.

6. **Gestion des retours :**
   - Implémente une méthode `retourner` dans les classes `Livre` et `LivreAudio` qui indique que le livre est de retour. Si tu as utilisé le module `Empruntable`, mets à jour le statut.
