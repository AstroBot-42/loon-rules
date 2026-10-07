# loon-rules

Loon (macOS / iOS) 在线规则与插件集合。

> Loon 3.3.3 (891) 起启用专属文件后缀：分流规则用 **`.lsr`**（Loon Shunt Rules），插件用 **`.lpx`**（Loon Plugin Extension），配置文件用 **`.lcf`**，任务用 **`.ltx`**。

## 规则集

| 名称 | 订阅链接 |
| --- | --- |
| Muse AI | `https://raw.githubusercontent.com/AstroBot-42/loon-rules/main/rules/muse.ai.lsr` |

在 Loon 配置的 `[Rule]` 段通过 `RULE-SET` 引用：

```ini
[Rule]
RULE-SET,https://raw.githubusercontent.com/AstroBot-42/loon-rules/main/rules/muse.ai.lsr,PROXY
```

## 插件

| 名称 | 安装链接 | 来源 |
| --- | --- | --- |
| YouTube 去广告 | `https://raw.githubusercontent.com/AstroBot-42/loon-rules/main/plugins/YouTubeNoAds.lpx` | [teaoea/shell](https://github.com/teaoea/shell) (MIT) |

在 Loon 的「插件」页面通过链接添加即可。脚本依赖（`dist/*.min.js`）仍指向原作者仓库，未做改动。

## 镜像加速（如 raw.githubusercontent.com 访问不畅）

```
https://cdn.jsdelivr.net/gh/AstroBot-42/loon-rules@main/rules/muse.ai.lsr
https://cdn.jsdelivr.net/gh/AstroBot-42/loon-rules@main/plugins/YouTubeNoAds.lpx
```

## 数据来源与许可

- Muse AI 规则：取自 [ddgksf2013 的 Ai.yaml](https://ddgksf2013.top/filter/Ai.yaml) 中的 `Muse AI` 分组。
- YouTube 去广告插件：来自 [teaoea/shell](https://github.com/teaoea/shell)，作者「可莉唯一的狗」，MIT 许可，版权与许可全文见 `licenses/YouTubeNoAds.MIT.txt`。
