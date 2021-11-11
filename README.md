# flutter-img-sync
a plugin for flutter images synchronization

## Deprecated/Update Tips
- AndroidStudio版本在2020.3.1及之后的版本请使用1.1.0版本的插件，老版本不支持，IDE中若能直接更新可直接更，若无更新提示，可下载该仓库下的包【flutter-img-sync-1.1.0.zip】
  - 更新内容：
       1. 适配新版本AndroidStudio
       2. 支持获取svg图片
       3. 移除端口预览功能
- vscode对应的插件无更新

# How To Use

## step1.创建资产图片存放目录

创建资产图片存放目录 如: ./assets/img，./assets/img/pay

## step2.修改pubspec.yaml

定义资产图片存放目录（写文件夹名字即可），如:

    assets:
      assets/img/
      assets/img/pay

## step3.执行 FlutterImgSync (flutter-img-sync)

- 执行后，弹窗选择图片所在目录，可多选，再点击确定
- 命令执行后，./lib/r.dart 将会被创建
- 在代码中导入r.dart文件，然后引用R类的变量


### 插件商店地址

IDEA/AS: https://plugins.jetbrains.com/plugin/12585-flutter-img-sync/

vscode: https://marketplace.visualstudio.com/items?itemName=Lihaha.flutter-img-sync&ssr=false#overview
