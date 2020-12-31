# Udacity Project - Refactor Udagram from Monolithic to Microservices Architecture

Purpose of this project is to refactor the initial Monolithic application we built previously into separate microservices.

Entire Project is divided into 4 parts (each in its own directory):
1. udagram-api-user - Source code for User rest api after separating from monolithic application.
2. udagram-api-feed - Source code for Feed rest api after separating from monolithic application.
3. udagram-frontend - ionic frontend application, No changes were made to this part.
4. deploy - contains yaml files for kubernetes services and deployments, also contains reverse proxy and docker compose.

##Travis CI Integration
One of the project requirement was that we build CI/CD pipeline using travisCI. TravisCI is linked to this repository and details are in .travis.yml

##Screen Shots
Relevant Build/Deploy Screen shots are screenshots folder.

## Runing the project:
1. Checkout the code
2. Make sure all dependencies are resolved
3. Setup proper secrets
4. run docker-compose -f docker-compose-build.yaml build --parallel
5. use browser to access