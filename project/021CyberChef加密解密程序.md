<center>CyberChef加密解密程序</center>





[toc]







## CyberChef

> CyberChef加密解密程序
>
> 网络瑞士军刀——一款用于加密、编码、压缩和数据分析的Web应用程序
>
> [github](https://github.com/gchq/CyberChef)





### 1. 安装

```shell
services:
  cyberchef:
    image: ghcr.io/gchq/cyberchef:latest
    container_name: cyberchef
    restart: always
    ports:
      - 1004:8080
    # 资源限制（可选，防止占用过多内存）
    deploy:
      resources:
        limits:
          memory: 512M
```











