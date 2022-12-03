# awesome-reconsidera-takeaway

本项目是原 [《数字极权时代生存手记》](https://reconsidera.github.io) 3.0 版懒人包的扩展，受 awesome-list、[Privacy Tools](https://www.privacytools.io)、[2047.one/g/2047/entity/Link](https://2047.one/g/2047/entity/Link)（原 2047.one/links）等项目的启发。

图例：![Open-Source Software][oss icon] = Open-source software/开源软件

目录  
- [工具](#工具)  
	- [操作系统](#操作系统)    
		- [隐私友好操作系统](#隐私友好操作系统)  
		- [隐私强化操作系统](#隐私强化操作系统)  
		- [操作系统启动盘制作工具](#操作系统启动盘制作工具)     
	- [代理工具](#代理工具)
		- [免费开源的代理工具](#免费开源的代理工具)
		- [开源翻墙代理客户端](#开源翻墙代理客户端)
		- [免费节点](#免费节点)
	- [浏览器](#浏览器)
		- [浏览器扩展](#浏览器扩展)
		- [浏览器安全性检测](#浏览器安全性检测) 
	- [匿名工具](#匿名工具)  
	- [加密工具](#加密工具)  
	- [密码管理](#密码管理)
		- [密码管理器](#密码管理器)
		- [双因素验证器](#双因素验证器)  
	- [信息备份](#信息备份)
		- [网页存档网站](#网页存档网站)
		- [网页存档辅助工具](#网页存档辅助工具) 
	- [RSS](#RSS)
		- [RSS资源导航](#RSS资源导航)  
		- [RSS阅读器](#RSS阅读器)
		- [RSS辅助工具](#RSS辅助工具)  
	- [其他工具](#其他工具)
		- [元数据清除](#元数据清除)
		- [沙盒工具](#沙盒工具)
		- [防火墙](#防火墙)
		- [网络流量分析](#网络流量分析)  
 		- [网络测速工具](#网络测速工具)  
		- [远程桌面](#远程桌面)
		- [文件同步](#文件同步)
		- [输入法](#输入法)
		- [PDF工具](#PDF工具) 
		- [电子书工具](#电子书工具)
		- [多媒体播放器](#多媒体播放器)  
		- [下载工具](#下载工具)
		- [邮箱客户端](#邮箱客户端)
		- [加密即时通讯](#加密即时通讯)
		- [视频会议](#视频会议)
	- [加密货币](#加密货币)
		- [比特币钱包](#比特币钱包)
		- [门罗币钱包](#门罗币钱包)
		- [加密货币转换工具](#加密货币转换工具)
		- [非实名制交易所清单](#非实名制交易所清单)
	- [未归类工具](#未归类工具)
- [网络资源](#网络资源)  
	- [隐私与安全](#隐私与安全)  
		- [网页代理](#网页代理)  
		- [网络封锁相关信息](#网络封锁相关信息)   
		- [密码泄露查询](#密码泄露查询)  
		- [在线病毒扫描](#在线病毒扫描)  
		- [短链接分析工具](#短链接分析工具)   
		- [加密邮箱](#加密邮箱)
		- [临时邮箱](#临时邮箱)
		- [一次性手机号](#一次性手机号)
		- [隐私强化前端](#隐私强化前端)
	- [日常办公](#日常办公)
		- [搜索引擎](#搜索引擎)
		- [文件传输](#文件传输)
		- [图床](#图床)
		- [在线剪贴板](#在线剪贴板)
		- [翻译](#翻译)
		- [地图](#地图)
		- [GitHub镜像站](#GitHub镜像站)
	- [社交媒体](#社交媒体)
	- [文化资源](#文化资源)
		- [影视资源](#影视资源)
		- [学术资源](#学术资源)
		- [被屏蔽资源镜像站](#被屏蔽资源镜像站)
	- [未归类资源](#未归类资源)	
- [信息安全参考资料](#信息安全参考资料)		
- [参考与鸣谢](#参考与鸣谢)

---

## 工具

### 操作系统

#### 隐私友好操作系统
- 桌面操作系统
	- GNU/Linux
		- [Debian](https://www.debian.org/)![Open-Source Software][oss icon]  
		- [Arch Linux](https://archlinux.org/)![Open-Source Software][oss icon]    
		- [Fedora Linux](https://getfedora.org/)![Open-Source Software][oss icon]
		- [Slackware](http://www.slackware.com/)![Open-Source Software][oss icon]    
		- …
	- BSD
		- [FreeBSD](https://www.freebsd.org/)![Open-Source Software][oss icon]  
		- …
- 移动操作系统
  - Android 替代  
    - [GrapheneOS](https://grapheneos.org/)![Open-Source Software][oss icon] – 仅支持 Google Pixel  
    - [CalyxOS](https://calyxos.org/)![Open-Source Software][oss icon] – 仅支持 Google Pixel 和少数非 Pixel 手机  
    - [LineageOS](https://www.lineageos.org/)![Open-Source Software][oss icon] – [支持设备列表](https://wiki.lineageos.org/devices/)  
- 路由器固件  
  - [OpenWrt](https://openwrt.org/)![Open-Source Software][oss icon]  

#### 隐私强化操作系统

- [Qubes OS](https://www.qubes-os.org/)![Open-Source Software][oss icon]  
- [Whonix](https://www.whonix.org/)![Open-Source Software][oss icon]   
- [Tails](https://tails.boum.org/)![Open-Source Software][oss icon]  
- [antiS](https://github.com/mdrights/LiveSlak/)![Open-Source Software][oss icon] – 针对中国环境优化；中文、粤语、藏语、维语友好；基于 Slackware Live  

#### 操作系统启动盘制作工具  
- [Etcher](https://github.com/balena-io/etcher)![Open-Source Software][oss icon] – Windows/macOS/Linux；操作系统映像烧录工具  
- [Ventoy](https://github.com/ventoy/Ventoy)![Open-Source Software][oss icon] – Windows/Linux；制作免烧录多系统 USB 启动盘
- [Rufus](https://github.com/pbatard/rufus)![Open-Source Software][oss icon] – Windows；多功能 USB 格式化实用工具

### 代理工具

#### 免费开源的代理工具
- [迷雾通](https://geph.io)![Open-Source Software][oss icon] | [GitHub 免翻墙镜像](https://github.com/geph-official/geph4-client/wiki/%E8%BF%B7%E9%9B%BE%E9%80%9A%EF%BC%88%E5%85%8D%E7%BF%BB%E5%A2%99%E9%95%9C%E5%83%8F%EF%BC%89)![Open-Source Software][oss icon] – Windows/macOS/Linux/Android/iOS  
- [nthLink](https://www.nthlink.com/)![Open-Source Software][oss icon] | [AWS 免翻墙下载链接](https://s3.us-west-1.amazonaws.com/dwo-jar-kmf-883/download.html)![Open-Source Software][oss icon] – Windows/macOS/Android/iOS  
- [Psiphon](https://psiphon.ca/zh/download.html)![Open-Source Software][oss icon] – Windows/macOS/Android/iOS

#### 开源翻墙代理客户端

- [Clash for Windows](https://github.com/Fndroid/clash_for_windows_pkg)![Open-Source Software][oss icon] – Windows/macOS/Linux
- [v2rayN](https://github.com/2dust/v2rayN)![Open-Source Software][oss icon] – Windows
- [ClashX](https://github.com/yichengchen/clashX)![Open-Source Software][oss icon]；[ClashX Pro](https://install.appcenter.ms/users/clashx/apps/clashx-pro/distribution_groups/public) – macOS  
- [v2rayNG](https://github.com/2dust/v2rayNG)![Open-Source Software][oss icon] – Android
- [Clash For Android](https://github.com/Kr328/ClashForAndroid)![Open-Source Software][oss icon] – Android  
- [SagerNet](https://github.com/SagerNet/SagerNet)![Open-Source Software][oss icon] – Android  
- [Shadowrocket](https://apps.apple.com/app/shadowrocket/id932747118) iOS；闭源付费  
- [Stash](https://apps.apple.com/app/stash/id1596063349) – iOS；闭源付费  
- [ShellClash](https://github.com/juewuy/ShellClash)![Open-Source Software][oss icon] – 路由器  
- [OpenClash](https://github.com/vernesong/OpenClash)![Open-Source Software][oss icon] – 路由器  

#### 免费节点

- [freefq/free](https://github.com/freefq/free) **免费节点有风险，非必要不推荐使用！**

### 浏览器
- [Tor Browser](https://www.torproject.org/download/)![Open-Source Software][oss icon] – Windows/macOS/Linux/Android  
- [Firefox Browser](https://www.mozilla.org/en-US/)![Open-Source Software][oss icon] – Windows/macOS/Linux/Android/iOS；警告：注意甄别【中国特供版】，墙内务必挂代理访问 Mozilla 官网下载  
- [Librewolf](https://librewolf.net/)![Open-Source Software][oss icon] – Windows/macOS/Linux; 基于 Firefox  
- [Firefox Focus](https://www.mozilla.org/en-US/firefox/browsers/mobile/focus/)![Open-Source Software][oss icon] – iOS/Android；内置广告拦截和隐私强化  
- [Bromite](https://www.bromite.org/)![Open-Source Software][oss icon] – Android; 基于 Chromium；内置广告拦截和隐私强化  

#### 浏览器扩展
- 隐私保护  
  - [uBlock Origin](https://github.com/gorhill/uBlock#ublock-origin)![Open-Source Software][oss icon] – 拦截广告  
  - [NoScript](https://noscript.net/)![Open-Source Software][oss icon] – 拦截 JavaScript 脚本  
  - [Decentraleyes](https://git.synz.io/Synzvato/decentraleyes)![Open-Source Software][oss icon] – 防止 CDN 跟踪  
  - [Cookie AutoDelete](https://github.com/Cookie-AutoDelete/Cookie-AutoDelete#installation)![Open-Source Software][oss icon] – 关闭网页后自动删除 cookies  
  - [ClearURLs](https://gitlab.com/KevinRoebert/ClearUrls/-/blob/master/README.md)![Open-Source Software][oss icon] – 自动清除链接中的追踪参数    
  - [UserAgent Switcher](https://github.com/ray-lothian/UserAgent-Switcher)![Open-Source Software][oss icon] – 模仿 user-agent  
- 隐私强化前端重定向  
  - [LibRedirect](https://libredirect.github.io/)![Open-Source Software][oss icon]    
- 视频强化  
  - [SponsorBlock for YouTube](https://sponsor.ajay.app/)![Open-Source Software][oss icon] – YouTube 去广告  
  - [Cat Catch](https://github.com/xifangczy/cat-catch)![Open-Source Software][oss icon] – 抓取网页视频，m3u8 解析下载合并工具  
- 浏览器代理  
  - [SwitchyOmega](https://github.com/FelisCatus/SwitchyOmega)![Open-Source Software][oss icon]  
- RSS 订阅源查找    
  - [RSSHub-Radar](https://github.com/DIYgod/RSSHub-Radar)![Open-Source Software][oss icon]  

#### 浏览器安全性检测  
- 检测 IP 泄露：[https://ipleak.net/](https://ipleak.net/)  
- 浏览器指纹：[https://amiunique.org/](https://amiunique.org/)  
- 检测 DNS 泄露：[https://www.dnsleaktest.com/](https://www.dnsleaktest.com/), [https://www.expressvpn.com/dns-leak-test](https://www.expressvpn.com/dns-leak-test)  
- 检测 WebRTC 泄露：[https://www.expressvpn.com/webrtc-leak-test](https://www.expressvpn.com/webrtc-leak-test)  
- 其它浏览器安全问题检测：[https://browserleaks.com/](https://browserleaks.com/)  
- 检测 Tor：[https://check.torproject.org/](https://check.torproject.org/)  
- [Cloudflare - Browsing Experience Security Check](https://www.cloudflare.com/ssl/encrypted-sni/)![Open-Source Software][oss icon] – 检测 DNS 加密 (DoH/DoT)、DNSSEC、TLS 1.3、SNI 加密 (ECH)  
- [Device Info](https://www.deviceinfo.me/)  

### 匿名工具
- [Whonix](https://www.whonix.org/)![Open-Source Software][oss icon]   
- [Tails](https://tails.boum.org/)![Open-Source Software][oss icon]  
- [Tor Browser](https://www.torproject.org/download/)![Open-Source Software][oss icon] – Windows/macOS/Linux/Android  
- [OnionShare](https://onionshare.org/)![Open-Source Software][oss icon] – Windows/macOS/Linux；匿名文件传输、洋葱网站托管、匿名聊天室  
- [I2P](https://geti2p.net/)![Open-Source Software][oss icon]  
	- [i2pd](https://github.com/PurpleI2P/i2pd)![Open-Source Software][oss icon]  

### 加密工具
- PGP
	- [GnuPG](https://gnupg.org/)![Open-Source Software][oss icon]
	- [Kleopatra](https://apps.kde.org/kleopatra/)![Open-Source Software][oss icon] – Windows/Linux  
- [VeraCrypt](https://www.veracrypt.fr/) – Windows/macOS/Linux；虚拟加密卷/磁盘加密  
- [Cryptomator](https://cryptomator.org) – Windows/macOS/Linux/Android/iOS；网盘的客户端加密工具  
- 隐写术工具
  - 零宽度字符
    - [StegCloak](https://github.com/KuroLabs/stegcloak)![Open-Source Software][oss icon]
    - [steganographr](https://github.com/neatnik/steganographr)![Open-Source Software][oss icon]
      - [实例](https://neatnik.net/steganographr)
  - 图片隐写术
    - [OpenStego](https://github.com/syvaidya/openstego)![Open-Source Software][oss icon]


### 密码管理
#### 密码管理器  
- [Bitwarden](https://bitwarden.com/)![Open-Source Software][oss icon] – Windows/macOS/Linux/Android/iOS
  - [Vaultwarden](https://github.com/dani-garcia/vaultwarden)  
- [KeePass](https://keepass.info/)![Open-Source Software][oss icon] – Windows/Mono
	- [KeePassXC](https://keepassxc.org/)![Open-Source Software][oss icon] – Windows/macOS/Linux  
 	- [KeePass2Android](https://play.google.com/store/apps/details?id=keepass2android.keepass2android)![Open-Source Software][oss icon] - Android  
  	- [Strongbox](https://itunes.apple.com/us/app/strongbox-password-safe/id897283731)![Open-Source Software][oss icon] – iOS/macOS  
#### 双因素验证器  
- [FreeOPT](https://freeotp.github.io)![Open-Source Software][oss icon] – iOS/Android  
- [Tofu](https://github.com/calleluks/Tofu)![Open-Source Software][oss icon] – iOS  
- [Aegis Authenticator](https://github.com/beemdevelopment/Aegis)![Open-Source Software][oss icon] – Android  

### 信息备份
#### 网页存档网站  
  - [https://web.archive.org/](https://web.archive.org/)  
  - [https://archive.today/](https://archive.today/)  
  - [https://ghostarchive.org/](https://ghostarchive.org/)  
#### 网页存档辅助工具  
  - [Wayback](https://github.com/wabarc/wayback)![Open-Source Software][oss icon]  
    - Wayback 公共实例  
      - [https://wabarc.eu.org](https://wabarc.eu.org)  
      - [https://initium.eu.org](https://initium.eu.org)  
      - 存档结果：[https://loph.notion.site/f514a62ea1254d05ac5c92a48b9fe9b5](https://loph.notion.site/f514a62ea1254d05ac5c92a48b9fe9b5)
    - Telegram bot  
      - [@wabarc_bot](https://t.me/wabarc_bot)  
    - 自托管
  - 浏览器插件 [Archiveror](https://github.com/rahiel/archiveror)
  - 命令行工具 [archivenow](https://github.com/oduwsdl/archivenow) 


### RSS

#### RSS资源导航 
- [All-about-RSS](https://github.com/AboutRSS/ALL-about-RSS)![Open-Source Software][oss icon] – RSS 相关事物列表，包括工具、服务、社区和教程       

#### RSS阅读器
- [Raven Reader](https://github.com/hello-efficiency-inc/raven-reader)![Open-Source Software][oss icon] – Windows/macOS/Linux  
- [Thunderbird](https://www.thunderbird.net/)![Open-Source Software][oss icon] – Windows/macOS/Linux    
- [NewsFlash](https://flathub.org/apps/details/com.gitlab.newsflash)![Open-Source Software][oss icon] – Linux    
- [NetNewsWire](https://github.com/Ranchero-Software/NetNewsWire)![Open-Source Software][oss icon] – macOS/iOS  
- [NewsBlur](https://github.com/samuelclay/NewsBlur)![Open-Source Software][oss icon] – Android  
- [ReadYou](https://github.com/Ashinch/ReadYou)![Open-Source Software][oss icon] – Android  

#### RSS辅助工具  
- [RSSHub](https://github.com/DIYgod/RSSHub)![Open-Source Software][oss icon] – 为不支持 RSS 的网站生成 RSS feed  
  - [RSSHub-Radar](https://github.com/DIYgod/RSSHub-Radar)![Open-Source Software][oss icon] – 嗅探 RSS 订阅源的浏览器插件  
- [kill-the-newsletter](https://kill-the-newsletter.com/)![Open-Source Software][oss icon] – 将邮件订阅转换成 RSS 订阅  


### 效率工具

#### 元数据清除

- [mat2](https://0xacab.org/jvoisin/mat2)![Open-Source Software][oss icon] | [Web](https://matweb.info/)
- [ExifTool](https://exiftool.org/)![Open-Source Software][oss icon] – Windows/macOS/Linux
- [Dangerzone](https://github.com/freedomofpress/dangerzone)![Open-Source Software][oss icon] – Windows/macOS/Linux  
- [Scrambled Exif](https://gitlab.com/juanitobananas/scrambled-exif)![Open-Source Software][oss icon] – Android


#### 沙盒工具

- [Firejail](https://github.com/netblue30/firejail)![Open-Source Software][oss icon] – Linux  
- [Sandboxie](https://github.com/sandboxie-plus/Sandboxie)![Open-Source Software][oss icon] – Windows  
- [Shelter](https://gitea.angry.im/PeterCxy/Shelter)![Open-Source Software][oss icon] – Android  
- [Insular](https://gitlab.com/secure-system/Insular)![Open-Source Software][oss icon] – Android  


#### 防火墙

- [Portmaster](https://github.com/safing/portmaster)![Open-Source Software][oss icon] – Windows/Linux

#### 网络流量分析
- [Wireshark](https://www.wireshark.org)![Open-Source Software][oss icon] – Windows/macOS/Linux

#### 网络测速工具
- [LibreSpeed](https://librespeed.org/)![Open-Source Software][oss icon] – Web

#### 远程桌面

- [RustDesk](https://github.com/rustdesk/rustdesk)![Open-Source Software][oss icon] – Windows/macOS/Linux/Android/iOS 

#### 文件同步

- [Syncthing](https://github.com/syncthing/syncthing)![Open-Source Software][oss icon] – Windows/macOS/Linux/Android 


#### 输入法

- [Fcitx](http://fcitx-im.org/)![Open-Source Software][oss icon] – Linux/FreeBSD
- [Rime](https://rime.im)![Open-Source Software][oss icon]  
	- 小狼毫 [Weasel](https://github.com/rime/weasel/) – Windows  
	- 鼠鬚管 [Squirrel](https://github.com/rime/squirrel/) – macOS  
	- [ibus-rime](https://github.com/rime/home/wiki/RimeWithIBus) – Linux
	- [fcitx-rime](https://github.com/fcitx/fcitx-rime) – Linux

#### PDF工具
- PDF 阅读器
  - [Sumatra PDF](https://www.sumatrapdfreader.org/free-pdf-reader.html)![Open-Source Software][oss icon] – Windows
- PDF 注释工具
    - [Xournalpp](https://xournalpp.github.io/)![Open-Source Software][oss icon] – Windows/macOS/Linux

#### 电子书工具  

- 电子书阅读器
  - [Koodo Reader](https://github.com/troyeguo/koodo-reader)![Open-Source Software][oss icon] – Windows/macOS/Linux/Web  
  - [KOReader](https://github.com/koreader/koreader)![Open-Source Software][oss icon] – Linux/Android/Kindle
  - [Foliate](https://github.com/johnfactotum/foliate)![Open-Source Software][oss icon] – Linux  
  - [Librera Reader](https://github.com/foobnix/LibreraReader)![Open-Source Software][oss icon] – Android
- 电子书管理  
  - [Calibre](https://calibre-ebook.com/)![Open-Source Software][oss icon] – Windows/macOS/Linux  

#### 多媒体播放器  
- [VLC](https://www.videolan.org/vlc/)![Open-Source Software][oss icon] – Windows/macOS/Linux/Android/iOS  
- [mpv](https://mpv.io)![Open-Source Software][oss icon] – Windows/macOS/Linux/Android

#### 下载工具  
- [Motrix](https://github.com/agalwood/Motrix)![Open-Source Software][oss icon] – Windows/macOS/Linux  
- [Seal](https://github.com/JunkFood02/Seal)![Open-Source Software][oss icon] – Android   
- BitTorrent  
  - 客户端  
    - [qBittorrent](https://github.com/qbittorrent/qBittorrent)![Open-Source Software][oss icon] – Windows/macOS/Linux      
    - [qBittorrent-Enhanced-Edition](https://github.com/c0re100/qBittorrent-Enhanced-Edition)![Open-Source Software][oss icon] – Windows/macOS/Linux  
  - BitTorrent Tracker  
    - [trackerslist](https://github.com/ngosang/trackerslist)  
    - [TrackersListCollection](https://github.com/XIU2/TrackersListCollection)

#### 邮箱客户端

- [Thunderbird](https://www.thunderbird.net/)![Open-Source Software][oss icon] – Windows/macOS/Linux    
- [K-9 Mail](https://github.com/thundernest/k-9)![Open-Source Software][oss icon] – Android 

#### 加密即时通讯
- 去中心化加密 IM
	- [Session](https://getsession.org/)![Open-Source Software][oss icon] – 默认端对端加密；实时同步
	- [Matrix](https://matrix.org/get-started)![Open-Source Software][oss icon] – 联邦式去中心化；默认端对端加密；实时同步
		- Matrix 客户端
			- [Element](https://element.io/)![Open-Source Software][oss icon] – Windows/macOS/Linux/Android/iOS/[Web](https://app.element.io/)
			- [FluffyChat](https://fluffychat.im/)![Open-Source Software][oss icon] – Linux/Android/iOS/Web
			- [更多客户端](https://matrix.org/clients/)
- 中心化加密 IM
	- [Telegram](https://telegram.org/) – Windows/macOS/Linux/Web/iOS/Android 客户端开源；注册需手机号码；私密模式支持端对端加密；实时同步  
	- [Signal](https://signal.org/)![Open-Source Software][oss icon] – Windows/macOS/Linux/iOS/Android；注册需手机号码
- 本地网络即时通讯工具
	- [Berty](https://github.com/berty/berty) – iOS/Android 默认端对端加密；P2P
	- [Briar](https://briarproject.org/) – Android
- 加密短信
	- [Silence-Android](https://git.silence.dev/Silence/Silence-Android/)![Open-Source Software][oss icon] – Android；加密 SMS/MMS 短信

#### 视频会议

- [Jitsi Meet](https://github.com/jitsi/jitsi-meet)![Open-Source Software][oss icon] – iOS/Android/Web

### 加密货币

#### 比特币钱包

- [Samourai](https://samouraiwallet.com/)![Open-Source Software][oss icon] – Android
- [Sparrow Wallet](https://sparrowwallet.com/)![Open-Source Software][oss icon] – Windows/macOS/Linux
- [Wasabi](https://wasabiwallet.io/)![Open-Source Software][oss icon] – Windows/macOS/Linux
- [Edge](https://edge.app/)![Open-Source Software][oss icon] – Android/iOS
- [Electrum](https://electrum.org/)![Open-Source Software][oss icon] – Windows/macOS/Linux

#### 门罗币钱包

- [Monero GUI Wallet](https://www.getmonero.org/downloads/#gui)![Open-Source Software][oss icon] – Windows/macOS/Linux
- [Feather Wallet](https://featherwallet.org/)![Open-Source Software][oss icon] – Windows/macOS/Linux
- [Cake Wallet](https://cakewallet.com/)![Open-Source Software][oss icon] – Android/iOS
- [Monerujo](https://www.monerujo.io/)![Open-Source Software][oss icon] – Android

#### 加密货币转换工具

- [unstoppableswap-gui](https://github.com/UnstoppableSwap/unstoppableswap-gui)![Open-Source Software][oss icon]

#### 非实名制交易所清单 

- [KYCNOT.ME](https://kycnot.me/) 


### 未归类工具

- [Anonymous Camera](https://apps.apple.com/us/app/anonymous-camera/id1504102584) – iOS；拍摄自动模糊人脸或全身的视频
- [Stingle](https://stingle.org/)![Open-Source Software][oss icon] – Android/iOS；端对端加密相册云备份工具


## 网络资源

### 隐私与安全

#### 网页代理  
- [StartPage 搜索引擎](https://www.startpage.com/) -->> 匿名浏览模式  
- [SearX 搜索引擎](https://searx.space/) -->> [morty](https://github.com/asciimoo/morty) 隐私强化代理（部分实例支持） 
- [https://www.4everproxy.com/](https://www.4everproxy.com/)  

#### 网络封锁相关信息
- 测试网站是否被 GFW 封锁  
  - [GreatFire Blocky](https://blocky.greatfire.org/) – Web  
  - [comparitech - blockedinchina](https://www.comparitech.com/privacy-security-tools/blockedinchina/) – Web   
- [NetBlocks](https://netblocks.org/) - 实时绘制互联网自由地图；Web
- [GFW Report](https://gfw.report/) | [GitHub](https://github.com/gfw-report) | [Twitter (Nitter) ](https://nitter.net/gfw-report)
- [Net4People论坛](https://github.com/net4people/bbs) – 针对翻墙工具开发者和研究人员的技术论坛

#### 密码泄露查询
- [have i been pwned](https://haveibeenpwned.com/)
- [DeHashed](https://www.dehashed.com/)
- [Leakcheck](https://leakcheck.io/)
- [Firefox Monitor](https://monitor.firefox.com/)
- [Spy Cloud](https://spycloud.com/check-your-exposure/)

#### 在线病毒扫描

- [VirusTotal](https://virustotal.com/) – 支持扫描文件、网站链接  
- [Hybrid Analysis](https://www.hybrid-analysis.com/) – 支持扫描文件、网站链接  

#### 短链接分析工具  

- [Unshorten](https://unshorten.link/)  

#### 加密邮箱  
  - [Protonmail](https://mail.protonmail.com)
  - [Tutanota](https://tutanota.com/)
  - [Disroot.org](https://disroot.org/en)  
  - [Onion Mail](https://onionmail.org/)

#### 临时邮箱  
- [https://maildrop.cc/](https://maildrop.cc/)
- [https://erine.email/](https://erine.email/)
- [https://temp-mail.org/en/](https://temp-mail.org/en/) 
- [https://mailsac.com/](https://mailsac.com/)
- [https://temporarymail.com/](https://temporarymail.com/)
- [https://grr.la/mail/grrmailb3fxpjbwm.onion](https://grr.la/mail/grrmailb3fxpjbwm.onion)
- [https://tempmail.plus](https://tempmail.plus)
- [https://10minutemail.net/?lang=en](https://10minutemail.net/?lang=en)
- [https://dropmail.me/en/](https://dropmail.me/en/)
- https://privatlab.com/
- https://emailfake.com/
- https://www.fakemail.net/
- https://www.dispostable.com/
- https://temp-mail.to/
- http://mailcatch.com
- https://getnada.com/
- https://www.guerrillamail.com/
- https://www.mailinator.com/
- https://www.emailondeck.com/
- https://yopmail.com/en/
- https://www.33mail.com/
- https://www.moakt.com/
- http://mailcatch.com/en/disposable-email
- http://mytrashmail.com/
- https://www.emaildrop.io/
- https://tempr.email/en/
- https://www.mohmal.com/en
- https://www.tempinbox.xyz/

credit: https://t.me/iyouport/12099

#### 一次性手机号

- Hushed ([Android](https://play.google.com/store/apps/details?id=com.hushed.release) | [iOS](https://itunes.apple.com/us/app/hushed-2nd-phone-number/id600520752&at=1l3vs3K/?at=1l3vs3K))
- Burner ([Android](https://play.google.com/store/apps/details?id=com.adhoclabs.burner) | [iOS](https://itunes.apple.com/us/app/burner-2nd-phone-number/id505800761&at=1l3vs3K/?at=1l3vs3K))
- CoverMe ([Android](https://play.google.com/store/apps/details?id=ws.coverme.im) | [iOS](https://itunes.apple.com/us/app/coverme-private-text-call/id593652484&at=1l3vs3K/?at=1l3vs3K)) 
- TextMe Up ([Android](https://play.google.com/store/apps/details?id=com.textmeinc.textme3&hl=en) | [iOS](https://itunes.apple.com/us/app/textme-up-second-phone-number/id996263494&at=1l3vs3K/?at=1l3vs3K))
- https://receive-sms-online.com
- https://receive-sms-now.com
- https://hs3x.com
- https://twilio.com
- https://freesmsverification.com
- https://freeonlinephone.org
- https://sms-receive.net
- https://smsreceivefree.com
- https://receive-a-sms.com
- https://receivefreesms.com
- https://freephonenum.com
- https://receive-smss.com
- https://receivetxt.com
- https://temp-mails.com
- https://receive-sms.com
- https://receivesmsonline.net
- https://receivefreesms.com
- https://sms-receive.net
- https://pinger.com
- https://textnow.com
- https://receive-a-sms.com
- https://k7.net
- https://kall8.com
- https://faxaway.com
- https://receivesmsonline.com
- https://receive-sms-online.info
- https://sellaite.com
- https://getfreesmsnumber.com
- https://smsreceiving.com
- https://smstibo.com
- https://catchsms.com
- https://freesmscode.com
- https://smsreceiveonline.com
- https://smslisten.com
- https://sms.sellaite.com
- https://smslive.co

credit: https://t.me/iyouport/6597


#### 隐私强化前端
- YouTube -->> [Invidious](https://github.com/iv-org/invidious)![Open-Source Software][oss icon]
	- [Invidious 公共实例列表](https://docs.invidious.io/Invidious-Instances.md)
- YouTube -->> [FreeTube](https://github.com/FreeTubeApp/FreeTube)![Open-Source Software][oss icon]
- Twitter -->> [Nitter](https://github.com/zedeus/nitter)![Open-Source Software][oss icon]  
  - [Nitter 公共实例列表](https://github.com/zedeus/nitter/wiki/Instances)
- Instagram-->> [Bibliogram](https://sr.ht/~cadence/bibliogram/)![Open-Source Software][oss icon]
  - [Bibliogram 公共实例列表](https://git.sr.ht/~cadence/bibliogram-docs/tree/master/docs/Instances.md)
- Reddit -->> [Libreddit](https://github.com/spikecodes/libreddit#instances)![Open-Source Software][oss icon]
	- [Libreddit 公共实例列表](https://github.com/spikecodes/libreddit#instances)
- Reddit -->> [Teddit](https://codeberg.org/teddit/teddit)![Open-Source Software][oss icon]
	- [Teddit  公共实例列表](https://codeberg.org/teddit/teddit#instances)


### 日常办公

#### 搜索引擎

  - [Whoogle](https://github.com/benbusby/whoogle-search)![Open-Source Software][oss icon] – Google 搜索的去 Javascript 前端  
    - [Whoogle 公共实例列表](https://github.com/benbusby/whoogle-search#public-instances)  
  - [SearX](https://github.com/searx/searx)![Open-Source Software][oss icon]  
  	- [SearX 公共实例列表](https://searx.space/)  
  - [LibreX](https://github.com/hnhx/librex)![Open-Source Software][oss icon] – 尊重隐私、支持搜索 Google 和 BT 种子站点的元搜索引擎  
    - [LibreX 公共实例列表](https://github.com/hnhx/librex/#instances)  
  - [DuckDuckGo](https://duckduckgo.com/)  
  - [Startpage](https://www.startpage.com/)  

#### 文件传输  
- 本地网络文件传输  
  - [Snapdrop](https://snapdrop.net)![Open-Source Software][oss icon]    
- 网盘（免注册）  
  - [AnonFile](https://anonfiles.com) – 单个文件上限 20 GB；无带宽限制  
  - [filechan](https://filechan.org/) – 同上  
  - [ufile](https://ufile.io) – 单个文件上限 5 GB  
  - [uptobox](https://uptobox.com/) – 单个文件上限 1 GB  
- 临时网盘/文件传输  
	- [Send](https://github.com/timvisee/send)![Open-Source Software][oss icon]    
    	- [公共实例列表](https://github.com/timvisee/send-instances/#instances) – 文件大小、有效时长取决于具体实例  
	- [Tmp.Ninja](https://tmp.ninja) – 单个文件上限 10 GB；有效时长 48 小时  
	- [Wormhole](https://wormhole.app) – 单个文件上限 10 GB；5 GB 以下保存 24 小时，5 GB 以上 P2P 实时传输  
	- [tmpfiles.org](https://tmpfiles.org/) – 单个文件上限 100 MB；有效时长 1 小时  

#### 图床  
- [https://imgbb.com](https://imgbb.com)  
- [https://postimages.org](https://postimages.org)  
- [https://upload.cc](https://upload.cc)  
- Telegraph  
  - [https://telegra.ph](https://telegra.ph)  
  - [https://graph.org](https://graph.org)  
  - [https://te.legra.ph](https://te.legra.ph)

#### 在线剪贴板  
  - [PrivateBin](https://privatebin.net/)![Open-Source Software][oss icon]  
    - [PrivateBin 公共实例列表](https://privatebin.info/directory/)  

#### 翻译  
- [LibreTranslate](https://github.com/LibreTranslate/LibreTranslate)![Open-Source Software][oss icon]
	- [LibreTranslate 公共实例列表](https://github.com/LibreTranslate/LibreTranslate#mirrors)
- [SimplyTranslate](https://git.sr.ht/~metalune/simplytranslate_web)![Open-Source Software][oss icon]
	- [SimplyTranslate 公共实例列表](https://git.sr.ht/~metalune/simplytranslate_web#list-of-instances)

#### 地图  
  - [OpenStreetMap](https://www.openstreetmap.org/)  
    - [OpenStreetMap 公共实例列表](https://wiki.openstreetmap.org/wiki/Tile_servers)

#### GitHub镜像站  
- [https://hub.fastgit.xyz](https://hub.fastgit.xyz)  
- [https://cdn.githubjs.cf](https://cdn.githubjs.cf)  
- [https://gitclone.com](https://gitclone.com)  
- [https://gh.api.99988866.xyz/](https://gh.api.99988866.xyz/)  
- [https://ghproxy.com/](https://ghproxy.com/)  
- [https://pd.zwc365.com/](https://pd.zwc365.com/)  


### 社交媒体

- [Mastodon](https://joinmastodon.org/)![Open-Source Software][oss icon]  
  - [Mastodon 公共实例列表](https://joinmastodon.org/servers)  
- [Pleroma](https://pleroma.social/)![Open-Source Software][oss icon]
- [Misskey](https://join.misskey.page/)![Open-Source Software][oss icon]  
- [NeoDB](https://neodb.social)![Open-Source Software][oss icon] – 联邦宇宙书影音游戏标注平台

### 文化资源

#### 影视资源
- BT 种子站
  - [迷客电影](https://www.mini4k.com/) – 电影/电视/动漫  
  - [人人影视分享站](https://yyets.dmesg.app/home)  
  - [YTS.MX](https://yts.mx/) – 电影 
  - [1337X](https://1337x.st)  
  - [RARBG](https://rarbg.to/torrents) – 电影/电视剧/音乐
  - [EZTV](https://eztv.re) – 电视剧资源
  - [动漫花园](https://dmhy.org/) – 中文ACG  

#### 学术资源
- [Libgen](https://libgen.is/) – 电子书/期刊论文  
- [Z-Library](https://singlelogin.me) – 电子书/期刊论文
- [Sci-Hub](https://sci-hub.ru/) – 期刊论文
- [无产阶级图书馆](https://library.proletarian.me) – 电子书  
- [书格](https://new.shuge.org/) – 中文古籍  
- 更多参见 [缪缪收藏的图书网址信息](https://bgme.me/@Camus/109284118369473526)

#### 被屏蔽资源镜像站

- [https://unblockit.pages.dev/](https://unblockit.pages.dev/)


### 未归类资源

- [Apple Censorship](https://applecensorship.com) – 检测在特定地区 App Store 被下架的 app
- [Tor Metrics](https://metrics.torproject.org/)  
- [Tor Project - Good Bad ISPs](https://community.torproject.org/relay/community-resources/good-bad-isps/)  


## 信息安全参考资料
- [编程随想的博客](https://program-think.blogspot.com/)  
- [digital-rights](https://gitlab.com/mdrights/digital-rights)  
- [PrivacyTools](https://www.privacytools.io/)
- [Privacy Guides - Privacy Tools](https://www.privacyguides.org/tools/)  
- [Prism Break](https://prism-break.org/) / [中文版](https://prism-break.org/zh-TW/) 
- [The Hitchhiker’s Guide to Online Anonymity](https://anonymousplanet.org/guide.html)
- [iYouPort](https://iyouport.substack.com/)  
- [现代隐私保护指南 - Modern Security Protection Guide - Arch Linux Studio](https://archlinuxstudio.github.io/ModernSecurityProtectionGuide/)  
- [Digital-Privacy](https://github.com/ffffffff0x/Digital-Privacy) 
- [Zebra Crossing](https://github.com/narwhalacademy/zebra-crossing) / [繁体中文版](https://github.com/narwhalacademy/zebra-crossing/blob/master/README-%E7%B9%81%E9%AB%94%E4%B8%AD%E6%96%87.md)
- [EFF｜Surveillance Self-Defense](https://ssd.eff.org/en#index)｜[中文翻译版](https://ocftw.github.io/ssd.eff.org/zh_TW/index.html)
- [Opsec：翻墙匿名反党圣经](https://community.geph.io/t/topic/6192)
- [左派如何学会"匿名上网"](https://learnleft.github.io/)
- [brainfucksec.github.io](https://brainfucksec.github.io/)
	- [brainfucksec.github.io | android-foss-apps-list](https://brainfucksec.github.io/android-foss-apps-list)


## 参考与鸣谢

- [2047.one/g/2047/entity/Link](https://2047.one/g/2047/entity/Link)  
- [AlternativeTo](https://alternativeto.net)  
- [android-foss](https://github.com/offa/android-foss)
- [Awesome-Linux-Software](https://github.com/luong-komorebi/Awesome-Linux-Software)    
- [抱月](https://mastodon.online/@baoyue)  
- [iYouPort](https://iyouport.substack.com/)  
	- [iYouPort | 安全手册：这里是你需要的几乎所有基本安全上网工具（1）](https://iyouport.substack.com/p/1-6dc)
	- [iYouPort | 安全工具箱补充版：分类工具列表（2）](https://iyouport.substack.com/p/2-36e)
- [learnleft](https://github.com/learnleft/learnleft.github.io)
- [libgen](https://2047.one/u/2764)  
- [NodeBE4](https://github.com/nodebe4)  
- [NarratorZ-new](https://i2pforum.net/memberlist.php?mode=viewprofile&u=6391)



[oss icon]: https://raw.githubusercontent.com/reconsidera/awesome-reconsidera-takeaway/main/media/open-source.png
