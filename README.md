# hrm-advisory-corps

**HRM 实战参谋团** · v1.0.1 · `team`

> China-market HRM team: one orchestrator plus eight specialists across org planning, talent sourcing, recruitment, talent, performance, compensation, compliance and SBTI assessment, gated by a unified compliance layer.


Part of the [WorkBuddy Experts](https://github.com/Lucewalk/lucewalk-experts) collection — expert teams, agents and skills for the WorkBuddy AI assistant platform.


## What it does

- **hrm-solution** — |
- **org-planning** — 组织规划私有 playbook——组织健康度诊断、编制规划、架构模型比选、经营运营简报。引用私有 KB（org-health / workforce-planning）与共享引擎 org_health.py。
- **recruitment-pipeline** — 招聘管道私有 playbook——渠道运营、JD 优化、简历解析/优化、人岗匹配、五维评分、面试设计、模拟面试陪练、数字人面试运营、校招/猎头/雇主品牌。引用私有 KB（recruiting-pipeline / interview-evaluation / candidate-
- **talent-development** — 人才发展私有 playbook——培训需求诊断、课程体系与教学设计、内容开发、新员工 30/60/90、领导力梯队、内训师 TTT、柯氏四级评估、合规培训。引用私有 KB（talent-development / training-program-design）。
- **performance-management** — 绩效管理私有 playbook——KPI（SMART 五维）/OKR（O+3×KR）设计、目标拆解与对齐、达成差距分析、校准会强制分布（5-20-60-10-5%）、绩效面谈提纲、PIP 触发。引用私有 KB（performance / okr-template-library）
- **compensation-strategy** — 薪酬策略私有 playbook——定薪决策与市场竞争对标（四层证据/置信度纪律）、薪资核算（个税+五险一金+年终奖优化）、申报排雷、全面薪酬框架。引用私有 KB（compensation-band / compensation-pitfalls / payroll-china）与
- **labor-compliance** — 劳动合规私有 playbook——劳动合规基线（25+ 主题）、合同/制度风险诊断（P0-P3）、高风险条款改写（六段式）、政策生成（六入七出）、争议处理话术、跨模块编排合规终审闸门（final_gate）。引用私有 KB（policy-generation / complian
- **personality-assessment** — 人才测评私有 playbook——SBTI 职场人格测评（32 题确定性引擎）与文本画像，输出结构化报告（类型代号/标题/描述/本地海报）。引用共享引擎 ../hrm-solution/scripts/sbti_assessment.py 与私有资产 assets/sbti/。
- **hr-practice-library** — |
- **talent-sourcing** — 人才寻访私有 playbook——招聘管道上游的主动寻访与人才库运营。当任务涉及用人需求解析为寻访画像、人才库定向搜索与匹配、寻访侧初评（触达难度/在职稳定性/薪酬契合度）、A/B/C 分级 shortlist 产出与交接、人才库五库（简历/职位需求/人才画像/人才地图/渠道）运

## Agent roster

| Agent | Role |
|---|---|
| `compensation-strategy` | 薪酬策略 Agent - 周予安 |
| `hrm-advisory-corps-lead` | HRM 实战参谋团 - 主理人 · 韩明轩 |
| `labor-compliance` | 劳动合规 Agent - 郑宜宁 |
| `org-planning` | 组织规划 Agent - 邵铭川 |
| `performance-management` | 绩效评估 Agent - 宋雨薇 |
| `personality-assessment` | 人才测评 Agent - 柳心悦 |
| `recruitment-pipeline` | 招聘管道 Agent - 唐嘉树 |
| `talent-development` | 人才发展 Agent - 孟启帆 |
| `talent-sourcing` | 人才寻访 Agent - 齐一鸣 |

## Install

1. Download the package zip from [Releases](https://github.com/Lucewalk/hrm-advisory-corps/releases) or clone this repo;
2. Unzip keeping the internal manifest structure intact;
3. Import/register in WorkBuddy (custom connector → trust & enable).

## Version

Current release: **v1.0.1** — see [CHANGELOG.md](CHANGELOG.md) if present, or the package manifest.

## License

MIT — see [LICENSE](LICENSE).
