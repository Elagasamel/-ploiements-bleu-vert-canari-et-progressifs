#Déploiements colorés : introduction aux déploiements bleu-vert, canari et progressifs

## Déploiement bleu-vert 
Le déploiement bleu-vert , en bref, consiste à avoir deux environnements identiques, devant lesquels se trouve un routeur ou un équilibreur de charge qui permet de diriger le trafic vers l'environnement approprié 
## Canary 
Canary consiste à déployer une application par petites étapes incrémentielles et uniquement pour un petit groupe de personnes. Il existe quelques approches possibles, la plus simple étant de ne servir qu'un certain pourcentage du trafic vers la nouvelle application
## Déploiement progressif
Le déploiement progressif est la stratégie de déploiement par défaut dans OpenShift. En bref, ce processus consiste à remplacer lentement les instances en cours d'exécution de notre application par de nouvelles.
