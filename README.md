# DevOps
Automatisation des Tests et Intégration Continue

Ce projet met en œuvre une stratégie complète d'automatisation des tests et d'intégration continue pour garantir la qualité et la fiabilité de l'application développée avec Spring Boot et Angular. L'utilisation de Vagrant facilite la création d'environnements de développement cohérents, tandis que Jenkins orchestre le processus d'intégration continue en s'appuyant sur Maven pour la gestion des dépendances et des phases de construction. Les tests unitaires et d'intégration sont réalisés à l'aide de JUnit, assurant une validation approfondie du code.

L'intégration de SonarQube permet une analyse statique du code source, fournissant des métriques de qualité du code et identifiant les zones nécessitant une amélioration. Git, utilisé comme système de contrôle de version, assure une gestion efficace du code source.

Docker et Docker Compose sont employés pour la conteneurisation de l'application, facilitant le déploiement et garantissant la portabilité. Les artefacts sont stockés dans Nexus, garantissant une gestion centralisée des dépendances.

Le suivi des performances est réalisé grâce à Prometheus et Grafana, offrant une visibilité en temps réel sur les métriques système. Enfin, DockerHub est utilisé pour le stockage des images Docker, simplifiant la distribution et la mise à jour de l'application.

Ce processus automatisé garantit une intégration continue fluide, une détection précoce des erreurs et une amélioration continue de la qualité du code, renforçant ainsi la robustesse de l'application tout au long de son cycle de développement. Pour des instructions détaillées sur la configuration et l'exécution de ces processus, veuillez vous référer à la documentation ci-dessous.

