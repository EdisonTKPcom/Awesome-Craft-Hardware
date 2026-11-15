<div align="center">

# Awesome Craft Hardware [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of open-source tools for PCB, FPGA, ASIC and chip design.

![Tools](https://img.shields.io/badge/tools-35-6366f1?style=for-the-badge)
[![Categories](https://img.shields.io/badge/categories-8-0ea5e9?style=for-the-badge)](#contents)
[![Combined stars](https://img.shields.io/badge/combined_stars-20.0k-f59e0b?style=for-the-badge&logo=github)](#-leaderboard)
[![Stars](https://img.shields.io/github/stars/EdisonTKPcom/Awesome-Craft-Hardware?style=for-the-badge&color=22c55e)](https://github.com/EdisonTKPcom/Awesome-Craft-Hardware/stargazers)
[![Last commit](https://img.shields.io/github/last-commit/EdisonTKPcom/Awesome-Craft-Hardware?style=for-the-badge&color=ec4899)](https://github.com/EdisonTKPcom/Awesome-Craft-Hardware/commits/main)

</div>

This list separates individual EDA tools from RTL-to-GDSII flows and from process design kits (PDKs). Official vendor FPGA and ASIC toolchains are proprietary and are not listed. Community bitstream projects are unofficial and incomplete on some families, and they do not grant a licence to vendor IP. Open PDKs still have foundry or shuttle-program terms. Check each project licence, including bundled components such as OpenSTA inside OpenROAD.

Related lists: [Awesome Craft](https://github.com/EdisonTKPcom/Awesome-Craft).

## Contents

- [Dashboard](#dashboard)
- [PCB design](#pcb-design)
- [Circuit simulation](#circuit-simulation)
- [HDL, simulation and formal](#hdl-simulation-and-formal)
- [FPGA implementation](#fpga-implementation)
- [ASIC and layout tools](#asic-and-layout-tools)
- [RTL-to-GDSII flows](#rtl-to-gdsii-flows)
- [Open PDKs](#open-pdks)
- [Packaged distributions](#packaged-distributions)

## Dashboard

<table>
<tr>
<td align="center"><h2>35</h2>listed projects</td>
<td align="center"><h2>8</h2>categories</td>
<td align="center"><h2>20.0k</h2>combined GitHub stars</td>
<td align="center"><h2>5.3k</h2>combined forks</td>
<td align="center"><h2>10/11</h2>pushed in the last 30 days</td>
<td align="center"><h2>5</h2>languages</td>
</tr>
</table>

Stats snapshot taken on 2026-11-15 from the GitHub API, for GitHub-hosted repositories only. Official documentation and other non-GitHub entries are listed but have no stars, forks or push dates. Star badges next to GitHub entries update live.

### 🏆 Leaderboard

<table>
<tr><th>Rank</th><th>Project</th><th>Kind</th><th align="right">Stars</th><th></th></tr>
<tr><td align="center">🥇</td><td><b>Yosys</b></td><td>RTL synthesis</td><td align="right">4.9k</td><td><code>████████████████████</code></td></tr>
<tr><td align="center">🥈</td><td><b>Verilator</b></td><td>HDL simulator</td><td align="right">4.1k</td><td><code>█████████████████</code></td></tr>
<tr><td align="center">🥉</td><td><b>OpenROAD</b></td><td>Place and route</td><td align="right">3.3k</td><td><code>█████████████</code></td></tr>
<tr><td align="center">4</td><td><b>OpenLane</b></td><td>ASIC flow</td><td align="right">2.0k</td><td><code>████████</code></td></tr>
<tr><td align="center">5</td><td><b>nextpnr</b></td><td>Place and route</td><td align="right">1.8k</td><td><code>███████</code></td></tr>
<tr><td align="center">6</td><td><b>Project IceStorm</b></td><td>Bitstream docs</td><td align="right">1.2k</td><td><code>█████</code></td></tr>
<tr><td align="center">7</td><td><b>OpenROAD Flow Scripts</b></td><td>ASIC flow</td><td align="right">808</td><td><code>███</code></td></tr>
<tr><td align="center">8</td><td><b>Magic</b></td><td>Layout editor</td><td align="right">729</td><td><code>███</code></td></tr>
<tr><td align="center">9</td><td><b>SymbiYosys</b></td><td>Formal verification</td><td align="right">570</td><td><code>██</code></td></tr>
<tr><td align="center">10</td><td><b>Project Trellis</b></td><td>Bitstream docs</td><td align="right">477</td><td><code>██</code></td></tr>
</table>


### Stars by category

```mermaid
pie showData
    title Combined GitHub stars by category
    "PCB design" : 0
    "Circuit simulation" : 0
    "HDL, simulation and formal" : 9546
    "FPGA implementation" : 3465
    "ASIC and layout tools" : 4173
    "RTL-to-GDSII flows" : 2815
    "Open PDKs" : 0
    "Packaged distributions" : 0
```

### Licences

![Custom](https://img.shields.io/badge/Custom-6-64748b?style=flat-square) ![ISC](https://img.shields.io/badge/ISC-3-64748b?style=flat-square) ![BSD-3-Clause](https://img.shields.io/badge/BSD--3--Clause-1-64748b?style=flat-square) ![Apache-2.0](https://img.shields.io/badge/Apache--2.0-1-64748b?style=flat-square)

"Custom" or "None" means GitHub could not match a standard SPDX licence, often because of extra terms or an undeclared licence. Read the project licence before you use it commercially.

## PCB design

- [Horizon EDA](https://github.com/horizon-eda/horizon) - A schematic and PCB tool with a pool-based library workflow. ![Stars](https://img.shields.io/github/stars/horizon-eda/horizon?style=flat-square&label=%E2%AD%90)
- [KiCad](https://www.kicad.org/) - A cross-platform EDA suite for schematic capture and PCB layout. The program is GPL-3.0-or-later; official libraries use CC-BY-SA 4.0.
- [LibrePCB](https://github.com/LibrePCB/LibrePCB) - A schematic and PCB editor with a consistent project library format. ![Stars](https://img.shields.io/github/stars/LibrePCB/LibrePCB?style=flat-square&label=%E2%AD%90)

## Circuit simulation

- [ngspice](https://ngspice.sourceforge.io/) - A SPICE-class circuit simulator used standalone and behind other schematic tools. Licence commonly given as BSD-3-Clause; confirm in the source distribution.
- [Xschem](https://github.com/StefanSchippers/xschem) - A schematic editor often used in open analog flows with ngspice and Magic or KLayout. ![Stars](https://img.shields.io/github/stars/StefanSchippers/xschem?style=flat-square&label=%E2%AD%90)
- [Xyce](https://github.com/Xyce/Xyce) - A parallel analog circuit simulator from Sandia National Laboratories, aimed at larger netlists. ![Stars](https://img.shields.io/github/stars/Xyce/Xyce?style=flat-square&label=%E2%AD%90)

## HDL, simulation and formal

- [cocotb](https://github.com/cocotb/cocotb) - A Python framework for writing HDL testbenches that talk to simulators through VPI, VHPI and similar interfaces. ![Stars](https://img.shields.io/github/stars/cocotb/cocotb?style=flat-square&label=%E2%AD%90)
- [GHDL](https://github.com/ghdl/ghdl) - A VHDL analyzer, compiler and simulator, with experimental synthesis paths. ![Stars](https://img.shields.io/github/stars/ghdl/ghdl?style=flat-square&label=%E2%AD%90)
- [GTKWave](https://github.com/gtkwave/gtkwave) - A waveform viewer for VCD, FST and related simulation dumps. ![Stars](https://img.shields.io/github/stars/gtkwave/gtkwave?style=flat-square&label=%E2%AD%90)
- [Icarus Verilog](https://github.com/steveicarus/iverilog) - A Verilog compiler and simulator. ![Stars](https://img.shields.io/github/stars/steveicarus/iverilog?style=flat-square&label=%E2%AD%90)
- [Surfer](https://github.com/surfer-project/surfer) - A waveform viewer with a modern interface. ![Stars](https://img.shields.io/github/stars/surfer-project/surfer?style=flat-square&label=%E2%AD%90)
- [SymbiYosys](https://github.com/YosysHQ/sby) - A front-end for Yosys-based formal verification such as bounded model checking. Solver backends have their own licences. ![Stars](https://img.shields.io/github/stars/YosysHQ/sby?style=flat-square&label=%E2%AD%90)
- [Verilator](https://github.com/verilator/verilator) - Compiles synthesizable Verilog and SystemVerilog into cycle-accurate C++ or SystemC models. Licence is LGPL-3.0-only or Artistic-2.0. ![Stars](https://img.shields.io/github/stars/verilator/verilator?style=flat-square&label=%E2%AD%90)
- [Yosys](https://github.com/YosysHQ/yosys) - An RTL synthesis framework with Verilog and synthesizable SystemVerilog support, used in FPGA and ASIC flows. ![Stars](https://img.shields.io/github/stars/YosysHQ/yosys?style=flat-square&label=%E2%AD%90)

## FPGA implementation

- [Amaranth](https://github.com/amaranth-lang/amaranth) - A Python-based HDL and toolchain that can target open FPGA flows. ![Stars](https://img.shields.io/github/stars/amaranth-lang/amaranth?style=flat-square&label=%E2%AD%90)
- [LiteX](https://github.com/enjoy-digital/litex) - A framework for building SoCs from LiteX cores and putting them on FPGA boards. Individual cores and board files may carry their own terms. ![Stars](https://img.shields.io/github/stars/enjoy-digital/litex?style=flat-square&label=%E2%AD%90)
- [nextpnr](https://github.com/YosysHQ/nextpnr) - A timing-driven, portable FPGA place-and-route tool that uses architecture databases from the bitstream projects below. This is not a drop-in replacement for vendor P&R on every family. ![Stars](https://img.shields.io/github/stars/YosysHQ/nextpnr?style=flat-square&label=%E2%AD%90)
- [openFPGALoader](https://github.com/trabucayre/openFPGALoader) - A utility for programming many FPGA boards over common debug adapters. ![Stars](https://img.shields.io/github/stars/trabucayre/openFPGALoader?style=flat-square&label=%E2%AD%90)
- [Project IceStorm](https://github.com/YosysHQ/icestorm) - Tools and documentation for Lattice iCE40 bitstreams, typically used with Yosys and nextpnr. This is community architecture documentation, not a vendor IDE. ![Stars](https://img.shields.io/github/stars/YosysHQ/icestorm?style=flat-square&label=%E2%AD%90)
- [Project Oxide](https://github.com/gatecat/prjoxide) - Documentation and tooling for Lattice Nexus devices, intended for use with nextpnr. Coverage and device testing are still incomplete. ![Stars](https://img.shields.io/github/stars/gatecat/prjoxide?style=flat-square&label=%E2%AD%90)
- [Project Trellis](https://github.com/YosysHQ/prjtrellis) - Documentation and databases for Lattice ECP5 bitstreams, used with nextpnr. ![Stars](https://img.shields.io/github/stars/YosysHQ/prjtrellis?style=flat-square&label=%E2%AD%90)
- [Project X-Ray](https://github.com/f4pga/prjxray) - Documentation and tooling for the Xilinx 7-series bitstream format. Coverage is incomplete relative to Vivado, and this is not official AMD or Xilinx support. ![Stars](https://img.shields.io/github/stars/f4pga/prjxray?style=flat-square&label=%E2%AD%90)

## ASIC and layout tools

- [KLayout](https://github.com/KLayout/klayout) - A high-capacity layout viewer and editor with DRC and LVS scripting, often used for GDS and OASIS inspection. ![Stars](https://img.shields.io/github/stars/KLayout/klayout?style=flat-square&label=%E2%AD%90)
- [Magic](https://github.com/RTimothyEdwards/magic) - A layout editor and DRC tool long used in academic and open ASIC flows. ![Stars](https://img.shields.io/github/stars/RTimothyEdwards/magic?style=flat-square&label=%E2%AD%90)
- [Netgen](https://github.com/RTimothyEdwards/netgen) - A layout-versus-schematic comparison tool, typically paired with Magic. ![Stars](https://img.shields.io/github/stars/RTimothyEdwards/netgen?style=flat-square&label=%E2%AD%90)
- [OpenROAD](https://github.com/The-OpenROAD-Project/OpenROAD) - A physical-design application covering floorplanning, placement, clock-tree synthesis and routing. The project is BSD-3-Clause but bundles OpenSTA, which is GPL-3.0. ![Stars](https://img.shields.io/github/stars/The-OpenROAD-Project/OpenROAD?style=flat-square&label=%E2%AD%90)
- [OpenSTA](https://github.com/parallaxsw/OpenSTA) - A static timing analysis engine that reads Liberty, Verilog, SDC, SPEF and SDF. Licence is GPL-3.0. ![Stars](https://img.shields.io/github/stars/parallaxsw/OpenSTA?style=flat-square&label=%E2%AD%90)

## RTL-to-GDSII flows

- [LibreLane](https://github.com/librelane/librelane) - The maintained successor to Efabless OpenLane 2, an automated RTL-to-GDSII flow around Yosys, OpenROAD, Magic, Netgen and KLayout. This is a flow, not a PDK. ![Stars](https://img.shields.io/github/stars/librelane/librelane?style=flat-square&label=%E2%AD%90)
- [OpenLane](https://github.com/The-OpenROAD-Project/OpenLane) - The earlier Efabless RTL-to-GDSII flow. Treat this as a legacy line unless a project you inherit still depends on it. ![Stars](https://img.shields.io/github/stars/The-OpenROAD-Project/OpenLane?style=flat-square&label=%E2%AD%90)
- [OpenROAD Flow Scripts](https://github.com/The-OpenROAD-Project/OpenROAD-flow-scripts) - A reference RTL-to-GDSII flow that integrates Yosys, OpenROAD and KLayout. ![Stars](https://img.shields.io/github/stars/The-OpenROAD-Project/OpenROAD-flow-scripts?style=flat-square&label=%E2%AD%90)
- [SiliconCompiler](https://github.com/siliconcompiler/siliconcompiler) - A modular hardware build system that can drive open-source and, where the user has licences, proprietary EDA tools. ![Stars](https://img.shields.io/github/stars/siliconcompiler/siliconcompiler?style=flat-square&label=%E2%AD%90)

## Open PDKs

- [GlobalFoundries GF180MCU PDK](https://github.com/google/gf180mcu-pdk) - An open PDK for GlobalFoundries 180 nm MCU process. The repository licence is not a substitute for foundry or shuttle-program rules. ![Stars](https://img.shields.io/github/stars/google/gf180mcu-pdk?style=flat-square&label=%E2%AD%90)
- [IHP Open PDK](https://github.com/IHP-GmbH/IHP-Open-PDK) - Open PDK material from IHP, including the SG13G2 process used in several open analog and RF flows. Read IHP documentation and foundry access terms before use. ![Stars](https://img.shields.io/github/stars/IHP-GmbH/IHP-Open-PDK?style=flat-square&label=%E2%AD%90)
- [SkyWater SKY130 PDK](https://github.com/google/skywater-pdk) - An open PDK for SkyWater 130 nm, widely used with LibreLane and OpenROAD flows. Tape-out still depends on foundry or shuttle-program terms. ![Stars](https://img.shields.io/github/stars/google/skywater-pdk?style=flat-square&label=%E2%AD%90)

## Packaged distributions

- [OSS CAD Suite](https://github.com/YosysHQ/oss-cad-suite-build) - A binary distribution of YosysHQ and related digital-design tools. Bundled tools keep their individual licences. ![Stars](https://img.shields.io/github/stars/YosysHQ/oss-cad-suite-build?style=flat-square&label=%E2%AD%90)

## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

<div align="center">

If this list is useful, give it a ⭐ so others can find it.

</div>
