# Harness Desktop Scoop bucket

[![Tests](https://github.com/baiyuscc13724-max/scoop-harness-desktop/actions/workflows/ci.yml/badge.svg)](https://github.com/baiyuscc13724-max/scoop-harness-desktop/actions/workflows/ci.yml)
[![Excavator](https://github.com/baiyuscc13724-max/scoop-harness-desktop/actions/workflows/excavator.yml/badge.svg)](https://github.com/baiyuscc13724-max/scoop-harness-desktop/actions/workflows/excavator.yml)

Harness Desktop 的 Scoop 软件源。它安装项目发布页中的 Windows x64 便携版，并通过公开的 `SHA256SUMS.txt` 校验下载文件。

## 安装

```powershell
scoop bucket add harness-desktop https://github.com/baiyuscc13724-max/scoop-harness-desktop
scoop install harness-desktop/harness-desktop
```
升级和卸载：

```powershell
scoop update harness-desktop
scoop uninstall harness-desktop
```

项目主页与图形安装包：<https://github.com/baiyuscc13724-max/deepseek-harness-desktop>

## English

This bucket installs the Windows x64 portable release of Harness Desktop and verifies it against the SHA-256 checksum published with the same GitHub Release.

```powershell
scoop bucket add harness-desktop https://github.com/baiyuscc13724-max/scoop-harness-desktop
scoop install harness-desktop/harness-desktop
```
