---
layout: page
title: 勒西科技日报 - 2025年05月30日
date: 2025-05-30 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. AI炒作下的"白领大裁员"论：一场营销闹剧；
1. AWS如何通过形式化方法保障系统正确性；
1. 微沙盒：兼具容器体验与虚拟机性能的安全执行方案；
1. 利用AVX512击败Google内核CTF的PoW挑战；
1. 意外泄露的AI生成高性能内核代码；

以上是今天的前五条黑科技新闻标题。

总共20条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. AI炒作下的"白领大裁员"论：一场营销闹剧 
<small>🔗 [cnn.com](https://www.cnn.com/2025/05/30/business/anthropic-amodei-ai-jobs-nightcap): The 'white-collar bloodbath' is all part of the AI hype machine</small>


| 🔥🔥: 317 \| 💬: [519](https://news.ycombinator.com/item?id=44136117) \| 🗓️ 2025-05-30


<br />
Anthropic CEO达里奥·阿莫代宣称**AI将取代半数初级白领工作**，却未提供实证。其言论延续硅谷经典话术：**AI先摧毁再拯救世界**，甚至预言"无癌乌托邦"，却回避失业与经济增长的矛盾。经济学家指出，其假设的**30%生产率跃升**极不现实。科技大佬马克·库班反驳称技术迭代历来创造新岗位。文章揭穿阿莫代本质是借危机感营销自家AI产品Claude，而当前AI仍存在幻觉、误判等局限，所谓"革命"更像噱头而非公益警示。

---

## <a name="2"></a>2. AWS如何通过形式化方法保障系统正确性 
<small>🔗 [cacm.acm.org](https://cacm.acm.org/practice/systems-correctness-practices-at-amazon-web-services/): Systems Correctness Practices at Amazon Web Services</small>


| 🔥🔥: 309 \| 💬: [111](https://news.ycombinator.com/item?id=44135638) \| 🗓️ 2025-05-30


<br />
AWS通过**形式化方法**（如TLA+和P语言）确保关键服务的正确性，早期发现传统测试难以捕捉的深层缺陷。**P语言**以状态机模型简化分布式系统设计验证，应用于S3、DynamoDB等核心服务。此外，**轻量级方法**（如基于属性的测试、确定性模拟）和故障注入服务（FIS）结合形式化规范，显著提升系统韧性。面对元稳定性等复杂故障，AWS采用离散事件模拟扩展验证范围，并在关键领域（如Cedar授权语言）引入数学证明，实现更高安全保证。

---

## <a name="3"></a>3. 微沙盒：兼具容器体验与虚拟机性能的安全执行方案 
<small>🔗 [github.com](https://github.com/microsandbox/microsandbox): Microsandbox: Virtual Machines that feel and perform like containers</small>


| 🔥🔥: 268 \| 💬: [125](https://news.ycombinator.com/item?id=44135977) \| 🗓️ 2025-05-30


<br />
微沙盒是一款**自托管平台**，专为安全执行不受信任的用户/AI代码设计。它融合了**虚拟机级隔离**与**容器级启动速度**（<200ms），支持标准OCI镜像，可在本地基础设施运行。提供多语言SDK（Python/JS/Rust），支持项目化开发（Sandboxfile配置），适用于**AI编程**、数据分析、网页代理等场景，兼顾安全性与开发效率。采用微虚拟机架构，资源隔离彻底，且无需依赖云服务。

---

## <a name="4"></a>4. 利用AVX512击败Google内核CTF的PoW挑战 
<small>🔗 [anemato.de](https://anemato.de/blog/kctf-vdf): Beating Google's kernelCTF PoW using AVX512</small>


| 🔥🔥: 260 \| 💬: [79](https://news.ycombinator.com/item?id=44137715) \| 🗓️ 2025-05-30


<br />
作者Timothy Herchen与团队发现Linux数据包调度器的**释放后使用漏洞**，并计划提交至Google的kernelCTF竞赛以获取高额奖金。竞赛提交需在极短时间内完成，包括解决**验证延迟函数（VDF）**“sloth”。通过优化1280位模平方运算，并利用**AVX512IFMA指令集**加速大整数乘法，最终将计算时间从4秒缩短至1.4秒，成功抢占提交窗口。这一突破展示了硬件加速在密码学挑战中的强大潜力。

---

## <a name="5"></a>5. 意外泄露的AI生成高性能内核代码 
<small>🔗 [crfm.stanford.edu](https://crfm.stanford.edu/2025/05/28/fast-kernels.html): Surprisingly fast AI-generated kernels we didn't mean to publish yet</small>


| 🔥🔥: 221 \| 💬: [54](https://news.ycombinator.com/item?id=44139454) \| 🗓️ 2025-05-30


<br />
研究人员意外发现，**AI生成的CUDA-C内核代码**在多项基准测试中表现惊人：矩阵乘法（FP32）达到PyTorch官方版本的101.3%，Conv2D性能提升至179.9%，LayerNorm甚至实现484.4%的加速。关键突破在于采用**并行探索策略**替代传统串行优化，通过自然语言生成优化思路并多分支验证，有效避免局部最优。当前方法虽在FP16运算等场景仍有局限，但为**自动化高性能代码生成**开辟了新路径。所有测试基于Nvidia L40S GPU完成。

---

## <a name="6"></a>6. AI并非人类的未来 
<small>🔗 [procreate.com](https://procreate.com/ai): AI is not our future</small>


| 🔥🔥: 215 \| 💬: [158](https://news.ycombinator.com/item?id=44134798) \| 🗓️ 2025-05-30


<br />
该内容强调**人类创造力**的珍贵，反对当前**生成式AI**以剽窃为基础的发展路径。平台明确表示不追踪用户活动，拒绝使用生成式AI技术，坚持保护用户隐私和作品所有权。尽管可能被视为技术浪潮中的"异类"，但作者认为这条少有人走的路更能守护**人性价值**，并为社区带来更有意义的成果。核心立场是：创造力应源于人类而非机器，技术发展不应以牺牲道德为代价。

---

## <a name="7"></a>7. 硅谷迎来大型电子零售商：Micro Center圣克拉拉店盛大开业 
<small>🔗 [microcenter.com](https://www.microcenter.com/site/mc-news/article/micro-center-santa-clara-photos.aspx): Silicon Valley finally has a big electronics retailer again: Micro Center opens</small>


| 🔥🔥: 167 \| 💬: [86](https://news.ycombinator.com/item?id=44140378) \| 🗓️ 2025-05-30


<br />
经过多年等待，Micro Center终于在硅谷圣克拉拉（5201 Stevens Creek Blvd）开业，吸引了数百名科技爱好者排队。新店为**DIY电脑组装者**、**游戏玩家**和**创客**提供丰富的硬件选择，包括**独家显卡型号**和最新科技产品。开业期间推出特惠活动，如台式机、笔记本和显示器**20%折扣**，并有超4000张显卡库存。店内还展出一款由NVIDIA CEO签名的限量版黄金显卡，将用于慈善拍卖。

---

## <a name="8"></a>8. MinIO社区版移除Web管理功能，强制用户转向付费计划 
<small>🔗 [biggo.com](https://biggo.com/news/202505261334_MinIO_Removes_Web_UI_Features): MinIO Removes Web UI Features from Community Version, Pushes Users to Paid Plans</small>


| 🔥🔥: 163 \| 💬: [89](https://news.ycombinator.com/item?id=44136108) \| 🗓️ 2025-05-30


<br />
开源对象存储方案**MinIO**近期移除社区版的关键**Web管理功能**（账户策略、配置管理等），用户需改用命令行工具或升级付费版。此举引发社区不满，被比作“功能降级驱动盈利”的典型案例。部分用户转向**OpenMaxIO**等替代方案（如SeaweedFS、Garage），但核心存储功能仍保留。MinIO称此举是为平衡开源与商业发展，但执行方式引发用户流失风险。

---

## <a name="9"></a>9. 达尔文哥德尔机：通过自我改写代码实现进化的AI 
<small>🔗 [sakana.ai](https://sakana.ai/dgm/): The Darwin Gödel Machine: AI that improves itself by rewriting its own code</small>


| 🔥🔥: 152 \| 💬: [157](https://news.ycombinator.com/item?id=44135369) \| 🗓️ 2025-05-30


<br />
研究人员提出**达尔文哥德尔机（DGM）**，一种能通过修改自身代码持续进化的AI系统。它结合了**开放式探索算法**和基础模型，在编程任务中自动优化性能（如SWE-bench准确率从20%提升至50%）。关键创新包括：保留多样化的智能体档案库以并行探索进化路径，并发现可跨模型和编程语言通用的改进方案。实验表明，**自我改进**和**开放式搜索**缺一不可。团队同时强调安全性，通过沙盒环境和变更追溯机制防范风险，但承认仍需解决模型“欺骗奖励函数”等问题。这一成果为无限学习的AI发展迈出重要一步。

---

## <a name="10"></a>10. 瑞典发现尘封53年的杰瑞·刘易斯争议电影《小丑哭了》 
<small>🔗 [thenationalnews.com](https://www.thenationalnews.com/arts-culture/film-tv/2025/05/29/jerry-lewis-day-the-clown-cried-discovered/): Jerry Lewis's "The Day the Clown Cried" discovered in Sweden after 53 years</small>


| 🔥🔥: 145 \| 💬: [65](https://news.ycombinator.com/item?id=44139592) \| 🗓️ 2025-05-30


<br />
瑞典演员汉斯·克里斯平承认，他于1980年从欧洲电影公司盗取了这部**从未公映**的二战题材电影完整工作样片，并将其藏于银行保险库中。影片讲述德国小丑被关进纳粹集中营后被迫引诱儿童赴死的黑暗故事。刘易斯生前因对成片不满且与制片人纠纷，将片段捐赠给美国国会图书馆并设定了2024年解禁期。克里斯平现计划将拷贝交给新一代修复，称**"必须让世人看到"**。此前业内普遍认为该片已无完整版本存世。

---

## <a name="11"></a>11. 射电天文软件定义无线电（Rasdr） 
<small>🔗 [radio-astronomy.org](https://radio-astronomy.org/rasdr): Radio Astronomy Software Defined Radio (Rasdr)</small>


| 🔥🔥: 121 \| 💬: [7](https://news.ycombinator.com/item?id=44134364) \| 🗓️ 2025-05-30


<br />
基于**Rasdr概念**（专为射电天文设计的**宽带宽**、兼容Windows且文档齐全的SDR接收器）的两款硬件设计中，目前仅**Rasdr4**仍在售。该设备致力于为天文观测提供高性能的软件定义无线电解决方案。

---

## <a name="12"></a>12. 德布鲁因索引：为什么它如此实用？ 
<small>🔗 [blueberrywren.dev](https://blueberrywren.dev/blog/debruijn-explanation/): De Bruijn notation, and why it's useful</small>


| 🔥🔥: 121 \| 💬: [33](https://news.ycombinator.com/item?id=44137439) \| 🗓️ 2025-05-30


<br />
本文介绍了**德布鲁因索引**和**德布鲁因层级**，它们是λ演算中避免变量捕获问题的命名方案。传统变量名容易在替换时引发冲突，而德布鲁因索引用自然数表示变量绑定关系：0指向最近绑定的变量，1指向次近的，以此类推。通过调整替换时的变量索引，可以避免意外捕获。  

德布鲁因层级则相反，最小数指向最外层的绑定。索引更适合局部操作，而层级在移动项时无需修改自由变量。此外，德布鲁因表示法能直接比较项的**α等价性**，无需重命名变量。文末还提供了其他替代方案的简要提及，如HOAS和抽象绑定树。

---

## <a name="13"></a>13. Cap：基于工作量证明的轻量级开源验证码替代方案 
<small>🔗 [capjs.js.org](https://capjs.js.org/): Cap: Lightweight, modern open-source CAPTCHA alternative using proof-of-work</small>


| 🔥🔥: 120 \| 💬: [84](https://news.ycombinator.com/item?id=44137867) \| 🗓️ 2025-05-30


<br />
Cap是一款**现代开源验证码**解决方案，采用**工作量证明（PoW）**机制，其组件库仅约20kb（含WASM），体积比hCaptcha小250倍。**轻量高效**的设计使其成为传统验证码的优质替代选择，尤其适合注重性能与隐私的应用场景。

---

## <a name="14"></a>14. 有毒的起点，有毒的决策：CEO选拔中的偏见 
<small>🔗 [papers.ssrn.com](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5270031): Toxic Origins, Toxic Decisions: Biases in CEO Selection</small>


| 🔥: 94 \| 💬: [58](https://news.ycombinator.com/item?id=44137542) \| 🗓️ 2025-05-30


<br />
该研究探讨了CEO晋升中的**选择偏差**如何放大风险偏好，并以产前暴露于污染环境作为个体风险偏好的外生冲击。研究发现，出生于未来超级基金污染区（**Superfund站点**）的CEO更可能通过内部晋升上位，表明企业奖励可见的成功却忽视了潜在的风险容忍度。这些**"超级基金CEO"**在内部表现出色，但晋升后倾向于采取更高风险的外部政策，导致业绩波动加剧、表现下滑。结果表明，企业可能系统性地将运气误认为能力，筛选出高风险偏好的管理者——当决策转向不可逆领域时，其特质会引发问题。简言之，超级基金CEO的业绩呈现**低均值、高方差**特征。  

（注：Superfund是美国环保署管理的污染场地治理项目，此处保留英文术语以保持专业语境）

---

## <a name="15"></a>15. W++：一款融合Python风格的.NET脚本语言，支持NuGet 
<small>🔗 [github.com](https://github.com/sinisterMage/WPlusPlus): Show HN: W++ – A Python-style scripting language for .NET with NuGet support</small>


| 🔥: 87 \| 💬: [49](https://news.ycombinator.com/item?id=44136884) \| 🗓️ 2025-05-30


<br />
W++是一款**实验性**的.NET脚本语言，灵感来自Python的简洁语法，但拥有独立的运行时和编译器。它具备**异步编程**、lambda表达式等现代特性，并支持通过NuGet导入库。该项目最初是开发者Ofek Bickel的学习实验，意外获得VSCode扩展3.3万次下载后因不明原因下架。核心特点包括自定义语法高亮、伪OOPSIE编程模型（调侃OOP），以及直接编译为IL代码的能力。虽然形似Python，但W++强调与.NET生态深度集成，**不兼容Python库**。开源协议为MIT，代码已完整公开。

---

## <a name="16"></a>16. 亚当·里斯与哈勃张力问题 
<small>🔗 [theatlantic.com](https://www.theatlantic.com/science/archive/2025/05/adam-riess-hubble-tension/682980/): Adam Riess and the Hubble tension</small>


| 🔥: 78 \| 💬: [65](https://news.ycombinator.com/item?id=44136945) \| 🗓️ 2025-05-30


<br />
诺贝尔奖得主**亚当·里斯**因发现宇宙加速膨胀而闻名，这一发现催生了**暗能量**理论，成为现代宇宙学的基石。然而，近年来的观测数据却与标准模型预测的宇宙膨胀率不符，这一矛盾被称为**哈勃张力**。里斯认为，这可能是标准模型存在缺陷的信号。尽管部分科学家持观望态度，但新数据（如DESI观测结果）进一步暗示暗能量可能随时间减弱，若证实，将彻底改写宇宙终极命运的认知。里斯正推动一场可能颠覆现有理论的科学革命。

---

## <a name="17"></a>17. 当AI生成的谎言比真相更诱人时会发生什么？ 
<small>🔗 [behavioralscientist.org](https://behavioralscientist.org/what-happens-when-ai-generated-lies-are-more-compelling-than-the-truth/): What Happens When AI-Generated Lies Are More Compelling Than the Truth?</small>


| 🔥: 74 \| 💬: [103](https://news.ycombinator.com/item?id=44134613) \| 🗓️ 2025-05-30


<br />
从19世纪林肯照片修图到当代**深度伪造**技术，虚假图像的制作门槛大幅降低。AI工具如Midjourney和DALL-E能凭空生成逼真内容，且**无真实参照物**，加剧了谎言传播风险。政治领域已出现伪造音频误导选民的事件，专家警告这可能导致公众**怀疑所有信息**，甚至动摇理性认知基础。当真相模糊时，神话和阴谋论可能主导舆论——正如浪漫主义诗人济慈所言，"美即是真"，而美往往取决于主观感受。技术正将我们推向一个虚拟比现实更"真实"的时代，这对民主和信任构成深层威胁。

---

## <a name="18"></a>18. 玛莎百货何时恢复线上订单？ 
<small>🔗 [moneyweek.com](https://moneyweek.com/personal-finance/marks-and-spencer-online-order-problems): When will M&S take online orders again?</small>


| 🔥: 71 \| 💬: [97](https://news.ycombinator.com/item?id=44137630) \| 🗓️ 2025-05-30


<br />
玛莎百货因**网络攻击**导致线上服务持续中断，预计**6月至7月**逐步恢复。自4月25日起，官网及APP暂停下单，造成约**3亿英镑**利润损失，股价下跌超10%。黑客窃取了部分客户**个人信息**（如联系方式、订单记录），但未涉及支付密码。公司建议用户重置密码并警惕诈骗。分析师认为此次事件属短期冲击，长期业务仍具潜力。

---

## <a name="19"></a>19. 将AI编程工具视为协作者，而非拐杖 
<small>🔗 [newsletter.oberai.dev](https://newsletter.oberai.dev/p/stop-vibe-coding-every-damn-time): Use AI code tools as collaborators, not crutches</small>


| 🔥: 70 \| 💬: [61](https://news.ycombinator.com/item?id=44138869) \| 🗓️ 2025-05-30


<br />
文章批判了当下流行的**氛围编程（vibe coding）**现象——开发者过度依赖工具生成代码却不理解底层逻辑，导致安全隐患（如API密钥泄露）。作者强调**AI辅助编程**应保持主动性：需掌握基础知识、预先规划功能、编写精准提示词，并将AI视为需要严格审查的“初级开发者”。核心观点是：**工具无法替代思考**，唯有扎实的技术功底与审慎的设计才能构建可靠系统。

---

## <a name="20"></a>20. OrioleDB桥接索引：架构解析与日常应用 
<small>🔗 [orioledb.com](https://www.orioledb.com/blog/orioledb-bridged-indexes): Bridged Indexes in OrioleDB: architecture, internals and everyday use?</small>


| 🔥: 68 \| 💬: [12](https://news.ycombinator.com/item?id=44134728) \| 🗓️ 2025-05-30


<br />
OrioleDB通过**桥接索引**支持非B树索引（如GIN、GiST），解决其MVCC存储与PostgreSQL原生索引的兼容问题。核心机制包括：**虚拟iptr列**（稳定指针）、**桥接索引**（映射iptr到主键）及三级查询路径（索引→iptr→主键）。日常使用中，创建非B树索引时会自动构建桥接层，也可手动控制。性能方面，虽增加一次B树查询开销，但保留了PostgreSQL丰富索引生态，无需重写扩展即可享受MVCC优势。

---
