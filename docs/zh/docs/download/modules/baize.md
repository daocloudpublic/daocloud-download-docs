---
hide:
  - toc
---

# AI Lab

本页可下载 AI Lab 模块各版本的离线安装包，其中包括：

- AI Lab 的 Helm Chart 和镜像。
- baize-agent 的 Helm Chart 和镜像。

## 下载

| 版本 | 架构 | 文件大小 | 安装包 | 校验文件 | 更新日期 |
|-----| ---- | ----- |--------| ------- | ------ |
| [v0.25.1](../../baize/intro/release-notes.md) | <font color=green>ARM 64</font> | 1.58 GB | [:arrow_down: baize_v0.25.1_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/baize_v0.25.1_arm64.tar) | [:arrow_down: baize_v0.25.1_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/baize_v0.25.1_arm64_checksum.sha512sum) | 2026-04-08 |
| [v0.25.1](../../baize/intro/release-notes.md) | AMD 64 | 1.65 GB | [:arrow_down: baize_v0.25.1_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/baize_v0.25.1_amd64.tar) | [:arrow_down: baize_v0.25.1_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/baize_v0.25.1_amd64_checksum.sha512sum) | 2026-04-08 |
| [v0.25.1](../../baize/intro/release-notes.md) | <font color=green>ARM 64</font> | 1.58 GB | [:arrow_down: baize_v0.25.1_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/baize_v0.25.1_arm64.tar) | [:arrow_down: baize_v0.25.1_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/baize_v0.25.1_arm64_checksum.sha512sum) | 2026-04-08 |
| [v0.25.1](../../baize/intro/release-notes.md) | AMD 64 | 1.65 GB | [:arrow_down: baize_v0.25.1_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/baize_v0.25.1_amd64.tar) | [:arrow_down: baize_v0.25.1_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/baize_v0.25.1_amd64_checksum.sha512sum) | 2026-04-08 |

## 校验

在下载离线安装包和校验文件的目录，执行以下命令校验完整性：

```sh
echo "$(cat baize_v0.25.1_amd64_checksum.sha512sum)" | sha512sum -c
```

校验成功后打印结果类似于：

```none
baize_v0.25.1_amd64.tar: ok
```

## 安装

参阅 [AI Lab 离线升级步骤](../../baize/quickstart/baize.md#_11)。

如果是初次安装，请[申请免费体验](../../dce/license0.md)或联系我们授权：电邮 info@daocloud.io 或致电 400 002 6898。
如果有任何许可密钥相关的问题，请联系 DaoCloud 交付团队。
