## 도커 컨테이너(Docker Desktop)

Docker Desktop을 통해 nginx를 실행해보자.

```
docker pull nginx
docker run --restart always --name <CONTAINER_NAME> -d -p <HOST_PORT>:<CONTAINER_PORT> nginx
```

이후 localhost:<HOST_PORT> 접속

## 호스트에 직접 설치

Mac 기반 컴퓨터에 직접 nginx를 설치해보자.

```
brew install nginx
```

nginx 설치 경로로 접속해보자

```
cd /usr/local/etc/nginx
```

실행 및 중단 명령어는

```
nginx
nginx -s stop
nginx -s reload // 현재 nginx.conf를 반영하여 실행
```
