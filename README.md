# hzj-skills

ZhiJinAGI 维护的 AI Agent Skills 集合。

这个仓库把经过实践的方法沉淀成可复用、可检查、可持续更新的技能包。每个 Skill 都放在独立目录中，以 `SKILL.md` 作为入口，并可按需附带参考资料。

## 当前 Skills

| Skill | 能做什么 | 明确触发方式 | 状态 |
| --- | --- | --- | --- |
| [`hzj-influence`](./hzj-influence/SKILL.md) | 在需要说服、协商、推动行动或识别套路时，帮助看清阻力、选择策略，并给出可执行的推进步骤。 | `/hzj-influence`<br>`使用影响力 skill`<br>`按《影响力》的框架` | 可用 |

> 新增 Skill 后，会同步更新这张表。

## hzj-influence

`hzj-influence` 基于《影响力》的七项原则，支持两类任务：

- 帮你说服别人，例如谈薪、请假、催款、砍价、争取资源。
- 帮你识别并应对套路，例如直播逼单、销售话术、人情绑架。

它不会因为普通的“说服”问题自动触发。请明确点名 Skill，例如：

```text
使用影响力 skill，帮我分析怎么和老板谈涨薪。
```

```text
按《影响力》的框架，帮我看看这段销售话术在用什么套路。
```

这个 Skill 只使用真实证据、真实期限和真实身份，不支持虚构稀缺、伪造背书、隐瞒风险或操纵弱势群体。

## 安装

把下面的仓库链接发给 WorkBuddy、Codex、Claude Code 等智能体，让它帮你安装需要的 Skill：

```text
请帮我安装这个仓库里的 hzj-influence Skill：
https://github.com/ZhiJinAGI/hzj-skills
```
