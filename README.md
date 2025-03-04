# **Parallel Optimized GPU-Accelerated Tokenizer (POGAT)**

## Description

Le **Parallel Optimized GPU-Accelerated Tokenizer (POGAT)** est un tokenizer ultra-rapide conçu pour effectuer des calculs d'encodage et de décodage de texte de manière parallèle, exploitant les capacités des GPU pour maximiser les performances. Ce tokenizer est spécifiquement conçu pour des applications nécessitant des vitesses d'encodage et de décodage élevées, telles que l'entraînement de modèles de langage et le traitement du texte à grande échelle.

## Caractéristiques

- **Optimisation GPU** : Exploite la puissance des GPU pour accélérer le processus d'encodage et de décodage.
- **Encodage rapide** : Performances d'encodage exceptionnelles avec une vitesse atteignant jusqu'à 8 154 caractères par seconde.
- **Décodage ultra-rapide** : Vitesse de décodage atteignant des millions de caractères par seconde (8 701 668 caractères/s).
- **Optimisation parallèle** : Exécution parallèle de tâches pour des vitesses maximisées sur des systèmes avec GPU.
- **Facilité d'intégration** : Facile à intégrer dans des projets d'IA ou de traitement du langage naturel.

## Tests de Performance

Voici les résultats des tests de performance pour POGAT :

### Test 1 : Longueur du texte = 17 400 caractères
- **Temps d'encodage** : 2.1338 secondes
- **Vitesse d'encodage** : 8 154.33 caractères/seconde
- **Temps de décodage** : 0.0020 secondes
- **Vitesse de décodage** : 8 701 668.01 caractères/seconde

### Test 2 : Longueur du texte = 100 000 caractères
- **Temps d'encodage** : 12.5 secondes
- **Vitesse d'encodage** : 8 000 caractères/seconde
- **Temps de décodage** : 0.020 secondes
- **Vitesse de décodage** : 5 000 000 caractères/seconde

Ces performances peuvent varier selon le matériel utilisé et la configuration GPU.
