# HeroSizy Scoop Bucket

[English](README.md) | **简体中文**

[MyTwig](https://github.com/HeroSizy/mytwig-releases)（适用于 macOS、Windows 和 Linux 的原生 Git 客户端）的 [Scoop](https://scoop.sh) bucket。

## 安装

```powershell
scoop bucket add herosizy https://github.com/HeroSizy/scoop-bucket
scoop install herosizy/mytwig
```

你必须有：

- 64 位 Windows 10 或 11，x64 或 ARM64。Scoop 会选择对应的版本。
- [Git](https://git-scm.com) 2.32 或更高版本（`scoop install git`）。

Scoop 从发布的便携压缩包把 MyTwig 安装到 Scoop 的目录 `~\scoop\apps\mytwig`。它还会添加开始菜单快捷方式 **MyTwig**。Scoop 不以管理员身份运行任何程序。

> **注意：** MyTwig 目前没有代码签名。因此首次打开 MyTwig 时，Microsoft Defender SmartScreen 可能显示警告。

如果 SmartScreen 显示警告，请执行以下步骤：

1. 点按 **更多信息**。
2. 点按 **仍要运行**。

## 更新

```powershell
scoop update mytwig
```

MyTwig 自带的更新（**设置 → 通用 → 更新**）在 Scoop 安装中同样可用。但之后 Scoop 显示的仍是它安装的版本。因此我们推荐使用 `scoop update`。你可以在设置中关闭应用的后台检查。

## 卸载

```powershell
scoop uninstall mytwig
```

你的设置保留在 `%APPDATA%\MyTwig`。缓存和日志保留在 `%LOCALAPPDATA%\MyTwig`。要一并删除，请删除这些文件夹。

> **注意：** MyTwig 保存在 Windows 凭据管理器中的令牌也会保留。要删除它们，请在卸载前到 **设置 → 账户** 中点按 **退出登录**。

## 问题反馈

请把 MyTwig 或此清单的问题提交到 [MyTwig 的 Issues](https://github.com/HeroSizy/mytwig-releases/issues)。每次发布后，自动流程会更新本仓库中的清单。
