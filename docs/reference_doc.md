# PAMS React install & 개발 가이드 문서

> 이 문서는 PAMS Frontend 전체 개발 과정과 관련된 설치 부터 개발, 배포 까지 모두를 기록 하는 문서 입니다.



## 1주차

### 설치

* create-react-app을 사용했다.

* 기존에 node와 npm은 설치되어있던 것으로 하였다.

  ```bash
  #version
  
  zsh> node -v
  zsh> v10.15.0
  zsh> npm -v
  zsh> 6.4.1
  ```

  ```bash
  zsh> yarn global add create-react-app # create-react-app으로 react 프로젝트 세팅
  zsh> cre3ate-react-app pams # pams react 프로젝트 생성
  zsh> cd pams && yarn start # react server run
  ```

* velopert 블로그를 보고 세팅하던 중에, sass 관련 라이브러리 설치도 있었고, 그냥 이걸 써보기로 했다..

  ```bash
  zsh> yarn add node-sass
  ```

* 설치 끝