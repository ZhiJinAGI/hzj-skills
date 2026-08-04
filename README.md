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

本仓库采用常见的 Agent Skills 目录结构。不同客户端的 Skill 加载位置可能不同，下面以 `~/.agents/skills/` 为例：

```bash
git clone https://github.com/ZhiJinAGI/hzj-skills.git
mkdir -p ~/.agents/skills
cp -R hzj-skills/hzj-influence ~/.agents/skills/
```

安装后，请重新加载或重启你的 Agent 客户端。如果目标目录里已有同名 Skill，请先确认版本，避免误覆盖。

## 仓库结构

```text
hzj-skills/
├── README.md
└── hzj-influence/
    ├── SKILL.md
    └── references/
        ├── principles.md
        └── scenarios.md
```

- `SKILL.md`：定义 Skill 的触发条件、工作流程、输出要求和使用边界。
- `references/`：存放按需读取的原则、案例和场景资料。

## 新增 Skill 的约定

每个新 Skill 至少应包含：

1. 独立目录和一份 `SKILL.md`。
2. 清楚的名称、用途和明确触发方式。
3. 可执行的工作流程，而不只是知识摘要。
4. 必要的风险边界与拒绝条件。
5. README 清单中的一条对应记录。

## 许可

本仓库目前尚未添加开源许可证。公开可见不等于已授权自由复制、改编或商业使用。
