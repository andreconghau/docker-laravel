## Init

docker-compose up -d --build

## start
docker-compose up


## Down

docker-compose down => tat docker


## Check list images
andre@andres-MBP:~/www/2022/docker-laravel$ docker-compose images
Container         Repository         Tag       Image Id       Size
--------------------------------------------------------------------
real_mysql   docker-laravel_mysql   latest   4e5536c07f08   519.4 MB
real_nginx   docker-laravel_nginx   latest   6907293d9615   141.5 MB
real_php     docker-laravel_php     latest   d0c61abc8fa1   481.5 MB




## access docker

docker-compose exec {name_docker} bash


andre@andres-MBP:~/www/2022/docker-laravel$ docker-compose exec nginx bash
root@99bd6d0095db:/var/www/html