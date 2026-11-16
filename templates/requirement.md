# 需求模板入口

原单一需求模板已拆分为四类模板。本入口保留用于兼容既有导航，不再作为具体需求正文复制。

| 需要记录的内容 | 使用模板 | 保存位置 |
| --- | --- | --- |
| 功能整体规则、范围和边界 | [功能规格](feature-spec.md) | [功能规格目录](../docs/features/README.md) |
| 相对规格基线的新增、修改或移除 | [增量 Story](story.md) | [增量 Story 目录](../docs/stories/README.md) |
| 前置条件、操作和预期结果 | [验收场景](acceptance-scenario.md) | [验收场景目录](../docs/acceptance/README.md) |
| 实际执行、结果与证据 | [验证记录](verification-record.md) | [验证记录目录](../docs/verification/README.md) |

复制所需模板，使用稳定编号和文件名，调整相对链接并更新[需求概述](../docs/requirements-overview.md)。四类文档通过编号、链接和版本关联，不用一份重复正文承载全部信息。

模板均为空结构，不是实际业务需求、已确认方案或测试结果。未知信息保留“待确认”；没有执行就不得填写验证通过。公开仓库只记录可核实且获授权公开的信息，遵循[维护约定](../AGENTS.md)。
