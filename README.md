# IT Will Online Judge - Front end
[![vue](https://img.shields.io/badge/vue-2.5.13-blue.svg?style=flat-square)](https://github.com/vuejs/vue)
[![vuex](https://img.shields.io/badge/vuex-3.0.1-blue.svg?style=flat-square)](https://vuex.vuejs.org/)
[![echarts](https://img.shields.io/badge/echarts-3.8.3-blue.svg?style=flat-square)](https://github.com/ecomfe/echarts)
[![iview](https://img.shields.io/badge/iview-2.8.0-blue.svg?style=flat-square)](https://github.com/iview/iview)
[![element-ui](https://img.shields.io/badge/element-2.0.9-blue.svg?style=flat-square)](https://github.com/ElemeFE/element)
[![Build Status](https://travis-ci.org/QingdaoU/OnlineJudgeFE.svg?branch=master)](https://travis-ci.org/QingdaoU/OnlineJudgeFE)

## 개발자
박지성

## 특징
- 웹팩3(Webkpack3)를 활용한 다중 페이지
- 쉽게 사용할 수 있는 코드 에디터
- E-Charts를 활용한 시각화 모듈
- 사용자 친화적인 명령어 기능

## 설치 방법
1. node js 설치
    ```
    # nvm을 설치합니다.
    curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash

    # nvm 활성화합니다.
    . ~/.nvm/nvm.sh

    # node를 설치합니다.
    nvm install node

    # 8.12.0 버전을 설치합니다.
    nvm install v8.12.0

    # 8.12.0 버전으로 변경합니다.
    nvm use v8.12.0

    # 8.12.0 버전을 기본으로 변경합니다.
    nvm alias default v8.12.0

    # FE 복사
    git clone https://github.com/IllIIIllll/online-judge-frontend.git && cd online-judge-frontend

    # 설치
    npm install

    # 웹팩3 DLL 레퍼런스를 이용해 빌드 시간을 절약합니다.
    # 기본적으로 이 명령어는 build/webpack.dll.conf.js 내부의 패키지를 업그레이드하지 않았다면 한 번만 수행하면 됩니다.
    # (매 번 실행할 필요가 없음.)
    NODE_ENV=development npm run build:dll

    # 개발 서버에서 백 엔드 서버에 프록시 테이블을 설정합니다.
    export TARGET=http://Your-backend

    # 기본적으로 8080 포트에서 프론트 서버가 생성됩니다.
    npm run dev
    ```

## Screenshots

## 브라우저 지원
- 인터넷 익스플로러 10 이상 버전을 포함한 다양한 모던 브라우저를 지원합니다.

## 오픈소스 라이센스
[MIT](http://opensource.org/licenses/MIT)
