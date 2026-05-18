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
