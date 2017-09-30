<img src="https://bisq.io/wp-content/uploads/2014/09/bitsquare-home2.jpg"/>

本篇
------------------
作为译文、中文交流
Q群:246165192

# 汉化
下载这个内容
https://github.com/kdaye/exchange/blob/master/common/src/main/resources/i18n/displayStrings_cn.properties
把`displayStrings_cn.properties`改成`displayStrings.properties`

打开电脑中`C:\Users\用户名\AppData\Local\Bisq\app`
右键`Bisq.jar` 打开解压缩
找到`i18n`文件夹
拖入`displayStrings.properties`覆盖即可完成汉化



Bisq是什么?
------------------

Bisq是一个跨平台的桌面应用程序，允许用户在不依赖中心化交易所（如火币,Okcoin,BTCchina,Coinbase，Bitstamp或（曾经的）Mt. Gox.）的情况下数字货币兑换法币（美元，欧元，人民币等）。。

通过在本地机器上运行Bisq，用户形成对等网络。购买和出售比特币的委托广播到该网络，并通过Bisq 界面发布委托和委托下单这些交易的过程，建立了市场。

Bisq网络中没有控制或失败的中心点。没有值得信赖的第三方。当双方同意对本币进行比特币交易时，要购买或出售的比特币使用本地基于比特币协议的多重签名交易功能进行托管。

由于任何交易的法定货币必须通过汇款手段进行转移，Bisq将人力仲裁的环节纳入解决任何错误或争议。

您可以阅读白皮书 [whitepaper](https://bisq.io/bitsquare.pdf)和仲裁文件[arbitration](https://bisq.io/arbitration_system.pdf)中的所有内容。还有几个视频[videos](https://bisq.io/blog/category/video)也可用。


Status
------
Bisq has released the beta version on the 27th of April 2016. It is operational since that time without any major incident.
Please follow the current development state at our [road map]( https://bisq.io/roadmap).
For the latest version checkout our [releases page](https://github.com/bisq-network/exchange/releases) at Github.

Building from source
--------------------

See [doc/build.md](doc/build.md).

[AUR for Arch Linux](https://aur.archlinux.org/packages/bisq-git/)


Staying in Touch
----------------

Contact the team and keep up to date using any of the following:

 - The [Bisq Website](https://bisq.io)
 - GitHub [Issues](https://github.com/bisq-network/exchange/issues)
 - The [Bisq Forum]( https://forum.bisq.io)
 - The [#bitsquare](https://webchat.freenode.net/?channels=bitsquare) IRC channel on Freenode ([logs](https://botbot.me/freenode/bitsquare)) 
 - Our [mailing list](https://groups.google.com/forum/#!forum/bitsquare)
 - [@Bitsquare_](https://twitter.com/bitsquare_) on Twitter


License
-------

Bisq is [free software](https://www.gnu.org/philosophy/free-sw.html), licensed under version 3 of the [GNU Affero General Public License](https://gnu.org/licenses/agpl.html).

In short, this means you are free to fork this repository and do anything with it that you please. However, if you _distribute_ your changes, i.e. create your own build of the software and make it available for others to use, you must:

 1. Publish your changes under the same license, so as to ensure the software remains free.
 2. Use a name and logo substantially different than "Bisq" and the Bisq logo seen here. This allows for competition without confusion.

See [LICENSE](LICENSE) for complete details.
