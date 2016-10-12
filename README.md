# fcitx-sogoupinyin

Sogou Pinyin IME (搜狗拼音输入法 for Linux)

## Dependencies

* [fcitx] (https://slackbuilds.org/repository/14.2/misc/fcitx/)
* [fcitx-qimpanel] (https://github.com/slackwarecn-slackbuilds/fcitx-qimpanel)
* **Optional** [opencc] (https://slackbuilds.org/repository/14.2/misc/opencc)
* unzip *Offical Support*
* qt4 *Offical Support*
* zlib *Offical Support*
* [kdeplasma-addons] *Offical Support*

## Recommends

* [fcitx-qt5] (https://github.com/slackwarecn-slackbuilds/fcitx-qt5)
* [google-droid-fonts] (https://slackbuilds.org/repository/14.2/system/google-droid-fonts/)

## Build & Install

```bash
source fcitx-sogoupinyin.info
wget -O sogoupinyin_${VERSION}_amd64.deb $DOWNLOAD_x86_64
# or wget -O sogoupinyin_${VERSION}_i386.deb $DOWNLOAD
sh ./fcitx-sogoupinyin.SlackBuild
installpkg /tmp//tmp/fcitx-sogoupinyin-2.1.0.0082-x86_64-1_SBo.tgz
# just check your slackbuild script output, last line like this:
#
# Slackware package /tmp/fcitx-sogoupinyin-2.1.0.0082-x86_64-1_SBo.tgz created.
#
```

## Usage

如果想要在进入桌面时自动启动搜狗输入法，有两种方式可以选择。

如果你在使用KDE桌面，打开并进入你的“系统设置 -> 开机和关机 -> 自动启动”，然后点击“添加程序”，在顶部的输入框中输入`sogou-qimpanel`，然后直接点击确定。

在随后弹出的对话框中，可根据需要自行修改部分选项。然后点击确定，即可完成。

要切换到搜狗输入法，右击你系统托盘中的小企鹅图标，在输入法选单中选择搜狗输入法。

然后，你就可以使用Ctrl+空格或其他你设置的快捷键来自由切换到搜狗输入法了，来享受Linux下全新的中文输入体验吧！
