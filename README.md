# CocKleBurs-DevelopmentKit

### AAA级Unity框架

使用这个框架，您无需担心增加任何插件或扩展包，即可立即编写自己的游戏。我将持续更新此框架，以确保其内容适应新的版本和Unity技术。

设计思路参考了我所使用过的GF、ET、CF等框架，并从我使用过的模板和插件中吸取了经验。CocKleBurs将支持网络游戏、买断制游戏、手游、全平台开发以及独立游戏。

## 为什么选择CocKleBurs GameFrameWork？

### 1. 总览

CKB包含23个完全模块化的系统（目前还在增加），包括：

- 过场动画
- 动画
- 流程
- 更新流程
- UI
- 启动项
- 状态机
- AI行为树
- 粒子特效
- 声音
- 本地化
- 事件（无需注册和注销，0GC）
- 资源管理（Addressables，AssetBundle）
- 引用
- Buff
- Ban
- 文件系统
- 热更新代码
- 数据库
- 一部分后端
- 配表

还支持多种保存方式：JSON、PlayerData、SteamWorks、XML。

### 1.1 简单的API

与其他GameFrameWork不同，CKB从设计上采用了模块化的系统，您可以轻松提取所需的系统。框架的核心是一个名为“Game”的组件，并且API设计简单直白，无需“奇怪”的前缀。

### 2. 架构方式

CKB采用类似UE引擎的GamePlay架构方式，因此可以用于任何类型的游戏。通过与CKB相同的命名和编写规则，您将获得“干净”的代码和“便利”的调试体验。

CKB支持基于FishNet的多人游戏开发，并封装了各种FishNet访问方式。自带一个OnInput功能，您可以定义一个输入结构体，改变时自动发送，无需RPC。

### 3. 优势

#### 3.1 团队协作

CKB包含一些帮助组件，包括注释组件和简单的版本控制，依赖于Notion的文档，您可以快速打开文档。协作时，其他成员可以看到留言，沟通更加直接。

未来可能会内置Bug反馈功能，玩家可以提交Bug或留言、评价，直接反馈到Notion。

#### 3.2 优化

其他网络框架往往忽视优化，而CKB是即插即用的。声音系统、粒子特效系统都经过池化和异步处理，所有SO由一个单例控制（Addressables），并且它们都通过CKB面板配置所有信息，无论是网络还是单机，CKB内置了更详细的全流程更新方式，完全替代Unity的更新系统。

#### 3.3 Steamwork

CKB支持开箱即用的VoiceChat、SteamRelayServer和SteamFriend Chat等功能。

![BackgroundLogo](https://github.com/user-attachments/assets/db75f238-66bb-4ece-a087-49a319631422)

---

# CocKleBurs-DevelopmentKit

### AAA Unity Framework

With this framework, you don't need to worry about adding any plugins or extensions; you can immediately start writing your own games. I will continuously update this framework to ensure that its content adapts to new versions and Unity technologies.

The design concepts are inspired by frameworks I have used, such as GF, ET, and CF, and I have drawn experience from templates and plugins I have used. CocKleBurs will support online games, buy-to-play games, mobile games, cross-platform development, and indie games.

## Reasons to Use CocKleBurs GameFrameWork

### 1. Overview

CKB contains a total of 23 fully modular systems (and this number is still increasing), including:

- Cutscene animations
- Animations
- Game flow
- Update flow
- UI
- Startup items
- State machines
- AI behavior trees
- Particle effects
- Sound
- Localization
- Events (no need for registration and unregistration, 0GC)
- Resource management (Addressables, AssetBundle)
- References
- Buffs
- Bans
- File system
- Hot code updates
- Databases
- Some backend systems
- Configuration tables

It also supports various save methods: JSON, PlayerData, SteamWorks, and XML.

### 1.1 Simple API

Unlike other GameFrameworks, CKB is designed with a fully modular system, allowing you to extract the systems you need easily. The core of the framework is a component called “Game,” and the API is simple and straightforward, with no “weird” prefixes.

### 2. Architectural Approach

CKB adopts a gameplay architecture similar to that of the UE engine, making it suitable for any game type. By following the same naming and writing rules as CKB, you will achieve “clean” code and “convenient” debugging experiences.

CKB supports multiplayer game development based on FishNet, encapsulating various FishNet access methods. It comes with an OnInput feature that allows you to define an input structure, which will automatically send updates when changed, eliminating the need for RPC.

### 3. Advantages

#### 3.1 Team Collaboration

CKB includes various helper components, such as comment components and simple version control, relying on Notion for documentation access. You can quickly open documents, and team members can see messages, making communication more direct.

In the future, there may also be built-in bug feedback features, allowing players to submit bugs or leave messages and feedback directly in Notion.

#### 3.2 Optimization

While other networking frameworks often neglect optimization, CKB is plug-and-play. The sound system and particle effects system have been optimized with pooling and asynchronous processing, all managed by a singleton (Addressables). They are all configured through a CKB panel for all information, whether for networked or standalone games. CKB includes a more detailed full-process update method that completely replaces Unity's update system.

#### 3.3 Steamwork

CKB supports out-of-the-box functionalities like VoiceChat, SteamRelayServer, and SteamFriend Chat.

![BackgroundLogo](https://github.com/user-attachments/assets/db75f238-66bb-4ece-a087-49a319631422)
