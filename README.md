# CocKleBurs Development Kit

CocKleBurs (CKB) 是一个 AAA 级的 Unity 框架，旨在无缝游戏开发，无需额外的插件或扩展。它支持各种游戏类型，包括在线游戏、买断制游戏、移动游戏和独立游戏，适用于多个平台。该框架持续更新，以与最新的 Unity 技术和实践保持一致，借鉴了 GF、ET 和 CF 等现有框架的经验。

## Key Features / 主要特点

### 1. Comprehensive Modules / 综合模块
CKB 包含 **23 个模块化系统**（未来还会增加），提供各个领域的功能：

- **Transitions and Animations / 过场动画和动画**: 高效管理动画和过场。
- **State Machines / 状态机**: 轻松实现复杂的游戏状态逻辑。
- **AI Behavior Trees / AI 行为树**: 创建智能 NPC 的行为树。
- **UI Management / UI 管理**: 简化用户界面处理。
- **Resource Management / 资源管理**: 使用 Addressables 和 AssetBundles。
- **Localization / 本地化**: 支持多种语言。
- **Hot Code Updates / 热更新代码**: 无需重启即可更新代码。
- **Database Support / 数据库支持**: 与各种数据库系统集成。
- **File Systems / 文件系统**: 管理不同保存方法的文件（JSON、PlayerData、SteamWorks、XML）。

### 2. Simplified API / 简单的 API
CKB 采用简单明了的 API，允许用户轻松提取模块。核心组件“Game”作为框架的主要枢纽。API 设计简单直观，避免不必要的前缀。

### 3. Architecture / 架构
CKB 采用类似 Unreal Engine 的 **GamePlay 架构**，使其适用于任何游戏类型。通过遵循一致的命名约定和编码标准，开发人员可以实现清晰的代码和方便的调试。

### 4. Multiplayer Support / 多人游戏支持
CKB 支持基于 **FishNet** 的多人游戏开发，封装访问方法并集成 OnInput 系统。输入变化时会自动发送更新，无需 RPC。

## Advantages / 优势

### 1. Team Collaboration / 团队协作
- **Documentation Integration / 文档集成**: 内置对 Notion 的支持，便于快速访问项目文档。
- **Commenting Features / 评论功能**: 团队成员可以留下评论，以更好地协作。
- **Future Bug Reporting / 未来的 Bug 报告**: 可能集成 Bug 反馈和玩家评论。

### 2. Performance Optimization / 性能优化
- **Pooling Systems / 池化系统**: 实现声音和粒子系统的池化，以增强性能。
- **Asynchronous Operations / 异步操作**: 针对网络和单机游戏优化流程。
- **Unified Control / 统一控制**: 单实例管理所有 SO（Scriptable Objects），简化资源管理。

### 3. SteamWorks Integration / SteamWorks 集成
- **Out-of-the-Box Features / 开箱即用的功能**: 包含语音聊天、Steam 继承服务器和好友聊天等功能。

![Background Logo](https://github.com/user-attachments/assets/db75f238-66bb-4ece-a087-49a319631422)

## Getting Started / 开始使用
Follow these steps to integrate the CocKleBurs Development Kit into your Unity project:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CocKleBurs-DevelopmentKit.git
