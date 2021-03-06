# ink_Werttin

> An ink theme based on offical theme.

## Warning

本主题暂时不会更新，如果遇到不兼容情况，~~请自己捣鼓捣鼓~~。

## 使用说明

### 预览

最简单的方法是去参观我的博客~ [传送门](http://ikevin.in)

以下截图可能有点旧。

[首页](https://cloud.githubusercontent.com/assets/9017470/10266999/daf3a772-6ab1-11e5-9449-5bcc47eabbc7.gif) \ [文章页](https://cloud.githubusercontent.com/assets/9017470/10267001/06981ca0-6ab2-11e5-9f6e-ad007b3e66b6.gif) \ [归档页](https://cloud.githubusercontent.com/assets/9017470/10267003/26286408-6ab2-11e5-97b4-1cf25b14a98a.gif)

### 下载

对于旧版 InkPaper（即主题目录下不包含 `config.yml` 的版本），见 [Release 页面](https://github.com/Skimige/ink_Werttin/releases) 。

> 目前的最新版本：Beta @ 1.0.3

对于新版 InkPaper，请点击 [这里](https://github.com/Skimige/ink_Werttin/archive/master.zip)

### 功能

 - 默认字体为 `Microsoft Yahei UI` ，对 `sans-serif` 和 `serif` 没啥好感
 - 支持 zh (Chinese) / en (English) / ru (Russian) / jp (Japanese) 四种语言（后两种感谢原作者 @imeoer），请修改根目录的 `config.yml` 中此处：

>     lang: **

 - 为了使加载速度更快，摒弃了大部分图片。其中包括首页作者Avatar、文章下小Avatar等
 - 文章内**不支持头图功能**（此功能被阉割）
 - 支持图片 Lazyload
 - 支持页面平滑滚动
 - more..

### 打开姿势

下载完整包，把其中唯一的文件夹扔到 ink 根目录。

修改 `config.yml` 中下列字段如下：

修改前：

```
site:
    ...
    theme: theme
    ...
```

修改后：

```
site:
    ...
    theme: ink_Werttin
    ...
``` 

在主题目录下的 `config.yml` 中，如果你的 `favicon.ico` 要替换或者修改为 PNG 格式的图片等，请自行修改。

如果没有图片或者懒得设置，**请删除这一行，否则可能会报错。**

从 Beta @ 1.0.3 起，本主题不再提供 `favicon.png` 。

另：虽然确实是去掉了首页的几个头像，但在文章页评论框上，作者简介中的头像并没有去掉。
所以…别忘了设置 `config.yml` 中的 `avatar` & `logo` ！

**如有任何问题，欢迎即刻联系我或者提 issue，不过处理时间可能很长就是，因为很忙。**

## License

遵循 [Apache License 2.0](https://github.com/Skimige/ink_Werttin/blob/master/LICENSE)
