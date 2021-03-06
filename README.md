# Seia-Soto/awscliv2.appimage-autobuild

> **Notice**
> The workaround about the auto-build is working on the original repository to improve and future auto built binaries will be provided on the original repository.
> Please check [simnalamburt/awscliv2.appimage](https://github.com/simnalamburt/awscliv2.appimage) for more information and future release.

This repository builds [simnalamburt/awscliv2.appimage](https://github.com/simnalamburt/awscliv2.appimage) repository automatically via GitHub Actions.
The GitHub action in this repository will try to find and build the latest aws CLI every hour.

For more information about AppImage, refer awscliv2.appimage repo.

## Installation

The following command will download the latest release of aws CLI v2 build and install.

- Via `wget`

```sh
wget https://github.com/Seia-Soto/awscliv2.appimage-autobuild/releases/latest/download/aws-x86_64.AppImage -O aws
chmod +x aws
```

- Via `curl`

```sh
curl -L https://github.com/Seia-Soto/awscliv2.appimage-autobuild/releases/latest/download/aws-x86_64.AppImage -o aws
chmod +x aws
```
