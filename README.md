# Awesome Development for Retro Computers and Consoles

## Table of Contents

- [Atari ST](#atari-st)
  - [Assemblers](#retro-atari-st-assemblers)
  - [C and C++ Toolchains](#retro-atari-st-c-and-cpp-toolchains)
  - [Frameworks and Libraries](#retro-atari-st-frameworks-and-libraries)
  - [Development Tools](#retro-atari-st-development-tools)
    - [Devkits](#retro-atari-st-devkit)
    - [IDEs](#retro-atari-st-ide)
  - [Graphics Tools](#retro-atari-st-graphics-tools)
  - [Music Tools](#retro-atari-st-music-tools)
  - [Packers](#retro-atari-st-packers)
  - [Emulators](#retro-atari-st-emulators)
  - [Source Code](#retro-atari-st-source-codes)
    - [Cracktro Source Code](#retro-atari-st-cracktro-source-codes)
    - [Game Source Code](#retro-atari-st-game-source-codes)
- [Commodore 64](#commodore-64)
  - [Assemblers](#retro-c64-assemblers)
  - [C and C++ Toolchains](#retro-c64-c-and-cpp-toolchains)
  - [Graphics Tools](#retro-c64-graphics-tools)
  - [Music Tools](#retro-c64-music-tools)
  - [Source Code](#retro-c64-source-codes)
    - [Cracktro Source Code](#retro-c64-cracktro-source-codes)
- [Commodore Amiga](#commodore-amiga)
  - [Assemblers](#retro-amiga-assemblers)
  - [C and C++ Toolchains](#retro-amiga-c-and-cpp-toolchains)
  - [Linkers](#retro-amiga-linkers)
  - [Graphics Tools](#retro-amiga-graphics-tools)
  - [Music Tools](#retro-amiga-music-tools)
  - [Source Code](#retro-amiga-source-codes)
    - [Demo Source Code](#retro-amiga-demo-source-codes)
    - [Cracktro Source Code](#retro-amiga-cracktro-source-codes)
    - [Game Source Code](#retro-amiga-game-source-codes)
    - [Examples](#retro-amiga-examples)
- [Sega Genesis](#sega-genesis)
  - [Assemblers](#retro-sega-genesis-assemblers)
  - [C and C++ Toolchains](#retro-sega-genesis-c-and-cpp-toolchains)
  - [Development Tools](#retro-sega-genesis-development-tools)
    - [Command Line Tools](#retro-sega-genesis-command-line-tools)
    - [IDEs](#retro-sega-genesis-ide)
  - [Hardware](#retro-sega-genesis-hardware)
  - [Graphics Tools](#retro-sega-genesis-graphics-tools)
  - [Music Tools](#retro-sega-genesis-music-tools)
  - [Reverse Engineering](#retro-sega-genesis-reverse-engineering)
  - [Source Code](#retro-sega-genesis-source-codes)
    - [Demo Source Code](#retro-sega-genesis-demo-source-codes)
    - [Game Source Code](#retro-sega-genesis-game-source-codes)
    - [Tools and Sound Drivers](#retro-sega-genesis-tools-and-sound-drivers)
- [Super Nintendo (SNES)](#super-nintendo-snes)
  - [Assemblers](#retro-snes-assemblers)
  - [C and C++ Toolchains](#retro-snes-c-and-cpp-toolchains)
  - [Development Tools](#retro-snes-development-tools)
    - [Devkits](#retro-snes-devkit)
  - [Graphics Tools](#retro-snes-graphics-tools)
  - [Music Tools](#retro-snes-music-tools)
    - [Audio Libraries and Drivers](#retro-snes-audio-libraries-and-drivers)
  - [Emulators](#retro-snes-emulators)
  - [Documentation and Tutorials](#retro-snes-documentation-and-tutorials)
  - [Source Code](#retro-snes-source-codes)
    - [Demo Source Code](#retro-snes-demo-source-codes)
    - [Cracktro and Trainer Intro Source Code](#retro-snes-cracktro-source-codes)
    - [Game Source Code](#retro-snes-game-source-codes)
    - [Examples and Test ROMs](#retro-snes-examples-and-test-roms)

---

## Atari ST

### <a name="retro-atari-st-assemblers"></a>Assemblers

*Assemblers for Atari ST programs*

- [RMAC](https://rmac.is-slick.com/) - A macro assembler with 68000 support and Atari ST executable output, available for modern host systems and the Atari ST
- [VASM](http://sun.hasenbraten.de/vasm/index.php?view=main) - A portable assembler with a 68000 backend, Motorola syntax, and Atari TOS executable output

### <a name="retro-atari-st-c-and-cpp-toolchains"></a>C and C++ Toolchains

*C and C++ compilers and runtime support for Atari ST software*

- [MiNT GCC](https://github.com/freemint/m68k-atari-mint-gcc) - GCC with C and C++ support for Atari TOS/MiNT targets; use the matching binutils and target libraries to complete the toolchain
- [vbcc](http://sun.hasenbraten.de/vbcc/) - An optimizing C compiler with Atari TOS and MiNT target packages, available for native and cross-development; does not compile C++

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

### <a name="retro-atari-st-graphics-tools"></a>Graphics Tools

*Pixel editors and image converters for Atari ST graphics*

- [Dithertron](https://github.com/sehugg/dithertron) - A browser image converter with a 320x200, 16-color Atari ST preset; exports PNG images that need conversion to a native ST format
- [GrafX2](https://grafx2.gitlab.io/grafX2/) - A pixel editor for modern systems, with Atari MiNT builds and support for reading and writing Degas PI1/PC1 and NeoChrome images

### <a name="retro-atari-st-music-tools"></a>Music Tools

*Music editors for the Atari ST's YM2149 sound chip*

- [Arkos Tracker](https://www.julien-nevo.com/arkostracker/) - A desktop AY/YM tracker with an AKY replay routine for Atari ST; the ST player does not support sound effects
- [maxYMiser](https://preromanbritain.com/maxymiser/) - A native Atari ST YM2149 tracker with instrument editing, MIDI support, and a replay routine; DMA sample features require an STE or compatible machine

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

### <a name="retro-atari-st-source-codes"></a>Source Code

#### <a name="retro-atari-st-cracktro-source-codes"></a>Cracktro Source Code

- [Ghostbusters Intro and Cracktro](https://github.com/diegoparrilla/atarist-ghostbusters-demo) - Original 1989 Atari ST assembly sources by Canal 23, with separate cracktro and sampled-audio demo builds and a Docker toolchain workflow
- [Orion's Cracktros, CD Intros, and Demos](https://github.com/orionfuzion/intros) - Original 68000 assembly sources by Orion of The Replicants and Fuzion, with graphics, music, and Devpac build instructions

#### <a name="retro-atari-st-game-source-codes"></a>Game Source Code

- [Alpha Waves](http://cc3d.free.fr/Alpha-Waves.zip) - Original Atari ST assembly sources and GFA BASIC development tools by Christophe de Dinechin, distributed as a ZIP archive
- [Amberstar](https://github.com/jhorneman/amberstar) - Historical sources and development files for Thalion's 1992 RPG; the incomplete snapshot includes tokenized GFA Assembler files and cannot build the full game
- [Return of Medusa (Rings of Medusa 2)](https://github.com/bubeck/rings-of-medusa/tree/original-sources) - Original 1991 Atari ST and Amiga sources in C and assembly, with graphics and sound; this tag preserves the code before the modern SDL port

---

## Commodore 64

### <a name="retro-c64-assemblers"></a>Assemblers

*Tools to program assembler on the C64*

- [ACME](https://github.com/meonwax/acme) - A cross assembler for 6502 and 6510 code, including undocumented opcodes, macros, and binary inclusion; this repository mirrors the SourceForge project
- [C6510](https://csdb.dk/release/?id=219569&show=summary) - A cross assembler with LUA macro interface
- [Kick Assembler](http://theweb.dk/KickAssembler/Main.html) - A cross assembler written in Java to produce 6502 code

### <a name="retro-c64-compilers"></a><a name="retro-c64-c-and-cpp-toolchains"></a>C and C++ Toolchains

*Cross compilers and runtime libraries for C64 software*

- [CC65](https://cc65.github.io/) - A C cross-development suite with a compiler, assembler, linker, and C64 runtime libraries; does not compile C++
- [LLVM-MOS SDK](https://github.com/llvm-mos/llvm-mos-sdk) - A Clang-based C and C++ cross-development SDK with a C64 target and runtime libraries; C++ exceptions are not supported
- [Oscar64](https://github.com/drmortalwombat/oscar64) - A C99 and partial C++ cross compiler focused on Commodore 6502 machines, with C64 libraries, banked cartridge support, and disk overlays

### <a name="retro-c64-graphics-tools"></a>Graphics Tools

*Editors for C64 character sets, tiles, maps, and bitmap graphics*

- [CharPad C64 Pro](https://subchristsoftware.itch.io/charpad-c64-pro) - A commercial Windows editor for C64 character sets, tiles, fonts, and maps, with bitmap import and binary data export
- [Pixcen](https://github.com/Hammarberg/pixcen) - A Windows pixel editor designed for C64 graphics, with source code and downloadable binaries

### <a name="retro-c64-music-tools"></a>Music Tools

*SID music editors for C64 productions*

- [CheeseCutter](https://github.com/theyamo/CheeseCutter) - A desktop SID tracker with a C64 player and utilities for exporting songs for playback on the target machine
- [GoatTracker 2](https://cadaver.github.io/tools.html) - A cross-platform C64 music editor with SID emulation, instrument tables, and a player for use in games and demos

### <a name="retro-c64-source-codes"></a>Source Code

#### <a name="retro-c64-cracktro-source-codes"></a>Cracktro Source Code

- [Colour Burst Intro](https://github.com/RichardTND/ColourBurstIntro) - Assembly source for a PAL C64 intro inspired by the Riff Raffs cracktro, with color effects, scrolling text, bouncing sprites, and TMPx build files
- [Interceptor Cracktro Remix](https://github.com/laurikka/Interceptor_cracktro_c64) - C64 assembly homage to Unit A's Amiga F/A-18 Interceptor cracktro, with graphics conversion tools, music, and a VASM build setup

---

## Commodore Amiga

### <a name="retro-amiga-assemblers"></a>Assemblers

*Tools to program assembler on the Commodore Amiga*

- [Asm-Pro](https://github.com/MK1Roxxor/ASMPro) - Source code for a native Amiga 680x0 assembler with an integrated editor, monitor, and disassembler
- [VASM](http://sun.hasenbraten.de/vasm/index.php?view=main) - A cross assembler to produce m68k code

### <a name="retro-amiga-c-and-cpp-toolchains"></a>C and C++ Toolchains

*Native and cross-development compilers for classic Amiga systems*

- [amiga-gcc](https://codeberg.org/bebbo/amiga-gcc) - A build system for a classic Amiga GCC cross-toolchain with C and C++ libraries, binutils, and Amiga-specific development tools
- [vbcc](http://sun.hasenbraten.de/vbcc/) - An optimizing C compiler with classic AmigaOS target libraries and native or cross-development packages; does not compile C++

### <a name="retro-amiga-linkers"></a>Linkers

*Linkers for the Commodore Amiga*

- [VLINK](http://sun.hasenbraten.de/vlink/index.php?view=main) - A portable linker to produce Amiga code

### <a name="retro-amiga-graphics-tools"></a>Graphics Tools

*Pixel editors for Amiga images and animation assets*

- [GrafX2](https://grafx2.gitlab.io/grafX2/) - A pixel editor with palette tools, color cycling, and Amiga IFF/ILBM image support; EHB images are not preserved as EHB when saved
- [PyDPainter](https://github.com/mriale/PyDPainter) - A Deluxe Paint-inspired editor for modern computers, with Amiga IFF and ANIM support, palette cycling, and animation tools

### <a name="retro-amiga-music-tools"></a>Music Tools

*Trackers for composing music for classic Amiga productions*

- [HivelyTracker](https://github.com/pete-gordon/hivelytracker) - A chip music tracker with AHX import and export, an extended HVL format, and replay routines for Amiga productions
- [ProTracker 2 Clone](https://github.com/8bitbubsy/pt2-clone) - A ProTracker 2.3D-style MOD editor for Windows, macOS, and Linux, with sample editing and Amiga audio emulation
- [ProTracker 2.3F](https://github.com/8bitbubsy/pt23f) - A native Amiga 68k tracker continuing ProTracker 2.3D, with playback fixes for fast Amigas and support for larger samples

### <a name="retro-amiga-source-codes"></a>Source Code

*Source code for classic Amiga games, demos, and programming examples*

#### <a name="retro-amiga-demo-source-codes"></a>Demo Source Code

- [1000%](https://github.com/rrath/1000percent) - 680x0 assembly sources for the 1998 Amiga 40K intro, including rendering routines and effect code
- [Alcatraz: Soil](https://github.com/virgill1974/Alcatraz-Soil) - C and assembly sources for an Amiga 500 40K intro, developed with vscode-amiga-debug and using LightSpeedPlayer for music playback
- [Amiga Demos in 68000 ASM](https://github.com/smart-fun/Amiga) - Assembly sources for intros, scrollers, a rotozoom effect, and a music disk, with instructions for SEKA and AsmOne
- [Bronx Amiga Sources](https://github.com/bronxwhq/amiga) - Demo and intro sources from Bronx, including Darklord's BOB intro and Ghost's assembly startup code
- [Circumvent](https://github.com/djh0ffman/TTE_Circumvent) - Assembly sources for TTE's Amiga intro from Revision 2024, coded by h0ffman and hoovephonique
- [Cydonia and Sect Sources](https://github.com/apcro/Amiga-Demos) - Assembly sources for Defy disk magazines, the Scrapbook slideshow magazine, and the unreleased Black Moon demo; original includes and binary assets are missing
- [demarination](https://github.com/wbcbz7/demarination) - An Amiga OCS 64K intro from Revision 2024, written mainly in C; the README documents a memory corruption bug after repeated runs
- [Desire FM](https://github.com/grahambates/desire-fm) - Assembly sources for Desire's Amiga OCS 40K intro from Gerp 2024, including checkerboard, city, and dot effects
- [Dreamdealers Sources](https://github.com/pchalamet/Dreamdealers) - Historical Amiga demo sources including Woodstock, Corinne, Live, and Raging Fire
- [Eire](https://github.com/pawelmat/Amiga-Eire) - Amiga 500 OCS 40K intro by Suspect and Scoopex, with music by Casyopea and a VS Code build setup using VASM, VLINK, and Shrinkler
- [FlexiTwister](https://github.com/christiangerbig/FlexiTwister) - Assembly source for Resistance's AGA production from Gerp 2025, with graphics and music; requires the linked Amiga and AGA include files
- [Ghostown and Whelpz Demoscene Sources](https://github.com/cahirwpz/demoscene) - Amiga OCS demo and effect sources with a framework and build tools; binary assets require Git LFS
- [Ikadalawampu](https://github.com/askeksa/Ikadalawampu) - Loonies' Amiga 4K intro from Breakpoint 2010, with assembly sources, data files, and a C port of its effect bytecode interpreter
- [Moon's Amiga Sources](https://github.com/Moon70/Amiga-sources) - Assembly sources for Abyss intros, music disks, and bootblock effects, including the Drugstore OCS trackmo
- [My Amiga Intros](https://github.com/spifd/MyAmigaIntros) - Assembly sources for 1990s intros and experiments; the author expects compatibility mainly with Kickstart 1.2 and 1.3
- [NAPHTA](https://github.com/steffest/naphta) - Amiga OCS demo from RSync 2025, written in C with direct hardware access; builds with SAS/C and includes graphics and music assets
- [No-CPU Demo and Framework](https://github.com/askeksa/NoCpuDemo) - Sources for the No-CPU Challenge invitation demo, with a Dart build framework, ProTracker music converter, and assets; requires the separate NoCpuChallenge runner
- [Old Jobbo Amiga Code](https://github.com/rjobling/Old-Jobbo-Amiga-Code) - Demo routines and two intros from 1994–1997, originally assembled with Devpac 3 for the A1200; includes unfinished effects
- [ORDO](https://github.com/steffest/ordo) - A system-friendly demo written in C for SAS/C, with bitmap loading, blitter effects, palette changes, and tracker music playback
- [Parcade](https://github.com/jonathanbennett73/amiga-parcade) - An Amiga 500 intro in 68000 assembly with sine scrollers, blitter objects, and vector effects
- [Planartunnel](https://github.com/Ozzyboshi/Planartunnel) - OCS/ECS 4K intro with a spaceship tunnel animation and music; builds with VASM, Shrinkler, and the supplied Makefile
- [Planet Rocklobster](https://github.com/AxisOxy/Planet-Rocklobster) - Source code for Oxyron's Amiga OCS demo, with technical explanations of its rendering effects
- [PlusEqualsPlus](https://github.com/roger-wetzel/PlusEqualsPlus) - Source code for Spreadpoint's OCS demo from MountainBytes 2026, targeting a PAL 68000 Amiga with 512 KB of chip RAM and 512 KB of additional RAM
- [Rampage Effects](https://github.com/tcurdt/rampage) - Assembly sources for the rotating circles and 3D mirror effects contributed to The Electronic Knights' 1994 trackmo
- [Rodonea](https://github.com/Ozzyboshi/Rodonea) - C and assembly sources for a Flashparty 2020 demo using rose-curve animations; requires 1 MB of chip RAM and uses GCC, VASM, and ACE routines
- [Serendipity](https://github.com/tgreaves/serendipity) - 68000 assembly source for an Amiga music disk, with graphics, music modules, and PowerPacker includes
- [System: Zoetrope](https://github.com/astrofra/system-zoetrope-amiga-demo) - Mandarine's Amiga OCS demo from Outline 2015, written in C and using graphics.library calls for scrolling, copper lists, and blitter objects
- [The Crows](https://github.com/Ozzyboshi/AmigaDemo_the_crows) - Assembly demo with documented copper lists, blitter effects, hardware sprites, dual playfields, and MOD playback
- [Timur Lenk and Fistpig](https://github.com/drslem/Spb-Eph-Amiga-4k) - Original assembly sources for Spaceballs and Ephidrena's 2003 Amiga 4K intros; build with AsmOne, but the original cruncher is not included
- [Unusual Suspects](https://github.com/astrofra/demo-unusual-suspects) - A system-friendly Amiga demo written in C for SAS/C 6.58, targeting classic machines from the A500 with AmigaOS 2.0 to the A4000
- [Vertex](https://github.com/Bensakone/Vertex) - Original 1993 Red Chrome demo source package, including assembly code, pictures, music, and include files

#### <a name="retro-amiga-cracktro-source-codes"></a>Cracktro Source Code

- [Genesia: Delight and Paradox](https://github.com/devpack/delight-genesia-amiga) - Reconstructed assembly sources for Paranormal's Amiga crack intro, with startup code, ProTracker replay, graphics, and music
- [The Terra Cresta Cracktro](https://github.com/roger-wetzel/TTCC) - 68000 assembly sources for the 2023 SCA and Spreadpoint cracktro, targeting PAL OCS Amigas with 512 KB; includes VASM instructions and LightSpeedPlayer music data

#### <a name="retro-amiga-game-source-codes"></a>Game Source Code

- [Agony](https://aminet.net/package/game/shoot/YvesGrolet-sources) - Original sources for Psygnosis' Amiga shooter, preserved in Yves Grolet's development archive alongside prototypes; commercial use is excluded
- [Alien Breed '92: Special Edition](https://github.com/hitchhikr/alienbreed) - Reassemblable disassembly of the Amiga CD32 version, with assets, Windows build tools, bug fixes, and a debug mode
- [Alien Breed 3D II](https://github.com/mheyer32/alienbreed3d2) - A maintained version of The Killing Grounds engine with bug fixes and performance improvements, compatible with original game data and mods
- [Ambermoon](https://github.com/jhorneman/ambermoon) - Historical 68000 assembly sources and development documents for Thalion's RPG; the snapshot is incomplete and cannot build the full game
- [Bagman](https://github.com/jotd666/bagman) - Amiga adaptation of the arcade game using original Z80 code translated to 68000 assembly, with asset conversion tools and build instructions
- [Blaze](https://github.com/keithbugeja/blaze) - Assembly source for an unfinished Amiga game
- [Blocky Skies](https://github.com/alpine9000/blockyskies) - Game source and development tools for a classic Amiga game designed for a 68000 and 512 KB of RAM
- [Breathless](https://aminet.net/package/game/shoot/Breathless-1996-Source) - Original assembly sources for Fields of Vision's Amiga FPS, including rendering, audio, and game logic; preserved from the Amiresource magazine release
- [Citadel](https://github.com/pawelmat/Amiga-Citadel) - Original code, game data, and editor for the 1995 Amiga game; some assets, including intro animations, are missing
- [Devil's Temple](https://github.com/mcgeezer/Devils-Temple-Amiga) - Assembly sources for the 2022 Amiga game, including player and enemy logic, scrolling, audio, and game assets
- [Gloom](https://github.com/earok/GloomAmiga) - Assembly and Blitz BASIC 2 sources for Black Magic's Amiga FPS; completeness and correspondence to the final release are not guaranteed
- [Leonardo](https://github.com/renestraub/amiga-leonardo) - Assembly sources for the 1989 Amiga box-moving puzzle game, including graphics, disk, and input routines
- [MatchPatch](https://github.com/tetracorp/matchpatch-amiga) - Assembly source and executable for the Amiga puzzle game, with coverdisk documentation, extracted maps, and a linked analysis
- [Menace: Amiga Format Sources](https://github.com/davepoo/Menace-Amiga-Format) - Sources from the Amiga Format programming series, with later adaptations, Devpac and VASM build instructions, and graphics conversion tools
- [Phantom Fighter](https://github.com/billynewport/PhantomFighter) - Original Lattice C and 68000 assembly sources for the 1988 game, with recovered assets and the author's notes on rendering and development
- [Phoenix](https://github.com/jotd666/phoenix) - Amiga ECS/AGA adaptation of the arcade game, with translated game code, graphics conversion work, and enhanced colors for AGA
- [Rally-X](https://github.com/jotd666/rally-x) - Amiga ECS/AGA port of Namco's arcade game using Z80-to-68000 translated code; the README notes performance problems on slow machines
- [RC (Rally Cross)](https://github.com/ResistanceVault/rc) - Source code for a multiplayer racing game for classic Amigas, with computer-controlled cars
- [Return of Medusa (Rings of Medusa 2)](https://github.com/bubeck/rings-of-medusa/tree/original-sources) - Original 1991 Amiga and Atari ST sources in C and assembly, with graphics and sound; this tag preserves the code before the modern SDL port
- [Snackzone](https://github.com/renestraub/amiga-snackzone) - Assembly sources for the 1993 BiFi Roll advertising game, including boot, input, and memory routines
- [The Faery Tale Adventure](https://github.com/viridia/faery-tale-amiga) - Original 1987 Amiga game source in Aztec C and 68000 assembly, published by its author as a historical reference
- [Turrican III: Payment Day](https://archive.org/details/TurricanIIISourceCode) - Historical 68000 assembly sources for NEON's Amiga adaptation of Factor 5's game, with level data, graphics, and tools; preserved in a third-party archive
- [Zool 2](https://github.com/hitchhikr/zool2) - Reassemblable disassembly of the Amiga CD32 game, with controls and gameplay fixes; original CD animations and audio tracks are omitted

#### <a name="retro-amiga-examples"></a>Examples

*Source code for learning Amiga hardware programming*

- [Amiga 68K Examples](https://github.com/pararaum/amigaexamples) - Examples and tutorials in 68K assembly and C, including demos and scrollers
- [Amiga Assembly Development Workflow](https://github.com/neildavis/amiga_asmdev_workflow) - A Linux build workflow with an assembly demo using bitplanes, blitter objects, sprites, and ZX0 decompression

---

## Sega Genesis

### <a name="retro-sega-genesis-assemblers"></a>Assemblers

*Tools to program assembler on the Sega Genesis*

- [Macroassembler AS](https://github.com/Macroassembler-AS/asl-releases) - A cross assembler with Motorola 68000 and Z80 backends for the Genesis CPUs; source releases are preserved on the upstream branch
- [VASM](http://sun.hasenbraten.de/vasm/index.php?view=main) - A cross assembler to produce m68k code

### <a name="retro-sega-genesis-devkit"></a><a name="retro-sega-genesis-c-and-cpp-toolchains"></a>C and C++ Toolchains

*Cross-development toolchains for Sega Genesis and Mega Drive software*

- [Marsdev](https://github.com/andwn/marsdev) - A GCC cross-toolchain for Mega Drive and 32X, with optional C++ builds, Newlib, and SGDK integration
- [SGDK](https://github.com/Stephane-D/SGDK) - A C development kit for Mega Drive with a GCC toolchain, hardware libraries, examples, and resource conversion tools

### <a name="retro-sega-genesis-development-tools"></a>Development Tools

#### <a name="retro-sega-genesis-command-line-tools"></a>Command Line Tools

*Command line tools for Sega Genesis development*

- [Sega Genesis Rom Checksum Utility](https://github.com/mrhappyasthma/Sega-Genesis-Checksum-Utility) - Python scripts to correct the ROM checksum
- [SVP Development Tools](https://github.com/jdesiloniz/svpdev) - Development tools for the SVP chip, found in Virtua Racing cartridges

#### <a name="retro-sega-genesis-ide"></a>IDEs

- [genesis-code](https://github.com/zerasul/genesis-code) - Visual Studio Code Extension for Sega Genesis/Mega Drive development

### <a name="retro-sega-genesis-hardware"></a>Hardware

*Hardware and firmware for the Sega Genesis*

- [Genesis Dumper](https://github.com/tonyp7/GenDumper) - Open Source hardware to dump cartridges
- [Opendrive-Genesis](https://github.com/soniccd123/OpenDrive-Genesis) - Open Hardware Flashcard for the Sega Genesis/32X

### <a name="retro-sega-genesis-gui-tools"></a><a name="retro-sega-genesis-graphics-tools"></a>Graphics Tools

*Editors and converters for Genesis graphics and level assets*

- [Codemasters Image Converter](https://github.com/lab313ru/CodemastersBinImage) - Extract and insert graphics in Codemasters games
- [Mega Happy Sprite](https://github.com/sigflup/Mega-Happy-Sprite) - Sprite/Scrollpane editor for the Sega Genesis
- [SGDK ResComp](https://github.com/Stephane-D/SGDK/blob/master/bin/rescomp.txt) - SGDK's resource compiler for palettes, tilesets, tilemaps, and animated sprites, with assembly output for use in a game build
- [Tilemap Studio](https://github.com/Rangi42/tilemap-studio) - A desktop tilemap editor with Genesis map format support and sample assets

### <a name="retro-sega-genesis-music-tools"></a>Music Tools

*Native and desktop trackers for Genesis FM and PSG music*

- [Furnace](https://github.com/tildearrow/furnace) - A desktop chiptune tracker with YM2612 and SN76489 support and VGM export; game integration requires a compatible player or conversion tool
- [mdtracker](https://github.com/corthax/mdtracker) - Source code for a native Sega Genesis music tracker
- [ZorroTracker](https://github.com/ZorroTrackerDev/ZorroTracker) - An abandoned Electron-based Genesis tracker with support for multiple sound drivers and VGM export

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

- [Cliffhanger, Ex-Mutants, and Gargoyles](https://shrigley.com/source_code_archive/) - Original Sega Genesis project archives published by programmer Chris Shrigley for educational use only; commercial use is prohibited
- [L'Abbaye des Morts](https://github.com/moon-watcher/AbbayeMD) - Source code for a Sega Genesis game
- [Landstalker](https://github.com/lordmir/landstalker_disasm) - 68000 assembly disassemblies of multiple regional releases, with build scripts and support for an expanded ROM layout
- [Mega Car Wars](https://github.com/realbrucest/Mega-Car-Wars) - C sources for an isometric adventure racing game for the Sega Genesis and Mega Drive
- [Mr. Nutz 2](https://archive.org/details/TurricanIIISourceCode) - Historical sources for NEON's unreleased Mega Drive port, bundled in the Turrican III archive; DISK_17 contains Nutz_Sources_11_8.lha, with related data and tools on adjacent disks
- [Scorpion Illuminati](https://github.com/moon-watcher/Scorpion-Illuminati-Core) - Homebrew rhythm game in 68000 assembly, with build instructions for ASM68K and SNASM68K
- [Sonic the Hedgehog 1 - C port](https://github.com/cuckydev/SoniCPort) - Source code for a C port of Sonic the Hedgehog 1
- [Sonic the Hedgehog 2](https://github.com/sonicretro/s2disasm) - Disassembly of the 16-bit game with Windows and Lua build scripts; provided for educational use, with commercial use prohibited
- [Sonic the Hedgehog 3 and Sonic & Knuckles](https://github.com/sonicretro/skdisasm) - Disassemblies with separate and combined ROM builds, organized by levels, objects, and sound; commercial use is prohibited
- [TetrisMD](https://github.com/NeroJin/TetrisMD) - Homebrew Tetris game written in C with SGDK 1.41, including hold, hard drop, and soft drop controls

#### <a name="retro-sega-genesis-tools-and-sound-drivers"></a>Tools and Sound Drivers

- [GEMS](https://github.com/realmonster/GEMS) - Sega Genesis GEMS Sound Driver
- [Genesis Debugger](https://github.com/flamewing/genesis-debugger) - Source code for a debugger on Sega Genesis

---

## Super Nintendo (SNES)

### <a name="retro-snes-assemblers"></a>Assemblers

*Assemblers for SNES programs and coprocessors*

- [Asar](https://github.com/RPGHacker/asar) - An assembler for creating SNES ROMs and applying patches, with 65c816, SPC700, and Super FX support
- [bass](https://github.com/ARM9/bass) - A macro assembler for multiple architectures, including the SNES; this fork includes Super FX/GSU support
- [ca65](https://cc65.github.io/doc/ca65.html) - The cc65 suite's macro assembler with 65816 support, used with the ld65 linker for SNES projects; the cc65 C compiler does not target the SNES CPU
- [WLA-DX](https://github.com/vhelin/wla-dx) - A cross assembler and linker package with 65816, SPC700, and Super FX support

### <a name="retro-snes-c-and-cpp-toolchains"></a>C and C++ Toolchains

*C toolchains for SNES development; the tools listed here do not provide C++ support*

- [Calypsi 65816](https://www.calypsi.cc/) - A C99 cross-toolchain with a SNES target that can use the console's hardware arithmetic units; closed source and free for hobby use
- [PVSnesLib](https://github.com/alekmaul/pvsneslib) - A C and assembly development kit with a compiler, linker, hardware libraries, asset tools, and examples

### <a name="retro-snes-development-tools"></a>Development Tools

#### <a name="retro-snes-devkit"></a>Devkits

*Toolchains and libraries for SNES development*

- [SNESKIT](https://github.com/mukunda-/sneskit) - A low-level SNES development kit with build tools, project templates, and a SNESMOD example

### <a name="retro-snes-command-line-tools"></a><a name="retro-snes-graphics-tools"></a>Graphics Tools

*Editors and converters for SNES palettes, tiles, sprites, and tilemaps*

- [gfx4snes](https://github.com/alekmaul/pvsneslib/tree/master/tools/gfx4snes) - PVSnesLib's PNG/BMP converter for SNES tiles, palettes, maps, and metasprites, including Mode 7 output
- [SuperFamiconv](https://github.com/Optiroc/SuperFamiconv) - A command line converter for palettes, tiles, and tilemaps, with support for SNES graphics modes including Mode 7
- [Tilemap Studio](https://github.com/Rangi42/tilemap-studio) - A desktop tilemap editor with SNES map format support and sample assets

### <a name="retro-snes-audio-tools-and-libraries"></a><a name="retro-snes-music-tools"></a>Music Tools

*Editors for composing music and sound effects for SNES projects*

- [OpenMPT](https://openmpt.org/) - A Windows tracker for composing Impulse Tracker modules for a SNESMOD conversion workflow; songs must follow the audio driver's format and memory limits
- [SNESGSS](https://github.com/nathancassano/snesgss) - A Windows music and sound effect editor for SNES homebrew, with sample-bank export and an SPC700 playback driver

#### <a name="retro-snes-audio-libraries-and-drivers"></a>Audio Libraries and Drivers

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

#### <a name="retro-snes-cracktro-source-codes"></a>Cracktro and Trainer Intro Source Code

- [Anthrox Mode 7 Trainer Intro](https://github.com/nyanpasu64/spc-dev/tree/master/sneskit/examples/atx-mode-7-trainer) - Historical 65816 assembly source by The White Knight, preserved alongside a ca65/SNESKit adaptation with Mode 7 effects and C64 fonts
- [Elitendo Intro 3](https://github.com/nyanpasu64/spc-dev/tree/master/sneskit/examples/elitendo-intro) - Radium's 1993 trainer intro sources, with menu options and animated scrolling text; includes the original source and a ca65/SNESKit adaptation

#### <a name="retro-snes-game-source-codes"></a>Game Source Code

*Source code for SNES games and playable game demos*

- [Castle Platformer](https://github.com/undisbeliever/castle_platformer) - A platformer engine and demo with interactive tiles, animated sprites, and dynamic maps, built with ca65
- [DOOM-FX](https://github.com/RandalLinden/DOOM-FX) - Source code for the SNES port of Doom using the Super FX GSU2A, released by Randal Linden
- [Final Fantasy VI / III](https://github.com/everything8215/ff6) - Disassembly of the Japanese and US releases using ca65, with documented game systems; requires an original ROM to extract assets
- [Horizontal Shooter](https://github.com/undisbeliever/horizontal-shooter) - A shooter demo using the entity and MetaSprite systems of the UnTech Game Engine
- [Skipp and Friends](https://github.com/mukunda-/skipp-and-friends) - Source code, level data, and development tools for the SNES game
- [Super 3D Noah's Ark](https://github.com/MatthewCallis/NOAH3D) - Original SNES sources recovered from Wisdom Tree development diskettes, including C and assembly code, assets, and Wolfenstein 3D engine tools
- [Super Metroid](https://github.com/InsaneFirebat/sm_disassembly) - Relocatable assembly disassembly based on P.JBoy's bank logs, built with Asar; requires an original NTSC ROM to extract assets
- [Super Sudoku](https://github.com/raphnet/super_sudoku) - A Sudoku game in assembly with a solver, hints, and support for standard controllers and the NTT Data Keypad
- [Sure Instinct](https://github.com/BenjaminSchulte/SureInstinct) - Game source code with the Aoba engine, level editor, and music tools; building requires FMA and Qt5 and has only been tested on Linux
- [Unnamed SNES Engine](https://github.com/undisbeliever/unnamed-snes-engine) - A single-screen top-down game demo and engine using Wiz and the Terrific Audio Driver

#### <a name="retro-snes-examples-and-test-roms"></a>Examples and Test ROMs

*Source code for learning SNES programming and testing hardware behavior*

- [Peter Lemon's SNES Examples](https://github.com/PeterLemon/SNES) - Assembly examples covering graphics, input, SPC700 audio, and Super FX programming using bass
- [SNES Stuff](https://github.com/bbbradsmith/SNES_stuff) - Small programs demonstrating graphics modes, color math, controllers, and SPC700 audio
- [SNES Test ROMs](https://github.com/undisbeliever/snes-test-roms) - Test ROM source code for investigating SNES hardware behavior
