# Log4j
Log4j漏洞自查工具

# Log4j2_detect工具使用说明
1、本工具用于自查本地服务器是否使用了与log4j相关的漏洞组件

2、支持windows、linux平台使用，windows支持命令行和界面版

3、检测原理：

判断检测目录的所有jar包里是否包含了log4j组件特征，并读取log4j版本号研判是否为存在漏洞版本，支持对jar包的嵌套检测并打印嵌套路径

4、使用说明

命令行运行程序 -h

5、漏洞版本：

rce漏洞:log4j2.x && <2.16.0，其中2.15.0属于疑似漏洞版本(rc1有漏洞rc2无漏洞)

dos漏洞:log4j2.x && <2.17.0

6、修复建议：

更新存在漏洞的jar包，更新地址：

https://github.com/apache/logging-log4j2/tags

# 程序截图

windows-命令行

![图片](http://r444q2fv9.hn-bkt.clouddn.com/win2-2.png)

linux-命令行

![图片](http://r444q2fv9.hn-bkt.clouddn.com/lin2-2.png)

windows-gui

![图片](http://r444q2fv9.hn-bkt.clouddn.com/wingui2-2.png)

了解更多详情可关注我们的公众号：

![图片](http://r444q2fv9.hn-bkt.clouddn.com/qrcode_for_gh_9e53931bba71_430.jpg)

## 免责声明:

本篇文章仅用于技术交流学习和研究的目的，严禁使用文章中的技术用于非法目的和破坏，否则造成一切后果与发表本文章的作者无关。

### 中文版本:

本免责声明旨在明确指出，本文仅为技术交流、学习和研究之用，不得将文章中的技术用于任何非法目的或破坏行为。发表本文章的作者对于任何非法使用技术或对他人或系统造成的损害概不负责。

阅读和参考本文章时，您必须明确并承诺，不会利用文章中提供的技术来实施非法活动、侵犯他人的权益或对系统进行攻击。任何使用本文中的技术所导致的任何意外、损失或损害，包括但不限于数据损失、财产损失、法律责任等问题，都与发表本文章的作者无关。

本文提供的技术信息仅供学习和参考之用，不构成任何形式的担保或保证。发表本文章的作者不对技术的准确性、有效性或适用性做任何声明或保证。

### 英文版本:

This disclaimer is intended to clearly state that this article is solely for the purpose of technical exchange, learning, and research, and the use of the techniques mentioned in the article for any illegal purposes or destructive actions is strictly prohibited. The author of this article shall not be held responsible for any consequences resulting from the misuse of the techniques mentioned.

By reading and referring to this article, you must acknowledge and commit that you will not exploit the techniques provided in the article for any illegal activities, infringement of rights of others, or attacks on systems. The author of this article bears no responsibility for any accidents, losses, or damages caused by the use of the techniques mentioned in this article, including but not limited to data loss, property damage, legal liabilities, etc.

The technical information provided in this article is for learning and reference purposes only and does not constitute any form of warranty or guarantee. The author of this article makes no representations or warranties regarding the accuracy, effectiveness, or applicability of the techniques mentioned.
