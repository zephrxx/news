---
layout: page
title: 勒西科技日报 - 2025年02月17日
date: 2025-02-17 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. X用户无法发布“Signal.me”链接；
1. searchcode.com的SQLite数据库可能比你的大6TB；
1. 调试无法调试的应用；
1. 多伦多机场发生飞机坠毁事件，航班翻转；
1. 观察R1的“思考”过程：动画化思维链；

以上是今天的前五条黑科技新闻标题。

总共25条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. X用户无法发布“Signal.me”链接 
<small>🔗 [disruptionist.com](https://www.disruptionist.com/p/elon-musks-x-blocks-links-to-signal): X users are unable to post “Signal.me” links</small>


| 🔥🔥: 740 \| 💬: [668](https://news.ycombinator.com/item?id=43076710) \| 🗓️ 2025-02-17


<br />
埃隆·马斯克的社交媒体平台X目前禁止用户发布“Signal.me”链接，这是一个用于加密通讯服务Signal的URL。用户在尝试发布时会收到各种错误提示，表明该链接被识别为潜在的有害内容。X不仅阻止了新链接的发布，甚至连已有的“Signal.me”链接也无法点击，用户会看到安全警告。尽管如此，用户仍可在X上发布他们的Signal用户名。Signal作为一种安全的通讯工具，尤其在最近的政府举报中显得尤为重要。

---

## <a name="2"></a>2. searchcode.com的SQLite数据库可能比你的大6TB 
<small>🔗 [boyter.org](https://boyter.org/posts/searchcode-bigger-sqlite-than-you/): Searchcode.com’s SQLite database is probably 6 terabytes bigger than yours</small>


| 🔥🔥: 224 \| 💬: [91](https://news.ycombinator.com/item?id=43076785) \| 🗓️ 2025-02-17


<br />
searchcode.com的SQLite数据库是全球最大的公共网站数据库之一，大小达到**6.4TB**。该网站用于搜索源代码，整合了多个平台的数据。为了减少依赖，作者选择了SQLite，尽管在迁移过程中遇到了一些挑战，如数据压缩和性能优化。最终，迁移成功，网站性能显著提升，作者计划进一步扩展其功能和盈利能力。

---

## <a name="3"></a>3. 调试无法调试的应用 
<small>🔗 [bryce.co](https://bryce.co/undebuggable/): Debugging an Undebuggable App</small>


| 🔥🔥: 213 \| 💬: [34](https://news.ycombinator.com/item?id=43081713) \| 🗓️ 2025-02-17


<br />
最近我遇到了一款应用，它通过多种方式阻止调试器附加，包括**早期退出**和**越狱检测**，甚至在越狱设备上会导致手机崩溃。这种保护机制使得调试和修改应用变得困难，但我们可以通过分析其使用的**ptrace**函数来绕过这些限制。通过设置断点和使用汇编代码，我们可以成功附加调试器并探索应用的内部工作原理。

---

## <a name="4"></a>4. 多伦多机场发生飞机坠毁事件，航班翻转 
<small>🔗 [cbc.ca](https://www.cbc.ca/news/canada/toronto/toronto-pearson-overturned-airplane-1.7461227): Plane crashes, overturns during landing at Toronto airport</small>


| 🔥🔥: 173 \| 💬: [238](https://news.ycombinator.com/item?id=43083012) \| 🗓️ 2025-02-17


<br />
在多伦多皮尔逊机场，一架来自明尼阿波利斯的**达美航空**飞机在降落时发生**坠毁并翻转**，导致8人受伤，其中3人伤势严重。机场已关闭跑道，所有乘客和机组人员均已确认安全。联邦运输部长表示正在密切关注此事件。

---

## <a name="5"></a>5. 观察R1的“思考”过程：动画化思维链 
<small>🔗 [github.com](https://github.com/dhealy05/frames_of_mind): Watch R1 "think" with animated chains of thought</small>


| 🔥🔥: 169 \| 💬: [56](https://news.ycombinator.com/item?id=43080531) \| 🗓️ 2025-02-17


<br />
通过将R1的思维过程可视化，我们可以**保存思维链**为文本，使用OpenAI API将其转换为**嵌入**，并利用t-SNE进行顺序绘图。示例中，R1回答“描述自行车如何工作”时，展示了思维的不同阶段，包括**搜索**、**思考**和**总结**。通过分析连续步骤的余弦相似度，我们能够观察到思维跳跃的大小变化。使用的提示包括如何设计新交通工具、解释秋天叶子变色的原因等。数据和代码可在指定位置获取。

---

## <a name="6"></a>6. 在PostgreSQL中表示图形数据 
<small>🔗 [richard-towers.com](https://www.richard-towers.com/2025/02/16/representing-graphs-in-postgres.html): Representing Graphs in PostgreSQL</small>


| 🔥🔥: 168 \| 💬: [68](https://news.ycombinator.com/item?id=43078100) \| 🗓️ 2025-02-17


<br />
在PostgreSQL中，可以通过两个表来表示图形数据，例如社交网络。`nodes`表存储节点信息，`edges`表存储连接关系。通过简单的查询，可以找到父母和朋友的关系，使用**递归CTE**可以灵活地查询任意层级的关系。这种方法允许通过参数化的方式传递根节点和路径，从而提高查询的灵活性和可重用性。

---

## <a name="7"></a>7. 无DRM电子书店列表 
<small>🔗 [libreture.com](https://libreture.com/bookshops/): List of DRM-Free Bookshops</small>


| 🔥🔥: 161 \| 💬: [38](https://news.ycombinator.com/item?id=43083772) \| 🗓️ 2025-02-17


<br />
这篇文章介绍了多个提供**无DRM电子书**的书店，强调了读者对这些书籍的所有权。书店包括**Clarkesworld Magazine**，以其获奖的科幻和奇幻作品而闻名；**Honford Star**，专注于东亚文学的翻译；以及**Roman Labs**，提供独特的数字漫画。其他书店如**University of Wales Press**和**Twisted Ink Magazine**也在推动开放获取和多样化文学方面发挥着重要作用。

---

## <a name="8"></a>8. Espargos：基于ESP32的WiFi传感阵列 
<small>🔗 [espargos.net](https://espargos.net/): Espargos: ESP32-based WiFi sensing array</small>


| 🔥🔥: 140 \| 💬: [23](https://news.ycombinator.com/item?id=43079023) \| 🗓️ 2025-02-17


<br />
ESPARGOS是一个**相位相干的ESP32天线阵列**，旨在简化WiFi传感应用的开发与部署。它实时提供**通道状态信息（CSI）**，并支持高达40 MHz的带宽。通过以太网供电和控制，用户可以快速配置和使用ESPARGOS。配套的**pyespargos**库使得多设备控制变得简单，提供多种演示应用，如角度到达估计和室内定位。虽然硬件设计和固件尚未开源，但相关库和演示应用是自由软件。

---

## <a name="9"></a>9. 隐私并未消亡：警惕全有或全无的心态 
<small>🔗 [privacyguides.org](https://www.privacyguides.org/articles/2025/02/17/privacy-is-not-dead/): Privacy Is Not Dead: Beware the All-or-Nothing Mindset</small>


| 🔥🔥: 134 \| 💬: [34](https://news.ycombinator.com/item?id=43083151) \| 🗓️ 2025-02-17


<br />
在隐私保护的讨论中，存在两种有害的心态：**隐私已死**的想法和**完美隐私**的追求。前者导致人们放弃努力，后者则使人们对不完美的隐私工具感到失望。我们应当庆祝每一个小进步，鼓励他人逐步改善隐私，而不是批评他们的选择。隐私不仅是工具，更是一种文化，需通过积极的态度和支持来共同建设。每一个小胜利都是向更好隐私实践迈出的重要一步。

---

## <a name="10"></a>10. Mistral Saba：区域语言模型的创新 
<small>🔗 [mistral.ai](https://mistral.ai/en/news/mistral-saba): Mistral Saba</small>


| 🔥🔥: 132 \| 💬: [19](https://news.ycombinator.com/item?id=43079046) \| 🗓️ 2025-02-17


<br />
Mistral Saba是首个专为中东和南亚地区定制的**24B参数模型**，旨在提供更准确、快速的响应，超越五倍于其规模的通用模型。该模型支持**阿拉伯语**及多种印度语言，特别是南印度语言如泰米尔语和马拉雅拉姆语，适用于虚拟助手、领域专精和文化内容创作等多种场景。Mistral Saba不仅能在本地安全环境中部署，还能通过API快速集成，满足客户对地方文化和语言的需求。

---

## <a name="11"></a>11. C++ 线程局部存储性能分析 
<small>🔗 [yosefk.com](https://yosefk.com/blog/cxx-thread-local-storage-performance.html): 0+0 > 0: C++ thread-local storage performance</small>


| 🔥🔥: 130 \| 💬: [75](https://news.ycombinator.com/item?id=43077675) \| 🗓️ 2025-02-17


<br />
本文探讨了如何确保对 **线程局部存储** (TLS) 的访问速度。尽管 TLS 语法简单，但其背后可能隐藏着较高的开销。通过分析不同情况下的汇编代码，作者揭示了在共享库和构造函数中使用 TLS 时的性能问题，强调了 **初始化开销** 和 **函数调用** 的影响。作者提出，尽管 TLS 提供了便利，但在某些情况下，性能可能不如预期，尤其是在多线程环境中。

---

## <a name="12"></a>12. 警方逮捕与多起谋杀案相关的“Zizian”邪教头目 
<small>🔗 [pressdemocrat.com](https://www.pressdemocrat.com/article/trending/police-arrest-apparent-leader-of-cultlike-zizian-group-linked-to-multiple/): Police arrest apparent leader of cultlike 'Zizian' group linked to killings</small>


| 🔥🔥: 124 \| 💬: [88](https://news.ycombinator.com/item?id=43083976) \| 🗓️ 2025-02-17


<br />
美国马里兰州警方逮捕了邪教组织“Zizians”的头目**杰克·拉索塔**及另一名成员**米歇尔·扎伊科**，两人面临多项指控，包括持有手枪和妨碍执法。该组织与多起谋杀案有关，包括1月在佛蒙特州杀害边境巡逻员**大卫·马兰**的事件。拉索塔在网上发布过极端思想的博客，涉及反理性主义和人工智能等话题。

---

## <a name="13"></a>13. 大卫·林奇的《绝地复仇》 
<small>🔗 [benningtonreview.org](https://www.benningtonreview.org/adam-golaski): On David Lynch's Revenge of the Jedi</small>


| 🔥🔥: 123 \| 💬: [31](https://news.ycombinator.com/item?id=43084145) \| 🗓️ 2025-02-17


<br />
文章回顾了大卫·林奇在1981年被乔治·卢卡斯考虑为《绝地复仇》的导演的背景。尽管林奇对该项目表示兴趣，但最终选择了执导《沙丘》。他认为《星球大战》是卢卡斯的作品，自己不适合。文章探讨了林奇的独特风格与《星球大战》的潜在融合，以及其他导演的可能性。

---

## <a name="14"></a>14. NLRB代理总 Counsel 撤销非竞争劳动政策 
<small>🔗 [natlawreview.com](https://natlawreview.com/article/nlrb-acting-general-counsel-rescinds-non-compete-labor-policy): NLRB acting general counsel rescinds non-compete labor policy</small>


| 🔥🔥: 122 \| 💬: [65](https://news.ycombinator.com/item?id=43083295) \| 🗓️ 2025-02-17


<br />
2025年2月14日，NLRB代理总 Counsel 威廉·B·考文撤销了前任总 Counsel 詹妮弗·阿布鲁佐关于**非竞争协议**和**停留或支付协议**的两份备忘录。这一决定标志着对雇主使用限制性契约的法律风险框架的重大变化，允许雇主在更少法律审查的情况下实施这些协议。然而，雇主仍需遵循州法律，并谨慎考虑可能的风险。

---

## <a name="15"></a>15. 开源项目可以出售SBOM片段 
<small>🔗 [thomas-huehn.com](https://www.thomas-huehn.com/open-source-projects-could-sell-sbom-fragments/): Open source projects could sell SBOM fragments</small>


| 🔥: 91 \| 💬: [51](https://news.ycombinator.com/item?id=43080378) \| 🗓️ 2025-02-17


<br />
开源项目可能通过出售**SBOM片段**来解决公司在扫描源文件以获取许可信息时的高成本和低效率问题。像OSSelot和ClearlyDefined这样的项目可以提供最新的SBOM信息，用户只需在GitHub上赞助即可获得这些信息，避免自己进行繁琐的扫描工作。这种方式不仅节省了时间，还能确保获取准确的**许可信息**。

---

## <a name="16"></a>16. hk：全新的 Git 钩子管理工具 
<small>🔗 [hk.jdx.dev](https://hk.jdx.dev/about.html): Hk, a new Git hook manager</small>


| 🔥: 91 \| 💬: [68](https://news.ycombinator.com/item?id=43080535) \| 🗓️ 2025-02-17


<br />
hk 是由 @jdx 开发的，旨在提升 **性能** 和 **灵活性**。它为用户提供了比 mise 更强大的功能，如仅在特定文件更改时运行任务。hk 采用 Rust 编写，速度更快，并且通过 pkl 文件配置，简化了插件管理。与 lefthook 和 pre-commit 相比，hk 在并行执行和配置方面具有优势。项目仍在实验阶段，欢迎贡献。

---

## <a name="17"></a>17. 在浏览器中使用WebAssembly运行Ruby on Rails 
<small>🔗 [web.dev](https://web.dev/blog/ruby-on-rails-on-webassembly): Run Ruby on Rails in the browser using WebAssembly</small>


| 🔥: 85 \| 💬: [24](https://news.ycombinator.com/item?id=43079791) \| 🗓️ 2025-02-17


<br />
想象一下，在浏览器中运行一个完整的博客应用程序，不需要服务器或云，只需你和WebAssembly。Vladimir Dementyev分享了如何在15分钟内将Ruby on Rails应用程序“wasmify”，并在浏览器中运行。通过WebAssembly，Ruby和Rails可以在本地运行，打破了传统Web开发的界限。借助`wasmify-rails`库，开发者可以轻松将Rails应用打包为Wasm模块，并通过服务工作者处理HTTP请求，实现了在浏览器中运行全栈应用的可能性。这一技术进步让开发者能够在本地环境中体验Rails的强大功能，仿佛魔法般的体验。

---

## <a name="18"></a>18. 谁雕刻了南美洲神秘的古代隧道？ 
<small>🔗 [clp.unesp.br](https://www.clp.unesp.br/Modulos/Noticias/401/paleoburrows-nature-2025.pdf): Who carved South America's mysterious ancient tunnels? [pdf]</small>


| 🔥: 78 \| 💬: [36](https://news.ycombinator.com/item?id=43082287) \| 🗓️ 2025-02-17


<br />
南美洲的古代隧道引发了广泛的好奇与研究，至今仍未有确凿的答案。考古学家们对这些隧道的起源、用途及其建造者进行了深入探讨，认为它们可能与古代文明的宗教、贸易或防御系统有关。这些隧道的复杂结构和广泛分布表明，**古代文明**在工程技术方面具有相当高的水平，可能反映了当时社会的组织能力和文化背景。

---

## <a name="19"></a>19. NES86 – NES上的IBM PC模拟器 
<small>🔗 [github.com](https://github.com/decrazyo/nes86): NES86 – IBM PC Emulator for the NES</small>


| 🔥: 77 \| 💬: [20](https://news.ycombinator.com/item?id=43082739) \| 🗓️ 2025-02-17


<br />
NES86是一个为NES设计的IBM PC模拟器，旨在模拟Intel 8086处理器及相关硬件，以运行**嵌入式Linux内核子集（ELKS）**及其他简单的x86软件。用户可以通过下载NES86和ELKS的ROM或从源代码构建来运行该模拟器。尽管NES86的映射配置理论上有效，但大多数模拟器和闪存卡并不支持。项目欢迎贡献和移植，详细的构建步骤和依赖项也在文档中提供。

---

## <a name="20"></a>20. 学习发生在优化理解而非胜利的环境中 
<small>🔗 [joanwestenberg.com](https://www.joanwestenberg.com/you-will-never-win-an-argument-on-the-internet-heres-why/): Learning happens in environments optimized for understanding, not winning</small>


| 🔥: 68 \| 💬: [24](https://news.ycombinator.com/item?id=43078701) \| 🗓️ 2025-02-17


<br />
互联网本应促进人类理解，但如今的在线辩论却让我们变得愚蠢。社交媒体算法奖励冲突而非清晰，导致我们在争论中追求胜利而非学习。我们需要通过**深度阅读**、**写作思考**和**控制环境**来恢复真正的讨论。逃离这种有害的在线辩论，寻找更好的学习空间，才能真正提升我们的思维能力。

---

## <a name="21"></a>21. 阿根廷总统因加密货币崩盘面临弹劾呼声 
<small>🔗 [bbc.com](https://www.bbc.com/news/articles/cp9x9j89evxo): Argentina president faces impeachment calls over crypto crash</small>


| 🔥: 66 \| 💬: [25](https://news.ycombinator.com/item?id=43083886) \| 🗓️ 2025-02-17


<br />
阿根廷总统**哈维尔·米莱**因在社交媒体上推广加密货币而面临弹劾和法律诉讼。他在推特上发布了关于$LIBRA币的信息，导致其价格暴涨后迅速下跌，投资者损失惨重。反对派计划启动弹劾程序，并指控米莱实施**欺诈**，称其行为类似于“**拉地毯**”骗局。尽管总统办公室表示米莱与该币的开发无关，并将进行调查，但反对派已称其为“前所未有的丑闻”。

---

## <a name="22"></a>22. ChatGPT自动补全的用户体验设计是否糟糕？ 
<small>🔗 [honzabe.com](https://honzabe.com/blog/posts/chatgpt-autocomplete-bad-ux-ui/): Is ChatGPT autocomplete bad UX/UI?</small>


| 🔥: 65 \| 💬: [55](https://news.ycombinator.com/item?id=43076418) \| 🗓️ 2025-02-17


<br />
作者对ChatGPT的**自动补全功能**表示困惑，认为其在聊天中的效果远不如在搜索中。尽管开发者可能有其理由，但在聊天时，用户的思维过程更像是**即兴对话**，而不是明确的搜索意图。作者指出，ChatGPT的自动补全常常插入与用户意图无关的内容，导致思维被打断，令人感到**烦恼**。这样的体验让人怀疑，是否有其他用户会觉得这种功能有用。

---

## <a name="23"></a>23. R.E.M.如何走向主流 
<small>🔗 [yalereview.org](https://yalereview.org/article/tavakoli-rem-peter-ames-carlin): What happened when REM went mainstream</small>


| 🔥: 63 \| 💬: [74](https://news.ycombinator.com/item?id=43081929) \| 🗓️ 2025-02-17


<br />
R.E.M.从一个**独立音乐**的代表，逐渐成为了主流文化的象征。尽管他们的音乐最初与当时流行的**大牌摇滚**和朋克风格截然不同，但他们凭借独特的声音和对创作的坚持，成功吸引了广泛的听众。随着时间的推移，他们从小型独立厂牌I.R.S.转向了大牌Warner Bros.，并在1991年发布的《Out of Time》进一步巩固了他们的地位。R.E.M.的成功不仅改变了他们的音乐轨迹，也推动了**另类音乐**的商业化，使其从大学电台走向了更广泛的听众。

---

## <a name="24"></a>24. 卡尔托费尔斯 – 细胞自动机、统计、32位RISC-V 
<small>🔗 [pwy.io](https://pwy.io/posts/kartoffels-v0.7/): Show HN: Kartoffels – Cellular Automata, Statistics, 32-bit RISC-V</small>


| 🔥: 54 \| 💬: [3](https://news.ycombinator.com/item?id=43080858) \| 🗓️ 2025-02-17


<br />
卡尔托费尔斯 v0.7 发布，新增了 **细胞自动机** 世界生成和 **统计** 功能。游戏中玩家需为土豆实现固件，生成的洞穴地图通过白噪声和细胞自动机生成，避免孤立洞穴。游戏引擎现支持 **32位RISC-V** 架构，优化了内存使用和指令集，重置了服务器并清理了所有上传的机器人。界面也进行了改进，支持键盘操作，玩家可在线或本地运行游戏。

---

## <a name="25"></a>25. 开源维护者面临压力 
<small>🔗 [theregister.com](https://www.theregister.com/2025/02/16/open_source_maintainers_state_of_open/): Open source maintainers are feeling the squeeze</small>


| 🔥: 53 \| 💬: [44](https://news.ycombinator.com/item?id=43077833) \| 🗓️ 2025-02-17


<br />
开源维护者的困境日益严重，尤其是在2025年开源大会上，许多技术巨头和志愿者都表达了这一问题。维护者们常常感到**过度工作**、**缺乏支持**，并受到用户的**虐待**。例如，Asahi Linux项目的负责人因开发者疲惫和用户要求过高而辞职。调查显示，约60%的维护者考虑退出，许多项目由少数人支持，面临持续的压力。解决方案并不简单，虽然财务支持可能有帮助，但更多的贡献者和社区管理同样重要。

---
