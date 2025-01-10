---
layout: page
title: 勒西科技日报 - 2025年01月08日
date: 2025-01-08 14:09:54
categories: 新闻
tags:
  - hacker_news
---


1. 在云端以不到8美元的成本破解512位DKIM密钥；
1. Fidget：大规模数学表达式的表示、编译与评估库；
1. NeuralSVG：基于隐式神经表示的文本到矢量图形生成；
1. 我不得不撤下我的课程交换网站，否则将被开除；
1. Facebook 正在删除有关色情广告的报道；

以上是今天的前五条黑科技新闻标题。

总共20条，具体内容您往下读...


![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 在云端以不到8美元的成本破解512位DKIM密钥 
<small>🔗 [dmarcchecker.app](https://dmarcchecker.app/articles/crack-512-bit-dkim-rsa-key): Cracking a 512-bit DKIM key for less than $8 in the cloud</small>


|🔥: 570 \| 💬: [↗](https://news.ycombinator.com/item?id=42633501) \| 🗓️ 2025-01-08


<br />
在对全球前100万网站的SPF、DKIM和DMARC记录进行研究时，发现超过1,700个DKIM密钥长度不足1,024位，这些密钥已被认为不安全。研究人员使用**CADO-NFS**工具在云端服务器上成功分解了一个512位RSA公钥，并生成了对应的私钥。尽管大多数邮件提供商拒绝了该密钥签名的邮件，但**Yahoo Mail**、**Mailfence**和**Tuta**仍通过了验证。研究强调，应避免使用512或768位密钥，邮件提供商应自动拒绝此类签名。

---

## <a name="2"></a>2. Fidget：大规模数学表达式的表示、编译与评估库 
<small>🔗 [mattkeeter.com](https://www.mattkeeter.com/projects/fidget/): Fidget</small>


|🔥: 356 \| 💬: [↗](https://news.ycombinator.com/item?id=42634624) \| 🗓️ 2025-01-08


<br />
Fidget 是一个用于表示、编译和评估大规模数学表达式（如数百或数千个算术子句）的库，主要设计为**隐式曲面**的后端。隐式曲面通过表达式 $f(x, y, z) \rightarrow d$ 表示，Fidget 支持**并行评估**和**构造实体几何（CSG）**操作。库采用 Rust 编写，支持 WebAssembly 编译，并通过**区间算术**和**表达式简化**优化性能，适用于 3D 渲染和 GPU 计算等场景。

---

## <a name="3"></a>3. NeuralSVG：基于隐式神经表示的文本到矢量图形生成 
<small>🔗 [sagipolaczek.github.io](https://sagipolaczek.github.io/NeuralSVG/): NeuralSVG: An Implicit Representation for Text-to-Vector Generation</small>


|🔥: 351 \| 💬: [↗](https://news.ycombinator.com/item?id=42636873) \| 🗓️ 2025-01-08


<br />
矢量图形在设计领域至关重要，提供分辨率无关且高度可编辑的视觉内容。现有方法常因**过度参数化**或忽视**分层结构**而受限。本文提出**NeuralSVG**，利用隐式神经表示生成矢量图形，通过Score Distillation Sampling优化，并引入dropout正则化增强分层结构。NeuralSVG支持推理时动态调整，生成灵活且结构化的SVG，优于现有方法。

---

## <a name="4"></a>4. 我不得不撤下我的课程交换网站，否则将被开除 
<small>🔗 [linkedin.com](https://www.linkedin.com/posts/jdkaim_github-jdkaimhuskyswap-huskyswap-project-activity-7282609173316415488-1jdb): I had to take down my course-swapping site or be expelled</small>


|🔥: 335 \| 💬: [↗](https://news.ycombinator.com/item?id=42638626) \| 🗓️ 2025-01-08


<br />
JD Kaim 是华盛顿大学计算机科学专业的学生，他开发了一个名为 **HuskySwap** 的应用程序，帮助学生交换已满的课程名额。该项目最初是作为课程作业开发的，但后来他试图与学校的注册系统集成以自动化课程数据导入。然而，学校以违反**注册篡改滥用政策**为由，威胁要开除他，并要求他撤下网站。尽管他感到失望，但他计划毕业后继续从事其他项目。

---

## <a name="5"></a>5. Facebook 正在删除有关色情广告的报道 
<small>🔗 [404media.co](https://www.404media.co/facebook-is-censoring-404-media-stories-about-facebooks-censorship/): Facebook is removing stories about pornographic ads</small>


|🔥: 224 \| 💬: [↗](https://news.ycombinator.com/item?id=42637267) \| 🗓️ 2025-01-08


<br />
近期，有用户举报在 Instagram Reels 上出现**露骨的色情广告**，广告内容为女性生殖器的特写图片，点击后跳转至“保密约会”或“本地约会”网站。尽管 Facebook 已开始删除部分广告，但大多数仍未被检测到。这表明 Facebook 在**广告审核**方面存在严重问题，甚至违反了自己的政策。

---

## <a name="6"></a>6. 再见Windows游戏？SteamOS正式扩展至Steam Deck之外 
<small>🔗 [arstechnica.com](https://arstechnica.com/gaming/2025/01/bye-bye-windows-gaming-steamos-officially-expands-past-the-steam-deck/): Bye-bye Windows gaming? SteamOS officially expands past the Steam Deck</small>


|🔥: 210 \| 💬: [↗](https://news.ycombinator.com/item?id=42633269) \| 🗓️ 2025-01-08


<br />
Lenovo宣布推出首款预装**SteamOS**的Legion Go S掌机，标志着**SteamOS**正式进入非Valve设备。该设备将提供Windows和SteamOS两个版本，后者起价500美元，比Windows版便宜。Valve还计划发布**SteamOS**测试版，支持更多设备，未来可能对Windows游戏市场构成挑战。

---

## <a name="7"></a>7. 老去的程序员 
<small>🔗 [youtube.com](https://www.youtube.com/watch?v=mVWQQeSOD0M): The Aging Programmer</small>


|🔥: 206 \| 💬: [↗](https://news.ycombinator.com/item?id=42632772) \| 🗓️ 2025-01-08


<br />
本文探讨了程序员在职业生涯中面临的**年龄挑战**，尤其是在技术快速变化的行业中。随着年龄增长，程序员可能面临**技能过时**和**职业发展瓶颈**的问题。文章还提到了一些应对策略，如持续学习和适应新技术，以保持竞争力。

---

## <a name="8"></a>8. 将SerenityOS移植到真实硬件，一步步编写驱动程序 
<small>🔗 [sdomi.pl](https://sdomi.pl/weblog/23-serenityos-realhw/): Bringing SerenityOS to real hardware, one driver at a time</small>


|🔥: 184 \| 💬: [↗](https://news.ycombinator.com/item?id=42636086) \| 🗓️ 2025-01-08


<br />
作者决定将**SerenityOS**移植到真实硬件，而非仅依赖QEMU模拟器。他选择了一台便宜的Chromebook（Dell 3100），并尝试通过**Cr50**调试芯片进行调试，但遇到了硬件限制。最终，他通过**UART**和**SPI**接口成功实现了调试功能，并编写了相关工具。这一过程展示了如何克服硬件限制，逐步将操作系统移植到真实设备上。

---

## <a name="9"></a>9. 密歇根大学机器人101：应用数值线性代数作为入门线性代数 
<small>🔗 [robotics.umich.edu](https://robotics.umich.edu/academics/courses/course-offerings/rob101-fall-2020/): Robotics 101 at UMich: Applied numerical linear algebra as intro linear algebra</small>


|🔥: 183 \| 💬: [↗](https://news.ycombinator.com/item?id=42633805) \| 🗓️ 2025-01-08


<br />
ROB 101是密歇根大学为**大一新生**设计的**计算线性代数**课程，结合数学理论与编程实践，重点讲解线性方程组、矩阵、回归等核心概念，并通过**Julia编程语言**实现。课程采用混合教学模式，强调工程中的数学应用，适合无编程或线性代数基础的学生。

---

## <a name="10"></a>10. Salesforce 2025年将不再招聘软件工程师，Marc Benioff表示 
<small>🔗 [salesforceben.com](https://www.salesforceben.com/salesforce-will-hire-no-more-software-engineers-in-2025-says-marc-benioff/): Salesforce will hire no more software engineers in 2025, says Marc Benioff</small>


|🔥: 171 \| 💬: [↗](https://news.ycombinator.com/item?id=42639417) \| 🗓️ 2025-01-08


<br />
Salesforce CEO Marc Benioff透露，由于**AI技术**带来的**30%生产力提升**，公司将在2025年停止招聘软件工程师。他表示，**Agentforce**（公司旗舰AI产品）已成为核心，未来将减少支持工程师，增加销售人员以推广AI价值。尽管公司规模可能扩大，但员工对裁员仍感担忧。

---

## <a name="11"></a>11. 洛杉矶野火迫使数千人撤离，NASA JPL关闭 
<small>🔗 [theregister.com](https://www.theregister.com/2025/01/08/los_angeles_fires_jpl/): LA wildfires force thousands to evacuate, NASA JPL closed</small>


|🔥: 170 \| 💬: [↗](https://news.ycombinator.com/item?id=42638735) \| 🗓️ 2025-01-08


<br />
洛杉矶县多起大规模野火失控，**7万人被迫撤离**，**40万人断电**，水压不足导致灭火困难。加州州长宣布进入紧急状态，**NASA喷气推进实验室（JPL）紧急关闭**，部分员工家园被毁。NASA已制定备用计划，将火星探测器控制权转移至戈德斯通深空网络。

---

## <a name="12"></a>12. 一些编程语言的想法 
<small>🔗 [jerf.org](https://jerf.org/iri/post/2025/programming_language_ideas/): Some Programming Language Ideas</small>


|🔥: 99 \| 💬: [↗](https://news.ycombinator.com/item?id=42637304) \| 🗓️ 2025-01-08


<br />
作者认为编程语言的发展似乎停滞不前，主要是对现有概念的重新组合，而非创新。他提出了一些未完全成形的想法，包括**松散函数调用**、**能力系统**、**生产级发布支持**和**半动态语言**。这些想法旨在解决现有语言中的一些问题，如函数调用的可靠性、权限管理、生产环境支持以及动态语言的性能优化。作者希望这些想法能激发更多讨论和创新。

---

## <a name="13"></a>13. 在Rust中嵌入Scheme 
<small>🔗 [raviqqe.com](https://raviqqe.com/doc/posts/stak/embedding-scheme-in-rust/): Embedding Scheme in Rust</small>


|🔥: 91 \| 💬: [↗](https://news.ycombinator.com/item?id=42632592) \| 🗓️ 2025-01-08


<br />
本文介绍了如何在**Rust**中嵌入**Stak Scheme**解释器，以实现动态修改程序行为的功能。通过将Scheme脚本嵌入Rust编写的HTTP服务器，展示了如何在不停止进程的情况下动态更新服务器逻辑。文章详细说明了如何初始化项目、添加依赖、编写Scheme脚本，并利用**热模块重载**功能实现实时更新。Scheme的简洁性和Rust的性能结合，为动态编程提供了强大工具。

---

## <a name="14"></a>14. 山地自行车导致的脊髓损伤超过冰球及其他高风险运动 
<small>🔗 [med.ubc.ca](https://www.med.ubc.ca/news/spinal-cord-injuries-from-mountain-biking-exceed-hockey-other-high-risk-sports/): Spinal cord injuries from mountain biking exceed hockey, other high-risk sports</small>


|🔥: 87 \| 💬: [↗](https://news.ycombinator.com/item?id=42632878) \| 🗓️ 2025-01-08


<br />
研究表明，**山地自行车**运动引发的**脊髓损伤**比例已超过冰球等其他高风险运动。这一发现强调了山地自行车运动中的潜在危险，提醒参与者需加强安全防护措施。

---

## <a name="15"></a>15. Ubuntu Linux 的领军人物 Steve Langasek 去世 
<small>🔗 [thenewstack.io](https://thenewstack.io/steve-langasek-one-of-ubuntu-linuxs-leading-lights-has-died/): Steve Langasek, One of Ubuntu Linux's Leading Lights, Has Died</small>


|🔥: 79 \| 💬: [↗](https://news.ycombinator.com/item?id=42639563) \| 🗓️ 2025-01-08


<br />
Steve Langasek，**Ubuntu Linux** 社区的重要贡献者之一，已不幸去世。他是开源社区的**核心人物**，为 Linux 发行版的开发和维护做出了巨大贡献。他的离世对全球开发者社区是一个重大损失。

---

## <a name="16"></a>16. Stack Overflow 新问题数量较 2022 年下降 77% 
<small>🔗 [gist.github.com](https://gist.github.com/hopeseekr/f522e380e35745bd5bdc3269a9f0b132): New questions on Stack Overflow are down 77% compared to 2022</small>


|🔥: 67 \| 💬: [↗](https://news.ycombinator.com/item?id=42633880) \| 🗓️ 2025-01-08


<br />
Stack Overflow 的新问题数量自 2023 年 3 月以来持续下降，从 **87,105** 降至 2024 年 12 月的 **25,566**，降幅达 **70.7%**。高贡献用户反映问题被迅速关闭，导致参与度下降。自 ChatGPT 推出后，问题数量减少了 **76.5%**，平台面临严重衰退。

---

## <a name="17"></a>17. 巴沙撒的时钟：夜光漆夜钟 
<small>🔗 [blog.karliner.net](https://blog.karliner.net/projects/belshazzars-clock/): Show HN: Belshazzar's Clock, luminous paint night clock</small>


|🔥: 59 \| 💬: [↗](https://news.ycombinator.com/item?id=42633035) \| 🗓️ 2025-01-08


<br />
作者多年来研究使用**夜光漆**和**紫外线LED**制作光栅或矢量显示的项目，最终设计出一款适合家庭环境的夜光时钟。时钟采用100mm直径的管道，涂有夜光漆，由28BYJ-48步进电机驱动。电子部分使用ESP32C3开发板控制步进电机和紫外线LED链，软件基于Micropython。作者还分享了制作过程中遇到的硬件问题，并提供了开源设计文件。

---

## <a name="18"></a>18. Linux 路由基础 
<small>🔗 [blog.sdn.clinic](https://blog.sdn.clinic/2025/01/linux-routing-fundamentals/): Linux Routing Fundamentals</small>


|🔥: 51 \| 💬: [↗](https://news.ycombinator.com/item?id=42632671) \| 🗓️ 2025-01-08


<br />
Linux 系统默认支持多种路由表，包括 **local**、**main** 和 **default** 表，并通过 **最长前缀匹配** 决定数据包的路由路径。路由表包含目标前缀、接口和下一跳信息。Linux 还支持 **策略路由** 和 **ICMP 错误处理**，并通过 `iproute2` 工具管理路由表。默认情况下，路由表按优先级顺序评估，确保本地流量优先处理。

---

## <a name="19"></a>19. 乘性无穷小 
<small>🔗 [github.com](https://github.com/Ericson2314/baccumulation/blob/main/math/multiplicative-infinitesimals.md): Multiplicative Infinitesimals</small>


|🔥: 50 \| 💬: [↗](https://news.ycombinator.com/item?id=42637853) \| 🗓️ 2025-01-08


<br />
本文探讨了**乘性无穷小**的概念，与传统**加性无穷小**不同，乘性无穷小接近于**1**而非**0**。通过引入**q**符号，作者定义了乘性无穷小在几何微积分中的应用，特别是与**弹性**和**几何导数**相关的公式。文章还指出，非标准分析中的**halo**概念可能已涵盖此类无穷小。

---

## <a name="20"></a>20. 白宫推出消费者设备网络安全信任标志计划 
<small>🔗 [nextgov.com](https://www.nextgov.com/cybersecurity/2025/01/white-house-unveils-cyber-trust-mark-program-consumer-devices/401991/): White House unveils Cyber Trust Mark program for consumer devices</small>


|🔥: 48 \| 💬: [↗](https://news.ycombinator.com/item?id=42636675) \| 🗓️ 2025-01-08


<br />
白宫推出了一项针对物联网设备的**网络安全信任标志**计划，旨在帮助消费者选择更安全的产品。该标志类似于能源之星标签，表明设备符合政府制定的网络安全标准。**UL Solutions**被选为项目主要管理者，亚马逊和百思买等大公司将协助推广。联邦政府计划在2027年前采购带有该标志的设备，以推动市场更安全。

---
