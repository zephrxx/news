---
layout: page
title: 勒西科技日报 - 2025年03月22日
date: 2025-03-22 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. PyTorch 内部机制解析；
1. Landrun：使用Landlock无根或容器化沙盒运行Linux进程；
1. 亚马逊挑战产品安全监管机构合宪性；
1. 利用计算机视觉增强OpenStreetMap地图功能；
1. “氛围编程”与现实的差距；

以上是今天的前五条黑科技新闻标题。

总共23条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. PyTorch 内部机制解析 
<small>🔗 [blog.ezyang.com](https://blog.ezyang.com/2019/05/pytorch-internals/): PyTorch Internals: Ezyang's Blog</small>


| 🔥🔥: 223 \| 💬: [15](https://news.ycombinator.com/item?id=43445931) \| 🗓️ 2025-03-22


<br />
本文深入探讨了 **PyTorch** 的内部结构，重点介绍了 **Tensor** 的核心概念及其实现方式。**Tensor** 是 PyTorch 的核心数据结构，包含数据、元数据（如大小、数据类型和设备）以及 **stride**（步幅），后者是 PyTorch 的独特特性，用于高效访问内存中的元素。文章还讨论了 **自动微分** 的实现机制，以及如何通过 **扩展点**（如设备、布局和数据类型）来扩展 Tensor 功能。最后，作者分享了在 PyTorch 代码库中导航的技巧，帮助开发者更好地理解和贡献代码。

---

## <a name="2"></a>2. Landrun：使用Landlock无根或容器化沙盒运行Linux进程 
<small>🔗 [github.com](https://github.com/Zouuup/landrun): Landrun: Sandbox any Linux process using Landlock, no root or containers</small>


| 🔥🔥: 198 \| 💬: [65](https://news.ycombinator.com/item?id=43445662) \| 🗓️ 2025-03-22


<br />
Landrun 是一个轻量级的工具，利用 **Landlock LSM** 在 Linux 内核中为任何进程提供安全的沙盒环境。它支持细粒度的文件系统访问控制、网络权限管理，并允许用户在不使用 root 权限或容器的情况下运行进程。适用于 Linux 5.13 及以上内核，支持 TCP 端口绑定和连接限制，适合需要高安全性和低开销的场景。

---

## <a name="3"></a>3. 亚马逊挑战产品安全监管机构合宪性 
<small>🔗 [washingtonpost.com](https://www.washingtonpost.com/technology/2025/03/21/amazon-product-safety-regulators-trump/): Amazon wants a product safety regulator declared unconstitutional</small>


| 🔥🔥: 132 \| 💬: [103](https://news.ycombinator.com/item?id=43446103) \| 🗓️ 2025-03-22


<br />
亚马逊起诉**美国消费品安全委员会（CPSC）**，称其结构违宪，试图逃避对平台上销售危险产品的责任。亚马逊认为其仅为第三方卖家提供物流服务，不应被视为“分销商”。此案可能影响联邦监管机构的独立性，尤其是特朗普政府试图削弱监管的背景下。

---

## <a name="4"></a>4. 利用计算机视觉增强OpenStreetMap地图功能 
<small>🔗 [blog.mozilla.ai](https://blog.mozilla.ai/map-features-in-openstreetmap-with-computer-vision/): Map Features in OpenStreetMap with Computer Vision</small>


| 🔥🔥: 132 \| 💬: [30](https://news.ycombinator.com/item?id=43447335) \| 🗓️ 2025-03-22


<br />
Mozilla.ai发布了**OpenStreetMap AI助手蓝图**，旨在通过**计算机视觉模型**加速地图绘制过程。该蓝图结合了**YOLOv11**目标检测和**SAM2**分割模型，自动识别并绘制地图特征，同时保留人工验证环节。通过此方法，绘制效率提升了约5倍，展示了AI在开源社区中的潜力。

---

## <a name="5"></a>5. “氛围编程”与现实的差距 
<small>🔗 [cendyne.dev](https://cendyne.dev/posts/2025-03-19-vibe-coding-vs-reality.html): "Vibe Coding" vs. Reality</small>


| 🔥🔥: 127 \| 💬: [89](https://news.ycombinator.com/item?id=43448432) \| 🗓️ 2025-03-22


<br />
“氛围编程”是一种依赖大型语言模型（LLM）自动生成代码的趋势，强调通过自然语言描述需求，让AI完成从构思到实现的整个过程。尽管这种工具让编程更易上手，但其**局限性**明显：生成的代码质量参差不齐，常犯低级错误，且无法处理复杂项目。**LLM代理**虽能快速搭建原型，但缺乏对细节的关注，难以胜任生产环境的需求。最终，**经验丰富的开发者**仍是确保软件可靠性和安全性的关键。

---

## <a name="6"></a>6. Facebook同意停止向英国女性投放定向广告 
<small>🔗 [bbc.co.uk](https://www.bbc.co.uk/news/articles/c1en1yjv4dpo): Facebook to stop targeting ads at UK woman after legal fight</small>


| 🔥🔥: 117 \| 💬: [86](https://news.ycombinator.com/item?id=43446821) \| 🗓️ 2025-03-22


<br />
Facebook同意停止使用个人数据向特定用户投放广告，此前Tanya O'Carroll对其母公司Meta提起诉讼。O'Carroll认为，**定向广告**属于**直接营销**，用户有权拒绝。英国信息专员办公室支持她的观点，认为企业应尊重用户的数据使用选择。Meta表示广告仅针对100人以上的群体，而非个人，但同意停止对O'Carroll的**个人数据**用于直接营销。她希望此举能为其他人提供先例，推动更多用户行使拒绝定向广告的权利。

---

## <a name="7"></a>7. FastOpenAPI：为多种Python框架自动生成API文档 
<small>🔗 [github.com](https://github.com/mr-fatalyst/fastopenapi): Show HN: FastOpenAPI – automated docs for many Python frameworks</small>


| 🔥: 94 \| 💬: [48](https://news.ycombinator.com/item?id=43445720) \| 🗓️ 2025-03-22


<br />
FastOpenAPI 是一个基于 **Pydantic v2** 的库，用于生成和集成 **OpenAPI** 文档，支持多种框架如 **Falcon、Flask、Sanic、Starlette** 和 **Tornado**。它提供了类似 FastAPI 的开发体验，支持数据验证和自动生成 Swagger UI 及 ReDoc 文档。安装简单，支持多种框架的快速集成，适合需要高效生成 API 文档的项目。

---

## <a name="8"></a>8. 极地涡旋即将减速：冬季天气或受影响 
<small>🔗 [climate.gov](https://www.climate.gov/news-features/blogs/polar-vortex/polar-vortex-hitting-brakes): The polar vortex is hitting the brakes</small>


| 🔥: 92 \| 💬: [23](https://news.ycombinator.com/item?id=43448023) \| 🗓️ 2025-03-22


<br />
根据NOAA的最新预测，**极地涡旋**在经历了整个冬季的强劲西风后，即将发生显著减速甚至逆转。这一现象被称为**突发平流层增温**，可能导致北极地区温度在短短几天内上升45°F（25°C）。虽然这种变化可能影响春季天气，但目前尚不确定是否会显著影响对流层和地表天气。

---

## <a name="9"></a>9. 微分几何入门：曲线与曲面的初步探索 
<small>🔗 [math.franklin.uga.edu](https://math.franklin.uga.edu/sites/default/files/users/user317/ShifrinDiffGeo.pdf): Differential Geometry: A First Course in Curves and Surfaces [pdf]</small>


| 🔥: 88 \| 💬: [3](https://news.ycombinator.com/item?id=43445614) \| 🗓️ 2025-03-22


<br />
本文介绍了**微分几何**的基础知识，重点探讨了**曲线**和**曲面**的数学性质。通过详细的公式推导和几何直观，帮助读者理解如何用数学工具描述和分析复杂的几何形状。适合对几何学感兴趣的初学者，为进一步学习高级几何理论打下基础。

---

## <a name="10"></a>10. 理解R1-Zero式训练：批判性视角 
<small>🔗 [github.com](https://github.com/sail-sg/understand-r1-zero): Understanding R1-Zero-Like Training: A Critical Perspective</small>


| 🔥: 85 \| 💬: [11](https://news.ycombinator.com/item?id=43445894) \| 🗓️ 2025-03-22


<br />
本文探讨了**R1-Zero式训练**的核心组件，包括基础模型和强化学习。研究发现，**Qwen2.5**基础模型在无提示模板的情况下表现出强大的推理能力，而**GRPO**算法存在偏差优化问题，提出了改进方案**Dr. GRPO**。通过实验，作者展示了如何在27小时内使用8块A100 GPU实现**Qwen2.5-Math-7B**的最优性能。研究还指出，模板和问题集的匹配对强化学习动态有重要影响。

---

## <a name="11"></a>11. Meta 使用盗版书籍训练其 AI 模型 
<small>🔗 [theatlantic.com](https://www.theatlantic.com/technology/archive/2025/03/libgen-meta-openai/682093/): Meta pirated books to train its AI</small>


| 🔥: 75 \| 💬: [71](https://news.ycombinator.com/item?id=43445616) \| 🗓️ 2025-03-22


<br />
Meta 在开发其旗舰 AI 模型 Llama 3 时，面临获取大量高质量文本的挑战。由于合法获取成本高且耗时，Meta 员工决定使用盗版图书馆 **Library Genesis (LibGen)** 的数据进行训练。LibGen 包含超过 750 万本书和 8100 万篇研究论文。Meta 内部讨论显示，此举存在**中高法律风险**，但公司仍选择下载并使用这些数据。Meta 和 OpenAI 均辩称，使用受版权保护的材料训练 AI 属于**合理使用**，但这一做法引发了广泛争议。

---

## <a name="12"></a>12. 马斯克告诫特斯拉员工不要抛售股票，而董事会和高管却在减持 
<small>🔗 [electrek.co](https://electrek.co/2025/03/21/elon-tells-tesla-employees-not-to-sell-tsla-stocks-board-execs-are-dumping/): Elon tells Tesla employees not to sell TSLA stock as board and execs are dumping</small>


| 🔥: 73 \| 💬: [24](https://news.ycombinator.com/item?id=43445557) \| 🗓️ 2025-03-22


<br />
2025年3月21日，埃隆·马斯克向特斯拉员工发出警告，**不要抛售公司股票**，尽管特斯拉董事会成员和高管们正在大量减持。这一举动引发了外界对特斯拉内部信心和未来前景的质疑。

---

## <a name="13"></a>13. 意大利要求谷歌根据严格的反盗版法污染DNS 
<small>🔗 [arstechnica.com](https://arstechnica.com/gadgets/2025/03/italian-court-orders-google-to-block-iptv-pirate-sites-at-dns-level/): Italy demands Google poison DNS under strict Piracy Shield law</small>


| 🔥: 71 \| 💬: [43](https://news.ycombinator.com/item?id=43448112) \| 🗓️ 2025-03-22


<br />
意大利法院命令**谷歌**立即开始污染其公共DNS服务器，以阻止非法足球流媒体网站。这是意大利**Piracy Shield**法律的最新举措，旨在打击盗版，但已引发争议。此前，意大利ISP和其他公司如**Cloudflare**也受到类似要求。尽管此举旨在保护版权，但DNS污染可能导致误封合法内容。

---

## <a name="14"></a>14. 如何打造一个更“无礼”的网络爬虫 
<small>🔗 [marginalia.nu](https://www.marginalia.nu/log/a_115_rude_crawler/): Improved ways to operate a rude crawler</small>


| 🔥: 70 \| 💬: [12](https://news.ycombinator.com/item?id=43445682) \| 🗓️ 2025-03-22


<br />
这篇讽刺性文章调侃了AI初创公司如何通过**无视robots.txt**、**滥用POST请求**和**耗尽服务器资源**来提升爬虫的“无礼”程度。文章建议爬虫应**频繁建立新连接**、**不关闭连接**，甚至**蹭邻居的WiFi**来获取数据。这些“技巧”虽然对服务器极不友好，但作者认为这是向投资者展示公司“创新”的好方法。

---

## <a name="15"></a>15. 保罗·狄拉克与弗里德里希·洪德的访谈（1982年）[视频] 
<small>🔗 [youtube.com](https://www.youtube.com/watch?v=xJzrU38pGWc): Paul A. M. Dirac, Interview by Friedrich Hund (1982) [video]</small>


| 🔥: 65 \| 💬: [14](https://news.ycombinator.com/item?id=43446442) \| 🗓️ 2025-03-22


<br />
在这段1982年的访谈中，**保罗·狄拉克**与物理学家弗里德里希·洪德讨论了**量子力学**的早期发展及其对现代物理学的影响。狄拉克回顾了他对**狄拉克方程**的贡献，并分享了他对科学哲学和未来研究的看法。这段访谈为理解20世纪物理学的重要突破提供了独特的视角。

---

## <a name="16"></a>16. AI的经济价值主要来自广泛自动化，而非研发 
<small>🔗 [epoch.ai](https://epoch.ai/gradient-updates/most-ai-value-will-come-from-broad-automation-not-from-r-d): Most AI value will come from broad automation, not from R&D</small>


| 🔥: 63 \| 💬: [59](https://news.ycombinator.com/item?id=43447616) \| 🗓️ 2025-03-22


<br />
文章反驳了AI经济价值主要来自研发自动化的观点，指出**研发的经济贡献被高估**，且自动化研发的难度远超预期。相反，**广泛自动化劳动力**将带来更大的经济价值，因为劳动力在产出中的弹性远高于研发。尽管研发对生产力增长有贡献，但其占比仅为20%，而资本深化和其他因素占主导。因此，AI的广泛应用将推动经济增长，而非局限于研发领域。

---

## <a name="17"></a>17. NixOS与可重现构建如何检测xz后门 
<small>🔗 [luj.fr](https://luj.fr/blog/how-nixos-could-have-detected-xz.html): NixOS and reproducible builds could have detected the xz backdoor</small>


| 🔥: 52 \| 💬: [12](https://news.ycombinator.com/item?id=43448075) \| 🗓️ 2025-03-22


<br />
2024年3月，xz压缩软件中被发现存在后门，攻击者通过伪装成维护者Jia Tan，逐步插入恶意代码，最终允许远程代码执行。**NixOS**和**可重现构建**技术可以通过对比构建结果，检测出此类恶意修改。文章探讨了后门的工作原理，并建议从可信源构建软件，以减少类似攻击的风险。

---

## <a name="18"></a>18. 马斯克暗中推动关闭美国图书馆机构，引发争议 
<small>🔗 [newrepublic.com](https://newrepublic.com/post/193015/elon-musk-doge-library-musem-imls): Elon Musk's Doge Moves to Gut Local Libraries While No One Is Looking</small>


| 🔥: 49 \| 💬: [8](https://news.ycombinator.com/item?id=43445571) \| 🗓️ 2025-03-22


<br />
据报道，**埃隆·马斯克**领导的**DOGE**部门正秘密关闭美国博物馆与图书馆服务协会（IMLS），该机构负责为全国图书馆和博物馆提供资金支持。IMLS的关闭将影响偏远地区的图书馆技术更新和员工培训。尽管IMLS仅占联邦预算的0.0046%，但其支持的文化机构每年产生500亿美元的经济效益。与此同时，马斯克因其与中国的关系和商业利益，被质疑是否适合参与美国政府的高级军事机密会议。

---

## <a name="19"></a>19. AI广告技术公司CEO因欺诈被判刑，曾承诺“无欺诈世界” 
<small>🔗 [arstechnica.com](https://arstechnica.com/gadgets/2025/03/ceo-of-ai-ad-tech-firm-pledging-world-free-of-fraud-sentenced-for-fraud/): CEO of AI ad-tech firm pledging "world free of fraud" sentenced for fraud</small>


| 🔥: 49 \| 💬: [9](https://news.ycombinator.com/item?id=43448606) \| 🗓️ 2025-03-22


<br />
2024年5月，广告技术公司Kubient的CEO **Paul Roberts**因欺诈罪被判入狱一年零一天。Roberts被指控通过虚假交易和伪造的AI工具报告，制造了**130万美元的虚假收入**，以推动公司IPO。Kubient曾宣称其AI技术能有效防止广告欺诈，但实际并未使用真实数据。公司现已倒闭，Roberts及其团队面临多项指控。

---

## <a name="20"></a>20. 一位母亲战胜Meta，将改变所有人的社交媒体体验 
<small>🔗 [thetimes.com](https://www.thetimes.com/uk/technology-uk/article/facebook-personal-data-opt-out-swg26rm5z): One mother's win over Meta will change social media for everyone</small>


| 🔥: 44 \| 💬: [36](https://news.ycombinator.com/item?id=43445755) \| 🗓️ 2025-03-22


<br />
英国消费者将能够选择退出**定向广告**，这得益于Tanya O’Carroll在与Meta的诉讼中取得的胜利。O’Carroll因无法关闭Facebook的**用户画像**功能而提起诉讼，该功能基于用户活动推断出700多种特征，用于推送广告。她的胜诉将为用户提供更多隐私控制权。

---

## <a name="21"></a>21. 法国发现全球最大氢矿，价值920亿美元 
<small>🔗 [interestingengineering.com](https://interestingengineering.com/energy/france-worlds-largest-hydrogen-deposit): France hits hydrogen jackpot: largest reserve valued $92B found</small>


| 🔥: 42 \| 💬: [3](https://news.ycombinator.com/item?id=43445454) \| 🗓️ 2025-03-22


<br />
法国科学家在摩泽尔地区的Folschviller地下发现了**4600万吨天然氢**，价值约920亿美元。这种**白色氢**无需工业加工，可直接作为清洁能源使用，有望彻底改变全球能源格局。这一发现不仅能为法国创造数千个就业机会，还可能推动全球向清洁能源转型。

---

## <a name="22"></a>22. 媒体对希特勒的误判 
<small>🔗 [theatlantic.com](https://www.theatlantic.com/ideas/archive/2025/03/hitler-press-germany/682130/): What the Press Got Wrong About Hitler</small>


| 🔥: 36 \| 💬: [21](https://news.ycombinator.com/item?id=43446431) \| 🗓️ 2025-03-22


<br />
1931年，美国记者多萝西·汤普森采访了希特勒，认为他“微不足道”，但一年后希特勒成为德国总理。**当时许多记者和政治观察家都低估了希特勒**，认为他滑稽可笑，甚至嘲笑他的名字和背景。然而，希特勒通过**政治策略和媒体操控**，最终掌握了权力。尽管他在早期选举中失败，但他利用保守派媒体的支持，逐步扩大影响力，最终成为独裁者。

---

## <a name="23"></a>23. MacBook占Mac总销量的86%，台式机仅占14% 
<small>🔗 [macdailynews.com](https://macdailynews.com/2025/03/19/macbooks-account-for-86-of-total-mac-sales-mac-desktops-just-14/): MacBooks account for 86% of total Mac sales; Mac desktops just 14%</small>


| 🔥: 33 \| 💬: [67](https://news.ycombinator.com/item?id=43444605) \| 🗓️ 2025-03-22


<br />
根据CIRP的数据，**MacBook**在苹果电脑产品线中占据主导地位，占总销量的**86%**，显示出消费者对便携性的强烈偏好。其中，**MacBook Pro**占53%，**MacBook Air**占33%。相比之下，Mac台式机仅占14%，**iMac**是其中最受欢迎的型号，占10%。这一趋势反映了市场对移动设备的青睐，苹果也因此将更多资源投入到笔记本电脑的研发中。

---
