# Spacey

prerequisites to run the project: docker desktop

Steps to run the project:

1. open terminal and go to the project folder
2. enter command "docker-compose up --build" ("docker-compose up" only if you have already built the project)
3. for frontend, go to localhost:3001
4. for backend, go to localhost: 3000

---

# Useful commands

- docker exect -it space_renter_web bash (go to terninal of the nextjs container)
- docker exect -it space_renter_app bash (go to terninal of the express (backend) container)
- docker exect -it space_renter_app_db mongo (go to terninal of the mongodb)
- docker-compose stop (stops all the containers)
- docker-compose down (stops the container and deletes all the builds)
- docker system prune -a (deletes all the containers and images)
- docker volume prune (deletes all volumes)
