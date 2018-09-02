# Magisk-Modules-Repo-CN

> Magisk-Modules-Repo-CN 对 [Magisk-Modules-Repo](https://github.com/Magisk-Modules-Repo) 中的模块进行汉化

欢迎任何想要作出贡献的人加入 Magisk-Modules-Repo-CN!

## 格式
这个列表以 模块名称(中文译名) [汉化状态] @译者 的方式呈现

#### 注意
- 正在汉化的模块请放到列表顶部
- 如果修正翻译，请保留原汉化者的信息

### 示例
#### 已经汉化完成的模块
[ViPER4Android-FX(蝰蛇音效)](https://github.com/Magisk-Modules-Repo-CN/ViPER4Android-FX) [已完成] @cjybyjk

#### 还未汉化完成的模块
[Greenify4Magisk(绿色守护 Magisk 模块)](https://github.com/Magisk-Modules-Repo-CN/Greenify4Magisk) [汉化中] @cjybyjk

## 不是模块
以下几个 repository 不是标准的模块, 但也非常重要。
希望有更多人加入到这几个 repository 的汉化中
- [Magisk Manager(CN) 中的 docs](https://github.com/Magisk-Modules-Repo-CN/Magisk/tree/master/docs) [等待汉化]
- [Magisk_Repo_Submissions(用于提交 Magisk 模块到仓库)](https://github.com/Magisk-Modules-Repo-CN/Magisk_Repo_Submissions) [汉化中] @cjybyjk
- [magisk-module-template(Magisk 模块编写示例)](https://github.com/Magisk-Modules-Repo-CN/magisk-module-template) [已完成] @cjybyjk

## 上传官方仓库中没有的模块
#### 注意
- repo 的 description 必须设置为模块 id

其余步骤与贡献翻译基本相同，除了以下几点
- 汉化状态 应该设置为 自制模块
- 必须保持使用[最新的 template](https://github.com/Magisk-Modules-Repo-CN/magisk-module-template)

*** 当 [Magisk_Repo_Submissions](https://github.com/Magisk-Modules-Repo-CN/Magisk_Repo_Submissions) 汉化完成后会更新这一小节

## 如何贡献翻译
#### 注意
- 部分格式遵循这个规范：[写给大家看的中文排版指南](http://zhuanlan.zhihu.com/p/20506092)
- 请同时翻译 README 和 module.prop 中的 description

### 如果你不是组织成员
1. fork [这个repository](https://github.com/Magisk-Modules-Repo-CN/modules_list)，在列表中按格式加入您想汉化的模块（可以是之前翻译错误的模块，也可以是还没有汉化的模块），注意汉化之前先看看列表里面有没有人已经认领了
2. 将您的汉化计划加入列表后, 提交一个 pull-request, 等待审核. 在等待审核的过程中您可以进行下一步
3. 从 [Magisk-Modules-Repo](https://github.com/Magisk-Modules-Repo) fork 你想要汉化的模块,进行翻译
4. 翻译结束后, 将列表里的 汉化状态 改为 [已完成]
5. 提交一个 pull-request，等待审核

### 如果你是组织成员
注意：在进行 push 操作时请先检查是否有更新的提交
1. clone [这个repository](https://github.com/Magisk-Modules-Repo-CN/modules_list), 在列表中按格式加入您想汉化的模块（可以是之前翻译错误的模块，也可以是还没有汉化的模块），注意汉化之前先看看列表里面有没有人已经认领了
2. 将您的汉化计划加入列表后, push 到远端分支
3. 从 [Magisk-Modules-Repo](https://github.com/Magisk-Modules-Repo) fork 你想要汉化的模块,进行翻译
4. 翻译结束后, 将列表里的 汉化状态 改为 [已完成]
5. push 到远端分支

## 模块列表
- [magisk_selinux_manager(Magisk SELinux 管理器)](https://github.com/Magisk-Modules-Repo-CN/magisk_selinux_manager) [已完成] @x4455
- [Magic-Charging-Switch(mcs 充电控制)](https://github.com/Magisk-Modules-Repo-CN/Magic-Charging-Switch) [汉化中] @x4455
- [Enable Doze for GMS Magisk Module(对谷歌服务启用Doze)](https://github.com/Magisk-Modules-Repo-CN/EnableGMSModuleMagisk) [已完成] @TayLin
- [Xposed-Framework-Unity(Xposed 框架 整合版)](https://github.com/Magisk-Modules-Repo/Xposed-Framework-Unity) [已完成] @cjybyjk
- [Magisk-Manager-for-Recovery-Mode(Recovery 模式下的 Magisk 管理器)](https://github.com/Magisk-Modules-Repo-CN/Magisk-Manager-for-Recovery-Mode) [已完成] @cjybyjk
- [terminal_app_systemizer(在终端中系统化 App)](https://github.com/Magisk-Modules-Repo-CN/terminal_app_systemizer) [已完成] @cjybyjk
- [ViPER4Android-FX(蝰蛇音效)](https://github.com/Magisk-Modules-Repo-CN/ViPER4Android-FX) [已完成] @cjybyjk
- [Greenify4Magisk(绿色守护 Magisk 模块)](https://github.com/Magisk-Modules-Repo-CN/Greenify4Magisk) [已完成] @cjybyjk
- [Wifi_Bonding_(Qualcomm)(Wifi锁频模块 - 高通专属)](https://github.com/Magisk-Modules-Repo-CN/magisk-wifi-bonding) [已完成] @TayLin
- [Project_WIPE_Systemless(安装 Project WIPE 调度)](https://github.com/Magisk-Modules-Repo-CN/Project_WIPE_Systemless) [自制模块] @yc9559 & @cjybyjk
- [Audio Modification Library(音频修改支持库)](https://github.com/Magisk-Modules-Repo-CN/Audio-Modification-Library) [已完成] @TayLin
- [VoEnabler(启用高清音视频通话)](https://github.com/Magisk-Modules-Repo-CN/VoEnabler) [已完成] @TayLin
 ## 交流群
 欢迎加入Magisk-Modules-Repo-CN小组，群聊号码：[859768584](https://jq.qq.com/?_wv=1027&k=53iHiNg)
