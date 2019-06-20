# flutter-img-sync
a plugin for flutter images synchronization

> 声明：插件灵感来自于[asset_generator](https://github.com/flutter-dev/asset_generator)，致谢作者
> 
> Android Studio及IDEA可在插件商店中搜索并安装: **flutter-img-sync**  [使用说明](https://www.jianshu.com/p/c7c063ce9e19)
> 
> vs code编辑器在扩展商店中搜索并安装： **flutter-img-sync**  [使用说明](https://www.jianshu.com/p/74b71719bc6d)
> 
> 功能：将资产目录下的图片自动添加到pubspec.yaml的assets配置下面，并生成R文件，代码中直接引用R文件下的定义即可
> 
> 如有疑问，[加群讨论【AndroidRunner】](https://jq.qq.com/?_wv=1027&k=5wXzlBY)
  
# How To Use

## step1.创建资产图片存放目录

创建资产图片存放目录 如: ./assets/img

## step2.修改pubspec.yaml

定义资产图片存放目录，如:

    assets:
    # assets-generator-begin
    # assets/img/*
    # assets-generator-end

## step3.执行 FlutterImgSync (flutter-img-sync)

- 命令执行后，图片将会被自动放置到pubspec.yaml文件的assets变量中
- ./lib/r.dart 将会被创建
- 在代码中导入r.dart文件，然后引用R类的变量

## step4.pub get 刷新一下

## 图片演示（android studio为例）

![创建图片存放目录](https://upload-images.jianshu.io/upload_images/2091835-ba87d8c8b1901873.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![修改pubspec.yaml](https://upload-images.jianshu.io/upload_images/2091835-91182b10e5ceeb60.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![执行脚本任务](https://upload-images.jianshu.io/upload_images/2091835-dbfb3d5a16e12659.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![assets图片资源自动放置并生成r.dart](https://upload-images.jianshu.io/upload_images/2091835-96584efbe01a80f3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![使用R文件](https://upload-images.jianshu.io/upload_images/2091835-3dc54a6ac6e0a8b8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


