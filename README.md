# elasticsearch-seunjeon-docker
은전한닢 플러그인이 포함된 Elasticsearch Dockerfile과 docker-compose 입니다. 
[dockerfile 팀](https://github.com/dockerfile)과 [Elasticsearch 문서](https://www.elastic.co/guide/en/elasticsearch/reference/5.2/docker.html)를 참고하여 만들었으며,
작성 기준 seunjeon plugin의 가장 최신 버전인 5.1.1으로 만들었습니다.

## 실행방법
Docker와 Docker-compose 설치 된 상태로 프로젝트 클론 후 빌드 (프로젝트 루트에서 실행)

```bash
$ docker build -t=elasticsearch-seunjeon-5.1.1 .

Sending build context to Docker daemon   192 kB
Step 1/16 : FROM ubuntu:16.04
 ---> f7b3f317ec73
...
...
...
Successfully built e68266b8c559
```

Docker-compose를 이용하여 실행 
```bash
$ docker-compose up
```


