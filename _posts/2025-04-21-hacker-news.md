---
layout: page
title: 勒西科技日报 - 2025年04月21日
date: 2025-04-21 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 被微软分叉的困境；
1. 开源对话TTS模型Dia：一键生成超真实语音对话；
1. 在任天堂Wii上运行的博客实验；
1. FTC指控优步欺诈性收费及取消服务违规；
1. EverTop：续航超百小时的电子墨水屏IBM XT复古电脑；

以上是今天的前五条黑科技新闻标题。

总共25条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 被微软分叉的困境 
<small>🔗 [philiplaine.com](https://philiplaine.com/posts/getting-forked-by-microsoft/): Getting forked by Microsoft</small>


| 🔥🔥: 1653 \| 💬: [877](https://news.ycombinator.com/item?id=43750535) \| 🗓️ 2025-04-21


<br />
作者三年前开发了开源工具**Spegel**，用于解决Kubernetes集群镜像分发的痛点。微软曾主动联系合作，但后续杳无音信。直到KubeCon上，作者发现微软推出了功能相似的**Peerd**，且代码中保留了大量Spegel的测试用例和注释，却未明确标注来源。尽管MIT许可证允许分叉，但微软未遵守署名要求，导致用户混淆，并挤压了原项目的生存空间。作者反思开源维护者与大公司的权力失衡，考虑变更许可证，并通过GitHub赞助维持开发。目前Spegel仍拥有1700星和1440万次下载，但这一事件暴露了开源生态的脆弱性。

---

## <a name="2"></a>2. 开源对话TTS模型Dia：一键生成超真实语音对话 
<small>🔗 [github.com](https://github.com/nari-labs/dia): Show HN: Dia, an open-weights TTS model for generating realistic dialogue</small>


| 🔥🔥: 433 \| 💬: [139](https://news.ycombinator.com/item?id=43754124) \| 🗓️ 2025-04-21


<br />
Nari Labs推出的**Dia**是一款1.6B参数的开源权重文本转语音模型，专为生成**高度拟真对话**设计。支持通过音频调节情感与语调，并能模拟笑声、咳嗽等非语言声音。模型权重已托管于Hugging Face，提供推理代码和在线演示。需GPU运行（A4000显卡实时生成），未来将优化CPU支持与量化版本。项目采用Apache-2.0许可，严禁用于伪造身份或恶意用途。开发者可通过Discord参与社区讨论。

---

## <a name="3"></a>3. 在任天堂Wii上运行的博客实验 
<small>🔗 [blog.infected.systems](https://blog.infected.systems/posts/2025-04-21-this-blog-is-hosted-on-a-nintendo-wii/): Blog hosted on a Nintendo Wii</small>


| 🔥🔥: 432 \| 💬: [87](https://news.ycombinator.com/item?id=43754953) \| 🗓️ 2025-04-21


<br />
一位开发者成功将**NetBSD 10.1**移植到任天堂Wii主机，并部署了一个静态博客。Wii搭载的**PowerPC 750架构**单核处理器性能有限，但通过优化（如禁用非必要服务、使用Caddy反向代理处理TLS加密）实现了稳定运行。文章详细记录了从破解Wii、安装NetBSD到配置轻量级Web服务器的全过程，并对比了Wii与太空探测器（如詹姆斯·韦伯望远镜）同款芯片的有趣性能差异。最终，这台功耗仅18W的“服务器”以每月约3.47英镑的成本运行，展现了**非传统硬件**的另类可能性。

---

## <a name="4"></a>4. FTC指控优步欺诈性收费及取消服务违规 
<small>🔗 [ftc.gov](https://www.ftc.gov/news-events/news/press-releases/2025/04/ftc-takes-action-against-uber-deceptive-billing-cancellation-practices): FTC takes action against Uber for deceptive billing and cancellation practices</small>


| 🔥🔥: 365 \| 💬: [207](https://news.ycombinator.com/item?id=43754274) \| 🗓️ 2025-04-21


<br />
美国联邦贸易委员会（FTC）于2025年4月21日对优步（Uber）采取行动，指控其存在**未经用户同意**订阅收费、**设置障碍**阻碍用户取消服务等**欺骗性行为**。FTC指出，优步通过隐蔽方式将消费者纳入付费订阅计划，并在取消流程中增加不必要的难度，损害了消费者权益。

---

## <a name="5"></a>5. EverTop：续航超百小时的电子墨水屏IBM XT复古电脑 
<small>🔗 [github.com](https://github.com/ericjenott/Evertop): Evertop: E-ink IBM XT clone with 100+ hours of battery life</small>


| 🔥🔥: 333 \| 💬: [110](https://news.ycombinator.com/item?id=43757037) \| 🗓️ 2025-04-21


<br />
EverTop是一款**超低功耗**的便携式电脑，复刻了IBM XT架构（80186处理器+1MB内存），支持运行DOS、Minix等80年代操作系统及Windows 3.0。其核心亮点包括：**电子墨水屏**显示（5.83英寸，无刷新不耗电）、**双10000mAh电池**与太阳能充电设计，单次充电可实现200至500小时持续使用，极端省电模式下甚至可达数千小时。内置丰富外设接口（PS/2、USB、以太网等），并支持蓝牙、Wi-Fi和LoRA无线通信。另有简化版"EverTop Min"移除键盘等部件以降低成本，保留核心功能。开发者通过ESP32微控制器实现硬件模拟，开源项目采用GPL-3.0协议。

---

## <a name="6"></a>6. 管道操作：编程语言中最优雅的特性 
<small>🔗 [herecomesthemoon.net](https://herecomesthemoon.net/2025/04/pipelining/): Pipelining might be my favorite programming language feature</small>


| 🔥🔥: 297 \| 💬: [262](https://news.ycombinator.com/item?id=43751076) \| 🗓️ 2025-04-21


<br />
管道操作（pipelining）是编程语言中一种让代码更清晰、更易读的特性。它允许开发者以链式调用的方式组织代码，避免嵌套函数带来的混乱。例如，在Rust中，`data.iter().filter(...).map(...).collect()` 的写法远比嵌套的 `collect(map(filter(...)))` 直观。  

**关键优势**：  
- **可读性**：代码按执行顺序排列，易于理解和注释。  
- **编辑友好**：添加或修改中间步骤时无需调整括号或缩进。  
- **工具支持**：IDE能基于类型提示自动补全链式调用的方法。  

此外，管道操作在SQL、构建器模式（Builder Pattern）等领域也有广泛应用，甚至能简化Haskell中复杂的函数组合。尽管语法细节因语言而异，但其核心思想——**让数据流动更直观**——始终是提升开发体验的关键。

---

## <a name="7"></a>7. 美国化石燃料发电占比首次跌破50% 
<small>🔗 [ember-energy.org](https://ember-energy.org/latest-updates/fossil-fuels-fall-below-50-of-us-electricity-for-the-first-month-on-record/): Fossil fuels fall below 50% of US electricity for the first month on record</small>


| 🔥🔥: 294 \| 💬: [285](https://news.ycombinator.com/item?id=43750617) \| 🗓️ 2025-04-21


<br />
根据全球能源智库Ember数据，2025年3月，**化石燃料**在美国发电量中的占比降至**49.2%**，首次低于50%，清洁能源占比达**50.8%**。这一里程碑主要得益于**风电和太阳能**创纪录增长（占总发电量24.4%），其中太阳能发电同比激增37%，风电增长12%。过去十年间，美国风光发电份额从5.7%跃升至当前水平，而化石燃料占比从65%持续下降。报告指出，风光发电正推动美国能源系统迈向清洁能源主导的转折点。

---

## <a name="8"></a>8. Bluesky推出全新验证机制：蓝标认证与可信验证者 
<small>🔗 [bsky.social](https://bsky.social/about/blog/04-21-2025-verification): A new form of verification on Bluesky</small>


| 🔥🔥: 281 \| 💬: [192](https://news.ycombinator.com/item?id=43753651) \| 🗓️ 2025-04-21


<br />
Bluesky宣布升级验证系统，新增**蓝标认证**功能，平台将主动为真实且知名的账号添加蓝色勾选标记。同时引入**可信验证者**机制，允许《纽约时报》等权威机构直接为旗下账号颁发特殊蓝标（带锯齿边），平台会二次审核确保真实性。用户可点击蓝标查看验证来源，或通过设置隐藏验证标识。目前暂未开放主动申请通道，但鼓励用户通过**域名绑定用户名**完成自主验证。

---

## <a name="9"></a>9. LLM工具是开发者的“机甲战衣”，而非替代者 
<small>🔗 [matthewsinclair.com](https://matthewsinclair.com/blog/0178-why-llm-powered-programming-is-more-mech-suit-than-artificial-human): LLM-powered tools amplify developer capabilities rather than replacing them</small>


| 🔥🔥: 250 \| 💬: [157](https://news.ycombinator.com/item?id=43752492) \| 🗓️ 2025-04-21


<br />
作者通过使用Claude Code快速构建两个项目的实践，指出**AI编程工具并非取代开发者，而是大幅增强其能力**。如同《异形》中雷普利操控动力装载机，开发者仍需掌控架构设计、质量标准和方向，但代码实现效率提升惊人。然而**AI存在过度行动倾向**，需开发者持续监督以避免错误决策。经验尤为关键——新手可能无法识别AI生成的隐患代码。未来开发者需掌握**与AI协作的新技能**，将重心从写代码转向业务理解与架构设计，同时培养果断推翻重来的勇气。这场变革中，人机协作的“半人马模式”将释放远超单独工作的潜力。

---

## <a name="10"></a>10. 教皇方济各逝世 多国领导人哀悼 
<small>🔗 [bbc.co.uk](https://www.bbc.co.uk/news/live/crknlnzlrzdt): Pope Francis has died</small>


| 🔥🔥: 221 \| 💬: [18](https://news.ycombinator.com/item?id=43749449) \| 🗓️ 2025-04-21


<br />
欧洲委员会主席**冯德莱恩**称教皇"以谦卑和纯粹的爱激励了数百万天主教徒及更广泛人群"。印度总理**莫迪**表示"深感悲痛"，波兰总理图斯克追忆其"善良、温暖而敏感"，埃及总统塞西赞其为"和平、爱与慈悲之声"。全球政要纷纷表达对这位精神领袖的深切缅怀。

---

## <a name="11"></a>11. AI驱动的搜索研究现已真正实用 
<small>🔗 [simonwillison.net](https://simonwillison.net/2025/Apr/21/ai-assisted-search/): AI assisted search-based research works now</small>


| 🔥🔥: 183 \| 💬: [82](https://news.ycombinator.com/item?id=43752262) \| 🗓️ 2025-04-21


<br />
Simon Willison在2025年4月21日的博客中指出，经过两年半的发展，**AI辅助搜索研究**终于达到实用水平。早期工具如Perplexity和GPT-4版Bing因**幻觉问题**令人失望，但2025年的**o3、o4-mini和Gemini 2.5 Pro**通过实时搜索与推理结合，显著提升了准确性和效率。例如，o4-mini成功帮作者迁移代码库，而Google和Anthropic的同类功能仍落后。这一进步可能颠覆传统搜索引擎的经济模式，但也引发对网络内容生态的担忧。

---

## <a name="12"></a>12. 走出迷雾：越南“婴儿空运行动”的救赎与伤痕 
<small>🔗 [theverge.com](https://www.theverge.com/cs/features/651701/vietnam-operation-babylift-adoption-transnational): Out of the Fog</small>


| 🔥🔥: 139 \| 💬: [31](https://news.ycombinator.com/item?id=43752532) \| 🗓️ 2025-04-21


<br />
1975年，美国在越战尾声发起**“婴儿空运行动”**，以“人道救援”名义将近3000名越南儿童送往西方收养。官方宣称这是拯救混血孤儿免遭迫害，但许多孩子实为与父母失散，甚至被强行带走。首架运输机坠毁导致138人死亡，后续航班却未停歇。数十年后，被收养者面临身份认同危机，部分人遭受虐待或与原生家庭永久分离。这场行动既暴露了**战争创伤**的复杂性，也揭示了跨国收养中**权力失衡**的阴影。

---

## <a name="13"></a>13. 英伟达王冠松动：算力未来面临四大挑战 
<small>🔗 [mohitdagarwal.substack.com](https://mohitdagarwal.substack.com/p/from-dominance-to-dilemma-nvidia): The Future of Compute: Nvidia's Crown Is Slipping</small>


| 🔥🔥: 127 \| 💬: [93](https://news.ycombinator.com/item?id=43757017) \| 🗓️ 2025-04-21


<br />
随着AI需求向**超大规模云厂商**集中，**定制芯片**崛起和**分布式训练**趋势加剧，英伟达的垄断地位正受冲击。谷歌TPU、亚马逊Trainium等自研芯片已替代部分GPU需求，而微软、Meta也在加速布局。**独立云服务商**因价格战陷入困境，进一步削弱英伟达的多元化客户基础。长期来看，超大规模企业主导的垂直整合模式可能重塑AI算力格局。

---

## <a name="14"></a>14. 价格调整公告 
<small>🔗 [windsurf.com](https://windsurf.com/blog/pricing-v2): An update to our pricing</small>


| 🔥🔥: 123 \| 💬: [80](https://news.ycombinator.com/item?id=43755321) \| 🗓️ 2025-04-21


<br />
本文为**风帆运动资讯**的订阅提醒，邀请用户通过填写**有效邮箱地址**及时获取最新动态。内容强调需确保邮箱格式正确以完成订阅，但未提及具体价格变动细节。核心目的是**提升用户订阅率**并保持信息触达的准确性。

---

## <a name="15"></a>15. 非洲互联网资源遭窃取：中国商人操控IP地址牟利 
<small>🔗 [capeindependent.com](https://www.capeindependent.com/article/the-campaign-to-subvert-africas-internet-registry): The campaign to subvert Africa's internet registry</small>


| 🔥🔥: 113 \| 💬: [28](https://news.ycombinator.com/item?id=43753738) \| 🗓️ 2025-04-21


<br />
非洲互联网注册机构**AFRINIC**原定选举新董事会，但因中国公民**卢恒**通过诉讼冻结其资产而陷入瘫痪。卢恒通过空壳公司获取非洲稀缺的IPv4地址（占非洲总量5%），并违规转售至境外，部分IP甚至涉及儿童色情和赌博。AFRINIC曾收回其IP，但卢恒在毛里求斯发起25起诉讼，利用法律漏洞瘫痪该机构运营。目前AFRINIC由官方接管，但核心功能仍受阻，威胁非洲互联网发展。

---

## <a name="16"></a>16. M.2 HDMI采集卡评测：小巧强悍的Linux兼容设备 
<small>🔗 [interfacinglinux.com](https://interfacinglinux.com/2025/04/18/magewell-eco-m-2-hdmi-capture-card/): A M.2 HDMI capture card</small>


| 🔥🔥: 109 \| 💬: [39](https://news.ycombinator.com/item?id=43755286) \| 🗓️ 2025-04-21


<br />
文章评测了**Magewell Eco M.2 HDMI采集卡**，这款产品利用M.2接口替代传统PCIe插槽，支持双路1080p 60帧采集。作者详细记录了在**x86**和**ARM架构**（如Rockchip 3588）的Linux系统上安装驱动的过程，包括内核模块编译步骤。实测显示其画质与高端采集卡相当，且支持OBS和WebRTC应用。虽然原价较高（385美元），但二手市场60-100美元的性价比突出，适合需要**紧凑型专业采集方案**的用户。缺点是需要手动安装驱动且缺乏支架配件。

---

## <a name="17"></a>17. Nerdlog：高效多主机日志查看工具，带时间轴直方图 
<small>🔗 [github.com](https://github.com/dimonomid/nerdlog): Show HN: Nerdlog – Fast, multi-host TUI log viewer with timeline histogram</small>


| 🔥🔥: 108 \| 💬: [38](https://news.ycombinator.com/item?id=43750765) \| 🗓️ 2025-04-21


<br />
Nerdlog 是一款**快速、去中心化**的终端界面日志查看工具，支持同时从多台远程主机获取日志，并生成时间轴直方图。无需中央服务器，直接通过SSH连接远程主机，**实时过滤和分析日志**，仅传输必要数据（如250条日志和直方图数据），节省带宽。适用于系统日志（如/var/log/messages），支持自定义日志格式和文件。提供类Vim的快捷键操作，包括查询历史、时间范围调整和日志导出功能。需SSH访问权限及Gawk支持，目前处于概念验证阶段，但已具备较高实用性。

---

## <a name="18"></a>18. 美国国家劳工关系委员会（NLRB）内部举报人揭露DOGE项目异常情况 
<small>🔗 [whistlebloweraid.org](https://whistlebloweraid.org/wp-content/uploads/2025/04/2025_0414_Berulis-Disclosure-HELP-and-Oversight-with-Exhibits.pdf): Whistleblower statement on anomalies at time of DOGE work at NLRB [pdf]</small>


| 🔥🔥: 108 \| 💬: [13](https://news.ycombinator.com/item?id=43755298) \| 🗓️ 2025-04-21


<br />
该PDF文件为举报人提交的正式声明，指控在美国国家劳工关系委员会（NLRB）**DOGE项目**工作期间发现的**异常操作**和潜在违规行为。文档包含技术元数据（如生成时间、操作系统版本等），但核心内容涉及内部流程中的**不当行为**，可能影响项目公正性。由于文件为加密PDF，具体细节未公开，但举报性质表明事件涉及**系统性风险**，需进一步调查。

---

## <a name="19"></a>19. 表格化编程：受限环境下的表达性计算新范式 
<small>🔗 [sam.elborai.me](https://sam.elborai.me/articles/tabular-programming/): Tabular Programming: A New Paradigm for Expressive Computing</small>


| 🔥🔥: 101 \| 💬: [25](https://news.ycombinator.com/item?id=43751168) \| 🗓️ 2025-04-21


<br />
作者受便携音乐设备m8启发，提出一种基于**表格化界面**的编程范式，专为8键微型硬件设计。核心是将代码组织为结构化表格，每行函数限定5个表达式，强制**原子化分解**，提升可维护性。通过硬件约束（如Teensy微控制器）重构编程逻辑，实现**无键盘操作**和显式数据流。文中以经典demo特效（如等离子动画）为例，展示如何在极简界面中完成复杂计算，并探讨其在像素艺术等创意工具中的潜力。

---

## <a name="20"></a>20. 在Go中挑战内存回收机制 
<small>🔗 [mcyoung.xyz](https://mcyoung.xyz/2025/04/21/go-arenas/): Cheating the Reaper in Go</small>


| 🔥: 95 \| 💬: [12](https://news.ycombinator.com/item?id=43756871) \| 🗓️ 2025-04-21


<br />
尽管作者是C++程序员，但Go语言因其**几乎不存在未定义行为**和简单的**GC语义**而吸引了他。文章探讨了如何在Go中实现**手动内存管理**，通过构建一个无类型的垃圾回收竞技场（arena）来展示这一可能性。Go的GC设计允许开发者在不依赖`runtime`包的情况下与GC协作，但需注意指针处理问题。通过基准测试，作者证明了arena分配器在性能上显著优于标准`new`操作，尤其在处理大内存块时提升可达2-4倍。关键挑战在于确保arena中的指针能被GC正确识别，避免提前释放。

---

## <a name="21"></a>21. 官方滥用国家安全手段：从恶劣走向骇人听闻 
<small>🔗 [theregister.com](https://www.theregister.com/2025/04/14/opinion_secret_state_security/?td=rt-3a): Official abuse of state security has always been bad, now it's horrifying</small>


| 🔥: 94 \| 💬: [10](https://news.ycombinator.com/item?id=43750144) \| 🗓️ 2025-04-21


<br />
英国政府试图秘密要求**苹果**在iCloud加密系统中植入后门，但遭拒绝后，苹果直接移除了英国用户的相关功能。此事因**秘密法庭**的争议浮出水面——法庭驳回了政府保密请求，暴露了其滥用国家安全名义的行为。与此同时，美国前总统**特朗普**以“压制言论自由”为由，撤销网络安全官员的安全许可，将国家安全机制武器化。文章指出，**数字时代的安全滥用危害更大**，需通过法律手段严惩此类行为，否则将威胁民主根基。

---

## <a name="22"></a>22. 苹果用户遭窃后数据被永久封锁，受害者集体起诉 
<small>🔗 [washingtonpost.com](https://www.washingtonpost.com/technology/2025/04/20/apple-stolen-iphone-lawsuit-theft/): Thieves took their iPhones. Apple won't give their digital lives back</small>


| 🔥: 92 \| 💬: [85](https://news.ycombinator.com/item?id=43755753) \| 🗓️ 2025-04-21


<br />
多名iPhone用户在手机被盗后，因**恢复密钥**被窃贼篡改，导致永久无法访问iCloud中的照片、工作文件等个人数据。尽管苹果掌握部分数据的解密密钥，却以**隐私保护政策**为由拒绝协助恢复。一起索赔500万美元的集体诉讼正在加州进行，原告指控苹果变相协助犯罪。最新推出的**失窃设备保护**功能需手动开启，多数用户并不知情。受害者呼吁苹果建立更灵活的身份验证机制，而非僵化执行安全协议。

---

## <a name="23"></a>23. 1是质数吗？这个问题为何重要？ 
<small>🔗 [mathenchant.wordpress.com](https://mathenchant.wordpress.com/2025/04/21/is-1-prime-and-does-it-matter/): Is 1 Prime, and Does It Matter?</small>


| 🔥: 77 \| 💬: [124](https://news.ycombinator.com/item?id=43755506) \| 🗓️ 2025-04-21


<br />
关于数字1是否属于**质数**的争议历史悠久。古希腊毕达哥拉斯学派认为1是构建数字的"单位"而非质数，而柏拉图学派则持相反观点。18世纪数学家欧拉和20世纪的哈代也曾将1归类为质数，体现了数学定义的灵活性。现代数学界达成共识将1排除在质数之外，主要因其会导致**算术基本定理**（唯一分解定理）等核心概念表述复杂化。但1的独特性使其被归为**单位数**，在代数数论中具有特殊地位。这场争论的本质并非数学真理的对立，而是人类为追求理论简洁性对术语的优化选择。

---

## <a name="24"></a>24. 正则表达式并不难（2023） 
<small>🔗 [timkellogg.me](https://timkellogg.me/blog/2023/07/11/regex): Regex Isn't Hard (2023)</small>


| 🔥: 71 \| 💬: [89](https://news.ycombinator.com/item?id=43750314) \| 🗓️ 2025-04-21


<br />
正则表达式常因复杂而饱受诟病，但掌握其**核心子集**就能轻松应对多数场景。关键在于四个基础概念：**字符集**（如`[a-z]`匹配小写字母）、**重复符**（`?`、`*`、`+`）、**分组**（提取或重复子模式）以及**边界符**（`^`和`$`）。作者建议忽略非便携的复杂特性（如`\w`或`.`），专注跨语言通用的简洁语法。正则能以极简代码高效处理文本，远超传统过程式代码。尽管部分语言（如Rust）提供替代方案，正则仍是文本处理的利器，值得投入少量时间学习。

---

## <a name="25"></a>25. ChatGPT等AI工具正在削弱人类智力吗？ 
<small>🔗 [theguardian.com](https://www.theguardian.com/technology/2025/apr/19/dont-ask-what-ai-can-do-for-us-ask-what-it-is-doing-to-us-are-chatgpt-and-co-harming-human-intelligence): Are ChatGPT and co harming human intelligence?</small>


| 🔥: 67 \| 💬: [81](https://news.ycombinator.com/item?id=43750165) \| 🗓️ 2025-04-21


<br />
近期研究显示，**人类智商（IQ）**出现下降趋势，可能与过度依赖AI处理认知任务有关。专家指出，**关键思维能力**和**记忆力**因AI代劳而退化，如同肌肉不用则萎缩。尽管环境因素复杂，但AI的便捷性导致人们减少主动思考，甚至影响创造力和抗风险能力。学者呼吁通过教育重建人类**批判性思维**优势，避免认知能力被算法取代。

---
