# My SQL docker 설치





docker image 다운로드

```shell
docker pull mysql:5.7 # mysql 이미지 pull
docker images # docker 이미지 조회
```



docker container run

```shell
docker run -d -p 3306:3306 -e MYSQL_ROOT_PASSWORD=YOUR_PASSWORD_HERE -name thkwon-mysql mysql:5.7
```



docker container bash 접속

```shell
docker exec -i -t thkwon-mysql bash

container bash> mysql -u root -p #mysql 콘솔 접속
```

