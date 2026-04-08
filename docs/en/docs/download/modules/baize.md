---
MTPE: windsonsea
date: 2026-04-08
hide:
  - toc
---

# AI Lab

On this page, you can download offline packages for various versions of the baize module, including Helm Chart and images for the baize component, as well as Helm Chart and images for the baize-agent component.

## Download

| Version | Architecture | Size | Package | Checksum | Date |
|---------|--------------|------|-----|--------------|------|
| [v0.25.1](../../baize/intro/release-notes.md) | <font color=green>ARM 64</font> | 10 GB | [:arrow_down: baize_v0.25.1_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/baize_v0.25.1_arm64.tar) | [:arrow_down: baize_v0.25.1_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/baize_v0.25.1_arm64_checksum.sha512sum) | 2026-04-08 |
| [v0.25.1](../../baize/intro/release-notes.md) | AMD 64 | 10 GB | [:arrow_down: baize_v0.25.1_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/baize_v0.25.1_amd64.tar) | [:arrow_down: baize_v0.25.1_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/baize_v0.25.1_amd64_checksum.sha512sum) | 2026-04-08 |
| [v0.25.1](../../baize/intro/release-notes.md) | <font color=green>ARM 64</font> | 1.58 GB | [:arrow_down: baize_v0.25.1_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/baize_v0.25.1_arm64.tar) | [:arrow_down: baize_v0.25.1_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/baize_v0.25.1_arm64_checksum.sha512sum) | 2026-04-08 |
| [v0.25.1](../../baize/intro/release-notes.md) | AMD 64 | 1.65 GB | [:arrow_down: baize_v0.25.1_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/baize_v0.25.1_amd64.tar) | [:arrow_down: baize_v0.25.1_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/baize_v0.25.1_amd64_checksum.sha512sum) | 2026-04-08 |

## Verification

In the directory where you downloaded the offline package and checksum file, run the following command to verify the integrity:

```sh
echo "$(cat baize_v0.25.1_amd64_checksum.sha512sum)" | sha512sum -c
```

If the checksum is successful, the command will print a result similar to:

```none
baize_v0.25.1_amd64.tar: ok
```

## Installation

Refer to [Offline Upgrade AI Lab](../../baize/quickstart/baize.md#offline-upgrade)。

If this is your first installation, please apply for a free trial or contact us for authorization: email info@daocloud.io or call 400 002 6898.
If you have any questions regarding the license key, please contact the DaoCloud delivery team.
