# iOS/macOS/watchOS/iMessage App Icon and App LaunchScreen Images

## Install Homebrew
```
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Install imagemagick
```
$ brew install imagemagick
```
## iMessage icon
```
$ sh iMessageGenerator.sh [square_file_path] [rectangle_file_path]

// EXAMPLE
$ sh iMessageGenerator.sh ~/square.png ~/rectangle.png
```
describution:
1. square image : 1024x1024 pixel.
2. rectangle image : 1200x768 pixel.

## iOS/macOS/watchOS icon
```
$ sh appleGenerator.sh [source_image] [destination_path]

// EXAMPLE
$ sh appleGenerator.sh 1024.png ~/icon
```
describution:
1. source_image: The source png image, 1024x1024 pixel.
2. destination_path: The destination path where the icons generate to.

## LaunchScreen image
```
$ sh launchScreenGenerator.sh [source_image] [bg_color] [destination_directory]

// EXAMPLE
$ sh launchScreenGenerator.sh 1024.png "#FF4981" ~/icon
```
describution:
1. source_image: The source png image, 1024x1024 pixel.
2. bg_color: Background collor of 'App Launch (Default) Images'. You can set value like this.
3. destination_directory: Destination directory for images (optional).

## 自己研发自己推广。欢迎点击跳转App Store安装。
### 一、iPhone/iPad端安装
>[1、iTelevision （更好用的直播流播放器/手机电视）](https://apps.apple.com/cn/app/itelevision/id6443470500)
> iTelevision群：[https://t.me/iTelevisions](https://t.me/iTelevisions)

>[2、iNFC （读写NFC标签，复制门禁卡）](https://apps.apple.com/cn/app/infc/id1562054959)
> iNFC群：[https://t.me/NFCMaster](https://t.me/NFCMaster)

>[3、iSMS （AI离线智能拦截垃圾短信）](https://apps.apple.com/cn/app/isms/id1610118657)
> iSMS群：[https://t.me/iSMS_iContact](https://t.me/iSMS_iContact)

>[4、iDraft (电子绘图、电子草稿)](https://apps.apple.com/cn/app/idraft/id1555981466)
> iDraft群：[https://t.me/iDrafts](https://t.me/iDrafts)

>[5、iBlog （博客园客户端，开发者的网上家园）](https://apps.apple.com/cn/app/iblog/id1571216825)
> iBlog群：[https://t.me/iCnblog](https://t.me/iCnblog)

>[6、iNetwork](https://t.me/iNetworka)
> iNetwork群：[https://t.me/iNetworka](https://t.me/iNetworka)
### 二、iMac、MacBook等安装：
>[1、iSpider （复原windows端的蜘蛛纸牌）](https://apps.apple.com/cn/app/spider-card/id1579985010?mt=12)

>[2、Minesweeper+（复原windows端的扫雷）](https://apps.apple.com/cn/app/minesweeper/id1576828278?mt=12)

>[3、Touch Bar Brickout （打砖块小游戏）](https://apps.apple.com/cn/app/touch-bar-brickout/id1582094533?mt=12)

>[4、Redis Pro （后端Redis工具）](https://apps.apple.com/cn/app/redis-pro/id1576996455?mt=12b)
