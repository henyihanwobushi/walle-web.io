title: walle-web 瓦力
---

## 瓦力 walle-web 是什么？

Walle-web 是一个开源的 [微信](https://walle-web.io) 上线部署系统。

Walle-web 的安装非常简单，因为它是一个标准的 [Composer](https://getcomposer.org/) 包。

### 环境需求

- PHP >= 5.5.9
- mcrypt 拓展
- openssl 拓展
- fileinfo 拓展（素材管理模块需要用到）

### 加入我们

你有以下两种方式加入到我们中来，为广大开发者提供更优质的免费开源的服务：

- **贡献代码**：我们 3.0 的代码都在 [overtrue/wechat](https://github.com/overtrue/wechat) ，你可以提交 PR 到任何一个项目，当然，前提是代码质量必须是 OK 的。
- **翻译或补充文档**：我们的文档在：[EasyWeChat/docs](https://github.com/easywechat/docs/)，你可以选择补充文档或者参与英文文档的翻译，目前有 `zh-cn` 与 `en` 两个分支，你可以提交对应的 PR 到目标分支参与翻译工作。

### 开始之前

本 SDK 不是一个全新再造的东西，所以我不会从 0 开始教会你开发微信，你完全有必要在使用本 SDK 前做好以下工作：

- 具备 PHP 基础知识，不要连闭包是啥都不明白，可以参考我在知乎的回答: [想要开发自己的PHP框架需要那些知识储备？](http://www.zhihu.com/question/26635323/answer/33812516)
- 熟悉 PHP 常见的知识：自动加载、composer 的使用、JSON 处理、Curl 的使用等；
- **仔细阅读并看懂** （不是**看过**，是**看明白+看完** :exclamation:） [微信官方文档](http://mp.weixin.qq.com/wiki/13/80a1a25adbc46faf2716774c423b3151.html)；
- 明白微信接口的组成，自有服务器、微信服务器、公众号（还有其它各种号）、测试号、以及通信原理（交互过程）；
- 了解基本的 HTTP 协议，Header 头、请求方式（GET\POST\PUT\PATCH\DELETE）等；
- 基本的 Debug 技能，查看 php 日志，nginx 日志等。

如果你不具备这些知识，请不要使用，因为这是开源项目，我没有义务每天帮你解决一些常识性的问题，心累。

另外你有必要看一下以下的链接：

- https://phphub.org/topics/535
- http://laravel-china.github.io/php-the-right-way/

如果你在群里问以下类似的问题，这真的是你没有做好上面的工作：

- "为啥我的不行啊，请问服务器日志怎么看啊？"
- "请问这是什么原因啊？[结果/报错截图]"
- "请问这个SDK怎么用啊？"
- "谁能告诉我这个SDK是怎么安装的啊？"
- "怎么接收用户发的消息啊？"
- "为啥我的报这个错啊：Class XXXX not found..."
- ...

我们专门针对一些容易出现的通用问题已经做了汇总： [疑难解答](http://easywechat.org/docs/troubleshooting.html) ，如果你在问题疑难解答没找到你出现的问题，那么可以在这里提问 [GitHub](https://github.com/overtrue/wechat/issues)，提问请描述清楚你用的版本，你的做法是什么，不然别人没法帮你。

最后，请 **不要在QQ单独找我提问**，除非你是发现了明显的bug。大家都要上班，都有其它事情要做，你有问题先审查代码，看文档, 再 google，然后 去群里发个问题，带上你的代码，重现流程，大家有空的会帮忙你解答。谢谢合作！:pray:


### 打赏支持

这是一个开源的项目，我们没有收费服务，你如果觉得你从中获益，简化了你的开发工作，你可以 [打赏](/donate.html) 来支持我们。
