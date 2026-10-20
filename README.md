# HeroSizy Scoop Bucket

**English** | [简体中文](README.zh-CN.md)

A [Scoop](https://scoop.sh) bucket for [MyTwig](https://github.com/HeroSizy/mytwig-releases), a native Git client for macOS, Windows and Linux.

## Install

```powershell
scoop bucket add herosizy https://github.com/HeroSizy/scoop-bucket
scoop install herosizy/mytwig
```

You must have:

- 64-bit Windows 10 or 11, x64 or ARM64. Scoop selects the correct build.
- [Git](https://git-scm.com) 2.32 or later (`scoop install git`).

Scoop installs MyTwig from the portable archive of the release into the Scoop folder, `~\scoop\apps\mytwig`. It also adds a Start menu shortcut, **MyTwig**. Scoop does not run anything as administrator.

> **NOTE:** MyTwig does not have a code signature yet. Thus, Microsoft Defender SmartScreen can show a warning the first time that you open MyTwig.

If SmartScreen shows a warning, do these steps:

1. Click **More info**.
2. Click **Run anyway**.

## Update

```powershell
scoop update mytwig
```

The updater of MyTwig (**Settings → General → Updates**) also works in a Scoop install. But then Scoop continues to show the version that it installed. Thus, we recommend `scoop update`. You can stop the background checks of the app in Settings.

## Uninstall

```powershell
scoop uninstall mytwig
```

Your settings stay in `%APPDATA%\MyTwig`. The cache and the logs stay in `%LOCALAPPDATA%\MyTwig`. To remove them too, delete these folders.

> **NOTE:** The tokens that MyTwig keeps in Windows Credential Manager also stay. To remove them, click **Sign Out** in **Settings → Accounts** before you uninstall.

## Problems

Report problems with MyTwig, or with this manifest, in [MyTwig's issues](https://github.com/HeroSizy/mytwig-releases/issues). After each release, an automatic process updates the manifest in this repository.
