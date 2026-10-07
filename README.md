# RAMOS

可靠性分析与维修优化系统（Reliability Analysis and Maintenance Optimization System）。

本仓库仅用于发布 Windows x64 程序、更新包和版本说明，不包含程序源码。软件需要有效授权；下载程序不代表取得使用授权。

## 下载与运行

在 [最新版本](https://github.com/L1Zefeng/RAMOS-Releases/releases/latest) 中下载 `RAMOS-Windows-x64.zip`，完整解压到当前用户可写的本地文件夹，然后运行 `RAMOS.exe`。无需安装 Python 或 Conda。请勿只复制 EXE，也不要直接在压缩包中运行。

首次运行输入提供者发放的激活码。之后每次打开联网验证，验证通过后运行中不再自动复查。软件计算在本机进行。

## 更新

从 2026.10.07.5 开始，软件启动后会检查新版本，也可在“关于 RAMOS”中检查。确认后下载，保存模型并从托盘退出，下次打开时安装。更新不会覆盖计算记录或本机授权。无法访问 GitHub 时，可以继续使用已通过授权验证的当前版本。

较早版本没有更新器，需要先换用一次完整包。`update-catalog.json`、`update-catalog.sig` 及带版本号的更新负载用于软件自动更新，不是可单独运行的程序。

## 说明

软件使用说明见包内 `RAMOS使用手册.docx` 和 `README.txt`。吉祥物默认关闭，可在“关于 RAMOS”中手动开启。

安装包有应用内完整性签名，但尚无 Windows Authenticode 代码签名证书。请仅从本仓库或提供者指定渠道下载。不要在公开 Issue 中提交激活码、机器标识、私人模型或计算数据。
