Développement d'un modèle prédictif permettant d'anticiper les réservations de vols des clients. Optimisation du ciblage marketing grâce à une analyse approfondie des comportements d'achat, atteignant un score AUC-ROC de 0.77.

Points clés (Bullet points pour l'expérience)
Ingénierie des données & Pipeline : Nettoyage et préparation de données complexes via un pipeline automatisé incluant le regroupement de catégories rares, l'encodage One-Hot et la standardisation des variables.

Modélisation Avancée : Entraînement et optimisation d'un algorithme Random Forest avec gestion du déséquilibre des classes (class_weight='balanced') pour maximiser la détection des acheteurs.

Optimisation des Performances : Utilisation de la Validation Croisée et du GridSearch pour affiner les hyperparamètres, améliorant la capacité de distinction du modèle à 77% (AUC).

Analyse de l'Importance des Variables : Identification des leviers de conversion majeurs : l'origine géographique du client, l'itinéraire de vol et le délai d'achat.

Déploiement Opérationnel : Création d'un outil de prédiction en ligne de commande (CLI) permettant aux équipes métier de tester instantanément la probabilité de conversion d'un nouveau profil client.

Compétences techniques validées :
Langages : Python (Pandas, Scikit-Learn).

Méthodes : Classification binaire, Random Forest, Evaluation (Matrice de confusion, Courbe ROC).

Outils : Pipelines Scikit-Learn, Joblib, CLI Development.
