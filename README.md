# DockerCourseM2
Este repositorio aloja la informacion de la evaluacion M2 del curso de docker

sudo docker run -d -e USERS="one|1234" -v pwd/archivos:/ftp/one delfer/alpine-ftp-server 

sudo docker build -f Dockerfile-http -t shttp.

sudo docker run -p 8000:8000 -v `pwd`/archivos:/http/http --name=shttp shttp 

sudo docker build -f Dockerfile-ftp -t sftp .

sudo docker run sftp
