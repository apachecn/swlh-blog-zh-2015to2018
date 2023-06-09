# 如何使用神经网络和 Google AMP 将年收入提高 97%

> 原文：<https://medium.com/swlh/how-to-increase-annual-revenue-by-97-using-neural-networks-and-google-amp-9d0bc70b8f66>

> 任何基于看似无关紧要的技术解决方案的实验对公司来说都是一种风险，因此在大多数情况下，许多想法仍然停留在纸上。哦，你知道我的意思。

![](img/97cdd1d64ea276f5706c3ca48c7a9fe0.png)

[Bash! Today](https://bash.today) — is the leading markeplace in Russia for booking event venues.

我们，在[狂欢！今天的](https://bash.today)(俄罗斯预订活动场地的第一大市场)，一直坚持一个简单的理念:*实验应该是我们项目*的一部分，没有它们我们就无法进步。它得到了回报:技术 AMP(加速移动页面)使我们的流量成倍增长，并且由于神经网络的实施，我们能够优化销售部门的工作。

由于 2017 年，我们在俄罗斯创意空间市场牢牢占据领先地位，并准备在英国推出。但并不是一切都开始得如此顺利。

**这一切是如何开始的**

![](img/f9dc5335615663db7e0c40fd4359b0d7.png)

[Bash! Today](https://bash.today) — is the leading markeplace in Russia for booking event venues.

2016 年年中，我们的 marketplace 在管理上相当复杂，所有代码都是使用过时的软件自己动手编写的，该网站甚至不适合移动设备，在良好的互联网连接下加载超过 8 秒钟。任何实验的引入也需要大量的时间。我们理解任务的范围，但也有困难。

我们在 2017 年初推出了新版本。代码从零开始重写，设计，结构改变，我们转移到一个新的服务器。粗略地说，旧系统没有留下一个字节，网站开始加载速度快了大约 12 倍。

当时我们的收入是 SEO 流量的 90%，所以最主要的风险是在搜索中的位置流失。我们仔细研究了预订请求的结构，并开发了一个 301 重定向系统，这样我们的客户通过打开旧的链接，就可以进入新网站的正确页面。然而，风险是严重的，因为那时和现在一样，我们没有投资营销。预计在我们开始失去流量的情况下，我们会增加预订的转化率。

**但是一切都出错了**

一如既往，事实证明略有不同。转换完全没有改变，并且位置在整整 24 小时后回到它们先前的位置。事情的这种转变完全不适合我们。

> 如果没有对用户行为模式的深入分析，技术是没有用的。

对于商业来说，15 秒或 0.5 秒内加载你的网站并不重要。搜索算法的多年发展导致了这样一个事实，即该网站获得了足够多的有明确需求的目标客户，这些客户会更快地流向你的竞争对手，因为那里便宜 20 美分。反过来，对于搜索引擎来说，客户的目标行动比你网站的表现更重要。

我们的情况变得更糟，因为我们必须建立一个严肃的生态系统，其中包括空间的所有者，他们仍然必须接收和处理预订请求。对他们来说，我们是新兴创意空间市场中为数不多的客户供应商之一。

**问题解决方案**

![](img/a9843a74762101fb84871fcd323c2c11.png)

我们迫切需要提高流量，并证明新网站的成本是合理的。首先，我们决定顺应潮流——*加速移动页面(谷歌)。*

这个决定是有风险的，因为我们不得不牺牲页面的动态性，因为你不能在没有严重失真的情况下组织一个照片库或一个带有选择日期选项的迷你日历。我们知道 AMP 将会替换 Google 搜索中的原始版本，但是仍然决定进行这个实验。几天之内，我们就复制了我们市场的所有页面。

因此，我们所有的市场都是专门“输入”的，用户离开请求的决定被转移到其他更复杂的页面。几天后，我们开始在谷歌迅速发展，在关键请求上超过了我们的主要竞争对手。

接下来的几个月，我们一头扎进指标中，试图完善我们的市场，研究用户在网站上的行为。我们积极地进行 A/B 测试，几乎每天都用不同的实验来发布新的版本。

> 结果是 SEO 流量 13% 的*转化，比之前翻了几倍。*

**好，我们有了流量和转化，接下来呢？**

当然，一切都不是那么顺利。我们不知道收到预订请求后发生了什么。我们从每笔交易中赚取佣金，所以对我们来说，场地所有者处理用户请求的方法极其重要。由于我们这个小团队的注意力集中在改善客户服务上，负责与客户打交道的网站经理开始工作得越来越差，我们的利润开始急剧下降，尽管请求的数量在上升。

> 我们决定在该系统上收集深入的统计数据，该系统直观地显示了几乎所有指标，包括总体指标和每个活动场馆的具体指标。

例如，我们看到经理对预订请求的回应率，或者预订请求被拒绝的百分比。除了统计数据的引入为我们提供了许多问题的答案这一事实之外，我们还认为与站点管理者本身共享一些功能是一个好主意。

这一功能成为付费专业账户的基础，为货币化开辟了额外的渠道。

如果这些网站不回电或者回电太晚，它们的评级会自动降低。当然，我们的主要胜利是经理之间的竞争，他们现在为每个预订请求而斗争并立即处理，因为这直接取决于他们在市场中的地位。

**神经网络介绍**

我们没有时间庆祝成功，因为又出现了一个问题。这些网站开始大规模欺骗我们，接受现金支付，绕过服务。他们中的许多人尽可能机智地做到了这一点，因为他们知道我们正在密切关注这些指标。

> 我们引入了一个秘密客户系统——我们的员工留下了预订请求，并经历了从预订阁楼到录制观看的整个过程。

一些不是特别有创造力的经理，立刻离职，向我们的员工支付现金。这样的网站，当然，立即被封锁了很长一段时间，并收到了罚款。但在全球范围内，我们无法解决这个问题，因为不清楚该打电话给谁，该检查谁，因为我们的网站数据库每天都在增长。

![](img/15374c3c014ca6486f4bbb8a406222ee.png)

English version of [Bash! Today](http://welcome.bash.today/english_request)

这里有必要深入一点这个理论，并回答这个问题，我们的大脑到底是如何做决定的。最有可能的是，首先我们以一些指标为基础，寻找它们之间的依赖关系并得出结论。如果依赖性不明显，问题就进入了人工智能领域。

> 当然，我们负担不起聘请人工智能专家并在这项任务上花费大量时间，所以我们必须用临时工具来应对。

首先，我们收集了几个指标，在决定是否需要额外的现场验证时，我们首先检查了这些指标。这当然包括收入、反馈、对预订请求的反应速度、受欢迎程度以及其他一些因素。

然后，我们选择了一个大名单上的网站被发现欺骗。由此我们获得了训练神经网络的第一批数据。欺诈的主要模式，当然，已经成为与系统和低收入的典范工作。奇怪的是，当经理在 10 分钟后给客户回电，收到数百个预订请求，90%变成拒绝，考虑到我们几乎所有的客户都是针对他的网站，无论是 loft，工作室还是培训大厅。

PHP 语言很少被用来解决这样的问题，但是只要有强烈的愿望，工具总是可以找到的。有许多简单、免费、可免费使用的库，对大多数任务都是详尽的，包括我们的。算法在一个晚上就实现了。我们得到了经理的分类名单。

> 该算法分析了他们的行为，并以百分比估计了欺诈的可能性。

甚至他们可能欺骗我们的百分比。每天都有一份经理名单清晰地展示出来，我们的经理会关注这份名单。如果欺骗被证实，那么这个经理的地点(页面)以及他们的参数进入神经网络的训练数据，神经网络每次都更准确、更精确地工作，将我们的员工从日常工作中解放出来。

![](img/2940f5354777d7e44f919700238ac649.png)

Page of a [venue](https://bash.today/platforms/928) on Bash! Today marketplace

**结果和计划**

现在，我们的服务几乎完全离线工作，让团队专注于投资问题和进入国外市场。

在实施了一系列技术解决方案后，我们取得了巨大的成果。但我们也相信，这在很大程度上取决于目标受众和技术实现的方式。有时候最好的解决方案是回滚到最便宜的单表单登陆，有时候让自己沉浸在用户行为的度量中是有意义的。

> 但是你不应该依赖别人的统计数据来做决定:*网站加速并不总是意味着转化率的增加。*

我们收集了几条建议，供那些准备尝试自动化成为科技公司的人参考。

**1。研究客户需求的层次。**

评估你的客户有多需要你提供的产品或服务。如果这是某种长期的观点，那么网站客户端的内部优化是我最不会想到的事情。

**2。试着确定你的客户为什么去找竞争对手。**

在这里，了解你的目标受众的导向是很重要的。在俄罗斯，这种方案通常适用于复制竞争对手的商业模式，但价格更低的情况。

**3。准确估计自己的实力。**

在 IT 市场上，现在质量专家非常缺乏。实践表明，把一个公司带到一个新的技术水平的过程可以由单位来完成。

**4。相信你的团队。**

我们总是试着和有相似精神的人一起工作，我们从不限制一个人，我们不强迫他进入通常的日程。有时候人的素质会掩盖职业上的短板。*可能是人们为了那种生活方式而来到搜索中的创业公司？*

在任何工作中，顾客的意见和执行者的意见不一致是经常发生的情况。成功决定了团队如何处理。

*更多故事接踵而至！*

*作者:亚历山大·布加耶夫，埃菲姆·科洛德金*

![](img/731acf26f5d44fdc58d99a6388fe935d.png)

## 这个故事发表在 [The Startup](https://medium.com/swlh) 上，这是 Medium 最大的企业家出版物，拥有 277，994+人。

## 在这里订阅接收[我们的头条新闻](http://growthsupply.com/the-startup-newsletter/)。

![](img/731acf26f5d44fdc58d99a6388fe935d.png)