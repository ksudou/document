# docker-compose 起動方法

## 起動
```
# foregroundで起動
$ docker-compose -f docker-compose.yml up
# backgroundで起動
$ docker-compose -f docker-compose.yml up -d
```

## 停止
```
$ docker-compose -f docker-compose.yml stop
```

## 停止 & 削除
```
$ docker-compose -f docker-compose.yml down
```
