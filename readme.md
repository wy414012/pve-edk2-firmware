<img src="https://www.proxmox.com/images/proxmox/Proxmox_logo_standard_hex_400px.png" width="200" height="48"/>

[![CI](https://github.com/wy414012/pve-edk2-firmware/actions/workflows/main.yml/badge.svg?branch=master)](https://github.com/wy414012/pve-edk2-firmware/actions/workflows/main.yml)
-----

pve-edk2-firmware

- 克隆的`pve-edk2-firmware`库

- 用于构建`pve-edk2-firmware.deb`包

### 其中分支说明 ：

- master 构建`edk2-stable`同步使用PVE的提交
- edk2-test 构建`edk2-latest`最新提交，只管将PVE提供的补丁向`latest`移植，保证成功构建，该分支版本号使用edk2的版本号来作为构建的版本号。
