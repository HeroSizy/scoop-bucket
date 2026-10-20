# HeroSizy Scoop Bucket

[English](README.md) | **简体中文**

[MyTwig](https://github.com/HeroSizy/mytwig-releases)（适用于 macOS、Windows 和 Linux 的原生 Git 客户端）的 [Scoop](https://scoop.sh) bucket。

## 安装

```powershell
scoop bucket add herosizy https://github.com/HeroSizy/scoop-bucket
scoop install herosizy/mytwig
```

需要 64 位 Windows 10 或 11（x64 或 ARM64，Scoop 会自动选择对应版本），以及 [Git](https://git-scm.com) 2.32 或更高版本（`scoop install git`）。MyTwig 会从发布的便携压缩包安装到 Scoop 的目录 `~\scoop\apps\mytwig`，并添加开始菜单快捷方式 **MyTwig**，全程不需要管理员权限。

MyTwig 目前没有代码签名。如果首次打开时 Microsoft Defender SmartScreen 弹出警告，请点按 **更多信息**，再点按 **仍要运行**。

## 更新

```powershell
scoop update mytwig
```

MyTwig 自带的更新（**设置 → 通用 → 更新**）在 Scoop 安装中同样可用，但之后 Scoop 显示的仍是它安装的版本。建议使用 `scoop update`，也可以在设置中关闭应用的后台检查。

## 卸载

```powershell
scoop uninstall mytwig
```

设置保留在 `%APPDATA%\MyTwig`，缓存和日志保留在 `%LOCALAPPDATA%\MyTwig`；如需一并删除，请手动删除这些文件夹。MyTwig 保存的令牌保留在 Windows 凭据管理器中；如需删除，请先在 **设置 → 账户** 中退出登录。

## 问题反馈

MyTwig 或此清单的问题请提交到 [MyTwig 的 Issues](https://github.com/HeroSizy/mytwig-releases/issues)。本仓库中的清单会在每次发布后自动更新。
