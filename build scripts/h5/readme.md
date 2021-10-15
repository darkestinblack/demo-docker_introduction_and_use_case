#### 构建H5镜像

------
docker build 命令默认使用当前目录下的dockerfile，作为构建镜像的配置。

dist文件夹、dockerfile、nginx.conf在同一目录下运行 docker build即可构建镜像

```shell
# vue脚手架项目 [-f dockerfile]
docker build . -t imagename:version
# 转码打包h5站点并构建镜像(powershell使用&&会报错，可换成git bash执行命令)
npm run build && docker build . -t imagename:version
```

