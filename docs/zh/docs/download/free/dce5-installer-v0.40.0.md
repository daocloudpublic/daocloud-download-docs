---
date: 2026-05-15
hide:
  - navigation
---

# DCE 5.0 社区版 v0.40.0

本页可下载 DCE 5.0 社区版的离线安装包和校验文件。

[返回下载导览页](../index.md){ .md-button } [更多历史版本](./dce5-installer-history.md){ .md-button }

## 下载

| 文件名称 | 版本 | 架构 | 文件大小 | 下载 | 更新日期 |
| ------- | --- | ---- | ------ | --- | ------- |
| offline-community-v0.40.0-amd64.tar | v0.40.0 | AMD 64 | 12.94GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.40.0-amd64.tar) | 2026-05-15 |
| offline-community-v0.40.0-arm64.tar | v0.40.0 | <font color="green">ARM 64</font> | 12.24GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.40.0-arm64.tar) | 2026-05-15 |

## 校验

进入离线安装包下载目录。

=== "AMD 64"

    执行以下命令校验安装包：

    ```sh
    echo "eb5192c19e0e9beb8ab474269050ac1d5db0dc89a5e737464cbd8eff7374eda957a7631edc77c3b0b03fa1b257db9040db88b62baf690c421229d26cfdedb11e  offline-community-v0.40.0-amd64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-community-v0.40.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令校验安装包：

    ```sh
    echo "ba2bf22c37203c2442bd8f185651ceaa35730e568ac8b5f23f635277e25bc506dd07ed72e8f730f09f8465525d35a1cbf3d0dd02bf970e2871c9e104465e3ffa  offline-community-v0.40.0-arm64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-community-v0.40.0-arm64.tar: OK
    ```

## 安装

成功校验离线包之后，

=== "AMD 64"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-community-v0.40.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-community-v0.40.0-arm64.tar
    ```

- 安装请参阅[社区版安装流程](../../install/community/k8s/online.md#_2)
- 成功安装之后请[申请免费社区体验](../../dce/license0.md)

## 模块

DCE 5.0 社区版默认包含以下模块：

| 模块     | 介绍            | 最新动态         |
| -------- | -------------- | -------------- |
| 全局管理 | 负责用户访问控制、权限、工作空间与层级、审计日志、个性化外观设置等 | [](../../ghippo/intro/release-notes.md#) |
| 容器管理 | 管理集群、节点、工作负载、Helm 应用、CRD、命名空间等 K8s 核心功能 | [](../../kpanda/intro/release-notes.md#) |
| 可观测性 | 提供丰富的仪表盘、场景监控、数据查询、告警等图文信息 | [](../../insight/intro/release-notes.md#) |

## 更多

- [在线文档](../../dce/index.md)
- [报告 bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
