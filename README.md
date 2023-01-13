# создание своего образа image 
docker build -t my-php-apache ./php 

# создание контейнера 
docker run -p 100:80 --name MyPhpApache -d my-php-apache 



# построение из файла docker-compose.yml 
docker-compose build 
# запуск образов из docker-compose.yml 
docker-compose up 