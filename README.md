# 孙黄薄人生战略顾问 · Sun–Huang–Bo Life Strategy

一套中文 ChatGPT Skill，借鉴**孙学（战略与机会成本）**、**黄毛思维（主体性与边界）**和**薄肌理论（身体管理与可持续执行）**的不同视角，帮助用户分析人生选择，并把判断变成可检验的行动。

> **项目状态：v1.0 初始研究版。** 本项目为独立创作的实践框架，并非孙宇晨、邵艾伦（Alan Shao）官方作品或背书；网络理论不等于经过科学验证的普遍规律。

## 能做什么

- **重大选择**：比较教育、职业、财务决策的机会成本、风险、可逆性和信息缺口。
- **反内耗与行动**：辨认对外界评价的担心，建立合理边界，设计可执行的小步行动。
- **身体与习惯**：关注力量、睡眠、饮食、恢复和长期精力，而不是追求极端体型。
- **持续复盘**：区分事实、假设和个人价值观；提供行动指标和改变建议的条件。

## 文件结构

- [SKILL.md](SKILL.md)：触发条件、工作流程、回复模式和安全边界
- [agents/openai.yaml](agents/openai.yaml)：ChatGPT Skill 显示信息
- [references/framework.md](references/framework.md)：三个理论视角及其局限
- [references/decision-protocol.md](references/decision-protocol.md)：决策和复盘流程
- [references/examples.md](references/examples.md)：典型问题的分析样例
- [references/sources.md](references/sources.md)：公开资料索引及归属说明

## 如何使用

在支持自定义 Skills 的 ChatGPT 中上传按标准目录结构打包的 ZIP，或将整个目录放入支持 Skills 的应用中。若从本仓库打包，可在本地运行：

```bash
git clone https://github.com/eppeal-stack/sun-huang-bo-lifestrategy.git sun-huang-bo-life-os
cd sun-huang-bo-life-os
git archive --format=zip --prefix=sun-huang-bo-life-os/ HEAD -o ../skill.zip
```

打开 ChatGPT 的 Skills 库，导入生成的 `skill.zip`（具体入口随版本和账号而不同）。

**使用示例：** “请用孙黄薄人生战略视角分析我该不该换工作，区分事实与假设，列出三种策略，并给我今天能做的一步。”

## 使用原则

- 使用原作者公开内容时注明来源，不杜撰引言、不包装成官方理论。
- 在金融、健康、关系等高风险问题上，以事实、风险控制、尊重和现实条件优先。
- 无需绑定账号；不会主动监控或保存个人资料。
- 此项目不包含第三方视频和完整转录稿。

**License：** 尚未选择开源许可证。仓库公开可见，不代表自动授予复制、修改或再分发权限。
