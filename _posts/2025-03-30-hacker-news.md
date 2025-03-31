---
layout: page
title: 勒西科技日报 - 2025年03月30日
date: 2025-03-30 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. FBI突袭知名计算机科学家住所，当事人失联且校方删除所有信息；
1. 美国宪法第一修正案的五大支柱如何遭受冲击；
1. 怀旧风桌面系统Blue95：重现童年电脑室的经典体验；
1. 当代大学生的困境：一位教授的观察；
1. GitHub CodeQL高危供应链漏洞：短暂泄露的密钥引发连锁攻击风险；

以上是今天的前五条黑科技新闻标题。

总共25条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. FBI突袭知名计算机科学家住所，当事人失联且校方删除所有信息 
<small>🔗 [arstechnica.com](https://arstechnica.com/security/2025/03/computer-scientist-goes-silent-after-fbi-raid-and-purging-from-university-website/): FBI raids home of prominent computer scientist who has gone incommunicado</small>


| 🔥🔥: 734 \| 💬: [303](https://news.ycombinator.com/item?id=43527001) \| 🗓️ 2025-03-30


<br />
**知名密码学专家**Xiaofeng Wang（印第安纳大学教授）近期失联，其雇主**悄无声息地删除了**他的个人资料、邮箱和电话。FBI同时突袭了他在布鲁明顿和卡梅尔的两处住所，搬走多箱物品，但未透露调查原因。Wang曾主导2300万美元的研究项目，专攻**加密技术与数据隐私**，其妻Nianli Ma的校方信息也被删除。同行学者质疑此事异常，校方未回应其是否在职。FBI仅确认行动获法院授权，拒绝进一步评论。案件细节仍未公开。

---

## <a name="2"></a>2. 美国宪法第一修正案的五大支柱如何遭受冲击 
<small>🔗 [krebsonsecurity.com](https://krebsonsecurity.com/2025/03/how-each-pillar-of-the-1st-amendment-is-under-attack/): How Each Pillar of the First Amendment Is Under Attack</small>


| 🔥🔥: 689 \| 💬: [367](https://news.ycombinator.com/item?id=43529707) \| 🗓️ 2025-03-30


<br />
本文揭露特朗普政府近期一系列威胁**言论自由**、**宗教自由**、**新闻自由**、**集会自由**及**请愿权**的行为。例如，通过解雇处理信息公开请求的官员、打压批评性媒体、限制学生抗议活动，甚至威胁削减法院预算以干预司法独立。**行政权力**的扩张正系统性削弱宪法保障的基本权利，引发对民主根基的担忧。

---

## <a name="3"></a>3. 怀旧风桌面系统Blue95：重现童年电脑室的经典体验 
<small>🔗 [github.com](https://github.com/winblues/blue95): Blue95: a desktop for your childhood home's computer room</small>


| 🔥🔥: 422 \| 💬: [217](https://news.ycombinator.com/item?id=43524937) \| 🗓️ 2025-03-30


<br />
Blue95是一款基于**Fedora Atomic Xfce**的轻量级桌面系统，通过**Chicago95主题**复刻了Windows 95的经典界面，兼顾现代功能与怀旧美学。支持通过ISO或**rpm-ostree rebase**从其他Atomic系统迁移，提供Live CD测试环境。项目目标包括保持Fedora核心更新、集成Universal Blue优化，并平衡**可用性**与复古设计，而非完全复刻旧系统。当前安装工具为测试版，建议优先通过镜像库部署。

---

## <a name="4"></a>4. 当代大学生的困境：一位教授的观察 
<small>🔗 [hilariusbookbinder.substack.com](https://hilariusbookbinder.substack.com/p/the-average-college-student-today): The average college student today</small>


| 🔥🔥: 396 \| 💬: [517](https://news.ycombinator.com/item?id=43522966) \| 🗓️ 2025-03-30


<br />
一位拥有30年教龄的教授指出，如今**普通大学生**的学术能力显著下滑：**功能性文盲**现象普遍（无法阅读严肃文学作品），写作水平仅相当于八年级，且依赖**ChatGPT**作弊。课堂表现同样堪忧——长期缺勤、手机成瘾、对学习漠不关心。他认为这不仅是教育问题，更是社会病态的缩影，而智能手机的沉迷是关键诱因。尽管教授试图维持标准，但现实迫使他调整教学方式。

---

## <a name="5"></a>5. GitHub CodeQL高危供应链漏洞：短暂泄露的密钥引发连锁攻击风险 
<small>🔗 [praetorian.com](https://www.praetorian.com/blog/codeqleaked-public-secrets-exposure-leads-to-supply-chain-attack-on-github-codeql/): Public secrets exposure leads to supply chain attack on GitHub CodeQL</small>


| 🔥🔥: 208 \| 💬: [36](https://news.ycombinator.com/item?id=43527044) \| 🗓️ 2025-03-30


<br />
研究人员发现GitHub的代码分析工具**CodeQL**存在严重漏洞：工作流生成的**GITHUB_TOKEN**密钥在1.022秒内可被截获。攻击者可利用此短暂时间窗口创建恶意分支、篡改标签，甚至通过覆盖`v3`标签触发**供应链攻击**，影响所有默认启用CodeQL的仓库。GitHub已修复漏洞并确认未被利用，但该漏洞暴露了CI/CD流程中密钥管理的核心风险。

---

## <a name="6"></a>6. Rust Any系列第三篇：向上转型终获支持 
<small>🔗 [lucumr.pocoo.org](https://lucumr.pocoo.org/2025/3/27/any-upcast/): Rust Any part 3: we have upcasts</small>


| 🔥🔥: 166 \| 💬: [71](https://news.ycombinator.com/item?id=43523238) \| 🗓️ 2025-03-30


<br />
Armin Ronacher在本文中回顾了三年前提出的**As-Any Hack**——一种在Rust稳定版中实现**向上转型到父特征**的变通方案。当时即使`DebugAny`继承自`Any`，也无法直接调用`Any`的方法（如`downcast_ref`）。随着**Rust 1.86**的发布，这一限制被彻底解决，现在可安全地将`&dyn DebugAny`转为`&dyn Any`并执行类型向下转换。作者欢呼这一改进将淘汰大量旧代码，并感谢相关贡献者。

---

## <a name="7"></a>7. 伦敦警方突袭贵格会所逮捕气候活动人士 
<small>🔗 [thetimes.com](https://www.thetimes.com/uk/society/article/met-smash-down-door-of-quaker-meeting-house-to-arrest-activists-jhhchrtlt): Met Police smash down door of Quaker meeting house to arrest activists</small>


| 🔥🔥: 144 \| 💬: [91](https://news.ycombinator.com/item?id=43525909) \| 🗓️ 2025-03-30


<br />
超过20名**伦敦警察厅**警员强行闯入伦敦市中心一间**贵格会**礼拜场所，逮捕6名参与讨论气候变化和加沙问题的女性。警方称她们涉嫌“密谋造成公共妨害”，但未提出指控。这是该和平主义宗教团体历史上首次遭遇此类突袭。贵格会谴责警方行动侵犯宗教场所尊严，要求道歉。事件引发对英国**抗议自由**过度压制的争议，涉事青年组织“Youth Demand”此前曾发起非暴力抗议活动。被捕者包括大学生，部分人声称遭遇超12小时羁押且住所被搜查。

---

## <a name="8"></a>8. SML语言四讲（1989年PDF） 
<small>🔗 [cs.tufts.edu](https://www.cs.tufts.edu/~nr/cs257/archive/mads-tofte/four-lectures.pdf): Four Lectures on Standard ML (1989) [pdf]</small>


| 🔥🔥: 139 \| 💬: [31](https://news.ycombinator.com/item?id=43522363) \| 🗓️ 2025-03-30


<br />
这份1989年的PDF文档包含四篇关于**Standard ML（SML）**编程语言的讲座内容。SML是一种**函数式编程语言**，以其严格的类型系统和形式化语义著称。讲座可能涵盖SML的基础语法、类型推导、模块系统等核心概念，适合对**编程语言理论**或函数式编程感兴趣的学习者。文档为技术性资料，内容较为专业。

---

## <a name="9"></a>9. 在教室安装空气净化器竟能显著提升学习成绩 
<small>🔗 [vox.com](https://www.vox.com/2020/1/8/21051869/indoor-air-pollution-student-achievement): Installing air filters in classrooms has surprisingly large educational benefits (2020)</small>


| 🔥🔥: 138 \| 💬: [59](https://news.ycombinator.com/item?id=43529257) \| 🗓️ 2025-03-30


<br />
洛杉矶学校因2015年天然气泄漏事件误报安装了**空气净化器**，结果学生**数学和英语成绩**分别提高了0.20和0.18个标准差，效果堪比缩减三分之一班级规模。研究表明，**空气污染**会损害认知能力，而净化器仅需700美元/间教室，是性价比极高的教育干预措施。低收入社区可能受益更大，建议推广试验以验证长期效果。

---

## <a name="10"></a>10. 因自闭症纪念纹身被ICE拘留 委内瑞拉男子遭遣送萨尔瓦多监狱 
<small>🔗 [latintimes.com](https://www.latintimes.com/man-detained-ice-autism-awareness-tattoo-still-sent-prison-after-officers-declared-him-clean-579373): Man Detained by ICE for Autism Awareness Tattoo Sent to Prison</small>


| 🔥🔥: 124 \| 💬: [24](https://news.ycombinator.com/item?id=43527154) \| 🗓️ 2025-03-30


<br />
25岁的**无证移民**内里·阿尔瓦拉多因三处纹身在休斯顿被拘留，其中一处是纪念患自闭症的弟弟的**自闭症意识丝带纹身**。尽管ICE探员确认他与犯罪组织无关并宣布"清白"，他仍被秘密转移，最终被列入238名遣送至萨尔瓦多恐怖主义拘留中心的委内瑞拉人名单。家属称其"连苍蝇都不伤害"，质疑拘留的**不公正性**。事件暴露移民执法中的任意性。

---

## <a name="11"></a>11. Span<T>.SequenceEquals 比 memcmp 更快 
<small>🔗 [richardcocks.github.io](https://richardcocks.github.io/2025-03-30-FasterThanMemCmp.html): Span<T>.SequenceEquals is faster than memcmp</small>


| 🔥🔥: 123 \| 💬: [64](https://news.ycombinator.com/item?id=43524665) \| 🗓️ 2025-03-30


<br />
本文探讨了在 .NET 中使用 **Span<T>** 提升性能的优势。作者在将代码从 .NET Framework 4.8.1 迁移到 .NET 8 时，发现许多代码依赖 `msvcrt.dll` 的 `memcmp` 函数来比较字节数组。通过基准测试发现，**Span<T>.SequenceEqual** 在现代 .NET 中表现更优，尤其在处理大数组时显著快于传统方法。例如，在 .NET 8 中，`SequenceEqual` 比 `memcmp` 快约 500 倍（1MB 数组）。对于 .NET Framework 用户，推荐使用 `Span<T>` 替代外部 C 库，而 .NET 8 用户可直接使用内置的 `SequenceEqual`，无需额外依赖。

---

## <a name="12"></a>12. 为什么这个网站用C语言构建 
<small>🔗 [marcelofern.com](https://marcelofern.com/posts/c/why-is-this-site-built-with-c/index.html): Why Is This Site Built with C</small>


| 🔥🔥: 120 \| 💬: [101](https://news.ycombinator.com/item?id=43526058) \| 🗓️ 2025-03-30


<br />
作者自2017年起搭建个人网站，经历了从**Django动态框架**到**Nuxt静态生成器**的迭代，但均因维护复杂、依赖过多而放弃。最终选择用C语言重写，核心工具是仅依赖标准库的**md4c解析器**，仅需250行代码即可将Markdown转为HTML，解析87篇文章仅需0.1秒。这一方案满足了**零依赖**、**长期稳定**和**极致速度**的核心需求，避免了现代工具链的臃肿问题。

---

## <a name="13"></a>13. 黑客定律大全 
<small>🔗 [hacker-laws.com](https://hacker-laws.com/): Hacker Laws</small>


| 🔥🔥: 119 \| 💬: [16](https://news.ycombinator.com/item?id=43523974) \| 🗓️ 2025-03-30


<br />
该内容汇总了软件开发中常见的**定律、原则与模式**，如**90-9-1法则**（网络社区中1%用户创造大部分内容）、**布鲁克斯定律**（增加人力可能延误项目）和**CAP定理**（分布式系统的一致性、可用性与分区容错性不可兼得）。涵盖技术、认知偏差（如**邓宁-克鲁格效应**）及组织管理（如康威定律），强调这些理论是观察而非绝对真理，需结合场景应用。附电子书、播客等扩展资源。

---

## <a name="14"></a>14. ICE因长相像墨西哥人而拘留美国公民数小时 
<small>🔗 [techdirt.com](https://www.techdirt.com/2025/03/28/ice-arrested-and-detained-a-us-citizen-for-hours-because-he-looked-mexican/): ICE Arrested and Detained a US Citizen for Hours Because He Looked Mexican</small>


| 🔥🔥: 117 \| 💬: [12](https://news.ycombinator.com/item?id=43527275) \| 🗓️ 2025-03-30


<br />
一名合法**美国公民**诺列加被ICE（移民海关执法局）无正式逮捕令拘留，仅因外貌像墨西哥人。文章指出，特朗普政府纵容ICE以“威胁”或“非公民”为由**随意逮捕棕色人种**，且缺乏监管，导致任何人均可能面临类似**非法拘押**。问题核心在于ICE滥用行政令，侵犯公民权利。

---

## <a name="15"></a>15. Organic Maps因微软封禁GitHub账户迁移至Forgejo 
<small>🔗 [mastodon.social](https://mastodon.social/@organicmaps/114233788700982882): Organic Maps migrates to Forgejo due to GitHub account blocked by Microsoft</small>


| 🔥🔥: 108 \| 💬: [33](https://news.ycombinator.com/item?id=43525395) \| 🗓️ 2025-03-30


<br />
由于**微软**突然封禁了Organic Maps的GitHub账户，这款开源地图应用决定将代码仓库迁移至**Forgejo**平台。团队强调此举是为了避免中心化托管服务的风险，确保项目持续开放。文中同时提到Mastodon的JavaScript依赖问题，但该内容与迁移事件无关。**去中心化**成为本次事件的核心议题。

---

## <a name="16"></a>16. 在数字时代为孩子打造模拟童年 
<small>🔗 [joshuakennon.com](https://www.joshuakennon.com/raising-kids-to-have-an-analogue-childhood-in-a-digital-world/): Raising Kids to Have an Analog Childhood in a Digital World</small>


| 🔥🔥: 106 \| 💬: [50](https://news.ycombinator.com/item?id=43527019) \| 🗓️ 2025-03-30


<br />
作者分享如何在数字时代为孩子营造**以实体体验为核心**的成长环境。家庭规则包括：**严格限制电子设备**（无平板、短内容平台），专注实体玩具（书籍、乐器、积木）和自由创意游戏；通过**延迟满足训练**（如限制游戏时间）培养专注力；建立**诚实与信任**的家庭文化（撒谎零容忍）。核心目标是保护孩子的注意力，培养自主性与情感韧性，使其未来能抵御数字营销的侵蚀。

---

## <a name="17"></a>17. ICE秘密撤销中东学生签证 校方与学生均不知情 
<small>🔗 [zeteo.com](https://zeteo.com/p/ice-manually-revoking-university-students-residency-status-middle-east): ICE Revoking Students' Immigration Statuses Without Their or the Uni's Knowledge</small>


| 🔥: 99 \| 💬: [34](https://news.ycombinator.com/item?id=43528356) \| 🗓️ 2025-03-30


<br />
据报道，**美国移民及海关执法局（ICE）**正利用《移民与国籍法》第237条中罕见的“外交政策风险”条款，**单方面撤销**来自中东和穆斯林国家学生的签证及居留身份，且未通知学生或校方。部分学生仅在检查**SEVIS系统**时才发现身份失效，面临突然拘留风险。校方称此类操作“前所未见”，质疑政府滥用职权。国务卿卢比奥称已撤销至少300份签证，但未透露具体依据。

---

## <a name="18"></a>18. Linux系统编程入门（抢先体验版） 
<small>🔗 [nostarch.com](https://nostarch.com/introduction-system-programming-linux): Introduction to System Programming in Linux (Early Access)</small>


| 🔥: 93 \| 💬: [13](https://news.ycombinator.com/item?id=43526763) \| 🗓️ 2025-03-30


<br />
本书是面向**Linux/Unix操作系统**的编程指南，涵盖系统编程基础、命令行操作、文件I/O、进程管理、线程同步等核心内容。作者以**40年教学经验**撰写，结合图表与实战项目，适合具备**C/C++基础**的读者。无需Linux基础，但需准备Linux环境。抢先体验版包含部分章节，预售享25%折扣。作者Stewart N. Weiss为亨特学院计算机科学教授，专注Unix系统编程与开源开发。

---

## <a name="19"></a>19. 德国伊萨尔航天公司首射Spectrum火箭失败：一级飞行阶段失控坠海 
<small>🔗 [nasaspaceflight.com](https://www.nasaspaceflight.com/2025/03/isar-first-launch/): Isar Aerospace launches Spectrum, fails early in first stage flight</small>


| 🔥: 91 \| 💬: [51](https://news.ycombinator.com/item?id=43524784) \| 🗓️ 2025-03-30


<br />
德国**伊萨尔航天公司**于2025年3月30日首次尝试发射**Spectrum**两级火箭，但火箭在升空18秒后失控，30秒时被终止飞行并坠入挪威海。此次任务名为“全频谱行动”，是挪威及欧洲大陆（不含不列颠群岛和俄罗斯）首次轨道发射尝试。Spectrum火箭高28米，采用碳复合材料和3D打印金属发动机部件，设计运力为1000公斤至近地轨道。尽管首飞失败，公司表示获得了宝贵数据以改进技术。该火箭瞄准中小型卫星市场，已获挪威航天局等客户订单，计划未来在挪威安岛和法属圭亚那库鲁执行发射任务。

---

## <a name="20"></a>20. 地球自转能否发电？物理学界争议新理论 
<small>🔗 [nature.com](https://www.nature.com/articles/d41586-025-00847-0): Can Earth's rotation generate power? Physicists divided over controversial claim</small>


| 🔥: 90 \| 💬: [183](https://news.ycombinator.com/item?id=43526443) \| 🗓️ 2025-03-30


<br />
近日，有物理学家提出一项**争议性主张**，认为通过地球在自身**磁场**中旋转可产生**电能**。该理论引发学界分歧，相关研究已发表于《物理评论研究》。此前，地球磁场与自转的相互作用多被忽视，若验证成功或开辟新能源途径。但订阅期刊需付费（单篇1.95美元起），完整内容需通过机构访问或购买《Nature》订阅服务。

---

## <a name="21"></a>21. BreezeWiki：让Fandom百科页面变得清爽可读 
<small>🔗 [breezewiki.com](https://breezewiki.com/): BreezeWiki makes wiki pages on Fandom readable</small>


| 🔥: 90 \| 💬: [34](https://news.ycombinator.com/item?id=43529163) \| 🗓️ 2025-03-30


<br />
BreezeWiki是一个优化Fandom百科页面的工具，**去除广告、视频和推荐内容**，提供简洁的阅读体验，节省设备资源和流量。使用方法简单：将网址中的"fandom.com"替换为"breezewiki.com"即可跳转。用户还可通过**浏览器扩展**实现自动跳转。BreezeWiki由多个独立运行的镜像站点支持，确保稳定性。  

需要注意的是，BreezeWiki并非Fandom的替代品，**不支持编辑或创建新页面**。如需自建百科，推荐使用Miraheze。用户反馈普遍称赞其去广告效果，并批评Fandom页面因广告过多导致的性能问题。

---

## <a name="22"></a>22. 航班因乘客手机丢失中途返航：锂电池安全隐患引关注 
<small>🔗 [washingtonpost.com](https://www.washingtonpost.com/travel/2025/03/28/air-france-lost-cellphone/): Why a plane turned around when a passenger lost a phone midflight</small>


| 🔥: 89 \| 💬: [142](https://news.ycombinator.com/item?id=43523765) \| 🗓️ 2025-03-30


<br />
一架**法航**飞往加勒比海的航班因乘客丢失手机中途返回巴黎，以防**锂电池过热**引发安全风险。这是该航司两个月内第二起因手机返航事件。手机最终被找到，航班延误4小时。专家指出，手机卡在座椅中若受压可能**起火**，航司处置正确。近期多国加强机上电子设备管理，美国去年报告85起锂电池相关事故。乘客需妥善保管设备，避免造成隐患。

---

## <a name="23"></a>23. 用ASM在Java中实现尾递归优化（2023） 
<small>🔗 [unlinkedlist.org](https://unlinkedlist.org/2023/03/19/tail-call-recursion-in-java-with-asm/): Tail Call Recursion in Java with ASM (2023)</small>


| 🔥: 87 \| 💬: [36](https://news.ycombinator.com/item?id=43523741) \| 🗓️ 2025-03-30


<br />
本文探讨了如何通过**字节码操作工具ASM**在Java中实现**尾递归优化**。尾递归是一种特殊的递归形式，其最后一步是递归调用自身，从而避免栈帧的持续堆积。作者以阶乘函数为例，对比了普通递归与尾递归的差异，并详细解析了JVM方法调用的栈帧机制。通过ASM库，可以重写字节码，将递归调用替换为循环跳转，复用当前栈帧以提升性能。关键点包括：**尾递归特征识别**、**栈帧复用原理**以及**ASM的字节码转换技术**。这种方法能有效防止`StackOverflowError`，同时保持代码的优雅性。

---

## <a name="24"></a>24. MAME 0.276 发布：性能优化与大量游戏修复 
<small>🔗 [mamedev.org](https://www.mamedev.org/?p=549): MAME 0.276</small>


| 🔥: 77 \| 💬: [23](https://news.ycombinator.com/item?id=43527552) \| 🗓️ 2025-03-30


<br />
MAME 0.276 版本于 2025 年 3 月 31 日发布，带来多项重要更新。**64 位 ARMv8 重新编译器**进一步提速，修复了 Konami GX 街机游戏和 Philips CD-i 软件的图形问题。新增多款 IGS 赌博游戏及中国版麻将游戏，并完善了 LinnDrum 打击乐合成器的交互控制与音频输出。此外，修复了多款街机游戏的音频问题，改进了 PC-88VA 模拟器和 TI-99 电脑外设支持。Windows 用户新增调试器窗口任务栏显示选项。详细更新内容可查阅官方文档。

---

## <a name="25"></a>25. 孩子与阴影（1975） 
<small>🔗 [johnirons.com](https://www.johnirons.com/pdfs/shadowleguin.pdf): The Child and the Shadow (1975) [pdf]</small>


| 🔥: 74 \| 💬: [18](https://news.ycombinator.com/item?id=43525079) \| 🗓️ 2025-03-30


<br />
该PDF文档似乎是一篇1975年的文章或研究，标题为《孩子与阴影》。由于内容以**PDF编码数据**呈现，无法直接提取可读文本。可能涉及**儿童心理**或**成长阴影**的主题，推测探讨童年经历对个体发展的影响。若需具体内容，建议检查文件完整性或转换格式以获取可读文本。

---
