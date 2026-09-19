# Awesome Development for Retro Computers and Consoles

## Table of Contents

- [Atari ST](#atari-st)
  - [Frameworks and Libraries](#retro-atari-st-frameworks-and-libraries)
  - [Development Tools](#retro-atari-st-development-tools)
    - [Devkits](#retro-atari-st-devkit)
    - [IDEs](#retro-atari-st-ide)
  - [Packers](#retro-atari-st-packers)
  - [Emulators](#retro-atari-st-emulators)
- [Commodore 64](#commodore-64)
  - [Assemblers](#retro-c64-assemblers)
  - [Compilers](#retro-c64-compilers)
- [Commodore Amiga](#commodore-amiga)
  - [Assemblers](#retro-amiga-assemblers)
  - [Linkers](#retro-amiga-linkers)
  - [Source Code](#retro-amiga-source-codes)
    - [Demo Source Code](#retro-amiga-demo-source-codes)
    - [Game Source Code](#retro-amiga-game-source-codes)
    - [Examples](#retro-amiga-examples)
- [Sega Genesis](#sega-genesis)
  - [Assemblers](#retro-sega-genesis-assemblers)
  - [Development Tools](#retro-sega-genesis-development-tools)
    - [Command Line Tools](#retro-sega-genesis-command-line-tools)
    - [Devkits](#retro-sega-genesis-devkit)
    - [IDEs](#retro-sega-genesis-ide)
  - [Hardware](#retro-sega-genesis-hardware)
  - [GUI Tools](#retro-sega-genesis-gui-tools)
  - [Reverse Engineering](#retro-sega-genesis-reverse-engineering)
  - [Source Code](#retro-sega-genesis-source-codes)
    - [Demo Source Code](#retro-sega-genesis-demo-source-codes)
    - [Game Source Code](#retro-sega-genesis-game-source-codes)
    - [Tools and Sound Drivers](#retro-sega-genesis-tools-and-sound-drivers)
- [Super Nintendo (SNES)](#super-nintendo-snes)
  - [Assemblers](#retro-snes-assemblers)
  - [Development Tools](#retro-snes-development-tools)
    - [Command Line Tools](#retro-snes-command-line-tools)
    - [Devkits](#retro-snes-devkit)
  - [Audio Tools and Libraries](#retro-snes-audio-tools-and-libraries)
  - [Emulators](#retro-snes-emulators)
  - [Documentation and Tutorials](#retro-snes-documentation-and-tutorials)
  - [Source Code](#retro-snes-source-codes)
    - [Demo Source Code](#retro-snes-demo-source-codes)
    - [Game Source Code](#retro-snes-game-source-codes)
    - [Examples and Test ROMs](#retro-snes-examples-and-test-roms)

---

## Atari ST

### <a name="retro-atari-st-frameworks-and-libraries"></a>Frameworks and Libraries

*Frameworks and libraries for Atari ST development*

- [GODLIB](https://github.com/ReservoirGods/GODLIB) - A library for Atari ST software with graphics, sprites, audio, input, and system access modules
- [NoExtra Framework](https://github.com/NoExtra-Team/framework) - A 68000 assembly framework for Atari STF/STE with examples and documentation in English and French

### <a name="retro-atari-st-development-tools"></a>Development Tools

#### <a name="retro-atari-st-devkit"></a>Devkits

*Development environments for Atari ST software*

- [Atari ST Toolkit Docker](https://github.com/sidecartridge/atarist-toolkit-docker) - A Docker development environment for Atari ST software with support for Atari Game Tools (AGT)

#### <a name="retro-atari-st-ide"></a>IDEs

- [Atari ST Dev](https://github.com/dgis/vscode-atari-st-dev) - A Visual Studio Code extension for C, C++, and 68k assembly development using GCC/GDB and a modified Hatari emulator

### <a name="retro-atari-st-packers"></a>Packers

*Executable and data compression tools for the Atari ST*

- [GUP](https://github.com/HansWessels/gup) - A data compressor and archiver with ARJ mode 7 support and small, fast depackers, originating from the Atari ST and Amiga scene
- [L-Packer](https://github.com/arnaud-carre/L-Packer) - An Atari and Amiga executable packer aimed at 64K demos, with a raw data mode; full source code is planned for version 1.0
- [PackFire](https://github.com/hitchhikr/packfire) - A Windows-based executable packer for Atari ST and other platforms, aimed at 64K intros and including a 68000 depacker
- [STrinkler](https://github.com/arnaud-carre/STrinkler) - An Atari ST port of Shrinkler for executables and raw data, aimed at 4 KiB intros
- [UPX](https://github.com/upx/upx) - An executable packer with Atari/TOS support; packing removes debug information

### <a name="retro-atari-st-emulators"></a>Emulators

*Emulators for running and testing Atari ST software*

- [Hatari](https://github.com/hatari/hatari) - An Atari ST/STE/TT/Falcon emulator with an integrated debugger; this repository is a mirror
- [NeoST](https://github.com/habib256/neost) - An Atari ST/STE emulator with breakpoints, watchpoints, symbols, and hardware views, also available as a WebAssembly build
- [Steem Engine](https://github.com/steem-engine/steem-engine) - Historical source code for the Steem 3.2 Atari ST emulator from 2004; the Steem SSE fork is hosted on SourceForge

---

## Commodore 64

### <a name="retro-c64-assemblers"></a>Assemblers

*Tools to program assembler on the C64*

- [C6510](https://csdb.dk/release/?id=219569&show=summary) - A cross assembler with LUA macro interface
- [Kick Assembler](http://theweb.dk/KickAssembler/Main.html) - A cross assembler written in Java to produce 6502 code

### <a name="retro-c64-compilers"></a>Compilers

*Compilers for the C64 platform*

- [CC65](https://cc65.github.io/) - A compiler to produce 6502 code

---

## Commodore Amiga

### <a name="retro-amiga-assemblers"></a>Assemblers

*Tools to program assembler on the Commodore Amiga*

- [VASM](http://sun.hasenbraten.de/vasm/index.php?view=main) - A cross assembler to produce m68k code

### <a name="retro-amiga-linkers"></a>Linkers

*Linkers for the Commodore Amiga*

- [VLINK](http://sun.hasenbraten.de/vlink/index.php?view=main) - A portable linker to produce Amiga code

### <a name="retro-amiga-source-codes"></a>Source Code

*Source code for classic Amiga games, demos, and programming examples*

#### <a name="retro-amiga-demo-source-codes"></a>Demo Source Code

- [Amiga Demos in 68000 ASM](https://github.com/smart-fun/Amiga) - Assembly sources for intros, scrollers, a rotozoom effect, and a music disk, with instructions for SEKA and AsmOne
- [demarination](https://github.com/wbcbz7/demarination) - An Amiga OCS 64K intro from Revision 2024, written mainly in C; the README documents a memory corruption bug after repeated runs
- [Ghostown and Whelpz Demoscene Sources](https://github.com/cahirwpz/demoscene) - Amiga OCS demo and effect sources with a framework and build tools; binary assets require Git LFS
- [Parcade](https://github.com/jonathanbennett73/amiga-parcade) - An Amiga 500 intro in 68000 assembly with sine scrollers, blitter objects, and vector effects
- [Planet Rocklobster](https://github.com/AxisOxy/Planet-Rocklobster) - Source code for Oxyron's Amiga OCS demo, with technical explanations of its rendering effects

#### <a name="retro-amiga-game-source-codes"></a>Game Source Code

- [Alien Breed 3D II](https://github.com/mheyer32/alienbreed3d2) - A maintained version of The Killing Grounds engine with bug fixes and performance improvements, compatible with original game data and mods
- [Blocky Skies](https://github.com/alpine9000/blockyskies) - Game source and development tools for a classic Amiga game designed for a 68000 and 512 KB of RAM
- [Citadel](https://github.com/pawelmat/Amiga-Citadel) - Original code, game data, and editor for the 1995 Amiga game; some assets, including intro animations, are missing
- [RC (Rally Cross)](https://github.com/ResistanceVault/rc) - Source code for a multiplayer racing game for classic Amigas, with computer-controlled cars
- [The Faery Tale Adventure](https://github.com/viridia/faery-tale-amiga) - Original 1987 Amiga game source in Aztec C and 68000 assembly, published by its author as a historical reference

#### <a name="retro-amiga-examples"></a>Examples

*Source code for learning Amiga hardware programming*

- [Amiga 68K Examples](https://github.com/pararaum/amigaexamples) - Examples and tutorials in 68K assembly and C, including demos and scrollers
- [Amiga Assembly Development Workflow](https://github.com/neildavis/amiga_asmdev_workflow) - A Linux build workflow with an assembly demo using bitplanes, blitter objects, sprites, and ZX0 decompression

---

## Sega Genesis

### <a name="retro-sega-genesis-assemblers"></a>Assemblers

*Tools to program assembler on the Sega Genesis*

- [VASM](http://sun.hasenbraten.de/vasm/index.php?view=main) - A cross assembler to produce m68k code

### <a name="retro-sega-genesis-development-tools"></a>Development Tools

#### <a name="retro-sega-genesis-command-line-tools"></a>Command Line Tools

*Command line tools for Sega Genesis development*

- [Sega Genesis Rom Checksum Utility](https://github.com/mrhappyasthma/Sega-Genesis-Checksum-Utility) - Python scripts to correct the ROM checksum
- [SVP Development Tools](https://github.com/jdesiloniz/svpdev) - Development tools for the SVP chip, found in Virtua Racing cartridges

#### <a name="retro-sega-genesis-devkit"></a>Devkits

*Complete toolchains to develop Sega Genesis programs*

- [Marsdev](https://github.com/andwn/marsdev) - A complete cross-platform development kit for Genesis / 32x
- [SGDK](https://github.com/Stephane-D/SGDK) - A complete cross-platform development kit for Sega Genesis / 32x

#### <a name="retro-sega-genesis-ide"></a>IDEs

- [genesis-code](https://github.com/zerasul/genesis-code) - Visual Studio Code Extension for Sega Genesis/Mega Drive development

### <a name="retro-sega-genesis-hardware"></a>Hardware

*Hardware and firmware for the Sega Genesis*

- [Genesis Dumper](https://github.com/tonyp7/GenDumper) - Open Source hardware to dump cartridges
- [Opendrive-Genesis](https://github.com/soniccd123/OpenDrive-Genesis) - Open Hardware Flashcard for the Sega Genesis/32X

### <a name="retro-sega-genesis-gui-tools"></a>GUI Tools

*GUI tools for the Sega Genesis*

- [Codemasters Image Converter](https://github.com/lab313ru/CodemastersBinImage) - Extract and insert graphics in Codemasters games
- [Mega Happy Sprite](https://github.com/sigflup/Mega-Happy-Sprite) - Sprite/Scrollpane editor for the Sega Genesis
- [ZorroTracker](https://github.com/ZorroTrackerDev/ZorroTracker) - Music Tracker created in Electron

### <a name="retro-sega-genesis-reverse-engineering"></a>Reverse Engineering

*Tools to reverse engineer the Sega Genesis platform*

- [bn-genesis](https://github.com/zznop/bn-genesis) - Plugins for Binary Ninja to reverse engineer Sega Genesis ROMs
- [Ghidra SMD loader](https://github.com/lab313ru/ghidra_sega_ldr) - Sega Genesis SMD loader for Ghidra
- [SMD IDA Tools](https://github.com/lab313ru/smd_ida_tools) - IDA plugin for SMD files
- [Scripts for IDA](https://github.com/zznop/ida-genesis) - Scripts to support Sega Genesis reverse engineering

### <a name="retro-sega-genesis-source-codes"></a>Source Code

*Source code for the Sega Genesis platform*

#### <a name="retro-sega-genesis-demo-source-codes"></a>Demo Source Code

- [Demo Malabars-Bumper](https://github.com/ResistanceVault/demo-Malabars-Bumper) - Source code for a Sega Genesis demo
- [Demo Masiaka](https://github.com/ResistanceVault/demo-Masiaka) - Source code for a Sega Genesis demo
- [Demo Zsenilla](https://github.com/ResistanceVault/demo-Zsenilia) - Source code for a Sega Genesis demo

#### <a name="retro-sega-genesis-game-source-codes"></a>Game Source Code

*Source code for games on the Sega Genesis platform*

- [L'Abbaye des Morts](https://github.com/moon-watcher/AbbayeMD) - Source code for a Sega Genesis game
- [Sonic the Hedgehog 1 - C port](https://github.com/cuckydev/SoniCPort) - Source code for a C port of Sonic the Hedgehog 1

#### <a name="retro-sega-genesis-tools-and-sound-drivers"></a>Tools and Sound Drivers

- [GEMS](https://github.com/realmonster/GEMS) - Sega Genesis GEMS Sound Driver
- [Genesis Debugger](https://github.com/flamewing/genesis-debugger) - Source code for a debugger on Sega Genesis
- [mdtracker](https://github.com/corthax/mdtracker) - Source code for a native Sega Genesis music tracker

---

## Super Nintendo (SNES)

### <a name="retro-snes-assemblers"></a>Assemblers

*Assemblers for SNES programs and coprocessors*

- [Asar](https://github.com/RPGHacker/asar) - An assembler for creating SNES ROMs and applying patches, with 65c816, SPC700, and Super FX support
- [bass](https://github.com/ARM9/bass) - A macro assembler for multiple architectures, including the SNES; this fork includes Super FX/GSU support
- [WLA-DX](https://github.com/vhelin/wla-dx) - A cross assembler and linker package with 65816, SPC700, and Super FX support

### <a name="retro-snes-development-tools"></a>Development Tools

#### <a name="retro-snes-command-line-tools"></a>Command Line Tools

*Asset conversion tools for SNES development*

- [SuperFamiconv](https://github.com/Optiroc/SuperFamiconv) - A command line converter for palettes, tiles, and tilemaps, with support for SNES graphics modes including Mode 7

#### <a name="retro-snes-devkit"></a>Devkits

*Toolchains and libraries for SNES development*

- [PVSnesLib](https://github.com/alekmaul/pvsneslib) - A C and assembly development kit with a compiler, linker, hardware libraries, asset tools, and examples
- [SNESKIT](https://github.com/mukunda-/sneskit) - A low-level SNES development kit with build tools, project templates, and a SNESMOD example

### <a name="retro-snes-audio-tools-and-libraries"></a>Audio Tools and Libraries

*Music and sound effect libraries for the SNES*

- [SNESMOD](https://github.com/mukunda-/snesmod) - An audio library supporting Impulse Tracker music and sound effect streaming to the SPC700
- [Terrific Audio Driver](https://github.com/undisbeliever/terrific-audio-driver) - A homebrew audio driver with Music Macro Language (MML) support for music and sound effects

### <a name="retro-snes-emulators"></a>Emulators

*Emulators for running and testing SNES software*

- [bsnes](https://github.com/bsnes-emu/bsnes) - A SNES emulator with coprocessor emulation, frame advance, and save states
- [Mesen Community Edition](https://github.com/nesdev-org/MesenCE) - A community-maintained fork of Mesen with SNES support for Windows, Linux, and macOS

### <a name="retro-snes-documentation-and-tutorials"></a>Documentation and Tutorials

*Hardware references and programming guides*

- [PVSnesLib Wiki](https://github.com/alekmaul/pvsneslib/wiki) - Installation guides and tutorials covering backgrounds, sprites, audio, input, and game engines
- [Super Famicom Development Wiki](https://wiki.superfamicom.org/) - Technical references for SNES hardware, graphics, SPC700 audio, and cartridge expansion chips

### <a name="retro-snes-source-codes"></a>Source Code

*Source code for the SNES platform*

#### <a name="retro-snes-demo-source-codes"></a>Demo Source Code

- [Cream Demo](https://github.com/HackerHarry/creamdemo) - Assembly source for a SNES demo from 1994; binary music data is not included
- [Demo-Twistit](https://github.com/ResistanceVault/demo-twistit) - Source code for a SNES demo

#### <a name="retro-snes-game-source-codes"></a>Game Source Code

*Source code for SNES games and playable game demos*

- [Castle Platformer](https://github.com/undisbeliever/castle_platformer) - A platformer engine and demo with interactive tiles, animated sprites, and dynamic maps, built with ca65
- [DOOM-FX](https://github.com/RandalLinden/DOOM-FX) - Source code for the SNES port of Doom using the Super FX GSU2A, released by Randal Linden
- [Horizontal Shooter](https://github.com/undisbeliever/horizontal-shooter) - A shooter demo using the entity and MetaSprite systems of the UnTech Game Engine
- [Skipp and Friends](https://github.com/mukunda-/skipp-and-friends) - Source code, level data, and development tools for the SNES game
- [Super Sudoku](https://github.com/raphnet/super_sudoku) - A Sudoku game in assembly with a solver, hints, and support for standard controllers and the NTT Data Keypad
- [Sure Instinct](https://github.com/BenjaminSchulte/SureInstinct) - Game source code with the Aoba engine, level editor, and music tools; building requires FMA and Qt5 and has only been tested on Linux
- [Unnamed SNES Engine](https://github.com/undisbeliever/unnamed-snes-engine) - A single-screen top-down game demo and engine using Wiz and the Terrific Audio Driver

#### <a name="retro-snes-examples-and-test-roms"></a>Examples and Test ROMs

*Source code for learning SNES programming and testing hardware behavior*

- [Peter Lemon's SNES Examples](https://github.com/PeterLemon/SNES) - Assembly examples covering graphics, input, SPC700 audio, and Super FX programming using bass
- [SNES Stuff](https://github.com/bbbradsmith/SNES_stuff) - Small programs demonstrating graphics modes, color math, controllers, and SPC700 audio
- [SNES Test ROMs](https://github.com/undisbeliever/snes-test-roms) - Test ROM source code for investigating SNES hardware behavior
