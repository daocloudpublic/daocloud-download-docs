---
hide:
  - toc
---

# 大模型服务平台

本页可下载大模型服务平台模块各版本的离线安装包。

## 下载

| 版本 | 架构 | 文件大小 | 安装包 | 校验文件 | 更新日期 |
| ---- | --- | ------ | ------ | ------ | ------- |
| [v0.10-dev-73956bb2](../../hydra/intro/release-notes.md) | ARM 64 | 653.18MB | [:arrow_down: hydra_v0.10-dev-73956bb2_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/hydra_v0.10-dev-73956bb2_arm64.tar) | [:arrow_down: hydra_v0.10-dev-73956bb2_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/hydra_v0.10-dev-73956bb2_arm64_checksum.sha512sum) | 2025-09-12 |
| [v0.10-dev-73956bb2](../../hydra/intro/release-notes.md) | AMD 64 | 678.40MB | [:arrow_down: hydra_v0.10-dev-73956bb2_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/hydra_v0.10-dev-73956bb2_amd64.tar) | [:arrow_down: hydra_v0.10-dev-73956bb2_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/hydra_v0.10-dev-73956bb2_amd64_checksum.sha512sum) | 2025-09-12 |
| [v0.9.0](../../hydra/intro/release-notes.md) | <font color="green">ARM 64</font> | 653 MB | [:arrow_down: hydra_v0.9.0_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/hydra_v0.9.0_arm64.tar) | [:arrow_down: hydra_v0.9.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/hydra_v0.9.0_arm64_checksum.sha512sum) | 2025-09-01 |
| [v0.9.0](../../hydra/intro/release-notes.md) | AMD 64 | 678 MB | [:arrow_down: hydra_v0.9.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/hydra_v0.9.0_amd64.tar) | [:arrow_down: hydra_v0.9.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/hydra_v0.9.0_amd64_checksum.sha512sum) | 2025-09-01 |

## 校验

在下载离线安装包和校验文件的目录，以 `v0.9.0_amd64` 为例，执行以下命令校验完整性：

```sh
echo "$(cat hydra_v0.9.0_amd64_checksum.sha512sum)" | sha512sum -c
```

校验成功后打印结果类似于：

```none
hydra_v0.9.0_amd64.tar: ok
```

## 安装

如果是初次安装，请[申请免费体验](../../dce/license0.md)或联系我们授权：电邮 info@daocloud.io 或致电 400 002 6898。
如果有任何许可密钥相关的问题，请联系 DaoCloud 交付团队。
