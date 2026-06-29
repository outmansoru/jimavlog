# JimaVlog — 短视频博主风格蒸馏器

> *"换任何话题，风格都不崩。"*

输入目标博主的视频文案 → 四层结构分析 → 产出可安装的 AI Skill，后续用这个 Skill 生成任何话题的短视频文案，风格始终一致。

## 与同类方案

| 方案 | 蒸什么 | 换话题崩不崩 |
|------|--------|------------|
| [blogger-distiller](https://github.com/otter1101/blogger-distiller) | 内容打法 | ⚠️ 可能崩 |
| [nuwa-skill](https://github.com/alchaincyf/nuwa-skill) | 心智模型 | ✅ 不崩 |
| **JimaVlog** | **短视频口播特化** | ✅ 不崩 |

## 为什么它不崩

四层递进：**底层世界观 → 决定论证方式 → 决定段落编排 → 最终落地为字词句**。

换了话题，只要 L4 认知框架不变，生成的文案仍然像这个博主——因为他面对新话题时，确实会用同一套思维模型来分析。

## 安装

```bash
# 在 Hermes Agent 中：
帮我安装 skill: https://github.com/ned-lab/jimavlog
```

## 使用

```bash
蒸馏抖音博主 https://v.douyin.com/xxxxx
```

或直接粘贴 20-50 条文案。

## 产出

```
{博主名}_style.skill/
├── SKILL.md          # 可安装的 AI Skill
└── references/
    └── examples.md   # 示例 + 标注
```

## 许可

MIT
