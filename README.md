# 洞见卡：把经验变成可调用判断

这是从姜胡说专栏归纳的方法技能，来源与改写记录见 [来源说明](references/sources.md)。

## 什么时候用

把一次工作教训整理成下次可用的判断，或检验旧卡有没有被过度泛化。

## 需要给什么

一段真实经历、文章片段或现有卡；最好附场景、做法、结果。

## 怎么调用

```text
$lany-insight-card-skill
把这段虚构演示材料做成一张候选卡：我做周报时先列本周交付，再写下周计划，经理能更快指出需要他协调的事；但只有一次观察。不要替我补数据。
```

## 示例结果（虚构演示）

核心判断：周报先给已交付结果，再突出需要协调的事项，可能减少读者寻找决策点的成本。
来源：本例是虚构演示，不能作真实经验引用。
机制假设：读者先知道进展，再判断阻碍；尚不能排除经理当日时间充裕等因素。
行动：下一次周报采用同顺序；记录经理提出的澄清问题与协调请求是否被回应。
边界：若组织有强制模板或经理主要做风险审批，应优先按其需求组织。
状态：候选，尚未实测。关联：暂无。


## 交付与边界

技能会提供具体判断、动作和验证方式。它不会把示例当成你的经历，也不会仅凭作者的成功故事承诺结果。文件创建或更新仅在当前任务确有需要且范围明确时进行。

[查看完整技能定义](SKILL.md)。

## 独立仓库与安装

仓库：[lany-insight-card-skill](https://github.com/LanyXiaosheng/lany-insight-card-skill)。本仓库根目录即技能目录，包含 `SKILL.md`、本说明及 `references/`。

确认目标目录不存在后，可在未设置 `CODEX_HOME` 的默认环境下安装：

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/LanyXiaosheng/lany-insight-card-skill.git ~/.codex/skills/lany-insight-card-skill
```

已设置 `CODEX_HOME` 时，将目标改为该目录下的 `skills/lany-insight-card-skill`。已有同名技能时先比较或备份，不覆盖。客户端发现技能后，使用 `$lany-insight-card-skill` 调用。

本独立库从[合集的已发布版本](https://github.com/LanyXiaosheng/lany-creator-skills/tree/367cd21c5417300c8122fe25ef4ff2e4d3f8bd3f)拆分，保留原有来源归属。浏览其他技能可进入[合集](https://github.com/LanyXiaosheng/lany-creator-skills)。
