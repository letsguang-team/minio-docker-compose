# minio-docker-compose

此项目为minio服务器使用中模板

--- 

1. 创建文件夹，以项目名称命名
2. 复制examples/minio.env到目录里
3. 按需求修改项目环境配置minio.env
4. 打开终端机，切换到项目目录里
5. 使用 `bin/docker-compose-plus` 代理 `docker-compose` 操作

```
# 调用方式： {此库路径}/bin/docker-compose-plus [按照docker-compose方式传入参数]

# 例
docker-compose up -d
# 即
{此库路径}/bin/docker-compose-plus up -d
```

