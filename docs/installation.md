# SeaTunnel部署指南

## ‌一、环境准备

### 一、更新系统

```bash
yum -y update  
yum -y upgrade
```

## ‌二、安装docker

#### EulerOS2.0
参考：[安装Docker](https://support.huaweicloud.com/bestpractice-hce/hce_bp_0002.html)

## ‌三、拉取镜像和创建容器

### 1.拉取镜像
```bash
docker pull apache/seatunnel:2.3.10
```
### 2.运行内置示例

```bash
docker run --rm -it apache/seatunnel:2.3.10 ./bin/seatunnel.sh -m local -c config/v2.batch.config.template
```
