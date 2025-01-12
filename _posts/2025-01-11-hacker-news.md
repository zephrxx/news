---
layout: page
title: 勒西科技日报 - 2025年01月11日
date: 2025-01-11 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 通过Go/TinyGo在Apple FindMy网络中追踪设备；
1. Matt Mullenweg 停用计划分叉 WordPress 的贡献者账户；
1. Marshall Uxbridge 蓝牙音箱的去智能化改造；
1. Show HN: TypeScript/React/Vue 窗口布局管理器（标签页、浮动、弹出窗口）；
1. 几乎所有二分查找和归并排序都有缺陷（2006）；

以上是今天的前五条黑科技新闻标题。

总共20条，具体内容您往下读...


![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 通过Go/TinyGo在Apple FindMy网络中追踪设备 
<small>🔗 [github.com](https://github.com/hybridgroup/go-haystack): Track your devices via Apple FindMy network in Go/TinyGo</small>


| 🔥🔥: 245 \| 💬: [67](https://news.ycombinator.com/item?id=42665367) \| 🗓️ 2025-01-11


<br />
该项目利用**OpenHaystack**和**Macless-Haystack**，通过Go/TinyGo编写的工具，帮助用户在Apple的“查找”网络中追踪个人蓝牙设备。支持多种硬件设备，如Adafruit Bluefruit、BBC Microbit等，并提供**TinyScan**本地设备扫描功能。用户需配置Apple ID和2FA，并通过Docker运行相关服务。

---

## <a name="2"></a>2. Matt Mullenweg 停用计划分叉 WordPress 的贡献者账户 
<small>🔗 [techcrunch.com](https://techcrunch.com/2025/01/11/matt-mullenweg-deactivates-wordpress-accounts-of-contributors-planning-a-fork/): Matt Mullenweg deactivates WordPress accounts of contributors planning a fork</small>


| 🔥🔥: 231 \| 💬: [96](https://news.ycombinator.com/item?id=42667766) \| 🗓️ 2025-01-11


<br />
WordPress 联合创始人兼 Automattic CEO **Matt Mullenweg** 停用了多位 WordPress.org 社区成员的账户，其中一些人正推动创建一个新的 WordPress 分叉项目。此举源于社区对 WordPress 治理的长期批评，尤其是与商业公司 **WP Engine** 的冲突。Mullenweg 表示支持分叉，但停用账户以“推动独立项目发展”。被停用账户的成员包括 **Joost de Valk** 和 **Karim Marucchi**，他们计划领导新的分叉项目。Mullenweg 还停用了其他三名曾批评 WordPress 治理的贡献者账户。

---

## <a name="3"></a>3. Marshall Uxbridge 蓝牙音箱的去智能化改造 
<small>🔗 [tomscii.sig7.se](https://tomscii.sig7.se/2025/01/De-smarting-the-Marshall-Uxbridge): De-smarting the Marshall Uxbridge</small>


| 🔥🔥: 218 \| 💬: [65](https://news.ycombinator.com/item?id=42666572) \| 🗓️ 2025-01-11


<br />
作者偶然获得两台 Marshall Uxbridge 智能音箱，决定将其改造为**高保真立体声系统**。通过移除智能模块并设计**主动滤波电路**和**线性功放**，成功将音箱转变为纯模拟输入设备，避免了蓝牙延迟和智能语音干扰。最终，音箱的音质表现令人惊艳，尤其是**立体声成像**的精准度和深度。

---

## <a name="4"></a>4. Show HN: TypeScript/React/Vue 窗口布局管理器（标签页、浮动、弹出窗口） 
<small>🔗 [github.com](https://github.com/mathuo/dockview): Show HN: TypeScript/React/Vue Window Layout Manager (Tabs, Floating, Popouts)</small>


| 🔥🔥: 196 \| 💬: [47](https://news.ycombinator.com/item?id=42666492) \| 🗓️ 2025-01-11


<br />
**dockview** 是一个**零依赖**的布局管理器，支持 **TypeScript**、**React** 和 **Vue**。它提供了标签页、分组、网格和分割视图等功能，支持拖放操作、弹出窗口和浮动分组。具备高度可定制性和主题化，支持序列化和反序列化布局管理，适用于复杂的应用场景。文档详细，测试覆盖率高，安全性强，适合需要灵活布局管理的开发者。

---

## <a name="5"></a>5. 几乎所有二分查找和归并排序都有缺陷（2006） 
<small>🔗 [research.google](https://research.google/blog/extra-extra-read-all-about-it-nearly-all-binary-searches-and-mergesorts-are-broken/): Nearly all binary searches and mergesorts are broken (2006)</small>


| 🔥🔥: 152 \| 💬: [165](https://news.ycombinator.com/item?id=42664400) \| 🗓️ 2025-01-11


<br />
2006年，Joshua Bloch指出，**二分查找**和**归并排序**等算法中存在一个长期未被发现的**溢出错误**。当数组长度超过2^30时，`(low + high) / 2`会导致整数溢出，引发数组越界。修复方法包括使用`low + ((high - low) / 2)`或位运算`(low + high) >>> 1`。这一错误提醒我们，即使是最基础的算法也可能存在隐患，编程需谨慎且持续测试。

---

## <a name="6"></a>6. PrivTracker – 面向所有人的私有BitTorrent追踪器 
<small>🔗 [privtracker.com](https://privtracker.com/): PrivTracker – Private BitTorrent tracker for everyone</small>


| 🔥🔥: 146 \| 💬: [28](https://news.ycombinator.com/item?id=42664409) \| 🗓️ 2025-01-11


<br />
PrivTracker 是一个允许用户与朋友**私密分享**种子文件的工具，不同于公共追踪器，它仅在**同一Announce URL组**内共享节点。用户只需点击按钮即可生成私有追踪器，并通过Transmission等工具创建**私有种子**，轻松与朋友分享文件。

---

## <a name="7"></a>7. Vim 的现状 
<small>🔗 [lwn.net](https://lwn.net/SubscriberLink/1002342/a8d8a17f30968b93/): The State of Vim</small>


| 🔥🔥: 145 \| 💬: [38](https://news.ycombinator.com/item?id=42665222) \| 🗓️ 2025-01-11


<br />
Vim 创始人 Bram Moolenaar 于 2023 年去世后，社区对项目的未来感到担忧。2024 年 VimConf 上，现任维护者 Christian Brabandt 介绍了 Vim 的重组计划及未来发展。**Vim 9.1** 版本已发布，包含虚拟文本、平滑滚动等改进。Brabandt 强调，Vim 目前处于维护模式，注重向后兼容性，并计划逐步淘汰过时的语言支持（如 Python 2）。社区正在努力保持项目的活力，同时继续支持慈善机构 ICCF Holland。

---

## <a name="8"></a>8. Show HN: 更好的日志服务 
<small>🔗 [txtlog.net](https://txtlog.net/): Show HN: A Better Log Service</small>


| 🔥🔥: 136 \| 💬: [82](https://news.ycombinator.com/item?id=42666139) \| 🗓️ 2025-01-11


<br />
为什么需要另一个日志服务？现有的解决方案在**性能**、**易用性**和**成本**方面存在不足。我们提出了一个新的日志服务，旨在通过**高效的数据处理**和**灵活的查询功能**，为用户提供更优质的体验。

---

## <a name="9"></a>9. 数学家Ingrid Daubechies荣获国家科学奖章 
<small>🔗 [today.duke.edu](https://today.duke.edu/2025/01/ingrid-daubechies-awarded-national-medal-science): Ingrid Daubechies Awarded National Medal of Science</small>


| 🔥🔥: 121 \| 💬: [8](https://news.ycombinator.com/item?id=42664893) \| 🗓️ 2025-01-11


<br />
数学家**Ingrid Daubechies**因其在**信号处理**领域的开创性工作，被授予2025年**国家科学奖章**。这是美国对科学家和工程师的最高荣誉。她的研究奠定了现代图像处理技术的基础，广泛应用于电影压缩等领域。Daubechies还致力于推动女性在STEM领域的参与，打破性别障碍。

---

## <a name="10"></a>10. SQLite：工作原理，Richard Hipp (2024) [视频] 
<small>🔗 [youtube.com](https://www.youtube.com/watch?v=ZSKLA81tBis): SQLite: How it works, by Richard Hipp (2024) [video]</small>


| 🔥: 85 \| 💬: [8](https://news.ycombinator.com/item?id=42665370) \| 🗓️ 2025-01-11


<br />
该视频由SQLite创始人Richard Hipp讲解，深入探讨了**SQLite**的核心机制。他介绍了**数据库引擎**的架构、**事务处理**的实现方式，以及SQLite如何通过**轻量级设计**实现高效运行。适合对数据库技术感兴趣的开发者观看。

---

## <a name="11"></a>11. 福特电动Mach-E在2024年销量超越燃油版Mustang 
<small>🔗 [electrek.co](https://electrek.co/2025/01/09/fords-mach-e-ev-outsold-gas-mustang-first-time/): Ford's electric Mach-E outsold the gas-powered Mustang in 2024</small>


| 🔥: 76 \| 💬: [66](https://news.ycombinator.com/item?id=42667902) \| 🗓️ 2025-01-11


<br />
2024年，**福特电动Mach-E**的销量首次超过了其燃油版**Mustang**，标志着电动汽车市场的进一步增长。与此同时，特斯拉推出了新款Model Y，被戏称为“复制了自己的模仿者”。这一趋势显示了电动汽车在消费者中的受欢迎程度持续上升。

---

## <a name="12"></a>12. 使用黑魔法实现快速环形缓冲区（2017） 
<small>🔗 [lo.calho.st](https://lo.calho.st/posts/black-magic-buffer/): Using black magic to make a fast circular buffer (2017)</small>


| 🔥: 68 \| 💬: [25](https://news.ycombinator.com/item?id=42664614) \| 🗓️ 2025-01-11


<br />
本文介绍了一种优化环形缓冲区的技术，通过将底层缓冲区映射到**两个连续的虚拟内存区域**，利用**内存管理单元**自动处理环绕逻辑，从而避免手动计算模运算。这种方法显著提高了读写效率，尤其是在处理跨越缓冲区边界的数据时。通过**mmap**和**memfd_create**系统调用，作者实现了这一优化，并展示了其性能优势。

---

## <a name="13"></a>13. 别再试图安排电话会议了 
<small>🔗 [matduggan.com](https://matduggan.com/stop-trying-to-schedule-a-call-with-me/): Stop Trying to Schedule a Call with Me</small>


| 🔥: 68 \| 💬: [12](https://news.ycombinator.com/item?id=42669754) \| 🗓️ 2025-01-11


<br />
作者吐槽了SaaS产品试用后的**销售骚扰**，从邮件轰炸到强制安排电话会议，再到冗长的演示和复杂的审批流程。最终，产品往往无法满足需求，而**开源工具**却提供了更好的解决方案。整个过程让人感到疲惫和无奈，最终选择放弃商业产品。

---

## <a name="14"></a>14. 穆伦维格的懦弱行为（2010年） 
<small>🔗 [kindness.is](https://kindness.is/examples/2010/mullenweg-the-coward/): Mullenweg the Coward (2010)</small>


| 🔥: 62 \| 💬: [9](https://news.ycombinator.com/item?id=42669293) \| 🗓️ 2025-01-11


<br />
2010年5月，Ben Cook发表了一篇题为《为什么Matt应该辞职》的文章，指出**Matt Mullenweg**在Automattic和WordPress基金会之间存在**利益冲突**，并建议他辞职以避免潜在问题。Mullenweg对此不满，私下联系了Cook的雇主Network Solutions，试图让他被解雇，但未成功。Cook随后公开了此事，批评Mullenweg的行为缺乏**透明度**和公正性，并揭示了他在WordPress社区中的“仁慈独裁者”形象背后的威胁与恐吓行为。

---

## <a name="15"></a>15. 摩根大通将结束30万员工的远程办公 
<small>🔗 [forbes.com](https://www.forbes.com/sites/terinaallen/2025/01/09/jpmorgan-ending-remote-work-for-300000-employees-report/): JPMorgan Reportedly Ending Remote Work for More Than 300k Employees</small>


| 🔥: 49 \| 💬: [34](https://news.ycombinator.com/item?id=42669143) \| 🗓️ 2025-01-11


<br />
摩根大通计划要求超过30万名员工每周五天返回办公室工作，结束疫情期间的混合办公政策。**CEO杰米·戴蒙**一直倡导面对面办公，认为这有助于创新、协作和员工成长。尽管远程工作在疫情期间普及，但戴蒙认为**面对面沟通**更为有效。此举反映了企业对传统办公模式的回归，但仍有其他公司提供高薪远程工作机会。

---

## <a name="16"></a>16. 1895年加利福尼亚自行车道路地图 
<small>🔗 [loc.gov](https://www.loc.gov/resource/g4361p.ct000092/?r=-0.628,0.425,1.749,0.902,0): Map of California roads for cyclers (1895)</small>


| 🔥: 45 \| 💬: [19](https://news.ycombinator.com/item?id=42667797) \| 🗓️ 2025-01-11


<br />
该地图由**George W. Blum**和**California Photo-Engraving Co.**于1895年制作，展示了加利福尼亚州的自行车道路。地图尺寸为48 x 34厘米，现藏于**美国国会图书馆地理与地图部**。该地图属于“交通与通信”类别，提供了多种数字格式供下载，包括JPEG、GIF和TIFF。地图内容不受版权限制，可用于教育和研究目的。

---

## <a name="17"></a>17. FCC提议为智能设备推出网络安全标签计划 
<small>🔗 [fcc.gov](https://www.fcc.gov/cybersecurity-certification-mark): FCC proposes cybersecurity labeling program for smart devices</small>


| 🔥: 34 \| 💬: [3](https://news.ycombinator.com/item?id=42669006) \| 🗓️ 2025-01-11


<br />
美国联邦通信委员会（FCC）提议推出**网络安全标签计划**，并设计了**U.S. Cyber Trust Mark**标志，目前正向美国专利商标局申请注册。该标志未经FCC书面许可不得使用，旨在帮助消费者识别符合网络安全标准的智能设备。

---

## <a name="18"></a>18. 为什么湾区每个活动都采用查塔姆规则？ 
<small>🔗 [sfstandard.com](https://sfstandard.com/2025/01/11/chatham-house-rule-burnout/): Chatham House Rule is suddenly everywhere in the Bay Area</small>


| 🔥: 33 \| 💬: [89](https://news.ycombinator.com/item?id=42669027) \| 🗓️ 2025-01-11


<br />
查塔姆规则（**Chatham House Rule**）源自1927年，旨在促进自由讨论，现已成为湾区各类活动的标配，从健康会议到AI沙龙，甚至私人晚宴。该规则禁止与会者透露发言者身份或分享具体信息，**虽有助于保护隐私**，但也限制了人际网络和问责。批评者认为，过度使用该规则可能导致**言论责任缺失**，甚至助长争议性观点的传播。

---

## <a name="19"></a>19. 关系衰退正在全球化 
<small>🔗 [ft.com](https://www.ft.com/content/43e2b4f6-5ab7-4c47-b9fd-d611c36dad74): The relationship recession is going global</small>


| 🔥: 32 \| 💬: [73](https://news.ycombinator.com/item?id=42665518) \| 🗓️ 2025-01-11


<br />
《金融时报》文章探讨了**关系衰退**的全球蔓延趋势。文章指出，随着经济压力和社会变化，**人际关系**和**社会联系**正在减弱，这一现象不仅限于特定地区，而是逐渐成为全球性问题。订阅服务提供了深度分析和专家观点，帮助读者理解这一复杂趋势。

---

## <a name="20"></a>20. Python 是新版的 BASIC 
<small>🔗 [log.schemescape.com](https://log.schemescape.com/posts/programming-languages/python-as-a-modern-basic.html): Python Is the New Basic</small>


| 🔥: 27 \| 💬: [63](https://news.ycombinator.com/item?id=42665441) \| 🗓️ 2025-01-11


<br />
BASIC 曾是 70-80 年代**非程序员**的首选编程语言，因其简单易用。如今，**Python** 继承了这一角色，成为**非程序员**的常用语言。尽管 Python 有语法缺陷和兼容性问题，但其**标准库丰富**、**生态广泛**，且易于上手。Python 的成功源于设计、社区和时机的结合，正如 BASIC 当年一样。

---
