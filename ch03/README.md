# 3주차 - Frontend Dockerfile 제작

### 3주차 - Frontend Dockerfile 더 잘짜보기

- Dockerfile cache에 대해서
    - layer
- multi stage build란?
    - 용량
    - alpine이란?
    - M1 mac에서의 환경설정.... (DOCKER_DEFAULT_PLATFORM=linux/amd64)
- gosu와 tini에 대해
    - root process 와 signal handling
    - trap
    - tini
    - 권한관리및 gosu
- cache, multi stage build, tini까지 포함된 Dockerfile제작해보기

- docker-entrypoint.sh파일 제작
    - entrypoint란?
    - gosu를 포함한 간단한 쉘스크립트
    - docker서비스를 긴급 재시작할수있도록 만드는 trick (쉘프로그래밍)

## 과제

- CMD와 ENTRYPOINT의 차이점은?
- 기존파일 ~~~~~버전도 수정해보기
