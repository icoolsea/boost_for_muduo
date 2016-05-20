* 简介
  : 


陈硕的网络库muduo依赖了boost，有些环境部署安装全量boost不大方便，故而用boost自带的bcp工具抽取了一个muduo依赖的子集，方便使用。

* boost使用boost_1_55_0（boost_1_56_0和boost_1_60_0都有问题，不能正常生成bootstrap.sh，需要手动copy boost到系统目录）
* 初步使用muduo v1.0.4和v1.0.8版本做了验证
