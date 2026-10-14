---
date: 2026-10-14
hide:
  - navigation
---

# d.run AI 操作系统 v0.45.0

本页可下载 d.run AI 操作系统的离线安装包和校验文件。

[返回下载导览页](../index.md#_2){ .md-button } [更多历史版本](./index.md){ .md-button }

## 下载

| 文件名称 | 版本 | 架构 | 文件大小 | 下载 | 更新日期 |
| ------- | --- | ---- | ------ | --- | ------- |
| offline-v0.45.0-amd64.tar | v0.45.0 | AMD 64 | 41.28 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.45.0-amd64.tar) | 2026-10-14 |
| offline-v0.45.0-arm64.tar | v0.45.0 | <font color="green">ARM 64</font> | 38.06 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.45.0-arm64.tar) | 2026-10-14 |

## 校验

进入离线安装包下载目录。

=== "AMD 64"

    执行以下命令校验安装包：

    ```sh
    echo "703ecee8d2512a6a14386d6fb7ea443c11f34a4792c41ce13aa59862147bda6912c79cad1edef8e16f3b2385095d9c56c1f5ae2e0365fd1bbfff0cb7ab6d9617  offline-v0.45.0-amd64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-v0.45.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令校验安装包：

    ```sh
    echo "401db857d9973bc8f6bc96fcda8dedd106f5d81e31213914ead76df61b021796ec214d981c9da205913289e8d23640446bf53479b7d92e19dbda5712704a6051  offline-v0.45.0-arm64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-v0.45.0-arm64.tar: OK
    ```

## 安装

成功校验离线包之后，

=== "AMD 64"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-v0.45.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-v0.45.0-arm64.tar
    ```

- 安装请参阅[商业版安装流程](../../install/commercial/start-install.md)
- 成功安装之后请联系我们授权：电邮 info@daocloud.io 或致电 400 002 6898

## 模块

d.run AI 操作系统包含以下模块，按需即插即用满足各类应用场景：

| 模块 | 介绍 | 最新动态 |
| ---- | --- | ------ |
| ClawOS | 多智能体运行和治理平台 | [v0.7.0](../../drun/clawos/workspace/index.md) |
| 大模型服务平台 | 提供从模型部署到运维管理的全生命周期服务，帮助企业和开发者高效地接入和使用各类大模型能力 | [v0.19.3](../../insight/intro/release-notes.md#v0193) |
| AI Lab | 训推一体化平台，算力资源统一调度，简化 AI 应用开发和部署 | [v0.30.0](../../insight/intro/release-notes.md#v0300) |
| 容器管理 | 管理集群、节点、工作负载、Helm 应用、CRD、命名空间等 K8s 核心功能 | [v0.50.1](../../kpanda/intro/release-notes.md#v0501) |
| 设备管理 | 面向智算中心打造的 Kubernetes 云原生基础设施管理组件，能够统一管理主机、交换机等硬件资源 | [v0.17.0](../../mspider/intro/release-notes.md#v0170) |
| 镜像仓库 | 用于存储 K8s、DevOps 和容器应用开发的镜像 | [v0.26.0](../../kangaroo/intro/release-notes.md) |
| 云原生网络 | 针对不同的 Linux 内核，支持多种 CNI 组合方案 | [v0.19.1](../../network/intro/release-notes.md) |
| 云原生存储 | 提供统一数据存储服务，支持文件、对象、块、本地存储，轻松接入存储厂商方案 | [v1.1.1](../../storage/hwameistor/release-notes.md) |
| 全局管理 | 负责用户访问控制、权限、工作空间与层级、审计日志、个性化外观设置等 | [v0.50.0](../../ghippo/intro/release-notes.md#v0500) |
| 可观测性 | 提供丰富的仪表盘、场景监控、数据查询、告警等图文信息 | [v0.45.0](../../insight/intro/release-notes.md#v0450) |

## 更多

- [在线文档](../../index.md)
- [报告 bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
