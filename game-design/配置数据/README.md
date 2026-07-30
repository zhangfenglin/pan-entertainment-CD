# 配置数据

[← 返回总索引](../README.md)

策划配置表存放于仓库根目录 **`config/`**，与程序读取路径一致。

## 已有配置（v3）

| 文件 | 模块 | 说明 |
|------|------|------|
| [time-economy.json](../../config/time-economy.json) | **时间锚点** | 时间槽、游戏日、精力、商队周期、铜币锚点 |
| [crops.json](../../config/crops.json) | 作物经济 | 产出、种子价、净铜/轮、每小时收益 |
| [crop-growth.json](../../config/crop-growth.json) | 作物生长 | 生长分钟数、阶段拆分、天气系数 |
| [materials.json](../../config/materials.json) | 材料 | 分级、基价、倾销窗口（48h） |
| [recipes.json](../../config/recipes.json) | 合成 | 设施、配方、合成分钟数 |
| [life-progression.json](../../config/life-progression.json) | 生活 | 住宅、道路、伴侣、48h 维护 |
| [weather-mapping.json](../../config/weather-mapping.json) | 事件 | 现实天气 → 游戏标签 |

## 待补充配置

| 文件 | 说明 |
|------|------|
| `tools.json` | 工具效率、耐久、障碍 |
| `tiles.json` | 地块类型、工作量 |
| `events.json` | 事件权重、阶段、应对 |
| `market.json` | 基础价、商队周期系数 |

## 维护约定

- **v3 联动原则**：修改 `time-economy.json` 中的时间槽或商队周期时，须同步检查 `crops.json`、`recipes.json`、`life-progression.json` 及对应系统设计文档
- 数值变更同步更新 [术语表](../05-数值策划/术语表.md) 与对应系统设计文档
- 配方/材料变更需跑平衡验收（见 [材料合成与产出](../04-系统设计/材料合成与产出.md#65-数值验收清单)）
