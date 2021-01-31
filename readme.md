# Site d'annonces
***
### Description du projet
***
Vous aller devoir créer un site de petites annonces qui n'utilise pas de logins et de mots de passe pour créer une annonce. Le site doit afficher les annonces et permettre d'en ajouter avec une simple adresse email.

Lors de la création d'une nouvelle annonce par un utilisateur anonyme celui-ci va recevoir un courriel avec deux liens. S'il clique sur un des deux lien, il pourra valider son annonce et il pourra également, si il le souhaite, le modifier et le valider avec l'autre lien.
Quand il aura validé, un courriel de confirmation lui sera envoyé (l'annonce a été mise en ligne) et aura dans ce même courriel la possibilité de supprimer son annonce.

Vous devez mettre en place des messages de confirmation lors de la validation et lors de la suppression.(JI)

Vous devez penser à la sécurité de l'application : en effet les nouvelles annonces ne doivent pas être modifiable sans le lien, grâce à un identifiant Unique pour chaque annonce qui vous permettra de la récuperer pour afficher le formulaire de modification.

La page d'accueil doit lister les 10 premières annonces du site et permettre d'afficher les suivantes 10 par 10.

Lorsqu'on clique sur une annonce pour la visualiser plus précisément, celle doit afficher un lien permettant de la télécharger au format pdf.

Vous devez afficher une image par défaut dans le cas où l'utilisateur n'ait pas ajouté d'images à son annonce. Lors de le création de l'annonce ne pas ajouter d'image ne doit pas être bloquant pour l'utilisateur.(JI)

Amelioration :
    1 - Tâche cron qui supprime les annonces qui sont en attente de publication à n+2 jours de la date de création. Envoyer un courriel à la personne de la suppression de son annonce en attente.

    2 - Tâche cron qui supprime les annonces qui sont publiées à n+15 jours de la date de création. Envoyer un mail à la personne de la suppression de son annonce.

    3 - Créer un infinite-scroll pour la pagination des annonces. 
***
### Étapes
- Créer le MCD
- Créer le MLD
- Créer le modèle physique de données
- Installer Composer sous Windows
- Installer vos dépendances PHP : AltoRouteur, mPDF
- Installer nodejs et npm ou yarn
- Installer vos dépendances front : sass
- Définir l'arborescence de vos dossiers
- Mettre en place le .gitignore
- Avec Composer généré l'Autoload (PSR-4)
- Définir les routes nécessaires à votre projet
- Mettre en place le Router et ajouter vos routes
- Créer les contrôleurs et méthodes nécessaires à vos routes
- Back-end : Créer les modèles; Pour chaque méthodes définir les variables nécessaires à la vue
- Front-End : 
    *Réaliser les wireframes de toutes vos pages et emails
    *Réaliser les vues nécessaires pour vos différentes pages
    *Réaliser les MJML de vos mails
    *Réaliser les code pour générer le PDF
    *Réaliser le CSS et responsive
