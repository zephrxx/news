---
layout: page
title: 勒西科技日报 - 2025年05月24日
date: 2025-05-24 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 利用OpenAI o3模型发现Linux SMB内核零日漏洞；
1. 旋转电话拨号盘Linux内核驱动项目；
1. 小公司就该有小公司的样子；
1. 树莓派2的“氙气死亡闪光”：相机如何差点杀死微型电脑；
1. 香港竹制脚手架：传统工艺的坚守者；

以上是今天的前五条黑科技新闻标题。

总共25条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 利用OpenAI o3模型发现Linux SMB内核零日漏洞 
<small>🔗 [sean.heelan.io](https://sean.heelan.io/2025/05/22/how-i-used-o3-to-find-cve-2025-37899-a-remote-zeroday-vulnerability-in-the-linux-kernels-smb-implementation/): I used o3 to find a remote zeroday in the Linux SMB implementation</small>


| 🔥🔥: 268 \| 💬: [79](https://news.ycombinator.com/item?id=44081338) \| 🗓️ 2025-05-24


<br />
作者通过**OpenAI的o3模型**成功发现了Linux内核SMB实现(ksmbd)中的两个**use-after-free漏洞**：CVE-2025-37778（Kerberos认证路径）和新发现的CVE-2025-37899（会话注销处理）。实验显示o3在分析3.3千行代码时能以1:4.5的真假阳性比发现漏洞，其报告质量接近人类专家水平。尽管在12千行大代码量下准确率下降，但o3仍成功识别出新漏洞，证明**AI辅助漏洞研究**已进入实用阶段，能显著提升安全研究人员效率。

---

## <a name="2"></a>2. 旋转电话拨号盘Linux内核驱动项目 
<small>🔗 [gitlab.com](https://gitlab.com/sephalon/rotary_dial_kmod): Show HN: Rotary Phone Dial Linux Kernel Driver</small>


| 🔥🔥: 262 \| 💬: [35](https://news.ycombinator.com/item?id=44080803) \| 🗓️ 2025-05-24


<br />
该项目开发了一个**Linux内核驱动**，可将老式**旋转电话拨号盘**转换为**evdev输入设备**，使其能在现代系统中使用。项目采用GNU通用公共许可证v2.0或更高版本，代码与文档已在GitHub开源。核心功能是通过硬件接口读取拨号脉冲信号，并映射为标准输入事件，适用于复古硬件改造或创意交互项目。

---

## <a name="3"></a>3. 小公司就该有小公司的样子 
<small>🔗 [longform.asmartbear.com](https://longform.asmartbear.com/little-company/): You're a little company, now act like one</small>


| 🔥🔥: 178 \| 💬: [31](https://news.ycombinator.com/item?id=44081494) \| 🗓️ 2025-05-24


<br />
作者Jason Cohen指出，初创企业常犯的错误是试图伪装成“成熟大公司”，使用空洞的营销话术和刻板形象，反而疏远了真正的目标客户——**早期采用者**。这类客户恰恰青睐小团队的灵活、真诚与快速响应，愿意容忍产品初期的缺陷以换取创新优势。关键在于**展现真实身份**：用具体、人性化的语言沟通，突出产品核心价值与可协作性，而非堆砌夸大术语。伪装成“行业领导者”只会让潜在客户失望，而坦诚相待能吸引真正需要你的用户。

---

## <a name="4"></a>4. 树莓派2的“氙气死亡闪光”：相机如何差点杀死微型电脑 
<small>🔗 [magnus919.com](https://magnus919.com/2025/05/the-xenon-death-flash-how-a-camera-nearly-killed-the-raspberry-pi-2/): The Xenon Death Flash: How a Camera Nearly Killed the Raspberry Pi 2</small>


| 🔥🔥: 161 \| 💬: [59](https://news.ycombinator.com/item?id=44080533) \| 🗓️ 2025-05-24


<br />
2015年，用户Peter Onion发现用**氙气闪光灯**拍摄树莓派2会导致其瞬间关机。社区调查发现，问题源于采用**WL-CSP封装**的电源芯片U16——裸露的硅晶片在强光下触发**光电效应**，扰乱电路。临时解决方案是用蓝丁胶遮挡芯片，最终通过硬件改版彻底修复。这一罕见漏洞揭示了现代电子设备微型化带来的潜在风险，也成为光电效应的生动案例，展现了开源社区协作解决问题的强大力量。

---

## <a name="5"></a>5. 香港竹制脚手架：传统工艺的坚守者 
<small>🔗 [nytimes.com](https://www.nytimes.com/2025/05/24/world/asia/hongkong-bamboo-scaffolding.html): Hong Kong's Famous Bamboo Scaffolding Hangs on (For Now)</small>


| 🔥🔥: 135 \| 💬: [35](https://news.ycombinator.com/item?id=44080549) \| 🗓️ 2025-05-24


<br />
在香港，**竹制脚手架**这一古老工艺仍是城市景观的一部分，而31岁的**Daisy Pak**是少数从事该行业的女性之一。她曾经历艰难成长、吸毒和负债，2021年转行学习这门手艺。尽管面临性别和身高的质疑，甚至遭遇同事刁难，她仍坚持用竹竿搭建复杂的结构，并为此自豪。**传统技艺**通过师徒传承，但Daisy通过多方学习掌握了技能。如今，这一行业在香港虽存续，却面临现代建筑技术的冲击。

---

## <a name="6"></a>6. DumPy：让高维数组操作像循环一样简单 
<small>🔗 [dynomight.net](https://dynomight.net/dumpy/): DumPy: NumPy except it's OK if you're dum</small>


| 🔥🔥: 128 \| 💬: [44](https://news.ycombinator.com/item?id=44080181) \| 🗓️ 2025-05-24


<br />
本文介绍了**DumPy**——一个旨在解决NumPy高维操作复杂性的库。作者指出，NumPy为规避Python循环的慢速，将高维逻辑分散到各函数中，导致代码晦涩难懂。**DumPy**的核心思想是**用循环语法实现向量化操作**：通过字符串标记维度（如`A['i','j']`），自动编译为高效GPU运算，同时保留直观性。文中对比了NumPy、JAX和DumPy的代码，展示后者如何用类循环语法简化高维矩阵运算（如希尔伯特矩阵生成、批处理协方差计算等），**显著降低认知负担**，而性能无损。

---

## <a name="7"></a>7. 好文章的两重境界 
<small>🔗 [paulgraham.com](https://paulgraham.com/goodwriting.html): Good Writing</small>


| 🔥🔥: 119 \| 💬: [145](https://news.ycombinator.com/item?id=44081586) \| 🗓️ 2025-05-24


<br />
好文章的标准有两种：**文笔优美**与**思想正确**。看似两者无关，实则紧密相连——优美的文笔往往能帮助呈现更准确的思想。作者通过排版修改和"摇晃箱子"的比喻说明，**外在形式的优化会自然推动内在逻辑的完善**。此外，流畅的文本降低了阅读难度，使作者更容易发现思想漏洞。但这一法则仅适用于通过写作探索思想的场景，对已有结论的记述型文本无效。最终，好文章如同精心设计的飞机——**形式与功能本质统一**，思想与表达难以割裂。

---

## <a name="8"></a>8. 重新发明轮子的价值 
<small>🔗 [endler.dev](https://endler.dev/2025/reinvent-the-wheel/): Reinvent the Wheel</small>


| 🔥🔥: 114 \| 💬: [62](https://news.ycombinator.com/item?id=44083467) \| 🗓️ 2025-05-24


<br />
文章批判了“不要重复造轮子”这一建议，指出它会扼杀**好奇心**与**探索精神**。作者强调，通过亲手实现基础工具（如字符串库或协议），能**深入理解原理**，甚至发现现有方案的不足。**实践中的取舍**（如性能与简洁性）是提升工程能力的关键。合理的“造轮子”动机包括学习、教学或解决特殊需求，但应避免因无知而重复劳动。最终建议：**为洞察而创新，为效率而复用**。

---

## <a name="9"></a>9. Tachy0n：最后一个0day越狱漏洞 
<small>🔗 [blog.siguza.net](https://blog.siguza.net/tachy0n/): Tachy0n: The Last 0day Jailbreak</small>


| 🔥🔥: 108 \| 💬: [9](https://news.ycombinator.com/item?id=44083388) \| 🗓️ 2025-05-24


<br />
开发者Siguza在2025年回顾了2020年发布的iOS 13.0-13.5内核漏洞**tachy0n**，这是近年来罕见的**0day越狱漏洞**，迫使苹果在一周内紧急修复。漏洞源于`lio_listio`系统调用中的竞态条件，导致双重释放（double free），最终实现内核提权。文章详细描述了漏洞的发现过程、历史背景（如iOS 12的SockPuppet漏洞回归）及利用技术，包括通过**mach端口伪造**和堆喷（heap spraying）绕过防护。此外，作者对比了早期团队合作开发的Spice越狱工具，并探讨了不同设备架构（如A7-A11）的利用差异。

---

## <a name="10"></a>10. AI、海德格尔与EVA：当技术吞噬人性 
<small>🔗 [fakepixels.substack.com](https://fakepixels.substack.com/p/ai-heidegger-and-evangelion): AI, Heidegger, and Evangelion</small>


| 🔥🔥: 104 \| 💬: [58](https://news.ycombinator.com/item?id=44081346) \| 🗓️ 2025-05-24


<br />
本文探讨AI引发的存在焦虑：**算法 indifference（无差别性）**消解了人类对意图与叙事的渴求，海德格尔的**“座架”理论**揭示技术将万物降格为可优化资源。而《EVA》的**人类补完计划**隐喻了数字化时代个体性消亡的危机。核心矛盾在于：AI模仿情感却无真实体验，其空洞性迫使人类重新捍卫**不可量化的存在价值**——痛苦、诗意与偶然性才是人性的最后疆域。

---

## <a name="11"></a>11. 实时人脸识别摄像头或成英国警方“标配” 
<small>🔗 [theguardian.com](https://www.theguardian.com/technology/2025/may/24/police-live-facial-recognition-cameras-england-and-wales): Live facial recognition cameras may become 'commonplace' as police use soars</small>


| 🔥🔥: 101 \| 💬: [77](https://news.ycombinator.com/item?id=44082326) \| 🗓️ 2025-05-24


<br />
英国警方内部文件显示，**实时人脸识别技术**在英格兰和威尔士的应用激增，2024年扫描人脸数达470万，较前一年翻倍。该技术通过摄像头实时比对警方监视名单，被批评者视为“持续指纹采集”。尽管缺乏法律明确授权，警方已扩大使用范围，包括固定摄像头试点和接入护照、移民数据库。**争议焦点**包括技术误判（尤其对黑人群体）及隐私风险。伦敦警方称80%市民支持该技术，并强调通过调整算法减少偏见。内政部正筹建国家级人脸匹配系统，但立法框架仍缺失。

---

## <a name="12"></a>12. 微软支持的英国科技独角兽Builder.ai破产 
<small>🔗 [ft.com](https://www.ft.com/content/9fdb4e2b-93ea-436d-92e5-fa76ee786caa): Microsoft-backed UK tech unicorn Builder.ai collapses into insolvency</small>


| 🔥: 91 \| 💬: [73](https://news.ycombinator.com/item?id=44080640) \| 🗓️ 2025-05-24


<br />
英国科技公司**Builder.ai**（曾获微软投资）因财务问题进入破产程序。该公司此前估值超过10亿美元，成为**独角兽企业**，但如今面临清算。文章来自《金融时报》，需订阅查看全文，其订阅方案包括标准版、高级版及印刷+数字组合套餐，提供全球新闻、专家分析和独家内容。此次事件凸显科技初创企业在融资环境收紧下的生存挑战。

---

## <a name="13"></a>13. F2：跨平台命令行批量重命名工具 
<small>🔗 [github.com](https://github.com/ayoisaiah/f2): Show HN: F2 – Cross-Platform CLI Batch Renaming Tool</small>


| 🔥: 88 \| 💬: [15](https://news.ycombinator.com/item?id=44081850) \| 🗓️ 2025-05-24


<br />
F2是一款基于Go语言开发的**跨平台命令行工具**，专为快速、安全地批量重命名文件和目录设计。其核心优势包括：**默认模拟运行**（可预览修改效果）、支持**文件属性变量**（如EXIF或ID3标签）、丰富的正则表达式功能，以及冲突检测与自动修复。此外，F2提供高性能批量处理、**撤销操作**和详尽文档，适合从简单替换到复杂重命名需求。支持Windows、macOS和Linux，可通过Go安装或直接下载预编译二进制文件。开源项目采用MIT许可证，已获935星标。

---

## <a name="14"></a>14. AI连简单bug都修不好，却成了裁员的借口 
<small>🔗 [nmn.gl](https://nmn.gl/blog/ai-scam): AI can't even fix a simple bug – but sure, let's fire engineers</small>


| 🔥: 87 \| 💬: [109](https://news.ycombinator.com/item?id=44082293) \| 🗓️ 2025-05-24


<br />
GitHub Copilot代理在微软.NET运行时中提交了错误代码，**人类工程师反复纠正却无果**，而企业高管却以此为由裁员。作者指出，**AI只是企业掩盖过度招聘的幌子**，真正高效的团队是**人类与AI协作**。开发者应掌握AI工具、记录其局限性，并公开分享真实案例，证明人类在复杂问题中不可替代。当前AI仍频繁出错，工程师的工作依然安全。

---

## <a name="15"></a>15. 中银胶囊大厦的传奇遗产 
<small>🔗 [designboom.com](https://www.designboom.com/architecture/moma-nakagin-capsule-tower-exhibition-many-lives-museum-modern-art-new-york-05-23-2025/): The legacy of the iconic Nakagin capsule tower</small>


| 🔥: 81 \| 💬: [23](https://news.ycombinator.com/item?id=44080820) \| 🗓️ 2025-05-24


<br />
扎哈·哈迪德建筑事务所的首个Adobe项目——**阿桑博物馆**在利雅得破土动工，引发建筑界广泛关注。该项目以**创新设计**和**文化融合**为核心理念，展现了未来建筑的先锋姿态。作为标志性作品，它不仅延续了扎哈事务所的**前卫风格**，更成为沙特阿拉伯文化地标的新亮点。

---

## <a name="16"></a>16. 蠢蛋进化论：反智社会的荒诞预言 
<small>🔗 [en.wikipedia.org](https://en.wikipedia.org/wiki/Idiocracy): Idiocracy</small>


| 🔥: 80 \| 💬: [23](https://news.ycombinator.com/item?id=44079755) \| 🗓️ 2025-05-24


<br />
《蠢蛋进化论》是2006年由迈克·乔吉执导的科幻喜剧片，讲述一名普通军人**乔**和妓女**丽塔**在休眠实验后苏醒于500年后的未来。这个社会因**反智主义**和过度繁衍沦为低能文明，总统由运动饮料代言人担任，农作物用电解质饮料灌溉。影片以荒诞手法讽刺消费主义、基因衰退等议题。尽管上映时因片方消极宣传票房惨淡，但凭借尖锐的社会批判成为**邪典经典**。主演卢克·威尔逊与玛娅·鲁道夫的表演为黑色幽默增色，而片中“欢迎来好市多，我们爱你”等台词至今被影迷津津乐道。

---

## <a name="17"></a>17. SuperUtilsPlus：Lodash 的现代替代方案 
<small>🔗 [github.com](https://github.com/dhaxor/super-utils-plus): Show HN: SuperUtilsPlus – A Modern Alternative to Lodash</small>


| 🔥: 75 \| 💬: [54](https://news.ycombinator.com/item?id=44080808) \| 🗓️ 2025-05-24


<br />
SuperUtilsPlus 是一个高性能的 JavaScript 工具库，旨在替代 Lodash，提供**更优的性能**、**完整的 TypeScript 支持**和**现代化的开发体验**。它支持 ES2020+ 语法，具备**树摇优化**和零依赖特性，适用于浏览器和 Node.js 环境。功能涵盖数组、对象、字符串、函数工具及类型检查，并扩展了更多实用方法。安装简单，支持 npm、yarn 和 pnpm，且提供模块化导入以优化打包体积。MIT 许可开源，适合追求效率与类型安全的开发者。

---

## <a name="18"></a>18. Lnk：基于 Git 的极简 dotfiles 管理工具 
<small>🔗 [github.com](https://github.com/yarlson/lnk): Show HN: Lnk – Git-native dotfiles manager</small>


| 🔥: 69 \| 💬: [47](https://news.ycombinator.com/item?id=44080410) \| 🗓️ 2025-05-24


<br />
Lnk 是一个**Git 原生**的 dotfiles 管理工具，通过自动化符号链接和版本控制简化配置管理。用户只需将文件移至 `~/.config/lnk` 目录，工具会自动创建指向原位置的符号链接，并支持常规 Git 操作（如提交、推送）。  

**核心功能**包括：一键初始化、冲突处理、原子化操作，且无需额外配置。支持多种安装方式（脚本、Homebrew 或源码编译），适合追求**轻量化**和**无依赖**的用户。  

与同类工具（如 chezmoi、yadm）相比，Lnk 专注基础需求，强调**简单易用**。目前为 MIT 许可，适合开发者快速部署多环境配置。

---

## <a name="19"></a>19. 独行程序员破解50年难题，找到Boggle游戏最高分棋盘 
<small>🔗 [ft.com](https://www.ft.com/content/0ab64ced-1ed1-466d-acd3-78510d10c3a1): Lone coder cracks 50-year puzzle to find Boggle's top-scoring board</small>


| 🔥: 69 \| 💬: [14](https://news.ycombinator.com/item?id=44082892) \| 🗓️ 2025-05-24


<br />
一名程序员通过独立编程，成功破解了困扰玩家50年的**Boggle游戏**最高分棋盘谜题。该成果展示了**算法优化**与**计算能力**的突破，为这款经典文字游戏提供了理论上的最优解。原文还提及了《金融时报》的订阅服务，但核心内容聚焦于这一技术成就。

---

## <a name="20"></a>20. 久坐族的1分钟微锻炼指南 
<small>🔗 [shortreps.com](https://shortreps.com): Show HN: 1 min workouts for people who sit all day</small>


| 🔥: 59 \| 💬: [20](https://news.ycombinator.com/item?id=44083687) \| 🗓️ 2025-05-24


<br />
这款应用为久坐人群提供**全天候微锻炼方案**，通过碎片化运动提升健康：**增强心肺功能**（提高摄氧量、降血压）、**改善代谢**（调节血糖和胰岛素敏感度），并快速释放内啡肽**缓解压力**。无需器械，AI每日推送5个定制动作，附视频指导确保动作规范，内置习惯追踪功能激励坚持。随时随地，咖啡间隙也能完成！

---

## <a name="21"></a>21. 资深工程师如何与LLM高效结对编程 
<small>🔗 [pmbanugo.me](https://pmbanugo.me/blog/peer-programming-with-llms): Peer Programming with LLMs, for Senior+ Engineers</small>


| 🔥: 58 \| 💬: [26](https://news.ycombinator.com/item?id=44081081) \| 🗓️ 2025-05-24


<br />
本文汇集多位资深工程师使用大语言模型（LLM）协作编程的实践经验，摒弃浮夸宣传，聚焦实用技巧。**“第二意见”**和**“临时调试脚本”**是Sean提出的核心方法，可提升日常效率；Harper则强调用LLM**协同规划**功能前需明确需求，避免无效对话。Lee指出**记录优质提示词**是关键习惯，而Seth提醒LLM本质是工具，需建立有效使用模式。文末建议：遇阻时先问AI，再问人。

---

## <a name="22"></a>22. 请为科学投入更多资金（2020） 
<small>🔗 [blog.samaltman.com](https://blog.samaltman.com/please-fund-more-science): Please Fund More Science (2020)</small>


| 🔥: 52 \| 💬: [35](https://news.ycombinator.com/item?id=44082968) \| 🗓️ 2025-05-24


<br />
专家指出，终结新冠疫情有三种途径：**有效疫苗**将全球R0值降至1以下、**特效治疗**消除民众恐惧，或建立完善的**检测、追踪与隔离体系**。作者呼吁联邦政府加大科研投入，但当前私营机构与慈善力量的快速响应令人振奋——生物科技公司与实验室的效率提升了十倍以上。科学家需要资金和人脉支持，投资者与捐赠者若能转向抗疫科研（包括未来流行病防御），将获得大量优质机会。这一领域的创新速度与专家协作令人充满希望。

---

## <a name="23"></a>23. 当我要求亚马逊告诉我Alexa听到的一切时，发现了什么 
<small>🔗 [theguardian.com](https://www.theguardian.com/technology/2025/may/24/what-i-discovered-when-i-asked-amazon-to-tell-me-everything-alexa-had-heard): What I discovered when I asked Amazon to tell me everything Alexa had heard</small>


| 🔥: 52 \| 💬: [31](https://news.ycombinator.com/item?id=44083105) \| 🗓️ 2025-05-24


<br />
作者通过请求亚马逊提供Alexa的交互数据，揭示了智能音箱如何深度介入家庭生活。**15,000条语音记录**显示，Alexa不仅是音乐播放器和计时器，还充当了**兽医、家教和心理顾问**等角色。数据暴露了孩子的成长轨迹（如音乐品味变化）和隐私问题（如深夜提问）。尽管亚马逊声称录音仅在唤醒词后上传，但海量存储的**语音和文字记录**仍引发对隐私的担忧。家庭成员对Alexa的态度各异，尤其是女儿Coco将其视为私密倾诉对象，而成人更多用于实用功能。智能音箱的普及让亚马逊掌握了用户习惯、需求甚至未言明的欲望，这种“持续改进服务”的代价是否值得？

---

## <a name="24"></a>24. 是时候停止向非统计专业学生教授频率学派方法了（2024） 
<small>🔗 [arxiv.org](https://arxiv.org/abs/1201.2590): It Is Time to Stop Teaching Frequentism to Non-Statisticians (2024)</small>


| 🔥: 48 \| 💬: [42](https://news.ycombinator.com/item?id=44082494) \| 🗓️ 2025-05-24


<br />
该论文主张**用贝叶斯统计取代频率学派统计**作为本科统计教学的核心内容。作者William Briggs指出，频率学派方法导致大量**混淆和过度自信**，尤其对非统计专业学习者而言。他认为贝叶斯框架更直观，能减少误用，并提升统计推断的准确性。论文最初发布于2012年，但议题至今仍具争议性。

---

## <a name="25"></a>25. 美国关税简史 
<small>🔗 [imprimis.hillsdale.edu](https://imprimis.hillsdale.edu/tariffs-in-american-history/): Tariffs in American History</small>


| 🔥: 43 \| 💬: [79](https://news.ycombinator.com/item?id=44080237) \| 🗓️ 2025-05-24


<br />
本文梳理了美国关税政策的演变：**关税**作为最古老的税种，早期用于增加财政收入，但殖民时期催生了大规模走私。独立后，**亚历山大·汉密尔顿**通过关税改革稳定经济，19世纪关税转向保护新兴工业，引发南北矛盾。1828年“可憎关税”激化分歧，甚至导致南卡罗来纳州威胁**废止联邦法律**。内战期间关税飙升，战后保护主义持续，直至20世纪初效率提升推动税率下降。1929年《斯姆特-霍利关税法》大幅提高税率，加剧大萧条，成为历史教训。

---
