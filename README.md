# Writing for Agents CN

**让代理知道什么时候读、读什么、做到哪里算完成。**

基于 [mattpocock/skills 的 writing-for-agents](https://github.com/mattpocock/skills/tree/main/skills/productivity/writing-for-agents) 小幅中文适配，独立维护、非官方。

## 保留与补充

保留上游的上下文指针、信息层级、完成条件、渐进披露、合并与拆分、删减重复内容等方法，以及原始技能机制参考。

中文补充关注自然触发条件、术语一致、可观察的完成结果，以及按实际宿主选择调用配置。先整理用户指定范围，用真实使用结果判断是否改善行为。

## 安装与调用

```bash
npx skills add batespaige357-tech/writing-for-agents-cn --skill writing-for-agents-cn
```

对助手说：“用 writing-for-agents-cn 整理这份代理文档，保留现有意图，检查触发条件、信息层级和完成标准。”Codex 可使用 `$writing-for-agents-cn`。

手动安装复制 `skills/writing-for-agents-cn` 完整目录，保留 SKILL-MECHANICS.md。调用配置依目标宿主实际支持为准，本包不提供跨平台自动转换器，也不会自动修改全局指引。

## 来源与检查

MIT，保留 Matt Pocock 原版权与完整许可证，详见 [CHANGES.md](CHANGES.md)。

已检查原正文和机制参考保留、UTF-8、本地引用和技能格式。未进行真实文档改写效果或助手行为评估，不宣称降低错误率或节省特定Token比例。未运行前端编译，不含示例网页、效果截图或前后对比。
