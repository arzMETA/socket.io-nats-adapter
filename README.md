# socket.io-nats

Last release: [v0.2.1](https://www.npmjs.com/package/socket.io-nats-adapter) - March 19, 2022

Pub/Sub adapter for socket.io using nats.io as pub/sub message queue

- Implements specification of socket.io adapter
- `at-most-once` semantics on adapter methods

Please let us know if you have any comments or features you would like to request.

## Milestone

- `v0.3`
    - [ ] Authmating test with jest
    - [ ] Performance benchmark tool
    - with `docker` environment

## Setting

Run script for docker setting

```shell
$ cd development
$ docker-compose up -d
```

## Install
```shell
$ npm install
```

## Run
```shell
$ npm start
```

## Test
```shell
$ npm test
```

레퍼런스 : 채널톡

Nats 아키텍처 모음
https://github.com/nats-io/nats-architecture-and-design

타 메시징 시스템들과의 비교
![image](https://github.com/arzMETA/socket.io-nats-adapter/assets/64263207/2aec0424-13eb-4c3b-909f-080e920946c9)
