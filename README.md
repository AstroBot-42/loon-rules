# loon-rules

Loon (macOS / iOS) 在线规则集。

## 规则集列表

| 规则集 | 订阅链接 |
| --- | --- |
| Muse AI | `https://raw.githubusercontent.com/AstroBot-42/loon-rules/main/rules/muse.ai.list` |

## 使用方法

在 Loon 配置中通过 `RULE-SET` 引用，例如：

```ini
[Rule]
RULE-SET,https://raw.githubusercontent.com/AstroBot-42/loon-rules/main/rules/muse.ai.list,PROXY
```

## 镜像加速（如 raw.githubusercontent.com 访问不畅）

```
https://cdn.jsdelivr.net/gh/AstroBot-42/loon-rules@main/rules/muse.ai.list
https://ghproxy.net/https://raw.githubusercontent.com/AstroBot-42/loon-rules/main/rules/muse.ai.list
```

## 数据来源

规则取自 [ddgksf2013 的 Ai.yaml](https://ddgksf2013.top/filter/Ai.yaml) 中的 `Muse AI` 分组，定期同步更新。
