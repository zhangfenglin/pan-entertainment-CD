# 《开荒》游戏策划文档

> 本目录按标准游戏策划要素组织。每个子目录的 **README.md** 即该模块入口；系统设计模块另有 6 份独立文档。

## 完整文件清单（打开即可阅读）

```
game-design/
├── README.md                          ← 你在这里
├── 01-项目概述/README.md              项目定位、目标用户、核心决策
├── 02-世界观叙事/README.md            背景、地图、叙事基调
├── 03-核心玩法/README.md              主循环、开荒、工具、种植
├── 04-系统设计/
│   ├── README.md                      系统索引
│   ├── 经济体系.md
│   ├── 随机事件系统.md
│   ├── 进度与成长.md
│   ├── 作物生长与时间节奏.md
│   ├── 材料合成与产出.md
│   └── 生活与社群.md
├── 05-数值策划/
│   ├── README.md                      数值摘要
│   ├── 术语表.md
│   └── 数值框架.md
├── 06-内容规划/
│   ├── README.md                      内容摘要
│   ├── 新手引导.md
│   └── MVP功能清单.md
├── 07-UI交互/README.md                界面与交互原则
├── 08-商业化/README.md                付费点与原则
├── 09-版本规划/README.md              里程碑与待办
└── 配置数据/README.md                 指向 config/*.json
```

## 模块导航

| 模块 | 入口 |
|------|------|
| 01 项目概述 | [01-项目概述/README.md](./01-项目概述/README.md) |
| 02 世界观叙事 | [02-世界观叙事/README.md](./02-世界观叙事/README.md) |
| 03 核心玩法 | [03-核心玩法/README.md](./03-核心玩法/README.md) |
| 04 系统设计 | [04-系统设计/README.md](./04-系统设计/README.md) |
| 05 数值策划 | [05-数值策划/README.md](./05-数值策划/README.md) |
| 06 内容规划 | [06-内容规划/README.md](./06-内容规划/README.md) |
| 07 UI交互 | [07-UI交互/README.md](./07-UI交互/README.md) |
| 08 商业化 | [08-商业化/README.md](./08-商业化/README.md) |
| 09 版本规划 | [09-版本规划/README.md](./09-版本规划/README.md) |
| 配置数据 | [配置数据/README.md](./配置数据/README.md) |

## 设计一句话

**「每一锄下去，都是未来的一亩良田。」**

## 核心闭环

```
劳动 → 土地 → 产出 → 货币/材料 → 工具/基建/生活建设 → 更高效劳动 + 更强归属感
```

## 配置表（仓库根目录 [`config/`](../config/)）

详细说明见 [配置数据/README.md](./配置数据/README.md)。

| 文件 | 用途 |
|------|------|
| [time-economy.json](../config/time-economy.json) | **v3 时间锚点**（时间槽、周期、精力） |
| [crops.json](../config/crops.json) | 作物产出与价格 |
| [crop-growth.json](../config/crop-growth.json) | 作物生长周期 |
| [materials.json](../config/materials.json) | 材料定义与产出 |
| [recipes.json](../config/recipes.json) | 合成配方 |
| [life-progression.json](../config/life-progression.json) | 住宅、道路、伴侣 |
| [weather-mapping.json](../config/weather-mapping.json) | 本地天气映射 |

## 建议阅读顺序

1. [01 项目概述](./01-项目概述/README.md) → [02 世界观](./02-世界观叙事/README.md)
2. [03 核心玩法](./03-核心玩法/README.md)
3. [04 系统设计](./04-系统设计/README.md) 下各文档
4. [05 数值策划](./05-数值策划/README.md)
5. [06 MVP](./06-内容规划/MVP功能清单.md) → [09 版本规划](./09-版本规划/README.md)

## 版本

- 初稿：2026-07-29
- 目录重组：2026-07-30
- **时间经济 v3.1**：2026-07-30 — 基础时间槽 **1 分钟**，联动加速生长与劳动节奏
- 状态：设计阶段，待原型验证
