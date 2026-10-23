# Architecture logicielle

## Présentation
 Participants : ABID Faycal - KHETACHE Billal
Ce dépôt regroupe mes travaux pratiques réalisés dans le cadre du cours d’architecture logicielle. L’objectif est de comprendre les principaux modèles d’architecture, leur organisation et leurs avantages en matière de conception, de maintenance et de test.

## Objectifs pédagogiques

- Comprendre les architectures MVC, MVP et MVVM.
- Identifier les responsabilités du modèle, de la vue et du contrôleur ou ViewModel.
- Étudier les interactions entre les composants d’une application.
- Mettre en place des tests automatisés avec Node.js.
- Appliquer et tester des règles métier.

## Technologies utilisées

- JavaScript
- Node.js
- Git et GitHub
- Markdown
- Mermaid pour les diagrammes de séquence

## Contenu du projet

- `TodoModel.js` : modèle de gestion des tâches et règles métier.
- `TodoModel.test.js` : tests unitaires du modèle.
- `TodoModel.regle.test.js` : tests de la règle limitant les titres à 60 caractères.
- `comparaison.md` : comparaison des architectures MVC, MVP et MVVM.
- `sequences.md` : diagrammes de séquence illustrant les interactions entre composants.

*Les fichiers peuvent être répartis dans différents sous-dossiers selon l’organisation du TP.*

## Règle métier étudiée

Un titre de tâche ne peut pas dépasser 60 caractères.

- Un titre de 60 caractères est accepté.
- Un titre de plus de 60 caractères est refusé avec le message : `60 caractères maximum`.
- Un titre vide est refusé.

## Exécution des tests

Depuis la racine du projet, exécuter les tests avec :

```bash
node --test
```

Pour lancer uniquement les tests de la règle métier :

```bash
node --test seance1-presentation/tp1-ABID-Faycal/TodoModel.regle.test.js
```

Adapter le chemin si les fichiers sont organisés différemment.

## Auteur

**ABID Faycal**

Étudiant en Master 1 Data & Intelligence Artificielle
