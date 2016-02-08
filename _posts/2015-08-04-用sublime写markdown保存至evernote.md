---
title: 用sublime写markdown保存至evernote
updated: 2015-08-04 10:09
---

在开始之前，你需要知道这三件事儿：
>1. Evernote（印象笔记）提供了API，供第三方应用管理笔记；
>2. Markdown标记语言，你值得拥有；
>3. Sublime Text，码农不必多说。

受益于上述三件幸运的事，使得我们可以十分方便的在Sublime Text中，利用markdown编辑修改Evernote（印象笔记）中的笔记。废话不多说，下面进入正题。

首先你要习惯使用Sublime Text，如果还不习惯，那么我强烈推荐你花点时间了解一下，对它的评价我只用两个字：”神器”！

打开Sublime Text之后，`ctrl + shift + p`打开`Package Control`，输入`install`，跳出插件库，然后输入`Evernote`安装Evernote插件。该插件的介绍和详细的使用说明请参考：[插件介绍](https://sublime.wbond.net/packages/Evernote)。

插件安装完成之后，第一次使用时需要进行授权认证。步骤如下：

1. 打开`Package Control`，输入`send to evernote`，在窗口底部会弹出一个小窗口，窗口中的内容为一个带`token`的链接。该token后面用到。
2. 将链接复制到浏览器并访问，登录授权后，会有一个`NoteStore URL`。中国版印象笔记用户，可直接用浏览器访问链接：https://app.yinxiang.com/api/DeveloperToken.action
3. 打开Sublime Text，打开`Preferences` > `Package Settings` > `Evernote` > `Settings User`，将步骤1和步骤2中的`token`和`NoteStore URL`复制为对应属性值。保存之后便可以开始使用了。
4. 按上述方法创建完成之后，便可以非常方便的使用Evernote（印象笔记）了，而且笔记对应的目录和tag都可以自动提示。详细的功能和使用方法还是参考：[插件介绍](https://sublime.wbond.net/packages/Evernote)。
