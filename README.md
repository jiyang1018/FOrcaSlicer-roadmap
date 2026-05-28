# FOrcaSlicer — Flexible OrcaSlicer — Dev Roadmap
This repo hosts the interactive development roadmap for [FOrcaSlicer](https://github.com/jiyang1018/FOrcaSlicer). The project source code lives there.

## Development Roadmap
Track progress, design decisions, and implementation details:
👉 **[View the interactive roadmap](https://jiyang1018.github.io/FOrcaSlicer-roadmap/)**

## About
[FOrcaSlicer](https://github.com/jiyang1018/FOrcaSlicer) is a fork of [Snapmaker OrcaSlicer](https://github.com/SoftFever/OrcaSlicer) adding mixed nozzle size printing support for the Snapmaker U1 4-head printer. The Snapmaker U1 supports 4 independent print heads with different nozzle diameters (e.g. 0.2mm, 0.4mm, 0.6mm, 0.8mm). Stock Snapmaker OrcaSlicer syncs all nozzles to the same size. FOrcaSlicer extends the slicer to:
- Allow independent nozzle diameter configuration per head
- Under Multimaterial tab, separate "Outer wall (OW)" and "Inner wall (IW)" from "Walls"
- Allow OW, IW, infill, solid infill, and prime tower to use different nozzle sizes independently
- Gate printing behind a nozzle verification dialog
- Visualize print line widths reflecting actual nozzle diameter per extruder
- Add color patch mode for painted faces. When a surface is painted with a color, only the outer N wall loops on that surface print in the painted color
- Support per-object, per-filament color patch loops
- Unpainted volume is sliced under original logic
- Color patch mode and original mode can be mixed per object

---

# FOrcaSlicer — 灵活版 OrcaSlicer — 开发路线图
本仓库托管 [FOrcaSlicer](https://github.com/jiyang1018/FOrcaSlicer) 的交互式开发路线图，项目源代码位于该仓库。

## 开发路线图
查看进度、设计决策和实现细节：
👉 **[查看交互式路线图](https://jiyang1018.github.io/FOrcaSlicer-roadmap/)**

## 关于本项目
[FOrcaSlicer](https://github.com/jiyang1018/FOrcaSlicer) 是 [Snapmaker OrcaSlicer](https://github.com/SoftFever/OrcaSlicer) 的分支版本，为 Snapmaker U1 四头打印机添加混合挤出口尺寸打印支持。Snapmaker U1 支持 4 个独立工作头，每个挤出口直径不同（如 0.2mm、0.4mm、0.6mm、0.8mm）。原版 Snapmaker OrcaSlicer 同步所有挤出口为相同尺寸。FOrcaSlicer 对切片引擎进行了以下扩展：
- 支持每个工作头独立配置挤出口直径
- 在多材料标签页中，将"外墙（OW）"和"内壁（IW）"从"总墙壁"中独立拆分
- 外墙、内壁、填充、实心填充及换料塔可分别指定不同尺寸挤出口
- 打印前通过挤出口验证对话框确认配置
- 预览中的打印线宽反映每个挤出机的实际挤出口直径
- 新增仅外壳着色模式：上色时，仅该面最外层 N 圈壁会由涂色耗材打印
- 支持逐对象、逐耗材着色区域路径数
- 未涂色区域按原始逻辑切片
- 外壳着色模式与原始模式可在同一实体上混合使用