## PefectAudioPlayerSystem

PefectAudioPlayerSystem 意指完美的数播系统

以前买音乐播放器，就是最求高度定制化的系统，希望达到更好听音感受。结果这么多年过去了，发现它们根本就是垃圾，系统兼容性，功能性全是废物，还敢卖那么多钱。

结果来说最强的 数播系统 还得是现在的普通手机/平板，在可以root的前提下，大公司还能更好的维护系统，使用还更加方便。

## 推荐设备

建议使用三星的平板
优势在于到了今时今日还能使用tf，本身系统优化也做的不错
系统自带 dolby atom，为新时代的全景声带来了系统支持。

## 系统支持

旧设备建议优先root系统，释放性能跟得到更强的设备全局eq体验。

https://magiskmanager.com/
https://github.com/topjohnwu/Magisk

magisk 官网能够更快捷的寻找到支持设备与相关信息

旧设备的话
推荐使用 uperf+Scene5 的组合，提高一下流程性

https://github.com/yc9559/uperf

https://www.coolapk.com/apk/com.omarea.vtools

Scene5专业版作为工具箱非常好用，买断也就十来块，值得一用。


## 全局eq，空间还原卷积器

各种方案汇集：

https://zackptg5.com/android.php#jdsp



个人优先建议使用 jamesdsp：
https://github.com/james34602/JamesDSPManager

https://github.com/therealahrion/JamesDSPManager


*由于joe神贵人多忘事，很多更新跟卷积器分享会在telegram上面分享。

请加入频道：
https://t.me/jDSP_V4A

对于没有root的手机：
https://github.com/ThePBone/RootlessJamesDSP

暂时对各机型的支持不太完善，也是一种解决方法。

导入eq数据：

https://github.com/ThePBone/DDCToolbox

ThePBone写的dcc文件生成器，可以用于任何的parameters eq

jamesdsp本身支持使用graphic eq，能够直接导入

## 数据来源

我现在主要使用的eq数据来源主要有两个

1. oratory1990 的 测试结果：

https://www.reddit.com/r/oratory1990/wiki/index/list_of_presets/

因为eq后oratory1990神还会进行二次测试，含金量非常的高。
如果所用耳机在这个列表中可以使用，请优先使用。

使用 DDCToolbox 生成文件后，直接放入DDC文件夹


2. jaakkopasanen 的 autoeq：

https://github.com/jaakkopasanen/AutoEq

有各种耳机的源数据跟eq结果，可以直接使用
也可以根据自己的需求使用autoeq进行再运算

里面提供了各种类型的eq参数，可以使用DDCToolbox倒入
graphic eq 则能够直接导入

通过fr测量与目标曲线截图打点，也可以获得自己的源数据：

https://apps.automeris.io/wpd/

实际测试可以用

jaako神还制作了排名，虽然他说不构成购买建议，但是实际上还是非常好用的：

https://github.com/jaakkopasanen/AutoEq/blob/master/results/RANKING.md


## 流媒体播放方案

流媒体首先建议使用

Apple music

新歌，无损，全景声
这几个要素已经足够了

作为补充使用的

由神刀天姬 制作的 网易音乐HD

详细内容：
https://g38yamn95p.feishu.cn/docs/doccnjL4viCcwKaJtw5PjfhZ9Pd#

v1可以任意使用，加群的话可以使用到v4

网易有很多海盗电台，我主要用这个


本地建议使用

最建议的是neutron，功能非常的强

https://neutroncode.com/

问题提在于国内要通过华为的应用商店，有点麻烦

vlc作为备用本地播放器还是可以的。

