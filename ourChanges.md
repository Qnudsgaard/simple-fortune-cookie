Created a new branch called "dev"
Created the file "ourChanges.md" to track the changes we make along the way
Made a pull request to merge the "ourChanges.md" file into the main branch(To test of it works)

Install go on cloud instance "sudo apt install golang-go"

Added the "frontend, backend and redis" to docker-compose and connected the dependencies and environments(Able to write a fortune, but not see the ones already made)

Added Dockerfile for frontend and backend, and connecteda database. We made a change in docker-compose, from an image argument to a build argument and removed enviroments. (Thought we started with k8 but we started without)
