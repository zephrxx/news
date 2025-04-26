---
layout: page
title: 勒西科技日报 - 2025年04月25日
date: 2025-04-25 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 2万美元的美国制造电动皮卡：无油漆、无音响、无屏幕；
1. FBI逮捕被控协助移民逃避执法的法官；
1. 当修改/etc/hosts文件导致Substack编辑器崩溃：一次Web内容过滤的探索；
1. 华盛顿检方质疑维基百科非营利组织资格；
1. 70%体积缩减，100%精度保留：动态长度浮点数实现无损LLM压缩；

以上是今天的前五条黑科技新闻标题。

总共25条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 2万美元的美国制造电动皮卡：无油漆、无音响、无屏幕 
<small>🔗 [theverge.com](https://www.theverge.com/electric-cars/655527/slate-electric-truck-price-paint-radio-bezos): A $20k American-made electric pickup with no paint, no stereo, no screen</small>


| 🔥🔥: 1086 \| 💬: [962](https://news.ycombinator.com/item?id=43794284) \| 🗓️ 2025-04-25


<br />
Slate Auto推出了一款**极简主义电动皮卡**，售价低于2万美元（含联邦补贴）。这款车采用**未上漆的聚丙烯复合材料车身**，设计为耐用且可个性化改装，支持DIY升级（如后座套件）。车内**无娱乐系统**，仅配备基础仪表盘，续航150英里。其低成本制造模式（省去喷漆和金属冲压）吸引了包括杰夫·贝索斯在内的投资者。预计2026年交付，挑战消费者对“数字化 detox”的接受度。

---

## <a name="2"></a>2. FBI逮捕被控协助移民逃避执法的法官 
<small>🔗 [apnews.com](https://apnews.com/article/immigration-judge-arrested-7997186bbca5730e70a25f2347e631f6): FBI arrests judge accused of helping man evade immigration authorities</small>


| 🔥🔥: 939 \| 💬: [866](https://news.ycombinator.com/item?id=43794576) \| 🗓️ 2025-04-25


<br />
美国密尔沃基县法官**汉娜·杜根**因涉嫌妨碍移民执法被捕。FBI指控她在法庭上**故意误导**联邦探员，导致一名面临轻罪指控的墨西哥移民**爱德华多·弗洛雷斯·鲁伊斯**逃脱拘留。事件引发争议，部分法官批评ICE在法院逮捕移民的做法会阻碍司法程序。杜根曾任贫困律师，2016年当选法官。此案是特朗普政府重启后首例地方官员因干预移民执法被起诉的案件。

---

## <a name="3"></a>3. 当修改/etc/hosts文件导致Substack编辑器崩溃：一次Web内容过滤的探索 
<small>🔗 [scalewithlee.substack.com](https://scalewithlee.substack.com/p/when-etchsts-breaks-your-substack): Writing "/etc/hosts" breaks the Substack editor</small>


| 🔥🔥: 516 \| 💬: [284](https://news.ycombinator.com/item?id=43793526) \| 🗓️ 2025-04-25


<br />
作者在Substack撰写技术文章时发现，输入系统路径如**/etc/hosts**会触发编辑器报错，显示“网络错误”。经排查，这是**Web应用防火墙(WAF)**的安全机制所致，旨在防范**路径遍历攻击**和**命令注入攻击**。尽管保护意图合理，但该过滤机制误伤了技术内容，且错误提示模糊。文章探讨了安全与用户体验的平衡，并建议平台优化过滤逻辑，例如区分代码块或提供明确提示。目前，作者通过改写路径（如添加引号）临时解决该问题。

---

## <a name="4"></a>4. 华盛顿检方质疑维基百科非营利组织资格 
<small>🔗 [washingtonpost.com](https://www.washingtonpost.com/technology/2025/04/25/wikipedia-nonprofit-ed-martin-letter/): Wikipedia’s nonprofit status questioned by D.C. U.S. attorney</small>


| 🔥🔥: 395 \| 💬: [328](https://news.ycombinator.com/item?id=43799302) \| 🗓️ 2025-04-25


<br />
美国华盛顿特区代理检察官埃德·马丁致信**维基媒体基金会**，指控其作为免税非营利组织，**纵容外国势力操纵内容**并传播对美 propaganda，可能违反501(c)(3)条款。信中要求基金会说明编辑审核机制及反干预措施。此事与特朗普政府近期针对自由派机构的行动相呼应，保守派长期批评维基百科存在**左倾偏见**。基金会回应称平台内容由全球志愿者协作确保中立，未直接回应指控。马丁此前曾质疑其他机构，其本人与俄罗斯媒体的关联亦受争议。

---

## <a name="5"></a>5. 70%体积缩减，100%精度保留：动态长度浮点数实现无损LLM压缩 
<small>🔗 [arxiv.org](https://arxiv.org/abs/2504.11651): Lossless LLM compression for efficient GPU inference via dynamic-length float</small>


| 🔥🔥: 310 \| 💬: [102](https://news.ycombinator.com/item?id=43796935) \| 🗓️ 2025-04-25


<br />
本文提出**DFloat11**框架，通过动态长度浮点编码对LLM权重进行**无损压缩**，模型体积减少30%且输出与原始模型完全一致。该方法利用BFloat16权重的低熵特性，结合熵编码实现信息最优压缩，并设计了专用GPU内核支持高效在线解压。实验证明，DFloat11在Llama-3.1等模型上显著提升推理吞吐量（1.9-38.8倍），并支持单节点部署810GB的超大模型。

---

## <a name="6"></a>6. 欧拉模块旋钮创意：磁编码器与插孔的混合设计 
<small>🔗 [mitxela.com](https://mitxela.com/projects/euroknob): Eurorack Knob Idea</small>


| 🔥🔥: 263 \| 💬: [100](https://news.ycombinator.com/item?id=43793288) \| 🗓️ 2025-04-25


<br />
作者设计了一款**磁编码旋钮**，将3.5mm音频插孔与AS5600磁编码器结合，通过嵌入插头的磁铁实现旋钮与信号线的功能切换。这一设计旨在解决模块化合成器（**Eurorack**）因空间限制而牺牲操作性的问题。原型测试成功，但商业化面临成本与兼容性挑战，例如需搭配电压控制电位器。尽管专利与量产难度高，作者认为**同轴电位器插孔**或更具市场潜力。项目开源，但坦言缺乏商业运作能力，呼吁合作者参与。

---

## <a name="7"></a>7. GCC 15.1 正式发布：重大更新与致谢 
<small>🔗 [gcc.gnu.org](https://gcc.gnu.org/gcc-15/): GCC 15.1</small>


| 🔥🔥: 220 \| 💬: [130](https://news.ycombinator.com/item?id=43792248) \| 🗓️ 2025-04-25


<br />
GCC开发团队于2025年4月25日发布了**GCC 15.1**，这是继GCC 14.x后的**重大版本更新**，包含多项新功能和改进。GCC原名“GNU C编译器”，现因支持多语言更名为**GNU编译器集合**。团队特别感谢全球贡献者的代码、测试与反馈，并推荐通过官网、镜像站或邮件列表获取帮助。本文档允许自由转载，但需保留版权声明。

---

## <a name="8"></a>8. AI时代如何避免技能退化 
<small>🔗 [addyo.substack.com](https://addyo.substack.com/p/avoiding-skill-atrophy-in-the-age): Avoiding skill atrophy in the age of AI</small>


| 🔥🔥: 219 \| 💬: [235](https://news.ycombinator.com/item?id=43791474) \| 🗓️ 2025-04-25


<br />
随着AI编程助手的普及，开发者面临**技能萎缩**的风险——过度依赖AI可能导致**批判性思维**和基础编码能力退化。研究表明，长期依赖AI会削弱独立解决问题的能力，甚至影响系统设计等高阶技能。文章建议将AI视为协作工具而非万能答案，通过定期练习无AI编码、主动验证AI输出、优先尝试自主解决问题等方式保持技能敏锐。关键在于平衡效率与深度学习，避免用短期便利换取长期专业能力的空心化。

---

## <a name="9"></a>9. 用OpenAI图像API打造个性化填色书服务 
<small>🔗 [clevercoloringbook.com](https://clevercoloringbook.com/): Show HN: I used OpenAI's new image API for a personalized coloring book service</small>


| 🔥🔥: 165 \| 💬: [88](https://news.ycombinator.com/item?id=43791992) \| 🗓️ 2025-04-25


<br />
这项服务可将**用户上传的照片**转换为黑白线稿，制作成实体填色书，售价**23.99美元**。操作简单：上传8-24张照片，系统通过**OpenAI的Sora模型**处理并印刷成册，邮寄到家。需遵守OpenAI内容政策，仅用于订单通知的联系信息严格保密。支持全球多国配送，结账自动生成账户方便查询。

---

## <a name="10"></a>10. 大型复制项目未能验证生物医学研究结果 
<small>🔗 [nature.com](https://www.nature.com/articles/d41586-025-01266-x): Reproducibility project fails to validate dozens of biomedical studies</small>


| 🔥🔥: 163 \| 💬: [85](https://news.ycombinator.com/item?id=43795300) \| 🗓️ 2025-04-25


<br />
一项由50多个研究团队参与的**大规模复制研究**发现，巴西生物医学研究中仅有不到一半的实验结果可被复现。该项目聚焦于三种常用实验方法，并分析了1998至2017年间发表的论文。结果显示，**21%的实验**符合复现标准，且原始研究的**效应量平均高估60%**。研究者呼吁通过政策或学术改革提升科研可靠性。该预印本尚未经同行评审。

---

## <a name="11"></a>11. 美防长被曝私设未加密网络使用Signal 
<small>🔗 [apnews.com](https://apnews.com/article/hegseth-signal-chat-dirty-internet-line-6a64707f10ca553eb905e5a70e10bd9d): Hegseth had an unsecured internet line set up in his office to connect to Signal</small>


| 🔥🔥: 150 \| 💬: [153](https://news.ycombinator.com/item?id=43792157) \| 🗓️ 2025-04-25


<br />
美国防部长**皮特·赫格塞思**被曝在办公室私设**未加密网络线路**，绕过五角大楼安全协议，用于在个人电脑上使用加密通讯应用**Signal**。此举可能使敏感国防信息面临黑客或监控风险。该线路被称为“脏线”，直接连接公共互联网，缺乏军方网络安全防护。赫格塞思此前被曝在Signal群聊中泄露军事行动细节，目前正接受国防部调查。白宫虽表态支持，但两党议员均对此提出质疑。

---

## <a name="12"></a>12. Magnitude：开源AI驱动的Web应用测试框架 
<small>🔗 [github.com](https://github.com/magnitudedev/magnitude): Show HN: Magnitude – open-source, AI-native test framework for web apps</small>


| 🔥🔥: 141 \| 💬: [33](https://news.ycombinator.com/item?id=43796003) \| 🗓️ 2025-04-25


<br />
Magnitude是一款**开源AI原生测试框架**，专为Web应用设计，结合**视觉AI代理**与自然语言交互，实现端到端测试。用户可通过自然语言编写测试用例，框架内置**智能规划代理**和快速视觉执行代理，自动适应UI变化。支持本地或CI/CD环境运行，兼容多种LLM模型（如Gemini、Moondream）。提供5,000次免费Moondream请求，适合高效测试开发。

---

## <a name="13"></a>13. 《我曾写过一本叫〈烂城记〉的书，当时觉得挺好笑》 
<small>🔗 [samj.substack.com](https://samj.substack.com/p/that-joke-isnt-funny-any-more): I wrote a book called "Crap Towns". It seemed funny at the time</small>


| 🔥🔥: 140 \| 💬: [74](https://news.ycombinator.com/item?id=43799820) \| 🗓️ 2025-04-25


<br />
作者回顾了2003年出版的《烂城记》，这本书通过网友提名和调侃，盘点英国最差城镇，意图以幽默引发对城市问题的讨论。如今，许多人认为该书在**当下政治敏感度**高涨的时代难以出版。作者反思了**幽默的边界**，承认书中尖锐的讽刺可能加剧了社会负面情绪，但也担忧当代对玩笑的过度审查会扼杀批判性思考。尽管部分人认为这类作品已过时，作者仍强调**自嘲式幽默**的价值——它能揭示真相，但需平衡善意与冒犯。

---

## <a name="14"></a>14. 用神经网络模拟世界 
<small>🔗 [madebyoll.in](https://madebyoll.in/posts/world_emulation_via_dnn/): World Emulation via Neural Network</small>


| 🔥🔥: 126 \| 💬: [22](https://news.ycombinator.com/item?id=43798757) \| 🗓️ 2025-04-25


<br />
作者通过**神经网络**将公寓附近的森林小径转化为可交互的虚拟世界，用户可在浏览器中离线探索。与传统游戏不同，该世界完全由神经网络实时生成图像，无需预设几何或光影代码。为实现这一效果，作者用手机录制了15分钟视频及运动数据，并升级了训练方法（如增加**多尺度输入**和**对抗损失**）。尽管当前效果仍不完美，但作者认为，**神经世界**像早期摄影一样，未来将随技术进步变得更真实、便捷，甚至成为独立创作媒介。

---

## <a name="15"></a>15. 用Lean定理证明器形式化《数学原理》 
<small>🔗 [github.com](https://github.com/ndrwnaguib/principia): Show HN: Formalizing Principia Mathematica using Lean</small>


| 🔥🔥: 123 \| 💬: [28](https://news.ycombinator.com/item?id=43797256) \| 🗓️ 2025-04-25


<br />
该项目旨在使用**Lean4**定理证明器对伯特兰·罗素的《数学原理》第一卷进行形式化验证，力求严格遵循原书逻辑。作者通过**元编程**复现了罗素独特的点记法（Peano-Russell notation），并开发了`Syll`战术来模拟原书的演绎推理链。尽管该形式化工作目前仅获8星关注，且存在更成熟的Coq版本，但作者认为此项目对理解数学基础构建极具启发意义。项目强调**严谨性**，每个定理均附带LaTeX片段与原书对照，未来或将继续形式化塔尔斯基的《逻辑、语义与元数学》。

---

## <a name="16"></a>16. Curry：一种融合函数式与逻辑编程的多范式语言 
<small>🔗 [curry-lang.org](https://curry-lang.org/): Curry: A functional logic programming language</small>


| 🔥🔥: 122 \| 💬: [25](https://news.ycombinator.com/item?id=43797212) \| 🗓️ 2025-04-25


<br />
Curry是一种**声明式多范式编程语言**，无缝整合了**函数式编程**（嵌套表达式、高阶函数、强类型、惰性求值）和**逻辑编程**（非确定性、内置搜索、自由变量、部分数据结构）的特性。其核心优势包括纯声明式设计、自动类型推断、非确定性操作支持，以及通过自由变量实现灵活的模式匹配。Curry的开发由国际社区推动，提供PAKCS等编译器、包管理工具CPM及API搜索引擎Curr(y)gle，适用于教学与研究。

---

## <a name="17"></a>17. 大语言模型对劳动力市场影响有限 
<small>🔗 [bfi.uchicago.edu](https://bfi.uchicago.edu/wp-content/uploads/2025/04/BFI_WP_2025-56-1.pdf): Large language models, small labor market effects [pdf]</small>


| 🔥🔥: 116 \| 💬: [28](https://news.ycombinator.com/item?id=43791385) \| 🗓️ 2025-04-25


<br />
该研究探讨了**大语言模型**（如GPT等）对就业市场的实际影响，发现其替代效应目前较为有限。尽管这类技术在部分领域（如文案生成、客服等）展现出潜力，但整体上尚未对劳动力市场造成显著冲击。研究指出，**技术应用速度**和**职业适应性**是关键变量，而当前影响主要集中在**特定低技能岗位**。未来需持续观察技术与人力协作的长期趋势。

---

## <a name="18"></a>18. BugStalker：一款专为Rust设计的现代调试工具 
<small>🔗 [github.com](https://github.com/godzie44/BugStalker): Show HN: BugStalker - a modern Rust debugger</small>


| 🔥🔥: 109 \| 💬: [15](https://news.ycombinator.com/item?id=43793627) \| 🗓️ 2025-04-25


<br />
BugStalker是一款针对**Linux x86-64平台**的**Rust原生调试器**，专注于简化调试流程并深度集成Rust特性。支持**断点调试、多线程应用检查**和**Tokio运行时分析**，提供控制台与TUI双模式切换。其扩展架构允许通过Oracle机制增强功能，且内置无需代码修改的Tokio监控工具。项目采用MIT协议开源，目前获723星标，欢迎开发者贡献代码或提出建议。

---

## <a name="19"></a>19. 论文转代码：机器学习论文的自动化代码生成 
<small>🔗 [arxiv.org](https://arxiv.org/abs/2504.17192): Paper2Code: Automating Code Generation from Scientific Papers</small>


| 🔥: 99 \| 💬: [13](https://news.ycombinator.com/item?id=43796419) \| 🗓️ 2025-04-25


<br />
该研究提出**PaperCoder**，一个基于**多智能体大语言模型（LLM）**的框架，用于将机器学习论文自动转化为可运行的代码库。其工作流程分为三阶段：**规划**（生成系统架构与配置文件）、**分析**（解析实现细节）和**生成**（输出模块化代码）。实验表明，该框架在**PaperBench**基准测试中显著优于基线模型，并能生成高质量、符合论文原意的代码实现，解决了研究复现效率低下的问题。

---

## <a name="20"></a>20. 伯克利开源轻量级人形机器人 
<small>🔗 [lite.berkeley-humanoid.org](https://lite.berkeley-humanoid.org/): Berkeley Humanoid Lite – Open-source robot</small>


| 🔥: 89 \| 💬: [4](https://news.ycombinator.com/item?id=43800002) \| 🗓️ 2025-04-25


<br />
当前商用**人形机器人**普遍存在成本高、**闭源**、技术不透明等问题，限制了领域发展。为此，伯克利团队推出**开源**设计「Berkeley Humanoid Lite」，采用模块化3D打印齿轮箱和易获取组件，总成本控制在5000美元内。通过优化摆线齿轮设计提升塑料部件的耐用性，并验证了强化学习控制策略的仿真到实机迁移能力。所有硬件设计、代码及训练框架均开源，旨在推动人形机器人技术的民主化发展。

---

## <a name="21"></a>21. D语言编程教程与参考手册 
<small>🔗 [ddili.org](https://ddili.org/ders/d.en/): Programming in D: Tutorial and Reference</small>


| 🔥: 85 \| 💬: [40](https://news.ycombinator.com/item?id=43798009) \| 🗓️ 2025-04-25


<br />
本书是Ali Çehreli编写的**D语言**权威指南，涵盖从基础语法到高级特性的全面内容。重点包括**基本数据类型**、**控制结构**、**函数与模板**、**面向对象编程**（如类和继承），以及并发编程（如**并行计算**和消息传递）。提供多种格式（PDF、EPUB等）和代码示例下载，适合初学者和进阶开发者。书中还涉及内存管理、契约编程等深度主题，是学习D语言的实用资源。

---

## <a name="22"></a>22. 2025年了，为何./configure还是单线程？ 
<small>🔗 [tavianator.com](https://tavianator.com/2025/configure.html): Parallel ./configure</small>


| 🔥: 80 \| 💬: [74](https://news.ycombinator.com/item?id=43799396) \| 🗓️ 2025-04-25


<br />
作者Tavian Barnes在GitHub上吐槽：2025年居然还要忍受**单线程的./configure脚本**，它逐项检测系统环境（如编译器、头文件、函数库等），过程冗长低效。尽管现代硬件支持**并行处理**，但这类基础工具仍未优化，凸显了开源生态中**遗留技术债**的问题。文中详细列出了数十项检测内容，从基础工具兼容性到Unicode支持，耗时且重复。

---

## <a name="23"></a>23. 现代电子表格工具GS-Calc：支持Python集成与大数据处理 
<small>🔗 [citadel5.com](https://citadel5.com/gs-calc.htm): Show HN: A modern spreadsheet with Python integration</small>


| 🔥: 74 \| 💬: [10](https://news.ycombinator.com/item?id=43796898) \| 🗓️ 2025-04-25


<br />
GS-Calc是一款**高性能电子表格软件**，专为处理**超大规模数据集**设计，支持3200万行×1.6万列的数据操作，无文件大小限制。其核心优势包括：**极速加载/计算**（如百万级VLOOKUP即时更新）、**多核并行处理**（支持64核）、**Python集成**（自定义函数返回矩阵/图像等）。此外，提供蒙特卡洛模拟、正则表达式过滤、动态拆分合并XLSX/CSV文件等功能，兼容多种数据库格式，且完全离线运行。适用于金融分析、科研建模等场景。

---

## <a name="24"></a>24. 用代码设计LED点阵PCB 
<small>🔗 [docs.tscircuit.com](https://docs.tscircuit.com/tutorials/building-led-matrix): I designed my LED matrix PCB with code</small>


| 🔥: 74 \| 💬: [30](https://news.ycombinator.com/item?id=43798832) \| 🗓️ 2025-04-25


<br />
本教程演示如何通过**Raspberry Pi Pico**和**WS2812B智能LED**构建3x5 WiFi可控点阵，适用于标牌、数据可视化等场景。核心步骤包括：使用`tscircuit`工具链式连接LED、通过**GP6引脚**控制数据流，并利用网格函数快速布局15颗LED。最终通过网页界面实现远程调光调色，所有电路设计均以代码生成，可直接导出PCB文件至JLCPCB生产。

---

## <a name="25"></a>25. 从微观视角看美国财政：削减开支真的能减少国债吗？ 
<small>🔗 [debtinperspective.com](https://www.debtinperspective.com/): A Scaled Down Look at Spending, Revenue, and What's Being Cut</small>


| 🔥: 71 \| 💬: [40](https://news.ycombinator.com/item?id=43795703) \| 🗓️ 2025-04-25


<br />
美国国债已达**36万亿美元**，但人类大脑难以理解如此庞大的数字。若将财政数据缩小3600万倍，可发现所谓"削减开支"（如取消社会福利拨款）仅节省15美分，对债务影响微乎其微。**利息支出**每年耗资5000亿美元，而取消弱势群体援助等政策虽社会代价巨大，却仅占预算的千万分之一。真正有效的解决方案是向企业海外收入征税或征收碳排放税，十年可节省数千亿美元。财政问题的核心在于**规模认知偏差**与**象征性削减**的无效性。

---
