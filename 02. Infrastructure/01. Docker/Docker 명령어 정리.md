## Docker 실행 명령어 정리

<br>

**🎈 Docker run 명령어**

* 컨테이너를 새로 생성하는 경우 사용
  
  `docker run [OPTIONS] IMAGE[:TAG|@DIGEST] [COMMAND] [ARG...]`
  
  `docker run --rm -it ubuntu:20.04 /bin/sh`

<br>

**🎈 Docker exec 명령어**

* 현재 실행되고 있는 컨테이너에 작업하는 경우 사용

  `docker exec [OPTIONS] CONTAINER COMMAND [ARG...]`
  
  `docker exec -it my_container sh -c "echo a && echo b"`

<br>

**📖 Docker 실행 option 종류**

  * 자세한 옵션 종류는 [해당](https://docs.docker.com/reference/cli/docker/container/run/#options) 링크 참조
  
    ![Docker Run Options](https://d36u0n6bmvvikl.cloudfront.net/github/docker-run-options.png)

  
  
<br>

