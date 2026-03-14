# sadnescity-plugins

Claude Code plugin marketplace by brisma.

## Installation

```bash
/plugin marketplace add sadnescity/claude-plugins
```

## Available Plugins

| Plugin | Version | Description | License |
|--------|---------|-------------|---------|
| `psx-spx` | 1.0.0 | Complete PSX hardware reference archived from psx-spx.consoledev.net. CPU, GPU, memory, DMA, CDROM, SPU, GTE, MDEC, controllers, BIOS, and more. | CC0-1.0 |
| `ghidra` | 1.1.0 | GhidraMCP integration: MCP server configuration and reverse engineering reference. Decompile, analyze, and annotate binaries in Ghidra via 48 MCP tools. | Apache-2.0 |
| `duckstation` | 1.1.0 | DuckStation PS1 emulator MCP integration: runtime debugging, memory inspection, GPU/SPU state, breakpoints, VRAM watches, controller automation. 95 MCP tools. | GPL-3.0 |
| `armips` | 1.1.0 | armips assembler reference: MIPS (R3000/R4000/Allegrex/RSP/EE) and ARM (ARM7/ARM9/THUMB) instruction sets, directives, expressions, macros, ROM hacking workflows, and project scaffolding. | MIT |
| `mesen2` | 1.0.0 | Mesen2 multi-system emulator MCP integration: runtime debugging, memory, disassembly, tracing, ROM hacking, text search. 75 MCP tools for NES/SNES/GB/GBA/PCE/SMS/WS. | GPL-3.0 |
| `ppsspp` | 2.1.0 | PPSSPP PSP emulator MCP integration: CPU debugging, GPU/GE inspection, memory watchpoints, framebuffer dumps, texture/CLUT/depth/stencil inspection, GE display list disassembly, GE breakpoints. 36 MCP tools. | GPL-2.0 |

### Install a plugin

```bash
/plugin install psx-spx@sadnescity-plugins
/plugin install ghidra@sadnescity-plugins
/plugin install duckstation@sadnescity-plugins
/plugin install armips@sadnescity-plugins
/plugin install mesen2@sadnescity-plugins
/plugin install ppsspp@sadnescity-plugins
```
