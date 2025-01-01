# Déploiement de l'API Flask sur Heroku

Ce projet met en œuvre une API Flask développée pour supporter un tableau de bord interactif créé avec Streamlit. L'API a été déployée sur la plateforme cloud Heroku afin de fournir des services backend robustes pour des applications basées sur des modèles de scoring de crédit.

## Fonctionnalités
- Implémentation d'une API RESTful avec Flask.
- Support des prédictions basées sur des modèles de machine learning pour le scoring de crédit.
- Connexion avec un tableau de bord Streamlit pour une interface utilisateur interactive.
- Déploiement transparent sur Heroku pour l'accessibilité cloud.

## Structure du projet

Voici les principaux fichiers et dossiers inclus dans ce dépôt :

- `app.py` : Point d'entrée de l'application Flask.
- `requirements.txt` : Liste des dépendances Python nécessaires pour exécuter l'application.
- `Procfile` : Configuration pour le déploiement Heroku.
- `models/` : Contient les fichiers de modèles pré-entrainés utilisés pour le scoring de crédit.
- `templates/` et `static/` : Ressources pour les vues HTML (si applicables).

## Prérequis

Assurez-vous d'avoir les outils suivants installés sur votre machine :

- Python 3.8 ou plus.
- Pip pour la gestion des paquets.
- Un compte Heroku pour le déploiement.

## Installation et déploiement local

1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/KH-spec/app_api_flask.git
   cd app_api_flask
   ```

2. Installez les dépendances :
   ```bash
   pip install -r requirements.txt
   ```

3. Lancez l'application localement :
   ```bash
   python app.py
   ```

4. Accédez à l'application dans votre navigateur à l'adresse [http://127.0.0.1:5000](http://127.0.0.1:5000).

## Déploiement sur Heroku

1. Connectez-vous à Heroku :
   ```bash
   heroku login
   ```

2. Créez une nouvelle application sur Heroku :
   ```bash
   heroku create your-app-name
   ```

3. Poussez le code sur Heroku :
   ```bash
   git push heroku main
   ```

4. Accédez à votre API déployée via l'URL fournie par Heroku.

## Utilisation

- Le backend permet au tableau de bord Streamlit de consommer des données et d'effectuer des prédictions de scoring de crédit.
- Les utilisateurs peuvent envoyer des requêtes POST à l'API pour obtenir des résultats basés sur leurs données d'entrée.

## Contribution

Les contributions sont les bienvenues. Veuillez suivre les étapes suivantes :

1. Forkez ce dépôt.
2. Créez une branche pour votre fonctionnalité ou correction de bug.
3. Soumettez une pull request pour revue.

## Auteur

- **KH-spec** - [GitHub Profile](https://github.com/KH-spec)

## License

Ce projet est sous licence MIT - consultez le fichier [LICENSE](LICENSE) pour plus de détails.

---

★ N'hésitez pas à consulter le dépôt pour plus d'informations et à signaler des problèmes si vous en rencontrez. Bonne exploration !
