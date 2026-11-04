# Say Human Language

面向 Coding Agent 的工程沟通技能。帮助你用具体、自然的语言写清变更、证据和验证范围。

适用于 README、用户手册、Issue、PR、代码审查、发布说明和任务交付。纯代码实现通常无需加载。

## 安装与使用

下载或克隆本仓库，将内层 [say-human-language](say-human-language/) 目录复制到工具配置的技能目录，保留 SKILL.md 和 references 的相对位置。在支持显式技能调用的工具中，可输入：

> $say-human-language 根据当前差异写一段 PR 描述。说明用户能观察到的变化，并区分已运行的检查和未验证的范围。

例如，只核对了安装配置时，可以写“命令名称已与安装配置核对，安装流程尚未运行”。

当前版本为 1.2。参见[更新日志](CHANGELOG.md)、[对照用例](EVALS.md)和 [MIT 许可证](LICENSE)。