# tiansuo_mall

# 常用命令:

1. 根据API生成代码:

```cmd
goctl api go --api  main.api --dir ../ --style=goZero
```

2. 生成API文档:


```cmd
goctl api plugin -plugin goctl-swagger="swagger -filename api.json -host localhost:8888" -api main.api -dir .
```
