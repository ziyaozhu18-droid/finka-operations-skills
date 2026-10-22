# Finka Operations Skills

面向运营同学的 Codex Skill 集合。目前包含：

- **运营提需澄清**：把一句话想法、用户反馈、活动方案或飞书文档整理为可供产品评估的提需澄清卡；补齐运营可回答的信息、识别边界，并标出 `需产品确认`。

## 使用范围

- 嗒哒：仅基于当前可访问的飞书资料做只读核验；资料不足时会明确写为“未发现依据”。
- 翻咔：按当前**无法发版**约束，只给出现有资源、运营流程、内容策略或人工执行范围内的方案；任何现网或产品决策不确定项均为 `需产品确认`。

## 安装

在 Codex CLI 中添加此 Marketplace：

```bash
codex plugin marketplace add ziyaozhu18-droid/finka-operations-skills
```

然后在 ChatGPT desktop app 的 Plugins Directory 中选择该 Marketplace，安装“运营提需澄清”。安装后请新开一个对话再使用。

## 更新

运行以下命令拉取 Marketplace 的最新版本：

```bash
codex plugin marketplace upgrade finka-operations-skills
```

随后重启 ChatGPT desktop app，并新开对话。每次更新会在 GitHub 提交记录中说明原因和影响。

## 反馈

遇到不符合实际工作流的输出，请提交 Issue，并附上脱敏后的输入、预期和实际结果。
