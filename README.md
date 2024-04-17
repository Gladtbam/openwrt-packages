## 适用于openwrt 19.07 及以上的分支.
## 所有插件都为网上收集的开源插件,感谢作者们的付出.

# Fork from [kiddin9/openwrt-packages](https://github.com/kiddin9/openwrt-packages.git)

# 以下软件与 [OpenWrt 官方](https://git.openwrt.org/) [packages](https://git.openwrt.org/feed/packages) 冲突，故删除，需要请使用原 Repo

` openssl opkg mbedtls firewall4 dnsmasq nftables firewall libnftnl netifd base-files wireless-regdb ppp`  
#

|包名|功能|
|:--:|:--:|
|luci-app-3ginfo|调制解调器状态可视化|
|luci-app-3proxy||
|luci-app-accesscontrol|访问时间控制|
|luci-app-adbyby-plus|广告屏蔽大师Plus|
|luci-app-adguardhome|AdGuard home广告过滤|
|luci-app-advanced|系统高级设置|
|luci-app-airconnect|iOS隔空播放|
|luci-app-airplay2|Apple AirPlay2 AirPlay无损音乐推流(安卓+IOS)|
|luci-app-airwhu|锐捷 802.1X 客户端 WebUI|
|luci-app-aliddns|阿里DDNS客户端（推荐ddns）|
|luci-app-alist||
|luci-app-aliyundrive-fuse|阿里云盘FUSE磁盘挂载|
|luci-app-aliyundrive-webdav|阿里云盘 WebDAV 服务|
|luci-app-amule|aMule下载工具|
|luci-app-apinger||
|luci-app-argon-config|Argon主题配置插件|
|luci-app-arpbind|IP/MAC绑定|
|luci-app-atinout||
|luci-app-autoipsetadder||
|luci-app-autoreboot|计划重启|
|luci-app-autorepeater||
|luci-app-autotimeset||
luci-app-baidupcs-web|百度网盘管理|
luci-app-beardropper||
|luci-app-bridge||
|luci-app-brook-server||
|luci-app-bypass||
|luci-app-cd8021x||
|luci-app-cellled||
|luci-app-cifs-mount|CIFS/SMB挂载设置|
|luci-app-clash|Clash|
|luci-app-cloudflarespeedtest||
|luci-app-cloudreve||
|luci-app-control-speedlimit||
|luci-app-control-timewol||
|luci-app-control-webrestriction||
|luci-app-control-weburl||
|luci-app-cpulimit||
|luci-app-cupsd||
|luci-app-ddns-go||
|luci-app-ddnsto||
|luci-app-diskman|磁盘管理工具|
|luci-app-dnscrypt-proxy2|DNSCrypt 设置 DNS, 解决DNS污染|
|luci-app-dnsfilter|DNSFilter基于DNS的广告过滤|
|luci-app-dnsforwarder|DNSForwarder防DNS污染|
|luci-app-dnsmasq-ipset||
|luci-app-docker|Docker容器|
|luci-app-dogcom||
|luci-app-e2guardian|Web内容过滤器|
|luci-app-easymesh|简单MESH(可有线+无线回程)|
|luci-app-easyupdate||
|luci-app-eqos|基于IP地址限速|
|luci-app-fileassistant|文件管理助手|
|luci-app-filebrowser||
|luci-app-filetransfer|文件传输|
|luci-app-fullconenat||
|luci-app-go-aliyundrive-webdav|阿里云盘webdav协议|
|luci-app-gost|隐蔽的https代理|
|luci-app-gowebdav||
|luci-app-gpoint||
|luci-app-gpsysupgrade||
|luci-app-guest-wifi||
|luci-app-haproxy-tcp||
|luci-app-homebox||
|luci-app-homeproxy||
|luci-app-iperf||
|luci-app-ipsec-server|服务器 IPSec|
|luci-app-ipsec-vpnd||
|luci-app-ipsec-vpnserver-manyusers||
|luci-app-iptvhelper||
|luci-app-irqbalance||
|luci-app-kcptun||
|luci-app-keepalived||
|luci-app-kodexplorer|KOD可道云私人网盘 (与vnStat冲突)|
|luci-app-log||
|luci-app-lorawan-basicstation||
|luci-app-lucky||
|luci-app-mail||
|luci-app-mentohust||
|luci-app-microsocks||
|luci-app-minieap||
|luci-app-mmconfig||
|luci-app-modemband||
|luci-app-modeminfo||
|luci-app-mosdns|MosDNS转发器|
|luci-app-msd_lite||
|luci-app-music-remote-center|PCHiFi 数字转盘遥控|
|luci-app-mwan3helper|MWAN3分流助手|
|luci-app-mwol||
|luci-app-mymind||
|luci-app-n2n|N2N内网穿透|
|luci-app-naiveproxy||
|luci-app-netdata|Netdata实时监控（图形化）|
|luci-app-netspeedtest||
|luci-app-nezha-agent||
|luci-app-nfs|NFS网络共享|
|luci-app-nginx-manager||
|luci-app-nginx-pingos||
|luci-app-ngrokc|Ngrok 内网穿透|
|luci-app-njitclient||
|luci-app-nps|内网穿透nps|
|luci-app-oaf||
|luci-app-onliner||
|luci-app-openclash|Clash|
|luci-app-openvpn-server||
|luci-app-oscam|OSCAM服务器|
|luci-app-packet-capture||
|luci-app-partexp||
|luci-app-passwall||
|luci-app-passwall2||
|luci-app-pgyvpn|蒲公英VPN|
|luci-app-phtunnel|花生壳PHTunnel内网穿透|
|luci-app-pikpak-webdav||
|luci-app-pingcontrol||
|luci-app-poweroff||
|luci-app-pppoe-relay|PPPoE NAT穿透 点对点协议（PPP）|
|luci-app-pppoe-server||
|luci-app-pptp-server|服务器pptp|
|luci-app-pptpd||
|luci-app-ps3netsrv|PS3 NET服务器(用于加载蓝光/游戏ISO/PKG)|
|luci-app-pushbot|全能推送(钉钉推送,企业微信推送,Bark,PushPlus推送)|
|luci-app-qbittorrent|BT下载工具(qBittorrent)|
|luci-app-qbittorrent-simple|BT下载工具(qBittorrent)简化版|
|luci-app-ramfree|释放内存|
|luci-app-rclone||
|luci-app-rtorrent||
|luci-app-scutclient||
|luci-app-serverchan|微信/Telegram 推送|
|luci-app-shadowsocks|SS|
|luci-app-shortcutmenu||
|luci-app-sms-tool||
|luci-app-smstools3||
|luci-app-socat|Socat多功能的网络工具(端口转发)|
|luci-app-softethervpn|SoftEther VPN服务器  NAT穿透|
|luci-app-softethervpn5||
|luci-app-speederv2||
|luci-app-speedtest-web||
|luci-app-ssr-libev-server||
|luci-app-ssr-mudb-server||
|luci-app-ssr-plus||
|luci-app-ssrserver-python|SSR Python 服务器|
|luci-app-store||
|luci-app-supervisord||
|luci-app-switch-lan-play||
|luci-app-syncdial|多拨虚拟网卡 (原macvlan)|
|luci-app-syncthing||
|luci-app-sysuh3c||
|luci-app-tcpdump||
|luci-app-telegrambot||
|luci-app-tencentcloud-cos||
|luci-app-tencentcloud-cos||
|luci-app-tencentddns||
|luci-app-timecontrol||
|luci-app-timewol||
|luci-app-trojan-server||
|luci-app-ttnode||
|luci-app-turboacc|Turbo ACC 网络加速(支持 Fast Path 或者 硬件 NAT)|
|luci-app-udp2raw||
|luci-app-unblockmusic|解锁网易云灰色歌曲3合1新版本|
|luci-app-unblockneteasemusic-go|解锁网易云灰色歌曲|
|luci-app-unishare||
|luci-app-usb-printer|USB 打印服务器|
|luci-app-usb3disable||
|luci-app-uugamebooster|UU网游加速器|
|luci-app-v2ray-server||
|luci-app-v2raya||
|luci-app-verysync|微力同步|
|luci-app-vlmcsd|KMS服务器|
|luci-app-vsftpd||
|luci-app-vssr||
|luci-app-webadmin|Web管理页面|
|luci-app-webdav|WebDAV|
|luci-app-webrestriction||
|luci-app-weburl||
|luci-app-wifidog||
|luci-app-wizard||
|luci-app-wolplus|WOL网络唤醒 Plus|
|luci-app-wrtbwmon|实时流量监测|
|luci-app-xfrpc||
|luci-app-xlnetacc|迅雷快鸟|
|luci-app-zerotier|ZeroTier内网穿透|
