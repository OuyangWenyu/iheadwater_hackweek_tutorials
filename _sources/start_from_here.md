# 从这里开始

工欲善其事，必先利其器。为了后续我们交流学习的方便，推荐大家注册使用团队平台（以下简称平台）的JupyterHub，通过内网（411教研室和研发中心），使用浏览器就能便捷访问到专属于个人的编程环境.非常方便。如果你是完全是编程小白，那么你就更应该用这个了，其他开启编程的方式对你都只会意味着更高门槛。

但是开始前，你需要能成功访问到内网，如果你有电脑在411教研室或研发中心，那你本地使用它或者远程连接到它就行了，如果没有，那就需要配置下研发中心VPN了，因为这里涉及到内部给的用户名和密码，所以就不在这里公开介绍了，请参考这个文档：https://dlut-water.yuque.com/docs/share/4cab7471-0be7-4570-a51a-8936b1c612d1?# 《研发中心VPN安装说明》，按照文档说明逐步操作。

如果你没有办法访问内网，那就需要要在本地搭建相同的环境，可以跳到[这里](https://github.com/iHeadWater/WaterResources/blob/master/tools/jupyterlab%26markdown.md)查看具体方法，不过目前本教程主要还是使用平台JupyterHub工具来介绍的，如果完全本地搭建会有一些环节衔接不上，但是大部分内容通过网络搜索解决办法，应该都是可以顺利学习的。

平台Jupyterhub注册地址在这里：[源平台JupyterHub内网访问注册](http://jupyterhub.waterism.com:666/hub/signup)，注册的时候请用自己名字全拼，例如欧阳文宇，用户名就用ouyangwenyu，这样方便我们整个平台的管理。如果已经注册过了则直接从[这里](http://jupyterhub.waterism.com:666/)登录，具体使用方法我们后续会介绍，这里注册好，记好自己的用户名密码即可。

接下来，就让我们使用平台提供的工具，看看怎么开启科研编程吧。

待到完成本教程后，我们将能够：

1. 了解可复现科研并学会使用一般工作流中用到的编程相关工具。  
2. 认识我们日常科研经常处理的数据文件
3. 掌握版本控制工具的基本操作方法
4. 熟悉Python最基础语法内容
5. 了解Python数据分析常用包
6. 初识深度学习（水文）
7. 使用深度学习工具Pytorch
8. 复现基于CAMELS数据集和LSTM模型的研究论文

本文的结构和部分内容重点参考了：[Earth Lab的资源](https://www.earthdatascience.org/)，感兴趣的同学可以去看一看他们的优质教程。