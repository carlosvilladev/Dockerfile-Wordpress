# Dockerfile-Wordpress

###Para contruir nuestra imagen con la configuración del DockerFile
docker build -t wordpress:claseutb_1 .

###Creamos nuestro contenedor
docker run -p 80:80 --name mydocker -d wordpress:claseutb_1

###Lo iniciamos con
docker start mydocker

###Servidor OK
Podemos revisar en http://localhost:80
