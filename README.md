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

## 效果演示(Android Studio or IDEA)

![Android Studio or IDEA](https://raw.githubusercontent.com/Leo0618/flutter-img-sync/master/androidstudio-play.gif)
  

## 效果演示(vs code)

![vs code](https://raw.githubusercontent.com/Leo0618/flutter-img-sync/master/vscode-play.gif)


# How To Use

## step1.创建资产图片存放目录

创建资产图片存放目录 如: ./assets/img

## step2.修改pubspec.yaml

定义资产图片存放目录，如:

    assets:
    # assets-generator-begin
    # assets/img/*
    # assets-generator-end

## step3.执行 FlutterImgSync (flutter-img-sync),AS和IDEA需要输入自定义图片预览的端口再点击确定执行插件

- 命令执行后，图片将会被自动放置到pubspec.yaml文件的assets变量中
- ./lib/r.dart 将会被创建
- 在代码中导入r.dart文件，然后引用R类的变量

## step4.pub get 刷新一下


