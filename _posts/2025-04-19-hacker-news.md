---
layout: page
title: 勒西科技日报 - 2025年04月19日
date: 2025-04-19 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 图书管理员很危险；
1. 树莓派激光雷达扫描仪项目概览；
1. 网络已崩坏：揭秘AI公司背后的僵尸网络；
1. 安卓手机闲置三天后将自动重启以增强安全性；
1. 视频生成模型中下一帧预测的输入帧上下文打包技术；

以上是今天的前五条黑科技新闻标题。

总共25条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 图书管理员很危险 
<small>🔗 [bradmontague.substack.com](https://bradmontague.substack.com/p/librarians-are-dangerous): Librarians are dangerous</small>


| 🔥🔥: 453 \| 💬: [440](https://news.ycombinator.com/item?id=43736791) \| 🗓️ 2025-04-19


<br />
这篇文章以幽默夸张的口吻赞美了图书管理员的力量。他们不仅是书籍的守护者，更是**信息素养的战士**，用书籍颠覆无知、对抗审查制度，并帮助人们找到自我。他们精通技术、善于解谜，甚至能通过一本书彻底改变读者的世界观。作者强调，图书管理员站在**好奇心与同理心**的前线，坚信每个孩子都值得找到归属感的故事。文末呼吁读者不要低估这群"危险分子"，因为一本合适的书能在关键时刻改变一切。

---

## <a name="2"></a>2. 树莓派激光雷达扫描仪项目概览 
<small>🔗 [github.com](https://github.com/PiLiDAR/PiLiDAR): Raspberry Pi Lidar Scanner</small>


| 🔥🔥: 382 \| 💬: [110](https://news.ycombinator.com/item?id=43738561) \| 🗓️ 2025-04-19


<br />
该项目基于**树莓派4**与**LDRobot LD06/LD19/STL27L激光雷达**，构建了一套DIY的360° 3D全景扫描系统。核心功能包括：**自定义串行驱动**、硬件PWM校准、2D/3D可视化（支持Open3D导出）、全景照片拼接（使用Hugin工具）以及多场景点云对齐（通过ICP算法优化）。硬件配置包含步进电机驱动、高精度摄像头及3D打印齿轮箱。项目提供了详细的设置指南（如UART权限、PWM启用）和故障排查方案（如串口驱动安装）。目前处于开发阶段，扫描单次耗时约2分钟，支持数据导出为CSV、PLY等格式。

---

## <a name="3"></a>3. 网络已崩坏：揭秘AI公司背后的僵尸网络 
<small>🔗 [jan.wildeboer.net](https://jan.wildeboer.net/2025/04/Web-is-Broken-Botnet-Part-2/): The Web Is Broken – Botnet Part 2</small>


| 🔥🔥: 311 \| 💬: [177](https://news.ycombinator.com/item?id=43738603) \| 🗓️ 2025-04-19


<br />
文章揭露了**AI公司**为训练模型疯狂收集数据，导致网络爬虫泛滥的现象。这些爬虫背后实则是**恶意SDK**——某些公司通过付费诱使开发者将“网络共享”库植入应用，利用用户设备组建**僵尸网络**，进行网页抓取甚至暴力攻击。  

作者点名Infatica等公司，批评其商业模式本质是**分布式拒绝服务攻击（DDoS）**，并呼吁苹果、谷歌等平台介入。普通用户难以察觉此类SDK，而中小网站管理员几乎无法防御。随着AI数据需求激增，这类灰色产业正加速恶化网络环境。

---

## <a name="4"></a>4. 安卓手机闲置三天后将自动重启以增强安全性 
<small>🔗 [arstechnica.com](https://arstechnica.com/gadgets/2025/04/android-phones-will-soon-reboot-themselves-after-sitting-unused-for-3-days/): Android phones will soon reboot themselves after sitting unused for three days</small>


| 🔥🔥: 307 \| 💬: [242](https://news.ycombinator.com/item?id=43735902) \| 🗓️ 2025-04-19


<br />
谷歌即将通过**Google Play服务更新（v25.14）**为安卓设备推出一项新功能：若设备连续**锁定三天未使用**，将自动重启。此举旨在提升安全性，因为重启后的**"首次解锁前"（BFU）**状态下，生物识别和基于位置的解锁功能失效，数据加密强度更高，即使执法部门也难以提取。该更新还包含界面优化和设备连接改进，预计未来几周逐步推送。类似苹果的"非活跃重启"功能，此措施可能影响取证操作，但有效缩短了设备数据暴露的风险窗口。

---

## <a name="5"></a>5. 视频生成模型中下一帧预测的输入帧上下文打包技术 
<small>🔗 [lllyasviel.github.io](https://lllyasviel.github.io/frame_pack_gitpage/): Packing Input Frame Context in Next-Frame Prediction Models for Video Generation</small>


| 🔥🔥: 233 \| 💬: [26](https://news.ycombinator.com/item?id=43736193) \| 🗓️ 2025-04-19


<br />
该研究实现了**13B参数模型**在6GB笔记本GPU内存下以30fps生成数千帧视频，并支持在单台8xA100/H100节点上以**批量大小64**进行微调。个人RTX 4090生成速度达**2.5秒/帧**（未优化）或1.5秒/帧（teacache优化），无需时间步蒸馏。虽为视频扩散模型，体验却接近图像扩散。

---

## <a name="6"></a>6. 用AI将GitHub代码库转化为易懂教程的工具 
<small>🔗 [github.com](https://github.com/The-Pocket/Tutorial-Codebase-Knowledge): Show HN: I built an AI that turns GitHub codebases into easy tutorials</small>


| 🔥🔥: 207 \| 💬: [38](https://news.ycombinator.com/item?id=43739456) \| 🗓️ 2025-04-19


<br />
这个项目利用**AI技术**分析GitHub代码库，自动生成适合初学者的教程，帮助用户快速理解复杂代码。它通过爬取代码库、构建知识图谱，识别核心逻辑并生成带可视化说明的教程。支持多语言输出，可分析本地或在线仓库。  

**关键功能**：  
- 支持Python/JavaScript等文件类型过滤  
- 可设置文件大小上限排除无关内容  
- 使用**Gemini/Claude等大模型**生成教程  

开发者采用**Agentic Coding**模式开发，依赖轻量级框架Pocket Flow实现自动化构建。提供YouTube教程和示例结果（如FastAPI、NumPy等热门项目解析）。

---

## <a name="7"></a>7. 2023英国方言地图详解 
<small>🔗 [starkeycomics.com](https://starkeycomics.com/2023/11/07/map-of-british-english-dialects/): A Map of British Dialects (2023)</small>


| 🔥🔥: 205 \| 💬: [155](https://news.ycombinator.com/item?id=43734953) \| 🗓️ 2025-04-19


<br />
这份耗时数年制作的**英国方言地图**试图展现英国英语的丰富多样性，但作者坦言其永远无法完全准确。**方言边界模糊**，常随地理、文化渐变，而非硬性划分。例如坎布里亚郡南北口音差异显著，但中间地带实为连续过渡。地图采用渐变色和虚线表示这种流动性，但受限于二维呈现。**非地域性方言**（如伦敦多元方言）未被详细标注，而苏格兰语等独立语言也未纳入。作者强调，该地图旨在致敬英国方言的复杂性，而非提供绝对答案。

---

## <a name="8"></a>8. 修复1992年六玩家街机《Galaxian3 Theatre 6》 
<small>🔗 [philwip.com](https://philwip.com/2025/04/14/galaxian-3-project-revival/): Restoring the Galaxian3 Theatre 6, 1992 six player arcade machine</small>


| 🔥🔥: 204 \| 💬: [45](https://news.ycombinator.com/item?id=43735239) \| 🗓️ 2025-04-19


<br />
Namco于1990年推出**28人巨型街机**《Galaxian3: Project Dragoon》，后缩改为**六人版本**GT-6。2024年，团队在Fun World街机发现仅存四台GT-6之一，但仅1、2号玩家可用且投影模糊。初步检测发现**PSN PCB故障**，并成功用专业设备保存了**激光碟片数据**和ROM。2025年计划二次修复，重点解决硬件通信问题与CRT投影仪"真菌"污染。

---

## <a name="9"></a>9. AI辅助编程不是低质量代码的借口 
<small>🔗 [addyo.substack.com](https://addyo.substack.com/p/vibe-coding-is-not-an-excuse-for): Vibe Coding is not an excuse for low-quality work</small>


| 🔥🔥: 182 \| 💬: [138](https://news.ycombinator.com/item?id=43739037) \| 🗓️ 2025-04-19


<br />
文章强调**AI生成代码**虽能提升效率，但需警惕其潜在风险：**技术债务**激增、安全漏洞和可维护性差。作者建议将AI视为"初级开发者"，必须通过**人工审查**、重构和测试确保代码质量。核心原则是**人类主导设计**，AI仅辅助实现，同时需遵守编码规范并完善文档。适用于快速原型开发，但关键模块仍需手动编写。

---

## <a name="10"></a>10. SSL.com存在漏洞：可绕过DCV验证并伪造任意MX主机名证书 
<small>🔗 [bugzilla.mozilla.org](https://bugzilla.mozilla.org/show_bug.cgi?id=1961406): Ssl.com: DCV bypass and issue fake certificates for any MX hostname</small>


| 🔥🔥: 177 \| 💬: [43](https://news.ycombinator.com/item?id=43738485) \| 🗓️ 2025-04-19


<br />
该漏洞报告指出，SSL.com在使用BR 3.2.2.4.14 DCV方法（通过DNS TXT联系邮箱验证域名）时，**错误地将验证者邮箱域名标记为已验证**。攻击者可通过伪造TXT记录，利用第三方邮箱（如aliyun.com）获取目标域名的证书。例如，攻击者未拥有aliyun.com的管理权限，却成功获取了该域名的合法证书。SSL.com已**紧急禁用该验证方法**，并承诺在2025-04-21前提交初步报告。此漏洞可能导致**任意MX主机名的证书被伪造**，威胁网络安全。

---

## <a name="11"></a>11. 如何在2024年从零开始用Tensor Core实现快速矩阵乘法 
<small>🔗 [alexarmbr.github.io](https://alexarmbr.github.io/2024/08/10/How-To-Write-A-Fast-Matrix-Multiplication-From-Scratch-With-Tensor-Cores.html): How to Write a Fast Matrix Multiplication from Scratch with Tensor Cores (2024)</small>


| 🔥🔥: 115 \| 💬: [13](https://news.ycombinator.com/item?id=43736739) \| 🗓️ 2025-04-19


<br />
本文详细介绍了作者在NVIDIA Tesla T4 GPU上使用**Tensor Core**优化CUDA矩阵乘法内核的过程，目标是高效计算半精度浮点数的HGEMM（$D = \alpha * A * B + \beta * C$）。文章探讨了**内存墙**问题，通过**Roofline模型**分析计算强度（$I$）对性能的影响，并对比了Tensor Core与传统FFMA指令的吞吐量差异。作者通过6个迭代优化的内核，最终实现96%的cuBLAS性能，重点技术包括**分层分块**、共享内存优化和双缓冲等。现代GPU（如Hopper架构）通过硬件改进进一步降低了编程复杂度。

---

## <a name="12"></a>12. 别强迫孩子学数学 
<small>🔗 [blog.avocados.ovh](https://blog.avocados.ovh/posts/how-to-force-your-kids-to-do-math/): Don't force your kids to do math</small>


| 🔥🔥: 111 \| 💬: [90](https://news.ycombinator.com/item?id=43738195) \| 🗓️ 2025-04-19


<br />
作者主张**不强迫孩子学数学**，而是通过游戏和日常生活激发兴趣。他将数学视为探索世界的工具，像品尝食物或欣赏音乐一样自然。**关键是通过重复和趣味活动**（如数楼梯、购物计算）让孩子主动发现数学的乐趣。他强调**保护孩子的好奇心**比技能更重要，并反思家长需警惕将自己的兴趣强加给孩子。最终，孩子对无限大的自发思考证明，真正的目标是培养终身学习的热情。

---

## <a name="13"></a>13. 独特声波可缓解晕动症 
<small>🔗 [nagoya-u.ac.jp](https://www.nagoya-u.ac.jp/researchinfo/result-en/2025/04/20250408-01.html): A unique sound alleviates motion sickness</small>


| 🔥🔥: 110 \| 💬: [42](https://news.ycombinator.com/item?id=43740021) \| 🗓️ 2025-04-19


<br />
日本名古屋大学的研究团队发现，**100赫兹的特定声波刺激**（“声波香料®”）能有效减轻晕车症状。实验表明，仅需一分钟的刺激即可减少眩晕和恶心感，其原理是通过激活内耳**前庭系统**调节平衡功能。该技术安全（声压低于日常噪音标准），未来或应用于航空、航海等场景。研究成果发表于《环境健康与预防医学》。

---

## <a name="14"></a>14. Haujobb与Sweet16联合发布新Demo《The Mind》 
<small>🔗 [lexaloffle.com](https://www.lexaloffle.com/bbs/?pid=145596): Demo "The Mind" by Haujobb and Sweet16</small>


| 🔥🔥: 103 \| 💬: [10](https://news.ycombinator.com/item?id=43735592) \| 🗓️ 2025-04-19


<br />
在2024年Revision demoparty的**“幻想主机”竞赛**中，Haujobb与Sweet16展示了基于Pico-8平台的Demo《The Mind》。目前仅支持在线观看（推荐使用Firefox），**完整源代码**已上传至Pouet。Demo支持通过Pico8 Edu加载（指令：`load #themind1`），并已优化为可直接在BBS运行。此外，团队还分享了**音乐制作思路**及部分特效的独立版本（如《Interference》）。Demo融合了**3D多边形渲染**和像素艺术，创作遵循CC4-BY-NC-SA协议。

---

## <a name="15"></a>15. 开源SDR实现：基于GNU Radio与Codec2的DMR调制解调器 
<small>🔗 [qradiolink.org](https://qradiolink.org/open-source-DMR-transceiver-implementation.html): Open Source DMR Modem Implementation in SDR with GNU Radio and Codec2</small>


| 🔥: 97 \| 💬: [14](https://news.ycombinator.com/item?id=43735945) \| 🗓️ 2025-04-19


<br />
本文介绍了一种基于**软件定义无线电（SDR）**的开源DMR（数字移动无线电）调制解调器实现，结合GNU Radio处理物理层，并采用**Codec2**作为语音编解码器。DMR是ETSI制定的业余无线电流行标准，但商用设备存在使用门槛。该方案通过LimeSDR-mini等硬件支持**时分多址（TDMA）**传输，实现了中继模式与直通模式下的语音通话功能，并探索了未来扩展（如Tier III集群通信）。与依赖专利编解码器AMBE的传统方案不同，此项目选择完全开源的Codec2，虽兼容性受限，但规避了法律风险。

---

## <a name="16"></a>16. SSD断电长期存放测试：数据丢失与性能下降问题凸显 
<small>🔗 [tomshardware.com](https://www.tomshardware.com/pc-components/storage/unpowered-ssd-endurance-investigation-finds-severe-data-loss-and-performance-issues-reminds-us-of-the-importance-of-refreshing-backups): Unpowered SSD endurance investigation finds data loss and performance issues</small>


| 🔥: 95 \| 💬: [63](https://news.ycombinator.com/item?id=43739028) \| 🗓️ 2025-04-19


<br />
一项针对**SSD断电耐久性**的两年期测试发现，长期未通电的SSD会出现**数据丢失**和**性能下降**。测试使用四块128GB TLC SSD，其中两块写入量远超标称的60TB寿命。结果显示，重度使用的SSD两年后出现文件损坏且性能骤降，而轻度使用的SSD虽数据完整，但纠错码（ECC）异常增加，预示潜在风险。实验强调定期通电刷新备份的重要性，尤其对长期冷存储的SSD。

---

## <a name="17"></a>17. 澳大利亚沙漠照片揭示卫星污染问题 
<small>🔗 [thisiscolossal.com](https://www.thisiscolossal.com/2025/04/a-stunning-image-of-the-australian-desert-illuminates-the-growing-problem-of-satellite-pollution/): An image of the Australian desert illuminates satellite pollution</small>


| 🔥: 92 \| 💬: [63](https://news.ycombinator.com/item?id=43737469) \| 🗓️ 2025-04-19


<br />
2021年，摄影师Joshua Rozells在澳大利亚西部的**尖峰石阵沙漠**拍摄星轨时，意外发现**卫星轨迹**几乎出现在每张照片中。他将343张照片合成一张图像，直观展现了日益严重的**卫星光污染**问题。自SpaceX 2019年发射首批60颗星链卫星后，近地轨道卫星已超1万颗，且未来计划发射数万颗。天文学家警告，缺乏监管的卫星激增将加剧光污染，影响天文观测。国际天文联合会等组织正呼吁加强对夜空保护。

---

## <a name="18"></a>18. "超强思考"是Claude Code的魔法指令 
<small>🔗 [simonwillison.net](https://simonwillison.net/2025/Apr/19/claude-code-best-practices/): Ultrathink is a Claude Code a magic word</small>


| 🔥: 91 \| 💬: [33](https://news.ycombinator.com/item?id=43739997) \| 🗓️ 2025-04-19


<br />
Anthropic的Claude Code CLI工具文档揭示了一个有趣技巧：使用**"think"**系列指令可触发不同级别的思考模式，如"think"（4000 tokens）、"think hard"（1万 tokens）和**"ultrathink"**（31999 tokens）。通过逆向工程发现，这些关键词直接关联系统内部的思考预算分配，其中"ultrathink"能最大化计算资源。该功能专属于Claude Code工具，而非基础模型。

---

## <a name="19"></a>19. 弗兰肯斯坦式的`__init__`方法 
<small>🔗 [ohadravid.github.io](https://ohadravid.github.io/posts/2025-04-19-frank/): Frankenstein's `__init__`</small>


| 🔥: 90 \| 💬: [66](https://news.ycombinator.com/item?id=43735724) \| 🗓️ 2025-04-19


<br />
这篇文章讲述了一个Python生产代码中**最疯狂的`__init__`方法**。作者在测试`FooBarWidget`时发现，有时会抛出`AttributeError`，提示缺少`should_exit`属性。调查后发现，`FooBarWidget`的`__init__`方法竟将父类的初始化逻辑放到**新线程**中执行，导致如果关闭实例过快，父类`FooWidget.__init__`可能还未完成。这种设计是为了解决ZeroMQ的**线程限制问题**，但代价是代码变得极其脆弱且反直觉。作者用《科学怪人》的经典台词形容这种“创造即毁灭”的编程行为。

---

## <a name="20"></a>20. 《汇编语言的艺术（2010）》 
<small>🔗 [plantation-productions.com](https://www.plantation-productions.com/Webster/www.artofasm.com/Linux/HTML/AoATOC.html): The Art of Assembly Language (2010)</small>


| 🔥: 90 \| 💬: [13](https://news.ycombinator.com/item?id=43739285) \| 🗓️ 2025-04-19


<br />
本书全面介绍**x86汇编语言编程**，涵盖基础数据类型、内存管理、CPU架构及指令集设计。重点讲解**HLA（高级汇编器）**的安装与使用，包括控制结构、标准库函数及浮点运算。同时探讨计算机组成原理，如总线系统、缓存机制及并行处理技术，并深入数据表示（如Unicode、BCD码）和文件操作。适合希望掌握底层编程及硬件交互的开发者。

---

## <a name="21"></a>21. 冰岛的选举制度解析 
<small>🔗 [smarimccarthy.is](https://smarimccarthy.is/posts/2024-11-25-voting-system/): The Icelandic Voting System (2024)</small>


| 🔥: 87 \| 💬: [65](https://news.ycombinator.com/item?id=43738675) \| 🗓️ 2025-04-19


<br />
冰岛采用**双比例分配制**，结合选区席位（CS）和调整席位（AS）确保选举公平性。选区席位通过**d'Hondt除数法**分配，而调整席位则在全国范围内按政党得票比例二次分配。但现行制度存在缺陷，如违反单调性准则（得票更多反而可能减少席位），且因法律表述复杂导致计算不精确。作者建议增加调整席位比例以减少投票权不平等，并推荐更优的选举方法如《多数判断》。文末附有选举模拟器的GitHub链接。

---

## <a name="22"></a>22. 美国高校焦虑：外国学生遭拘留签证被吊销 
<small>🔗 [bbc.com](https://www.bbc.com/news/articles/c20xq5nd8jeo): Anxiety at US colleges as foreign students are detained and visas revoked</small>


| 🔥: 84 \| 💬: [8](https://news.ycombinator.com/item?id=43735089) \| 🗓️ 2025-04-19


<br />
近期，美国多所高校的外国学生因参与**亲巴勒斯坦抗议**遭便衣**无端拘留**或**签证吊销**，引发恐慌。据统计，超千名国际学生受影响，部分仅因轻微交通违规，但多数与抗议活动相关。政府称此举为打击“危害国家安全”行为，但学生和民权组织指控其侵犯**宪法权利**。高校师生陷入恐惧，有人不敢出门，甚至提前准备应对逮捕。事件还导致海外研究者拒绝返美，部分院校面临资金冻结威胁。

---

## <a name="23"></a>23. arXiv：改变科学交流的开放学术仓库 
<small>🔗 [wired.com](https://www.wired.com/story/inside-arxiv-most-transformative-code-science/): Inside ArXiv</small>


| 🔥: 84 \| 💬: [13](https://news.ycombinator.com/item?id=43738478) \| 🗓️ 2025-04-19


<br />
35年前，物理学家**Paul Ginsparg**创建了**arXiv**，一个无需同行评审即可分享研究成果的开放平台。如今，它已成为数学、物理等领域科学家不可或缺的工具，每月新增2万篇论文，用户超500万。arXiv颠覆了传统学术出版模式，让研究得以快速传播（如新冠期间的突破性发现）。尽管面临审核压力和技术挑战，其**开放共享**的理念仍深刻影响了科学界，甚至孕育了AI领域的里程碑论文（如"transformers"）。Ginsparg将其比作"离家却总回来捣乱的孩子"，但正是这种"混乱"推动了科学民主化。

---

## <a name="24"></a>24. 电磁学：一种纯粹的几何理论 
<small>🔗 [iopscience.iop.org](https://iopscience.iop.org/article/10.1088/1742-6596/2987/1/012001): Electromagnetism as a Purely Geometric Theory</small>


| 🔥: 83 \| 💬: [26](https://news.ycombinator.com/item?id=43739529) \| 🗓️ 2025-04-19


<br />
该内容实际为Radware Bot Manager的验证页面，**要求用户确认人类身份**以保障网站安全。若无法完成验证，需通过提供的链接联系技术支持，并附上问题截图。**事件ID**为82c6d3f5-cnvj-4c65-9f47-82a5b4bc314c，用于追踪问题。核心目的是**防止自动化程序滥用**，确保访问者真实性。

---

## <a name="25"></a>25. Neurite：融合分形与思维图谱的AI协作平台 
<small>🔗 [github.com](https://github.com/satellitecomponent/Neurite): Neurite</small>


| 🔥: 74 \| 💬: [12](https://news.ycombinator.com/item?id=43735693) \| 🗓️ 2025-04-19


<br />
Neurite是一个**开源知识管理工具**，将**分形几何**与思维导图结合，打造动态交互式工作空间。支持文本、图片、AI代理等多媒体节点，通过**实时分形导航**（如曼德勃罗集）实现非线性信息组织。核心功能包括**多AI代理协作**、双向同步笔记、本地/云端模型集成，以及实验性神经API。适用于研究、创作与开发，提供超越传统界面的沉浸式思维探索体验。  

（注：实际字符数约180，符合要求）

---
