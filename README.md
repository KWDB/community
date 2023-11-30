# KaiwuDB 开源社区导览

欢迎来到KaiwuDB社区。

KaiwuDB是浪潮控股的数据库企业，核心产品囊括：KaiwuDB分布式多模数据库与KDP数据服务平台；面向工业物联网、数字能源、车联网、智慧产业等各大行业领域，提供稳定安全、高性能、易运维的创新数据软件与服务，一站式满足AIoT等场景下数据管理需求及关键行业核心系统的自主可控需求。

本仓库（Community）包含了关于KaiwuDB社区组织架构、社区角色、社区贡献、社区公约等相关信息。 


## 社区组织架构

![社区组织架构图](/Figures/Organization_structure.png)


- **Council(社区理事会)**

社区理事会是KaiwuDB开源社区的最高领导和决策机构。 
<br>主要负责：  
①指导社区的发展方向，制定长期发展规划和实施指导意见。  
②审视社区各种委员会工作，给出指导意见。
<br>③制定战略合作，促进社区生态提升社区活力。
<br>详细信息见[社区理事会](Council.md)介绍。

- **Tech Committee(技术委员会)**

技术委员会是社区项目的技术管理机构，提供技术指导、决策和监督。拥有技术决策的最终裁决权。<br>主要职责：
<br>①决策社区技术的发展愿景和技术创新，保证社区具有持续的技术竞争力。
<br>②落实社区日常开发工作，保证社区发行版高质量发布。
<br>③决策社区 SIG 的成立、撤销、合并等事务，维护其日常运作。
<br>详细信息见[技术委员会](Tech_committee.md)介绍。

- **User Committee(用户委员会)**

用户委员会是社区用户需求沟通机构，主要负责产品宣传以及案例推广等。<br>主要职责：
<br>①收集用户需求，制定发展规划。
<br>②案例整理与品牌推广，提升产品影响力。
<br>③构建社区生态，协同厂商与开发者形成传播合力。
<br>详细信息见[用户委员会](User_committee.md)介绍。

- **SIGs(专项兴趣小组)**

专项兴趣小组是针对某个具体的技术方向，由3位及以上成员组成的学习、研究小组。
<br>每个小组负责：
<br>①针对特定的一个或多个主题建立社区项目。
<br>②推动各项目输出交付成果。
<br>详细信息见[专项兴趣小组](SIGs.md)介绍。

## 社区角色
- **Contributor（贡献者）**
<br>Contributor（贡献者）是向开源项目的存储库贡献代码或文档的人。
<br>任何有注册账号，并签署本社区CLA协议成功的用户都可以成为Contributor。

- **Committer（提交者）**
<br>Committer（提交者）是始终如一的贡献者（Contributor），通常是项目的主要开发人员，能够修改开源软件特定部分源代码，是项目的带头人之一，被视为社区中值得信赖的成员。与此同时，提交者通常负责审查贡献者（Contributor）提交的补丁，以便将其合并到项目库中。
<br>如何成为[Committer](Tech_committee.md)？

- **Maintaner（维护者）**
<br>Maintaner（维护者）是开源项目的领导者。负责参与构建或发布源代码的最终决策。参与各自领域内进行所有的代码审查，并对项目该领域的方向做出最终决定。以及审查Pull请求和其他贡献、发布新版本的软件、分类和处理安全修复、以及社区管理和审核。
<br>如何成为[Maintaner](Tech_committee.md)？

- **Demand Specialist(需求师)**
<br>负责收集整理用户技术和产品需求。
<br>如何成为[需求师](User_committee.md)？
- **Ambassador(社区大使)**
<br>负责开展各种市场营销活动，组织KaiwuDB数据库技术、用户案例、解决方案和社区的宣传活动。作为开源社区和用户的沟通桥梁，负责宣传最新的技术进展，并从用户获取反馈。
<br>如何成为[社区大使](User_committee.md)？

## 如何下载资源
- **文档下载**

