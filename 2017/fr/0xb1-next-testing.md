# +T Pespectives pour les vérificateurs

## Mise en place d'un test permanent de la sécurité applicative

Développer du code sécurisé est important, mais il est capital que la sécurité que vous voulez intégrer soit réellement présente, correctement mise en oeuvre et employée partout où elle devrait l'être. Le test de la sécurité applicative a pour but d'en apporter la preuve. C'est un travail complexe et difficile, tandis que les processus de développement modernes à grande vitesse comme Agile et DevOps font peser une énorme pression sur les outils et approches traditionnelles. De ce fait, nous vous encourageons à bien réfléchir sur la façon dont vous allez pouvoir vous concentrer sur ce qui est important pour la totalité de votre portefeuille applicatif et la façon de le faire au meilleur coût.

Les risques modernes évoluent rapidement : l'époque où un examen minutieux ou un test de pénétration annuel à la recherche de vulnérabilités suffisait est révolue depuis longtemps. Le développement de logiciels modernes impose des tests permanents de sécurité applicative au cours de toute la durée de vie de ce développement. Cherchez à améliorer les outils de développement existants à l'aide de sécurisations automatiques qui ne ralentissent pas le développement. Quelle que soit l'approche que vous retenez, déterminez le coût annuel de test, analyse, remédiation, nouveau test et redéploiement d'une application unique, puis multipliez-le par le nombre d'éléments de votre portefeuille applicatif.

| Activité | Description |
| --- | --- |
| Comprendre le modèle de risques | Avant de débuter tout test, assurez-vous d'avoir compris ce à quoi vous devez consacrer du temps. Les priorités proviennent du modèle de risques : si vous en êtes dépourvu, vous devez en créer un avant de débuter les tests. Reportez vous au [ASVS OWASP](https://owasp.org/www-project-application-security-verification-standard/) et au [Guide de Test OWASP](https://owasp.org/www-project-web-security-testing-guide/) comme point de départ et ne vous fiez pas aux vendeurs d'outils pour décider de ce qui est important pour votre entreprise. |
| Comprendre votre SDLC | Votre approche du test de la sécurité applicative doit être hautement compatible avec le personnel, les processus et les outils impliqués dans le cycle de vie de développement logiciel ou SDLC (_Software Development LifeCycle_). Toute tentative d'introduction forcée d'étapes supplémentaires, de seuils et de contrôles risquent fort de provoquer des tensions, d'être court-circuitées et délicates à adapter. Rechercher des occasions naturelles pour rassembler des informations de sécurité et injectez-les dans votre processus. |
| Stratégies de test | Choisissez la technique la plus simple, la plus rapide et la plus pertinente pour répondre à chaque exigence. La [Base de connaissances de sécurité OWASP](https://owasp.org/www-project-security-knowledge-framework/) et la [norme de vérification de sécurité applicative OWASP](https://owasp.org/www-project-application-security-verification-standard/) peuvent être de précieuses sources d'informations sur les exigences sécuritaires fonctionnelles et non fonctionnelles dans votre processus de tests unitaires et d'intégration. Veillez à prendre en compte les ressources humaines nécessaires pour gérer les faux positifs générés par les outils automatiques ainsi que du danger considérable des faux négatifs.
| Obtenir précision et couverture | Il est inutile de tout tester à fond dès le début. Concentrez-vous sur ce qui est important et développez votre programme de vérification au fil du temps. Cela signifie augmenter l'ensemble des défenses sécuritaires et des risques qui sont automatiquement contrôlés ainsi que le nombre d'applications et d'API concernées. L'objectif est de parvenir à un stade où la sécurité primordiale de toutes vos applications et API est constamment vérifiée. |
| Communiquez clairement sur vos identifications | Peu importe votre efficacité en matière de test : elle n'a aucune importance si vous ne communiquez pas efficacement. Construisez la confiance en montrant que vous comprennez le foncitonnement de l'application. Décrivez clairement, sans employer de jargon,  comment elle pourrait être détournée et illustrez par un scénario d'attaque pour concrétiser. Effectuez une estimation réaliste de la difficulté d'identification et d'exploitation de la faille et des conséquences possibles. Enfin, montrez les résultats dans les outils employés par l'équipe de développement, pas sous forme de fichiers PDF. |