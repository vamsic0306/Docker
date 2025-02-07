#Docker
1. ####### docker build -t <your-dockerhub-username>/<image-name>:<tag> .   ex: docker build -t johnsmith/myapp:v1 .
2. ########## #docker run -d -p 8080:80 <your-dockerhub-username>/<image-name>:<tag>    ex: docker run -d -p 8080:80 johnsmith/myapp:v1
3. ######### docker login
4. ######### docker push <your-dockerhub-username>/<image-name>:<tag>    ex: docker push johnsmith/myapp:v1

