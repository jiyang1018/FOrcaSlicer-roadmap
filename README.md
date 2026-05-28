# FOrcaSlicer — Flexible OrcaSlicer
A fork of [Snapmaker OrcaSlicer](https://github.com/SoftFever/OrcaSlicer) adding mixed nozzle size printing support for the Snapmaker U1 4-head printer.

## Development Roadmap
Track progress, design decisions, and implementation details:
👉 **[View the interactive roadmap](https://jiyang1018.github.io/FOrcaSlicer-roadmap/)**

## About
The Snapmaker U1 supports 4 independent print heads with different nozzle diameters (e.g. 0.2mm, 0.4mm, 0.6mm, 0.8mm). Stock Snapmaker OrcaSlicer syncs all nozzles to the same size. FOrcaSlicer extends the slicer to:
- Gate printing behind a nozzle verification dialog — each head independently configurable
- Route outer wall (OW), inner wall (IW), infill, solid infill, and prime tower to different nozzle sizes independently
- Visualize print line widths reflecting actual nozzle diameter per extruder
- Allow independent nozzle diameter configuration per head
- Support per-object, per-filament color patch loops — N outer loops printed in painted color, inner loops and infill use base filament ✅

---

# FOrcaSlicer — 灵活版 OrcaSlicer
[Snapmaker OrcaSlicer](https://github.com/SoftFever/OrcaSlicer) 的分支版本，为 Snapmaker U1 四头打印机添加混合挤出口尺寸打印支持。

## 开发路线图
查看进度、设计决策和实现细节：
👉 **[查看交互式路线图](https://jiyang1018.github.io/FOrcaSlicer-roadmap/)**

## 关于本项目
Snapmaker U1 支持 4 个独立工作头，每个挤出口直径不同（如 0.2mm、0.4mm、0.6mm、0.8mm）。原版 Snapmaker OrcaSlicer 将所有挤出口同步为相同尺寸。FOrcaSlicer 对切片器进行了以下扩展：
- 打印前通过挤出口验证对话框确认配置 — 每个工作头可独立设置
- 外墙（OW）、内壁（IW）、填充、实心填充及换料塔可分别指定不同挤出口尺寸
- 预览中的打印线宽反映每个挤出机的实际挤出口直径
- 支持每个工作头独立配置挤出口直径
- 支持逐对象、逐耗材着色区域循环数 — 外层 N 圈以涂色耗材打印，内壁及填充使用基础耗材 ✅