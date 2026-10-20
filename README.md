# HeroSizy Scoop Bucket

**English** | [简体中文](README.zh-CN.md)

A [Scoop](https://scoop.sh) bucket for [MyTwig](https://github.com/HeroSizy/mytwig-releases), a native Git client for macOS, Windows and Linux.

## Install

```powershell
scoop bucket add herosizy https://github.com/HeroSizy/scoop-bucket
scoop install herosizy/mytwig
```

It needs 64-bit Windows 10 or 11, x64 or ARM64 (Scoop picks the right build), and [Git](https://git-scm.com) 2.32 or later (`scoop install git`). MyTwig is installed in Scoop's folder, `~\scoop\apps\mytwig`, from the release's portable archive, with a Start menu shortcut, **MyTwig**. Nothing is run as administrator.

MyTwig isn't code-signed yet. If Microsoft Defender SmartScreen warns you the first time you open it, click **More info**, then **Run anyway**.

## Update

```powershell
scoop update mytwig
```

MyTwig's own updater (**Settings → General → Updates**) works in a Scoop install too, but Scoop then keeps listing the version it installed. Prefer `scoop update`, and you can turn the app's background checks off in Settings.

## Uninstall

```powershell
scoop uninstall mytwig
```

Your settings stay in `%APPDATA%\MyTwig`, and the cache and logs in `%LOCALAPPDATA%\MyTwig`; delete those folders to remove them too. Tokens MyTwig saved stay in Windows Credential Manager; sign out in **Settings → Accounts** first to remove them.

## Problems

Report problems with MyTwig, or with this manifest, in [MyTwig's issues](https://github.com/HeroSizy/mytwig-releases/issues). The manifest in this repository is updated automatically after each release.
