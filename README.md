# CocKleBurs-DevelopmentKit

AAA级框架使用这个框架，你不需要担心去增加任何插件，任何扩展包就可以立马编写你自己的游戏

让您使用CocKleBurs GameFrameWork的理由：
1.总览
CKB里面一共包含23个完全模块化系（目前还在增加） 包括过场动画 动画 流程 更新流程  UI  启动项 状态机 AI行为树  粒子特效 声音  本地化 事件（无需注册和注销 0GC） 资源管理 （Addressables，AssetBundle）引用 Buff Ban 文件系统 等等

还有不同选择的保存方式  JSON  PlayerData  SteamWorks  XML

1.1简单的API
CKB与其他GameFrameWork不同 CKB从设计上就采用了全部系统模块化 所以你完全可以把里面的系统提取出来 只有一个“Game”它作为整个框架的核心 并且API简单直白 不带任何“奇怪”的前缀

2.架构方式
CKB采用的是类似UE引擎的GamePlay架构方式，所以它能用于任何游戏类型 通过与CKB相同的命名和编写规则 你会获得 “干净”的代码 “便利”的Debug

支持多人游戏开发基于FishNet 并且封装了各种FishNet访问方式 自带一个OnInput 你可以定义一个输入结构体 改变的时候他会自动发送 无需RPC

3.优势
3.1 团队协作
CKB包含一些帮助组件 包括注释组件 简单的版本控制 还有依赖于Notion 你可以快速打开文档 你可以看到协作时 其他成员能看到留言更加直接

未来可能还有内置Bug反馈 玩家可以提交Bug或者是留言 评价 返回到Notion 

3.2优化
其他的网络框架都不在意优化 CKB即插即用 声音系统 粒子特效系统  都经过池化 和异步并且所有SO由一个单例控制(Addressables) 并且他们都用一个CKB面板配置所有东西信息  无论是网络还是单机 CKB内置自己的全流程更详细的更新方式 完全替代Unity

3.3Steamwork
VoiceChat SteamRelayServer SteamFriend Chat  开箱即用 作者：蒼浪子 https://www.bilibili.com/read/cv39263083/?spm_id_from=333.999.0.0&jump_opus=1 出处：bilibili
![BackgroundLogo](https://github.com/user-attachments/assets/db75f238-66bb-4ece-a087-49a319631422)
