# Say Human Language

面向 Coding Agent 的工程沟通Skill。帮助你用具体、自然的语言写清变更、证据和验证范围。

适用于 README、用户手册、Issue、PR、代码审查、发布说明和任务交付。纯代码实现通常无需加载。

## 安装与使用

1. [下载仓库 ZIP](https://github.com/Cyber100T/say-human-language/archive/refs/heads/main.zip) 并解压，或使用 `git clone https://github.com/Cyber100T/say-human-language.git`。
2. 将内层 [say-human-language](say-human-language/) 整个目录复制到目标工具已配置的技能目录。复制完成后，应能看到 `say-human-language/SKILL.md` 和同级的 `references/` 目录。
3. 在支持 `$技能名` 显式调用的工具中，用下面的提示试用。技能发现方式和调用语法取决于工具。

> $say-human-language 根据当前差异写一段 PR 描述。说明用户能观察到的变化，并区分已运行的检查和未验证的范围。

例如，只核对了安装配置时，可以写“命令名称已与安装配置核对，安装流程尚未运行”。

当前版本为 1.2。参见[更新日志](CHANGELOG.md)、[对照用例](EVALS.md)和 [MIT 许可证](LICENSE)。

## 验证与反馈

[对照用例](EVALS.md)提供测试输入和验收条件。不同工具中的模型表现和自动触发仍待实测。

提交反馈时，请附上工具与模型版本、技能调用方式、可复现的提示和实际输出。涉及写作规则的改动，可以在 PR 中附一组输入和预期输出。
