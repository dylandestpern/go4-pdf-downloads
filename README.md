# Go4 PDF

A native PDF viewer and editor for **Windows and Linux**, by **Go4 Software**.

## Downloads

**[Download installers and release notes](https://github.com/dylandestpern/go4-pdf-downloads/releases)**

Choose the installer for your system from a release's **Assets** list:

| System (x64) | Installer | Install |
| --- | --- | --- |
| Windows 10/11 | `*-windows-x64-setup.exe` | Double-click Setup; installs for your account. |
| Ubuntu 22.04+ / Debian 12+ | `*.deb` | `sudo apt install ./go4-pdf_0.3.4_amd64.deb` |
| Fedora with glibc 2.35+ / RHEL 10 and compatible systems | `*.rpm` | `sudo dnf install ./go4-pdf-0.3.4-1.x86_64.rpm` |

Portable Windows ZIP and Linux tar.gz archives are also available. Keep their extracted files together. PDFium is included; users do not need Rust or Python. RHEL 9 and ARM systems are not supported by these builds.

## Features

- Continuous PDF scrolling, tabs, search, bookmarks, zoom, and dark/light themes.
- Fill AcroForm fields directly on PDF pages.
- Annotate, edit supported text and images, organize pages, and export documents.
- Save, undo/redo, crash recovery, and system printing.

## Updates

Starting with 0.3.4, open **Updates** in the toolbar to choose automatic downloads with an install prompt (the default), installation on close, notifications only, or manual checks. Automatic checks run daily while the app is open. You can also choose whether to include preview releases.

On Windows, installation on close runs the installer after Go4 PDF exits. On Linux, this option opens your system package installer, which may request administrator authorization. Portable copies download an archive for manual replacement.

**Upgrading from 0.3.3:** install 0.3.4 manually once to get these update features.

## Preview status

Version 0.3.4 is a development preview. The Windows installer is currently **unsigned** and Windows may show an unknown-publisher or reputation prompt. See each release for verification results and known limitations.

Close Go4 PDF before upgrading. Uninstall through Windows Settings or your Linux package manager. Installers register PDF Open with choices without changing your default PDF application.

SHA-256 checksum files accompany each release. Application and third-party license notices are included in every package.

This repository contains public downloads and release documentation; application source is maintained separately.
