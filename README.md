# KaiwuDB 开源社区导览

欢迎来到KaiwuDB社区。

KaiwuDB 是浪潮控股的数据库企业，汇聚了全球顶尖的数据库人才，核心产品囊括：KaiwuDB 分布式多模数据库与 KDP 数据服务平台；面向工业物联网、数字能源、车联网、智慧产业等各大行业领域，提供稳定安全、高性能、易运维的创新数据软件与服务，一站式满足 AIoT 等场景下数据管理需求及关键行业核心系统的自主可控需求。

本仓库（Community）包含了关于KaiwuDB社区的社区治理、社区活动、开发者贡献指南、沟通交流指南等信息。

## 社区组织架构

![社区组织架构图](/Figures/Organization_structure.png)


- **Council(社区理事会)**

社区理事会是KaiwuDB开源社区的最高领导和决策机构。 
<br>主要负责：  
①指导社区的发展方向，制定长期发展规划和实施指导意见。  
②审视社区各种委员会工作，给出指导意见。
<br>③制定战略合作，促进社区生态提升社区活力。
<br>详细信息见[社区理事会](Council.md)介绍。

- **Tech committee(技术委员会)**

<br>技术委员会是社区项目的技术管理机构，提供技术指导、决策和监督。拥有技术决策的最终裁决权。<br>主要职责：
<br>①决策社区技术的发展愿景和技术创新，保证社区具有持续的技术竞争力。
<br>②落实社区日常开发工作，保证社区发行版高质量发布。
<br>③决策社区 SIG 的成立、撤销、合并等事务，维护其日常运作。
<br>详细信息见[技术委员会](Tech_committee.md)介绍。

- **User committee(用户委员会)**

用户委员会是社区用户需求沟通机构，主要负责产品宣传以及案例推广等。<br>主要职责：
<br>①收集用户需求，制定发展规划。
<br>②案例整理与品牌推广，提升产品影响力。
<br>③构建社区生态，协同厂商与开发者形成传播合力。
<br>详细信息见[用户委员会](User_committee.md)介绍。

- **SIGs(专项兴趣小组)**

专项兴趣小组（SIG）是针对某个具体的技术方向，由3位及以上成员组成的学习、研究小组。
<br>每个小组负责：
<br>①针对特定的一个或多个主题建立社区项目。
<br>②推动各项目输出交付成果。
<br>详细信息见[专项兴趣小组](SIGs.md)介绍。
## 社区角色
- **Contributor（贡献者）**
<br>Contributor（贡献者）是向开源项目的存储库贡献代码或文档的人。
<br>任何有注册账号，并签署本社区CLA协议成功的用户都可以成为Contributor

- **Committer（提交者）**
<br>Committer（提交者）是始终如一的贡献者（Contributor），通常是项目的主要开发人员，能够修改开源软件特定部分源代码，是项目的带头人之一，被视为社区中值得信赖的成员。与此同时，提交者通常负责审查贡献者（Contributor）提交的补丁，以便将其合并到项目库中。
<br>如何成为[Committer](Tech_committee.md)？

- **Maintaner（维护者）**
<br>Maintaner（维护者）是开源项目的领导者。负责参与构建或发布源代码的最终决策。参与各自领域内进行所有的代码审查，并对项目该领域的方向做出最终决定。以及审查Pull请求和其他贡献、发布新版本的软件、分类和处理安全修复、以及社区管理和审核。
<br>如何成为[Maintaner](Tech_committee.md)？

- **Demand Specialist(需求师)**
<br>负责收集整理用户技术和产品需求
如何成为[需求师](User_committee.md)？
- **Ambassador(社区大使)**
<br>负责开展各种市场营销活动，组织KaiwuDB数据库技术、用户案例、解决方案和社区的宣传活动。作为开源社区和用户的沟通桥梁，负责宣传最新的技术进展，并从用户获取反馈。
如何成为[社区大使](User_committee.md)？
## 如何下载资源
- **文档下载**

community仓库拥有本项目最新的社区文档，docs仓库拥有本项目最新的开发文档，所有用户均可下载。

- **下载代码**

希望阅读代码或更改代码的用户需要进入[KaiwuDB代码仓库](https://gitee.com/kaiwudb-opensource/kaiwudb)
下载相应版本最新代码。

- **编译好的二进制可执行文件下载**

仅希望使用本项目产品的用户可以直接下载社区编译好的二进制可执行文件。
## 如何贡献代码
![贡献流程图](/Figures/Contribute_process.png)

1.[**注册Gitee账号**](https://gitee.com/signup?redirect_to_url=%2F)（如果已有，则忽略此步骤）

2.**下载资源**
<br>资源类型包括文章、文档、源代码、二进制可执行文件。

3.**使用资源**

- 您可以直接使用下载的资源。
- 对于KaiwuDB文章和文档的引用，应当注明来源。对于源代码或文档修改，应当遵守Apache License 2.0的约束。
- 对于二进制文件使用过程中遇到的问题，可以通过Bug提报(bug@openKaiwuDB.com)的方式反馈给社区。

4.**选定SIG**
<br>为了便于社区工作开展和交流，KaiwuDB项目组已设立5个SIG小组，请从已有的SIG小组中选择自己感兴趣的小组。
如果当前还没有您感兴趣的小组，您可以通过发邮件（sigs@openKaiwuDB.com）的方式来申请成立新的兴趣小组，在收到邮件后，我们会第一时间评估讨论。

5.**选择Issue**
<br>从现有的统一的[Issue列表](https://gitee.com/kaiwudb-opensource/issues)中给自己分配Issue任务，在评论区输入/assign即可。

6.**解决Issue**

- 开展编码工作，来解决Issue。
- 如果过程中遇到其它的bug，请参考下面的 **Bug（问题）和需求登记** 。

7.**签署CLA**
<br>若您选择成为贡献者，请签署KaiwuDB社区贡献者许可协议（CLA）。

8.**提交Issue**
<br>在解决完Issue并自测成功之后，您可以Pull Request到相应仓库中，您只需等待审核者审核合并相应提交即可。

9.**审核**
<br>审核者在得知贡献者PR代码后，会对代码进行Review和自动化测试。

10.**Bug检查**
<br>社区组织中的专职人员对上报Bug信息进行审核确认。

11.**贡献完成**
<br>Issue解决并合并到相应仓库中，或者新发现的Bug登记后，贡献流程完成。

详见[贡献流程](Contribute_process.md)

## 如何提报问题与建议
- **Bug（问题）和需求登记**

在阅读文档、代码，修改代码和使用中发现的任何问题或需求，请提交到对应的仓库中，若不确定问题或需求属于那个仓库，可以吧其提交到[community](https://gitee.com/kaiwudb-opensource/community/issues)，感谢您支持，[issues提交指南](https://gitee.com/kaiwudb-opensource/community/blob/master/issues%20Submission%20Guidelines.md)。

- **意见与建议**
若你有任何关于本社区的意见或者建议，可以发送邮件至user@openKaiwuDB.com