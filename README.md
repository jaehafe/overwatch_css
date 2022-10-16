
scss - parcel bundler를 이용한 초기 세팅 방법

$ npm init -y
$ npm i -D parcel-bundler

// package.json
> 추가
"scripts": {
    "dev": "parcel index.html",
    "build": "parcel build index.html"
  },

> 파일 생성
index.html
main.scss 

> index.html에 연결
<link rel="stylesheet" href="./main.scss" />
