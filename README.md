# docker-challenge-template

1. Installation Docker following this guide https://docs.docker.com/desktop/install/mac-install/ (I am using MacOS)
2. Try build up db
- Installing mariadb (not sure do I need it yet)
3. Then, update the docker-compose.yml
4. Update Dockerfile in db folder because there was an error about path to COPY /init/init.sql /docker-entrypoint-initdb.d
5. Run docker up again but also found path issues on Dockerfiles. So I modified it.
6. 