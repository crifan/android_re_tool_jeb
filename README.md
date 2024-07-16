# 安卓逆向利器：JEB

* 最新版本：`v1.0.1`
* 更新时间：`20240716`

## 简介

介绍安卓逆向中的好用工具JEB，主要用于静态分析中的反编译apk/dex，和动态调试安卓程序。先是JEB概览；然后是如何下载和运行JEB；然后介绍JEB的功能和界面，包括Bytecode/Hierarchy、单个文件多个显示模式、底部多个Tab页、保存项目为jdb2文件、多主题显示效果、支持的反编译器、脚本功能、插件机制；然后介绍JEB的静态分析，包括反编译安卓apk，其中包含反编译出java和解析so库文件；反编译出java包括单个反编译、全部反编译、反编译效果对比，其下包括JEB和jadx对比；接着是JEB动态调试；以及JEB使用心得，包括页面显示方面和反编译java代码方面；以及JEB常见问题，包括页面显示问题和反编译java代码问题。

## 源码+浏览+下载

本书的各种源码、在线浏览地址、多种格式文件下载如下：

### HonKit源码

* [crifan/android_re_tool_jeb: 安卓逆向利器：JEB](https://github.com/crifan/android_re_tool_jeb)

#### 如何使用此HonKit源码去生成发布为电子书

详见：[crifan/honkit_template: demo how to use crifan honkit template and demo](https://github.com/crifan/honkit_template)

### 在线浏览

* [安卓逆向利器：JEB book.crifan.org](https://book.crifan.org/books/android_re_tool_jeb/website/)
* [安卓逆向利器：JEB crifan.github.io](https://crifan.github.io/android_re_tool_jeb/website/)

### 离线下载阅读

* [安卓逆向利器：JEB PDF](https://book.crifan.org/books/android_re_tool_jeb/pdf/android_re_tool_jeb.pdf)
* [安卓逆向利器：JEB ePub](https://book.crifan.org/books/android_re_tool_jeb/epub/android_re_tool_jeb.epub)
* [安卓逆向利器：JEB Mobi](https://book.crifan.org/books/android_re_tool_jeb/mobi/android_re_tool_jeb.mobi)

## 版权和用途说明

此电子书教程的全部内容，如无特别说明，均为本人原创。其中部分内容参考自网络，均已备注了出处。如发现有侵权，请通过邮箱联系我 `admin 艾特 crifan.com`，我会尽快删除。谢谢合作。

各种技术类教程，仅作为学习和研究使用。请勿用于任何非法用途。如有非法用途，均与本人无关。

## 鸣谢

感谢我的老婆**陈雪**的包容理解和悉心照料，才使得我`crifan`有更多精力去专注技术专研和整理归纳出这些电子书和技术教程，特此鸣谢。

## 其他

### 作者的其他电子书

本人`crifan`还写了其他`150+`本电子书教程，感兴趣可移步至：

[crifan/crifan_ebook_readme: Crifan的电子书的使用说明](https://github.com/crifan/crifan_ebook_readme)

### 关于作者

关于作者更多介绍，详见：

[关于CrifanLi李茂 – 在路上](https://www.crifan.org/about/)
