# AI-Rules

AI 域名分流规则，Surge / Shadowrocket / Quantumult X 通用格式。

## 文件

| 文件 | 说明 | 导入后策略 |
|------|------|-----------|
| `ai.txt` | 国外 AI 域名列表（含 FlClash AI 分流并入的精选域名） | 代理分组（如"人工智能"） |
| `ai-direct.txt` | 国产 AI（DeepSeek / 通义 / Kimi / 豆包等 6 个域名，国内直连更快） | DIRECT |

## 导入链接（raw）

```
https://raw.githubusercontent.com/JLuo327/AI-Rules/main/ai.txt
https://raw.githubusercontent.com/JLuo327/AI-Rules/main/ai-direct.txt
```

- Quantumult X：在「过滤器」中添加远程引用，策略选对应分组
- Shadowrocket：在「配置 - 规则」中添加，类型选 Remote File，策略选对应分组
