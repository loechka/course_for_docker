docker exec -it e69590a94abf bash

docker cp wine.data e69590a94abf:/home/jovyan/wine.data 
д
docker run -p 8888:8888 jupyter/scipy-notebook:17aba6048f44

docker run -v /Users/annie/Desktop/docker:/home/jovyan/ -p 8888:8888 jupyter/scipy-notebook:17aba6048f44


<!-- docker build .
docker run -v /Users/annie/Desktop/docker:/home/jovyan/ -p 8888:8888 0649d149f1d8
взято из Successfully built после билда -->

то же самое с тэгом

docker build -t my_notebook .
docker run -v /Users/annie/Desktop/docker:/home/jovyan/ -p 8888:8888 my_notebook

docker-compose up