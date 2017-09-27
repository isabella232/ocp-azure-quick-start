# 开发运维一体化和持续集成

持续集成（Continuous integration，缩写为 CI），一种软件工程流程，将所有工程师对于软件的工作复本，每天集成数次到共用主线上。持续集成目的在产生以下效益如下：
+ 及早发现集成错误且由于修订的内容较小所以易于追踪，这可以节省项目的时间与成本。
+ 避免发布日期的前一分钟发生混乱，当每个人都会尝试为他们所造成的那一点点不兼容的版本做检查。
+ 当单元测试失败或发生错误，若开发人员需要在不除错的情况下还原代码库到一个没有问题的状态，只需要放弃一小部分的更改 (因为集成的次数频繁)。
+ 让 "最新" 的程序可保持可用的状态供测试、展示或发布用。
+ 频繁的提交代码会促使开发人员创建模块化，低复杂性的代码。

Team Foundation Server 支持持续集成能力，开发人员可以通过TFS 或者其SaaS版本Visual Studio Online 实现持续集成过程。内容主要包括：
+ 微软DevOps解决方案介绍幻灯片
+ 实验手册
+ 用于实验的样例项目 PartsUnlimited-master.zip