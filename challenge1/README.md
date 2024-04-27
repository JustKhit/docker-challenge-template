# Steps
1. Create public folder with index.html in it
2. Edit index.html includes my name and student id
3. Create a Dockerfile
4. Put docker commands in it.
5. Build docker image by `docker build -t webserver .`
6. Run the built image `docker run -it --rm -d -p 8080:80 --name web webserver`