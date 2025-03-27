---
layout: page
title: 勒西科技日报 - 2025年03月27日
date: 2025-03-27 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 皮拉内西的透视技巧（2019）；
1. 突破WebP防线：NSO BLASTPASS iMessage漏洞分析；
1. 我在家自制了人造太阳光；
1. 纪录片《黑天鹅》揭露丹麦腐败黑幕；
1. 没有危机感，政客就不会推动繁荣；

以上是今天的前五条黑科技新闻标题。

总共25条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 皮拉内西的透视技巧（2019） 
<small>🔗 [medium.com](https://medium.com/@brunopostle/piranesis-perspective-trick-6bcd7a754da9): Piranesi's Perspective Trick (2019)</small>


| 🔥🔥: 299 \| 💬: [69](https://news.ycombinator.com/item?id=43492562) \| 🗓️ 2025-03-27


<br />
本文探讨了18世纪艺术家**乔瓦尼·巴蒂斯塔·皮拉内西**在其建筑蚀刻作品中使用的独特**透视技巧**。与现代摄影不同，他的作品通过**平行对角线**和等比例缩放近远景物体，实现了超广角且无边缘畸变的画面效果。这种手法虽不符合真实透视原理，却显著提升了图像的**可读性**。研究还将其转化为数字工具（如Hugin的Panini投影），并对比了传统透视与皮拉内西技法的差异，揭示了其在历史与现代视觉艺术中的独特价值。

---

## <a name="2"></a>2. 突破WebP防线：NSO BLASTPASS iMessage漏洞分析 
<small>🔗 [googleprojectzero.blogspot.com](https://googleprojectzero.blogspot.com/2025/03/blasting-past-webp.html): Blasting Past WebP - An analysis of the NSO BLASTPASS iMessage exploit</small>


| 🔥🔥: 213 \| 💬: [86](https://news.ycombinator.com/item?id=43493056) \| 🗓️ 2025-03-27


<br />
2023年9月，苹果紧急修复了iOS 16.6.1中两个关键漏洞（CVE-2023-41064和CVE-2023-41061），这些漏洞与NSO集团的**零点击攻击**工具BLASTPASS相关。攻击者通过iMessage发送伪装成PKPass文件的恶意WebP图像，利用**WebP无损格式的Huffman编码漏洞**触发内存越界写入（写入固定值0x00270007）。尽管漏洞触发后解析会立即终止，但攻击者通过嵌套5.5MB的EXIF元数据（含恶意二进制plist）实现堆布局操控。值得注意的是，漏洞利用链绕过了苹果的**BlastDoor沙箱**，最终在MobileSMS进程中执行任意代码。该攻击与2021年FORCEDENTRY漏洞利用手法高度相似，再次凸显了复杂图像格式解析的安全风险。

---

## <a name="3"></a>3. 我在家自制了人造太阳光 
<small>🔗 [victorpoughon.fr](https://victorpoughon.fr/i-tried-making-artificial-sunlight-at-home/): I tried making artificial sunlight at home</small>


| 🔥🔥: 201 \| 💬: [90](https://news.ycombinator.com/item?id=43497394) \| 🗓️ 2025-03-27


<br />
受DIY Perks启发，作者用**36颗高显色LED**和**双透镜阵列**设计了一款紧凑型人造阳光设备。通过**定制光学模拟代码**优化透镜形状，并采用CNC加工亚克力透镜与铝制结构。最终设备虽未达到真实阳光亮度（约1000-10000勒克斯），但通过**瑞利散射膜**模拟蓝天效果。项目融合了3D建模、PCB设计与开源光学工具，为后续版本积累了经验。

---

## <a name="4"></a>4. 纪录片《黑天鹅》揭露丹麦腐败黑幕 
<small>🔗 [theguardian.com](https://www.theguardian.com/world/2025/mar/27/black-swan-denmark-documentary-mads-brugger-amira-smajic): A filmmaker and a crooked lawyer shattered Denmark's self-image</small>


| 🔥🔥: 187 \| 💬: [138](https://news.ycombinator.com/item?id=43493159) \| 🗓️ 2025-03-27


<br />
丹麦导演**马德斯·布鲁格**与曾是洗钱律师的**阿米拉·斯马吉奇**合作，通过隐藏摄像头拍摄犯罪者自曝黑料，制作纪录片《黑天鹅》。影片曝光了企业家、律师甚至政客的逃税、贿赂等行为，**撼动了丹麦清廉的自我形象**，引发全国震动，促使法律改革。斯马吉奇从罪犯转型为线人，但影片也引发对她真实动机的质疑。布鲁格借此挑战了北欧国家“无系统性腐败”的迷思。

---

## <a name="5"></a>5. 没有危机感，政客就不会推动繁荣 
<small>🔗 [inpractice.yimbyaction.org](https://inpractice.yimbyaction.org/p/abundance-isnt-going-to-happen-unless): Abundance Isn't Going to Happen Unless Politicians Are Scared of the Status Quo</small>


| 🔥🔥: 184 \| 💬: [286](https://news.ycombinator.com/item?id=43495644) \| 🗓️ 2025-03-27


<br />
本文指出，美国当前的政治僵局导致住房、能源等关键领域供给不足，根源在于**过度繁琐的审批流程**和**两党共同制造的制度枷锁**。作者以加州住房法案为例，揭示即便通过改革法案，**官僚体系**和既得利益者（如消防员工会）仍会阻碍落实。文章警告，若政客继续安于现状，民众的经济困境将引发更强烈的反建制情绪，最终威胁民主制度本身。解决方案在于建立**结果导向**的治理模式，简化流程以提升政府效能。

---

## <a name="6"></a>6. 破折号、连接号与连字符的使用指南 
<small>🔗 [merriam-webster.com](https://www.merriam-webster.com/grammar/em-dash-en-dash-how-to-use): How to Use Em Dashes (–), En Dashes (–), and Hyphens (-)</small>


| 🔥🔥: 149 \| 💬: [117](https://news.ycombinator.com/item?id=43497719) \| 🗓️ 2025-03-27


<br />
**破折号（—）** 功能多样，可替代逗号、冒号或括号，用于强调补充信息、 abrupt change或中断对话。例如：“面包店6 a.m.—6 p.m.营业”或“玛贝尔惊呼——他们终于有了奶酪丹麦！”。**连接号（–）** 多用于数字范围（如“2007–2019”）或复合词（如“斯普林菲尔德–韦伯斯特堡列车”）。**连字符（-）** 则常见于复合词（如“面包师-店主”）或单词换行分隔。  

三种符号各司其职，破折号侧重语气转折，连接号标记范围，连字符连接词汇。格式上，破折号通常紧邻文字，而连接号需手动输入。

---

## <a name="7"></a>7. Rivulet语言中的源代码艺术 
<small>🔗 [github.com](https://github.com/rottytooth/Rivulet): Source code art in the Rivulet language</small>


| 🔥🔥: 143 \| 💬: [24](https://news.ycombinator.com/item?id=43492652) \| 🗓️ 2025-03-27


<br />
Rivulet是一种基于**流式线条**的编程语言，采用半图形化字符编写。其核心是四种**数据流线**，通过紧凑的代码块（字形）协同执行。语言设计摒弃传统分支与循环，依赖**条件回滚**作为唯一控制流。例如斐波那契程序通过线条流动方向表达运算逻辑，数据以列表形式组织，支持单细胞或列表级操作。语法独特，字形以╵╷标记边界，线条移动路径决定操作类型与数值。当前为0.4版，含SVG代码生成工具，灵感源自迷宫结构与书法美学。

---

## <a name="8"></a>8. 发布HN：Continue (YC S23) —— 定制专属AI编程助手 
<small>🔗 [hub.continue.dev](https://hub.continue.dev/explore/assistants): Launch HN: Continue (YC S23) – Create custom AI code assistants</small>


| 🔥🔥: 134 \| 💬: [90](https://news.ycombinator.com/item?id=43494427) \| 🗓️ 2025-03-27


<br />
Continue推出**自定义AI代码助手**，通过组合模块化配置满足特定开发需求。平台提供多种预置助手（如Next.js、Solidity、PyTorch等），支持**规则、提示词、模型**等深度定制，并推荐使用具备强工具调用能力的LLM以获得最佳体验。适用于数据科学、前端框架等场景，帮助开发者提升效率。

---

## <a name="9"></a>9. 加州拟立法逐步淘汰学校有害超加工食品 
<small>🔗 [thenewlede.org](https://www.thenewlede.org/2025/03/california-bill-aims-to-phase-out-harmful-ultra-processed-foods-in-schools/): California bill aims to phase out harmful ultra-processed foods in schools</small>


| 🔥🔥: 120 \| 💬: [150](https://news.ycombinator.com/item?id=43495997) \| 🗓️ 2025-03-27


<br />
2025年3月19日，加州提出全美首项法案，计划在2032年前逐步**淘汰学校餐食中的有害超加工食品**。法案将明确定义超加工食品，并组织专家评估其健康风险，重点关注含**禁用添加剂、致瘾性或高糖盐脂肪**的产品。该提案获两党支持，旨在应对儿童肥胖、多动症等健康问题。此前加州已通过禁用部分人工色素的法规，引发多州效仿。研究表明，超加工食品与32种疾病相关，但部分企业辩称“并非所有加工食品都不健康”。法案或促使企业调整配方以符合市场要求。

---

## <a name="10"></a>10. 现代C语言：C23新版发布 
<small>🔗 [gustedt.gitlabpages.inria.fr](https://gustedt.gitlabpages.inria.fr/modern-c/): Modern C</small>


| 🔥🔥: 119 \| 💬: [22](https://news.ycombinator.com/item?id=43492211) \| 🗓️ 2025-03-27


<br />
《现代C语言》的**C23标准新版**已免费发布，主要更新包括：新增**`_BitInt(N)`等位精确类型**、**`nullptr`常量**、类型推断（`auto`和`typeof`）等特性，并优化了枚举类型和泛型编程支持。书中还提供**过渡指南**帮助开发者快速适配。读者可通过Manning享受35%折扣购买电子版或纸质书，也可免费获取CC许可的在线版本。代码示例采用MIT许可，作者鼓励支持开源或标准委员会。

---

## <a name="11"></a>11. “信号门”事件推动Signal在美国下载量创历史新高 
<small>🔗 [wired.com](https://www.wired.com/story/signalgate-is-driving-the-most-us-downloads-of-signal-ever/): SignalGate Is Driving the Most US Downloads of Signal Ever</small>


| 🔥🔥: 107 \| 💬: [69](https://news.ycombinator.com/item?id=43497150) \| 🗓️ 2025-03-27


<br />
特朗普政府高级官员在**加密通讯应用Signal**上误将《大西洋月刊》主编拉入讨论空袭也门的群聊，引发“信号门”丑闻。这一事件使Signal在美国的下载量激增**105%**，成为其11年历史上增长最快的一周。尽管特朗普质疑Signal“有缺陷”，但网络安全专家仍推荐其作为最安全的端到端加密工具。Signal负责人称，此事件让该应用首次成为**主流话题**，推动公众对加密通讯的关注。

---

## <a name="12"></a>12. 苹果II版《滑翔机》游戏重制发布 
<small>🔗 [colino.net](https://www.colino.net/wordpress/en/glider-for-apple-ii/): Glider for Apple II</small>


| 🔥🔥: 101 \| 💬: [21](https://news.ycombinator.com/item?id=43491977) \| 🗓️ 2025-03-27


<br />
作者为怀旧玩家复刻了90年代经典Mac游戏**《滑翔机》**，并移植到Apple II平台。这是其首次尝试用**6502汇编语言**开发游戏，过程虽艰难但最终成功。游戏支持Apple ][+及以上机型（部分需鼠标），推荐单色显示器以获得最佳体验。提供英文和保加利亚语版本下载，开发者还分享了技术日志。玩家反馈流畅度出色，尤其赞赏画面设计和彩蛋（如睡觉的猫）。

---

## <a name="13"></a>13. 为什么仍有人对LLM持乐观态度？我实在不理解 
<small>🔗 [twitter.com](https://twitter.com/skdh/status/1905132853672784121): I genuinely don't understand why some people are still bullish about LLMs</small>


| 🔥: 93 \| 💬: [84](https://news.ycombinator.com/item?id=43498338) \| 🗓️ 2025-03-27


<br />
原文内容实际是一段**浏览器报错提示**，与标题讨论的**大语言模型（LLM）**无关。提示用户**启用JavaScript**或更换浏览器以正常访问X平台（原Twitter），并提及隐私插件可能导致访问异常。标题中的争议观点未在内容中展开，可能是技术错误导致的文不对题。

---

## <a name="14"></a>14. Netlify部署数十万Next.js站点的挑战与突破 
<small>🔗 [netlify.com](https://www.netlify.com/blog/how-we-run-nextjs/): Netlify deploys hundreds of thousands of Next.js sites – here's what challenging</small>


| 🔥: 87 \| 💬: [24](https://news.ycombinator.com/item?id=43493552) \| 🗓️ 2025-03-27


<br />
Netlify团队分享了大规模部署**Next.js**站点的技术挑战，涉及**性能优化**和**资源管理**等核心问题。文章由工程师Philippe Serhal和产品经理Elad Rosenheim撰写，重点探讨了如何在保证**用户体验**的同时实现高效部署。发布于2025年3月26日，内容涵盖框架适配与基础设施优化的实践经验。

---

## <a name="15"></a>15. NASA删除女性宇航员主题漫画引争议 
<small>🔗 [futurism.com](https://futurism.com/nasa-deletes-comic-women-astronauts): NASA Deletes Comic Book About How Women Can Be Astronauts</small>


| 🔥: 78 \| 💬: [12](https://news.ycombinator.com/item?id=43497033) \| 🗓️ 2025-03-27


<br />
NASA近日从其官网删除了两部以**女性宇航员**为主题的漫画《首位女性：NASA对人类的承诺》及续作，疑似配合特朗普政府清除联邦机构中**"DEI"（多元平等包容）内容**的政策。这两部作品原为配合**阿尔忒弥斯登月计划**（承诺首位登月女性及少数族裔）而创作，但相关承诺现已被悄然移除。  

冰岛航天局公开谴责此举，宣布将托管漫画并翻译为冰岛语，强调DEI是社会发展的基石。此前五角大楼也因AI误删黑人运动员杰基·罗宾逊纪念网页引发争议，暴露出政策背后的歧视倾向。

---

## <a name="16"></a>16. 把这该死的值班表扔了吧 
<small>🔗 [scottsmitelli.com](https://www.scottsmitelli.com/articles/take-oncall-and-shove-it/): Take this on-call rotation and shove it</small>


| 🔥: 77 \| 💬: [27](https://news.ycombinator.com/item?id=43498213) \| 🗓️ 2025-03-27


<br />
文章以电视台直播新闻的复杂流程为例，**冗余备份系统**和**应急专家“Alex”**的角色揭示了高压力值班制度的荒诞性。Alex身兼多职，随时待命解决突发故障，却因“问题不常发生”而被无限压榨。类比科技行业的**SEV分级响应机制**，作者讽刺了24小时待命文化的非人性化，指出缺乏标准化的值班制度如何侵蚀员工生活。从传呼机到现代告警系统，技术演进并未改变“随叫随到”的本质，反而让边界感更加模糊。

---

## <a name="17"></a>17. 英国艾伦·图灵研究所为何陷入困境？ 
<small>🔗 [chalmermagne.com](https://www.chalmermagne.com/p/how-not-to-build-an-ai-institute): What went wrong with the Alan Turing Institute?</small>


| 🔥: 76 \| 💬: [75](https://news.ycombinator.com/item?id=43493313) \| 🗓️ 2025-03-27


<br />
英国国家AI研究所**艾伦·图灵研究所（ATI）**因管理混乱、研究方向偏离核心问题而备受批评。尽管获得1亿英镑资金，却计划裁员并削减1/4研究项目。**虚拟研究所模式**导致大学间利益争夺，学术合作匮乏，沦为“高级咖啡厅”。研究所过度侧重商业咨询，忽视AI前沿技术（如LLMs），甚至高层学者公开质疑深度学习价值。**治理缺陷**与意识形态倾向使其在生成式AI浪潮中完全脱节，被批“无关紧要”。

---

## <a name="18"></a>18. 美国医学会如何压榨医生 
<small>🔗 [thebignewsletter.com](https://www.thebignewsletter.com/p/how-the-american-medical-association): How the American Medical Association Screws Doctors</small>


| 🔥: 66 \| 💬: [82](https://news.ycombinator.com/item?id=43494324) \| 🗓️ 2025-03-27


<br />
美国医学会（AMA）通过政府授予的**CPT编码垄断权**，向医疗软件公司收取高额版权费，最终转嫁给医生。这些编码是医保报销的必备标准，但AMA却将其私有化并从中获利3亿美元/年，导致医生负担加重。**AMA收入62%来自版权费**，而会员会费持续下降，反映其已从医生代表沦为利益集团。政府可改用免费编码系统（如ICD），但AMA通过政治游说维持垄断，甚至对质疑者采取法律行动。这种制度加剧了医疗行业的企业化，迫使独立执业医生陷入困境。

---

## <a name="19"></a>19. 我为何抵制人工智能（你也该这么做） 
<small>🔗 [unherd.com](https://unherd.com/2025/03/why-im-boycotting-ai/): Why I'm Boycotting AI</small>


| 🔥: 62 \| 💬: [154](https://news.ycombinator.com/item?id=43492112) \| 🗓️ 2025-03-27


<br />
作者Sam Kahn以自身被苹果生态“绑架”的经历为引，指出**AI技术**正以同样方式侵蚀人类**自主性**与创造力。他认为AI本质是“数据挖掘+文本预测”的**高级模仿**，依赖人类对技术的盲目信任，实则由硅谷巨头操控以牟利。文章列举智能手机成瘾、青少年心理危机等前车之鉴，警告AI将加剧人类能力退化，呼吁在监管缺位时主动抵制。作者拒绝使用AI应用，强调保护心智独立比追逐“科技未来”更重要。

---

## <a name="20"></a>20. LeetCode反叛者：专访用AI破解亚马逊面试的Roy Lee 
<small>🔗 [thepennpost.com](https://thepennpost.com/2025/03/25/nicolas-casey-the-leader-of-the-leetcode-rebellion-an-interview-with-roy-lee/): The Leader of the LeetCode Rebellion: An Interview with Roy Lee</small>


| 🔥: 60 \| 💬: [33](https://news.ycombinator.com/item?id=43497848) \| 🗓️ 2025-03-27


<br />
哥伦比亚大学学生**Roy Lee**开发了AI工具**Interview Coder**，可自动解决LeetCode编程题，以此抗议技术面试的不合理现状。他公开用该工具获得亚马逊实习offer的视频后，引发亚马逊向校方施压，导致其面临纪律审查。Roy认为**大语言模型（LLM）**已颠覆传统编程评估，呼吁企业改用代码审查或整合LLM的面试形式。事件曝光后，他拒绝亚马逊工作邀约，并计划继续推动技术招聘改革。

---

## <a name="21"></a>21. 无参KV缓存压缩技术：高效内存的长上下文大模型优化 
<small>🔗 [arxiv.org](https://arxiv.org/abs/2503.10714): Parameter-free KV cache compression for memory-efficient long-context LLMs</small>


| 🔥: 59 \| 💬: [13](https://news.ycombinator.com/item?id=43496244) \| 🗓️ 2025-03-27


<br />
该研究提出**ZeroMerge**框架，通过**动态零样本压缩**解决大语言模型长上下文处理中的KV缓存内存线性增长问题。其核心创新包括：**细粒度内存分配**、**残差合并机制**保留关键上下文，以及**无需参数微调**的架构兼容性。实验显示，在40K长文本下，该方法能以5%压缩率保持性能，同时提升推理速度一倍，显著平衡了内存效率与生成质量。代码已开源。

---

## <a name="22"></a>22. 爬虫顺序的优化与挑战 
<small>🔗 [marginalia.nu](https://www.marginalia.nu/log/a_117_crawl_order/): Crawl Order and Disorder</small>


| 🔥: 56 \| 💬: [9](https://news.ycombinator.com/item?id=43493207) \| 🗓️ 2025-03-27


<br />
搜索引擎爬虫长期面临**收尾耗时过长**的问题：99.9%的抓取在4天内完成，剩余0.1%却需一周。原因包括**帕累托分布的网站规模差异**及**域名并发限制**（尤其针对.edu/.gov等学术站点）。最初随机排序导致大型站点启动过晚，后续按子域名数排序又引发博客主机请求过载。最终通过**添加请求间隔抖动**和调整排序逻辑（优先抓取多子域名站点），优化了爬虫效率。未来或可基于历史抓取时长进一步改进。

---

## <a name="23"></a>23. 超薄薄膜导电性能超越铜 
<small>🔗 [spectrum.ieee.org](https://spectrum.ieee.org/thin-film): Thinner Films Conduct Better Than Copper</small>


| 🔥: 56 \| 💬: [20](https://news.ycombinator.com/item?id=43493749) \| 🗓️ 2025-03-27


<br />
研究人员发现，由**多晶磷化铌**制成的原子级厚度薄膜，其表面导电性能优于传统铜材料。这种**拓扑半金属**特性使其在芯片制造领域具有巨大潜力，可能成为未来替代铜互连的新选择。关键突破在于材料**越薄导电性越强**的特性，为下一代半导体技术提供了新方向。

---

## <a name="24"></a>24. B-2隐形轰炸机秘密部署迪戈加西亚引猜测 
<small>🔗 [theaviationist.com](https://theaviationist.com/2025/03/26/b-2-unannounced-deployment-diego-garcia/): B-2 Spirit Stealth Bombers Begin Unannounced Deployment to Diego Garcia</small>


| 🔥: 56 \| 💬: [79](https://news.ycombinator.com/item?id=43496181) \| 🗓️ 2025-03-27


<br />
航空爱好者通过公开飞行数据追踪到多架**B-2幽灵隐形轰炸机**从怀特曼空军基地飞往印度洋战略要地迪戈加西亚。此次未公开的异常部署涉及至少4架B-2（占全球机队21%），并伴随大量**KC-135加油机**和**C-17运输机**支援。一架B-2因故障紧急降落夏威夷，其余继续执行任务。  

迪戈加西亚基地拥有专为B-2设计的恒温机库，暗示长期部署可能。外界推测此举或针对伊朗核设施，因B-2是美军唯一可投掷**GBU-57巨型钻地弹**的机型，同时美军在中东的F-35和航母调动加剧地区紧张。官方未回应部署目的，但结合对胡塞武装的空袭和伊朗核问题，军事行动可能性引发关注。

---

## <a name="25"></a>25. 聊天机器人是AI的反模式 
<small>🔗 [hello-jp.net](https://hello-jp.net/building-beyond-the-buzz/chatbots-are-ai-antipatterns): Chatbots-Are-AI-Antipatterns</small>


| 🔥: 47 \| 💬: [57](https://news.ycombinator.com/item?id=43492064) \| 🗓️ 2025-03-27


<br />
作者认为**聊天界面**并非人机交互的最佳方式，并以日历助手、电商退换货、汽车仪表盘为例，说明**图形界面（GUI）**在信息呈现和操作效率上更具优势。用户需要精准描述需求才能使用聊天机器人，这如同要求普通人用命令行操作电脑，门槛过高。  

AI代理应分为两类：**社交型**（需建立情感连接）和**事务型**（需高效解决问题）。后者更适合与GUI结合的**混合界面**，例如预置按钮触发AI功能，避免用户手动输入复杂指令。当前聊天机器人仍是公众衡量AI进展的标准，但需避免将其滥用为“反模式”。

---