Community仓库拥有本项目最新的社区文档，[docs仓库](https://gitee.com/kaiwudb-opensource/docs)拥有本项目最新的开发文档，所有用户均可下载。

- **代码下载**

希望阅读代码或更改代码的用户需要进入[KaiwuDB代码仓库](https://gitee.com/kaiwudb-opensource/kaiwudb)
下载相应版本最新代码。

- **编译好的二进制可执行文件下载**

仅希望使用本项目产品的用户可以直接下载社区编译好的二进制可执行文件。

## 如何参与社区贡献
![贡献流程图](/Figures/Contribute_process.png)

1.[**注册Gitee账号**](https://gitee.com/signup?redirect_to_url=%2F)（如果已有，则忽略此步骤）
<br>KaiwuDB源代码托管在Gitee（码云）上，请参考[Gitee官方文章](http://https://gitee.com/help/articles/4113)注册您的Gitee账户类型。

2.**选定SIG**
<br>为促进开源社区工作开展和交流，KaiwuDB设立5个SIG（Special Interest Group）特别兴趣小组。欢迎您才加入并参与贡献，您可以在 SIG 对应的代码仓库上提交 Issue，参与 Issue 讨论，提交 Pull Request，参与代码检视等。如下SIG兴趣列表供你选择：

| SIG                              | 职责                                                        | 联系方式                   |
|----------------------------------|-----------------------------------------------------------|------------------------|
| SQL engine SIG（计算引擎小组）           | 负责KaiwuDB社区SQL计算引擎的开发和维护                                  | sql@kaiwudb.org.cn     |
| Storage engine SIG（存储引擎小组）       | 负责KaiwuDB社区存储引擎的开发和维护                                     | storage@kaiwudb.org.cn |
| AIoT SIG（多模时序技术小组）               | 负责KaiwuDB社区数据库相关AI和IoT技术的开发和维护                            | aiot@kaiwudb.org.cn    |
| Docs SIG（产品文档小组）                 | 负责KaiwuDB社区文档的开发和维护                                       | docs@kaiwudb.org.cn    |
| Release Management SIG（产品发布技术小组） | 负责开源项目管理技术的开发和维护，协调KaiwuDB社区各个SIG maintainer， 规划社区版本的发布工作 | release@kaiwudb.org.cn |

如果未有感兴趣的小组，您可发邮件至sigs@kaiwudb.org.cn，申请成立新兴趣小组。

3.**选择Issue**
<br>从现有的统一的[Issue列表](https://gitee.com/organizations/kaiwudb-opensource/issues)中给自己分配Issue任务，在评论区输入/assign即可。在社区正式更新Issue列表之前，所有人都可为自己分配Issue列表中的任务，即使该 issue 已经有伙伴参与有其他人已经在做了。如果您感兴趣，也可以在评论框中发表自己的意见参与 Issue 讨论。

4.**解决Issue**

- 开展编码工作，来解决Issue。
- 如果过程中遇到其它的Bug，请参考下面的 **Bug和需求登记**提交Bug 。

5.**签署CLA**
<br>若您选择成为贡献者，请签署KaiwuDB社区贡献者许可协议（CLA）。

6.**提交Issue**
<br>在解决完Issue并自测成功之后，您可以Pull Request到相应仓库中，您只需等待审核者审核合并相应提交即可。若您的 Pull Request 没有得到回复，可通过对应 SIG邮件列表求助。

7.**审核**
<br>审核者在得知贡献者PR代码后，会对代码进行Review和自动化测试。测试通过的代码提交请求将予以通过，代码正式合并到代码库，并更新社区Issue列表。审核不通过的PR请求予以退回。贡献者可以按照comment重新修改。

 **至此，所有的贡献流程全部完成。** 详见[贡献流程](Contribute_process.md)

## 如何提报Bug与建议
<br>为营造更加具有活力的生态社区，我们在多环节开放“Bug检查”。所有伙伴在使用社区的任何资源（包括文章、文档、源代码、二进制产品文件等）过程中发现问题，都可提交Bug请求。我们也将设置专员负责Bug信息的审核、确认、修改及回复工作。

- **Bug和需求登记**
在阅读文档、代码，修改代码和使用中发现的任何问题或需求，请提交到对应的仓库中，若不确定问题或需求属于哪个仓库，可以提交到[community](https://gitee.com/kaiwudb-opensource/community/issues)。感谢您支持，详见[issues提交指南](https://gitee.com/kaiwudb-opensource/community/blob/master/issues%20Submission%20Guidelines.md)。

- **意见与建议**
若您有任何关于本社区的意见或者建议，可以发送邮件至user@kaiwudb.org.cn