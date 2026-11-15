# qqbot-runtime

[qqbot-oneclick](https://github.com/Novait1) 安装包使用的运行时文件镜像，方便国内网络下载。

这里保留 v15 需要的 Linux Shell 运行时包。原始归档来源：
[`XingYunStar/NapCatQQ`](https://github.com/XingYunStar/NapCatQQ/releases/tag/v4.18.42)。

## 下载

- [`NapCat.Shell.zip`](https://github.com/Novait1/qqbot-runtime/releases/download/v4.18.42/NapCat.Shell.zip) — Linux Shell 版
- [`napcat-v4.18.42-linux-arm64-mirror.zip`](https://github.com/Novait1/qqbot-runtime/releases/download/v4.18.42/napcat-v4.18.42-linux-arm64-mirror.zip) — 完整镜像包（含注入库、启动器、校验和）

## 用法

安装时指定镜像直链：

```bash
bash install.sh --nap-zip https://github.com/Novait1/qqbot-runtime/releases/download/v4.18.42/NapCat.Shell.zip
```

或者把 `NapCat.Shell.zip` 放到容器 `/root/qq-napcat/` 再重跑安装。
包会对 `NapCat.Shell.zip` 做 sha256 校验：`02e5ff0f79916c1e04c81c1b4590056406fb4293f1f1300c955e71fd08b2829d`。

## 校验和

见 Release 里的 `SHA256SUMS.txt`。

## 注意

仓库从 `Novait1/NapCatQQ` 改名为 `Novait1/qqbot-runtime`；旧链接由 GitHub 自动重定向。
