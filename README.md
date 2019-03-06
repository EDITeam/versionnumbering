<h4 align="center"><i><b> To Infinity... and Beyond! </b></i></h4>
<p align="center">
  <a href="https://github.com/EDITeam/versionnumbering"><img src="/static/buzz-lightyear.png" width="160" alt="Buzz Lightyear's logo" /></a>
</p>
<h3 align="center"><a href="https://github.com/EDITeam/versionnumbering">Buzz Lightyear</a></h3>

# **Buzz Lightyear** ![progress](http://progressed.io/bar/10?title=done) ![version](https://img.shields.io/badge/version-1.0.1-blue.svg?cacheSeconds=2592000) ![license](https://img.shields.io/badge/license-MIT-green.svg) ![date](https://img.shields.io/date/1550979780.svg)

***Buzz Lightyear*** is our version numbering project's nickname!

# 版本号命名规则与说明

## 1.版本命名规范

版本号由四部分组成，第一部分为主版本号，第二部分为次版本号，第三部分为修订版本号，第四部分为希腊字母版本号。希腊字母版本号共有五种，分别为base、alpha、beta、RC、release。

    如：版本号 1.12.200_beta

    1为主版本号，12为次版本号，200为修订版本号，beta为希腊字母版本号


## 2.软件版本阶段说明

base：此版本表示该版本添加的功能仅仅是一个假面链接，只实现了基本页面，并未对实际操作做完整的实现。

alpha：软件初级版本，未经测试，只是开发人员内部交流使用，以及给到测试人员，即测试版。此版本一般bug较多。

beta：经内部测试人员测试并对bug进行了修改之后，可以供客户进行测试使用的版本，此版本之后一般不会进行大变动。

release：发行版。此版本基本是一家客户的最后一个beta版，此版本之后基本不会有变动，同时也是给其他有意向客户演示的版本。


## 3.版本号修改规则

### （1）主版本号：

当框架更新更换或平台发生重大变化时变化。

    比如：当前BFIRE前端框架为angular，未来使用vue，即以2.00.000为起始版本。

### （2）次版本号：

当模块功能有重大更新时发生变化。

    比如：当前BFIRE版本为1.01.018，即只有库存模块功能，当增加了现场服务模块功能后，应以1.02.000为起始版本。

### （3）修订版本号：

当对功能内页面、事件的实现，bug的修复或其他比较小的更新时变化。

    比如：当前BFIRE版本为1.02.000，新增了库存任务汇报同步功能，则更新版本号为1.02.001。
    
    *注：修订版本号的更新一般不会只增加1，若次版本较上一版本添加了更新、删除、同步功能，则直接为1.02.003。

    注：1.02.00版本功能为模版生成的初始化功能。

### （4）希腊字母版本号：

此版本主要标注当前app、服务处于哪个阶段，根据实际阶段修改为对应版本号。一般流程为：base（初始化版）、alpha（实现与测试版）、beta（稳定版）、release（最终发布版）。


## 完整版本号修改举例说明

当前BRIRE版本号应为1.01.020_release，当通过脚本或其他技术生成现场服务模块（签到、任务汇报、报销三个功能）初始化代码后，版本应为1.02.000_base。
    
当签到功能实现了具体事件后，版本应为1.02.001_alpha，并交予测试人员及产品经理进行测试。
    
测试并对测试问题进行相应修改后确认无重大bug且满足当前需求后，修改版本号为1.02.001_beta，并交予客户进行测试。

在项目交付前最后一次发布时，版本号应为1.02.034_release。

当版本号为1.02.004_alpha时，客户提出需求需增加客户评价功能，通过脚本或其他技术生成客户评价功能初始化代码后，版本号应为1.02.005_base。

## *注意事项

版本号上一级增加时，下级要归0。
希腊字母版本号以低级为主。
    如：下一版本同时是某功能的稳定版且是某一功能base版，则希腊字母版本号为base。

# ***Vote***

[![](https://api.gh-polls.com/poll/01D4EXW6HB0307XQTJSPRTH1W3/Agree)](https://api.gh-polls.com/poll/01D4EXW6HB0307XQTJSPRTH1W3/Agree/vote)
[![](https://api.gh-polls.com/poll/01D4EXW6HB0307XQTJSPRTH1W3/Disagree)](https://api.gh-polls.com/poll/01D4EXW6HB0307XQTJSPRTH1W3/Disagree/vote)
[![](https://api.gh-polls.com/poll/01D4EXW6HB0307XQTJSPRTH1W3/I%20have%20other%20proposals)](https://api.gh-polls.com/poll/01D4EXW6HB0307XQTJSPRTH1W3/I%20have%20other%20proposals/vote)

# ***Contributors***
<a href="https://github.com/EDITeam/versionnumbering/graphs/contributors">
  <img src="https://avatars2.githubusercontent.com/u/16353458?s=400&v=4" width="70" alt="Harold.Duan" />
  <img src="https://avatars3.githubusercontent.com/u/4202696?s=400&v=4" width="70" alt="Pancy.Fan" />
  <img src="https://avatars2.githubusercontent.com/u/28555389?s=400&v=4" width="70" alt="Aaton.Kang" />
  <img src="https://avatars1.githubusercontent.com/u/45222954?s=400&v=4" width="70" alt="Shuo.Liu" /></a>
</a>

# ***Thanks***
<h3 align="left">
  <a href="https://github.com/EDITeam">EDITeam</a>
</h3>