# 创业失败的内幕

> 原文：<https://medium.com/swlh/inside-the-failure-of-a-startup-b4a123c962bb>

我们从一个伟大的产品中学到了什么，六个月，没有任何顾客。

![](img/33e96f63be5796aa6c6260e155f425d5.png)

Photo credit: [https://unsplash.com/@kevseto](https://unsplash.com/@kevseto)

尘埃落定，创业失败后，会有一段奇怪的自我反思期，以找出哪里出了问题。这通常是相当明显的，你想知道为什么你没有早点发现它，或者为什么你这么长时间忽视房间里的大象。我不得不提醒自己,“启动”作为一个术语是用词不当——它们应该被称为“关闭”,只是为了设定正确的期望水平。

我已经在科技创业现场呆了足够长的时间，拥有了坚强的外壳和病态的幽默感来度过这一切。即便如此，在目睹了如此多的创业失败后，即使对于一个愤世嫉俗、经验丰富的老手来说，我最近的失败仍然令人瞠目结舌。发生了什么事？

# “一个非常好的主意”

在日常工作中，我们为其他公司开发软件解决方案，同时我们也开始了这项事业。这是一个简单的想法——我们的产品让 WordPress 网站变得不可破解、可扩展并且非常快。

像许多创业想法一样，这是偶然出现在我们面前的。在每个客户项目的最后总会有一个网站，它是*总是* WordPress。客户通常有一个他们想要使用的代理或模板，我们帮助他们在某个地方建立一个服务器作为最终交付。这是最后一次冲过终点线。

如果你不知道，WordPress 是世界上大多数*网站背后过时的灾难，从安全角度来看，它是一片有毒的荒地。从 WordPress 平台内部解决这个问题，你真的无能为力，尽管大多数现有的安全和性能产品都存在于此。我们的产品采取了不同的方法，在你的 WordPress 安装周围放置一个核掩体，并单独处理网站交付。*

**更新:更多详情请见** [**建造沙堡和保护。**](https://itnext.io/building-sandcastles-and-securing-wordpress-fe59d483a22)

实现很简单。作为一家基于 AWS 的公司，我们一直使用企业级的可靠工具，因此我们使用 WAF、DDoS 和 edge 服务来完成繁重的工作，将你的定时炸弹 WordPress 服务器从互联网上完全移除。真的很简单。

WordPress 不像现代应用程序那样水平扩展，它没有真正的安全性。如果你能想象你手机上的所有应用程序都有能力接管硬件并做任何事情，这就是 WordPress 的设计——苹果和谷歌将会处理手机在任何地方爆炸起火的情况。太可怕了。我们把它作为一个安全包装器，在没有告诉任何人的情况下自动部署到客户站点，只是为了避免客户因为产品成功而被黑客攻击或网站崩溃的尴尬。

几周之内，我们就有 10 个网站在运行这个解决方案。客户很喜欢它，网站速度快得令人窒息，我们接触的每个安全专家都有点困惑，因为没有服务器可以入侵，所有经典的 WordPress 问题都得到了缓解。安装后，产品运行良好，我有一个完整的未来功能和改进的产品路线图，目标是电子商务、其他 CMS 系统和更广泛的网站生态系统。我的意思是，我真的有一个很好的计划，因为谁不希望他们的网站更快，更不受攻击呢？

到了 8 月份，我们开始在这个项目上投入更多的时间，我的合伙人制定了商业计划、上市策略、幻灯片和所有其他有趣的东西，让你成为一个合法的初创公司。

# 当你成为纸百万富翁的那一天

在很短的时间内，我们有了一个完全可用的产品，十几个网站，我的联合创始人在提高风投、天使投资人和她认识的其他商业影响者的兴趣水平方面做了惊人的工作。到 9 月底，我们收到了来自一个简单推介平台的口头投资提议，并且每隔几天就与一些重要人物会面。我的日记里写满了推介、演示和问答环节。

如果你曾在任何一家初创公司工作过，你可能会有这样的一天:估值魔法(VBM)发生了，你最终变得非常富有。那一天发生了，一位投资者随便出价 15 万美元购买一家没有收入的公司 10%的股份。这使得我的部分仅在第一轮就价值 75 万美元，我们都知道在随后的投资回合中会发生什么。

我们兴奋地开始计划精心制作的财务电子表格、公司文件和法律协议。谁知道我们第一次击球就能把它击出公园？但是每次会议都进行得很顺利——每个人都喜欢这个想法，喜欢这个解决方案，并表现出兴趣。在我见过的所有初创公司中，第一次没有人告诉我们离开办公室，或者这个想法完全是在浪费任何人的时间。似乎所有的部分都到位了。

金融产品取决于能否找到少数付费客户，这似乎是个小障碍。我们研究了竞争格局，认为大多数公司愿意每月支付 50-100 美元，购买无需配置或持续管理就能确保网站安全并永久加速的产品。

这也与关于 WordPress 黑客、重大安全漏洞和无处不在的黑客的每日新闻相吻合。每个网站对 SSL 的普遍推动，对 GDPR 及其对网站的影响的极度恐惧，以及谷歌对移动用户更快速度的推动——这些都正中我们的下怀，强调了对我们产品的需求。

# 第一个付款的顾客

我的联合创始人已经找到了一批非常合适的有意愿的目标客户。第一个是一家大型网络机构，它管理着几十个客户网站，并且在自己的客户网站上有严重的 SSL 证书安装问题。他们的首席技术官和首席执行官很喜欢这个产品演示，他们渴望尝试一下。

我提供了设置说明，只需要更改 DNS 来授权新的 SSL 证书，并将域名指向我们的基础设施。改变本身只花了几分钟，但几天后，电子邮件被忽略，电话转到语音信箱。*蟋蟀*

但不用担心——我们还有其他人。一家安全公司表现出了兴趣，他们的首席执行官对一切都说“是，是，是”，希望昨天就能让产品上线。我们匆忙准备了显示他们网站速度和安全问题的“预”报告，并发送了所需的 DNS 更改。*蟋蟀*

这种情况一直在发生。我们认为对 DNS 的修改会有一些阻力，所以我们调整了产品，以消除任何停机时间，并创建一个中转站点，让客户可以看到新的和改进的站点，以比较速度和安全性指标。*蟋蟀*

# 为什么没人接我们的电话？

10 月初开始觉得有严重的问题。尽管所有的兴趣，有前途的会议，精彩的演示和发光的速度和安全报告，没有人回来找我们。从近二十几条热门线索来看，这条路走不通。

我们经历了一个自我分析的阶段，导致了一些有问题的结论。也许是因为产品名称？也许它令人困惑，解释不清或者太复杂了？也许我们缺乏可信度？也许产品做了太多的声明，需要拆分，以便客户可以选择功能，而不是一次获得所有功能？

我们探索了每一个问题，创建了新的平台、新的登录页面、新的内容，以至于我们在任何一天提供的内容都变得令人困惑。我们终于有了一些令人信服的商业案例，在这些案例中，我们可以展示移动设备上 15 秒的页面加载时间减少到了 3 秒，或者 WordFence 攻击从每月大约 15，000 次减少到了零。还是没兴趣。

几个我认识很久的人也不再回复我了。会议总是计划在“下周”举行，或者推迟到“假期后”，我知道这是“永远不”的代名词。甚至那些最初对我表现出狂热兴趣的人也变得冷淡，很明显他们不想再听到我们的消息了。

经过几个星期的努力，我通过匿名调查联系了所有的线索，想知道为什么没有人采取行动？有人能诚实地告诉我们问题出在哪里吗？除了这个想法有多棒，它有多聪明，多棒，多先进，等等，我们还是一无所获。

# 哪天你买不起一杯咖啡

如果你曾在任何初创公司工作过，你可能有一天会意识到自己已经死了。你走着，呼吸着，环顾四周，突然发现你不再是活人了。这是一个奇怪的时刻，因为它是突然的、可怕的、悲惨的——同时也是不可避免的。

对我们来说，那一天是在 12 月初。其中一家表现出兴趣的早期公司回复了一封关于改变 DNS 的电子邮件。已经过了两个月，但现在他们准备好了。

我们已经对每月 50-100 美元失去了所有的幻想，并且正在研究每月 20 美元的业务的可行性。只需 20 美元，您甚至可以获得免费的 SSL 证书！当我们问他们愿意为这项服务支付多少钱时，他们的回答有效地结束了这项业务:

“哦，你的意思是我们要为此付钱？我们以为它是免费的。”

他们不是唯一的。我们永远无法接触到第一个付费客户，所以我们永远无法实现投资者的钱，我的百万美元估值蒸发了。虽然我可能从未真正相信它值一百万美元，但我也不认为它一文不值。

之后，风投会议开始进入一个奇怪的领域。一个人希望我们为 Magento 重写一切(同时免费修复他们自己的 WordPress 网站)，而几个人认为这“不值得投资”，因为我们只需要找到客户。

# 吸取的惨痛教训

我们的产品制造出来了，而且很有效。它解决了使用企业基础设施的 WordPress 站点的一个主要问题。它在测试版中有十几个快乐的业务，它从未失败、失败、出故障或做任何事情，除了它在盒子上说的。我会见了几位导师，看看我们到底哪里做错了。

“安全产品是不可能卖出去的，”一位曾在两家大型安全初创公司工作过的经验丰富的软件老手说。“人们不会为此付费，他们不了解这个问题，也从未想过自己会被黑客攻击。不可能的。”他短短 10 秒钟的解释反映了我们所看到的一切。

“除非是电子商务，否则没人关心速度，”另一个人说。“只有在比其他地方节省 10 倍的钱的情况下，你才能为此收费。”这再次反映了我们之前的一个问题，即如果 T2 的公司使用这种产品，他们不需要什么。

另一位导师说，“你真的应该瞄准创业公司。现有的企业永远不会改变他们正在做的事情，中小企业没有钱。把它给创业公司，看看是否有一家成功了。”当然，他是对的——我们一直看到中型公司已经根深蒂固，老派 IT 和大公司永远不会尝试任何新事物。

最终，扼杀这个想法的不是 DNS 交换机、可信度，甚至可能不是钱。事实是我发现了一个主要问题 WordPress 的速度和安全性——客户并不关心。我犯了产品管理的大罪，解决了一个没有人解决的问题。这是最难的部分，因为我很了解这个问题，而且解决方案也非常好。

幸运的是，我们没有浪费任何人的钱，没有签署办公室合同，也没有雇佣那些家庭在圣诞节前没有收入的开发人员。我们只是浪费了自己的时间和我们三个人的大约一千美元。此外，我很幸运，以前的启动经验告诉我什么时候按下终止开关。

但这次我有一个从未有过的疑惑。这个产品正在工作，我拥有我曾经合作过的最好的团队，在演示中除了积极的反馈什么也没有收到。我亲眼目睹了企业是如何每天被软件销售淹没的，他们对我们声称要解决的问题越来越麻木。市场上存在冷漠，软件的货币价值普遍贬值，尽管我们的下一个想法可能更好，但对于一个三人团队来说，这仍然是一个不可逾越的挑战吗？

现在，我们一直在思考下一个想法，并把这些经验带向前。我们正在解决一个真正的客户问题吗？这是真正的需求吗？有人会为这个解决方案买单吗？我们只能尽量避免来自善意但最终不帮忙的人的支持性评论的回音室。我们必须提醒自己，大多数初创公司都是倒闭的，但无论如何，你都必须不断尝试。

*James Beswick 是 Indevelo 的联合创始人，Inde velo 为客户构建 AWS 解决方案。*

**更新:** [**参见**](https://itnext.io/building-sandcastles-and-securing-wordpress-fe59d483a22) **。**

[![](img/308a8d84fb9b2fab43d66c117fcc4bb4.png)](https://medium.com/swlh)

## 这篇文章发表在 [The Startup](https://medium.com/swlh) 上，这是 Medium 最大的创业刊物，拥有+395，714 名读者。

## 在此订阅接收[我们的头条新闻](http://growthsupply.com/the-startup-newsletter/)。

[![](img/b0164736ea17a63403e660de5dedf91a.png)](https://medium.com/swlh)