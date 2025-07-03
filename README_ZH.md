<p align="center">
  <h1 align="center">SeaTunnel分布式数据集成平台</h1>
  <p align="center">
    <a href="README.md"><strong>English</strong></a> | <strong>简体中文</strong>
  </p>

## 目录

- [仓库简介](#项目介绍)
- [前置条件](#前置条件)
- [镜像说明](#镜像说明)
- [获取帮助](#获取帮助)
- [如何贡献](#如何贡献)

## 项目介绍
[SeaTunnel](https://github.com/apache/seatunnel) 是一个非常易用、超高性能的分布式数据集成平台，支持实时海量数据同步。

**为什么需要 SeaTunnel**
SeaTunnel专注于数据集成和数据同步，主要旨在解决数据集成领域的常见问题：
- **数据源多样：** 常用数据源有数百种，版本不兼容。 随着新技术的出现，更多的数据源不断出现。 用户很难找到一个能够全面、快速支持这些数据源的工具。
- **同步场景复杂：** 数据同步需要支持离线全量同步、离线增量同步、CDC、实时同步、全库同步等多种同步场景。
- **资源需求高：** 现有的数据集成和数据同步工具往往需要大量的计算资源或JDBC连接资源来完成海量小表的实时同步。 这增加了企业的负担。
- **缺乏质量和监控：** 数据集成和同步过程经常会出现数据丢失或重复的情况。 同步过程缺乏监控，无法直观了解任务过程中数据的真实情况。
- **技术栈复杂：** 企业使用的技术组件不同，用户需要针对不同组件开发相应的同步程序来完成数据集成。
- **管理和维护困难：** 受限于底层技术组件（Flink/Spark）不同，离线同步和实时同步往往需要分开开发和管理，增加了管理和维护的难度。

本项目提供的开源镜像商品 [**SeaTunnel**]()，已预先安装 SeaTunnel 及其相关运行环境，并提供部署模板。快来参照使用指南，轻松开启“开箱即用”的高效体验吧。

> **系统要求如下：**
> - CPU: 2GHz 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GB

## 前置条件
[注册华为账号并开通华为云](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## 镜像说明

| 镜像规格                         | 特性说明                                           | 备注 |
|------------------------------|------------------------------------------------| --- |
| [SeaTunnel-2.3.10-鲲鹏-v1.0]() | 基于 鲲鹏服务器 + Huawei Cloud EulerOS 2.0 64bit 安装部署 |  |

## 获取帮助
- 更多问题可通过 [issue](https://github.com/HuaweiCloudDeveloper/seatunnel-image/issues) 或 华为云云商店指定商品的服务支持 与我们取得联系
- 其他开源镜像可看 [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## 如何贡献
- Fork 此存储库并提交合并请求
- 基于您的开源镜像信息同步更新 README.md
