---
name: chat-topic
description: Build playful social chat topic packs from a given theme. Use when the user gives a topic like 港乐、咖啡、宠物、MBTI、旅行 and wants a ready-to-chat pack with background knowledge, open questions, cold facts, discussion points, and invite angles.
---

# 聊天话题包

## 目的

把一个话题整理成适合社交聊天的内容包，风格要轻松、好接话、带一点趣味，适合男女聊天场景。

## 选文件

生成前先从 `references/` 里找对应主题文件。

固定映射如下：

- 港乐 -> `references/gang-le.md`
- 咖啡 -> `references/kafei.md`
- 宠物 -> `references/chongwu.md`
- MBTI -> `references/mbti.md`
- 旅行 -> `references/lvyou.md`

如果用户输入的是近义词或变体，选最接近的那个文件。

## 输出格式

严格按下面顺序输出，并且只用这五个二级标题：

1. `## 背景知识`
1. `## 开放问题`
1. `## 冷知识`
1. `## 讨论点`
1. `## 邀约切口`

## 写作要求

- 偏社交场景，偏男女聊天。
- 不要百科腔，不要像资料汇编。
- 句子短一点，口语一点，最好能直接复制去聊天。
- 开放问题要容易接话，最好能引出经历、偏好、态度。
- 冷知识要有一点“原来还有这回事”的感觉，但别太硬核。
- 讨论点要能自然往下聊，不要空泛。
- 邀约切口要自然，像聊天顺势带出来，不要像销售话术。

## 生成顺序

1. 先读对应 reference。
1. 先提炼这个话题最适合聊天的气质。
1. 再生成四类内容，保持有趣、轻松、可接话。
1. 如果信息不够，宁可写得轻巧一点，也不要写成百科。

