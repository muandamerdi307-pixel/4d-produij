# 4D PRODUIJ — Android MVP 1.0

Prototype Flutter Android avec :
- écran d'accueil / connexion par numéro (interface de démonstration, sans SMS réel)
- navigation Accueil, Découvrir, Créer, LIVE et Profil
- identité bleu électrique et noir
- seuil LIVE affiché à 1 000 abonnés

## Ouvrir le projet
1. Installer Flutter et Android Studio sur un ordinateur, ou utiliser un environnement cloud compatible Flutter.
2. Ouvrir ce dossier comme projet Flutter.
3. Exécuter `flutter pub get`.
4. Connecter un appareil Android ou démarrer un émulateur.
5. Exécuter `flutter run`.

Pour générer un APK de test : `flutter build apk --debug`.
APK de publication : `flutter build apk --release` (après configuration de signature).

## Ce qui n'est pas encore connecté
Cette version est un MVP d'interface/navigation. Elle ne contient pas encore de backend, base de données, SMS OTP, téléversement réel de vidéos, streaming LIVE, cadeaux monétaires, paiements, modération serveur ni système de certification. Ces modules nécessitent des services sécurisés et des tests avant publication.
