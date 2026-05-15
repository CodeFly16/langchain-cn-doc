# 翻译同步日志

记录每次从上游 `langchain-ai/docs` 同步翻译的变更内容。

---

## 2026-05-15 (2) | 208070d..90dd81a

**变更统计**：5 个文件，+25 / -3 行

### 修改（5 个）

| 文件 | 变更说明 |
|------|---------|
| `langsmith/assertions.mdx` | Note 内容精简；新增 `<Tip>` 段落介绍 Engine 自动提议 assertions |
| `langsmith/engine.mdx` | 第 4 步补充 assertions 链接和说明；底部参考链接新增 assertions |
| `oss/python/integrations/chat/openai.mdx` | 新增 base_url 代理/环境变量配置说明（含 stream_usage 行为） |
| `oss/python/integrations/embeddings/openai.mdx` | 新增 base_url 代理/环境变量配置说明 |
| `oss/python/integrations/llms/openai.mdx` | 新增 base_url 代理/环境变量配置说明 |

---

## 2026-05-15 | d132a7d..208070d

**变更统计**：39 个文件，+5,558 / -1,150 行

### 修改（6 个）

| 文件 | 变更说明 |
|------|---------|
| `oss/python/deepagents/customization.mdx` | 大幅重构：内联代码块替换为 snippet 组件引用，新增 ContextHubBackend Tab |
| `oss/python/deepagents/quickstart.mdx` | 步骤 3/4/5 代码片段化，更新部署链接和 streaming 链接 |
| `oss/javascript/deepagents/customization.mdx` | 同 Python 版重构，补齐未翻译的英文段落 |
| `oss/javascript/deepagents/quickstart.mdx` | 同 Python 版更新，部署链接指向 langsmith |
| `snippets/code-samples/manage-prompts-pull-commit-java.mdx` | 小改动 |
| `snippets/code-samples/manage-prompts-push-java.mdx` | 小改动 |

### 新增（27 个）

全部位于 `snippets/code-samples/`，为 deepagents customization/quickstart 拆出的代码片段：

- `customization-interpreters-{js,py}.mdx`
- `customization-memory-filesystem-{js,py}.mdx`
- `customization-memory-state-{js,py}.mdx`
- `customization-memory-store-{js,py}.mdx`
- `customization-middleware-{js,py}.mdx`
- `customization-middleware-do-{js,py}.mdx`
- `customization-middleware-dont-{js,py}.mdx`
- `customization-profiles-py.mdx`
- `customization-structured-output-{js,py}.mdx`
- `customization-system-prompt-{js,py}.mdx`
- `customization-tools-{js,py}.mdx`
- `quickstart-create-agent-{js,py}.mdx`
- `quickstart-run-agent-{js,py}.mdx`
- `quickstart-search-tool-{js,py}.mdx`

### 遗漏补翻（6 个）

| 文件 | 说明 |
|------|------|
| `langsmith/deploy-managed-deep-agent.mdx` | 托管 Deep Agent 部署文档 |
| `langsmith/engine.mdx` | LangSmith Engine 文档 |
| `langsmith/managed-deep-agents-api.mdx` | 托管 Deep Agents API 参考 |
| `oss/javascript/langgraph/event-streaming.mdx` | JS 版事件流文档 |
| `oss/python/langgraph/event-streaming.mdx` | Python 版事件流文档 |
| `snippets/backend-context-hub-py.mdx` | Backend ContextHub 代码片段 |
