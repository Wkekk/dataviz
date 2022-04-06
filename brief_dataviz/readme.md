# Brief docker/grafana

## Le projet

Ce projet avait pour objectif l'utilisation de docker et grafana afin de faire de la data visiualisation et d'utiliser des container.

## Le déroulé

Nous avons commencé par récupérer les différentes images des logiciel à utiliser, à savoir MySQL et Grafana. nous avons ensuite créé les différent fichier nécéssaire au lancement du projet : `stack.yml` pour avoir une interface graphique pour la base de donnée MySQL, `docker-compose.yml`, `Dockerfile` et `devcontainer.json` pour le fonctionnement de Grafana. Pour faire fonctionner le ^projet de manière cohérente nous avons fait attention à ce que les différent processus puisse comuniquer entre eux en respectant les différent ports et sockets. Une fois les processus lancé nous avons chargé la base `vaccinations.sql` dans l'interface graphique de MySQL. 

### Les graphiques

Pour la création des différent graphiques nous avons utilisé grafana et son interface graphique, nous avons pu créer facilement les différentes requêtes permettant d'afficher les données (que ce soit l'évolution du nombre de vaccinations en France ou le nombre de personnes complètemlent vaccinées en italie).