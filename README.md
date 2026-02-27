# brisma-plugins

Claude Code plugin marketplace by brisma.

## Installation

```bash
/plugin marketplace add brisma/claude-plugins
```

## Available Plugins

| Plugin | Version | Description | License |
|--------|---------|-------------|---------|
| `psx-spx` | 1.0.0 | Complete PSX hardware reference archived from psx-spx.consoledev.net. CPU, GPU, memory, DMA, CDROM, SPU, GTE, MDEC, controllers, BIOS, and more. | CC0-1.0 |
| `ghidra` | 1.1.0 | GhidraMCP integration: MCP server configuration and reverse engineering reference. Decompile, analyze, and annotate binaries in Ghidra via 48 MCP tools. | Apache-2.0 |
| `duckstation` | 1.0.0 | DuckStation PS1 emulator MCP integration: runtime debugging, memory inspection, GPU/SPU state, breakpoints, VRAM watches, controller automation. 95 MCP tools. | GPL-3.0 |
| `armips` | 1.1.0 | armips assembler reference: MIPS (R3000/R4000/Allegrex/RSP/EE) and ARM (ARM7/ARM9/THUMB) instruction sets, directives, expressions, macros, ROM hacking workflows, and project scaffolding. | MIT |
| `mesen2` | 1.0.0 | Mesen2 multi-system emulator MCP integration: runtime debugging, memory, disassembly, tracing, ROM hacking, text search. 75 MCP tools for NES/SNES/GB/GBA/PCE/SMS/WS. | GPL-3.0 |

### Install a plugin

```bash
/plugin install psx-spx@brisma-plugins
/plugin install ghidra@brisma-plugins
/plugin install duckstation@brisma-plugins
/plugin install armips@brisma-plugins
/plugin install mesen2@brisma-plugins
```
