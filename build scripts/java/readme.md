#### jar包构建镜像

---

```shell
# 构建镜像
docker build -t imagename:tag . --no-cache

# 运行
docker run -d -p 8080:8080 imagename:tag

```

