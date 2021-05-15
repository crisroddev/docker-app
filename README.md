1. `docker build --tag=api .`
2. `docker image ls`
3. `docker run -p 8000:5001 -it --rm -d --name my-running-app api`
4. `docker exec -it containerID bash`