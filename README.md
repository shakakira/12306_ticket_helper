12306.CN 订票助手
===================

这是一个用于辅助在[12306.CN]上订票的Chrome&amp;Firefox脚本。



功能
---------------------

这是一个可以运行在**[遨游3]**、**[Chrome]**、**[猎豹]**或**[Firefox]**浏览器上的脚本扩展，可以帮助您在 [12306.CN](https://dynamic.12306.cn/otsweb/) 购买火车票（或抢火车票？），反正就是偷懒呗。
    

**目前已经实现的功能包括**：

*	记录登录的用户名和密码，在打开登录页面后自动填写；
*	自动登录，遇到人过多或繁忙的时候自动重试，直到登录成功（有点儿抢线的味道）；
*	自动记录查询信息，一次查询线路后下次再查询自动填入；
*	自动刷新查询，当没有需要的车次时，自动重新刷新；
*	在[Chrome]/[遨游3]/[猎豹]下，查票和登录有右下角提示和声音提示；[Firefox]下暂不支持声音提示，但有桌面弹窗提示。
*	自动提交订单，直到订单成功
*	查询失败时自动刷新
*	预定失败时自动重新预定
*	禁用查询缓存
*	查询界面参数和设置自动保存
*	支持过滤无法预定车次
*	支持过滤无需要席别车次
*	现在系统已禁止验证码自动跳过，所以当出现验证码错误时，系统将会自动刷新验证码并自动定位到验证码输入框中并请求输入验证码，输入满四位的时候系统将会自动重新提交。


安装需求
---------------------

目前支持**[Chrome]**（含RC、Beta以及每夜版），**[Firefox]**（需要Scriptish扩展支持，使用了新的API所以GreaseMonkey不支持），**[遨游3]**（**需要使用高速模式，不过没用的话也没关系，脚本会提示你用高速模式的**），**[猎豹]浏览器**。

**提示**：如果您不是很熟**[Firefox]**或**[Chrome]**浏览器，那么您在付款时可能会遇到问题。**此时强烈建议您使用[遨游3]**！

####[遨游3]下安装

[遨游3] 请至官方的扩展库中安装，请 **[点击这里转到扩展页面](http://extension.maxthon.cn/detail/index.php?view_id=1339)**。

####在Chrome/[猎豹]上安装
[Chrome]下可以直接安装。直接打开 [助手主页](http://www.fishlee.net/soft/44/)，在**下载**一节中点击**通用版本**后（如果您实在木有找到，也可以直接[点击这里安装](http://www.fishlee.net/Service/Download.ashx/44/47/12306_ticket_helper.user.js)），Chrome将会在浏览器下方的下载区域通知进行安装：

![Chrome安装提示1](https://github.com/iccfish/12306_ticket_helper/raw/master/images/installation/chrome_1.png)

点击『继续』后，在弹出的对话框中继续点击『安装』。安装完成后即可。

![Chrome安装提示2](https://github.com/iccfish/12306_ticket_helper/raw/master/images/installation/chrome_2.png)


如果您未能看到安装提示，而是提示了下载或其它内容，请确认您的浏览器版本较新。

####在Firefox上安装
在[Firefox]上运行需要**Scriptish**扩展提供支持。**请注意，由于使用了Scriptish提供的新语法，因此_GreaseMonkey_扩展是不支持的**。

* 如果您尚未给[Firefox]安装Scriptish扩展，请[在此安装](https://addons.mozilla.org/zh-CN/firefox/addon/scriptish/)；
* 打开 [助手主页](http://www.fishlee.net/soft/44/)，在**下载**一节中点击**通用版本**后（如果您实在木有找到，也可以直接[点击这里安装](http://www.fishlee.net/Service/Download.ashx/44/47/12306_ticket_helper.user.js)）
* 正常情况下，Scriptish会弹出下列的安装提示，请点击『安装』继续；如果没有这样的提示框而是看到了下载或一堆『乱码』，那么请检查是否成功安装了Scriptish扩展。


提醒
---------------------

由于各大网银都不支持Firefox/Chrome支付，因此请务必在订票前做好支付的准备措施。
这里推荐使用银联在线支付，请开通银联后绑定快捷支付，这样在Firefox和Chrome下都可以顺利付款。
也可以使用招行的手机银行进行支付。


更新历史
----------------------

** 版本 4.2.5 原作者版本 **
* 移除自动提交 (验证码不可提前输入)" *
* 修正加载联系人 *

**我自己的更新 src 目录下**

**4.2.2.1**
* TDB 又修改了获取联系人的方式. 真是蛋疼. 脸蛋疼 * 

官方网站
---------------------

* [官方发布主页](http://www.fishlee.net/soft/44/)
* [作者的腾讯微博](http://t.qq.com/ccfish)
* [项目主页@GitHub](https://github.com/iccfish/12306_ticket_helper)

相关资料
---------------------

* 感谢所有开发过相关脚本，以及作出贡献的前人们。


[遨游3]: http://www.maxthon.cn/mx3/
[软件主页]: http://www.fishlee.net/soft/44/
[腾讯微博]: http://t.qq.com/ccfish/
[木鱼]: http://www.fishlee.net/ "木鱼的软件主页"
[12306.CN]: http://dynamic.12306.cn/otsweb/ "12306.CN 购票网站"
[Chrome]: https://www.google.com/chrome/ "Google Chrome"
[Firefox]: http://www.mozilla.org/en-US/firefox/all.html "Firefox"
[猎豹]: http://www.liebao.cn/ "猎豹浏览器"
