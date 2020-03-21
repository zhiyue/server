## 野火IM解决方案

野火IM是一套跨平台、核心功能开源的即时通讯解决方案，主要包含以下内容。

| 仓库                                                         | 说明                                                    | 备注 |
| ------------------------------------------------------------ | ------------------------------------------------------- | ---- |
| [android-chat](https://github.com/wildfirechat/android-chat) | 野火IM Android SDK源码和App源码                       |可以很方便地进行二次开发，或集成到现有应用当中      |
| [ios-chat](https://github.com/wildfirechat/ios-chat)         | 野火IM iOS SDK源码和App源码                            |可以很方便地进行二次开发，或集成到现有应用当中      |
| [pc-chat](https://github.com/wildfirechat/pc-chat)           | 基于[Electron](https://electronjs.org/)开发的PC平台应用 |      |
| [web-chat](https://github.com/wildfirechat/web-chat)          | Web平台的Demo, [体验地址](http://web.wildfirechat.cn)   |      |
| [wx-chat](https://github.com/wildfirechat/wx-chat)           | 微信小程序平台的Demo   |      |
| [server](https://github.com/wildfirechat/server)             | IM server                                               |      |
| [app server](https://github.com/wildfirechat/app_server)     | 应用服务端                                          |      |
| [robot_server](https://github.com/wildfirechat/robot_server) | 机器人服务端                                        |      |
| [push_server](https://github.com/wildfirechat/push_server)   | 推送服务器                                              |      |
| [docs](https://github.com/wildfirechat/docs)                 | 野火IM相关文档，包含设计、概念、开发、使用说明          |      | |                                            |

# server
本工程为野火IM 社区版IM服务软件。野火IM作为一个通用的即时通讯解决方案，可以集成到各种应用中。请阅读[docs](http://docs.wildfirechat.cn)或下载服务器[发布版本](https://github.com/wildfirechat/server/releases)


开发一套IM系统真的很艰辛，请路过的朋友们给点个star，支持我们坚持下去🙏🙏🙏🙏🙏

### 联系我们

> 商务合作请优先采用邮箱和我们联系。技术问题请到[野火IM论坛](http://bbs.wildfirechat.cn/)发帖交流

1. heavyrain.lee  邮箱: heavyrain.lee@wildfirechat.cn  微信：wildfirechat
2. imndx  邮箱: imndx@wildfirechat.cn  微信：wfchat

### 问题交流

1. 如果大家发现bug，请在GitHub提issue
2. 其他问题，请到[野火IM论坛](http://bbs.wildfirechat.cn/)进行交流学习
3. 微信公众号

<img src="http://static.wildfirechat.cn/wx_wfc_qrcode.jpg" width = 50% height = 50% />

> 强烈建议关注我们的公众号。我们有新版本发布或者有重大更新会通过公众号通知大家，另外我们也会不定期的发布一些关于野火IM的技术介绍。

#### 体验Demo
我们提供了体验demo，请使用微信扫码下载安装体验

![野火IM](http://static.wildfirechat.cn/download_qrcode.png)

#### 加入野火官方体验交流群
使用野火IM移动客户端扫码下面二维码（不是使用微信扫码），和野火IM的爱好者一起畅谈野火IM的问题和经验：

![野火IM官方交流群](http://static.wildfirechat.cn/wildfirechat_official_group.jpeg)

#### 应用截图
![ios-demo](http://static.wildfirechat.cn/ios-demo.gif)

<img src="http://static.wildfirechat.cn/ios-message-view.png" width = 50% height = 50% />

<img src="http://static.wildfirechat.cn/ios-contact-view.png" width = 50% height = 50% />

<img src="http://static.wildfirechat.cn/ios-discover-view.png" width = 50% height = 50% />

<img src="http://static.wildfirechat.cn/ios-settings-view.png" width = 50% height = 50% />

<img src="http://static.wildfirechat.cn/ios-messagelist-view.png" width = 50% height = 50% />

<img src="http://static.wildfirechat.cn/ios-chat-setting-view.png" width = 50% height = 50% />

<img src="http://static.wildfirechat.cn/ios-takephoto-view.png" width = 50% height = 50% />

<img src="http://static.wildfirechat.cn/ios-record-voice-view.png" width = 50% height = 50% />

<img src="http://static.wildfirechat.cn/ios-location-view.png" width = 50% height = 50% />

<img src="http://static.wildfirechat.cn/ios-voip-view.png" width = 50% height = 50% />

## 编译
在安装JDK1.8以上及maven的前提下，在命令行中执行```mvn clean compile package```，生成的目标文件在```./distribution/target/distribution-xxxx-bundle-tar.tar.gz```

## 捐赠者名单

| 捐赠者 | 商标 | 金额 | 简介 |
| ----- | ---- | -------- | --- |
| [SAMOS](http://samos.io) | ![SAMOS](http://static.wildfirechat.cn/SAMOS.png) | 保密 | 一站式区块链解决方案服务商(http://samos.io) |

## 特别感谢
1. [moquette](https://github.com/moquette-io/moquette) 本项目是基于此项目二次开发而来，处理MQTT相关业务。
2. [loServer](https://github.com/looly/loServer) 本项目使用loServer处理HTTP相关业务。

*** 对他们表示诚挚的感谢🙏 ***

## License

1. Under the Creative Commons Attribution-NoDerivs 3.0 Unported license. See the [LICENSE](https://github.com/wildfirechat/server/blob/wildfirechat/LICENSE) file for details.
2. Under the Anti 996 License. See the [Anti 996 LICENSE](https://github.com/wildfirechat/server/blob/wildfirechat/LICENSE_996) file for details.
