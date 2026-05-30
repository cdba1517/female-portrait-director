# 版本管理

当前公开版本：

```text
FEMALE-PORTRAIT-DIRECTOR-V1.1
```

## 版本格式

```text
FEMALE-PORTRAIT-DIRECTOR-V主版本.次版本
```

- 主版本：核心结构、路由规则或输出契约发生不兼容变化时递增。
- 次版本：增加风格、补充示例、优化措辞或改进安全表达时递增。

## V1.1 变更摘要

`FEMALE-PORTRAIT-DIRECTOR-V1.1` 是创作扩写增强版。该版本新增模块解析与视觉扩写流程，扩充五官、身形、服装、场景、镜头、光线和滤镜规则，并将默认输出统一为：

```text
一、参数锁定结果
二、模块解析
三、最终提示词
四、负面约束
```

## 发布要求

发布新版本时需要同步更新：

1. `NOTICE.md`
2. `CHANGELOG.md`
3. `README.md`
4. `README_zh.md`、`README_ja.md`、`README_ko.md`
5. `skill/skill.md`
6. `agents/openai.yaml`（如 UI 描述变化）

公开仓库不包含私有路由规则、内部稳定核、提示词指纹或未发布商业模块。
