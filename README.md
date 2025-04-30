<p align="center">
  <img src="aura.png" alt="Logo" width="200" height="200">
</p>

# AURA

Application Android bancaire de consultation de solde et virement entre utilisateurs.

Développée en **Kotlin** avec une architecture **MVVM**, en exploitant les bonnes pratiques Android modernes.



---



## 🚀 Présentation du projet

**Contexte** :  
L'application **AURA** a été conçue pour simuler une expérience bancaire fluide, permettant à un utilisateur de consulter son **solde en temps réel** et de réaliser des **virements** sécurisés.

**Mission** :  
- Repenser une ancienne structure **monolithique** pour migrer vers une architecture **MVVM propre** et scalable.
- Intégrer **Retrofit** pour les échanges REST avec un backend simulé.
- Utiliser **Hilt** pour l'injection de dépendances.
- Mettre en place des **états UI réactifs** (chargement, erreur, succès).
- Couvrir les logiques métier avec des **tests unitaires** robustes.



---



## ⚙️ Fonctionnalités principales

- Authentification de l'utilisateur via une API REST.
- Affichage dynamique du **solde bancaire**.
- Envoi de **virements bancaires** vers un autre utilisateur.
- **Gestion centralisée des états** (`Loading`, `Success`, `Error`) via sealed classes.
- **Navigation intuitive** entre les écrans (connexion, home, virement).
- **Reconnexion automatique** ou manuelle en cas d'échec réseau.
- **Tests unitaires** pour valider les cas d’usage et logique ViewModel.



---



## 📈 Tâches réalisées

| Étape | Objectifs | Résultats |
| :--- | :--- | :--- |
| **Refactor architecture** | Passage d’une structure monolithique vers MVVM | Séparation claire UI / logique / données |
| **Connexion utilisateur** | Authentification via API REST | Intégration de Retrofit avec gestion des erreurs |
| **Gestion des virements** | Envoi de virement avec validation | État réactif selon la réponse du serveur |
| **UI + UX** | Navigation et feedback utilisateur | Interface simple et retour visuel clair |
| **Tests unitaires** | Sécuriser la logique métier | Utilisation de JUnit et MockK sur les ViewModels |



---



## 🛠️ Stack technique

- **Langage** : Kotlin
- **UI** : Jetpack Compose (partiel)
- **Architecture** : MVVM (Model - View - ViewModel)
- **Networking** : Retrofit + OkHttp + Moshi
- **DI** : Hilt
- **Asynchrone** : Kotlin Coroutines + Flow
- **Tests** : JUnit 4 + MockK
- **IDE** : Android Studio




---



## 🎯 Résultat final

✅ Application fluide respectant le pattern **MVVM**.  
✅ Communication REST fiable grâce à **Retrofit**.  
✅ Code modulaire et testable avec **Hilt**.  
✅ Gestion d’états centralisée et intuitive.  
✅ Couverture **tests unitaires** sur les ViewModels métier.



---



![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)
![MVVM](https://img.shields.io/badge/MVVM-000000?logo=android&logoColor=white)
![Retrofit](https://img.shields.io/badge/Retrofit-2.9.0-orange?logo=retrofit)
![Hilt](https://img.shields.io/badge/Hilt-DI-blueviolet?logo=dagger&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit-25A162?logo=java&logoColor=white)
![MockK](https://img.shields.io/badge/MockK-Mocking-red?logo=kotest)
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?logo=androidstudio&logoColor=white)
![Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?logo=jetpackcompose&logoColor=white)

---
