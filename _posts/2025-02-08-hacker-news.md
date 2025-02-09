---
layout: page
title: 勒西科技日报 - 2025年02月08日
date: 2025-02-08 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 我们正在摧毁软件；
1. 甲板：一个开源的跨平台多人卡牌游戏引擎；
1. Show HN: FlashSpace – 快速開源的 macOS Spaces 替代品；
1. 使用福图恩算法生成Voronoi图；
1. 数学书写技巧；

以上是今天的前五条黑科技新闻标题。

总共25条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 我们正在摧毁软件 
<small>🔗 [antirez.com](https://antirez.com/news/145): We are destroying software</small>


| 🔥🔥: 477 \| 💬: [341](https://news.ycombinator.com/item?id=42983275) \| 🗓️ 2025-02-08


<br />
这篇文章探讨了当前软件开发中的一些关键问题，强调了**技术债务**、**过度复杂性**和**缺乏用户反馈**对软件质量的负面影响。作者认为，许多开发者在追求快速交付时，忽视了代码的可维护性和用户需求，导致软件的长期损害。通过反思这些问题，文章呼吁开发者重新审视他们的工作方式，以确保软件的可持续发展和用户满意度。

---

## <a name="2"></a>2. 甲板：一个开源的跨平台多人卡牌游戏引擎 
<small>🔗 [github.com](https://github.com/xajik/thedeck): The Deck: An open-source cross-platform multiplayer card game engine in Flutter</small>


| 🔥🔥: 209 \| 💬: [52](https://news.ycombinator.com/item?id=42983699) \| 🗓️ 2025-02-08


<br />
“甲板”是一个基于Flutter的开源跨平台移动回合制卡牌游戏引擎，旨在为经典纸牌游戏提供数字化解决方案。其独特之处在于可以将一台设备作为“桌子”，让所有玩家实时查看卡牌状态，增强了游戏的沉浸感。该项目欢迎贡献，并在MIT许可证下发布。

---

## <a name="3"></a>3. Show HN: FlashSpace – 快速開源的 macOS Spaces 替代品 
<small>🔗 [github.com](https://github.com/wojciech-kulik/FlashSpace): Show HN: FlashSpace – fast, open-source, macOS Spaces replacement</small>


| 🔥🔥: 163 \| 💬: [52](https://news.ycombinator.com/item?id=42984420) \| 🗓️ 2025-02-08


<br />
FlashSpace 是一款**快速**的虛擬**工作區**管理器，旨在取代原生的 macOS Spaces，提供無需等待動畫的切換體驗。它支持多顯示器，允許為每個工作區分配特定應用，並具備熱鍵操作、浮動應用以及與 SketchyBar 的整合功能。FlashSpace 強調性能、簡潔和可靠性，並採用 MIT 許可，使用者可通過 Homebrew 安裝或從源碼構建。

---

## <a name="4"></a>4. 使用福图恩算法生成Voronoi图 
<small>🔗 [redpenguin101.github.io](https://redpenguin101.github.io/html/posts/2025_01_21_voronoi.html): Generating Voronoi Diagrams Using Fortune's Algorithm (With Odin)</small>


| 🔥🔥: 156 \| 💬: [15](https://news.ycombinator.com/item?id=42982015) \| 🗓️ 2025-02-08


<br />
这篇文章讨论了如何使用**福图恩算法**以O(nlogn)的时间复杂度生成**Voronoi图**。Voronoi图通过将平面划分为多个区域来表示与多个点的距离关系。福图恩算法通过一个**扫线**方法处理事件，形成“海滩线”，并通过计算抛物线的交点来确定边界。尽管实现过程可能相当复杂，但最终效果令人满意。对于小型图形，使用O(n^2)的实现或现成的库可能更为简单。

---

## <a name="5"></a>5. 数学书写技巧 
<small>🔗 [johnkerl.org](https://johnkerl.org/doc/ortho/ortho.html): Tips for mathematical handwriting (2007)</small>


| 🔥🔥: 155 \| 💬: [60](https://news.ycombinator.com/item?id=42985427) \| 🗓️ 2025-02-08


<br />
在工程、科学和数学领域，**清晰的手写**至关重要，以避免符号混淆。通过具体的方法，如添加钩子、交叉线和开口顶，可以有效地区分相似的字母和数字。此外，**掌握希腊字母**的准确书写有助于准确传达复杂的数学表达式。遵循这些建议不仅提升沟通效果，还能减少误解，确保数学工作更为精确。

---

## <a name="6"></a>6. 用 Rust 编写简单的 Windows 驱动 
<small>🔗 [scorpiosoftware.net](https://scorpiosoftware.net/2025/02/08/writing-a-simple-driver-in-rust/): Writing a simple windows driver in Rust</small>


| 🔥🔥: 152 \| 💬: [60](https://news.ycombinator.com/item?id=42984457) \| 🗓️ 2025-02-08


<br />
Rust 语言生态日益增长，因其在编译时提供**内存和并发安全**而备受关注。本文作者通过 Rust 编写一个简单的 **WDM 驱动**，展示了如何创建驱动对象，处理 IRP 请求，并实现线程优先级的修改。使用 **WDK crates** 和 **cargo** 构建系统，作者克服了从 C 类型转换到 Rust 的冗长问题，并提供了代码签名和驱动安装的步骤。结论指出，尽管 Rust 在驱动开发方面仍处于初级阶段，但其安全性和现代特性使其成为系统编程的有力工具，未来支持将进一步增强。

---

## <a name="7"></a>7. Carbon 不是一门编程语言（某种程度上） 
<small>🔗 [herecomesthemoon.net](https://herecomesthemoon.net/2025/02/carbon-is-not-a-language/): Carbon is not a programming language (sort of)</small>


| 🔥🔥: 119 \| 💬: [59](https://news.ycombinator.com/item?id=42983733) \| 🗓️ 2025-02-08


<br />
Carbon 是 Google 开发的实验性开源 **“C++继任者”语言**，旨在通过 **自动化代码迁移** 大规模减少 C++ 的技术债务。项目重点在于创建一个现代、明确的语言演进和治理模型，与 C++ 几乎无缝互操作。与其他继任者语言如 Cpp2 不同，Carbon 从根本上重塑语言，尽量减少对 C++ 的依赖，尽管尚未达到 0.1 发布里程碑，但其目标是解决 C++ 现代化过程中遇到的复杂问题。

---

## <a name="8"></a>8. 几个发行版为共同目标：可复现构建 
<small>🔗 [video.fosdem.org](https://video.fosdem.org/2025/h1302/fosdem-2025-6479-a-tale-of-several-distros-joining-forces-for-a-common-goal-reproducible-builds.av1.webm): A tale of several distros joining forces for a common goal: reproducible builds</small>


| 🔥🔥: 116 \| 💬: [48](https://news.ycombinator.com/item?id=42982270) \| 🗓️ 2025-02-08


<br />
在过去的十年中，**可复现构建**项目致力于实现多个项目的可复现构建，期间双重构建了许多软件包以验证其可复现性。但这仅是理论上的目标。实际上，项目团队希望通过工具 **rebuilderd**，自2020年起在 **Arch Linux** 中使用，并计划于2024年在Debian中应用，来重建并匹配发行版分发的软件包。本次演讲将解释Arch Linux与Debian在可复现构建方面的共同点与差异，以及在实现用户受益之前所面临的挑战。来自Debian和Arch Linux的开发者将共同呈现此次演讲。

---

## <a name="9"></a>9. 软件抽象真的会扼杀文明吗？ 
<small>🔗 [datagubbe.se](https://datagubbe.se/endofciv/): Is software abstraction killing civilization? (2021)</small>


| 🔥: 100 \| 💬: [49](https://news.ycombinator.com/item?id=42986485) \| 🗓️ 2025-02-08


<br />
本文批判性地分析了游戏开发大师Jonathan Blow关于**软件抽象**可能导致文明崩溃的观点。作者指出，Blow的论据存在多处错误和误解，例如他错误地认为“**五个九**”的高可用性指标已不再使用，并且误解了现代软件的**健壮性**。文章还反驳了Blow关于科技公司不再推动技术前进的看法，强调当前“硬科技”领域的持续创新。此外，作者认为抽象并未导致编程能力的丧失，反而有更多人掌握底层编程语言。通过对比历史与现今的软件开发实践，作者总结认为，现代软件更为稳健，程序员的生产力并未下降，甚至在某些方面有所提升，从而否定了Blow关于软件抽象将导致文明崩溃的悲观预言。

---

## <a name="10"></a>10. 大语言模型心理师效应 
<small>🔗 [softwarecrisis.dev](https://softwarecrisis.dev/letters/llmentalist/): The LLMentalist Effect</small>


| 🔥: 96 \| 💬: [84](https://news.ycombinator.com/item?id=42983571) \| 🗓️ 2025-02-08


<br />
过去一年，我一直在研究**语言模型**和**扩散模型**在软件企业中的应用。研究中我发现，许多人认为聊天型语言模型具有智能，但实际上LLMs只是**语言符号的数学模型**，它们并不具备思考或推理能力。AI研究人员和供应商一再强调，LLMs并不“思考”。我认为，这种“智能幻觉”源自用户的认知，而非模型本身。这种现象类似于**心理师的骗局**，通过使用模糊但让人感觉准确的陈述，使用户误以为模型具有智能。许多被提出的用例看起来几乎像是**欺诈性的伪科学**。这种机制依赖于人类的**主观验证效应**，使得用户将通用的陈述与自身相关联，从而误认为模型具备理解和推理能力。这种现象不仅揭示了LLMs本质上的局限，也提醒我们在面对所谓的“智能”技术时，需保持警惕和理性。

---

## <a name="11"></a>11. 无依赖的单文件C/C++库集合，主要用于游戏 
<small>🔗 [github.com](https://github.com/RandyGaul/cute_headers): Collection of one-file C/C++ libraries with no dependencies, primarily for games</small>


| 🔥: 69 \| 💬: [32](https://news.ycombinator.com/item?id=42983197) \| 🗓️ 2025-02-08


<br />
该项目汇集了多个**跨平台**、**单文件**且**无依赖**的C/C++库，主要面向游戏开发。库涵盖音频处理、图形渲染、网络通信、数学运算等多个关键领域，便于开发者快速集成至项目中，无需处理繁琐的依赖关系或构建脚本。通过简单的头文件包含和单次实现定义，用户可轻松使用这些库。此外，项目还提供丰富的示例代码和测试案例，帮助理解和应用各个库。开发者可通过Discord社区或Twitter联系维护者，获取支持和交流经验。每个库采用灵活的许可证，如公有领域或zlib，确保在不同项目中的广泛使用。这些单文件库为需要轻量、高性能解决方案的游戏开发者提供了极大的便利和效率。

---

## <a name="12"></a>12. 亚马逊错失Alexa主导AI的机会，员工称 
<small>🔗 [fortune.com](https://fortune.com/2024/06/12/amazon-insiders-why-new-alexa-llm-generative-ai-conversational-chatbot-missing-in-action/): Amazon blew Alexa's shot to dominate AI, according to employees (2024)</small>


| 🔥: 64 \| 💬: [53](https://news.ycombinator.com/item?id=42984791) \| 🗓️ 2025-02-08


<br />
亚马逊前高管**David Limp**使**Alexa**成为消费者喜爱的智能助手。然而，随着**ChatGPT**的兴起，Alexa在AI领域的竞争力逐渐下降。超过十多名参与Alexa项目的员工认为，Amazon未能及时调整战略，导致其无法在人工智能市场中保持领先地位，从而错失了主导AI发展的良机。

---

## <a name="13"></a>13. Show HN：FreeDemandLetter – 对抗被欺负的利器 
<small>🔗 [freedemandletter.com](https://www.freedemandletter.com): Show HN: FreeDemandLetter – A Weapon for Anyone Who's Sick of Getting Shafted</small>


| 🔥: 54 \| 💬: [51](https://news.ycombinator.com/item?id=42983148) \| 🗓️ 2025-02-08


<br />
FreeDemandLetter 提供**符合州法律**的专业模板，简化流程让用户在几分钟内创建需求函，确保**法律合规**并提高解决纠纷的成功率。无论是未支付工资、合同纠纷还是退还押金，用户都能通过平台有效维护自己的权利，享受无法律烦恼的服务体验。

---

## <a name="14"></a>14. Chez Scheme 的 txtar Go 端口 
<small>🔗 [git.sr.ht](https://git.sr.ht/~egtann/txtar/): Show HN: Chez Scheme txtar port from Go</small>


| 🔥: 54 \| 💬: [6](https://news.ycombinator.com/item?id=42984962) \| 🗓️ 2025-02-08


<br />
该项目要求**支持 POSIX ACLs**，避免使用硬件 DMA 或 DMA32 区域。此外，还涉及到增强功能和优化，如处理未认证的用户和改进系统性能。该端口旨在提高**兼容性**和**效率**，适应多种操作环境需求。

---

## <a name="15"></a>15. 黎明之女 (1920) 
<small>🔗 [afi.com](https://www.afi.com/news/the-daughter-of-dawn-1920-afi-catalog-spotlight/): The Daughter of Dawn [1920] (2024)</small>


| 🔥: 36 \| 💬: [4](https://news.ycombinator.com/item?id=42984813) \| 🗓️ 2025-02-08


<br />
在美国**原住民文化**月，AFI目录聚焦1920年的电影《黎明之女》，这部早期作品由全**美洲原住民演员**主演并参与制作，真实展现了**基奥瓦与科曼奇**文化。尽管当时面临政府干涉和歧视，该片后来被遗失近一个世纪，直至2005年被发现并修复。2013年入选国家电影登记册，成为文化与历史的重要象征。

---

## <a name="16"></a>16. SilverBullet – Git友好的笔记应用，替代Logseq与Obsidian 
<small>🔗 [silverbullet.md](https://silverbullet.md/): SilverBullet – note-taking Git-friendly alternative to Logseq and Obsidian</small>


| 🔥: 35 \| 💬: [8](https://news.ycombinator.com/item?id=42981690) \| 🗓️ 2025-02-08


<br />
SilverBullet 是一个开源的个人知识管理系统，支持**自托管**，用户可以通过 Markdown 快速记录笔记，并将笔记转化为可查询的数据库，构建自定义的知识应用。作为一个渐进式网络应用（PWA），它既支持在线模式也支持离线操作，优化了键盘操作体验。通过**端用户编程**，用户可以利用对象、实时查询和模板动态管理内容，甚至在笔记中创建应用程序。此外，SilverBullet 提供双向链接、强大的模板机制以及可通过库和插件扩展的功能，适合喜欢高度定制和灵活性的用户。完全免费且采用 MIT 许可，SilverBullet 为追求高效与自由的笔记记录提供了理想选择。

---

## <a name="17"></a>17. Mozilla Firefox的Deep Fake检测扩展 
<small>🔗 [addons.mozilla.org](https://addons.mozilla.org/en-US/firefox/addon/deep-fake-detector/): Deep Fake Detector Extension by Mozilla Firefox</small>


| 🔥: 34 \| 💬: [12](https://news.ycombinator.com/item?id=42986613) \| 🗓️ 2025-02-08


<br />
Fakespot的Deepfake Detector扩展助您区分**人类撰写的文本**与**AI生成的内容**。该扩展融合了Fakespot独有的**APOLLO方法**以及多种开源检测模型，用户只需高亮任何在线文本，即可进行即时分析。分析结果将详细展示每个模型的检测发现，用户还可以轻松切换不同模型，找到最适合自己的组合。目前，文本检测功能已全面上线，未来将支持**图像和视频分析**。安装后，用户只需在网页上选中文本并请求分析，Detector便能立即判断其是否由人类撰写或存在AI生成的痕迹。尽管AI检测无法达到百分之百的准确率，Fakespot持续改进其APOLLO DFT引擎，力求提升检测的可靠性。该扩展需存储和访问用户在所有网站的数据，遵循Mozilla Public License 2.0，并提供主页、支持网站及支持邮箱等相关链接。

---

## <a name="18"></a>18. Ada 珍宝存档 
<small>🔗 [adacore.com](https://www.adacore.com/gems): Ada Gems (2014)</small>


| 🔥: 31 \| 💬: [4](https://news.ycombinator.com/item?id=42986149) \| 🗓️ 2025-02-08


<br />
"Ada Gems" 是由 **AdaCore** 推出的每周博客系列，涵盖了从 **单元测试**、**多核编程** 到 **语言扩展** 等多种 Ada 编程主题。该存档包括 Gem #1 至 Gem #161，涉及**异常处理**、**类型安全**、**并发编程**等多个方面，为 Ada 开发者提供了宝贵的资源和知识。虽然该系列已正式退休，但丰富的存档依然可供读者回顾和学习。

---

## <a name="19"></a>19. 穆斯克DOGE团队的青少年成员毕业于‘The Com’ 
<small>🔗 [krebsonsecurity.com](https://krebsonsecurity.com/2025/02/teen-on-musks-doge-team-graduated-from-the-com/): Teen on Musk's DOGE Team Graduated from 'The Com'</small>


| 🔥: 29 \| 💬: [3](https://news.ycombinator.com/item?id=42982964) \| 🗓️ 2025-02-08


<br />
据《连线》周报道，一名19岁青年Edward Coristine加入**埃隆·马斯克**的所谓政府效率部（DOGE），并获得了敏感的美国政府系统访问权限，尽管他曾与网络犯罪社区‘The Com’有过关联，这本应阻止他获得必要的安全许可。Coristine创立的Tesla.Sexy LLC控制多个域名，包括俄罗斯注册的域名，并在Discord服务器上提供DDoS攻击服务。他在DOGE团队中的快速上位，引发了对**安全审查**流程的质疑。此外，Coristine在被指控泄露公司内部文件后被解雇，其过往背景使得他在获得政府高权限职位时存在重大安全风险。此事件揭示了DOGE团队在处理具有潜在安全隐患成员时的严重疏漏。

---

## <a name="20"></a>20. Zig无libc版本现已超越Glibc Zig 
<small>🔗 [ziglang.org](https://ziglang.org/devlog/2025/#2025-02-07): No-Libc Zig Now Outperforms Glibc Zig</small>


| 🔥: 25 \| 💬: [1](https://news.ycombinator.com/item?id=42983364) \| 🗓️ 2025-02-08


<br />
Andrew Kelley 重构了 Zig 的 **调试分配器**，消除了对编译时固定页大小的依赖，使其支持 **Asahi Linux**。新的实现优化了内存分配元数据的存储方式，大幅减少了内存映射的数量，并提升了性能。在实际编译任务中，**无libc Zig** 在速度和内存使用上都显著优于 **Glibc Zig**，标志着 Zig 语言及其标准库已超越了 C 和 libc，成为更优的选择。

---

## <a name="21"></a>21. 构建欧洲项目/公司列表，您能帮助我添加更多吗？ 
<small>🔗 [github.com](https://github.com/uscneps/Awesome-European-Tech): Building a list of European projects/companies, can you help me to add more?</small>


| 🔥: 22 \| 💬: [31](https://news.ycombinator.com/item?id=42981772) \| 🗓️ 2025-02-08


<br />
这是一个**社区驱动**的**欧洲优秀科技项目**列表，专注于**隐私**、**可持续性**和**创新**。目标是支持遵守**GDPR**法规的欧盟和EFTA国家的初创公司和项目，增强欧洲科技生态系统。欧洲企业往往遵循独特标准，提升用户体验并设定全球创新、隐私和可持续性的标杆。例如，**GDPR合规**确保了比许多其他地区更严格的数据隐私和安全，**可持续发展标准**则使欧洲公司在环保实践上处于领先地位。项目鼓励全球合作，旨在通过支持欧洲初创企业，促进一个多样化、具有韧性和互联的全球科技环境。社区成员可以通过提交拉取请求来扩展和完善列表，进一步推动欧洲科技的成长与协作。

---

## <a name="22"></a>22. 迪士尼+广告政策重大调整 
<small>🔗 [wiki.rossmanngroup.com](https://wiki.rossmanngroup.com/wiki/Disney%2B_Ad_Policy_Change): Disney+ Ad Policy Change</small>


| 🔥: 22 \| 💬: [3](https://news.ycombinator.com/item?id=42985423) \| 🗓️ 2025-02-08


<br />
自2025年1月起，**迪士尼+**在所有订阅层级中引入广告，包括原本标榜“无广告”的高级套餐。此次变更通过更新服务条款实施，所有现有用户除非取消订阅，否则将受新条款约束。此举改变了购买后服务的基本特性，引发了**消费者保护**方面的关注。

---

## <a name="23"></a>23. 计算专家称程序员需要更多数学 
<small>🔗 [quantamagazine.org](https://www.quantamagazine.org/computing-expert-says-programmers-need-more-math-20220517/): Computing Expert Says Programmers Need More Math</small>


| 🔥: 18 \| 💬: [2](https://news.ycombinator.com/item?id=42982241) \| 🗓️ 2025-02-08


<br />
莱斯利·兰波特（Leslie Lamport）是计算机科学领域的重要人物，他的工作推动了**分布式系统**的发展，使现代计算机能够高效协同工作。他因**Paxos 算法**获得了图灵奖，这一算法成为业界标准，确保多台计算机在复杂任务中达成一致。兰波特还开发了**TLA+**，一种用于软件和硬件系统**形式验证**的规范语言，强调在编写代码前先进行数学上的精确设计，以减少bug和设计缺陷。他批评当前计算机科学教育缺乏对数学思维的重视，认为程序员应更多地运用数学来提升编程的严谨性和效率。兰波特的工作不仅影响了学术界，也为谷歌和亚马逊等公司的云基础设施奠定了基础，显著提升了软件工程的质量和可靠性。

---

## <a name="24"></a>24. 汽车交流发电机是优秀的电动机 
<small>🔗 [hackaday.com](https://hackaday.com/2020/01/16/car-alternators-make-great-electric-motors-heres-how/): Car Alternators Make Great Electric Motors;</small>


| 🔥: 18 \| 💬: [1](https://news.ycombinator.com/item?id=42983497) \| 🗓️ 2025-02-08


<br />
汽车**交流发电机**不仅用于将内燃机的动力转换为电力，还可以被改装成高效的**电动机**。这些发电机通常为三相，采用三角形接线配置，具备数马力的输出能力，并且二手价格低廉，适合电动车项目如英国的Hacky Racer系列。转换过程包括拆除调节器和整流器，保留定子和刷子的连接，并接入适当的**无刷控制器**和直流电源。改装后的发电机能够可靠地作为电动车的驱动系统，虽然可能需要额外的散热措施。利用废旧发电机作为电动机，为个人及团队提供了一种经济实惠且高效的动力解决方案。

---

## <a name="25"></a>25. 如何遵守英国在线安全法；屏蔽英国 
<small>🔗 [geoblockthe.uk](https://geoblockthe.uk/): How to Comply with the UK's Online Safety Act; Block the UK</small>


| 🔥: 18 \| 💬: [0](https://news.ycombinator.com/item?id=42983997) \| 🗓️ 2025-02-08


<br />
英国的在线安全法要求“用户对用户服务”的运营者进行**风险评估**和“儿童访问评估”，否则将面临高额罚款或监禁。幸运的是，OFCOM确认**屏蔽英国用户访问网站**是合法的合规方式。文中还提供了实现屏蔽的**技术选项**以及绕过地理封锁的方法，如使用Tor浏览器。

---
