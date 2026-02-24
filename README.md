# 欢迎点击进入我的App Store主页下载本人已上架发布的应用。
<a href='https://apps.apple.com/cn/developer/%E5%BC%BA-%E6%9B%BE/id1453461397'><img height='70' alt='Download from AppStore' src='https://img.whalenas.com:283/image/202207141215375.png' /></a>
> [https://apps.apple.com/cn/developer/%E5%BC%BA-%E6%9B%BE/id1453461397](https://apps.apple.com/cn/developer/%E5%BC%BA-%E6%9B%BE/id1453461397)
# 关注Telegram频道，获取最新信息。
> [https://t.me/iTelecast](https://t.me/iTelecast)

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
$ sh appleGenerator.sh ~/1024.png ~/icon
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
