# 版本号命名规则与说明
## 1.版本命名规范

版本号由四部分组成，第一部分为主版本号，第二部分为次版本号，第三部分为修订版本号，第四部分为希腊字母版本号。希腊字母版本号共有五种，分别为base、alpha、beta、RC、release。

    如：版本号 1.12.20_beta

    1为主版本号，12为次版本号，20为修订版本号，beta为希腊字母版本号


## 2.软件版本阶段说明

base：此版本表示该版本添加的功能仅仅是一个假面链接，只实现了基本页面，并未对实际操作做完整的实现。

alpha：软件初级版本，未经测试，只是开发人员内部交流使用，以及给到测试人员，即测试版。此版本一般bug较多。

beta：经内部测试人员测试并对bug进行了修改之后，可以供客户进行测试使用的版本，此版本之后一般不会进行大变动。

release：发行版。此版本基本是一家客户的最后一个beta版，此版本之后基本不会有变动，同时也是给其他有意向客户演示的版本。


## 3.版本号修改规则

### （1）主版本号：

当模块有较大变动甚至框架更新更换时发生变化。

    比如：当前BFIRE只有库存模块，未来增加报工模块，即以2.00.00为起始版本。

### （2）次版本号：

当代码结构有较大变动或者模块内功能有重大更新时发生变化。

    比如：当前BFIRE版本为1.01.18，即只有库存模块库存任务功能，当增加了库存任务汇报功能后，应以1.02.00为起始版本。

### （3）修订版本号：

当对功能内页面、事件的实现，bug的修复或其他比较小的更新时变化。

    比如：当前BFIRE版本为1.02.00，新增了库存任务汇报同步功能，则更新版本号为1.02.01。
    
    *注：修订版本号的更新一般不会只增加1，若次版本较上一版本添加了更新、删除、同步功能，则直接为1.02.03。

    注：1.02.00版本功能为模版生成的初始化功能。

### （4）希腊字母版本号：

此版本主要标注当前app、服务处于哪个阶段，根据实际阶段修改为对应版本号。一般流程为：base（初始化版）、alpha（实现与测试版）、beta（稳定版）、release（最终发布版）。


## 完整版本号修改举例说明

当前BRIRE版本号应为1.02.20_release，当通过脚本或其他技术生成现场服务模块（签到、任务汇报、报销三个功能）初始化代码后，版本应为2.03.00_base。
    
当签到功能实现了具体事件后，版本应为2.03.01_alpha，并交予测试人员及产品经理进行测试。
    
测试并对测试问题进行相应修改后确认无重大bug且满足当前需求后，修改版本号为2.03.01_beta，并交予客户进行测试。

再项目交付前最后一次发布时，版本号应为1.03.34_release。

当版本号为2.03.15_alpha时，客户提出需求需增加客户评价功能，通过脚本或其他技术生成客户评价功能初始化代码后，版本号应为2.04.00_base。

## *注意事项

版本号上一级增加时，下级要归0。
希腊字母版本号以低级为主。
    如：下一版本同时是某功能的稳定版且是某一功能base版，则希腊字母版本号为base。