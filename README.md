# Test
test..



## MongoDB

### 1. 설치

install guide : https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/

### 2. 서버 시작 / 종료

시작

```
mongod --config /usr/local/etc/mongod.conf
```

종료

```
mongo admin --eval "db.shutdownServer()"
```

인가 설정 후 종료

```
mongo admin -u root -p 1234 --eval "db.shutdownServer()"
```

