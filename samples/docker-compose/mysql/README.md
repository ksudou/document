# 構成
```
├── docker
│   └── db
│       ├── data
│       └── my.cnf
├── docker-compose.yml
└── README
```

# 起動方法
```
docker-compose -f docker-compose.yml up -d
```

# macからのアクセス方法
```
mysql -uroot -p -h 127.0.0.1
```

# 停止
```
docker-compose -f docker-compose.yml down
```
