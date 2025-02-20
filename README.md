# sandbox-build

This is a test to build Apptainer containers using GitHub actions and to store them as GitHub packages.

To create a new container image, or to rebuild the exiting containers, you have to add or modify the container definition file, tag the repository with a new version and push it to GitHub. The build and deploy [action](.github/workflows/apptainer-build-deploy.yml) will subsequently build the containers and push then to the GitHub Container repository.