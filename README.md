# Go4 PDF

A native PDF viewer and editor for **Windows and Linux**, by **Go4 Software**.

## Downloads

**[Download installers and release notes](https://github.com/dylandestpern/go4-pdf-downloads/releases)**

Choose the installer for your system from a release's **Assets** list:

| System (x64) | Installer | Install |
| --- | --- | --- |
| Windows 10/11 | `*-windows-x64-setup.exe` | Double-click Setup; installs for your account. |
| Ubuntu 22.04+ / Debian 12+ | `*.deb` | `sudo apt install ./go4-pdf_0.3.7_amd64.deb` |
| Fedora with glibc 2.35+ / RHEL 10 and compatible systems | `*.rpm` | `sudo dnf install ./go4-pdf-0.3.7-1.x86_64.rpm` |

Portable Windows ZIP and Linux tar.gz archives are also available. Keep their extracted files together. PDFium is included; users do not need Rust or Python. RHEL 9 and ARM systems are not supported by these builds.

## Features

- Continuous PDF scrolling, tabs, search, bookmarks, zoom, and dark/light themes.
- Fill AcroForm fields directly on PDF pages; move and resize supported fields in Edit mode.
- Read and copy notes in Select mode; explicitly open editing when needed.
- Annotate, edit supported text and images, organize pages, and export documents.
- Save, undo/redo, crash recovery, and system printing.

## Application menu

Use **File / Edit / View / Help** for application commands. **Help → About Go4 PDF** shows the installed version and publisher. Left-aligned document tabs sit above the document toolbar. **Select**, **Edit**, **Highlight**, **Note**, **Add text**, **Organize** and **Export** provide common tools. Page navigation and zoom stay in the bottom bar; document settings open in docked panels.

## Updates

**To update from 0.3.4:** open **Updates**, enable **Include preview releases**, then click **Check now**. In 0.3.5 and later, use **Help → Check for updates**. Download if needed, then install when your documents are saved.

Open **Help → Update preferences** to choose automatic downloads with an install prompt (the default), installation on close, notifications only, or manual checks. Automatic checks run daily while the app is open. You can also choose whether to include preview releases.

On Windows, installation on close runs the installer after Go4 PDF exits. On Linux, this option opens your system package installer, which may request administrator authorization. Portable copies download an archive for manual replacement.

**Upgrading from 0.3.3:** install 0.3.7 manually once to get these update features.

## Preview status

Version 0.3.7 is a development preview. The Windows installer is currently **unsigned** and Windows may show an unknown-publisher or reputation prompt. See each release for verification results and known limitations.

Close Go4 PDF before upgrading. Uninstall through Windows Settings or your Linux package manager. Installers register PDF Open with choices. At startup, Go4 PDF offers to become the default reader when another app is selected. Linux changes the association only after acceptance; Windows opens Default apps for the user to select Go4 PDF.

SHA-256 checksum files accompany each release. Application and third-party license notices are included in every package.

This repository contains public downloads and release documentation; application source is maintained separately.
