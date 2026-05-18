# FOrcaSlicer — Flexible OrcaSlicer

A fork of [Snapmaker OrcaSlicer](https://github.com/SoftFever/OrcaSlicer) adding mixed nozzle size printing support for the Snapmaker U1 4-head printer.

## Development Roadmap

Track progress, design decisions, and implementation details:

👉 **[View the interactive roadmap](https://jiyang1018.github.io/FOrcaSlicer-roadmap/)**

## About

The Snapmaker U1 supports 4 independent print heads with different nozzle diameters (e.g. 0.2mm, 0.4mm, 0.6mm, 0.8mm). Stock OrcaSlicer treats all nozzles as the same size. FOrcaSlicer extends the slicer to:

- Route outer wall loops to the fine nozzle and inner wall loops to the coarse nozzle
- Scale line widths per extruder based on actual nozzle diameter
- Allow independent nozzle diameter configuration per head
- Gate printing behind a nozzle verification dialog
- Support per-filament color patch loops (in progress)

---

# FOrcaSlicer — 灵活版 OrcaSlicer

[Snapmaker OrcaSlicer](https://github.com/SoftFever/OrcaSlicer) 的分支版本，为 Snapmaker U1 四头打印机添加混合喷嘴尺寸打印支持。

## 开发路线图

查看进度、设计决策和实现细节：

👉 **[查看交互式路线图](https://jiyang1018.github.io/FOrcaSlicer-roadmap/)**

## 关于本项目

Snapmaker U1 支持 4 个独立打印头，每个喷嘴直径不同（如 0.2mm、0.4mm、0.6mm、0.8mm）。原版 OrcaSlicer 将所有喷嘴视为相同尺寸。FOrcaSlicer 对切片器进行了以下扩展：

- 将外壁循环路由到细喷嘴，内壁循环路由到粗喷嘴
- 根据实际喷嘴直径按挤出机缩放线宽
- 支持每个打印头独立配置喷嘴直径
- 打印前通过喷嘴验证对话框确认配置
- 支持按耗材配置颜色补丁循环数（开发中）
