# iStore OS 固件 | 定制的麻烦自行 fork 修改

[![iStore使用文档](https://img.shields.io/badge/使用文档-iStore%20OS-brightgreen?style=flat-square)](https://doc.linkease.com/zh/guide/istoreos) [![最新固件下载](https://img.shields.io/github/v/release/draco-china/istoreos-rk35xx-actions?style=flat-square&label=最新固件下载)](../../releases/latest)

![支持设备](https://img.shields.io/badge/支持设备:-blueviolet.svg?style=flat-square) 
<!-- ![H88K](https://img.shields.io/badge/H88K-blue.svg?style=flat-square) ![H66K](https://img.shields.io/badge/H66K-blue.svg?style=flat-square) ![H68K](https://img.shields.io/badge/H68K-blue.svg?style=flat-square) ![H69K](https://img.shields.io/badge/H69K-blue.svg?style=flat-square) ![R5S](https://img.shields.io/badge/R5S-blue.svg?style=flat-square) ![R6S](https://img.shields.io/badge/R6S-blue.svg?style=flat-square) ![R66S](https://img.shields.io/badge/R66S-blue.svg?style=flat-square) ![R68S](https://img.shields.io/badge/R68S-blue.svg?style=flat-square) ![STATION P2](https://img.shields.io/badge/STATION%20P2-blue.svg?style=flat-square) ![T68M](https://img.shields.io/badge/T68M-blue.svg?style=flat-square) -->

## 默认配置

- IP: `http://192.168.100.1` or `http://iStoreOS.lan/`
- 用户名: `root`
- 密码: `password`
- 如果设备只有一个网口，则此网口就是 `LAN` , 如果大于一个网口, 默认第一个网口是 `WAN` 口, 其它都是 `LAN`
- 如果要修改 `LAN` 口 `IP` , 首页有个内网设置，或者用命令 `quickstart` 修改
- 北京时间每天 `0:00` 定时编译, `Release` 中只保留不同架构的最新版本
- 历史版本在 `Actions` 中选择一个已经运行完成且成功的 `workflow` 在页面底部可以看到 `Artifacts`, `Artifacts` 需要登录 Github 才能下载

## 支持架构

### RK35xx 架构

| 设备           | 包名称                                                                   |
| -------------- | ------------------------------------------------------------------------ |
| Radxa ROCK 3C | istoreos-rockchip-rk35xx-radxa-rock-3c-squashfs-combined.img.gz       |


### x86 架构

| 启动       | 包名称                                              |
| ---------- | --------------------------------------------------- |
| X86-64     | istoreos-x86-64-generic-squashfs-combined.img.gz    |
| X86-64-EFI | storeos-x86-64-generic-squashfs-combined-efi.img.gz |

## 鸣谢

- [istoreos](https://github.com/istoreos/istoreos)
- [P3TERX/Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)
- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean&#39;s OpenWrt](https://github.com/coolsnowwolf/lede)
- [tmate](https://github.com/tmate-io/tmate)
- [mxschmitt/action-tmate](https://github.com/mxschmitt/action-tmate)
- [csexton/debugger-action](https://github.com/csexton/debugger-action)
- [Cowtransfer](https://cowtransfer.com)
- [WeTransfer](https://wetransfer.com/)
- [Mikubill/transfer](https://github.com/Mikubill/transfer)
- [softprops/action-gh-release](https://github.com/softprops/action-gh-release)
- [ActionsRML/delete-workflow-runs](https://github.com/ActionsRML/delete-workflow-runs)
- [dev-drprasad/delete-older-releases](https://github.com/dev-drprasad/delete-older-releases)
- [peter-evans/repository-dispatch](https://github.com/peter-evans/repository-dispatch)
