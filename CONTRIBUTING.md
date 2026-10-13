# 贡献指南

感谢关注 Library Harness Framework。当前项目处于概念验证阶段，优先接受能够帮助澄清边界、验证接口和建立真实用例的贡献。

## 贡献原则

1. 不把尚未实现的设计描述为已有能力。
2. 框架只接收可被多个图书馆应用复用的能力；单一应用规则应留在应用项目中。
3. 新的外部依赖、运行时或数据源必须说明用途、替代方案和安全影响。
4. 示例数据必须脱敏，不得提交读者身份、借阅明细、密钥或生产配置。
5. 重要架构决定应先提交提案，并在 `docs/decisions/` 留下记录。

## 建议流程

1. 先通过 Issue 描述问题、业务背景和期望边界。
2. 对齐方案后再提交小而聚焦的 Pull Request。
3. 在 PR 中列出变更范围、验证方法、已知限制和后续工作。
4. 文档、测试和实现应保持一致。

## 提交信息

建议使用清晰、可检索的提交信息，例如：

```text
docs: clarify validation module boundary
feat(core): add domain component contract
test(workflow): cover failed step transition
```

## 完成标准

- 范围与模块边界清晰。
- 不包含敏感数据或凭据。
- 新增行为有对应测试或明确说明暂未实现。
- README、架构文档和示例按需同步。

