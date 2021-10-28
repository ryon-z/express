# Express with Typescript

## Node.js 설치
패키지 매니저를 통한 설치 https://nodejs.org/ko/download/package-manager/

Ubuntu https://github.com/nodesource/distributions/blob/master/README.md

Node.js LTS
```bash
$ curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
$ sudo apt-get install -y nodejs
```

## Express 설치
```bash
npm init
npm install express --save
```

## Typescript 설치
```bash
npm install typescript --save-dev # typescript 설치

tsc --init  # tsconfig.json 설정

npm install @types/node --save-dev
npm install @types/express --save-dev
npm install ts-node --save-dev
```

## nodemon
Simple monitor script for use during development of a node.js app.
https://www.npmjs.com/package/nodemon
```bash
npm install nodemon --save-dev
```




