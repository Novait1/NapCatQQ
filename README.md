# NapCatQQ v4.18.42 归档镜像

上游 [`NapNeko/NapCatQQ`](https://github.com/NapNeko/NapCatQQ) 已于 2026-11 停止维护并清空仓库
（README 只剩 “Ending”，release 全部 404），官方安装器 `napcat-linux-installer` 也一起下线。

这里保留 [qqbot-oneclick](https://github.com/Novait1) v15 使用的 **NapCat v4.18.42 Linux Shell** 包，
方便国内网络下载。原始归档来源：[`XingYunStar/NapCatQQ`](https://github.com/XingYunStar/NapCatQQ/releases/tag/v4.18.42)。

## 下载

- [`NapCat.Shell.zip`](https://github.com/Novait1/NapCatQQ/releases/download/v4.18.42/NapCat.Shell.zip) — Linux Shell 版
- [`napcat-v4.18.42-linux-arm64-mirror.zip`](https://github.com/Novait1/NapCatQQ/releases/download/v4.18.42/napcat-v4.18.42-linux-arm64-mirror.zip) — 完整镜像包（含注入库、启动器、校验和）

## 用法（qqbot-oneclick v15）

安装时指定镜像直链：

```bash
bash install.sh --nap-zip https://github.com/Novait1/NapCatQQ/releases/download/v4.18.42/NapCat.Shell.zip
```

或者把 `NapCat.Shell.zip` 放到容器 `/root/qq-napcat/` 再重跑安装。
包会对 `NapCat.Shell.zip` 做 sha256 校验：`02e5ff0f79916c1e04c81c1b4590056406fb4293f1f1300c955e71fd08b2829d`。

## 校验和

见 Release 里的 `SHA256SUMS.txt`。

## 注意

- 这是第三方归档，不是官方发布。
- NapCat 使用自定义许可证，**禁止商业用途**；它是因腾讯律师函下架的项目，上游不再修复。
- 使用非官方客户端登录个人号可能有封号风险，请使用小号并自行评估。
