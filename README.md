# 开荒（Kaihuang）

一款以土地开垦与农场经营为核心的休闲策略游戏设计项目。

## 文档

完整设计文档见 **[docs/](./docs/README.md)**：

| 章节 | 文档 |
|------|------|
| 索引 | [文档目录](./docs/README.md) · [术语表](./docs/00-术语表.md) |
| 01 | [游戏概述](./docs/01-游戏概述.md) |
| 02 | [核心玩法](./docs/02-核心玩法.md) |
| 03 | [经济体系](./docs/03-经济体系.md) |
| 04 | [随机事件系统](./docs/04-随机事件系统.md) |
| 05 | [进度与成长](./docs/05-进度与成长.md) |
| 06 | [数值框架与 UI](./docs/06-数值框架与UI.md) |
| 07 | [作物生长与时间节奏](./docs/07-作物生长与时间节奏.md) |
| 08 | [材料合成与产出](./docs/08-材料合成与产出.md) |
| 09 | [生活与社群](./docs/09-生活与社群.md) |

## 配置

| 文件 | 说明 |
|------|------|
| [config/crop-growth.json](./config/crop-growth.json) | 作物生长周期 |
| [config/materials.json](./config/materials.json) | 材料定义与产出 |
| [config/recipes.json](./config/recipes.json) | 合成配方 |
| [config/life-progression.json](./config/life-progression.json) | 住宅、道路、伴侣 |
| [config/weather-mapping.json](./config/weather-mapping.json) | 本地天气映射 |

## 核心卖点

**「每一锄下去，都是未来的一亩良田。」**

玩家扮演勤奋的农场主，在荒芜之地开荒、种植、合成与生活建设；作物按现实时间生长，随时可种、成熟可收；可升级住宅、铺设道路、与同伴共建庄园。

## 核心闭环

```
劳动 → 土地 → 产出 → 货币/材料 → 工具/基建/生活建设 → 更高效劳动 + 更强归属感
```
