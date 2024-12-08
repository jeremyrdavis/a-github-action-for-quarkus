# quarkus-github-action
A GitHub Action file that checks out, packages, builds and pushes a Docker container

## Description
The build uses Temeurin Java 21.  Check with actions/setup-java@v4 to change the version.

The Docker container uses the POM's artifactId for the name of the container and the POM's version for version.  The container is also tagged, "latest."

## To Use
Drop the .github directory into your Quarkus project.  Add your Docker hub username and an access token as secrets to your repository's actions.  Directions for creating tokens can be found here: https://docs.docker.com/security/for-developers/access-tokens/

![actions-secrets-values](actions-secrets-values.png)


# a-github-action-for-quarkus
