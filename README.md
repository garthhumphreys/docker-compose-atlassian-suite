# Docker Compose Atlassian Suite
Docker compose to start the dockers for the Atlassian tools:
- Jira [https://hub.docker.com/r/atlassian/jira-software](https://hub.docker.com/r/atlassian/jira-software)
- Bitbucket and; [https://hub.docker.com/r/atlassian/bitbucket-server/](https://hub.docker.com/r/atlassian/bitbucket-server/)
- Bamboo [https://hub.docker.com/r/atlassian/bamboo-server](https://hub.docker.com/r/atlassian/bamboo-server)

> Note you will need to [sign-up with Atlassian](https://www.atlassian.com/try) in order to generate a trial key to use these tools in the docker containers.

> Make sure your container has the necessary resources allocated to it. We recommend **2GiB of memory** allocated to accommodate the application server.

## Start all the Atlassian tools
Run the following to start the above tools:
```bash
$ docker compose up
```

Docker compose file made with:
- [https://www.composerize.com/](https://www.composerize.com/)
- [https://github.com/magicmark/composerize](https://github.com/magicmark/composerize)
