 [中文](https://p3terx.com/archives/build-openwrt-with-github-actions.html)

# Actions-OpenWrt

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/P3TERX/Actions-OpenWrt/blob/master/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Forks&logo=github)

## Usage

- 使用[JiaY-shi/openwrt](https://github.com/JiaY-shi/openwrt.git) [immortalwrt](https://github.com/immortalwrt/immortalwrt.git)源码
- 支持GL-inet AXT-1800, GL-inet MT-3000机型(192.168.8.1)，x86(192.168.100.1)，默认无密码。
- MT3000 23.05.2 内置Tailscale，风扇控制，WIFI计划，微信推送，释放内存，固定内核魔法值，可直接安装immortalwrt软件源内的内核软件包
- AXT1800 内置Tailscale，风扇控制，openclash，微信推送，mosdns，WIFI计划，kms激活，ttyd，quickstart，释放内存，完全支持有线以及无线QCA-NSS特性，需要关闭软件流量分载
- x86 内置Wireguard，openclash，微信推送，mosdns，kms激活，ttyd，释放内存,socat,固定内核魔法值，可直接安装immortalwrt软件源内的内核软件包
![image](https://github.com/m0eak/Openwrt_Builder/assets/50049180/9671d793-51f8-484c-bae7-9567e3fd5f9c)



## Credits

- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [JiaY-shi/openwrt](https://github.com/JiaY-shi/openwrt.git)
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

## License

[MIT](https://github.com/P3TERX/Actions-OpenWrt/blob/main/LICENSE) © [**P3TERX**](https://p3terx.com)
