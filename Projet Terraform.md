# Projet Terraform

Le projet utilise Terraform et un fournisseur VMware Workstation pour décrire et gérer des machines Debian dans un laboratoire local.

## Mise en œuvre

- Préparer un modèle Debian et vérifier que l’hôte VMware dispose des ressources et du réseau prévus.
- Décrire les machines et leurs paramètres dans les fichiers Terraform. Séparer les variables du code et fournir les valeurs sensibles via l’environnement.
- Exécuter les étapes d’initialisation, de prévisualisation et de déploiement. Contrôler que les changements attendus figurent dans le plan avant de l’appliquer.
- Vérifier que les machines démarrent et que le service de test est joignable depuis le réseau autorisé.
- Retirer l’infrastructure après le TP et contrôler l’état Terraform.

Le [guide du projet](HOW%20TO.md) complète ces notes.
