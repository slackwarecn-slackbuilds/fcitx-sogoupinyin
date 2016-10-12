# fcitx-sogoupinyin

Sogou Pinyin IME (搜狗拼音输入法 for Linux)

## Dependencies

* [fcitx] (https://slackbuilds.org/repository/14.2/misc/fcitx/)
* [fcitx-qimpanel] **Working for it...**
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
