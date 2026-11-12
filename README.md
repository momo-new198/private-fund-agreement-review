# 中国境内私募基金协议审核

`private-fund-agreement-review` v1.0.0 用于审核拟在中国境内新设的私募基金。适用文件包括合伙协议、公司章程、股东协议、契约型基金合同，以及认购、管理和托管文件。

审核先按组织形式、产品类型和适用日期核对监管要求，定位不合规条款及必备条款缺失，并给出条文依据和修改建议。随后按 GP、LP 或中立立场审阅费用、分配、回拨、治理和退出等商业安排。公司制和契约制基金使用实际角色进行分析。

## 安装与使用

1. 从 [v1.0.0 Release](https://github.com/momo-new198/private-fund-agreement-review/releases/tag/v1.0.0) 下载 `private-fund-agreement-review-v1.0.0.zip` 并解压。
2. 将整个 `private-fund-agreement-review` 文件夹放入 Codex 的个人技能目录 `~/.codex/skills/`，使 `SKILL.md` 位于该文件夹根目录。
3. 在 Codex 中输入 `$private-fund-agreement-review`，提供拟审核的协议、基金类型和审核立场。未指定立场时采用中立分析。

示例请求：使用 `$private-fund-agreement-review` 从 LP 立场审阅所附拟新设股权基金合伙协议。先列监管缺口及依据，再给商业条款修改建议和可替换文本。

## 资料与适用范围

技能内附监管规则索引、原文定位和脱敏商业场景。适用范围为拟新设境内私募基金。法规依据以包内标明版本及本次审阅获得的资料为准，遇到版本或事实缺口时应列明待核事项。商业场景中的条款和算例用于比较结构、经济后果及执行条件。

使用流程、主题路由和引用规范见 [SKILL.md](SKILL.md)。
