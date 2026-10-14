---
date: 2026-10-14
hide:
  - navigation
---

# DCE 社区版 v0.45.0

本页可下载 DCE 社区版的离线安装包和校验文件。

[返回下载导览页](../index.md){ .md-button } [更多历史版本](./dce5-installer-history.md){ .md-button }

## 下载

| 文件名称 | 版本 | 架构 | 文件大小 | 下载 | 更新日期 |
| ------- | --- | ---- | ------ | --- | ------- |
| offline-community-v0.45.0-amd64.tar | v0.45.0 | AMD 64 | 21.02GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.45.0-amd64.tar) | 2026-10-14 |
| offline-community-v0.45.0-arm64.tar | v0.45.0 | <font color="green">ARM 64</font> | 19.93GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.45.0-arm64.tar) | 2026-10-14 |

## 校验

进入离线安装包下载目录。

=== "AMD 64"

    执行以下命令校验安装包：

    ```sh
    echo "6850986ed120b7320317fc72f9b0409c7c24a1def22786c92da22151f36bf87caef80797193e25d1a33aeaf7a32b187f652ab9142d2fb87ccd8d2cef15fcb182  offline-community-v0.45.0-amd64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-community-v0.45.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令校验安装包：

    ```sh
    echo "4e91d576de32fc9a10779b6179f1888e72671158623c5ca51c9f57b35b74c0cb48a64447a11cb7a26ec1cbce49499ebfb84fa571878b1b9afb099b3a0354ea2d  offline-community-v0.45.0-arm64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-community-v0.45.0-arm64.tar: OK
    ```

## 安装

成功校验离线包之后，

=== "AMD 64"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-community-v0.45.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-community-v0.45.0-arm64.tar
    ```

- 安装请参阅[社区版安装流程](../../install/community/k8s/online.md#_2)
- 成功安装之后请[申请免费社区体验](../../dce/license0.md)

## 模块

DCE 社区版默认包含以下模块：

| 模块     | 介绍            | 最新动态         |
| -------- | -------------- | -------------- |
| 全局管理 | 负责用户访问控制、权限、工作空间与层级、审计日志、个性化外观设置等 | [0.50.0](../../ghippo/intro/release-notes.md#0500) |
| 容器管理 | 管理集群、节点、工作负载、Helm 应用、CRD、命名空间等 K8s 核心功能 | [0.50.1](../../kpanda/intro/release-notes.md#0501) |
| 可观测性 | 提供丰富的仪表盘、场景监控、数据查询、告警等图文信息 | [0.45.0](../../insight/intro/release-notes.md#0450) |

## 更多

- [在线文档](../../dce/index.md)
- [报告 bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
