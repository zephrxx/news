---
layout: page
title: 勒西科技日报 - 2025年04月29日
date: 2025-04-29 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 亚马逊将向消费者展示关税成本；
1. 递归思维链：让AI自我辩论以提升思考能力；
1. 经济学家：生成式AI尚未影响就业与工资水平；
1. 印度法院下令封禁Proton Mail加密邮箱服务；
1. 亚马逊RDS for PostgreSQL 17.4的隔离级别异常分析；

以上是今天的前五条黑科技新闻标题。

总共19条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 亚马逊将向消费者展示关税成本 
<small>🔗 [punchbowl.news](https://punchbowl.news/article/tech/amazon-display-tariff-costs/): Amazon to display tariff costs for consumers</small>


| 🔥🔥: 434 \| 💬: [399](https://news.ycombinator.com/item?id=43831027) \| 🗓️ 2025-04-29


<br />
亚马逊计划在产品页面明确标注**特朗普政府关税**导致的额外费用，以避免为贸易战成本担责。消息人士称，平台将在商品总价旁单独显示**关税占比**，让消费者直观了解政策影响。此举正值科技行业因关税、芯片法案及出口管制等问题与政府关系紧张之际。

---

## <a name="2"></a>2. 递归思维链：让AI自我辩论以提升思考能力 
<small>🔗 [github.com](https://github.com/PhialsBasement/Chain-of-Recursive-Thoughts): Chain of Recursive Thoughts: Make AI think harder by making it argue with itself</small>


| 🔥🔥: 324 \| 💬: [160](https://news.ycombinator.com/item?id=43835445) \| 🗓️ 2025-04-29


<br />
该项目通过让AI模型**递归生成并评估多个回答**，显著提升了输出质量。核心机制包括：**自我质疑**、**多轮优化**和**动态思考深度**。测试显示，Mistral 3.1 24B模型应用该方法后，编程任务表现从“一般”跃升至“惊艳”。用户可安装工具包直接体验，**关键优势**在于竞争性答案生成与迭代筛选。项目开源（MIT协议），欢迎贡献改进。

---

## <a name="3"></a>3. 经济学家：生成式AI尚未影响就业与工资水平 
<small>🔗 [theregister.com](https://www.theregister.com/2025/04/29/generative_ai_no_effect_jobs_wages/): Generative AI is not replacing jobs or hurting wages at all, say economists</small>


| 🔥🔥: 310 \| 💬: [453](https://news.ycombinator.com/item?id=43830613) \| 🗓️ 2025-04-29


<br />
一项针对丹麦11个职业的研究显示，**生成式AI**（如ChatGPT等）目前对工资和工作时长的影响微乎其微。尽管AI工具被广泛采用，但**实际经济效益**有限，仅节省约2.8%的工作时间，且部分被新增任务抵消。研究指出，企业投入与工人收益之间存在差距，仅3%-7%的生产力提升转化为工资增长。专家认为，AI的**变革性潜力**尚未在短期内显现。

---

## <a name="4"></a>4. 印度法院下令封禁Proton Mail加密邮箱服务 
<small>🔗 [techcrunch.com](https://techcrunch.com/2025/04/29/indian-court-orders-blocking-of-proton-mail/): Indian court orders blocking of Proton Mail</small>


| 🔥🔥: 275 \| 💬: [114](https://news.ycombinator.com/item?id=43834942) \| 🗓️ 2025-04-29


<br />
印度卡纳塔克邦高等法院下令政府封禁加密邮箱服务**Proton Mail**，原因是新德里公司M Moser Design Associates投诉其员工收到通过该平台发送的**淫秽内容邮件**，而Proton Mail拒绝提供发件人信息。法院依据《2008年信息技术法》要求政府执行封锁，但截至报道时尚未生效。这是Proton Mail在印度面临的第二次封禁令，此前泰米尔纳德邦警方也因**虚假炸弹威胁邮件**要求封禁，但瑞士当局介入阻止。Proton Mail强调封禁只会影响守法用户，无法阻止境外犯罪分子改用其他服务。

---

## <a name="5"></a>5. 亚马逊RDS for PostgreSQL 17.4的隔离级别异常分析 
<small>🔗 [jepsen.io](https://jepsen.io/analyses/amazon-rds-for-postgresql-17.4): Jepsen: Amazon RDS for PostgreSQL 17.4</small>


| 🔥🔥: 204 \| 💬: [62](https://news.ycombinator.com/item?id=43833195) \| 🗓️ 2025-04-29


<br />
测试发现，**亚马逊RDS for PostgreSQL多可用区集群**未完全实现**快照隔离**，而是可能提供稍弱的**并行快照隔离**。在健康状态下，测试中观察到非相邻的G循环（如长分叉），表明读事务可能无法看到其他事务的完整提交顺序。此行为与单节点PostgreSQL的快照隔离表现不同。建议用户对关键事务使用写入端点或包含写入操作以确保一致性。测试覆盖了13.15至17.4版本，但未证明系统完全正确。

---

## <a name="6"></a>6. 性能优化为何如此艰难？本质是暴力穷举的苦差 
<small>🔗 [purplesyringa.moe](https://purplesyringa.moe/blog/why-performance-optimization-is-hard-work/): Performance optimization is hard because it's fundamentally a brute-force task</small>


| 🔥🔥: 202 \| 💬: [93](https://news.ycombinator.com/item?id=43831705) \| 🗓️ 2025-04-29


<br />
性能优化的核心难点在于其**暴力穷举**的本质：需测试大量代码变体（如25种算法组合）才能确定最优方案，且优化策略可能相互冲突（如组合后反而性能下降）。**硬件反直觉行为**（如分支预测失败、向量化意外提速）和**工具链缺陷**（编译器无法理解高阶抽象、缺乏Apple Silicon详细文档）加剧了复杂性。尽管可通过团队协作分摊工作量，但最终仍需依赖**反复试错**与性能分析，而微小的改动（如概率分支阈值）可能导致显著性能波动。作者认为，即使10%的优化也是艺术，其累积效应能显著提升用户体验。

---

## <a name="7"></a>7. 一键拒绝非必要Cookie的Chrome扩展 
<small>🔗 [blog.bymitch.com](https://blog.bymitch.com/posts/reject-cookies/): Show HN: A Chrome extension that will auto-reject non-essential cookies</small>


| 🔥🔥: 196 \| 💬: [121](https://news.ycombinator.com/item?id=43831298) \| 🗓️ 2025-04-29


<br />
这款Chrome扩展旨在**自动拒绝非必要Cookie**，解决用户频繁手动关闭Cookie弹窗的痛点。与现有自动接受Cookie的扩展不同，它优先尝试**拒绝Cookie**，失败则直接关闭弹窗，符合**GDPR**和《电子隐私指令》要求。扩展通过识别主流Cookie管理平台（如OneTrust）的特定元素实现功能，代码已开源。目前支持有限，鼓励用户反馈未覆盖的网站或问题，帮助完善功能。

---

## <a name="8"></a>8. Beatsync：跨设备精准同步音频的开源工具 
<small>🔗 [github.com](https://github.com/freeman-jiang/beatsync): Show HN: Beatsync – perfect audio sync across multiple devices</small>


| 🔥🔥: 173 \| 💬: [48](https://news.ycombinator.com/item?id=43835584) \| 🗓️ 2025-04-29


<br />
Beatsync是一款基于网页的**高精度音频播放器**，专为多设备同步播放和**空间音频**设计。它采用类似NTP的时间同步技术，实现毫秒级精准同步，支持跨平台使用（推荐Chrome浏览器）。用户可通过虚拟声源控制各设备音量，创造沉浸式听觉效果。项目提供自托管选项，当前处于早期开发阶段，桌面端Chrome支持最佳，移动端尚不稳定。采用Turborepo架构，包含Next.js前端和Bun后端，需配置.env文件后通过`bun dev`启动服务。

---

## <a name="9"></a>9. 编程语言应内置树形遍历原语 
<small>🔗 [blog.tylerglaiel.com](https://blog.tylerglaiel.com/p/programming-languages-should-have): Programming languages should have a tree traversal primitive</small>


| 🔥🔥: 170 \| 💬: [133](https://news.ycombinator.com/item?id=43831628) \| 🗓️ 2025-04-29


<br />
作者Tyler Glaiel提出，现代编程语言缺乏类似`for/foreach`的**树形遍历控制结构**，导致开发者频繁手动实现递归函数。他设计了一个`for_tree`语法原型：通过**分支表达式**自动展开递归（如`N : {N->left, N->right}`），支持`break`、`continue`和独有的`prune`（跳过子节点）。该设计不仅简化代码，还能处理内存中不存在的逻辑树（如生成字符串组合）。虽然深度优先遍历更易实现，但广度优先需额外内存。文末附有C++模板实现的实验性代码。

---

## <a name="10"></a>10. Waymo与丰田合作 推动个人自动驾驶汽车发展 
<small>🔗 [waymo.com](https://waymo.com/blog/2025/04/waymo-and-toyota-outline-strategic-partnership): Waymo partners with Toyota to bring autonomous driving to personal vehicles</small>


| 🔥🔥: 159 \| 💬: [103](https://news.ycombinator.com/item?id=43839123) \| 🗓️ 2025-04-29


<br />
丰田汽车与Waymo达成初步协议，将共同探索**自动驾驶技术**的开发与部署。合作将整合Waymo的自动驾驶系统和丰田的车辆制造优势，重点提升**个人车辆（POV）**的智能化水平。双方致力于通过技术创新提升道路安全，并推动丰田“零交通事故”愿景的实现。Waymo作为全球自动驾驶领导者，已在美国多地运营数十万次自动驾驶服务，事故率较人类驾驶降低81%。此次合作或将为丰田车主带来Waymo的**自动驾驶技术**，进一步普及安全出行方案。

---

## <a name="11"></a>11. 开发者漠不关心，我连房租都交不起了 
<small>🔗 [happyfellow.bearblog.dev](https://happyfellow.bearblog.dev/i-cant-pay-rent-because-devs-just-dont-care/): I can't pay rent because devs just don't care</small>


| 🔥🔥: 139 \| 💬: [115](https://news.ycombinator.com/item?id=43836619) \| 🗓️ 2025-04-29


<br />
作者因**银行应用更新失败**导致无法登录支付房租，愤怒抨击开发者忽视用户体验。旧手机无法运行臃肿应用，**追踪脚本和冗余代码**加剧资源消耗，而开发者却以“性能达标”为借口。文中痛斥技术团队滥用资源，导致普通用户为**电池损耗和硬件淘汰**买单，尤其批评政府服务网站对老旧设备兼容性差，认为这种“优化惰性”让弱势群体陷入困境。

---

## <a name="12"></a>12. 如何培养内在动机：科学研究的启示 
<small>🔗 [erringtowardsanswers.substack.com](https://erringtowardsanswers.substack.com/p/intrinsic-motivation): How to build Intrinsic Motivation: a review of the science</small>


| 🔥🔥: 131 \| 💬: [30](https://news.ycombinator.com/item?id=43830544) \| 🗓️ 2025-04-29


<br />
本文探讨了**内在动机**的本质及其重要性。作者通过个人经历引出主题：当行为源于兴趣而非外部奖励时（如学习、运动），人们会表现出更强的持久力和愉悦感。研究指出，**自我决定理论（SDT）**认为内在动机是人类探索和发展的核心驱动力，而外部压力可能抑制这种天性。关键因素包括**自主性**和兴趣培养，过度依赖奖惩会削弱内在动力。文章还回顾了相关实验，证明动物和人类天生具有探索欲望，这与行为主义的强化理论形成对比。

---

## <a name="13"></a>13. ArkFlow：基于 Rust 的高性能流处理引擎 
<small>🔗 [github.com](https://github.com/arkflow-rs/arkflow): ArkFlow: High-performance Rust stream processing engine</small>


| 🔥🔥: 127 \| 💬: [27](https://news.ycombinator.com/item?id=43833310) \| 🗓️ 2025-04-29


<br />
ArkFlow 是一个用 **Rust** 开发的高性能流处理引擎，支持多数据源输入/输出和强大的处理能力。其核心特性包括：**低延迟异步运行时**（基于 Tokio）、**多数据源支持**（如 Kafka、MySQL、文件等），以及内置 **SQL 查询** 和 JSON 处理等功能。采用模块化设计，易于扩展，适用于实时数据分析场景。项目开源，遵循 Apache-2.0 协议，社区活跃。

---

## <a name="14"></a>14. Bamba：开源混合模型，突破Transformer的二次方瓶颈 
<small>🔗 [research.ibm.com](https://research.ibm.com/blog/bamba-ssm-transformer-model): Bamba: An open-source LLM that crosses a transformer with an SSM</small>


| 🔥🔥: 123 \| 💬: [36](https://news.ycombinator.com/item?id=43835495) \| 🗓️ 2025-04-29


<br />
IBM开源了**Bamba**，一种结合**Transformer**与**状态空间模型（SSM）**的混合架构，显著降低了KV缓存内存需求，推理速度可达同类Transformer的两倍。Bamba-9B在关键基准测试中媲美Meta的Llama-3.1 8B，且支持32,000词长上下文。团队与Red Hat合作优化vLLM支持SSM，未来或实现百万级词长处理。这一创新有望解决Transformer的二次方计算瓶颈，提升效率与性能。

---

## <a name="15"></a>15. 苏联金星探测器残骸53年后将失控坠回地球 
<small>🔗 [gizmodo.com](https://gizmodo.com/after-53-years-a-failed-soviet-venus-spacecraft-is-crashing-back-to-earth-2000595234): After 53 years, a failed Soviet Venus spacecraft is crashing back to Earth</small>


| 🔥🔥: 121 \| 💬: [44](https://news.ycombinator.com/item?id=43831602) \| 🗓️ 2025-04-29


<br />
1972年苏联发射的**金星探测器"宇宙482号"**因推进故障未能脱离地球轨道，其重达495公斤的着陆舱预计在2025年5月10日左右失控再入大气层。由于该设备原设计可承受金星高温大气，专家警告**部分残骸可能完整撞击地表**，但风险等级接近陨石概率。目前坠落时间和地点仍受太阳活动影响难以精确预测，但大概率会坠入无人海域。这是冷战时期航天遗产的意外回归。

---

## <a name="16"></a>16. Pyrefly：用Rust编写的更快Python类型检查器 
<small>🔗 [pyrefly.org](https://pyrefly.org/): Pyrefly - A faster Python type checker written in Rust</small>


| 🔥🔥: 117 \| 💬: [66](https://news.ycombinator.com/item?id=43831524) \| 🗓️ 2025-04-29


<br />
Pyrefly是一款基于**Rust**开发的Python类型检查工具，旨在显著提升类型检查速度。通过利用Rust的高性能特性，它能够比传统Python工具（如mypy）更高效地处理代码分析。该项目专注于**静态类型验证**，适合大型代码库，同时保持与现有Python类型注解的兼容性。开发者可借此优化工作流，减少等待时间。

---

## <a name="17"></a>17. 什么是"诱发大气振动"？ 
<small>🔗 [physics.stackexchange.com](https://physics.stackexchange.com/questions/848666/what-is-induced-atmospheric-vibration): What Is "Induced Atmospheric Vibration"?</small>


| 🔥: 99 \| 💬: [54](https://news.ycombinator.com/item?id=43831708) \| 🗓️ 2025-04-29


<br />
近期伊比利亚半岛的大规模停电被归因于一种罕见现象——**诱发大气振动**。该现象由西班牙极端温差引发，导致400千伏高压线路出现异常振荡，进而造成电网同步故障，最终引发欧洲互联电网的连锁反应。  

**关键机制**在于高温导致空气电离（**电晕放电**），改变了线路的电容和电感特性，使电网调节系统失效。现代电网因快速响应能力反而放大了这类问题。未来随着气候变化，此类事件可能更频繁。  

（注：原文中技术细节较多，此处提炼核心逻辑，控制在简洁易懂的范围内。）

---

## <a name="18"></a>18. Meta推出基于Llama 4的AI语音助手应用 
<small>🔗 [about.fb.com](https://about.fb.com/news/2025/04/introducing-meta-ai-app-new-way-access-ai-assistant/): Meta AI App built with Llama 4</small>


| 🔥: 89 \| 💬: [100](https://news.ycombinator.com/item?id=43833783) \| 🗓️ 2025-04-29


<br />
Meta发布全新**Meta AI应用**，内置**Llama 4**模型，主打语音交互与个性化体验。用户可通过独立应用与AI进行自然对话，并整合图像生成、编辑等功能。目前支持美国、加拿大等地区，提供**全双工语音技术**演示（需手动开启）。AI能根据用户偏好（如旅行、语言学习）提供个性化回答，并同步Facebook/Instagram数据优化响应。应用还包含Discover社区供分享AI创意，并支持与Ray-Ban智能眼镜及网页端无缝切换。用户可随时控制语音开关及隐私设置。

---

## <a name="19"></a>19. 日本推出全球首款太阳能超级面板 
<small>🔗 [japanenergyevent.com](https://www.japanenergyevent.com/media-insights-hub/industry-news/japan-unveils-world-s-first-solar-super-panel-more-powerful-than-20-nuclear-reactors/): Japan unveils first solar super-panel</small>


| 🔥: 78 \| 💬: [41](https://news.ycombinator.com/item?id=43831667) \| 🗓️ 2025-04-29


<br />
日本发布全球首个**钙钛矿太阳能电池（PSC）**技术，其发电量相当于20座核电站，计划到2040年实现20吉瓦产能。这种**轻量化、柔性可弯曲**的电池可安装在建筑外墙、车窗等城市空间，解决土地短缺问题。日本凭借全球第二大碘产国的优势，构建本土供应链，推动2050年净零排放目标。目前PSC仍面临耐久性与成本挑战，但预计到2040年成本将降至10日元/瓦。日本太阳能发电占比已从2014年的1.9%升至10%，未来目标为2030年可再生能源占比36%-38%。

---
