# hzj-skills

ZhiJinAGI 维护的 AI Agent Skills 集合。

这个仓库把经过实践的方法沉淀成可复用、可检查、可持续更新的技能包。每个 Skill 都放在独立目录中，以 `SKILL.md` 作为入口，并可按需附带参考资料。

## 当前 Skills

| Skill | 能做什么 | 明确触发方式 | 状态 |
| --- | --- | --- | --- |
| [`hzj-influence`](./hzj-influence/SKILL.md) | 在需要说服、协商、推动行动或识别套路时，帮助看清阻力、选择策略，并给出可执行的推进步骤。 | `/hzj-influence`<br>`使用影响力 skill`<br>`按《影响力》的框架` | 可用 |
| [`hzj-positioning`](./hzj-positioning/SKILL.md) | 用《定位》的框架分析品牌、产品、公司或个人如何进入用户心智，并给出竞争位置与避坑建议。 | `/hzj-positioning`<br>`使用定位 skill`<br>`按《定位》的方法` | 可用 |
| [`hzj-naval-thinking`](./hzj-naval-thinking/SKILL.md) | 用《纳瓦尔宝典》的框架分析职业、创业、财富、取舍、幸福与自我成长问题，并给出具体行动方向。 | `/hzj-naval-thinking`<br>`使用纳瓦尔思考 skill`<br>`按《纳瓦尔宝典》的框架` | 可用 |

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

## hzj-positioning

`hzj-positioning` 把《定位》的核心方法整理成一套可直接调用的分析流程：

- 判断品牌在目标用户心中的位置和竞争角色。
- 从抢先占位、寻找空位、重新定位竞争对手、创建新品类中匹配策略。
- 检查品牌延伸、模仿领导者、只讲技术和目标人群过宽等常见陷阱。

使用时请明确点名 Skill，并提供产品、目标用户、主要竞争对手和当前困惑，例如：

```text
使用 hzj-positioning，分析一个新开的社区咖啡品牌，应该在周边上班族心里占据什么位置。
```

## hzj-naval-thinking

`hzj-naval-thinking` 把《纳瓦尔宝典》中的财富、决策与幸福思想整理成可调用的分析流程：

- 分辨财富、金钱和地位，检查专长、杠杆、股权和可复制资产。
- 用可逆性、长期复利和判断力检查职业与创业选择。
- 在焦虑、欲望、嫉妒与接受问题中，选择最相关的框架并给出下一步行动。

它不会机械罗列全部原则，也不会在忽视生存压力和现实约束的情况下劝人辞职或创业。

使用时可以这样提问：

```text
使用 hzj-naval-thinking，帮我分析：我该继续在大厂积累，还是开始做自己的 AI 产品？
```

## 安装

把下面的仓库链接发给 WorkBuddy、Codex、Claude Code 等智能体，让它帮你安装需要的 Skill：

```text
请帮我安装这个仓库里的 hzj-positioning Skill：
https://github.com/ZhiJinAGI/hzj-skills
```
