Created the file "ourChanges.md" to track the changes we make along the way
Made a pull request to merge the "ourChanges.md" file into the main branch (To test of it works).

Install go on cloud instance "sudo apt install golang-go".

Added the "frontend, backend and redis" to docker-compose and connected the dependencies and environments(Able to write a fortune, but not see the ones already made).

Added Dockerfile for frontend and backend, and connected database. We made a change in docker-compose, from an image argument to a build argument and removed enviroments. 

Added CI pipeline by using GitHub Actions. In the folder ".github/workflows" a yaml file is added, and the files contains the jobs for the tests. We're testing clone down, frontend-dockerImage, backend-dockerImage, and frontend-go-test.

Try to add Kubernetes by making a folder containing deployment and service files. Images created and tagged in Docker Hub, pods checked, container checked. 

Kubernetes still doesn't work...


