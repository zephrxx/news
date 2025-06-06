---
layout: page
title: 勒西科技日报 - 2025年06月06日
date: 2025-06-06 00:00:00
categories: 新闻
tags:
  - hacker_news
---


1. 立即关闭侵入性AI发现流；
1. 如何将GitLab仓库备份时间从48小时缩短至41分钟；
1. Jepsen测试报告：TigerBeetle 0.16.11；
1. Dystopian tales of that time when I sold out to Google；
1. Infomaniak公开支持瑞士争议性加密法案；

以上是今天的前五条黑科技新闻标题。

总共6条，具体内容您往下读...


<iframe src="/signup.html" width="100%" height="270" frameborder="0"></iframe>
![](/assets/images/hacker_news.jpg)


## <a name="1"></a>1. 立即关闭侵入性AI发现流 
<small>🔗 [mozillafoundation.org](https://www.mozillafoundation.org/en/campaigns/meta-shut-down-your-invasive-ai-discover-feed-now/): Meta: Shut down your invasive AI Discover feed</small>


| 🔥🔥: 383 \| 💬: [169](https://news.ycombinator.com/item?id=44201872) \| 🗓️ 2025-06-06


<br />
Mozilla指控Meta正将用户的**私密AI聊天**悄然转化为**公开内容**，且多数用户毫不知情。该组织要求Meta：立即关闭Discover信息流直至建立有效隐私保护；默认所有AI互动为私密状态，未经明确**知情同意**不得公开；公布受影响用户数量；建立全平台一键退出AI训练机制；主动通知内容遭公开的用户并提供永久删除选项。Mozilla强调用户应享有知情权，呼吁公众联署要求Meta停止侵犯隐私行为。

（字数：179）

---

## <a name="2"></a>2. 如何将GitLab仓库备份时间从48小时缩短至41分钟 
<small>🔗 [about.gitlab.com](https://about.gitlab.com/blog/2025/06/05/how-we-decreased-gitlab-repo-backup-times-from-48-hours-to-41-minutes/): How we decreased GitLab repo backup times from 48 hours to 41 minutes</small>


| 🔥🔥: 236 \| 💬: [98](https://news.ycombinator.com/item?id=44201975) \| 🗓️ 2025-06-06


<br />
GitLab团队通过优化核心Git功能，将大型仓库备份时间从48小时大幅缩减至41分钟。根源在于`git bundle create`命令中一个存在15年的**O(N²)复杂度函数**`object_array_remove_duplicates()`——该函数通过嵌套循环去重引用，在百万级引用的仓库中引发指数级性能衰退。团队贡献上游修复方案，采用**映射数据结构**替代嵌套循环，使10万引用仓库的打包速度提升6倍。此优化带来三大核心价值：备份耗时降至原1.4%，服务器负载显著降低，且彻底解决备份时长与仓库扩容的矛盾。企业现可实现高频无损备份，灾难恢复点目标（RPO）从"天"缩至"分钟"级，同时降低云环境运算成本。该补丁已并入GitLab 18.0及以上版本，无需额外配置即可生效。

---

## <a name="3"></a>3. Jepsen测试报告：TigerBeetle 0.16.11 
<small>🔗 [jepsen.io](https://jepsen.io/analyses/tigerbeetle-0.16.11): Jepsen: TigerBeetle 0.16.11</small>


| 🔥🔥: 207 \| 💬: [63](https://news.ycombinator.com/item?id=44199592) \| 🗓️ 2025-06-06


<br />
TigerBeetle是一款专为**双入口会计**设计的OLTP数据库，强调安全性与高性能。它基于**Viewstamped Replication共识协议**实现强序列化一致性，采用固定模式存储账户和转账记录，适用于金融交易等高吞吐场景。其核心架构为单节点纵向扩展（非横向），通过批处理、IO并行及硬件优化提升单核性能。

该数据库特别注重容错性，明确建模内存、进程、时钟、存储和网络故障，结合校验和与多副本写入确保数据安全。其独特升级机制允许单二进制文件包含多版本代码，集群可自动协调滚动更新，避免状态分歧。时间模型融合物理时钟与逻辑顺序，要求节点间时钟同步以维持严格单调性。

数据模型仅支持账户与转账两种类型，字段固定且大多不可变。操作以原子请求为单位执行，支持链式事件实现子事务原子性。Jepsen测试验证了其在故障注入下的安全性，通过时间戳顺序与语义分析检查强序列化承诺，覆盖版本0.16.11至0.16.30。

---

## <a name="4"></a>4. Dystopian tales of that time when I sold out to Google 
<small>🔗 [wordsmith.social](https://wordsmith.social/elilla/deep-in-mordor-where-the-shadows-lie-dystopian-stories-of-my-time-as-a-googler): Dystopian tales of that time when I sold out to Google</small>


| 🔥🔥: 191 \| 💬: [167](https://news.ycombinator.com/item?id=44200773) \| 🗓️ 2025-06-06


<br />
好的，这是根据要求撰写的中文摘要：

**向谷歌“卖身”的黑色记忆**

作者回顾了2007年作为软件工程师加入谷歌巴西的经历，揭露了理想与现实间的巨大鸿沟。满怀期待加入这个标榜“不作恶”、拥有“**20%自由时间**”等诱人福利的“最佳雇主”，却发现工作枯燥（修复内部系统漏洞）、薪酬低于当地市场、承诺的“20%时间”形同虚设（95%员工无法使用）。当作者在内部博客指出“20%时间”的虚假性后，遭到经理训斥，并被灌输“激进透明不等于可以说负面”的理念，深感公司营造**强制幸福**的氛围如同反乌托邦小说。

文章还描述了公司内部森严的等级制度：核心工程师（“Googler”）享有声誉，而大量“临时工、兼职工和合同工”被视为**二等阶层**，信息访问受限（作者因开发一个内部术语查询IRC机器人被指责“泄密”）。作者作为“Gaygler™”，其酷儿身份被广告部门利用以获取社群用语用于广告精准投放，个人简介中提及性取向也成为绩效评估的“罪状”。尽管工作环境光鲜，但高压、低薪（依赖“移民北美”的胡萝卜诱惑）和幻灭感最终使作者认清了谷歌作为监控广告巨头的本质。

---

## <a name="5"></a>5. Infomaniak公开支持瑞士争议性加密法案 
<small>🔗 [tomsguide.com](https://www.tomsguide.com/computing/vpns/infomaniak-breaks-rank-and-comes-out-in-support-of-controversial-swiss-encryption-law): Infomaniak comes out in support of controversial Swiss encryption law</small>


| 🔥🔥: 181 \| 💬: [95](https://news.ycombinator.com/item?id=44199377) \| 🗓️ 2025-06-06


<br />
瑞士云服务商**Infomaniak**打破行业共识，公开表态支持该国极具争议的加密法案。该法案要求科技公司协助政府监控加密通信，可能强制服务商**解密用户数据**或安装后门程序。此举引发隐私倡导者强烈反对，尤其担忧法案对**VPN服务**的深远影响——或迫使VPN提供商削弱加密强度，危及用户数据安全与数字权利。

---

## <a name="6"></a>6. 捷克政府门户网站用户满意度调查 
<small>🔗 [portal.gov.cz](https://portal.gov.cz/e-petice/1205-petice-za-povinne-zverejneni-zdrojovych-kodu-softwaru-pouzitych-ve-verejne-sprave): Czech Republic: Petition for open source in public administration</small>


| 🔥🔥: 177 \| 💬: [26](https://news.ycombinator.com/item?id=44199299) \| 🗓️ 2025-06-06


<br />
该文本实为捷克公共行政门户网站的用户满意度调查问卷，包含五个核心部分：用户**知晓该门户的渠道**（电视/互联网/亲友推荐等）；访问目的（查询政务服务或好奇浏览）；对网站**视觉设计、信息清晰度、实用性**等属性的1-5级评分；**使用频率**（每日/每周/每月）；以及未来使用意向（是/否及原因）。问卷结尾提供提交、暂存或关闭选项。全文未涉及开源请愿内容，聚焦于门户网站用户体验评估。

---

### 关键说明：
1. **标题调整**：原标题提及开源请愿，但正文实为满意度调查，故标题按实际内容重拟
2. **核心聚焦**：加粗呈现三项核心调查维度（知晓渠道、关键评估项、使用频率）
3. **字符控制**：严格限定在250字内（中文字符）
4. **结构优化**：采用自然段落整合问卷模块，避免列表格式

---
