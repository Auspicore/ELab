# Install ELab

[简体中文](#zh-cn) · [Download status](download.md)

ELab has no public installation packages yet. Use the installation steps and supported system versions in the notes for the release you download. Back up existing projects before updating.

## Check a download

Download the SHA-256 checksum file from the same release as your package. Enter the command for your system in a terminal in the download folder, substituting the application's actual filename. Compare the result with the line for that exact filename in the checksum file before opening the download.

| Platform | Command |
| --- | --- |
| Windows (PowerShell) | `Get-FileHash -Algorithm SHA256 -LiteralPath 'PACKAGE_FILENAME'` |
| Linux | `sha256sum -- 'PACKAGE_FILENAME'` |
| macOS | `shasum -a 256 'PACKAGE_FILENAME'` |

If the values differ, discard the download and obtain a fresh copy from the same release. For macOS, review the signing, notarization, and first-launch information in the release notes before opening the app.

[Run your first experiment](quick-start.md)

<a name="zh-cn"></a>

## 安装 ELab

[下载状态](download.md#zh-cn)

ELab 尚未开放安装包下载。下载后，请按对应发行说明查看适用系统版本和安装步骤。更新前请备份已有工程。

### 校验下载文件

从安装包所属版本下载 SHA-256 校验文件。在下载文件夹打开终端，按上表选择对应操作系统的命令，并将 `PACKAGE_FILENAME` 替换为实际下载的文件名。打开软件包前，将计算结果与校验文件中同名文件的值进行比较。

若数值不同，请删除该下载文件并从同一发行页重新获取。macOS 用户请先查看该版本的签名、公证及首次启动说明。

[开始第一个实验](quick-start.md#zh-cn)
