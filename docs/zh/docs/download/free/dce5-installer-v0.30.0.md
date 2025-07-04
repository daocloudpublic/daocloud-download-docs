---
date: 2025-07-04
hide:
  - navigation
---

# DCE 5.0 社区版 v0.30.0

本页可下载 DCE 5.0 社区版的离线安装包和校验文件。

[返回下载导览页](../index.md){ .md-button } [更多历史版本](./dce5-installer-history.md){ .md-button }

## 下载

| 文件名称 | 版本 | 架构 | 文件大小 | 下载 | 更新日期 |
| ------- | --- | ---- | ------ | --- | ------- |
| offline-community-v0.30.0-amd64.tar | v0.30.0 | AMD 64 | 13.17GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.30.0-amd64.tar) | 2025-07-04 |
| offline-community-v0.30.0-arm64.tar | v0.30.0 | <font color="green">ARM 64</font> | 12.48GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.30.0-arm64.tar) | 2025-07-04 |

## 校验

进入离线安装包下载目录。

=== "AMD 64"

    执行以下命令校验安装包：

    ```sh
    echo "25ed66ad9bc619a292230851dd0d67c54a33928bd6b6aeb5926cccfb52bc7ca26b9d6c6c2eb094674613a75cfa985104dcfbf2452e844b486c08f30dff85450f  offline-community-v0.30.0-amd64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-community-v0.30.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令校验安装包：

    ```sh
    echo "90f2a8d0d06781c1f3419808dd35b163cc9989aa6cc207e3bb56805b23a0f08b3bd308de2ba7a15703589833d10d8ac239e28dad3a91cf59f8694e6df456db59  offline-community-v0.30.0-arm64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-community-v0.30.0-arm64.tar: OK
    ```

## 安装

成功校验离线包之后，

=== "AMD 64"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-community-v0.30.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-community-v0.30.0-arm64.tar
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
