# paper-devops-1
LIDICalSo Paper about DevOps and Infrastructure

Useful Links:

| *Tool* | *Link* | *Credentials* |
| ------------- | ------------- | ------------- |
| Jenkins | http://${docker-machine ip default}:18080 | no login required |
| SonarQube | http://${docker-machine ip default}:19000 | admin/admin |
| Nexus | http://${docker-machine ip default}:18081 | admin/admin123 |
| GitLab | http://${docker-machine ip default}:10080 | root/5iveL!fe |
| Redmine | http://${docker-machine ip default}:10083 | admin/admin |

Steps:

1. docker-compose pull

2. mkdir /opt/docker/gitlab/gitlab /opt/docker/gitlab/redis /opt/docker/postgres/data

3. Start GitLab
docker-compose up -d gitlab

4. Start Nexus (It may take a few mintues)
docker-compose up -d nexus

5. Start Sonar (It may take a few mintues)
docker-compose up -d sonar
