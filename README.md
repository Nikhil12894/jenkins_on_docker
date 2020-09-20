## Jinkins on Docker.

for this I used jenkins officeal image from docker hub with [docker-compose.yml](https://github.com/Nikhil12894/jenkins_on_docker/blob/master/docker-compose.yml).

#### volumes

> * `- ~/jenkins:/var/jenkins_home`
> * `- /var/run/docker.sock:/var/run/docker.sock`
> * `- /usr/local/bin/docker:/usr/local/bin/docker`
> * `- /usr/bin/docker:/usr/bin/docker`
> * `- /usr/local/bin/docker-compose:/usr/local/bin/docker-compose`
