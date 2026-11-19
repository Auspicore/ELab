# ELab 电气实验室

[English](README.md)

**一次学习，多平台使用。**

电气设计、动态仿真与虚拟实验，尽在 ELab。

绘制电气控制原理图，启动虚拟实验，观察电路如何响应。ELab 面向电气工程师、自动化工程师、学生、教师及职业教育机构。

**Windows** · 发行准备中 ｜ **Linux** · 发行准备中 ｜ **macOS** · 发行准备中

[下载 ELab](#download-elab) · [产品演示](#product-demo) · [了解核心功能](#core-capabilities) · [版本更新](#release-history) · [反馈问题](#feedback-and-licensing)

<a name="download-elab"></a>

## 下载 ELab

| 平台 | 架构 | 公开发布状态 |
| --- | --- | --- |
| Windows | x64 | 发行准备中 |
| Windows | ARM64 | 发行准备中 |
| Linux | x64 | 发行准备中 |
| Linux | ARM64 | 发行准备中 |
| macOS | Intel x64 | 发行准备中 |
| macOS | Apple Silicon ARM64 | 发行准备中 |

公开桌面安装包仍在准备。各平台发行时将列明已测试系统、安装包类型、版本、文件大小和 SHA-256 校验值。

[离线文档 v1.1.0](https://github.com/Auspicore/ELab/releases/tag/docs-v1.1.0) · [下载指南](docs/download.md#zh-cn) · [安装与校验](docs/installation.md#zh-cn)

<a name="core-capabilities"></a>

## 核心功能

### 绘制与组织原理图

- 搜索并预览断路器、按钮、接触器和电动机等元件，再放置到图纸上。
- 从端子到端子绘制导线，修改设备属性和线号，也可撤销操作回到先前的设计。
- 将主回路、控制回路和指示回路分图绘制，通过跨页引用找到同一设备的线圈与触点。

### 运行与观察控制回路

- 在实时仿真中操作开关、按钮及保护器件，直接在原理图上观察触点、电动机与指示灯的状态变化。
- 在操作台暂停或单步执行，查看事件时间线，了解各器件发生动作的先后顺序。
- 用起保停案例观察自保持，再通过热继电器模拟过载脱扣，对照两次实验结果。

### 检查设计、规划布置与导出

- 运行设计校验查找接线和设备引用问题，并根据提示定位到相关对象或图纸。
- 在安装板上规划导轨、线槽和设备位置，通过布置检查发现重叠或越界。
- 生成可搜索的设备表、端子表和连接表，将工程报表导出为 CSV、原理图导出为 SVG，便于评审与归档。

<a name="product-demo"></a>

## 产品演示

**松开启动按钮后，电动机为什么还在运行？** 按顺序观察接触器吸合、辅助触点形成自保持回路，以及按下停止按钮后接触器释放。然后模拟热继电器脱扣，对照两次停机的事件。实验指南列出了每一步的预期结果。[电动机起保停实验](docs/quick-start.md#motor-startstop-zh)

## 典型应用场景

- **电气设计评审。** 分图绘制主回路和控制回路，追查相关触点，带着设备表与端子表参加评审。
- **课堂演示。** 请学生先判断松开启动按钮后电动机会不会继续运行，再通过实时原理图核对判断。
- **自主排障练习。** 分别使用停止按钮和热继电器脱扣来停止电动机，通过事件时间线对照两种停机过程。

## 30 秒快速了解

取得适用平台的版本后，在**案例库**创建一个可编辑的电动机控制案例副本。打开**实时仿真**，合上断路器，按下并松开启动按钮。观察电动机和接触器，再按下停止按钮。[查看完整步骤](docs/quick-start.md#zh-cn)

<a name="release-history"></a>

## 版本更新

- **文档 v1.1.0** 补充设计与仿真流程、电动机控制实验和平台指南。[发行说明与离线文档](https://github.com/Auspicore/ELab/releases/tag/docs-v1.1.0)
- **文档 v1.0.0** 归档首版双语产品介绍与快速上手指南。[发行说明与离线文档](https://github.com/Auspicore/ELab/releases/tag/docs-v1.0.0)

[全部 GitHub Releases](https://github.com/Auspicore/ELab/releases) · [更新记录](CHANGELOG.md#zh-cn)

<a name="feedback-and-licensing"></a>

## 反馈问题与商业授权

通过 GitHub Issues 提交问题或功能建议。商业合作、商业授权及院校授权联系方式待公布。[选择反馈类型](https://github.com/Auspicore/ELab/issues/new/choose) · [反馈指南](docs/feedback.md#zh-cn) · [私密漏洞报告](SECURITY.md#security-zh-cn) · [常见问题](docs/faq.md#zh-cn)

## 版权与软件许可

ELab 是商业闭源软件。软件的使用以对应发行版提供的许可条款为准。
