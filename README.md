# ZKImageTractor
获取别家 App 的图片资源方法

##记得很久之前是直接在 iTunes 获取 ipa 包, 直接打开在 payload 中获取的, 不过随着越来越多的 App 通过 Assets 管理图片资源的, 所以之前的方法获取的图片就少之又少了, 现在介绍一个新方法
* 
用 iTunes 或者 iTools 将 App 拖到桌面

![QQ20160920-1.png](http://upload-images.jianshu.io/upload_images/1298481-fda35cd8bbe8cc7a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
* 
右键解归档打开这个 ipa 文件, 会看到一个 payload 文件, 右键显示包内容, 会看到一些图片资源, 注意: 这时候看到的图片资源是不完整的, 如果开发者没有将图片资源直接放在工程文件自己创建的目录而是放在 Assets 文件中, 这样是看不到的.
* 
那么怎么打开 Assets 文件中的图片资源呢
* 
https://github.com/devcxm/iOS-Images-Extractor/blob/master/README_zh-Hans.md
原来这位热心开发者写了一个工具, 来分分钟解决这个问题.
