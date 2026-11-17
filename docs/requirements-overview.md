# 需求概述

## 文档状态

本仓库按功能规格、增量 Story、验收场景和验证记录组织。已按获授权公开的脱敏需求整理标准目录目标规格、增量及预期场景，业务确认待确认，暂无产品验证结果。文档不代表排期、交付承诺、已实现、已上线或验收通过；后续内容须基于可核实且可公开的依据补充。

## 产品背景与目标

| 项目 | 内容 | 依据 |
| --- | --- | --- |
| 产品名称及背景 | 待确认 | 待提供可公开依据 |
| 目标用户及使用场景 | 待确认 | 待提供可公开依据 |
| 需要解决的问题 | 待确认 | 待提供可公开依据 |
| 业务目标及衡量方式 | 待确认 | 待提供可公开依据 |
| 范围与约束 | 待确认 | 待提供可公开依据 |
| 需求负责人及确认机制 | 待确认 | 待提供可公开依据 |

## 功能规格索引

参见[目录说明](features/README.md)及[功能规格模板](../templates/feature-spec.md)。

| 编号 | 功能名称及文档 | 规格版本 | 业务确认状态 |
| --- | --- | --- | --- |
| FS-SC-001 | [标准目录导入导出与翻译维护](features/standard-catalog-import-export.md) | v0.1 | 待确认；目标规则 |

## 增量 Story 索引

参见[目录说明](stories/README.md)及[增量 Story 模板](../templates/story.md)。

| 编号 | Story 名称及文档 | 关联功能规格及基线版本 | 业务确认状态 | 优先级及依据 |
| --- | --- | --- | --- | --- |
| ST-SC-001 | [标准目录导入导出优化](stories/standard-catalog-import-export.md) | [FS-SC-001](features/standard-catalog-import-export.md)；无既有仓库规格基线，目标 v0.1 | 待确认 | 待确认 |

## 验收场景索引

以下均为预期场景，未执行。参见[目录说明](acceptance/README.md)及[验收场景模板](../templates/acceptance-scenario.md)。

| 编号 | 场景名称及文档 | 场景版本 | 对应规格条目及 Story（如有） | 业务确认状态 |
| --- | --- | --- | --- | --- |
| AC-SC-001 | [异步导入](acceptance/standard-catalog-async-import.md) | v0.1 | FS-SC-001 v0.1 SC-R01；ST-SC-001 v0.1 SC-D01 | 待确认 |
| AC-SC-002 | [翻译维护路径](acceptance/standard-catalog-translation-maintenance.md) | v0.1 | FS-SC-001 v0.1 SC-R02、SC-R03；ST-SC-001 v0.1 SC-D02、SC-D03 | 待确认 |
| AC-SC-003 | [英文导出翻译](acceptance/standard-catalog-english-export.md) | v0.1 | FS-SC-001 v0.1 SC-R04；ST-SC-001 v0.1 SC-D04 | 待确认 |
| AC-SC-004 | [导出翻译文件兼容](acceptance/standard-catalog-export-fields.md) | v0.1 | FS-SC-001 v0.1 SC-R05；ST-SC-001 v0.1 SC-D05 | 待确认 |
| AC-SC-005 | [不变操作边界](acceptance/standard-catalog-unchanged-operations.md) | v0.1 | FS-SC-001 v0.1 SC-R06；ST-SC-001 v0.1 SC-D06 | 待确认 |

## 验证记录索引

当前无条目。参见[目录说明](verification/README.md)及[验证记录模板](../templates/verification-record.md)。

| 编号 | 验证记录文档 | 关联场景及版本 | 被验证对象及版本 | 执行结论 |
| --- | --- | --- | --- | --- |

## 状态与关联

- 业务确认状态按证据填写，例如“待确认”“已确认”“已撤回”，不代表实现或上线。没有优先级依据时填写“待确认”。
- 验收场景记录预期结果；验证记录单独记录实际结果。没有执行就没有通过结论；执行受阻、未执行或证据缺失须如实注明。
- 规格条目、Story、场景和验证记录通过稳定编号及相对链接关联，同时记录适用版本。未知关联保留“待确认”，不以虚构链接补齐。
- 本页只维护摘要和索引；业务事实和变更依据保留在相应正文，实际执行证据保留在验证记录。不要重复维护同一事实。

## 待确认事项

- 产品背景、目标用户、实际问题和目标是什么？
- 标准目录的具体未决边界见 [FS-SC-001 待确认问题](features/standard-catalog-import-export.md#6-依赖风险与待确认问题)；后续新增内容仍须确认公开范围。
- 谁负责确认业务结论，采用什么确认方式？
- 是否已有明确的范围、约束及验收口径？

以上为初始化提问方向，不预设答案，不构成已确认的业务要求。维护时遵循[维护约定](../AGENTS.md)，新增、移动、改名或变更状态时同步相应索引与链接。
