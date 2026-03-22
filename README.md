# 🎮 Awesome Game File Format Reversing

[Awesome](https://github.com/sindresorhus/awesome)
[License: CC0-1.0](LICENSE)

> 通过工程实践与工具收集，汇总游戏文件格式的文档、逆向笔记与开源资源。

## 📖 About

游戏通常以模型、贴图、音频、脚本、关卡等资产为专有或定制格式存储。

本清单面向这些格式的开发者与 Mod 作者，提供解析、提取、转换与制作所需的工具和知识。

**欢迎贡献：** 提交 PR 补充新工具、文档或修正内容。

## 🗺️ How to Use This List

- **新手**：从 [学习资源与教程](#-learning-resources--tutorials) 和 [通用工具](#general-tools) 开始。
- **针对某游戏**：Ctrl+F 或在 [目录](#-contents) 中找到对应的工作室/游戏名称。
- **找引擎/中间件**：查看 [引擎](#-engines) 与 [中间件 / SDK](#-middleware--sdks)。
- **需要社区帮助**：访问 [论坛与社区](#forums--communities) 及 [Discord 服务器](#discord-servers)。

## 📑 Contents

- [👥 Communities \& Wikis](#-communities--wikis)
  - [Forums \& Communities](#forums--communities)
  - [Discord Servers](#discord-servers)
  - [Knowledge Bases \& Format Databases](#knowledge-bases--format-databases)
  - [Platform \& SDK Documentation](#platform--sdk-documentation)
  - [Game-Specific Wikis](#game-specific-wikis)
  - [📚 Learning Resources \& Tutorials](#-learning-resources--tutorials)
    - [🎥 Video Tutorials](#-video-tutorials)
  - [Asset Databases](#asset-databases)
- [🛠️ General Tools](#general-tools)
  - [🎨 Asset Viewers \& Converters](#-asset-viewers--converters)
  - [📦 Archive Extractors](#-archive-extractors)
  - [🔊 Audio Tools](#-audio-tools)
  - [🌐 Translation \& Localization](#-translation--localization)
  - [🔍 Hex Editors](#-hex-editors)
  - [🔬 Format Analysis \& Reverse Engineering](#-format-analysis--reverse-engineering)
  - [💻 Development Libraries](#-development-libraries)
  - [📂 Script Collections \& Multi-Game Tools](#-script-collections--multi-game-tools)
- [⚙️ Engines](#�?engines)
  - [GameMaker](#gamemaker)
  - [Source (Valve)](#source-valve)
  - [Unity](#unity)
  - [Unreal Engine](#unreal-engine)
  - [CryEngine](#cryengine)
  - [Hedgehog Engine](#hedgehog-engine)
  - [Northlight Engine](#northlight-engine)
  - [Pragma Engine](#pragma-engine)
  - [Build Engine](#build-engine)
  - [3DSTATE](#3dstate)
  - [AtiSushi Engine](#atisushi-engine)
  - [Genie Engine](#genie-engine)
  - [RPG Maker](#rpg-maker)
  - [Ren'Py](#renpy)
  - [Rawthrills G7 Engine](#rawthrills-g7-engine)
  - [OpenSpace](#openspace)
- [🔧 Middleware \& SDKs](#-middleware--sdks)
  - [Fast3d/F3dex (N64)](#fast3df3dex-n64)
  - [Havok](#havok)
  - [JSYSTEM (GameCube/Wii)](#jsystem-gamecubewii)
  - [MikuMikuDance](#mikumikudance)
  - [RenderWare](#renderware)
  - [CRI](#cri)
  - [XNA](#xna)
  - [Sappy (GBA Audio)](#sappy-gba-audio)
  - [RAD Game Tools](#rad-game-tools)
  - [Nintendo SDKs \& Hardware](#nintendo-sdks--hardware)
- [Game \& Studio Tools](#game--studio-tools)
  - [Activision / Infinity Ward / Treyarch](#activision--infinity-ward--treyarch)
    - [Call of Duty](#call-of-duty)
    - [Tony Hawk's Pro Skater](#tony-hawks-pro-skater)
    - [Ghostbusters](#ghostbusters)
    - [A Series of Unfortunate Events](#a-series-of-unfortunate-events)
    - [Spider-Man (Neversoft)](#spider-man-neversoft)
  - [Angel Matrix (Neon White)](#angel-matrix-neon-white)
  - [Angel Studios / Rockstar San Diego](#angel-studios--rockstar-san-diego)
  - [Anthony Bongers](#anthony-bongers)
  - [Ape, Inc](#ape-inc)
  - [Arrowhead Game Studios (Helldivers 2)](#arrowhead-game-studios-helldivers-2)
  - [11 bit studios (Frostpunk)](#11-bit-studios-frostpunk)
  - [Avalanche Studios (Generation Zero)](#avalanche-studios-generation-zero)
  - [Remedy Entertainment](#remedy-entertainment)
    - [Max Payne](#max-payne)
  - [Argonaut Games](#argonaut-games)
  - [Arkane Studios](#arkane-studios)
  - [Atlus](#atlus)
  - [Asobo Studio](#asobo-studio)
  - [Black Element Software (Alpha Prime)](#black-element-software-alpha-prime)
  - [Bandai Namco](#bandai-namco)
  - [Electronic Arts](#electronic-arts)
    - [SSX](#ssx)
  - [EA DICE](#ea-dice)
    - [Battlefield Series](#battlefield-series)
    - [Star Wars: Battlefront](#star-wars-battlefront)
  - [EgoSoft (X4)](#egosoft-x4)
  - [Capcom](#capcom)
    - [RE Engine](#re-engine)
    - [Resident Evil](#resident-evil)
    - [Monster Hunter](#monster-hunter)
    - [Devil May Cry](#devil-may-cry)
    - [Street Fighter](#street-fighter)
    - [Ultimate Marvel vs Capcom 3](#ultimate-marvel-vs-capcom-3)
    - [Mega Man](#mega-man)
    - [Gregory Horror Show](#gregory-horror-show)
    - [Gotcha Force](#gotcha-force)
    - [Phoenix Wright: Ace Attorney](#phoenix-wright-ace-attorney)
  - [CCR (RF Online)](#ccr-rf-online)
  - [CCP Games (EVE Online)](#ccp-games-eve-online)
  - [CR-Space (Martial Heroes)](#cr-space-martial-heroes)
  - [CD Projekt Red](#cd-projekt-red)
    - [The Witcher 3 / REDEngine 3](#the-witcher-3--redengine-3)
    - [The Witcher](#the-witcher)
    - [Cyberpunk 2077 / REDEngine 4](#cyberpunk-2077--redengine-4)
  - [Clover Studio (Okami)](#clover-studio-okami)
  - [Cygames (Granblue Fantasy Relink)](#cygames-granblue-fantasy-relink)
  - [Disney Interactive](#disney-interactive)
    - [Toontown Online](#toontown-online)
  - [Double Fine (Psychonauts, Costume Quest)](#double-fine-psychonauts-costume-quest)
  - [8monkey Labs](#8monkey-labs)
  - [Crystal Dynamics / Eidos Interactive](#crystal-dynamics--eidos-interactive)
  - [Ion Storm](#ion-storm)
    - [Anachronox](#anachronox)
    - [Deus Ex](#deus-ex)
  - [Massive Entertainment](#massive-entertainment)
    - [AquaNox](#aquanox)
    - [World in Conflict](#world-in-conflict)
  - [Surreal Software](#surreal-software)
  - [Dynamix / Sierra](#dynamix--sierra)
    - [Tribes Series](#tribes-series)
  - [DOKA Studios](#doka-studios)
  - [EA Black Box](#ea-black-box)
    - [Need for Speed Series](#need-for-speed-series)
  - [FromSoftware](#fromsoftware)
  - [Frictional Games (Amnesia, Soma)](#frictional-games-amnesia-soma)
  - [Gearbox Software](#gearbox-software)
    - [MechWarrior 4](#mechwarrior-4)
  - [Game Freak](#game-freak)
    - [Gen I \& II](#gen-i--ii)
    - [Gen III](#gen-iii)
    - [Gen VI](#gen-vi)
    - [Gen V](#gen-v)
  - [Gameloft](#gameloft)
  - [Genius Sonority](#genius-sonority)
  - [Genki](#genki)
  - [Grezzo](#grezzo)
  - [Human Head Studios](#human-head-studios)
  - [id Software](#id-software)
  - [Guerrilla Games](#guerrilla-games)
  - [LucasArts](#lucasarts)
  - [Gust (Koei Tecmo)](#gust-koei-tecmo)
  - [Harmonix](#harmonix)
  - [HAL Laboratory](#hal-laboratory)
  - [Heavy Iron Studios](#heavy-iron-studios)
  - [Hudson Soft](#hudson-soft)
  - [Insomniac Games](#insomniac-games)
  - [Intelligent Systems](#intelligent-systems)
    - [Paper Mario 64](#paper-mario-64)
    - [Paper Mario: TTYD / Super Paper Mario](#paper-mario-ttyd--super-paper-mario)
  - [Interactive Studios](#interactive-studios)
    - [Glover](#glover)
  - [Illusion](#illusion)
  - [Innerloop Studios](#innerloop-studios)
  - [iNiS](#inis)
  - [Jupiter](#jupiter)
  - [Jagex](#jagex)
  - [Koei Tecmo](#koei-tecmo)
    - [Fatal Frame](#fatal-frame)
  - [Konami](#konami)
    - [Metal Gear Solid](#metal-gear-solid)
    - [Silent Hill](#silent-hill)
    - [Castlevania](#castlevania)
    - [Enthusia Professional Racing](#enthusia-professional-racing)
  - [Kuju London](#kuju-london)
  - [Larian Studios](#larian-studios)
    - [Baldur's Gate 3](#baldurs-gate-3)
    - [Divinity: Original Sin 2](#divinity-original-sin-2)
  - [Level-5](#level-5)
  - [Lionhead Studios (Black \& White)](#lionhead-studios-black--white)
  - [Macrospace](#macrospace)
    - [Fatal Force: Earth Assault](#fatal-force-earth-assault)
  - [Metropolis Software](#metropolis-software)
    - [Gorky 17](#gorky-17)
  - [Microsoft Studios / Bungie / Turn 10](#microsoft-studios--bungie--turn-10)
    - [Halo](#halo)
    - [Destiny](#destiny)
    - [Gears of War](#gears-of-war)
    - [Forza](#forza)
    - [Age of Empires](#age-of-empires)
  - [Mobius Digital (Outer Wilds)](#mobius-digital-outer-wilds)
  - [Midway](#midway)
    - [Area 51](#area-51)
    - [Gauntlet](#gauntlet)
    - [NFL Blitz](#nfl-blitz)
  - [Monolith Productions](#monolith-productions)
    - [F.E.A.R](#fear)
    - [Trespasser](#trespasser)
    - [Blood](#blood)
    - [Blood 2: The Chosen](#blood-2-the-chosen)
    - [No One Lives Forever](#no-one-lives-forever)
    - [Shogo: Mobile Armor Division](#shogo-mobile-armor-division)
    - [Serious Sam](#serious-sam)
  - [Monolith Soft](#monolith-soft)
    - [Xenoblade Chronicles](#xenoblade-chronicles)
  - [Oddworld Inhabitants](#oddworld-inhabitants)
  - [Naughty Dog](#naughty-dog)
    - [Crash Bandicoot 1-3 \& CTR](#crash-bandicoot-1-3--ctr)
    - [Spyro the Dragon](#spyro-the-dragon)
    - [Jak and Daxter](#jak-and-daxter)
  - [NanaOn-Sha](#nanaon-sha)
  - [Nintendo EAD](#nintendo-ead)
    - [Animal Crossing](#animal-crossing)
    - [AST](#ast)
    - [Luigi's Mansion](#luigis-mansion)
    - [Pikmin](#pikmin)
    - [Pikmin 2](#pikmin-2)
    - [Mario Artist](#mario-artist)
    - [Mario Kart: Double Dash](#mario-kart-double-dash)
    - [Super Mario 64](#super-mario-64)
    - [Super Mario 64 DS](#super-mario-64-ds)
    - [Super Mario (Other)](#super-mario-other)
    - [New Super Mario Bros Wii](#new-super-mario-bros-wii)
    - [Zelda](#zelda)
    - [Wii Sports](#wii-sports)
    - [Star Fox Adventures](#star-fox-adventures)
    - [Star Fox 64](#star-fox-64)
    - [Star Fox 64 3D](#star-fox-64-3d)
    - [Super Monkey Ball](#super-monkey-ball)
    - [F-Zero](#f-zero)
    - [Chibi-Robo](#chibi-robo)
    - [Snowboard Kids](#snowboard-kids)
    - [Wave Race 64](#wave-race-64)
    - [The New Tetris](#the-new-tetris)
    - [New Super Mario Bros DS](#new-super-mario-bros-ds)
    - [Metroid Prime](#metroid-prime)
    - [Pokemon](#pokemon)
  - [Ntreev Soft](#ntreev-soft)
  - [BioWare](#bioware)
    - [Mass Effect](#mass-effect)
    - [Dragon Age: Origins](#dragon-age-origins)
    - [Knights of the Old Republic](#knights-of-the-old-republic)
  - [Obsidian Entertainment](#obsidian-entertainment)
    - [Neverwinter Nights 2](#neverwinter-nights-2)
  - [Panic (Playdate)](#panic-playdate)
  - [Paradox Interactive](#paradox-interactive)
  - [Petroglyph Games](#petroglyph-games)
  - [PlatinumGames](#platinumgames)
    - [Bayonetta](#bayonetta)
    - [Nier: Automata / Replicant](#nier-automata--replicant)
  - [Primal Software](#primal-software)
    - [The I of the Dragon](#the-i-of-the-dragon)
  - [Procedural Arts](#procedural-arts)
    - [Façade](#façade)
  - [Polytron (Fez)](#polytron-fez)
  - [Mithis Entertainment](#mithis-entertainment)
    - [Nexus: The Jupiter Incident](#nexus-the-jupiter-incident)
  - [Punchline](#punchline)
  - [People Can Fly](#people-can-fly)
    - [Painkiller](#painkiller)
    - [Dreamkiller](#dreamkiller)
  - [Piranha Bytes](#piranha-bytes)
  - [Polyphony Digital (Gran Turismo)](#polyphony-digital-gran-turismo)
  - [Rebel Act](#rebel-act)
  - [Rebellion Developments](#rebellion-developments)
    - [Aliens vs. Predator 2](#aliens-vs-predator-2)
    - [Aliens vs. Predator (2010)](#aliens-vs-predator-2010)
  - [Rare](#rare)
    - [Banjo-Kazooie](#banjo-kazooie)
    - [Banjo-Tooie](#banjo-tooie)
    - [Donkey Kong 64](#donkey-kong-64)
    - [Diddy Kong Racing](#diddy-kong-racing)
    - [GoldenEye 007](#goldeneye-007)
    - [Conker's Bad Fur Day](#conkers-bad-fur-day)
    - [Banjo-Kazooie (Xbox 360)](#banjo-kazooie-xbox-360)
  - [Raven Software](#raven-software)
    - [Heretic II](#heretic-ii)
    - [Soldier of Fortune](#soldier-of-fortune)
  - [Runic Games](#runic-games)
    - [Torchlight](#torchlight)
    - [Torchlight II](#torchlight-ii)
  - [Runecraft](#runecraft)
  - [1C Company / Best Way](#1c-company--best-way)
    - [Men of War](#men-of-war)
    - [Royal Quest Online](#royal-quest-online)
  - [Ironclad Games / Stardock](#ironclad-games--stardock)
    - [Sins of a Solar Empire](#sins-of-a-solar-empire)
  - [Radical Entertainment](#radical-entertainment)
  - [Reflections Interactive](#reflections-interactive)
  - [Riot Games](#riot-games)
  - [Santa Monica Studio (God of War)](#santa-monica-studio-god-of-war)
  - [SCS Software (Euro Truck Simulator)](#scs-software-euro-truck-simulator)
  - [Sega](#sega)
    - [Creative Assembly](#creative-assembly)
      - [Alien: Isolation](#alien-isolation)
      - [Total War Series](#total-war-series)
  - [Sonic Team](#sonic-team)
    - [Sonic Adventure](#sonic-adventure)
    - [Sonic Heroes / Shadow](#sonic-heroes--shadow)
    - [Other Sonic Games](#other-sonic-games)
  - [Snowblind Studios](#snowblind-studios)
    - [Baldur's Gate: Dark Alliance](#baldurs-gate-dark-alliance)
  - [Sony (First Party)](#sony-first-party)
  - [Square Enix](#square-enix)
    - [Final Fantasy](#final-fantasy)
    - [Chrono Cross](#chrono-cross)
    - [Xenogears](#xenogears)
    - [Xenosaga](#xenosaga)
    - [Vagrant Story](#vagrant-story)
    - [Soul Blazer](#soul-blazer)
    - [Sleeping Dogs](#sleeping-dogs)
    - [The World Ends With You](#the-world-ends-with-you)
    - [Babylon's Fall](#babylons-fall)
    - [Hitman](#hitman)
  - [Sucker Punch](#sucker-punch)
    - [Sly Cooper](#sly-cooper)
  - [Supercell](#supercell)
  - [SuperTuxKart](#supertuxkart)
  - [Telltale Games](#telltale-games)
  - [GSC Game World](#gsc-game-world)
    - [S.T.A.L.K.E.R](#stalker)
  - [Troika Games (Vampire: The Masquerade)](#troika-games-vampire-the-masquerade)
  - [Terminal Reality (Nocturne)](#terminal-reality-nocturne)
    - [BloodRayne](#bloodrayne)
  - [THQ / Rainbow Studios](#thq--rainbow-studios)
    - [Cars](#cars)
    - [MX vs ATV](#mx-vs-atv)
    - [Twisted Metal](#twisted-metal)
  - [3D Realms](#3d-realms)
    - [Duke Nukem 3D](#duke-nukem-3d)
    - [Duke Nukem: Manhattan Project](#duke-nukem-manhattan-project)
    - [Duke Nukem Forever (2001)](#duke-nukem-forever-2001)
    - [Duke Nukem Forever (2011)](#duke-nukem-forever-2011)
    - [The Outforce](#the-outforce)
  - [Techland](#techland)
  - [Thekla Inc (The Witness)](#thekla-inc-the-witness)
  - [Slitherine / Proxy Studios](#slitherine--proxy-studios)
  - [Visceral Games (Dead Space, Dante's Inferno)](#visceral-games-dead-space-dantes-inferno)
  - [Wargaming (World of Warships)](#wargaming-world-of-warships)
  - [Ubisoft](#ubisoft)
    - [Anno 1800](#anno-1800)
  - [Bethesda](#bethesda)
  - [2K Games / Firaxis Games](#2k-games--firaxis-games)
  - [2K Czech / Illusion Softworks](#2k-czech--illusion-softworks)
  - [Natsume (Harvest Moon)](#natsume-harvest-moon)
  - [Falcom (Ys)](#falcom-ys)
  - [Working Designs (Lunar)](#working-designs-lunar)
  - [Toby Fox (Undertale)](#toby-fox-undertale)
  - [Terry Cavanagh](#terry-cavanagh)
    - [VVVVVV](#vvvvvv)
  - [Studio MDHR (Cuphead)](#studio-mdhr-cuphead)
  - [TaleWorlds Entertainment](#taleworlds-entertainment)
    - [Mount\&Blade](#mountblade)
  - [TT Games (LEGO Island)](#tt-games-lego-island)
  - [Acclaim Entertainment (Turok)](#acclaim-entertainment-turok)
  - [Whoopee Camp (Tomba!)](#whoopee-camp-tomba)
  - [Team Shanghai Alice (Touhou)](#team-shanghai-alice-touhou)
  - [5th Cell](#5th-cell)
  - [Asmik Ace Entertainment (LSD: Dream Emulator)](#asmik-ace-entertainment-lsd-dream-emulator)
  - [Stainless Games (Carmageddon)](#stainless-games-carmageddon)
  - [Gumi (Brave Frontier)](#gumi-brave-frontier)
  - [Ninja Kiwi (Bloons TD)](#ninja-kiwi-bloons-td)
  - [Eutechnyx (Ford Racing)](#eutechnyx-ford-racing)
  - [Eurocom](#eurocom)
  - [Hasbro Interactive (Frogger)](#hasbro-interactive-frogger)
  - [H2O Entertainment (Aidyn Chronicles)](#h2o-entertainment-aidyn-chronicles)
  - [Bohemia Interactive](#bohemia-interactive)
  - [Bugbear Entertainment (FlatOut)](#bugbear-entertainment-flatout)
  - [Bugbear Entertainment (Team6 Engine - FlatOut 3)](#bugbear-entertainment-team6-engine---flatout-3)
  - [Blizzard Entertainment (World of Warcraft)](#blizzard-entertainment-world-of-warcraft)
  - [Westwood Studios / EA Los Angeles](#westwood-studios--ea-los-angeles)
  - [Mojang Studios](#mojang-studios)
  - [Grasshopper Manufacture (No More Heroes, Killer7)](#grasshopper-manufacture-no-more-heroes-killer7)
  - [Free Radical Design (TimeSplitters)](#free-radical-design-timesplitters)
  - [Enhance Games (Rez)](#enhance-games-rez)
  - [Gravity (Ragnarok Online)](#gravity-ragnarok-online)
  - [Her Interactive (Nancy Drew)](#her-interactive-nancy-drew)
  - [HeroForge (HeroForge)](#heroforge-heroforge)
  - [Yostar / Revived Witch](#yostar--revived-witch)
  - [CyberStep (CosmicBreak)](#cyberstep-cosmicbreak)
  - [Firesprite (Run Sackboy! Run!)](#firesprite-run-sackboy-run)
  - [Bandai Namco (Dragon Ball)](#bandai-namco-dragon-ball)
- [🔗 Related Lists](#-related-lists)
- [📄 License](#-license)
- [🙏 Acknowledgments](#-acknowledgments)

## 👥 社区与 Wiki

*面向逆向工程与文件格式的知识库、论坛与学习资源。*

### 论坛与社区

- [ZenHAX](https://zenhax.com/) - 游戏破解与逆向工程论坛。
- [ResHax](https://reshax.com/) - 游戏逆向档案与格式社区。
- [XeNTaX 论坛（已关闭）](https://web.archive.org/web/20231024043128/https://forum.xentax.com/) - 游戏封包与格式研究论坛。

### Discord 服务器

- [REGames](https://discord.com/invite/regames-760531247704702996) - 游戏逆向与文件格式研究社区。
- [The VG Resource](https://discord.com/invite/tsr) - 面向 The VG Resource 资产库（模型、贴图、精灵、音效）的社区。
- [The Cutting Room Floor (TCRF)](https://discord.com/invite/SGeE8dcWR6) - 发现与记录游戏未使用/调试内容的社区。
- [Reverse Engineering](https://discord.com/invite/reverse-engineering-391398885819547652) - 通用逆向工程社区与资源。
- [noclip.website](https://discord.com/invite/bkJmKKv) - 浏览器内游戏查看器项目 noclip.website 的社区。

*注：还有大量针对单个游戏或系列的 Discord 服务器，此处仅列出通用逆向社区。*

### 知识库与格式数据库

- [Just Solve the File Format Problem](http://fileformats.archiveteam.org/wiki/Game_data_files) - ArchiveTeam 的文件格式 wiki。
- [XeNTaX Wiki（已关闭）](https://web.archive.org/web/20230822181840/https://wiki.xentax.com/index.php/Game_File_Format_Central) - 大型文件格式规范数据库。

### 平台与 SDK 文档

- [Psy-Q SDK 文档](https://psx.arthus.net/sdk/Psy-Q/DOCS/) - 官方 PlayStation SDK 文档归档，包含文件格式参考、开发指南与 API 文档。
  - [文件格式参考](https://psx.arthus.net/sdk/Psy-Q/DOCS/Devrefs/Filefrmt.pdf) - 官方 Psy-Q SDK 文件格式说明。
- [PSX-SPX Console Dev](https://psx-spx.consoledev.net/) - 详尽的 PlayStation 技术文档与参考，涵盖 CD-ROM 文件格式、硬件规格、BIOS 函数与开发资料。
  - [CD-ROM 文件格式](https://psx-spx.consoledev.net/cdromfileformats/) - PlayStation CD-ROM 文件格式与结构的详细说明。

### 特定游戏 Wiki

- [The Cutting Room Floor](https://tcrf.net/Help:Contents/Finding_Content) - 发现与记录游戏未使用/调试内容的社区。
- [Nintendo File Formats](https://nintendo-formats.com/) - Wii U 与 Switch 游戏的格式文档。
- [Custom Mario Kart Wiiki](https://wiki.tockdom.com/wiki/List_of_File_Formats) - Mario Kart Wii 等使用的格式。
- [Mario Kart 8 Wiki](https://mk8.tockdom.com/wiki/Main_Page) - Mario Kart 8 的格式与 Mod 文档。
- [Luma's Workshop](https://www.lumasworkshop.com/wiki/Category:File_formats) - 任天堂系的 Mod wiki。
- [Splatoon Technical Wiki](https://wiki.oatmealdome.me/index.php/Special:AllPages) - Splatoon 格式的技术文档。
- [Souls Modding Wiki](https://www.soulsmodding.com/doku.php?id=start) - FromSoftware 相关格式文档。

### 📚 学习资源与教程

- **[DGTEFF](https://web.archive.org/web/20230817151933/http://wiki.xentax.com/index.php/DGTEFF) - 探索文件格式的权威指南。**
- [The VG Resource Wiki](https://wiki.vg-resource.com/Main_Page) - 覆盖多平台的撷取/制作精灵、模型、贴图与声音的教程 Wiki。
- [Compression Deep Dive](https://chronovore.dev/posts/2023-01-25-1234P-compression-deepdive.html) - 游戏中使用的压缩算法技术剖析。
- [How to Crack a Binary File Format](https://www.iwriteiam.nl/Ha_HTCABFF.html) - 经典的二进制文件格式逆向教程。
- [kovidomi/game-reversing](https://github.com/kovidomi/game-reversing) - 面向初学者的电子游戏逆向学习资料。
- [How to Grab Models and Textures](https://aknavj.github.io/3d/2019/06/10/Grabbing-models-and-textures-from-game-or-3D-application.html) - 提取游戏模型与贴图的实战指南。
- [ReWolf's Retrogaming Blog](http://blog.rewolf.pl/blog/?cat=23) - 复古游戏与逆向工程相关博文。
- [vgmdocs](https://github.com/loveemu/vgmdocs) - 游戏音乐格式的资料与文档，含 GBA 声音驱动指南、FM 合成预设、转换工具与格式说明。
- [Inazuma-Eleven-GO-Modding](https://github.com/SxncYT/Inazuma-Eleven-GO-Modding) - 《闪电十一人 GO 光/影》功能文档，涵盖脚本、格式规范与 Mod 技巧。

#### 🎥 视频教程

- [Binary File Format Engineering and Reverse Engineering](https://www.youtube.com/watch?v=8OxtBxXfJHw) - Peter Bindels 在 ACCU 2023 的二进制文件格式分析与逆向演讲。
- [Reverse engineering game formats for fun and profit! (or just fun)](https://www.youtube.com/watch?v=MXbo6y6MCPE) - Spencer Alves 在 !!Con West 2020 的游戏文件格式逆向分享。
- [What's In A Bit - Designing, Using And Reverse-engineering Binary File Formats](https://www.youtube.com/watch?v=QEIGc3tXGmM) - Peter Bindels 在 cpponsea 的二进制格式设计与逆向演讲。
- [File Format Reverse Engineering 1 - Intro, target, and tools](https://www.youtube.com/watch?v=_zCekiF5aBQ) - CO/DE 教程系列：文件格式逆向入门、目标与工具。
- [Reverse Engineered old Compression Algorithm for Frogger](https://www.youtube.com/watch?v=BwoOB2QFXvw) - LiveOverflow：经典游戏《Frogger》压缩算法的逆向案例。

### 资产数据库

- [The VG Resource (archived)](https://archive.vg-resource.com/index.php) - 模型、贴图、音效与精灵的数据库及论坛。
  - [The Spriters Resource](https://www.spriters-resource.com/) - 专注精灵图与像素美术的数据库。
  - [The Models Resource](https://models.spriters-resource.com/) - 专注 3D 模型的数据库。
  - [The Textures Resource](https://textures.spriters-resource.com/) - 专注贴图的数据库。
  - [The Sounds Resource](https://sounds.spriters-resource.com/) - 专注音频与音乐的数据库。

## 🛠️ General Tools

*支持大量不同游戏的多格式工具。*

### 🎨 资源查看与转换

- [Noesis](https://richwhitehouse.com/index.php?content=inc_projects.php&showproject=91) - 流行的多合一模型/贴图/动画预览与转换工具，原生支持 500+ 格式，支持批量转换，插件生态丰富。
  - [Noesis Plugins (Rich Whitehouse)](https://richwhitehouse.com/index.php?content=inc_projects.php#prjmp91) - 作者官方插件合集。
  - [Noesis Plugins (HimeWorks)](https://himeworks.com/noesis-plugins/) - 社区插件，覆盖 100+ 游戏，偏 MMORPG 和动作类。
    涵盖传说系列、Midnight Club 2、龙之谷、黑暗之魂、英雄联盟、C9、Cabal Online、怪物猎人 3、超次元游戏：海王星、伊苏等。
  - [Noesis Plugins (Durik256)](https://github.com/Durik256/Noesis-Plugins) - 社区合集，150+ 插件，含最终幻想系列、黑暗之魂 2、丧尸围城 4、山脊赛车、NHL 21 等。
  - [Noesis Plugins (mrpostiga)](https://github.com/mrpostiga/noesis-plugins-official) - 额外的社区维护插件合集。
  - [Noesis Plugins (RoadTrain)](https://github.com/RoadTrain/noesis-plugins) - LS3D 引擎 (.4ds) 插件，支持《四海兄弟：失落的天堂》、Chameleon、《隐秘而危险 2》、War of Wings。
  - [Noesis Plugins (Zheneq)](https://github.com/Zheneq/Noesis-Plugins) - 面向 Megaman X8（PC）、零红蝶 4（Wii）、星球大战：原力释放（Wii）、Planet 51（Wii）、寂静岭：破碎的记忆（Wii）、火焰纹章（Wii）、MT Framework（3DS）的插件。
  - [noesis_dukemdx](https://github.com/DaZombieKiller/noesis_dukemdx) - Duke Nukem 扩展模型 MDX 格式插件。
  - [noesis_iqe](https://github.com/viciious/noesis_iqe) - 将模型导出为 Inter-Quake Export (IQE) 格式的插件。
- [TexViewer](https://github.com/Puxtril/TexViewer) - 帮助识别未知贴图格式的工具。
- [ImageHeat](https://github.com/bartlomiejduda/ImageHeat) - 编码贴图的查看工具。
  - 格式：RGBA8888、RGB888、RGB565、DXT1、ASTC、索引格式 (PAL4/8/16)。
  - 平台：PSP、PS2、PS3、PS4、Xbox（支持反去交错/反平铺）。
  - 特性：解压 (RLE、PackBits、ZLIB)、导出 DDS/PNG/BMP。
- [swizzleinator](https://github.com/v4nguard/swizzleinator) - 去平铺/去 swizzle 的图像库，`no_std` 友好，支持 PS3/PS4/X360 贴图的 swizzle/unswizzle。
- [RAW pixels viewer](https://www.kernellabs.com/rawpixels/) - 基于 Web 的原始图像数据分析工具，可显示帧缓冲/视频缓冲/未压缩视频的内存转储，交互探索宽高、偏移、翻转、色彩格式，便于识别未知像素格式。
- [DDS.Tools](https://github.com/BoBoBaSs84/DDS.Tools) - 大规模 DDS 与 PNG 互转的简易工具集，支持重复检测与排序。
- [Sprite Sheet Addon for Blender](https://www.moddb.com/engines/blender-game-engine/downloads/sprite-sheet-addon-for-blender) - Blender VSE（视频序列编辑器）精灵图拼图脚本。
- [Sprite Sheet Addon for Blender VSE](https://www.moddb.com/groups/blender-game-engine/downloads/sprite-sheet-addon-for-blender-vse) - Blender VSE 精灵图拼图脚本。
- [blender-tooling](https://github.com/bigianb/blender-tooling) - 向 Blender 导入文件的脚本集合。
- [Blender_ioEDM](https://github.com/ndevenish/Blender_ioEDM) - DCS World 使用的 .EDM 模型文件的实验性 Blender 导入/导出插件，支持基础几何、贴图、动画与连接器。
- [3ds-Max-Scripts](https://github.com/tge-was-taken/3ds-Max-Scripts) - 3ds Max 脚本归档，含多种游戏格式的模型导入与实用脚本。
- [blender_magicavoxel](https://github.com/AstrorEnales/blender_magicavoxel) - MagicaVoxel `.vox` 的 Blender 导入插件，支持层级/贪婪网格、体素 hull 减面、UV 感知材质模式。
- [MagicaVoxel-Importer](https://github.com/scayze/MagicaVoxel-Importer) - Godot 引擎插件，将 MagicaVoxel `.vox` 导入为网格，支持 Godot 3.0+，可按体素分辨率缩放与居中。
  - 选项：多种网格生成模式（体素即模型、简单立方/四边形、贪婪网格）、UV 展开、顶点色、贴图烘焙、体素 hull 修剪。
  - 材质模式：忽略、顶点色、按颜色分材质、调色板贴图、UV 展开贴图模型。
- [mviewer](https://github.com/majimboo/mviewer) - 用于查看和分析 MView 3D 文件格式的逆向工具。
- [psx-modding-toolchain](https://github.com/mateusfavarin/psx-modding-toolchain) - PS1 Mod 工具链，包含模型与贴图工具。
- [detex](https://github.com/hglm/detex) - 贴图块解压与操作的底层库。
  - 格式：BC1/DXT1/S3TC、BC2-BC3、BC4/RGTC1、BC5/RGTC2、BC6 (BPTC_FLOAT)、BC7 (BPTC)、ETC1、ETC2 系列、KTX、DDS。
  - 特性：贴图解压、像素格式转换。
- [heightmap-viewer](https://github.com/impiaaa/heightmap-viewer) - 简单的 3D 查看器，支持常规与特殊格式高程图。
- [io_mesh_ninjaripper](https://github.com/REDxEYE/io_mesh_ninjaripper) - Blender 2.78-2.79 的 NinjaRipper `.rip` 导入插件。

### 📦 Archive Extractors

- [QuickBMS](https://aluigi.altervista.org/quickbms.htm) - 通用的封包提取/回写工具，拥有覆盖数千游戏的脚本库，使用 BMS 脚本描述格式。
- [RTB-QuickBMS-Scripts](https://github.com/RandomTBush/RTB-QuickBMS-Scripts) - 各类游戏的 QuickBMS 脚本合集。
- [isodump](https://github.com/Lameguy64/isodump) - PS1 ISO 内容提取工具，支持从 PSX ISO/BIN 镜像提取文件，兼容 ISO9660 文件系统、XA/STR 文件，可生成 MKPSXISO 兼容的 XML 工程以重建 ISO。
- [UnkrawerterGBA](https://github.com/MCJack123/UnkrawerterGBA) - 针对使用 Krawall 声音引擎的 GBA 游戏的 ROM 提取/转换器，音频可导出为 XM/S3M，自动检测乐器/采样列表与模块，支持无损直读模式，可作为库使用。
- [PKGTool](https://github.com/thesupersonic16/PKGTool) - 《英雄传说：闪之轨迹》PKG 文件的提取与回打工具。
- [wad-tools](https://github.com/libertyernie/wad-tools) - WAD 封包工具（Wii/GC），源自 BFGR WadTools，增强了命令行选项（输出目录、common-key.bin 路径等），支持 C++ 与 C++/CLI 编译。
- [mymc](https://github.com/uyjulian/mymc) - PS2 记忆卡映像（PCSX2 格式）工具，支持导入/导出 MAX Drive (.max) 与 EMS (.psu) 存档，查看卡内容、新建卡、添加/提取单文件，含 GUI 与 CLI。
- [archives](https://github.com/mholt/archives) - Go 语言跨平台封包库，提供统一 API 与 `io/fs` 兼容虚拟文件系统。
  - 格式：zip、tar（含压缩变体）、rar（只读）、7z（只读）、brotli、bzip2、gzip、lz4、lzip、minlz、snappy/S2、xz、zlib、zstandard。
  - 特性：流式 API、自动格式识别、支持密码 7z/rar、无需重建即可向 tar/zip 插入、Gzip 多线程、DeepFS 透明穿透嵌套包。
- [GARbro](https://github.com/morkt/GARbro) - Galgame/视觉小说资源浏览与提取工具，支持大量格式。
  - 引擎：KiriKiri (KAG3/TJS2)、Nitro+、NScripter、Ren'Py、CatSystem2、AliceSoft、BGI/Ethornell、Liar-soft、Unity、Wolf RPG Editor、RealLive (Key/Visual Arts)、Majiro、Nekoneko Soft、Active Soft、DRS、NeXAS 等。
  - 格式：`.xp3` (KiriKiri)、`.npa` (Nitro+)、`.nsa`/`.sar`/`.dat` (NScripter)、`.rpa` (Ren'Py)、`.int`/`.hg3` (CatSystem2)、`.ald`/`.afa`/`.alk` (AliceSoft)、`.arc`/`.bsa` (BGI/Ethornell)、`.xfl` (Liar-soft)、UnityFS、`.assets` (Unity)、`.wolf`、`.data` (Wolf RPG Editor) 等 200+ 封包格式。
  - 代表作品：*Fate/stay night*、*Fate/hollow ataraxia*、*Steins;Gate*、*Chaos;Head*、*月姬*、*海猫鸣泣之时*、*残疾女孩的故事*、*心跳文学部*、*灰色果实*、*兰斯* 系列、*Clannad*、*Little Busters!*、*Muv-Luv* 系列等。

### 🔊 音频工具

- [vgmstream](https://github.com/vgmstream/vgmstream) - 支持 1000+ 游戏音频格式（循环、多声道、主机特定编码）的播放库，可单独运行或作为 Winamp/foobar2000 插件；常见游戏音频几乎都能播。
- [jpsxdec](https://github.com/m35/jpsxdec) - 跨平台 PS1 音视频转换器。
- [VGAudio](https://github.com/Thealexbarney/VGAudio) - .NET 游戏音频编解码与处理库。
  - 格式：BRSTM、BCSTM、BFSTM、IDSP、HPS、DSP（任天堂系）。
- [vgm_ripping](https://github.com/hcs64/vgm_ripping) - 游戏音乐提取工具的源码集合。
- [wwiseutil](https://github.com/hpxro7/wwiseutil) - 操作 Wwise SoundBank 与 File Package 的工具，适用于任何使用 Wwise 中间件的游戏。
  - 格式：.bnk/.nbnk（SoundBank）、.pck/.npck（File Package）、WEM（音频）。
  - 特性：解包 WEM、带元数据更新的音频替换、循环点编辑。
- [soundbank-editor](https://github.com/t1f7/soundbank-editor) - Python 版 Wwise .bnk 编辑器，列出/提取/替换 WEM，保持头/事件/元数据；适用于所有用 Wwise 的游戏。
- [Wwise-Unpacker](https://github.com/Vextil/Wwise-Unpacker) - Windows 工具，将 Wwise PCK/BNK 容器提取为 OGG/MP3，适用于任意 Wwise 游戏。
- [Wwise-BNKExtract](https://github.com/rickvg/Wwise-BNKExtract) - Wwise BNK（<=v113）提取工具，导出 WEM 以转为 OGG Vorbis。
- [wwiser](https://github.com/bnnm/wwiser) - Wwise .bnk 浏览与音频模拟器，解析 HIRC 脚本数据、生成 vgmstream 用的 TXTP、导出内容，Python 编写，适用所有 Wwise 游戏。
- [WwiseParser](https://github.com/xyx0826/WwiseParser) - C# 库，解析 Wwise 2016.1 SoundBank 对象，支持反序列化、重建 Master/Actor Mixer 层级、导出 JSON，适用所有 Wwise 游戏。
- [wwise-audio-tools](https://github.com/WolvenKit/wwise-audio-tools) - Wwise WEM 转 OGG 的静态/动态库与命令行工具，是 ww2ogg+revorb 的现代替代，便于集成。
- [ww2ogg](https://github.com/hcs64/ww2ogg) - 将 Wwise RIFF/RIFX Vorbis (.wem) 转为标准 Ogg Vorbis 的命令行工具，支持多种编码变体的打包 codebook。播放推荐 vgmstream，但需要 Ogg 输出时很有用。
- [atrac9j](https://github.com/ShadelessFox/atrac9j) - LibAtrac9 的 Java 移植，用于解码 PS 系列使用的 ATRAC9 音频。
- [BassoonTracker](https://github.com/steffest/BassoonTracker) - 纯 JS 的网页版复古 Amiga 音轨器，播放/编辑 MOD 与 FastTracker XM。
- [DSP2BRSTM](https://github.com/onepiecefreak3/DSP2BRSTM) - DSP→BRSTM 转换与多声道合并器，可将多 DSP 合为一条多声道 BRSTM，也支持 DSP→WAV。
- [fsb5_split](https://github.com/CyberBotX/fsb5_split) - 将多流 FSB5 拆成多个单流 FSB5。
- [Fmod5Sharp](https://github.com/Masusder/Fmod5Sharp) - C# 托管库，解码 FMOD 5 声音包（FSB）。
  - 格式：PCM8、PCM16、PCM32、GCADPCM、IMAADPCM、VORBIS
  - 导出：WAV（PCM）、OGG（Vorbis）
  - 特性：采样提取、元数据读取、格式检测
- [MCAConverter](https://github.com/onepiecefreak3/MCAConverter) - Capcom MCA 格式转换，支持 MCA 与 WAV 互转。
- [HIRCDump](https://github.com/neptuwunium/HIRCDump) - 通过事件 ID 导出 soundbank 采样。
- [vgmstream-funkify](https://github.com/gheskett/vgmstream-funkify) - vgmstream 库，播放各类流式游戏音频格式。
- [ray2get](https://github.com/Synthesis/ray2get) - 将《雷曼 2》(PC) 的 .apm 音乐转为 .wav。
- [libnus3audio](https://github.com/jam1garner/libnus3audio) - 操作 nus3audio 文件的 Rust 库。
- [ntrWavTool](https://github.com/turtleisaac/ntrWavTool) - 将 WAV 转为 IMA ADPCM SWAV，用于 NDS 游戏。
- [es-ps2-vag-tool](https://github.com/eurotools/es-ps2-vag-tool) - PS2 VAG ↔ WAV PCM 16-bit 转换。
- [es-xbox-adpcm-tool](https://github.com/eurotools/es-xbox-adpcm-tool) - Xbox ADPCM ↔ WAV PCM 16-bit 转换。
- [es-dsp-adpcm-tool](https://github.com/eurotools/es-dsp-adpcm-tool) - GC DSP ADPCM ↔ WAV PCM 16-bit 转换与编码。
- [es-ima-adpcm-encoder-decoder](https://github.com/eurotools/es-ima-adpcm-encoder-decoder) - IMA ADPCM ↔ WAV PCM 16-bit 转换。
- [es-eurocom-adpcm-encoder-decoder](https://github.com/eurotools/es-eurocom-adpcm-encoder-decoder) - Eurocom 自定义 ADPCM ↔ WAV PCM 16-bit 转换。
- [Citric-Composer](https://github.com/gota7/Citric-Composer) - 3DS/Wii U/Switch 声音文件编辑器，另有 [Tiniifan 分支](https://github.com/Tiniifan/Citric-Composer)。

### 🌐 翻译与本地化

- [Kuriimu](https://github.com/IcySon55/Kuriimu) - 通用游戏翻译工具箱。
- [Kuriimu2](https://github.com/FanTranslatorsInternational/Kuriimu2) - Kuriimu 的下一代版本。

### 🔍 十六进制编辑器

- [010 Editor](https://www.sweetscape.com/010editor/) - 专业十六进制编辑器，拥有强大的模板系统用于分析二进制结构（付费）。
- [ImHex](https://github.com/WerWolv/ImHex) - 现代开源十六进制编辑器，自带模式语言以逆向文件格式（免费）。
- [hexerator](https://github.com/crumblingstatue/hexerator) - 强大的 GUI 十六进制编辑器，聚焦二进制探索与模式识别，Rust 编写。
- [hexyl](https://github.com/sharkdp/hexyl) - 彩色输出的命令行十六进制查看器。
- [hex](https://github.com/cosarara/hex) - 类 vi 模式的简洁十六进制编辑器。
- [hxd-plugin-framework](https://github.com/maelh/hxd-plugin-framework) - HxD 插件框架，支持自定义文件格式。

### 🔬 格式分析与逆向

- [Kaitai Struct](https://kaitai.io/) - 声明式二进制结构描述语言，生成多语言解析代码。
- [Veles](https://codisec.com/veles/) - 开源二进制分析与可视化工具。
- [atlas](https://github.com/nblockbuster/atlas) - 用于逆向的哈希工具，插件化，支持 FNV(0/1/1a)、MD2/4/5、Murmur2/3、SipHash、SHA1/2/3、XXHash/XXHash3 等，便于分析格式中的哈希值。
- [010 Templates / ImHex Patterns](https://github.com/neptuwunium/bt) - 适用于二进制分析的模板集合。
- [010GameTemplates](https://github.com/Nenkai/010GameTemplates) - 多款游戏的 010 Editor 模板，如 GT、Forza、Project Cars、Ridge Racer 7、薄暮传说、异度神剑、碧蓝幻想：Relink、Driveclub、WWE 2K 等。
- [010-Editor-Templates](https://github.com/tge-was-taken/010-Editor-Templates) - 010 Editor 二进制模板合集。
- [mafia-formats](https://github.com/pudingus/mafia-formats) - 《四海兄弟：失落的天堂》文件格式的 010 模板。
- [chtdb](https://github.com/tge-was-taken/chtdb) - PSX 游戏的金手指/补丁数据库，主要用于 DuckStation，包含 GameShark 代码等。
- [XenonRecomp](https://github.com/hedge-dev/XenonRecomp) - 将 Xbox 360 可执行文件转换为可跨平台重编译的 C++ 代码的再编译工具。
- [DataExplorer](https://github.com/x64dbg/DataExplorer) - x64dbg 的数据浏览插件，集成 ImHex 的模式语言。
- [HexForge](https://github.com/elastic/HexForge) - IDA 插件，扩展汇编/hex 视图，可在 IDA 内直接解码/解密/修改数据。
- [FakePDB](https://github.com/Mixaill/FakePDB) - 从 IDA 数据库生成 PDB，支持 IDA≥7，可导出 JSON、生成签名、导入函数名。
- [HexRaysCodeXplorer](https://github.com/REhints/HexRaysCodeXplorer) - Hex-Rays 反编译器插件，改进 C++ 代码重建与导航，自动类型重建、虚表检测、RTTI 分析。
- [microavx](https://github.com/gaasedelen/microavx) - Hex-Rays AVX 指令提升器，扩展 IDA 对 AVX 的部分支持，示范如何用 microcode 支持新指令。
- [Ouroboros](https://github.com/Hexorg/Ouroboros) - Rust 编写的符号执行反编译器，支持 CFG、结构化重建、调用约定推断，界面基于 egui。
- [qiling](https://github.com/qilingframework/qiling) - 高级二进制仿真框架，多平台（Win/macOS/Linux/Android/BSD/UEFI/DOS）、多架构（x86/ARM/MIPS/RISC-V/PowerPC），支持 PE/Mach-O/ELF，细粒度插桩、跨架构调试与热补丁。
- [Pattern16](https://github.com/Dasaav-dsv/Pattern16) - 高速 x86-64 签名匹配库，最高 25 GB/s，使用 AVX/SSE/BMI 指令，纯头文件 C++，用于内存模式扫描。
- [Recaf](https://github.com/Col-E/Recaf) - 现代 Java 字节码编辑器，集成反编译器、内置编译器、字节码汇编器，支持标准 Java 与 Android。
- [iced](https://github.com/icedland/iced) - 高速且精确的 x86/x64 反汇编/汇编/编码库，提供 Rust/.NET/Java/Python/Lua 版本，适合游戏二进制逆向。
- [IDArling](https://github.com/IDArlingTeam/IDArling) - IDA/Hex-Rays 协作插件，允许多人同时编辑同一 IDA 数据库。
- [Reloaded.Hooks](https://github.com/Reloaded-Project/Reloaded.Hooks) - 高性能 x86/x64 函数 hook 库（.NET），支持单元测试，用于 Reloaded 模组框架。
- [Reloaded-II](https://github.com/Reloaded-Project/Reloaded-II) - 通用 .NET Core 模组框架（x86/x64），基于 DLL 注入，带模组管理、可选 SDK、丰富插件。
- [ExeGag](https://github.com/efimandreev0/ExeGag) - 在已编译 ELF 中修改游戏字符串。
- [binviz](https://github.com/VelocityRa/binviz) - 二进制可视化工具，快速发现压缩/加密、结构化数据、填充区，便于在无结构封包中定位资产边界。
- [JSC-PyDecrypt-Tool](https://github.com/bartlomiejduda/JSC-PyDecrypt-Tool) - 解密 Cocos2d 游戏的 JSC（JavaScript Compiled）文件，需要通过 Frida 抓到密钥。
- [pics](https://github.com/corkami/pics) - 文件格式的拆解与可视化资料。
- [psxrev](https://github.com/emu-russia/psxrev) - Sony PlayStation PCB/芯片逆向文档与资源。
- [Ghidra-GameCube-Loader](https://github.com/Cuyler36/Ghidra-GameCube-Loader) - Ghidra 的 NGC 二进制加载器。
- [NTRGhidra](https://github.com/onepiecefreak3/NTRGhidra) - Ghidra 的 NDS 二进制加载器。
- [Ghidra-RSP](https://github.com/Random06457/Ghidra-RSP) - Ghidra 的 N64 RSP 处理器模块与加载器。
- [dwarf2cpp](https://github.com/seilc/dwarf2cpp) - 将 ELF 中的 DWARF v1 调试信息转成 C/C++ 结构/枚举/函数定义，适合含 DWARF 调试的游戏。
- [BinaryX](https://github.com/Cuyler36/BinaryX) - 同时支持大端/小端的 BinaryReader。
- [research](https://github.com/ProjectDreamland/research) - 游戏引擎与反编译代码的研究。
- [gsaxml](https://github.com/Candoran2/gsaxml) - 编译后的 GSA（Game Script Archive）文件的二进制 XML 描述。
- [decomp-toolkit](https://github.com/encounter/decomp-toolkit) - NGC/Wii 反编译工具包。
- [splat](https://github.com/ethteck/splat) - 辅助反编译/Mod 项目的二进制拆分工具。
- [objdiff](https://github.com/encounter/objdiff) - 反编译项目的本地二进制 diff 工具。
- [decomp-permuter](https://github.com/simonlindholm/decomp-permuter) - 随机重排 C 文件以更贴近目标二进制。
- [m2c](https://github.com/matt-kempster/m2c) - MIPS 与 PowerPC 反编译器。
- [vutrace](https://github.com/chaoticgd/vutrace) - PS2 向量单元跟踪调试器。
- [hlsldecompiler-rs](https://github.com/cohaereo/hlsldecompiler-rs) - 静态链接的 3dmigoto Rust 封装，用于 HLSL 着色器反编译。

### 💻 开发库

- [assert-offset](https://github.com/cohaereo/assert-offset) - Rust 派生宏，断言结构体字段的内存偏移，适用于底层 FFI 与嵌入式。
- [ReverseBox](https://github.com/bartlomiejduda/ReverseBox) - 逆向辅助的 Python 库，提供校验和、压缩、加密、哈希、图像处理等。
  - 特性：校验 (Adler32、CRC 变体、Fletcher、XOR)、压缩 (BZIP2、LZ4、LZMA、MIO0、PackBits、RLE 变体)、加密 (ROT13、XOR)、哈希 (FNV、DJB2、MD5、SHA、Murmur3)。
  - 像素格式：100+（含 DXT、PVRTC、ETC、ASTC、BC），支持多平台 swizzle。
- [binread](https://github.com/jam1garner/binread) - Rust 二进制读取库，使用派生宏描述格式。
- [DragonLib](https://github.com/neptuwunium/DragonLib) - 面向文件格式研究的通用库。
- [GL Editor Framework](https://github.com/jupahe64/GL_EditorFramework) - 基于 OpenGL 的 3D 游戏编辑器框架，支持硬件加速渲染。
- [SFGraphics](https://github.com/ScanMountGoat/SFGraphics) - 用于渲染游戏格式的 OpenGL 图形库，广泛用于查看器。
- [MeshSharp](https://github.com/MinshuG/MeshSharp) - 纯 C# 的 3D 库，读写多种格式。
  - 格式：FBX、STL、PLY。
- [Assimp.Net](https://github.com/StirlingLabs/Assimp.Net) - Assimp（Open Asset Import Library）的 .NET Core 封装，导入 3D 模型。
- [ooz](https://github.com/powzix/ooz) - Oodle 压缩格式（Kraken/Mermaid/Selkie/Leviathan/LZNA/Bitknit）开源解压器，常见于 Warframe 等现代游戏。
- [Syroot.BinaryData](https://gitlab.com/Syroot/BinaryData) - .NET 简化二进制读写的库，支持多端序与编码。
- [Amicitia.IO](https://github.com/tge-was-taken/Amicitia.IO) - 高性能文件 IO 库，全面支持大端与偏移。
- [SharpRiff](https://github.com/gigaherz/SharpRiff) - .NET RIFF 读写库，适用于 WAV/AVI/WebP。
- [XeNTaXTools-Legacy](https://github.com/XeNTaXTools/XeNTaXTools-Legacy) - 从 XeNTaX 论坛收集的旧工具。
- [formast](https://github.com/amorilia/formast) - 通过简单 API 暴露文件格式描述的库。
- [vmf](https://github.com/Galaco/vmf) - Go 库，解析 Valve Hammer 的 .vmf 地图。
- [GameFormatReader](https://github.com/lioncash/GameFormatReader) - 读取多种游戏格式的库（偏任天堂）。
- [CTLib](https://github.com/narahiero/CTLib) - Mario Kart Wii 自定义赛道使用的格式创建/转换工具库。
- [Byaml-Tool](https://github.com/KillzXGaming/Byaml-Tool) - 简单 BYAML 工具，当前主要做端序转换（基于 Syroot Byaml 库）。
- [tinybcdec](https://github.com/jandk/tinybcdec) - 纯 Java 小型块压缩解码库，零依赖，注重速度与准确，可部分解码。
  - 格式：BC1-DXT1、BC2-DXT3、BC3-DXT5、BC4-ATI1、BC5-ATI2、BC6H、BC7。
- [Console-Swizzler](https://github.com/matyamod/Console-Swizzler) - C 语言库，为主机游戏处理 DDS 贴图 swizzle/unswizzle，支持 PS4/Switch，可配置 GOB block 高度，附 CLI 批处理。
- [prs.net](https://github.com/FraGag/prs.net) - PRS 压缩/解压库及 GUI（.NET），PRS 基于 LZ77+RLE，广泛用于 SEGA Saturn 以来的游戏（含 PSU）。
- [NKZIPLib](https://github.com/pixeldesu/NKZIPLib) - 解析早期 2000s MMO 使用的 NKZIP 封包的 C# 库，格式简单无压缩，顺序存放文件并含魔数/版本/大小/数量。

### 📂 脚本合集与多游戏工具

- [noclip.website](https://github.com/magcius/noclip.website) - 浏览器内 3D 查看器，支持 60+ 游戏与多平台。
  - 游戏：Source 系列（含 HL2、Portal1/2、TF2、CS:GO、L4D2 等 17 款），任天堂（马里奥 64、马车系列、塞尔达系列、皮克敏、路易鬼屋、银河 1/2、纸片马里奥系列、星之卡比、任天堂明星大乱斗 Melee/Brawl），Rare（班卓熊、DKC），GTA（3/VC/SA），古惑狼、黑暗之魂、块魂、大神、脑航员、极品飞车：最高通缉、海绵宝宝系列、Outer Wilds、Halo CE 等。
- [GameArchives](https://github.com/PikminGuts92/GameArchives) - C# 库，读取 14+ 游戏封包格式。
  - 游戏：Harmonix（Frequency、Amplitude、吉他英雄系列、摇滚乐队 1-4、Beatles、Green Day、Lego、VR、Karaoke Revolution、Disney Fantasia）、科乐美音游（DDR Universe 1-3、DDR 2010、Dance Masters）、FreeStyleGames（DJ Hero 系列、Guitar Hero Live、Sing Party）、Psychonauts、Power Gig 等。
  - 格式：Ark、PSARC、PACKAGE、PFS、STFS、XDVDFS、U8。另有 [maxton 分支](https://github.com/maxton/GameArchives) 增加 Sing Party 的 FSAR。
- [psarc](https://github.com/ShadelessFox/psarc) - PSARC 封包查看/提取，提供 GUI 与 CLI。
- [MeltyTool](https://github.com/MeltyPlayer/MeltyTool) - Multitool for viewing/extracting assets from various N64/GCN/3DS/PC games.
  - Games: Super Mario 64, Mario Artist (Polygon Studio, Talent Studio), Paper Mario TTYD, Super Paper Mario, Mario Kart Double Dash, Pikmin 1 & 2, Super Mario Sunshine, Chibi-Robo, Super Smash Bros. Melee, Battalion Wars 1 & 2, Super Mario 64 DS, Luigi's Mansion 3D, Majora's Mask 3D, Ocarina of Time 3D, Professor Layton vs. Phoenix Wright, Dead Space, Glover, Halo Wars, Celeste 64, Pokemon Colosseum, and more.
- [Noesis Plugins](https://richwhitehouse.com/index.php?content=inc_projects.php&showproject=91) - Community plugin collections extending Noesis support to hundreds more games.
  - See [6 major plugin collections](https://richwhitehouse.com/index.php?content=inc_projects.php#prjmp91) including Tales series, Midnight Club 2, Visceral Games titles, and many more formats.
- [EdnessP/scripts](https://github.com/EdnessP/scripts) - Collection of scripts for various game file formats.
  - Games: Bully series, Burnout series (1, 2, 3, Legends, CRASH!), Call of Duty: Finest Hour, Jak & Daxter series (1, II, 3, X), Midnight Club series (2, 3), Saints Row series (2, Undercover), The Sims series (Bustin' Out, Urbz, 2, Pets, Castaway), The Simpsons Game, Tomb Raider (Wii), Need for Speed: Shift (PSP), Activision/Atari Anthology, Adventure Time, Bomberman Act:Zero, Big Rigs, Castle Strike, Driver: San Francisco, Epic Mickey, Exit, Freaky Flyers, Ready 2 Rumble Boxing, SpongeBob's Surf & Skate Roadtrip, Strike Suit Zero/Infinity, Yakuza 1 & 2 (PS2), and more.
- [bartlomiejduda/Tools](https://github.com/bartlomiejduda/Tools) - Collection of tools to manage and modify files from many various games. Includes archive tools, binary templates, and format-specific utilities.
  - Games: 150+ titles including Harry Potter series, Bully, Crash Bandicoot series, Tony Hawk's Underground, Sonic 2006/Unleashed, Resident Evil 7, Silent Hill series, Just Cause, Splinter Cell, SimCity 3000, LEGO games, The Sims series, Super Mario Sunshine, Star Wars Jedi Academy, Tekken 5, Transformers, Beyond Good & Evil, and many more.
- [Murugo/Misc-Game-Research](https://github.com/Murugo/Misc-Game-Research) - Research artifacts and tools for various games.
  - Games: Vib-Ribbon (PS1), Gitaroo Man (PS2), Silent Hill 2 & 3 (PS2), Kingdom Hearts series (PS2), Rule of Rose (PS2), Musashi: Samurai Legend (PS2).
- [game-extraction-toolbox](https://github.com/shawngmc/game-extraction-toolbox) - Python CLI tools for extracting ROMs from game rereleases and investigating game files.
  - Supports extracting ROMs from collections like Capcom Arcade Stadium, Street Fighter 30th Anniversary Collection, Mega Man Legacy Collections, SNK 40th Anniversary Collection, and many more.
- [save-decrypters](https://github.com/bucanero/save-decrypters) - Collection of custom save-game decrypters and checksum fixers for PS3, PSP, and PS4.
  - Games: GTA5, The Last of Us, Uncharted series, Metal Gear Solid series, Resident Evil series, Final Fantasy XIII series, and many more.
- [HyoutaTools](https://github.com/AdmiralCurtiss/HyoutaTools) - .NET CLI collection of tools for packing and unpacking video game archives. Includes functions for extracting data from and reinserting data into various games.
- [vgm-disasm](https://github.com/loveemu/vgm-disasm) - Disassembly collection of classic video game music drivers. Disassembles VGM (Video Game Music) files for educational and preservation purposes.
- [RTB-3DSMax-Scripts](https://github.com/RandomTBush/RTB-3DSMax-Scripts) - Comprehensive collection of 3ds Max scripts for importing models from dozens of games and engines.
  - Games: Pokémon (Switch/3DS), Zelda (BOTW/TOTK/Wind Waker HD), Mario (Odyssey/Kart 8/3D World), Splatoon (1-3), Hyperdimension Neptunia series, Crash Bandicoot N. Sane Trilogy, Sonic (Unleashed/Riders), Telltale Games (Walking Dead/Batman), and many more.
  - Highlights: Support for ISM2, IGZ, MDL, D3DMesh, and Nintendo BFRES/BCH formats across PS1, PS3, Wii, Wii U, and Switch.

## ⚙️ 引擎

*面向主流第三方游戏引擎的工具。*

### GameMaker

- [UndertaleModTool](https://github.com/UnderminersTeam/UndertaleModTool) - GameMaker 游戏的 Mod/反编译工具。
- [GMS-Explorer](https://github.com/puggsoy/GMS-Explorer) - Game Maker Studio `data.win` 浏览器。
- [GMSD](https://github.com/lynn/GMSD) - GameMaker Studio 反编译器（F#）。
- [UndertaleTools](https://github.com/fjay69/UndertaleTools) - GameMaker data.win 解包/回打工具。
- [pugIFF](https://github.com/nkrapivin/pugIFF) - GameMaker IFF 游戏文件读取器（GML）。
- [YYTextureView](https://github.com/YAL-GameMaker-Tools/YYTextureView) - 查看 GameMaker 游戏贴图的工具。
- [libaltar](https://github.com/Prashant-Jonny/libaltar) - 处理 GameMaker: Studio 二进制格式的库（含反编译）。
- [gamemaker2-data-research](https://github.com/jam1garner/gamemaker2-data-research) - GameMaker 2 数据文件的工具/文档。
- [LojRipper](https://github.com/nkrapivin/LojRipper) - 从 GameMaker YYC 编译可执行文件导出 .win 用于 Mod。

### Source (Valve)

- [valve-bsp-parser](https://github.com/ReactiioN1337/valve-bsp-parser) - Valve BSP（地图）解析器。
- [Blender Source Tools](https://github.com/Artfunkel/BlenderSourceTools) - Blender 插件，导入/导出 Source 引擎模型与动画格式，在 Blender 中制作/修改 Source 资产。
- [noclip.website (Source Engine)](https://github.com/magcius/noclip.website/tree/main/src/SourceEngine) - 浏览器版 Source 引擎地图查看器，支持 CS:S、HL2 全系列、TF2、Portal 1/2、CS:GO、L4D2、The Stanley Parable、Infra、Neo Tokyo、Estranged Act I 等。
- [noclip.website (GoldSrc)](https://github.com/magcius/noclip.website/tree/main/src/GoldSrc) - 浏览器版 Half-Life（GoldSrc）查看器。
- [srctools](https://github.com/TeamSpen210/srctools) - 操作 Source 文件格式的 Python 模块。
  - 格式：VMF、BSP、VPK。
- [vdf-parser](https://github.com/lukezbihlyj/vdf-parser) - 解析 Source 游戏使用的 VDF（Valve Data Format）。
- [go-valve](https://github.com/handsomematt/go-valve) - Go 库，查询 Source 服务器的 A2S 信息。
- [valve-vrm](https://github.com/UnBeatWaterGH/valve-vrm) - Valve 实验性 VRM 模型格式的文档与转换器。
- [sledge-formats](https://github.com/LogicAndTrick/sledge-formats) - C# 解析器，适配 Half-Life 1 及相关引擎。
- [corvid](https://github.com/KILLTUBE/corvid) - 将 Source 引擎关卡转换到《使命召唤》。
- [Plumber](https://github.com/lasa01/Plumber) - Blender 插件，导入 Source 1 地图/模型/材质/贴图（CS:GO/TF2/CS:S 等）。
  - 特性：完整地图导入（刷子、叠加、灯光、道具、天空盒）、MDL/材质/贴图导入（含配色）、内嵌文件浏览。
- [powerjack](https://github.com/cohaereo/powerjack) - TF2 资产查看/演示播放器，直接从 BSP 采样光照贴图以改进渲染。
- [SourceOps](https://github.com/bonjorno7/SourceOps) - Blender 导出 Source 1 模型的插件，比 BST 更便捷；可导出对象为 SMD/FBX、动作为 SMD，基于 UI 生成 QC，按钮一键编译/预览，实验性导出刷子/地形为 VMF。需 Blender 2.83+。
- [io_mesh_SourceBSP](https://github.com/REDxEYE/io_mesh_SourceBSP) - Blender 导入/导出 Source BSP 地图插件。
- [io_texture_VTF](https://github.com/REDxEYE/io_texture_VTF) - Blender 导入/导出 Source VTF 贴图插件（已归档）。
- [AutoMDL](https://github.com/NvC-DmN-CH/AutoMDL) - Blender 4+ 插件，自动将 models 目录下的 .blend 编译为 .mdl，支持 Hammer++ 热加载、自动材质路径、碰撞模型、studiomdl.exe 集成。
- [AutoVTF](https://github.com/NvC-DmN-CH/AutoVTF) - C# WinForms VTF 工具，监听材质目录自动转 VTF，保留设置；支持拖拽、进阶 VTF 选项、Hammer++ 热加载。
  - 格式：PNG/BMP/TGA/JPG/PSD（输入），VTF（输出）。
- [StdPatch](https://github.com/kohtep/StdPatch) - StudioMDL 编译器补丁，移除 Source 模型编译限制，扩展顶点/权重/表情控制数组以支持高模；附 StdInjector 用于向 studiomdl 进程注入。
- [3D Studio Max SMD Import Plugin](https://www.moddb.com/games/half-life/downloads/3d-studio-max-smd-import-plug-in-import-smd-mode) - 3DS Max 9/2008/2009 导入 Valve SMD 插件（灵感来自 Cannonfodder 对 5-7 版的工作）。
- [3D Studio Max SMD Export Plug-in](https://www.moddb.com/games/half-life/downloads/3d-studio-max-smd-export-plug-in) - 3DS Max 9/2008/2009 导出 Source 参考与动画 SMD，支持多/子材质、Editable Mesh/Poly、Skin/Physique、辅助节点。
- [Dvondrake's SMD exporter for Blender](https://www.moddb.com/groups/source-developers/downloads/dvondrake-smd-blender) - Blender 首个完整 Source SMD 导出器，支持参考/物理/动画，附视频教程。
- [Autodesk Softimage Mod Tool 7.5 (Source Developers)](https://www.moddb.com/groups/source-developers/downloads/autodesk-softimage-mod-tool-75) - 原 XSI Mod Tool，免费的 Autodesk Softimage，提供 Source、CryEngine2、UE3、XNA、Unity 等插件。
- [Blender3D SMD Exporter (Half-Life 2)](https://www.moddb.com/games/half-life-2/downloads/blender3d-smd-exporter) - 让 Blender3D 导出 HL2 SMD，支持绑定网格与动画。
- [ValveResourceFormat](https://github.com/ValveResourceFormat/ValveResourceFormat) - Source 2 Viewer，可浏览 VPK、查看/提取/反编 Source 2 资产（地图/模型/材质/贴图/声音等），并附 C# 库读写 Valve 资源文件。
- [studiomodel](https://github.com/Galaco/studiomodel) - Go 库，加载 Valve studiomodel 格式。
  - 格式：.mdl、.vtx、.vvd。
- [VTFLib](https://github.com/NeilJed/VTFLib) - 读写 VTF/VMT 贴图/材质的 C/C++ 库。
- [source-engine](https://github.com/nillerusr/source-engine) - Valve 2017 版 Source 引擎修改版（2020 泄露，非商业用途）。
- [Kisak-Strike](https://github.com/SwagSoftware/Kisak-Strike) - 可完整构建的 Source1 版 CS:GO 开源移植，需原游戏资源。
- [GtkRadiant](https://github.com/TTimo/GtkRadiant) - 开源跨平台关卡编辑器，适配 id Tech 与 Source。
- [Goldsrc Model Viewer (V 0.3a Beta2)](https://www.moddb.com/games/half-life/downloads/goldsrc-model-viewer-v-03a-beta2-archived-for-other-use) - GoldSrc（HL1）模型查看器，支持 MDL（v0.3a Beta2，已归档；暂不支持 MDL v4）。
- [Half Life 2 MDL (v37) Importer V 0.9 Beta for 3DS](https://www.moddb.com/games/half-life-2/downloads/half-life-2-mdl-v37-importer-v-0-9-beta-for-3ds)
- [Jed's Half-Life Model Viewer 1.36](https://www.moddb.com/games/half-life/downloads/jeds-half-life-model-viewer-136) - 带皮肤编辑与包浏览的 HL 模型查看器 (v1.36)。
- [Source Model Viewer [Build: 2019-04-23] (Half-Life 2)](https://www.moddb.com/games/half-life-2/downloads/source-model-viewer-build-2019-04-23)
- [VTF-2-TGA Convertor Utility (Half-Life 2)](https://www.moddb.com/games/half-life-2/downloads/vtf-2-tga-convertor-utility) - 批量将 VTF 转为 TGA。
- [Texture Tool v1.2.1 (Half-Life)](https://www.moddb.com/mods/half-life-episode-two/downloads/texture-tool) - 为 Trinity\\Abyss 外部加载器生成 detailtextures.txt，便于批量标记高分辨率贴图。
- [BSP Decompiler by 005 (Half-Life)](https://www.moddb.com/games/half-life/downloads/bsp-decompiler-by-005) - BSP 反编译器（支持度因引擎而异），可输出多种地图编辑器格式。
- [Bloody Knife + Addon DB Skin Tutorial (Counter-Strike: Source)](https://www.moddb.com/games/counter-strike-source/downloads/bloody-knife-addon-db-skin-tutorial) - 官方教程插件，含 20+ 分钟配音视频，演示 Source 系游戏改皮肤。
- [Bloodlines Character Search Tool v1.0 (Vampire: The Masquerade �?Bloodlines)](https://www.moddb.com/games/vampire-the-masquerade-bloodlines/downloads/bloodlines-character-search-tool-v10)
- [Detail Tool v1.0 (Half-Life)](https://www.moddb.com/mods/half-life-episode-two/downloads/detail-tool-v10) - 为 Trinity\\Abyss detail 生成器自动生成 detailtextures.txt。
- [Game Server Browser & Admin Tool 1.2.1 (Half-Life 2)](https://www.moddb.com/games/half-life-2/downloads/game-server-browser-admin-tool-1-2-1) - 服务器浏览与管理工具。
- [GMad Extractor (Garry's Mod)](https://www.moddb.com/mods/garrys-mod-11-half-life-rebuilt/downloads/gmad-extractor) - GUI 工具，提取 Garry's Mod 插件 (.GMA)。
- [Half Life 1 Modding Kit Addon 2](https://www.moddb.com/mods/half-life-modding-kit/downloads/half-life-1-modding-kit-addon-2) - HL1 Mod 地图与预制（武器/车辆/道具等，未全部验证）。
- [Half-Life Asset Manager V3.0.0](https://www.moddb.com/games/half-life/downloads/half-life-asset-manager-v300) - 基于 HL Model Viewer 2 改进的模型工具；HL1/GoldSource 最佳查看器（不支持 HL2/Source/Source2）。
- [Half-Life DLL Decompiler](https://www.moddb.com/games/half-life/downloads/half-life-dll-decompiler) - Steam 前零售版 HL 的 DLL 反编译器，附源码。
- [Half-Life: Insecure - Mapping Tools and Source Code v1.3](https://www.moddb.com/mods/half-life-insecure/downloads/half-life-insecure-mapping-tools-and-source-code-version-13) - HL: Insecure 模组的地图工具与源码，针对 Steam 版 HL (v1.3)。
- [Half-Life Quick Mod Creation tool](https://www.moddb.com/games/half-life/downloads/half-life-quick-mod-creation-tool) - 快速生成 HL 模组骨架（liblist.gam 与目录）。
- [Half-Life to Quake 3 .MAP converter](https://www.moddb.com/games/half-life/downloads/half-life-to-quake-3-map-converter) - 将 Worldcraft 3.3 输出的 .map 与 Quake3 互转的小工具。
- [Half-Life Unified SDK Map Decompiler (Counter-Strike)](https://www.moddb.com/games/counter-strike/downloads/half-life-unified-sdk-map-decompiler) - SamVanheer 的 HL1 BSP v29/v30 反编译器（C#），亦支持 HL/Alpha 0.52，含树/面两种反编策略并自动应用 Nodraw。
- [Keybinder Source Tool (Counter-Strike: Source)](https://www.moddb.com/games/counter-strike-source/downloads/keybinder-source-tool) - 英德双语 CS:S 配置工具，快速绑键/买枪并调 30+ 图形设置，含专家模式与备份。
- [Jed's Half-Life Model Viewer 1.36 (Counter-Strike)](https://www.moddb.com/games/counter-strike/downloads/jeds-half-life-model-viewer-1361) - 带皮肤编辑与包浏览功能的 HL 模型查看器 (v1.36)。
- [Xash studioMDL Goldsrc Large Model Compiler (Counter-Strike)](https://www.moddb.com/games/counter-strike/downloads/xash-studiomdl-goldsrc-large-model-compiler) - HL 大模型编译器，支持 16MB 模型、9x blending、$texrendermode、最高 1024x1023 贴图。
- [Half-Life Studio Model Decompiler v1.2.1 (Win32, Linux, Mac)](https://www.moddb.com/games/half-life/downloads/half-life-studio-model-decompilerwin32-linux-mac) - 跨平台 HL Studio 模型反编译器，改进 mdldec：检测 texrendermode、自定义活动、Paranoia2/PrimeXT 特性，修复 UV/动画，输出类似 Crowbar .qc。
- [Valve Batch Compile Tool](https://www.moddb.com/engines/source/downloads/valve-batch-compile-tool) - Valve 地图批量编译管理器。
- [XSI Valve Source Tools](https://www.moddb.com/downloads/valve-source-tools) - Mod Tool 7.5/6 与 32 位 Softimage 的 Source 插件，含 SMD/VMF 导入导出、权重图、骨架工具、样例骨架。
- [Wedge MDL Compiler (QC Generator) 1.0.1](https://www.moddb.com/company/wedge/downloads/wedge-mdl-compiler-qc-generator-1-0-1) - 快速生成 QC 并编译 MDL（俄语，需注册）。
- [Windows Vista/7 Phoneme Extractor 1.3](https://www.moddb.com/groups/source-developers/downloads/windows-vista7-phoneme-extractor-13) - Source 2007/2009 的 Faceposer 口型提取器，在 Vista/7 效果更好。
- [XSI Mod Tool 6.01](https://www.moddb.com/groups/source-developers/downloads/xsi-mod-tool-601) - 免费版 Softimage|XSI，支持 Source、CryEngine2、UE3、XNA、Unity 等。

### Unity

- [UABEANext](https://github.com/nesrak1/UABEANext) - SerializedFile 与 AssetBundle 的研究/Mod 工具。
- [AssetStudio (Perfare)](https://github.com/Perfare/AssetStudio) - 经典版 Asset/Bundle 浏览、提取、导出工具。
- [AssetStudio (aelurum fork)](https://github.com/aelurum/AssetStudio) - 活跃维护分支，UI 优化与增强。
- [AssetStudio (zhangjiequan fork)](https://github.com/zhangjiequan/AssetStudio) - 延续 Perfare 版，支持更新 Unity 版本并改进。
- [UABEA (Unity Asset Bundle Extractor Avalonia)](https://github.com/nesrak1/UABEA) - 基于 Avalonia 的跨平台 UABE（C#），适配新 Unity 版本，编辑/提取 AssetBundle 与 SerializedFile。
- [UnityExplorer](https://github.com/sinai-dev/UnityExplorer) - 运行时 UI，探索/调试/修改 IL2CPP 与 Mono Unity 游戏。
- [Unity Asset Editor v0.2 (7 Days To Die)](https://www.moddb.com/games/7-days-to-die/downloads/unity-asset-editor) - 插件式资产编辑/导入/导出器，支持原始数据格式，可扩展新资产类型 (v0.2)。
- [Il2CppDumper](https://github.com/Perfare/Il2CppDumper) - 提取 Unity IL2CPP 元数据并转换二进制的逆向工具。
- [Il2CppInspector](https://github.com/djkaty/Il2CppInspector) - 自动化 IL2CPP 逆向工具，输出 C# 存根、.NET 过渡 DLL、C++ 脚手架。
- [UnityPy](https://github.com/K0lb3/UnityPy) - Python 模块，提取/解包/编辑 Unity 资产。
- [AssetsTools.NET](https://github.com/nesrak1/AssetsTools.NET) - 基于 UABE 的 Unity 资产/Bundle 读写库。
- [CC3Decrypt](https://github.com/tge-was-taken/CC3Decrypt) - 解密 Chain Chronicle 3 使用的 Bundle 头。
- [Unity3DCompressor](https://gitgoon.dev/IllusionMods/Unity3DCompressor) - LZ4 压缩 Unity Bundles，减小体积、加快加载。
- [XUnity.AutoTranslator](https://github.com/bbepis/XUnity.AutoTranslator) - Unity 通用机翻框架，支持多翻译后端与 IL2CPP。
- [il2cpp-modder](https://github.com/juanmjacobs/il2cpp-modder) - 生成 IL2CPP 游戏 DLL 注入模板，自动生成 Hook/字段修改/实现替换代码，无需手写指针计算。

### Unreal Engine

- [pyUE4Parse](https://github.com/MinshuG/pyUE4Parse) - Python 编写的 UE4 资产解析器。
- [Unreal-Mappings-Archive](https://github.com/TheNaeem/Unreal-Mappings-Archive) - Unreal 引擎映射文件归档。
- [io_scene_psk_psa](https://github.com/DarklightGames/io_scene_psk_psa) - Blender 导入/导出 UE PSK（骨骼网格）/PSA（动画）插件，支持法线、额外 UV、顶点色、形态键。
- [io_scene_ase](https://github.com/DarklightGames/io_scene_ase) - Blender 导出 UE1/UE2 使用的 ASE（ASCII Scene Export）格式（如 UT2004）。
- [UEViewer (UModel)](https://github.com/gildor2/UEViewer) - UE1-4 资产查看/导出器（UE Viewer）。
  - [兼容性表](https://www.gildor.org/projects/umodel/compat) - 官方列表。
- [UE4Dumper](https://github.com/kp7742/UE4Dumper) - UE4 资产与结构转储工具。
- [UAssetGUI](https://github.com/atenfyr/UAssetGUI) - GUI 查看/编辑 UE UAsset 文件。
- [blender3d_import_psk_psa](https://github.com/Befzz/blender3d_import_psk_psa) - Blender 导入 UE PSK/PSA。
- [repak](https://github.com/trumank/repak) - Rust 编写的 UE .pak 库与 CLI。
- [Unreal-Library](https://github.com/EliotVU/Unreal-Library) - UE 文件格式读写库。
- [UE4-AES-Key-Extracting-Guide](https://github.com/Cracko298/UE4-AES-Key-Extracting-Guide) - 提取 UE4 AES 密钥指南。
- [uesave-rs](https://github.com/trumank/uesave-rs) - Rust 库，读写 UE 存档文件。
- [UAssetAPI](https://github.com/atenfyr/UAssetAPI) - 低层 .NET UE 资产读写库。
- [UEFormat](https://github.com/h4lfheart/UEFormat) - UE 文件格式处理库。
- [UEAssetToolkit](https://github.com/Archengius/UEAssetToolkit) - UE 资产提取与修改工具集。
- [FModel](https://fmodel.app/) - 开源 UE4-5 数据挖掘工具。
- [CUE4Parse](https://github.com/FabianFG/CUE4Parse) - C# UE 归档解析器。
- [UnrealExporter](https://github.com/luk-gg/UnrealExporter) - 批量导出工具。
- [UE-Modding-Tools](https://github.com/Buckminsterfullerene02/UE-Modding-Tools) - UE 通用 Mod 工具数据库。
- [Snooper](https://github.com/FModel/Snooper/tree/opengl) - 基于 OpenGL 的烹饪包 3D 查看器。
- [ActorX Tools](https://www.moddb.com/groups/unreal-tournament-3-mod-developers/downloads/actorx-tools-for-maya-85-3dsmax-9) - ActorX 插件，可在多种 3D 软件中导入 UE 骨骼网格与动画。
- [ActorX Softimage Exporter](https://www.moddb.com/downloads/actorx-softimage-exporter) - Softimage 的 ActorX 导出插件，将骨骼网格/动画导出为 UE 可导入的二进制；安装至 \\Application\\Plugins。
  - 格式：.psk、.psa（骨骼与动画）、.ase（静态网格）。
- [kismet-analyzer](https://github.com/trumank/kismet-analyzer) - 分析/操作烹饪 UE 资产中的 kismet 字节码，生成 CFG 与类层次。
- [BPPseudoCodeGen](https://github.com/Archengius/BPPseudoCodeGen) - 从解析后的蓝图代码生成 C++ 伪代码。
- [unhood](https://github.com/yole/unhood) - UE3 版 UnrealScript 反编译器，测试于 UT3，兼容 Gears/Mass Effect/Mirror's Edge 等。
- [U3D](https://www.moddb.com/games/unreal-tournament/downloads/u3d-v10-unreal-model-conversion-tool) - Unreal 模型转换工具，解决现有转换器版本/限制问题。
- [Unreal to Deus Ex mesh converter](https://www.moddb.com/games/deus-ex/downloads/unreal-to-deus-ex-mesh-converter) - 将 Unreal/UT 网格转换为 Deus Ex 格式，可结合 MilkShape、3ds2unr 等导出。
- [DUT TOOL-2.0.2.0 (Unreal Tournament 3)](https://www.moddb.com/mods/defend-unreal-territories/downloads/dut-tool-2020) - C# 制作 UT3 模组的工具 (v2.0.2.0)。
- [UEd Style Tools for Maya (Unreal Tournament)](https://www.moddb.com/games/unreal-tournament/downloads/ued-style-tools-for-maya) - Maya 窗口，提供 UEd 风格 CSG 工具，处理 Maya/UEd 尺寸差异。
- [UShock - Unreal level viewer (Unreal Tournament)](https://www.moddb.com/games/unreal-tournament/downloads/ushock-unreal-level-viewer) - 实验性关卡查看器，支持 Unreal1-UT2004，自动加载依赖包并用 OpenGL 渲染。
- [Unreal Unit Converter](https://www.moddb.com/downloads/unreal-unit-converter1)
- [PS3 Mod Tools version 2.1 (Unreal Tournament 3)](https://www.moddb.com/games/unreal-tournament-3/downloads/ps3-mod-tools-version-21) - 发布支持 PS3 的 UT3 模组工具 (v2.1)。
- [WOTgreal Package Exporter (Unreal Tournament)](https://www.moddb.com/games/unreal-tournament/downloads/wotgreal-package-exporter) - 查看/导出 UE1/2 静态贴图、模型、声音，并反编译 UC。
- [Advanced Model Support SDK (Unreal Tournament)](https://www.moddb.com/mods/ut-skins-voices-mods-fixes/downloads/advanced-model-support-sdk) - UT 插件玩家模型 (AMS v102/v110) 制作文档，亦适用于大型模组的骨骼模型与 AMS 代码。
- [Blender 2.49 Scripts for UT2004](https://www.moddb.com/games/unreal-tournament-2004/downloads/blender-249-scripts-for-ut2004) - UT2004 的 Blender 2.49 脚本集合，含 PSA/PSK 转换、IQM/ASE 等。
- [February 2015 Unreal Development Kit (UDK)](https://www.moddb.com/engines/unreal-development-kit/downloads/february-2015-unreal-development-kit-udk) - 最后一版 UDK（2015 年 2 月），UE3 免费版。

### CryEngine

- [Far Cry 1 Noesis import plugin](https://www.moddb.com/games/far-cry/downloads/far-cry-1-noesis-import-plugin) - Noesis 导入 FC1 模型插件（不支持导回 CryEngine）。
- [Far Cry 1 3dsmax 9 plugin](https://www.moddb.com/games/far-cry/downloads/far-cry-1-3dsmax-9-plugin) - 3DS Max 9 导出 FC1 模型插件。
- [CryEngine 2 3d archive](https://www.moddb.com/games/crysis/downloads/cryengine-2-3d-archive) - CryEngine 2 资源与文件归档，用于 Crysis/Crysis Wars Mod。
- [CryENGINE 2 Resources (Crysis)](https://www.moddb.com/games/crysis/downloads/cryengine-2-resources1) - 同上，CryEngine 2 资源归档。
- [CryEngine2 Archive (Crysis)](https://www.moddb.com/games/crysis/downloads/cryengine2-archive) - CryEngine 2 教程归档（浏览器可读）。
- [Crysis Benchmarking Tool 1.05](https://www.moddb.com/games/crysis/downloads/crysis-benchmarking-tool-1-05) - Crysis 性能测试前端 (v1.05)。
- [Cryengine Mod SDK 1.4 (Far Cry)](https://www.moddb.com/games/far-cry/downloads/cryengine-mod-sdk-14) - Crytek 发布的 Far Cry 1 官方 SDK (v1.4)。
- [Enhanced Gibbed Tools with Hash Decoder (Far Cry 2)](https://www.moddb.com/games/far-cry-2/downloads/enhanced-gibbed-tools-with-hash-decoder) - Wobatt 修改的 Gibbed FC2 工具，增加哈希解码；基于 Rick 原版工具，非官方。
- [Far Cry 2 Mod Tools](https://www.moddb.com/mods/far-cry-2-redux/downloads/far-cry-2-mod-tools) - 更新版 FC2 Mod 工具，功能增强与兼容性提升。
- [Far Cry 3 Mod Tools](https://www.moddb.com/mods/far-cry-3-redux/downloads/far-cry-3-mod-tools) - 更新版 FC3 Mod 工具。
- [FCMAP Tool v0.3B-0.5B (Far Cry)](https://www.moddb.com/mods/fcmap-tool/downloads/fcmap-tool-v03b-05b) - 💙 首个自动化 Far Cry 1 地图/Mod 工具，Python3 编写。
- [FCMAP Tool v1.0 (Far Cry)](https://www.moddb.com/mods/fcmap-tool/downloads/fcmap-tool-v05-10) - 💙 同上，v1.0 版本。

### Hedgehog Engine

- [HedgeLib](https://github.com/Radfordhound/HedgeLib) - 为《索尼克》系列 Mod 提供的 C++ 库与工具集合。
- [Hedgehog Engine Blender I/O](https://github.com/hedge-dev/HedgehogEngineBlenderIO) - WIP Blender 插件，支持 Hedgehog Engine 的导入/导出与动画编辑。
- [RflTemplates](https://github.com/blueskythlikesclouds/RflTemplates) - Hedgehog Engine 2 RFL 文件的 010 模板。
- [surfboard-templates](https://github.com/DeaTh-G/surfboard-templates) - Hedgehog 系列使用的 SWIF 格式各版本模板。
- [HedgehogEngineReversing](https://github.com/WistfulHopes/HedgehogEngineReversing) - Hedgehog 引擎逆向的 BinSync 项目。
- [Shadow-the-Hedgehog-.BON-MTN-import-export-tool](https://github.com/Shadowth117/Shadow-the-Hedgehog-.BON-MTN-import-export-tool) - 脚本：将《Shadow the Hedgehog》.BON 的外部属性应用到使用 AAP RWIO 导入后的 .DFF 骨骼上。
- [SonicHeroesUTXEditor](https://github.com/Heroes-Hacking-Central/SonicHeroesUTXEditor) - 《索尼克英雄》UTX 编辑器。

### Northlight Engine

- [BlenderNorthlight](https://github.com/OpenAWE-Project/BlenderNorthlight) - Blender 插件，加载 Northlight 游戏 (Control/Alan Wake 2/Quantum Break) 的 binmsh/binfbx。

### Pragma Engine

- [io_pragma_engine](https://github.com/REDxEYE/io_pragma_engine) - Blender 导入/导出 Pragma 模型插件。

### Build Engine

- [BUILD Map Importer](https://github.com/jensnt/io_import_build_map) - Blender 导入 BUILD 地图 (Blood、Duke3D 等)，可自动从 `.ART`/`.GRP`/`.RFF` 抽取贴图。
  - 选项：分割 sector/墙/天空，保留 sprite 偏移，复用材质，明暗写入顶点色，原始数据存自定义属性。
- [Build palette editing tools (Duke Nukem 3D)](https://www.moddb.com/mods/black-shadow/downloads/build-palette-editing-tools) - BUILD 引擎（含 Duke3D）调色板编辑工具（进行中）。

### 3DSTATE

- [3DS MAX 5 and 3DS MAX 6 converter](https://www.moddb.com/engines/3dstate/downloads/3ds-max-5-and-3ds-max-6-converter) - 将 3DS Max 场景转 3DSTATE WLD，保留灯光/阴影/特效；含烘焙贴图脚本和二进制转换。

### AtiSushi Engine

- [AtiSushi](https://github.com/REDxEYE/AtiSushi) - UniLoader 插件，导入 AtiSushi 引擎文件。

### Genie Engine

- [geniedoc](https://github.com/aap/geniedoc) - 《帝国时代 II》.dat（Genie 引擎）格式文档。

### RPG Maker

- [rgssad](https://github.com/luxrck/rgssad) - 提取 RPG Maker 的 rgssad/rgss2a/rgss3a。
- [rpga](https://github.com/elizagamedev/rpga) - RPG 封包提取/创建工具；支持 RPG Maker XP+ 及 Wolf RPG（后者创建暂未完成）。

### Ren'Py

*广泛用于独立与商业视觉小说的引擎。*

- [unrpa](https://github.com/Lattyware/unrpa) - 解包 Ren'Py 使用的 RPA 封包。

### Rawthrills G7 Engine

- [G7Reader](https://github.com/Surasia/G7Reader) - 读取 Rawthrills G7 封包的小工具。

### OpenSpace

- [openspace-ps2-extractor](https://github.com/byvar/openspace-ps2-extractor) - OpenSpace PS2 封包提取器。
- [BinarySerializer.OpenSpace](https://github.com/BinarySerializer/BinarySerializer.OpenSpace) - BinarySerializer 扩展，用于序列化 OpenSpace 格式。

## 🔧 中间件与 SDK

*跨多平台/多作品使用的开发中间件、库与 SDK 格式。*

### Fast3d/F3dex (N64)

*SGI 为 N64 定义 3D 图形的微代码格式，见 [Super Mario 64](#super-mario-64)、[Paper Mario 64](#paper-mario-64)、[Banjo-Kazooie](#rare) 等。*

- [n64-fast3d-engine](https://github.com/Emill/n64-fast3d-engine) - N64 Fast3D 引擎实现。
- [noclip.website (Banjo)](https://github.com/magcius/noclip.website/blob/main/src/BanjoKazooie/f3dex.ts) - Banjo-Kazooie 查看器的 F3DEX 实现。
- [MeltyTool (F3dzex2)](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Libraries/F3dzex2) - F3DZEX2 支持。
- [F3DEX2Decoder](https://github.com/Mr-Wiseguy/F3DEX2Decoder) - F3DEX2 显示列表解码器。
- [F3D2F3DEX](https://github.com/Trenavix/F3D2F3DEX) - F3D 变体转换器。
- [Hack64 Fast3D Commands](https://hack64.net/wiki/doku.php?id=super_mario_64:fast3d_display_list_commands) - Fast3D 显示列表命令文档。
- [CloudModding F3DZEX2](https://wiki.cloudmodding.com/oot/F3DZEX2) - F3DZEX2 规格文档。

### Havok

*跨平台数百游戏使用的物理/动画中间件。*

- [Havok IO (Blender)](https://github.com/NewSkyLine-dev/havokmax-blender) - Blender 的 Havok 工具（替代旧 HavokMax 3ds Max 插件），导入 `.hkx/.hkt/.hka/.igz/.pak`（XML/二进制）。
  - 能力：由动画数据构建骨架与关键帧，几何块生成静态网格，解包 PAK/IGZ。
- [HavokNoesis](https://github.com/PredatorCZ/HavokNoesis) - Noesis 的 Havok 插件。
- [MapEditor](https://github.com/BF3RM/MapEditor) - Venice Unleashed（战地 3）实时地图编辑 Mod。
- [HavokPreviewToolsBatch2018](https://github.com/asasasasasbc/HavokPreviewToolsBatch2018) - Havok Preview Tool 2018 的批转换脚本，自动转 HKX/HKT 格式。
- [hkxlib](https://github.com/aerisarn/hkxlib) - 用 JAXB 解析/编辑 Havok TAGXML 文件。
- [hkxEdit](https://github.com/aerisarn/hkxEdit) - 基于 hkxlib 的 Havok 2010.2 可视化编辑器（Java）。
- [TagTools](https://github.com/blueskythlikesclouds/TagTools) - 编辑 Havok 2015/2016 二进制 tag 文件的工具，含 TagTools 转换器与 CollisionConverter。
- [FF16-Model-Importer](https://github.com/Nenkai/FF16-Model-Importer) - 《最终幻想 16》.mdl 进/出为 .gltf/.dae。
- [SSE-Fallout-4-Animation-Converter](https://github.com/Backporter/SSE-Fallout-4-Animation-Converter) - 将动画转 PS4 格式，供《上古卷轴 5：特别版》与《辐射 4》使用。

### JSYSTEM (GameCube/Wii)

*任天堂 GC/Wii 时代自研中间件，见 [Pikmin](#pikmin)、[Luigi's Mansion](#luigis-mansion)、[Super Mario Sunshine](#super-mario-other)、[Super Mario Galaxy](#super-mario-other)、[Wind Waker](#zelda)、[Twilight Princess](#zelda)、[Mario Kart: Double Dash](#mario-kart-double-dash) 等。*

- [gclib](https://github.com/LagoLunatic/gclib) - Python 实现的多种 GameCube 文件格式，用于 ROM hacking。
- [Amnoid GC Resources](http://amnoid.de/gc/) - GameCube 文件格式文档与资源。
- [JStudio (LordNed)](https://github.com/LordNed/JStudio) - WW J* 工具类。
- [J3D-Model-Viewer](https://github.com/LordNed/J3D-Model-Viewer) - J3D 模型查看器。
- [Hack.io](https://github.com/SuperHackio/Hack.io) - J3D 时代格式库。
- [noclip.website (JSYSTEM)](https://github.com/magcius/noclip.website/tree/main/src/Common/JSYSTEM) - 浏览器 JSYSTEM 查看器。
- [MeltyTool (JSystem)](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Libraries/JSystem) - JSystem 格式查看/导出。
- [SuperBMD](https://github.com/Sage-of-Mirrors/SuperBMD) - GC/Wii BMD/BDL 模型转换。
- [p2setoolkit](https://github.com/NerduMiner/p2setoolkit) - 《皮克敏 2》BMS 序列音乐拆/重组工具。
- [Rain336/JSystem](https://github.com/Rain336/JSystem) - Rust 解析 Wii/GC 格式库。
  - 格式：BCSV、RARC、U8。
- [Luma's Workshop (BMD)](https://lumasworkshop.com/wiki/BMD/BDL_(File_Format)) - BMD/BDL 文档。
- [Wiki.CloudModding (JSYSTEM)](https://wiki.cloudmodding.com/zgcn/JSYSTEM) - JSYSTEM 文档。
- [blojob](https://github.com/arookas/blojob) - J2DGraph BLO 工具。
- [pyblo2-gui](https://github.com/RenolY2/pyblo2-gui) - BLO GUI 工具。
- [j3dview](https://github.com/blank63/j3dview) - J3DGraph 查看器。
- [blemd](https://github.com/Sage-of-Mirrors/blemd) - J3D 模型 Blender 插件。
- [J3DUltra](https://github.com/Sage-of-Mirrors/J3DUltra) - 高级 J3D 模型工具。
- [Jekyll](https://github.com/Sage-of-Mirrors/Jekyll) - J3D 动画工具。
- [RiiStudio](https://github.com/snailspeed3/RiiStudio) - 现代 J3D 模型编辑器。
- [Tockdom BMD/BDL](https://wiki.tockdom.com/wiki/BMD_and_BDL_(File_Format)) - BMD/BDL 文档。
- [ibnktool](https://github.com/XAYRGA/ibnktool) - JAudio 音色库工具。
- [pyjmap](https://github.com/SunakazeKun/pyjmap) - JMap 格式库。
- [jpc_conv](https://github.com/PikHacker/jpc_conv) - JParticle 转换器。
- [pikmin2-stb](https://github.com/RenolY2/pikmin2-stb) - JStudio 工具。
- [Yaz0Decoder](https://github.com/Cuyler36/Yaz0Decoder) - Yaz0 解压。
- [rarc-rs](https://github.com/gcnhax/rarc-rs) - RARC 归档 Rust 库。
- [WArchive-Tools](https://github.com/LordNed/WArchive-Tools) - RARC 工具。
- [RARClib.py](https://github.com/RenolY2/RARClib.py) - RARC Python 库。
- [yaz0-decode-encode](https://github.com/RenolY2/yaz0-decode-encode) - Yaz0 压缩/解压工具。
- [BTITool](https://github.com/Sage-of-Mirrors/BTITool) - BTI 贴图工具。
- [GCFontTool](https://github.com/Sage-of-Mirrors/GCFontTool) - GC 字体工具。
- [libbti](https://github.com/Sage-of-Mirrors/libbti) - BTI 贴图库。
- [RarcPack](https://github.com/Sage-of-Mirrors/RarcPack) - RARC 打包器。
- [pyjkernel](https://github.com/SunakazeKun/pyjkernel) - JKernel 格式 Python 库。
- [WiiExplorer](https://github.com/SuperHackio/WiiExplorer) - Wii 文件系统浏览器。
- [ARCTool](https://github.com/tpwrules/ARCTool) - Python 脚本，解包 RARC/Yaz0/U8。
- [atirut.bdl](https://github.com/atirut-w/atirut.bdl) - Godot 引擎的 JSYSTEM BMD/BDL 导入器。
- [wsystool](https://github.com/XAYRGA/wsystool) - WAVESYSTEM modification toolkit for JSYSTEM games.
- [jampacked](https://github.com/XAYRGA/jampacked) - BAA unpacker for JSYSTEM games.

### MikuMikuDance

*免费动画制作软件及其模型/动作格式（.pmx、.pmd、.vmd）。*

- [MikuMikuLibrary](https://github.com/blueskythlikesclouds/MikuMikuLibrary) - 处理 MMD 格式的库。
- [MMD Tools](https://github.com/MMD-Blender/blender_mmd_tools) - Blender 导入/导出 MMD 资产插件，支持物理、骨骼约束、动作/姿势。
- [MMD Tools Append](https://github.com/MMD-Blender/blender_mmd_tools_append) - MMD Tools 的补充扩展，提供材质/场景控制、灯光预设、Rigify 辅助。

### RenderWare

*Criterion 开发的跨平台 3D 引擎/中间件，驱动 GTA 三部曲、Burnout 等。*

- [librw](https://github.com/aap/librw) - RenderWare 图形引擎再实现。
- [DragonFF](https://github.com/Parik27/DragonFF) - Blender 插件，处理 RenderWare `.dff` 模型、`.txd` 贴图、`.col` 碰撞、`.ipl` 地图。
- [Blender-3D-RW-Anm-plugin](https://github.com/Psycrow101/Blender-3D-RW-Anm-plugin) - Blender 导入/导出 RenderWare 动画 (.anm)。
- [rwio](https://github.com/aap/rwio) - 3ds Max 的 RenderWare 导入/导出插件。
- [rwd3d9](https://github.com/aap/rwd3d9) - GTA III/VC 的 RenderWare D3D9 扩展。
- [RenderWareFile](https://github.com/igorseabra4/RenderWareFile) - RenderWare 二进制文件库。
- [RenderWareNET](https://github.com/Venomalia/RenderWareNET) - 操作 RenderWare 3 格式的库。
- [RWIDE2YTYP](https://github.com/Hancapo/RWIDE2YTYP) - 将 RenderWare .IDE 转为 Five .YTYP / NY .IDE。

### CRI

*CRI 中间件格式（CPK 封包、ADX 音频等），广泛用于多平台日系游戏。*

- [CriPakTools](https://github.com/esperknight/CriPakTools) - CPK 提取/回打工具。
- [CriPakTools (GUI)](https://github.com/wmltogether/CriPakTools) - CPK GUI 版，支持 Shift-JIS、2GB+ PS3 CPK、批处理、压缩、更好的头处理。
- [Universal-CPK-Mod-Installer](https://github.com/PTKay/Universal-CPK-Mod-Installer) - 通用 CPK Mod 安装器。
- [CriFsV2Lib](https://github.com/Sewer56/CriFsV2Lib) - CRI FileSystem V2 封包库。
- [AfsLib](https://github.com/Sewer56/AfsLib) - 读写 CRIWare AFS 的简单快速库。
- [AfsBatch](https://github.com/tge-was-taken/AfsBatch) - 批量 AFS 打包器，将子目录各自打成同名 AFS。
- [PyCriCodecs](https://github.com/Youjose/PyCriCodecs) - CRI 编解码工具的 Python 前端。

### XNA

*微软 XNA 框架模型格式，见多款 Xbox 360/PC 游戏。*

- [blender_xna](https://github.com/REDxEYE/blender_xna) - Blender 导入 XNA 模型插件。

### Sappy (GBA Audio)

*GBA 声音引擎的 SDK 格式，用于 [宝可梦 Gen III](#gen-iii) 等大量 GBA 游戏。*

- [gba-mus-ripper](https://github.com/berg8793/gba-mus-ripper) - GBA 音乐提取。
- [SapPy](https://github.com/mayhaps-perchance/SapPy) - 基于 Python 的 GBA 声音工具。
- [agbplay](https://github.com/ipatix/agbplay) - GBA 音乐播放器/提取器。
- [sappy](https://github.com/maddievision/sappy) - GBA 声音工具。
- [Sappy (Touched)](https://github.com/Touched/Sappy) - 增强分支。
- [shinen-gax-python](https://github.com/beanieaxolotl/shinen-gax-python) - Shin'en GAX 声音引擎的 Python 工具，含转换/解包/波形导出/渲染，亦支持 NAX。
- [gsfopt](https://github.com/loveemu/gsfopt) - GSF 优化器，移除未用代码/数据，将 miniGSF/gsflib 合并为单 GSF，含自动定时标签。
- [saptapper](https://github.com/loveemu/saptapper) - 使用 Sappy 驱动的自动 GSF 提取器，自动从 GBA ROM 抽取音乐。
- [deadbeef_GSFdecoder](https://github.com/joshbarrass/deadbeef_GSFdecoder) - DeaDBeeF 的 GSF 解码插件（基于 viogsf/VBA-M）。

### RAD Game Tools

*Bink/Granny/Miles 等中间件提供商，跨平台大量游戏使用。*

- [Knit](https://github.com/neptuwunium/Knit) - 全托管 C# Granny 2 读库。
- [GR2Toolkit](https://github.com/REDxEYE/GR2Toolkit) - Granny 3D (GR2) 模型工具。

### Nintendo SDKs & Hardware

*任天堂主机/SDK 通用的格式与工具。*

- [Nintendo-File-Formats](https://github.com/kinnay/Nintendo-File-Formats) - Wii U / Switch 格式文档。
- [hactool](https://github.com/SciresM/hactool) - 查看/解密/解包 Switch 格式（NCA/XCI/PFS0/HFS0/RomFS/ExeFS/存档等）。
- [WiiUTools](https://github.com/NWPlayer123/WiiUTools) - Wii U Python 工具集，涵盖 IPK、RPX、SARC、贴图编辑 (TexHaxU)。
- [Syroot.NintenTools.Bfres](https://gitlab.com/Syroot/NintenTools) - 读写 Wii U BFRES 模型库。
- [Nitro Files](https://wiki.vg-resource.com/Nitro_Files) - NDS 文件格式文档。
- [narchive](https://github.com/nickworonekin/narchive) - 提取/创建 DS 使用的 NARC 封包。
- [RomFS-Builder](https://github.com/SciresM/RomFS-Builder) - 将文件夹生成 3DS RomFS 二进制，配合 makerom。
- [XCI-Explorer](https://github.com/StudentBlake/XCI-Explorer) - 查看 Switch XCI/NSP，支持元数据、分区、NCA hash、提取/改证书。
- [gc-c-kit](https://github.com/RenolY2/gc-c-kit) - 使用 devkitppc 编译 C 并注入 GC DOL，可适配不同 GC 游戏。
- [WiiTools](https://github.com/Megazig/WiiTools) - Wii 逆向与函数识别工具。
- [N64Recomp](https://github.com/N64Recomp/N64Recomp) - N64 静态再编译器，将 ROM 转为可跨平台编译的 C。
- [wfslib](https://github.com/koolkdev/wfslib) - WFS（WiiU 文件系统）库与工具。
- [ctpktool](https://github.com/dnasdw/ctpktool) - 导入/导出 3DS 使用的 CTPK 贴图包。
- [AudiobankToC](https://github.com/sauraen/AudiobankToC) - N64 Audiobank 与 C 代码互转脚本，保持二进制匹配。
- [libansnd](https://github.com/Oaisus/libansnd) - Wii/GC 自制音频库，支持 ADPCM 解码与重采样，最多 48 声道硬件 ADPCM。
- [LegacySwitchLibraries](https://github.com/KillzXGaming/LegacySwitchLibraries) - Switch Toolbox 等的 Switch 格式库。
- [exefs_patches](https://github.com/misson20000/exefs_patches) - Switch ExeFS 补丁工具。
- [otptool](https://github.com/SciresM/otptool) - Switch OTP 文件工具。
- [switch-reversing](https://github.com/SciresM/switch-reversing) - Reverse engineering resources for Nintendo Switch.
- [sarc](https://github.com/jam1garner/sarc) - Rust library for reading and writing Nintendo SARC and SZS (yaz0 compressed SARC) archive formats.
- [sarc-extract](https://github.com/RenolY2/sarc-extract) - Extractor for SARC archive format.
- [GARC-Unpack](https://github.com/vgmoose/GARC-Unpack) - Unpacker for Nintendo GARC archive format.
- [lzarc](https://github.com/jam1garner/lzarc) - Rust library and CLI for working with LZARC compressed archives used in Paper Mario Color Splash.
- [Lzarc-Tool](https://github.com/Fuzzy2319/Lzarc-Tool) - Tool for LZARC compressed archive format.
- [msbt2sheets](https://github.com/CaXaPeK/msbt2sheets) - Converter for MSBT files to spreadsheet format.
- [MSBTEditor](https://github.com/efimandreev0/MSBTEditor) - MSBT text extractor/replacer for .msbt and .umsbt LE-files.
- [umsbt_cmd_extractor](https://github.com/efimandreev0/umsbt_cmd_extractor) - Command extractor for UMSBT files.
- [BFRES-Viewer](https://github.com/KillzXGaming/BFRES-Viewer) - Viewer for Nintendo BFRES model format files.
- [BFRES-Tool](https://github.com/aboood40091/BFRES-Tool) - Tool for working with Nintendo BFRES files.
- [BFRES-Extractor](https://github.com/LordNed/BFRES-Extractor) - Extractor for Nintendo BFRES format files.
- [TinkeDSi](https://github.com/R-YaTian/TinkeDSi) - Viewer and extractor for Nintendo DS/DSi file formats.
- [ctpktool](https://github.com/dnasdw/ctpktool) - Tool for working with CTPK texture package files.
- [gc-gcm](https://github.com/jam1garner/gc-gcm) - Tool for GameCube GCM file format.
- [LibGCM](https://github.com/Sage-of-Mirrors/LibGCM) - Library for GameCube memory card formats.
- [dolreader](https://github.com/RenolY2/dolreader) - Reader for GameCube/Wii DOL executable format.
- [gci-bt](https://github.com/jam1garner/gci-bt) - GameCube GCI file tool with Bluetooth support.
- [Chihuahua](https://github.com/Sage-of-Mirrors/Chihuahua) - Tool for GameCube/Wii file formats.
- [TSCBReader](https://github.com/Sage-of-Mirrors/TSCBReader) - Reader for TSCB format files.
- [KMP-Expander](https://github.com/Ermelber/KMP-Expander) - Expander for KMP format files.
- [pymsc](https://github.com/jam1garner/pymsc) - Python library for MSC format files.
- [cgrr-gameboy](https://github.com/sopoforic/cgrr-gameboy) - Tools for Game Boy file formats.
- [cgrr-gamecube](https://github.com/sopoforic/cgrr-gamecube) - Tools for GameCube file formats.
- [HexManiacAdvance](https://github.com/haven1433/HexManiacAdvance) - Hex editor for Game Boy Advance ROMs with scripting support.
- [UnkrawerterGBA](https://github.com/MCJack123/UnkrawerterGBA) - Game Boy Advance ROM extractor and converter.
- [Hatenatools](https://github.com/pbsds/Hatenatools) - Python tools for Flipnote Studio (Nintendo DSi) file formats. Supports reading and writing .ppm (Flipnote files), .tmb (thumbnail files), .ugo (user data), and .ntft (image files). Can extract metadata, frames, and audio from Flipnote files.
- [SuperFamiconv](https://github.com/Optiroc/SuperFamiconv) - Command-line tool to convert graphics to Super Nintendo format.
- [M1TE2](https://github.com/nesdoug/M1TE2) - SNES Mode 1 Tile Editor for generating, editing, and arranging SNES tiles and tilemaps (2bpp/4bpp) with palette support. Designed for Mode 1 but works with any mode needing 2bpp or 4bpp graphics.
- [3dstool](https://github.com/dnasdw/3dstool) - All-in-one tool for extracting and creating 3DS file formats.
  - Formats: CIA, CCI, NCCH, NCSD.
- [apicula](https://github.com/scurest/apicula) - Converter for Nintendo DS .nsbmd 3D model format.
- [apicula/wiki/FILETYPES](https://github.com/scurest/apicula/wiki/FILETYPES) - Documentation for Nintendo DS file types.
- [nitro-fs](https://github.com/DanielPXL/nitro-fs) - Nintendo DS filesystem tools.
- [nitro-g3d-tools](https://github.com/Ermelber/nitro-g3d-tools) - Tools for Nintendo DS 3D graphics.
- [nitroefx](https://github.com/Fexty12573/nitroefx) - Nintendo DS effect tools.
- [NitroEffectMaker](https://github.com/HaroohiePals/NitroEffectMaker) - Effect editor for Nintendo DS.
- [narc](https://github.com/lhearachel/narc) - NARC archive tool for Nintendo DS.
- [NitroSDK](https://github.com/ntrtwl/NitroSDK) - Official Nintendo DS SDK.
- [NitroSystem](https://github.com/ntrtwl/NitroSystem) - Nintendo DS system library.
- [NTRGhidra](https://github.com/pedro-javierf/NTRGhidra) - Ghidra plugin for Nintendo DS.
- [NitroSharp](https://github.com/PlatinumMaster/NitroSharp) - Nintendo DS file format library.
- [nitrog3d](https://github.com/red031000/nitrog3d) - Nintendo DS 3D tools.
- [nitrogfx](https://github.com/red031000/nitrogfx) - Nintendo DS graphics tools.
- [Ekona](https://github.com/SceneGate/Ekona) - Nintendo DS file format library.
- [Nds4j](https://github.com/turtleisaac/Nds4j) - Java library for Nintendo DS formats.
- [Cafe-Shader-Studio](https://github.com/KillzXGaming/Cafe-Shader-Studio) - Shader editor and viewer for Wii U games.
- [REGames Editor](https://www.reddit.com/r/REGames/comments/12o004k/a_friend_and_i_made_a_full_editor_for_a_nintendo/) - Full-featured editor for Nintendo DS games.
- [nod](https://github.com/encounter/nod) - Rust library for reading and writing Nintendo Optical Disc images (GameCube and Wii). Includes nodtool CLI for extraction, conversion, and verification.
  - Formats: ISO (GCM), WIA/RVZ, WBFS, CISO, NFS (Wii U VC), GCZ, TGC.

## Game & Studio Tools

### Activision / Infinity Ward / Treyarch

#### Call of Duty

- [Tyrant](https://github.com/Scobalula/Tyrant) - 针对 CoD 的 RE Engine 资产提取器。
- [ShibaInu](https://github.com/Scobalula/ShibaInu) - CoD Mod Tools 用的武器文件转换器。
- [iwd-tool](https://github.com/ZoneTool/iwd-tool) - 生成 CoD IWD 的命令行工具。
- [lui-tool](https://github.com/xensik/lui-tool) - 组装/反组装 IW 引擎 UI 脚本，支持 CoD: Ghosts (IW6)。
- [blender-cod](https://github.com/CoDEmanX/blender-cod) - Blender CoD Mod 插件。
- [WraithXArchon](https://github.com/dtzxporter/WraithXArchon/) - 著名的 CoD 资产提取工具。
- [KisakCOD](https://github.com/SwagSoftware/KisakCOD/) - 可完整构建的 CoD4 多人开源重实现，面向 Mod 开发。
- [Cordycep](https://github.com/Scobalula/Cordycep) - 利用修改 exe 载入 fastfile 的 CoD 工具。
- [zonebuilder](https://github.com/RagdollPhysics/zonebuilder) - IW4 (MW2) fastfile 生成器。
- [IWI DDS Fast Converter V1.40 (Call of Duty 2)](https://www.moddb.com/games/call-of-duty-2/downloads/iwi-dds-fast-converter-v140)
- [x to xmodel_export converter 1.6 cod5 Version (Call of Duty: World at War)](https://www.moddb.com/games/call-of-duty-world-at-war/downloads/x-to-xmodel-exporter-converter-16-cod5-version) - 将 *.x / *.obj 转为 WaW 的 xmodel_export，之后可用 Asset Manager 转 xmodel；把 xconv.exe 放到 CoD5 目录运行 (v1.6)。
- [iw4-open-formats](https://github.com/iw4x/iw4-open-formats/blob/main/src/iw4-of/assets/assets.cpp) - MW2 资产转换系统。
- [BSP Decompiler (Call of Duty)](https://www.moddb.com/games/call-of-duty/downloads/bsp-decompiler) - CoD BSP 反编译器与源码。
- [gsc-asm](https://github.com/ZoneTool/gsc-asm) - IW5 (MW3) 的 GSC 汇编/反汇编器。
- [Call of Duty 1 Milkshape plugins](https://www.moddb.com/games/call-of-duty/downloads/call-of-duty-1-milkshape-plugins) - CoD1 Milkshape 插件合集。
- [Call of Duty 1 Mod Tools No Installer Version](https://www.moddb.com/games/call-of-duty/downloads/call-of-duty-1-mod-tools-no-installer-version) - CoD1 Mod 工具的免安装版，解决官方安装器注册表缺失问题。
- [Call of Duty 2 Mod Tools](https://www.moddb.com/games/call-of-duty-2/downloads/call-of-duty-2-mod-tools) - CoD2 官方 Mod 工具。
- [Call of Duty 2 Mod Tools No Installer](https://www.moddb.com/games/call-of-duty-2/downloads/call-of-duty-2-mod-tools-no-installer) - CoD2 Mod 工具免安装版。
- [CoD4 Mod Tools 1.1 (mirror)](https://github.com/promod/CoD4-Mod-Tools) - CoD4 官方 Mod Tools 与 1.1 更新镜像。
- [Iwi Converter (Call of Duty 2)](https://www.moddb.com/games/call-of-duty-2/downloads/iwi-converter) - 支持多选的 CoD2 IWI 转换器。
- [KV Map Converter v2 Beta2 (Call of Duty 4: Modern Warfare)](https://www.moddb.com/games/call-of-duty-4-modern-warfare/downloads/kv-map-converter-v2-beta2) - 将 Source 地图转 CoD4 的工具 (v2 Beta2)。

#### Tony Hawk's Pro Skater

- [WAD Tool v1.0 (Tony Hawk's Pro Skater)](https://www.moddb.com/games/tony-hawks-pro-skater/downloads/wad-tool-v10) - 早期 THPS 引擎 WAD 打/解包小工具。
- [C2M](https://github.com/sheilan102/C2M) - 从 CoD 导出地图的工具。
- [TOXEC (The Obj to Xmodel Export Converter)](https://www.moddb.com/games/call-of-duty-world-at-war/downloads/toxec-the-obj-to-xmodel-export-converter) - 将 OBJ 转 Xmodel（用于 CoD4/WaW 地图制作）。
- [DDS/IWI Converter 1.5 (Call of Duty 2)](https://www.moddb.com/games/call-of-duty-2/downloads/dds-iwi-converter-1-5)

#### Ghostbusters

- [Gibbed.Ghostbusters](https://github.com/gibbed/Gibbed.Ghostbusters) - 《捉鬼敢死队：游戏版》(2009) 的工具与代码。

#### A Series of Unfortunate Events

- [resPack](https://github.com/XAYRGA/resPack) - XBox《雷蒙·斯尼奇的不幸历险》封包提取器。

#### Spider-Man (Neversoft)

- [spidey-decomp](https://github.com/krystalgamer/spidey-decomp) - Neversoft《蜘蛛侠》PC 版反编译，用于研究格式与内部。

### Angel Matrix (Neon White)

- [noclip.website (Neon White)](https://github.com/magcius/noclip.website/tree/main/src/NeonWhite) - 浏览器版《Neon White》查看器。

### Angel Studios / Rockstar San Diego

- [GTAVHandlingEditor](https://github.com/ikt32/GTAVHandlingEditor) - GTA V 载具操控实时编辑器。

### Anthony Bongers

- [GhostsAndGraves (decomp)](https://github.com/AnthonyBongers/GhostsAndGraves) - NES《Ghosts And Graves》匹配反编译 (100%)。
- [gta5-nativedb-data](https://github.com/alloc8or/gta5-nativedb-data) - GTA V 原生函数数据库。
- [AngelStudiosBlenderAddon](https://github.com/Dummiesman/AngelStudiosBlenderAddon) - Blender 插件，处理 1999-2006 Angel Studios/RS San Diego 格式，支持 Midnight Club 2、Midtown Madness 1 等。
  - 格式：BMS、DLP、MOD/XMOD、BND、SKEL、GEO。
- [MidnightClub2 (Noesis)](https://himeworks.com/noesis-plugins/) - Midnight Club 2 模型格式的 Noesis 插件。
- [Sollumz](https://github.com/Hancapo/Sollumz) - Blender 导入 GTA V CodeWalker 转换 XML 的插件，RAGE 引擎 Mod 套件。[文档](https://docs.sollumz.org)。
- [pyrpfiv](https://github.com/gmroder/pyrpfiv) - Python 库，解析/操作 GTA IV RPF 归档，支持提取、修改、加密 TOC。
- [noclip.website (Grand Theft Auto III)](https://github.com/magcius/noclip.website/tree/main/src/GrandTheftAuto3) - 浏览器版 GTA III 查看器。
- [openrw](https://github.com/rwengine/openrw) - GTA III 可执行文件的开源重实现。
- [noclip.website (Grand Theft Auto: Vice City)](https://github.com/magcius/noclip.website/tree/main/src/GrandTheftAuto3) - 浏览器版 GTA:VC 查看器。
- [noclip.website (Grand Theft Auto: San Andreas)](https://github.com/magcius/noclip.website/tree/main/src/GrandTheftAuto3) - 浏览器版 GTA:SA 查看器。
- [MidtownExtractor](https://github.com/0x1F9F1/MidtownExtractor) - 《疯狂城市 1/2》及 Midnight Club 2 文件提取器。
- [RGLExtractor](https://github.com/Disquse/RGLExtractor) - 解包 Rockstar Launcher RAGE packfile（目前 Launcher.rpf，RPF7 AES 不同）。
- [MeltyTool](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Libraries/AngelStudios) - 大批量查看/提取多款 N64/GCN/3DS/PC 游戏资产的多功能工具。
- [CLEO library v2.0.0.5 (GTA III)](https://www.moddb.com/games/grand-theft-auto-3/downloads/cleo-library-by-seemann-for-gta-iii) - 著名可扩展插件 CLEO（GTA III 版）。
- [CLEO library v2.0.0.5 (GTA Vice City)](https://www.moddb.com/games/grand-theft-auto-vice-city/downloads/cleo-library-v2005-by-seemann-for-gta-vc) - CLEO GTA:VC 版。
- [CLEO library v4.3.22 (GTA San Andreas)](https://www.moddb.com/games/grand-theft-auto-san-andreas/downloads/cleo-library-v4322-by-seemann-for-gta-sa) - CLEO GTA:SA 版。
- [Epic GTA2 Script Decompiler Source Code (GTA2)](https://www.moddb.com/games/grand-theft-auto-2/downloads/epic-gta2-script-decompiler-source-code) - Epic GTA2 脚本反编译器源码。
- [GMP/STY file format descriptions (GTA2)](https://www.moddb.com/games/grand-theft-auto-2/downloads/gmpsty-file-format-descriptions) - GTA2 GMP/STY 官方格式文档。
- [GTA Font compiler (GTA1)](https://www.moddb.com/games/grand-theft-auto/downloads/gta-font-compiler) - 查看/创建/编辑 GTA1 字体文件的工具。
- [GTA V Suspend Resume tool (GTA V)](https://www.moddb.com/games/grand-theft-auto-v/downloads/gta-v-suspend-resume-tool)
- [IMG Tool v1.3 (GTA III)](https://www.moddb.com/games/grand-theft-auto-3/downloads/iii-img-tool-v13)
- [IMG Tool 2.0 (GTA: SA)](https://www.moddb.com/games/grand-theft-auto-san-andreas/downloads/img-tool-20) - 操作 GTA3.img 归档（GTA3/VC/SA）的工具，安装车辆/皮肤/武器等必备 (v2.0)。

### Ape, Inc

- [earthbound-script-dumper](https://github.com/CataLatas/earthbound-script-dumper) - 《EarthBound》文本提取。
- [ebtexted](https://github.com/PKHackers/ebtexted) - Tomato 的《EarthBound》文本编辑器。
- [EBME](https://github.com/Supremekirb/EBME) - 《EarthBound》主世界区域 GUI 编辑器。
- [ebbinex](https://github.com/Herringway/ebbinex) - 提取 EarthBound ROM 数据的小工具。

### Arrowhead Game Studios (Helldivers 2)

- [helldivers2-rs](https://github.com/nblockbuster/helldivers2-rs) - WIP 的《地狱潜者 2》文件提取。

### 11 bit studios (Frostpunk)

- [Frostract - Frostpunk idx and dat unpacker](https://www.moddb.com/games/frostpunk/downloads/frostract-frostpunk-idx-and-dat-unpacker) - 《冰汽时代》idx/dat 解包。

### Avalanche Studios (Generation Zero)

- [ApexPredator](https://github.com/REDxEYE/ApexPredator) - Apex 引擎资产读取库/工具，现支持《除零》；C++ 编写。

### Remedy Entertainment

#### Max Payne

- [Game Levels Importing plugin for Maya (Max Payne)](https://www.moddb.com/games/max-payne/downloads/game-levels-importing-plugin-for-maya)
- [MAX-FX Tools (Max Payne)](https://www.moddb.com/games/max-payne/downloads/max-fx-tools) - 《马克思·佩恩 1》官方 Mod 包（Steam 版不含，单独提供）。
- [Max Payne 1-2 Packer](https://www.moddb.com/games/max-payne-2/downloads/max-payne-1-2-packer) - RasMaker 打包的批处理封装。
- [MaxPayne Toolset](https://www.moddb.com/games/max-payne/downloads/maxpayne-toolset) - MP1/2 Mod/RAS 打包与解包，支持从 LDB 抽取贴图。
- [Mod Tools (Max Payne 2)](https://www.moddb.com/games/max-payne-2/downloads/mod-tools) - 《马克思·佩恩 2》官方关卡/内容制作工具集。

### Argonaut Games

- [croc (decomp)](https://github.com/xeeynamo/croc) - 《小鳄鱼冒险》匹配反编译。
- [PS1-BRender-Reverse](https://github.com/OverSurge/PS1-Argonaut-Reverse) - PS1 BRender 引擎（如哈利波特、Croc 2）逆向工具。
- [Stratigise](https://github.com/Argonaut-PS1-Reverse/Stratigise) - WIP tool for disassembling and (re)assembling ASL binaries for Croc 1.
- [CrocUtils](https://github.com/Rexhunter99/CrocUtils) - Utilities for Croc game file formats.

### Arkane Studios

- [Arx Fatalis .PAK unpacker](https://www.moddb.com/games/arx-fatalis/downloads/arx-fatalis-pak-unpacker-v13) - 《Arx Fatalis》PAK 解包器，含源码 (v1.3)。
- [disrev](https://github.com/chipolux/disrev) - Python 工具，提取/修改《耻辱 2》资产。
- [dishonored2_scripts](https://github.com/usernametoolo/dishonored2_scripts/blob/master/tools/scripts/unpack_resources.py) - 解包 .pak 的资源脚本。
- [Obscura](https://github.com/Mikompilation/Obscura) - 《耻辱》系列 Mod 工具包。
- [Field Editor 0.5.1 (Dishonored)](https://www.moddb.com/games/dishonored/downloads/field-editor-051-tautologist-tool) - 《耻辱》字段编辑器，改进菜单/快捷键/自动补全/分组/过滤，保存设置，浏览 XML (v0.5.1)。

### Atlus

- [Amicitia](https://github.com/tge-was-taken/Amicitia) - 处理 P3/4/5 文件格式的工具。
- [yafe](https://github.com/tge-was-taken/yafe) - P5 场景编辑，导入 FBN/HBN 至 3ds Max 进行可视化编辑。
- [P5X_vFileContentExtract](https://github.com/DeathChaos25/P5X_vFileContentExtract) - P5X vFile 归档内容提取。
- [DDS3-Model-Studio](https://github.com/tge-was-taken/DDS3-Model-Studio) - WIP，DDS3 引擎（女神异闻录 Nocturne、DDS 1/2、莱多 1/2）模型编辑。
- [AtlusFileSystemLibrary](https://github.com/tge-was-taken/AtlusFileSystemLibrary) - Atlus 游戏文件系统工具库。
- [Atlus-Script-Tools](https://github.com/tge-was-taken/Atlus-Script-Tools) - Atlus 脚本工具集，支持 .bf 流程脚本、.bmd/.bm2 文本，覆盖女神异闻录、真女神转生、凯瑟琳、创伤中心等。
- [AtlusPM1MessageScriptEditor](https://github.com/tge-was-taken/AtlusPM1MessageScriptEditor) - P1 消息脚本编辑器。
- [GFD-Studio](https://github.com/tge-was-taken/GFD-Studio) - 查看/编辑/转换 GMD/GFS（P3D/P4D/P5D、P5）模型的编辑器。
- [EvtTool](https://github.com/tge-was-taken/EvtTool) - P5/P5R EVT 编辑，EVT/ECS/LSD ↔ JSON。
- [SMT1L1ON](https://github.com/tge-was-taken/SMT1L1ON) - 《真女神转生 1》翻译工具。
- [P5RFieldTexUtility](https://github.com/ShrineFox/P5RFieldTexUtility) - P5R 场景贴图批量提取/回打，支持 .BIN+DDS。
- [EPLGen](https://github.com/ShrineFox/EPLGen) - P5R EPL 粒子 GUI，生成带动画精灵的叶节点，支持 DDS 贴图与 GMD 集成。
- [p5s-txteditor](https://github.com/samudebug/p5s-txteditor) - 《女神异闻录 5 乱战》文本编辑。
- [smt1dasm](https://github.com/spannerisms/smt1dasm) - SFC《真女神转生》J1.0 反汇编。
- [p4u2modtools](https://github.com/zarroboogs/p4u2modtools) - P4U2/P4U 等 Mod 工具，含 bddata.bin 解包与自定义更新生成。
- [P5CharacterSwapper](https://github.com/ShrineFox/P5CharacterSwapper) - P5 按 ID 批量替换模型/动画，可重定向。
- [PersonaRandomizer](https://github.com/ShrineFox/PersonaRandomizer) - P3F/P4/P5 快速随机化工具，支持多种 TBL（PERSONA/UNIT/SKILL/ITEM/NAME/ENCOUNT 等）。
- [AemulusModManager](https://github.com/TekkaGB/AemulusModManager) - P4G/P3F/P5/P5S Mod 包管理器，自动合并冲突的 bin/bmd/pm1/bf/tbl。
- [p4g-saveconv](https://github.com/zarroboogs/p4g-saveconv) - P4G 存档转换（Vita ↔ PC，含 data00XX/system/sdslot）。
- [p5-rte](https://github.com/TheHiddenHour/p5-rte) - 越狱 PS3 的 P5 实时编辑（人物槽/属性/技能）。
- [GMDTool](https://github.com/lemoncove/GMDTool) - 命令行将 Persona .GMD 模型转 Collada .DAE，基于 GFDLibrary。

### Asobo Studio

- [fmtk](https://github.com/widberg/fmtk) - FUEL Modding Toolkit.
- [ImZouna](https://github.com/widberg/ImZouna) - ImHex patterns for Zouna data structures used in Asobo Studio games (FUEL, WALL-E, Ratatouille, Toy Story 3, A Plague Tale series, Microsoft Flight Simulator, and more).

### Black Element Software (Alpha Prime)

- [Alpha Prime RES Unpacker](https://www.moddb.com/mods/alpha-prime-dominus-prime/downloads/alpha-prime-res-unpacker-modding-tool) - Modding Tool for opening the .RES files for the "data00.res" and "data01.res" in Alpha Prime.

### Bandai Namco

- [kl2_lv_decomp (decomp)](https://github.com/entriphy/kl2_lv_decomp) - Matching decompilation of Klonoa 2: Lunatea's Veil (PS2).
- [Dragon-Ball-Legends (decomp)](https://github.com/GodkuHacking/Dragon-Ball-Legends) - Matching decompilation of Dragon Ball Legends (Android APK).
- [SoulCalibur2-game-unpacker](https://github.com/PS2Homebrew-arcade/SoulCalibur2-game-unpacker) - Unpacker for Soul Calibur 2 game files.
- [BinarySerializer.Klonoa](https://github.com/BinarySerializer/BinarySerializer.Klonoa) - Serializer for Klonoa games.
- [TalesOfFantasy (Noesis)](https://himeworks.com/noesis-plugins/) - Noesis plugins for Tales series.
- [ARC](https://github.com/Bigchillghost/ARC) - Animation Recipe Cracker for Bandai Namco games.
- [MBTL.BIN.Tool](https://github.com/Ekey/MBTL.BIN.Tool) - Tool for extracting BIN archives from MELTY BLOOD: TYPE LUMINA.
- [RRUnpacker](https://github.com/Nenkai/RRUnpacker) - Unpacker for Ridge Racer PSP/6/7/PS Vita and Go Vacation .DAT files. Supports extraction of all files including custom compressed ones.
- [BBFSUnpacker](https://github.com/Nenkai/BBFSUnpacker) - Extraction tool for Ridge Racer Drifttopia files.
- [ggst_collision_editor_rs](https://github.com/WistfulHopes/ggst_collision_editor_rs) - Collision editor for Guilty Gear Strive.
- [noclip.website (Klonoa)](https://github.com/magcius/noclip.website/tree/main/src/rres) - In-browser Klonoa viewer.
- [noclip.website (Katamari Damacy)](https://github.com/magcius/noclip.website/tree/main/src/KatamariDamacy) - In-browser Katamari Damacy viewer.

### Electronic Arts

- [EA-Graphics-Manager](https://github.com/bartlomiejduda/EA-Graphics-Manager) - Handles FSH, SSH, XSH, PSH, GSH, ASH, QFS and MSH files from EA games. Parse, preview, and export/import graphics as DDS/PNG/BMP.
  - Games: FIFA series (97, 2000, 06, 09, 14, Street, UEFA Euro 2004), Need For Speed series (1994, II, High Stakes, Hot Pursuit 2, Porsche Unleashed, Carbon, Undercover), Medal of Honor series (Frontline, Rising Sun, Vanguard, European Assault), Madden NFL (06, 08), NHL series (2001, 2002, 2005, 07), NBA Live 97, MVP Baseball/NCAA Baseball (2005, 2007), SSX series, Cricket (2005, 2007), Harry Potter (Chamber of Secrets, Quidditch World Cup), Def Jam: Fight For New York, Fight Night Round 3, GoldenEye, SimCity 4 Deluxe, Triple Play 2000, ReBoot, F.A. Premier League Football Manager 2000, EA Playground (Wii), and more across PS1, PS2, PSP, PC, Xbox, Wii, and Zeebo platforms.
- [EA-Font-Manager](https://github.com/bartlomiejduda/EA-Font-Manager) - Handles EA font files (FFN, PFN, XFN, MFN, SFN formats). Preview, decode flags, edit character tables, and convert font images.
  - Games: FIFA 97, Need for Speed series (2, High Stakes, Hot Pursuit, Undercover), NBA Live 06-07, SSX series, MVP Baseball 2005, Medal of Honor: European Assault,
  NHL series, Def Jam: Fight for NY, Harry Potter and the Chamber of Secrets, The Sims, and more.
- [EA-Loc-Manager](https://github.com/bartlomiejduda/EA-Loc-Manager) - Extract and import localization files (LOC format) from EA games. Supports UTF-8, UTF-16, and Latin-1 encodings.
  - Games: Harry Potter and the Chamber of Secrets (PS2), Medal of Honor: European Assault (Xbox), SSX On Tour, SSX Tricky (PS2), NHL 07 (PSP), and more.

#### SSX

- [ssx (decomp)](https://github.com/ssxdecomp/ssx) - Matching decompilation of SSX (2000).
- [ssx3 (decomp)](https://github.com/ssxdecomp/ssx3) - Matching decompilation of SSX 3 (2003).
- [ssxdvd (decomp)](https://github.com/ssxdecomp/ssxdvd) - Matching decompilation of SSX Tricky (2001).

### EA DICE

- [Frostbite-Scripts](https://github.com/NicknineTheEagle/Frostbite-Scripts) - Scripts and tools for Frostbite engine games.
- [libbndl](https://github.com/Bo98/libbndl) - Library for reading BUNDLE archives used in Burnout Paradise.

#### Battlefield Series

- [BF1942 3dsmax 8 plugin](https://www.moddb.com/games/battlefield-1942/downloads/bf1942-3dsmax-8-plugin) - Plugin for 3DS Max 8 to import/export Battlefield 1942 meshes and animations. Extracted from the Battlefield Mod Development Toolkit 1.0B by DICE.
- [BF2 Maya 4-6 Tools](https://www.moddb.com/games/battlefield-2/downloads/bf2-maya-4-6-tools) - Official Battlefield 2 tools for Maya 4-6 for exporting and importing game assets. Also included with the BF2 Editor but provided separately here.
- [BF42 3dsMax plugins 2.762](https://www.moddb.com/mods/battlefield-2-play-for-free-mod/downloads/bf42-3dsmax-plugins-2762) - 3DS Max plugins for Battlefield 2/1942 for Max 9 and higher (v2.762).
- [BGF Heightmap Converter](https://www.moddb.com/games/battlefield-2/downloads/bgf-heightmap-converter-utility) - Utility for viewing and resizing heightmap (.RAW) files. Primarily intended for converting maps from Battlefield 1942 or Battlefield Vietnam to Battlefield 2, but can also be used to change a BF2 map to a different size.
- [DDS Viewer Plugin (Battlefield Vietnam)](https://www.moddb.com/games/battlefield-vietnam/downloads/dds-viewer-plugin) - Plugin for previewing DDS files in folder preview window before conversion. Useful for mappers and modders.
- [NVIDIA DDS Utilities (Battlefield 2)](https://www.moddb.com/games/battlefield-2/downloads/nvidia-dds-utilities) - Collection of utilities for manipulating DDS image files: nvDXT (command-line binary), detach (extracts MIP levels), stitch (recombines MIP levels), and readDXT (reads compressed images).
- [NVIDIA Texture Atlas Tool (Battlefield 2)](https://www.moddb.com/games/battlefield-2/downloads/nvidia-texture-atlas-tool) - A collection of tools for creating texture atlases, which can help to increase batch sizes.
- [POE2 3DS Max 6-8 BF2 Tools (Battlefield 2)](https://www.moddb.com/games/battlefield-2/downloads/poe2-3ds-max-6-8-tools) - POE2's advanced rendition of the 3DS Max BF2 tools (for Max 6-8).
- [POE2 3DS Max 9 BF2 Tools (Battlefield 2)](https://www.moddb.com/games/battlefield-2/downloads/poe2-3ds-max-9-bf2-tools) - POE2's advanced rendition of the 3DS Max BF2 tools (for Max 9).
- [Windows Texture Viewer v089b (Battlefield 2)](https://www.moddb.com/games/battlefield-2/downloads/windows-texture-viewer-v089b) - Tool for viewing .dds texture files. Shows resolution, DDS format, mipmap count, and alpha channel used by HUD.
- [Texture Tool 0.2 (Battlefield 2)](https://www.moddb.com/games/battlefield-2/downloads/texture-tool-0-2) - Ecomap that automates the texturing of BF2 maps.
- [Clan Tool (Battlefield 2)](https://www.moddb.com/games/battlefield-2/downloads/clan-tool) - Advanced Tactical Center for Battlefield 2. Connect team members to online sessions, create detailed tactics together in real time. Includes zoom, text tools, export tactics, and Custom Map Wizard.
- [Dragon UnPACKer (Battlefield 2)](https://www.moddb.com/games/battlefield-2/downloads/dragon-unpacker) - Tool for viewing and extracting files from game archive formats (e.g., Quake 2 PAK files). Includes HyperRipper for scanning files for known formats.
  - Formats: MP3, OGG, WAV, AVI, TGA, BMP.

#### Star Wars: Battlefront

- [StarWars Battlefront unpacker / decoder](https://www.moddb.com/games/star-wars-battlefront/downloads/starwars-battlefront-unpacker-decoder) - Custom toolset for unpacking and extracting Star Wars: Battlefront archives.
- [Star Wars: Battlefront Modification Tools](https://www.moddb.com/games/star-wars-battlefront/downloads/star-wars-battlefront-modification-tools) - Official modding tools for creating levels in Star Wars: Battlefront. Originally from Game Front. Download subject to End User License Agreement terms.
- [3D Object Converter (Star Wars Battlefront II)](https://www.moddb.com/games/star-wars-battlefront-ii/downloads/3d-object-converter) - Polygon-based 3D object file format converter supporting 440 file formats.

### EgoSoft (X4)

- [X4Tools](https://github.com/REDxEYE/X4Tools) - X4 资产导入/导出的独立插件。

### Capcom

#### RE Engine

- [REE.PAK.Tool](https://github.com/Ekey/REE.PAK.Tool) - RE ENGINE PAK 解包/回打工具。
- [RE-Engine-VSDF-Template](https://github.com/Silvris/RE-Engine-VSDF-Template) - RE Engine VSDF 模板。

#### Resident Evil

- [BioHazard File Archive Tool (Resident Evil 4)](https://www.moddb.com/games/resident-evil-4/downloads/biohazard-file-archive-tool) - 《生化危机 4》封包工具，提供 XP 版与 Win7 移植版（均 32 位，兼容 64 位）。

#### Monster Hunter

- [mh1j (decomp)](https://github.com/2Tie/mh1j) - 《怪物猎人》初代（PS2 日版）匹配反编译。
- [mhst2-arc-tool](https://github.com/Fexty12573/mhst2-arc-tool) - 《怪物猎人物语 2》封包工具。
- [MHW-Research](https://github.com/TheCrazyT/MHW-Research) - 《怪物猎人：世界》格式研究与工具。
- [MHST2-Save-Tools](https://github.com/AsteriskAmpersand/MHST2-Save-Tools) - 《怪物猎人物语 2》存档工具。
- [Mod3-MHW-Importer](https://github.com/AsteriskAmpersand/Mod3-MHW-Importer) - Blender 导入/导出 MHW Mod3 模型。
- [RingingBloom](https://github.com/Silvris/RingingBloom) - WWise 音频编辑套件，适配 MHW 等 Capcom 作品。
- [GFDConverter](https://github.com/onepiecefreak3/GFDConverter) - 将 MT Framework 的 GFD v1 转 v2。
- [GMDConverter](https://github.com/onepiecefreak3/GMDConverter) - MT Framework GMD 转换器，支持 v1/v2。
  - 功能：BNK/PCK 编辑、循环计算、WEM 生成、WWCT/WWBK/WWPK/EPVSP 编辑。
  - 格式：.nbnk/.bnk、.npck/.pck、.wwct、.wwbk/.wwpk、.epvsp、.wem。

#### Devil May Cry

- [dmc_hd_tools](https://github.com/Kerilk/dmc_hd_tools) - 《鬼泣 HD 合集》工具包，含 Noesis 插件与二进制模板。

#### Street Fighter

- [3s-decomp (decomp)](https://github.com/crowded-street/3s-decomp) - 《街霸 3 三度冲击》PS2 匹配反编译。

#### Ultimate Marvel vs Capcom 3

- [umvc3-tools](https://github.com/tge-was-taken/umvc3-tools) - 《终极漫威 vs 卡普空 3》工具与研究，含 MT Framework MOD 导入/导出（3ds Max）、TEX/MTL 转换、二进制模板。
- [ThreeWorkTool](https://github.com/EternalYoshi/ThreeWorkTool) - GUI 管理 UMVC3 的 MT .arc，支持 DDS 导入、角色动画关键帧进/出、归档管理。

#### Mega Man

- [mmx4 (decomp)](https://github.com/sozud/mmx4) - 《洛克人 X4》PS1 匹配反编译。
- [MegaManPoweredUpTool](https://github.com/efimandreev0/MegaManPoweredUpTool) - 提取《洛克人改造计划》主封包。
- [MegaManLINKExtract](https://github.com/efimandreev0/MegaManLINKExtract) - 处理《洛克人改造计划》.link 封包。
- [ARC Unpacker & Repacker](https://www.moddb.com/games/devil-may-cry-4/downloads/arc-unpacker-repacker-v09428) - MT Framework ARC 解/打包（RE5/RE6/DD/ DMC4 等），可转换多种封包内格式。

#### Gregory Horror Show

- [GregoryHorrorShow-Blender-IO](https://github.com/boringhexi/GregoryHorrorShow-Blender-IO) - 将 PS2《格雷戈里恐怖秀》资产 (.ghs/.map-pm2/.pm2) 导入 Blender。

#### Gotcha Force

- [gotcha-afs-tool](https://github.com/RenolY2/gotcha-afs-tool) - 《玩具战记》AFS 解/打包（GC 版测试）。

#### Phoenix Wright: Ace Attorney

- [pwaa1 (decomp)](https://github.com/atasro2/pwaa1) - 《逆转裁判 1》（日版）匹配反编译。
- [recv-dc-decomp (decomp)](https://github.com/fmil95/recv-dc-decomp) - 《生化危机 代号：维罗妮卡》DC 版反编译。
- [recvx-decomp (decomp)](https://github.com/fmil95/recvx-decomp) - 《生化危机 代号：维罗妮卡 X》PS2 版反编译。

### CCR (RF Online)

- [RF Online Addon](https://github.com/Cardboard-box-a/cbb-rf-online-addon) - Blender 4.3 导入/导出 RF Online `.msh/.bn/.ani/.bsp`。

### CCP Games (EVE Online)

- [yretenai/Jackdaw](https://github.com/neptuwunium/Jackdaw) - EVE Online Carbon 引擎格式研究。

### CR-Space (Martial Heroes)

- [Diamond](https://github.com/tge-was-taken/Diamond) - 《武林群英传》逆向与增强项目，含解析器、VFS 工具、010 模板等。

### CD Projekt Red

#### The Witcher 3 / REDEngine 3

- [WolvenManager](https://github.com/rfuzzo/WolvenManager) - 《巫师》系列文件格式管理器。
- [WolvenKit (legacy)](https://github.com/WolvenKit/WolvenKit-7) - REDEngine 3 文件编辑器，加速《巫师 3》Mod 流程（旧版）。

#### The Witcher

- [Blender 2.49 exporter for The Witcher](https://www.moddb.com/games/the-witcher/downloads/blender-exporter-for-the-witcher) - Blender 2.49 导出静态模型为《巫师 1》MDL 脚本。
- [twMax v1.2.3.2 -- mdb Importer for 3DSMax (The Witcher)](https://www.moddb.com/games/the-witcher/downloads/twmax-v1232-mdb-importer-for-3dsmax) - 《巫师》MDB 二进制模型导入 3DS Max 9 (v1.2.3.2)。
- [Extra tools (The Witcher)](https://www.moddb.com/games/the-witcher/downloads/extra-tools) - 《巫师》DLG/QST/BIF/MDB/GFF/NSS 工具合集。

#### Cyberpunk 2077 / REDEngine 4

- [WolvenKit](https://github.com/WolvenKit/WolvenKit) - REDEngine 4 文件编辑器，加速《赛博朋克 2077》Mod。
- [Cyber Engine Tweaks](https://github.com/maximegmd/CyberEngineTweaks) - Lua 脚本框架，开放内部脚本 API。
- [inl-cpp-parser-mangler](https://github.com/Mozz3d/inl-cpp-parser-mangler) - 独立内联 C++ 解析/改名/哈希脚本，用于逆向 CP2077 链接名。
- [CR2WTools](https://github.com/rfuzzo/CR2WTools) - WIP，读取 CR2W（巫师/赛博朋克）文件的库。
- [Gibbed.RED4](https://github.com/gibbed/Gibbed.RED4) - CP2077 文件格式工具。

### Clover Studio (Okami)

- [noclip.website (Okami)](https://github.com/magcius/noclip.website/tree/main/src/rres) - 浏览器版《大神》查看器。

### Cygames (Granblue Fantasy Relink)

- [GBFRBlenderTools](https://github.com/WistfulHopes/GBFRBlenderTools) - Blender 导入《蔚蓝幻想 Relink》网格。
- [GBFR2Blender2GBFR](https://github.com/WistfulHopes/GBFR2Blender2GBFR) - 《Relink》动画/碰撞导入导出工具。

### Disney Interactive

#### Toontown Online

- [omUlette](https://github.com/lifelandman/omUlette) - 轻量导出 Panda3D `.egg`（Toontown）文件，无需安装 Panda3D。

### Double Fine (Psychonauts, Costume Quest)

- [CostumeQuest-Decomp (decomp)](https://github.com/Costume-Quest-Modding/CostumeQuest-Decomp) - 《万圣节小捣蛋》PC 匹配反编译。
- [noclip.website (Psychonauts)](https://github.com/magcius/noclip.website/tree/main/src/psychonauts) - 浏览器版《脑航员》查看器。

### 8monkey Labs

- [Translation Tool (Darkest of Days)](https://www.moddb.com/games/darkest-of-days/downloads/darkest-of-days-translation-tool) - 《最黑暗的物质》翻译工具。

### Crystal Dynamics / Eidos Interactive

- [soul-re (decomp)](https://github.com/fmil95/soul-re) - 《凯恩的遗产：噬魂者》PS1 匹配反编译。
- [gex64decomp (decomp)](https://github.com/matbourgon/gex64decomp) - 《壁虎小子 64》匹配反编译。
- [Blood Omen 2 3D Rip Tools](https://www.moddb.com/games/blood-omen-2/downloads/blood-omen-2-3d-rip-tools) - CLI 工具，将《嗜血印记 2》原始 3D 模型导出为 OBJ/DDS。
- [trview](https://github.com/chreden/trview) - 速通向的《古墓丽影 1-5》关卡查看器（房间、触发、路线分析）。格式：.TR2/.TR4/.TRC/.PHD。

### Ion Storm

#### Anachronox

- [Anachronox Modding Tools](https://www.moddb.com/games/anachronox/downloads/anachronox-modding-tools) - 《时空之轮 Anachronox》制图/Mod 工具，含文档。

#### Deus Ex

- [cdcEngineDXHR (decomp)](https://github.com/rrika/cdcEngineDXHR) - 《杀出重围：人类革命》匹配反编译。
- [Gibbed's Deus Ex HR tools](https://www.moddb.com/games/deus-ex-3/downloads/gibbeds-deus-ex-hr-tools) - Crystal Dynamics 引擎数据编/反编译工具 (.NET 4 Client Profile)。

### Massive Entertainment

#### AquaNox

- [aquanox-tools](https://github.com/Swyter/aquanox-tools) - 《深海霸主》初代格式逆向工具，含 010 模板解密 .pak、提取脚本，文档覆盖 .dds/.tga/.sco/.des/.fog/.msb。
- [AquaNox 1-2 modding tools](https://www.moddb.com/games/aquanox/downloads/aquanox-1-2-modding-tools) - 《深海霸主》1-2 Mod 工具：存档编辑、PAK 解包、MSB→X 转换、指南等。

#### World in Conflict

- [Broadcast Tool v6/7/8 (World in Conflict)](https://www.moddb.com/games/world-in-conflict/downloads/broadcast-tool-v8) - DX10 观战广播工具（v6/v7/v8），便于局域网或多人比赛旁观。

### Surreal Software

- [Drakan Editing Tools v1.2](https://www.moddb.com/games/drakan-order-of-the-flame/downloads/drakan-editing-tools-v12) - 《神龙传说》关卡/模型编辑器。
- [reo converter to obj (Drakan: Order of the Flame)](https://www.moddb.com/games/drakan-order-of-the-flame/downloads/reo-converter-to-obj) - Roosen5 制作，将 .reo 转 OBJ，便于关卡编辑/Mod。

### Dynamix / Sierra

#### Tribes Series

- [Tribes 2 3D Studio MAX Export Plug-in](https://www.moddb.com/games/tribes-2/downloads/tribes-2-3d-studio-max-export-plug-in) - 3ds Max v2.5 导出插件，制作/修改《Tribes 2》物体。
- [Tribes: Vengeance Editing Tools](https://www.moddb.com/games/tribes-vengeance/downloads/tribes-vengeance-editing-tools) - 《Tribes: Vengeance》地图编辑器 TribesEd 测试版。
- [Tribes 1.40 LoDFix plugin](https://www.moddb.com/games/tribes/downloads/tribes-140-lodfix-plugin) - Plugin that fixes a known level of detail (LOD) issue with certain weapons in Tribes. Affects users with field of view (FOV) higher than default. Place LoDFix.dll in plugins folder. Created by Groove (v1.40).

### DOKA Studios

- [reSL (decomp)](https://github.com/konovalov-aleks/reSL) - 《ShortLine》v1.1 匹配反编译。

### EA Black Box

- [Castaway (decomp)](https://github.com/HaydnTrigg/Castaway) - 《模拟人生 2：荒岛求生》匹配反编译。

#### Need for Speed Series

- [Binary](https://github.com/NFSCO/Binary) - 编辑 Black Box NFS 的 .BIN/.BUN/.LZC。
- [Icebreaker](https://github.com/R-033/icebreaker) - NIS（NFS:MW 过场）编辑。
- [MAD x VP6 x MPC x MPV x WMV Compiler](https://github.com/bluesky-dev12/MAD-x-VP6-x-MPC-x-MPV-x-WMV-Compiler) - 为 BB 游戏编译 WMV/MAD/VP6/MPC/MPV 的工具集。
- [NFS.BIN.Tool](https://github.com/Ekey/NFS.BIN.Tool) - 解包主机版 NFS ZZDATA。
- [NFS Carbon PDFData Compiler](https://github.com/bluesky-dev12/PFDataCompiler) - 将音乐转为 NFS Carbon 格式。
- [NFS SPEECHTOOL](https://github.com/TheUnpunished/SpeechTool) - 编辑 NFS PS/Undercover/World 语音音频。
- [NFS TMXTOOL](https://github.com/TheUnpunished/tmxtool) - PS/Undercover/World TMX 音频编码器。
- [UCGT](https://github.com/NI240SX/UCGT) - NFS Undercover 几何编辑/编解器。
- [Vivianne](https://github.com/TheXDS/Vivianne) - NFS3/4 VIV 与 FSH/QFS 全能编辑（贴图、性能、fedata）。
- [noclip.website (Need for Speed: Most Wanted)](https://github.com/magcius/noclip.website/tree/main/src/NeedForSpeedMostWanted) - 浏览器版《NFS：最高通缉》查看器。

### FromSoftware

*Demon's Souls, Dark Souls, Bloodborne, Sekiro, Elden Ring.*

- [UXM](https://github.com/JKAnderson/UXM) - 《黑魂 3》《只狼》封包解包。
- [DarkSoulsIII.FileFormats](https://github.com/Atvaark/DarkSoulsIII.FileFormats) - 读取《黑魂 3》格式的库。
- [dstools](https://github.com/katalash/dstools) - 《黑魂》系列格式工具。
- [ds3-open-re](https://github.com/garyttierney/ds3-open-re) - 《黑魂 3》公开逆向资料。
- [ParamCrypt](https://github.com/Grimrukh/ParamCrypt) - 《黑魂》param 加解密。
- [Souls Modding Wiki](https://www.soulsmodding.com/doku.php?id=start) - FS 系格式文档。
- [libER](https://github.com/Dasaav-dsv/libER) - 《艾尔登法环》C++20 API 库，精确布局、类型/线程安全，按版本分符号。
- [Awesome Elden Ring](https://github.com/sovietspaceship/awesome-elden-ring) - 《艾尔登法环》资源合集。
- [Sekiro Modding Wiki](https://github.com/SekiroResurrection/modding-wiki) - 《只狼》Mod 文档。
- [DSMapStudio](https://github.com/soulsmods/DSMapStudio) - 魂/血/法环地图编辑器。
- [DSMSPortable](https://github.com/mountlover/DSMSPortable/tree/main) - DSMapStudio 便携版。
- [FLVER_Editor](https://github.com/asasasasasbc/FLVER_Editor) - 多功能 FLVER 查看/编辑（只狼、黑魂、血源等）。
- [elden-ring-open-re](https://github.com/garyttierney/elden-ring-open-re) - 《艾尔登法环》逆向公开资料。
- [BinderTool](https://github.com/Atvaark/BinderTool) - BND/BHD 解/打包。
- [dark-souls-map-viewer](https://github.com/colevk/dark-souls-map-viewer) - Web 版《黑魂》地图查看。
- [blender-flver](https://github.com/elizagamedev/blender-flver) - Blender 导入/导出 FLVER（黑魂/重制/血源/只狼）。
- [Coremats](https://github.com/JKAnderson/Coremats) - .NET FS 格式库。
- [soulsformats-rs](https://github.com/garyttierney/soulsformats-rs) - Rust 读取/写入 FS 近代游戏格式。
- [FromSoftware-Blender-Importer](https://github.com/FelixBenter/FromSoftware-Blender-Importer) - Blender 导入 FLVER（DS1/2/3、只狼；角色/parts/地图）。
- [soulstruct](https://github.com/Grimrukh/soulstruct) - Python 库，魂系列格式/Mod。
- [soulstruct-blender](https://github.com/Grimrukh/soulstruct-blender) - soulstruct 的 Blender 插件。
- [SoulsTemplates](https://github.com/JKAnderson/SoulsTemplates) - 魂系列 010 模板。
- [noclip.website (DarkSouls)](https://github.com/magcius/noclip.website/tree/main/src/DarkSouls) - 浏览器版《黑魂》地图。
- [DSAnimStudio](https://github.com/Meowmaritus/DSAnimStudio) - 魂系动画/过场编辑。
- [dark_souls_hkx](https://github.com/Danilodum/dark_souls_hkx) - Noesis HKX 插件，支持根骨/根运动。
- [ESDLang](https://github.com/thefifthmatt/ESDLang) - ESD 事件脚本反编译。
- [Zeditor](https://github.com/AinTunez/Zeditor) - ESD 编辑器。
- [Gibbed.DarkSouls](https://github.com/gibbed/Gibbed.DarkSouls) - 《黑魂》工具与代码。
- [DS2Template](https://github.com/LordRadai/DS2Template) - 《黑魂 2》专用 010 模板。
- [ER.DATA.Tool](https://github.com/Ekey/ER.DATA.Tool) - 《重启地球》（移动端）数据封包解包。

### Frictional Games (Amnesia, Soma)

- [AmnesiaLoader](https://github.com/REDxEYE/AmnesiaLoader) - UniLoader 插件，适配 Frictional（《失忆症》《Soma》等）。

### Gearbox Software

- [Gibbed.Borderlands3.Datamining](https://github.com/gibbed/Gibbed.Borderlands3.Datamining) - 《无主之地 3》数据挖掘工具。
- [Borderlands 2 Texture Modding Tool for PC](https://www.moddb.com/games/borderlands-2/downloads/borderlands-2-texture-modding-tool-for-pc) - PC 端贴图提取/编辑/替换指南与 TexMod。

#### MechWarrior 4

- [MW4 Sound Extractor (MechWarrior 4: Mercenaries)](https://www.moddb.com/games/mechwarrior-4-mercenaries/downloads/mw4-sound-extractor) - 《机甲佣兵 4》音频提取器。

### Game Freak

*Pokémon games across various generations.*

#### Gen I & II

- [map-editor](https://github.com/KernelEquinox/map-editor) - 宝可梦一/二代地图编辑器。
- [polished-map](https://github.com/Rangi42/polished-map) - 二代地图编辑器（Polished Map）。
- [puzzleleague64 (decomp)](https://github.com/angheloalf/puzzleleague64) - 《宝可梦拼图联盟》匹配反编译。
- [xd-decomp (decomp)](https://github.com/TeamOrre/xd-decomp) - 《宝可梦 XD：暗之旋风 黑暗龙》GC 版匹配反编译。
- [pokeheartgold (decomp)](https://github.com/pret/pokeheartgold) - 《心金》匹配反编译 (100%)。
- [pokefirered (decomp)](https://github.com/pret/pokefirered) - 《火红》匹配反编译 (100%)。
- [pokecrystal (decomp)](https://github.com/pret/pokecrystal) - 《水晶》匹配反编译 (100%)。
- [pokegold (decomp)](https://github.com/pret/pokegold) - 《金》匹配反编译 (100%)。
- [pokegold-spaceworld (decomp)](https://github.com/pret/pokegold-spaceworld) - 《金》SpaceWorld Demo 匹配反编译 (100%)。
- [pokeyellow (decomp)](https://github.com/pret/pokeyellow) - 《黄》匹配反编译 (100%)。
- [pokered (decomp)](https://github.com/pret/pokered) - 《红》匹配反编译 (100%)。

#### Gen III

*音频工具见 [Sappy (GBA Audio)](#sappy-gba-audio)。*

- [SaveStadium](https://github.com/Ploaj/SaveStadium) - 《精灵宝可梦 竞技场》存档编辑。
- [Wargrave-Pokemon-Gen2-Editors](https://github.com/sandbPublic/Wargrave-Pokemon-Gen2-Editors) - 二代编辑器。
- [Pokemon-Shuffle-Unpacker](https://github.com/SciresM/Pokemon-Shuffle-Unpacker) - 《宝可梦拼图》封包解包。
- [JPoke-Export](https://github.com/vgmoose/JPoke-Export) - 宝可梦存档导出。
- [blue-spider](https://github.com/cosarara/blue-spider) - 红/蓝宝石/绿宝石地图编辑。
- [porymap](https://github.com/huderlem/porymap) - 三代现代地图编辑器。
- [MEH](https://github.com/shinyquagsire23/MEH) - 三代地图编辑器。
- [pokeemerald-jp (decomp)](https://github.com/pret/pokeemerald-jp) - 《绿宝石》日版匹配反编译 (100%)。
- [pokeemerald (decomp)](https://github.com/pret/pokeemerald) - 《绿宝石》匹配反编译 (100%)。
- [AwesomeMapEditor](https://github.com/Sierraffinity/AwesomeMapEditor) - 三代备选地图编辑器。
- [pokeruby (decomp)](https://github.com/pret/pokeruby) - 《红宝石》匹配反编译 (100%)。
- [gomons](https://github.com/huderlem/gomons) - Go 库，读写《绿宝石》存档。
- [Bulbapedia (Gen I)](https://bulbapedia.bulbagarden.net/wiki/Save_data_structure_(Generation_I)) - 一代存档结构。
- [Bulbapedia (Gen II)](https://bulbapedia.bulbagarden.net/wiki/Save_data_structure_(Generation_II)) - 二代存档结构。
- [Bulbapedia (Gen III)](https://bulbapedia.bulbagarden.net/wiki/Save_data_structure_(Generation_III)) - 三代存档结构。

#### Gen VI

- [pokediamond (decomp)](https://github.com/pret/pokediamond) - 《钻石》匹配反编译 (100%)。
- [pokeplatinum (decomp)](https://github.com/pret/pokeplatinum) - 《白金》匹配反编译 (100%)。
- [Personal-Editor](https://github.com/SciresM/Personal-Editor) - 六代（XY、ORAS）Personal.GARC 提取后的编辑器。

#### Gen V

- [SwissArmyKnife](https://github.com/PlatinumMaster/SwissArmyKnife) - 五代（黑/白/黑2/白2）跨平台 ROM 编辑器，支持地图容器/文本/事件/区域/实体/遭遇。
- [pbr-dtk (decomp)](https://github.com/bgsamm/pbr-dtk) - 《宝可梦对战革命》匹配反编译。
- [pokestadium (decomp)](https://github.com/pret/pokestadium) - 《宝可梦竞技场》匹配反编译 (100%)。
- [pokestadiumgs (decomp)](https://github.com/pret/pokestadiumgs) - 《宝可梦竞技场 2》匹配反编译 (100%)。
- [pmd-red (decomp)](https://github.com/pret/pmd-red) - 《宝可梦不可思议迷宫：赤之救助队》匹配反编译 (100%)。
- [pmd-sky (decomp)](https://github.com/pret/pmd-sky) - 《探险队：空》匹配反编译 (100%)。
- [pokepinballrs (decomp)](https://github.com/pret/pokepinballrs) - 《宝可梦弹珠台 红蓝宝石》匹配反编译 (100%)。
- [pokepinball (decomp)](https://github.com/pret/pokepinball) - 《宝可梦弹珠台》匹配反编译 (100%)。
- [poketcg (decomp)](https://github.com/pret/poketcg) - 《宝可梦集换式卡牌 GB》匹配反编译 (100%)。
- [poketcg2 (decomp)](https://github.com/pret/poketcg2) - 《宝可梦集换式卡牌 2》匹配反编译 (100%)。
- [pokeblack (decomp)](https://github.com/pokemodding/pokeblack) - 《宝可梦 黑》匹配反编译。

### Gameloft

- [GameloftEngineLoader](https://github.com/REDxEYE/GameloftEngineLoader) - UniLoader 插件，导入 Gameloft 引擎 PIG（含网格/贴图/变换/节点，LZ4/ZSTD）。
- [Greenier-Farm-3-Decomp (decomp)](https://github.com/SmithGoll/Greenier-Farm-3-Decomp) - 《Green Farm 3》匹配反编译。

### Genius Sonority

*Pokémon Colosseum, Pokémon XD: Gale of Darkness.*

- [pokemon_fsys_tool](https://github.com/gamemasterplc/pokemon_fsys_tool) - 《斗技场/暗之旋风黑暗龙》FSYS 封包工具。
- [PokemonFSYSConverter](https://github.com/vgmoose/PokemonFSYSConverter) - 从部分 GC/Wii .fsys 提取 .obm 与贴图。
- [tdmextractor](https://github.com/NerduMiner/tdmextractor) - 《电子宠物人》系列封包解/打包，可替代 The Denpa Men 3 的 quickbms 脚本。

### Genki

*Jade Cocoon: Story of the Tamamayu, Jade Cocoon 2.*

- [Jade-Cocoon-Unpacker-Repacker](https://github.com/Meos4/Jade-Cocoon-Unpacker-Repacker) - 《玉繭物语》PS1 DATA.001 解/打包。
- [Jade-Cocoon-2-Unpacker-Repacker](https://github.com/Meos4/Jade-Cocoon-2-Unpacker-Repacker) - 《玉繭物语 2》PS2 封包解/打包。
- [Tamamayu-Monogatari-Dennou-Bijutsukan-Unpacker](https://github.com/Meos4/Tamamayu-Monogatari-Dennou-Bijutsukan-Unpacker) - 玉繭物语试作版 DATA.001 解包。
- [GUTArchiveTools](https://github.com/igorciz777/GUTArchiveTools) - GUT 封包工具，适配 Genki PS2 赛车（湾岸系列等）。

### Grezzo

*Ocarina of Time 3D, Majora's Mask 3D, Luigi's Mansion remake, Ever Oasis.*

- [io_scene_cmb](https://github.com/M-1-RLG/io_scene_cmb) - Blender 插件，导入 Grezzo CMB。
- [noclip.website (OoT3D)](https://github.com/magcius/noclip.website/tree/main/src/OcarinaOfTime3D) - 浏览器版《时之笛 3D》查看器。
- [MeltyTool (Grezzo)](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Libraries/Grezzo) - Grezzo 格式查看/导出。
- [N3DSCmbViewer](https://github.com/xdanieldzd/N3DSCmbViewer) - 3DS CMB 模型查看器。
- [Scarlet](https://github.com/xdanieldzd/Scarlet) - 通用 3DS/Vita 工具。
- [Gar/Zar UnPacker](https://gbatemp.net/threads/release-gar-zar-unpacker-v0-1.385264/) - 《时之笛 3D》《穆修拉假面 3D》Gar/Zar 解包。
- [Switch-Toolbox](https://github.com/KillzXGaming/Switch-Toolbox/tree/master/File_Format_Library/FileFormats/Grezzo) - 处理多种游戏格式的工具，含 Grezzo 支持。
- [GARTool](https://github.com/efimandreev0/GARTool) - 在《Ever Oasis》《路易鬼屋》等测试的 GAR 工具。
- [irarc_unpacker](https://github.com/efimandreev0/irarc_unpacker) - IRARC 解包（《Blaster Master Zero》《枪弹辩驳》3DS 等）。

### Human Head Studios

- [Gwynhala's Model Exporter (Rune)](https://www.moddb.com/games/rune/downloads/gwynhalas-model-exporter) - 《符文》SuperCoolModel 导出器（Milkshape 3D）。

### id Software

- [DOOM64-RE (decomp)](https://github.com/Erick194/DOOM64-RE) - 《毁灭战士 64》匹配反编译。
- [PSXDOOM-RE (decomp)](https://github.com/Erick194/PSXDOOM-RE) - PS 版《毁灭战士》匹配反编译。
- [valen](https://github.com/jandk/valen) - 多游戏资源提取 GUI，支持《DOOM Eternal》《Dark Ages》《Great Circle》等，带浏览/批导出/贴图模型骨骼动画预览。
  - Formats: DDS, PNG, GLTF (export).
- [blender_io_mesh_bsp](https://github.com/andyp123/blender_io_mesh_bsp) - Blender 导入 Quake BSP 地图。
- [wadext](https://github.com/ZDoom/wadext) - WAD 解包 CLI，支持 Doom/Heretic/Hexen/Strife 调色板，提取并转 PNG/WAV。
- [DOOMP](https://github.com/Ret-HZ/DOOMP) - Doom 格式解析/提取。
- [DoomRPG-RE-3DS](https://github.com/efimandreev0/DoomRPG-RE-3DS) - 逆向《Doom RPG》3DS 移植。
- [rtcw-wet-blender-model-tools](https://github.com/mino-git/rtcw-wet-blender-model-tools) - 《RTCW: ET》Blender 模型工具。
- [ExtractDoomDisk](https://github.com/gibbed/ExtractDoomDisk) - Doom 光盘镜像提取。
- [Doom 3 model import tutorial files](https://www.moddb.com/games/doom-iii/downloads/doom-3-model-import-tutorial-files) - Doom 3 模型导入教程示例文件。
- [Doom 3 Compatibility Tool Mod](https://www.moddb.com/games/doom-iii/downloads/doom-3-compatibility-tool-mod) - Doom 3 兼容性工具。
- [Doom 3 - Quake 3 Map Converter](https://www.moddb.com/games/doom-iii/downloads/doom-3-quake-3-map-converter) - Quake3 地图→Doom3/Quake4 格式转换，亦可转换贴图。
- [Doom 3: ROE (XBOX) .gfc extract](https://www.moddb.com/games/doom-iii/downloads/doom-3-roe-xbox-gfc-extract) - QuickBMS 脚本，提取 Doom3: ROE Xbox 版 .gfc。
- [Doom maps Converter 1.4](https://www.moddb.com/games/doom-iii/downloads/doom-maps-converter-14) - Converter of old Doom maps to maps for Doom 3, made from QuakeDM sources.
- [DOOM Audio Tools](https://www.moddb.com/games/doom-4/downloads/doom-audio-tools) - Dragon UnPACKer, Wwise ADPCM Converter, Batch script for handling multiple files. Guide below.
- [Export Font To Doom 3 v1.02](https://www.moddb.com/games/doom-iii/downloads/export-font-to-doom-3-v102) - A command-line application that exports standard fonts into Doom 3's font format. Created by Grant Davis. Includes source code.
- [.GOB & global.d3tfull unpacker (Doom III)](https://www.moddb.com/games/doom-iii/downloads/gob-globald3tfull-unpacker)
- [IdTech4 File Unpacker 1.5 (Doom III)](https://www.moddb.com/games/doom-iii/downloads/idtech4-file-unpacker-15) - IdTech4 (Trinity) 自动解包：Doom3/ROE、Quake4、Prey、ETQW、Wolfenstein (v1.5)。
- [Lightwave to MD5 converter (Doom III)](https://www.moddb.com/games/doom-iii/downloads/lightwave-to-md5-converter)
- [Daikatana to Quake 2 model converter](https://www.moddb.com/games/daikatana/downloads/daikatana-to-quake-2-model-converter) - 《武士刀》→Quake2 模型转换，含源码。
- [Quake 1 Model Viewer v0.50 alpha](https://www.moddb.com/games/quake/downloads/quake-1-model-viewer-v050-alpha) - Quake1 模型查看器 (v0.50 alpha)。
- [Skyboxer - Map-to-Skybox Tool for Quake (1.0)](https://www.moddb.com/games/quake/downloads/skyboxer-a-map-to-skybox-tool-for-quake-10) - 将 Quake 地图生成天空盒的工具 (v1.0)。
- [Adjusted MD5 blender exporter (Quake III Arena)](https://www.moddb.com/mods/project-rdx/downloads/adjusted-md5-blender-exporter) - 修改版 Blender MD5 导出器，可选择不导出某些通道，便于组合动画。
- [Q3-Games Model Tool v1.6.0 (Quake III Arena)](https://www.moddb.com/games/quake-iii-arena/downloads/q3-games-model-tool-v160) - Q3 引擎模型工具（原 ET Model Tool），供玩家模型/地图/Mod 制作者使用 (v1.6.0)。
- [RtCW �?SDK Editing Tools v1.1 (Return to Castle Wolfenstein)](https://www.moddb.com/mods/rtcw-classic-cooperative-campaign/downloads/rtcw-sdk-editing-tools-v11) - Editing tools for creating and editing Return to Castle Wolfenstein levels for solo and multiplayer modes. Includes WolfRadiant editor (updated version of QERadiant/GTK Radiant). Not the full SDK (v1.1).
- [RTCW .bsp to .map Converter (Return to Castle Wolfenstein)](https://www.moddb.com/games/return-to-castle-wolfenstein/downloads/rtcw-bsp-to-map-converter) - RtCW .BSP to .MAP Converter - A very handy map-making tool for Return to Castle Wolfenstein mappers, either new or experienced. The "comdlg32.ocx" file is also included in the download, with instructions on how to install it. Usage Information # Run DeBSP.EXE and [Browse] for the BSP file you wis...
- [Wolfenstein SPK & MPK Extractor v0.2](https://www.moddb.com/games/wolfenstein/downloads/wolfenstein-spk-mpk-extractor-v02) - The Wolfenstein SPK/MPK Extractor made by Bellox902 is a powerful tool to extract .spk/.mpk gamefiles from the Wolfenstein Game. These files contain all kinds of stuff like the music (.mp3), bink videos (.bik) or textures (.dds). The latest 0.2 version can also pack mp3 files into spk/mpk!
- [Blender Terrain scripts (Quake III Arena)](https://www.moddb.com/mods/project-rdx/downloads/blender-terrain-scripts) - Blender scripts to turn an elevation grid into a terrain in .map format to be used in Radiant.
- [Blocks II v0.2 Editing Package (Doom II)](https://www.moddb.com/mods/blocks-of-doom-ii/downloads/blocks-ii-v02-editing-package) - Editing package with all tools needed to create levels for Blocks of Doom II (v0.2).
- [Blender MD3 Import-Export Tool](https://www.moddb.com/games/quake-iii-arena/downloads/blender-md3-import-export-tool) - MD3 import/export script for Blender with shader path configuration, material name mapping, animation frame export, and UV image preview.

### Guerrilla Games

- [ProjectZeroDawn](https://github.com/neptuwunium/ProjectZeroDawn) - 《地平线：零之曙光》格式研究与工具。
- [decima](https://github.com/ShadelessFox/decima) - Decima 引擎资源 GUI 查看/编辑/导出/回打，支持 HZD/死亡搁浅等。
- [decima-native](https://github.com/ShadelessFox/decima-native) - Decima 工具的本地库组件。
- [decima-rpcs3-dumper](https://github.com/ShadelessFox/decima-rpcs3-dumper) - 从 RPCS3 导出 Decima 资源。
- [odradek](https://github.com/ShadelessFox/odradek) - 《地平线：西之禁地》资产查看/提取，Decima Workshop 的延续。
- [forbidden-west-localizer](https://github.com/ShadelessFox/forbidden-west-localizer) - 《西之禁地》本地化修改，支持 JSON 替换文本。
- [cauldron](https://github.com/cauldronloader/cauldron) - Decima 游戏 Mod Loader（HZD/西之禁地/死亡搁浅），Rust 实现，DLL 代理与 RTTI dump。
- [stormbird](https://github.com/neptuwunium/stormbird) - HZD 互操作库，处理其格式与数据。
- [decima-dmf](https://github.com/REDxEYE/decima-dmf) - Blender 导入 Decima Workshop 生成的 DMF。
- [ProjectDecima](https://github.com/spammydavis/ProjectDecima) - Decima 资源预览/导出/修改 GUI，含归档浏览与贴图预览（分支版）。

### LucasArts

- [rogue_squadron64 (decomp)](https://github.com/Tmcg2/rogue_squadron64) - 《星球大战：侠盗中队》N64 匹配反编译。
- [SW_RACER_RE (decomp)](https://github.com/tim-tim707/SW_RACER_RE) - 《星战前传 1：赛车》匹配反编译。
- [scummtools](https://github.com/UnBeatWaterGH/scummtools) - SCUMM 脚本/资源工具。
- [Grim Fandango model viewer](https://www.moddb.com/games/grim-fandango/downloads/grim-fandango-model-viewer) - 《神通鬼大》模型查看器。
- [Easy Saber Editing Script 2.0 (Jedi Academy)](https://www.moddb.com/games/star-wars-jedi-academy/downloads/easy-saber-editing-script-2-0) - 跳过光剑菜单给默认光剑的脚本 (v2.0)。
- [JK editing manuals (Jedi Knight: Dark Forces II)](https://www.moddb.com/games/star-wars-jedi-knight-dark-forces-ii/downloads/jk-editing-manuals) - JED 关卡编辑教程离线合集。
- [JKVersions Tool 3.0](https://www.moddb.com/mods/todoa/downloads/jkversions-tool-by-the-mazzter) - 提取 JK 1.01 并降/升到 JKUP 的工具 (v3.0)。

### Gust (Koei Tecmo)

- [slpm86183 (decomp)](https://github.com/Erizur/slpm86183) - 《Pop'n Music CS1》PS1 匹配反编译。
- [gust_stuff](https://github.com/eArmada8/gust_stuff) - Gust 游戏（炼金工房等）G1M 模型 Mod 工具集。
- [Project-G1M](https://github.com/Joschuka/Project-G1M) - Noesis 插件，导入 Gust / Bandai Namco 的 G1M。
- [Cethleann](https://github.com/neptuwunium/Cethleann) - KTGL(Soft Engine) 数据探索工具，适配光荣特库摩作品。

### Harmonix

*Rock Band, Guitar Hero, Amplitude, Dance Dance Revolution Universe, Frequency, Karaoke Revolution.*

- [rb3ds (decomp)](https://github.com/ieee802dot11ac/rb3ds) - 《摇滚乐队 3》NDS 匹配反编译。
- [LibForge](https://github.com/maxton/LibForge) - 读写/转换 Forge 引擎格式（RB4、RB VR、FUSER）；[PikminGuts92 分支](https://github.com/PikminGuts92/LibForge) 增补 v2 RB MIDI、MAGMA v1、AMP/RBVR .mid_*。
  - Formats: MIDI, PNG/BMP (textures), FBX/OBJ (models), DTA/DTB, RBmid, RBsong, lipsync, CON/GP4/PKG (packages).
- [pikaxe](https://github.com/PikminGuts92/pikaxe) - Milo 引擎 Mod 工具，支持 吉他英雄1-2/80s、RB 系列、Dance Central 等，处理 DTA/GLTF/ARK（Xbox/Wii/PS3），是 Mackiloha 的延续。
- [DtxCS](https://github.com/maxton/DtxCS) - 解析 DTA/DTB（RB/GH 脚本）的 C# 库。
- [CON-Tools](https://github.com/PikminGuts92/CON-Tools) - 创建/修改/合并 RB CON，并转 Phase Shift/Wii/PS3。
- [PyMilo](https://github.com/PikminGuts92/PyMilo) - Milo 管理库（Python），含 GUI 与解包（已归档）。
- [BFForever](https://github.com/PikminGuts92/BFForever) - BandFuse 文件管理/创建库（PS3/X360），处理 RIFF/CELT。
- [Beatles Rock Band Blender plugin](https://www.moddb.com/games/rock-band/downloads/beatles-rock-band-blender-plugin) - Beatles: Rock Band 的 Blender 插件。
- [amplitools](https://github.com/PikminGuts92/amplitools) - 《Amplitude '03》工具。
- [offbeat](https://github.com/PikminGuts92/offbeat) - DDR Universe Rust 库，含 DDM→glTF。
- [praise-mod](https://github.com/PikminGuts92/praise-mod) - 《Guitar Praise》自定义内容工具，Clone Hero 歌曲→GP，支持 ogg。
- [WorshipTools](https://github.com/PikminGuts92/WorshipTools) - Jam Band 歌曲→Clone Hero（已归档）。
- [ghlcrypt](https://github.com/maxton/ghlcrypt) - 《Guitar Hero Live》C# 工具。
- [re-notes](https://github.com/PikminGuts92/re-notes) - Harmonix 游戏（DDR Universe、DJ Hero、Karaoke Revolution 等）逆向笔记与模板，含 010 模板/Python 脚本/BlitzTech/Forge/Milo 数据。

### HAL Laboratory

*Kirby, Super Smash Bros series.*

- [slippi-ssbm-asm](https://github.com/project-slippi/slippi-ssbm-asm) - SSBM Slippi 格式汇编工具。
- [rdb_tool](https://github.com/Raytwo/rdb_tool) - 以哈希语法打补丁 SSBU RDB 的工具。
- [ARCropolis](https://github.com/Raytwo/ARCropolis) - SSBU Mod 框架，基于 Skyline。
- [skyline](https://github.com/skyline-dev/skyline) - SSBU 运行时 Hook/补丁环境。
- [StudioSB](https://github.com/Ploaj/StudioSB) - SSBU 模型查看/处理 WIP 工具。
- [GekkoAssembler](https://github.com/CryZe/GekkoAssembler) - Gekko 汇编转 Action Replay/Gecko 作弊码（GC/Wii Mod）。
- [KirbyAirRideTools](https://github.com/LuigiBlood/KirbyAirRideTools) - 《卡比赛车》格式工具。
- [k64cs-project](https://github.com/shygoo/k64cs-project) - 《卡比 64》破解工具/笔记，含 Web 模型查看、DAE→几何转换、ROM/RAM 结构、调试脚本。
- [Sm4shExplorer](https://github.com/jam1garner/Sm4shExplorer) - 管理 Wii U 《任天堂明星大乱斗》文件系统。
- [smash-arc](https://github.com/jam1garner/smash-arc) - 操作 SSBU ARC 格式的库。
- [BrawlLib](https://github.com/libertyernie/brawltools) - 《任天堂明星大乱斗X》及 Wii 游戏格式库。
- [Smash-Forge](https://github.com/jam1garner/Smash-Forge) - SSB4 格式开源编辑器。
- [smash-fnv](https://github.com/jam1garner/smash-fnv) - Rust 读写 sound_volume_fighter_num_table.fnv（3DS/WiiU/SSBU）。
- [smash-sli](https://github.com/jam1garner/smash-sli) - Rust 读写 soundlabelinfo.sli（SSBU）。
- [smash-csb](https://github.com/jam1garner/smash-csb) - Rust 读写 commonsoundtable.csb（SSBU）。
- [smash-bgm-property](https://github.com/jam1garner/smash-bgm-property) - Rust 读写 bgm_property.bin（SSBU）。
- [ArcExplorer](https://github.com/ScanMountGoat/ArcExplorer) - SSBU data.arc 浏览/提取，跨平台。
- [ArcCross](https://github.com/Ploaj/ArcCross) - SSBU ARC 提取器（5.0 前 data.arc 可用，后被 ArcExplorer 取代）。
- [arc-fuse](https://github.com/jam1garner/arc-fuse) - SSBU ARC FUSE 挂载。
- [HSDLib](https://github.com/Ploaj/HSDLib) - HAL HSD 格式库（用于 Melee）。
- [MeleeMedia](https://github.com/Ploaj/MeleeMedia) - Melee 媒体提取。
- [noclip.website (Melee)](https://github.com/magcius/noclip.website/tree/main/src/SuperSmashBrosMelee) - 浏览器版 Melee 场景查看。
- [noclip.website (Super Smash Bros Brawl)](https://github.com/magcius/noclip.website/tree/main/src/rres) - 浏览器版 Brawl 查看。
- [noclip.website (SYSDOLPHIN)](https://github.com/magcius/noclip.website/tree/main/src/SYSDOLPHIN) - 浏览器版 SYSDOLPHIN 视图。
- [noclip.website (Kirby Air Ride)](https://github.com/magcius/noclip.website/tree/main/src/KirbyAirRide) - 浏览器版《卡比赛车》。
- [noclip.website (Kirby's Return to Dream Land)](https://github.com/magcius/noclip.website/tree/main/src/rres) - 浏览器版《卡比Wii 返回梦之地》。
- [RDLMINT](https://github.com/firubii/RDLMINT) - 《卡比Wii》MINT 字节码拆/装工具，支持解包/反汇编/重编译。
- [MeltyTool (Sysdolphin)](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Libraries/Sysdolphin) - Sysdolphin 查看/导出。
- [Melee DAT format](https://smashboards.com/threads/melee-dat-format.292603/) - Melee DAT 格式文档。
- [DATReaderC](https://github.com/EstevanBR/DATReaderC) - C 读取 Melee .dat。
- [ssb-decomp-re (decomp)](https://github.com/vetritheretri/ssb-decomp-re) - 《任天堂明星大乱斗》N64 匹配反编译。
- [melee (decomp)](https://github.com/doldecomp/melee) - Melee 匹配反编译。
- [brawl (decomp)](https://github.com/doldecomp/brawl) - Brawl 匹配反编译。

### Heavy Iron Studios

- [bfbb (decomp)](https://github.com/bfbbdecomp/bfbb) - 《海绵宝宝：比基尼海滩之战》匹配反编译。
- [SBMI-Decomp (decomp)](https://github.com/Juanen100/SBMI-Decomp) - 《SpongeBob Moves In!》安卓匹配反编译。
- [BFBBJSPTool](https://github.com/igorseabra4/BFBBJSPTool) - BFBB JSP 工具。
- [SpyroETDChunkTool](https://github.com/igorseabra4/SpyroETDChunkTool) - 《小龙斯派罗：龙之怒吼》区块工具。
- [IndustrialPark](https://github.com/igorseabra4/IndustrialPark) - BFBB 与 Scooby-Doo 关卡查看/编辑。
- [noclip.website (SpongeBob BFBB)](https://github.com/magcius/noclip.website/tree/main/src/HeavyIron) - 浏览器 BFBB 查看。
- [noclip.website (SpongeBob The Movie)](https://github.com/magcius/noclip.website/tree/main/src/HeavyIron) - 浏览器《海绵宝宝电影》查看。
- [noclip.website (SpongeBob ROTFD)](https://github.com/magcius/noclip.website/tree/main/src/SpongebobRevengeOfTheFlyingDutchman) - 浏览器《飞行荷兰人复仇》查看。

### Hudson Soft

*Mario Party series (Nintendo 64).*

- [bm642romtool](https://github.com/gamemasterplc/bm642romtool) - 《炸弹人64 二次攻击》ROM 压缩工具。
- [bland2digtool](https://github.com/gamemasterplc/bland2digtool) - 《炸弹人乐园2》DIG 解/打包。
- [PartyPlanner64](https://github.com/PartyPlanner64/PartyPlanner64) - N64《马力欧派对》全功能棋盘编辑/Mod 工具。
- [symbols](https://github.com/PartyPlanner64/symbols) - 《马力欧派对》逆向调试符号。
- [mpdsarchivetool](https://github.com/gamemasterplc/mpdsarchivetool) - 《马力欧派对 DS》.bin 封包解包。
- [mpromtool](https://github.com/gamemasterplc/mpromtool) - 《马力欧派对 1-3》N64 ROM 解/重建。
- [hsfview](https://github.com/Muzzarino/hsfview) - Wii《马力欧派对》模型查看器。

### Insomniac Games

- [RatchetLevelEditor](https://github.com/badger41/RatchetLevelEditor) - 《瑞奇与叮当》关卡编辑。
- [ALERT](https://github.com/Tkachov/ALERT) - Luna 引擎研究工具（Python + dat1lib + Web 资产浏览器）。
  - 游戏：日落过载、漫威蜘蛛侠（重制/迈尔斯/2）、金刚狼、瑞奇与叮当：时空裂缝。
  - 功能：模型转换 (.model/.ascii/.gltf)、应用动画、音频注入、DSAR 压缩、资产提取。
- [rivet](https://github.com/neptuwunium/rivet) - 《瑞奇与叮当：时空裂缝》格式研究。
- [ripped_apart](https://github.com/chaoticgd/ripped_apart) - 《时空裂缝》Mod 工具包。
- [insomniac-model](https://github.com/sleepyzay/insomniac-model) - Insomniac 模型格式研究与工具。
- [DDLParser](https://github.com/macton/DDLParser) - 解析 Insomniac Data Definition Language (DDL)。
- [replanetizer](https://github.com/RatchetModding/replanetizer) - PS3《瑞奇与叮当》全功能关卡编辑。
- [RaCTrilogy-PS3-Tools](https://github.com/thtrandomlurker/RaCTrilogy-PS3-Tools) - 提取 PS3 三部曲护甲/模型网格的 Python 脚本。
- [wrench](https://github.com/chaoticgd/wrench) - PS2《瑞奇与叮当》Mod 工具集。
- [horizon-forge](https://github.com/Horizon-Private-Server/horizon-forge) - PS2《瑞奇与叮当：全面反击》多人地图编辑。
- [Overstrike](https://github.com/Tkachov/Overstrike) - Insomniac PC 版的开源 Mod 管理器。

### Intelligent Systems

- [fe11-us (decomp)](https://github.com/Eebit/fe11-us) - 《火焰之纹章 新·暗黑龙与光之剑》NDS 美版匹配反编译。
- [Kid-Icarus-JSON-Parser](https://github.com/onepiecefreak3/Kid-Icarus-JSON-Parser) - 《光神话 帕尔提娜之镜》文件格式的 JSON 解析器。
- [FEAT](https://github.com/SciresM/FEAT) - 火焰纹章归档工具，可自动提取 3DS 火焰纹章封包数据。
- [FEIF_ARC](https://github.com/GovanifY/FEIF_ARC) - 《火焰纹章 if》ARC 封包解/打包工具。

#### Paper Mario 64

*See also [Fast3d/F3dex (N64)](#fast3df3dex-n64) for graphics format tools used in this game.*

- [papermario (decomp)](https://github.com/pmret/papermario) - 《纸片马里奥》N64 匹配反编译。
- [leaflitter (decomp)](https://github.com/darxoon/leaflitter) - 《纸片马里奥：贴纸星人》WIP 反编译。
- [noclip.website (PM64)](https://github.com/magcius/noclip.website/tree/main/src/PaperMario64) - 浏览器版 PM64 地图查看。
- [star-rod](https://github.com/z64a/star-rod) - PM64 Mod 工具，含地图编辑与脚本。
- [Hack64 Paper Mario](https://hack64.net/wiki/doku.php?id=paper_mario) - PM64 格式与数据结构文档。

#### Paper Mario: TTYD / Super Paper Mario

*更多格式工具见 [JSYSTEM](#jsystem-gamecubewii)。*

- [ttyd (decomp)](https://github.com/doldecomp/ttyd) - 《纸片马里奥：千年之门》匹配反编译。
- [spm-decomp (decomp)](https://github.com/seekyct/spm-decomp) - 《超级纸片马里奥》匹配反编译。
- [SpmViewer](https://github.com/follyfoxe/SpmViewer) - 查看《超级纸片马里奥》模型。
- [ttyd-utils](https://github.com/jdaster64/ttyd-utils) - TTYD Mod 工具。
- [noclip.website (TTYD)](https://github.com/magcius/noclip.website/tree/main/src/PaperMarioTTYD) - 浏览器版 TTYD 地图查看。
- [MeltyTool (TTYD)](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Games/PaperMarioTheThousandYearDoor) - TTYD 模型查看/导出。
- [PistonMiner/ttyd-tools](https://github.com/PistonMiner/ttyd-tools) - 开发工具（Blender 导出器、反汇编、REL 链接器）。
- [PaperMarioModelViewer](https://github.com/uyjulian/PaperMarioModelViewer) - 纸片马里奥系列模型查看器。
- [lzarc](https://github.com/jam1garner/lzarc) - Rust 库/CLI，解/打包《色彩喷溅》LZARC 封包。
- [CollisionSceneBinary](https://github.com/KillzXGaming/CollisionSceneBinary) - 处理纸片马里奥 csb/ctb 碰撞文件的库与工具。

### Interactive Studios

#### Glover

- [noclip.website (Glover)](https://github.com/magcius/noclip.website/tree/main/src/Glover) - 浏览器版 Glover 关卡查看器。
- [libgarib](https://github.com/naclomi/libgarib) - Glover 逆向工具与资料库。

### Illusion

*Koikatsu、Koikatsu Sunshine、Honey Select、AI Girl、PlayHome。*

- [KK-Blender-Porter-Pack](https://archive.org/details/kkbp-importer-8.0.2) - Blender 中的 Koikatsu 角色导入/导出包，几乎完美还原网格与贴图，含面部形状键、Rigify 骨架与 FBX 导出。
  - 游戏：Koikatsu、Koikatsu Sunshine。
  - 另见 [gitgoon 镜像](https://gitgoon.dev/kkbp-dev/KKBP_Importer)。
- [KKBP_Exporter](https://gitgoon.dev/kkbp-dev/KKBP_Exporter) - 游戏内 BepInEx 插件，将 Koikatsu 角色卡导出为带贴图与骨骼的 PMX 模型，供 KKBP Importer 或 MMD 使用。
- [KoikatsuModdingTools](https://gitgoon.dev/IllusionMods/KoikatsuModdingTools) - Unity 编辑器工具包，用于制作 Koikatsu Mod（服装、饰品、发型、地图、自定义着色器）；支持 AssetBundle 构建、带骨骼优化的 FBX 导入、uTinyRipper 集成。
- [ZipStudio](https://gitgoon.dev/IllusionMods/ZipStudio) - 将 Koikatsu 硬装 Mod 转为 sideloader 格式的工具，自动把列表转 CSV 并可编辑 manifest。

### Innerloop Studios

- [IGI2ModTool](https://github.com/REDxEYE/IGI2ModTool) - 《秘密潜入 2：绝密任务》文件格式 Mod 工具。

### iNiS

- [Murugo/Misc-Game-Research (Gitaroo Man)](https://github.com/Murugo/Misc-Game-Research/tree/main/PS2/Gitaroo%20Man) - PS2《吉他英雄》逆向笔记。
- [blender3d_xeios](https://github.com/boringhexi/blender3d_xeios) - Xeios 引擎游戏的 Blender 导入插件，支持《吉他英雄》(PS2) 及 まげ�?つけ�?はしーる。

### Jupiter

*《马里奥的超级绘图》（Game Boy）。*

- [MarioPicrossRipper](https://github.com/AkagitsuneYuki/MarioPicrossRipper) - 《马里奥的超级绘图》资源提取工具。
- [MeltyTool (Picross)](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Games/MariosPicross/MariosPicross) - 《马里奥的超级绘图》格式查看/导出。
- [cgrr-mariospicross](https://github.com/sopoforic/cgrr-mariospicross) - 《马里奥的超级绘图》图形提取工具。
- [MarioPicrossLoader3000](https://github.com/T0biasCZe/MarioPicrossLoader3000) - 《马里奥的超级绘图》资源加载与查看器。
- [Picross Level Data](https://www.zophar.net/fileuploads/3/21546xutra/picrossleveldata.txt) - 《马里奥的超级绘图》关卡数据技术文档。

### Jagex

*《旧版 RuneScape》/《RuneScape》。*

- [CacheModelTools](https://github.com/Bloodspawns/CacheModelTools) - 提取并查看 OSRS 缓存模型的工具。
- [OSRS-Environment-Exporter](https://github.com/ConnorDY/OSRS-Environment-Exporter) - 《旧版 RuneScape》环境/地图导出器。
- [modelviewer](https://github.com/waleedyaseen/modelviewer) - RuneScape 缓存文件模型查看器。

### Koei Tecmo

#### Fatal Frame

- [himuro (decomp)](https://github.com/mikompilation/himuro) - 《零 Zero》（PS2）匹配反编译。
- [minakami (decomp)](https://github.com/mikompilation/minakami) - 《零 ～红蝶～》（PS2）匹配反编译。

### Konami

#### Metal Gear Solid

- [Rex](https://github.com/Jayveer/Rex) - 提取 PS1《合金装备》Stage Dir 与 Dar 文件的工具。
- [libgcl](https://github.com/Jayveer/libgcl) - 逆向《合金装备 4》所用 libgcl 库的尝试，需按原样在大端架构编译。
- [MGS-KMD-Noesis](https://github.com/Jayveer/MGS-KMD-Noesis) - Noesis 插件，导入 PS1《合金装备》KMD 模型与 OAR 动画。
- [MGS2 HZX Format](https://github.com/GirianSeed/mgs2/blob/trunk/source/include/fmt_hzx.h) - 《合金装备 2》HZX（Hazard）地图导航格式文档，含巡逻路线、导航网格、触发、摄像头与空间区域。
- [MGS-MDL-Noesis](https://github.com/Jayveer/MGS-MDL-Noesis) - Noesis 插件，导入《合金装备 3》MDL 模型与 MTAR 动画。
- [DAR Archive Editor (Metal Gear Solid 2: Sons of Liberty)](https://www.moddb.com/games/metal-gear-solid-2-sons-of-liberty/downloads/dar-archive-editor) - 《合金装备 2：自由之子》DAR 封包编辑器。
- [mgs_reversing (decomp)](https://github.com/FoxdieTeam/mgs_reversing) - PSX《合金装备》匹配反编译。

#### Silent Hill

- [silent-hill-decomp (decomp)](https://github.com/Vatuu/silent-hill-decomp) - 《寂静岭》匹配反编译（PS1，美版 1.1）。
- [sh2SaveTools](https://github.com/TheMachineAmbassador/sh2SaveTools) - 《寂静岭 2》存档工具。
- [SH2Unpack](https://github.com/SamusAranX/SH2Unpack) - 《寂静岭 2》封包解包器。
- [SilentHillOrigins_PS2_AudioExtractor](https://github.com/iluny1/SilentHillOrigins_PS2_AudioExtractor) - 《寂静岭 起源》（PS2）音频提取器。
- [sh3redux](https://github.com/Palm-Studios/sh3redux) - 《寂静岭 3》封包提取与修改工具。
- [Sparagas/Silent-Hill](https://github.com/Sparagas/Silent-Hill) - 《寂静岭》文件格式逆向研究与文档。
- [Murugo/Misc-Game-Research (Silent Hill 2)](https://github.com/Murugo/Misc-Game-Research/tree/main/PS2/Silent%20Hill%202%2B3) - PS2《寂静岭 2/3》逆向笔记。
- [Silent Hill Museum](https://silenthillmuseum.org/) - 《寂静岭》系列资料站，含格式文档。
- [dreamingmoths/silent-hill-museum](https://github.com/dreamingmoths/silent-hill-museum) - Silent Hill Museum 网站仓库，含技术文档。
- [Silent-Hill-2-Enhancements](https://github.com/elishacloud/Silent-Hill-2-Enhancements) - 《寂静岭 2》(PC) 画面与音频增强项目，含构建/修改 SH2 音频（SFX/BGM/对白）的脚本。


#### Castlevania

- [Castlevania](https://github.com/Sparagas/Castlevania) - 《恶魔城》文件格式逆向文档与工具。
- [cv64 (decomp)](https://github.com/k64ret/cv64) - 《恶魔城64》匹配反编译。
- [cvaos (decomp)](https://github.com/testyourmine/cvaos) - 《恶魔城：晓月圆舞曲》匹配反编译。
- [sotn-decomp (decomp)](https://github.com/xeeynamo/sotn-decomp) - 《恶魔城X 月下夜想曲》（PSX/PSP/土星）匹配反编译。

#### Enthusia Professional Racing

- [EnthusiaVolumeFS](https://github.com/Nenkai/EnthusiaVolumeFS) - 提取 PS2《Enthusia Professional Racing》封包的工具，支持 SLPM_68519/Subaru Demo、SLPM_65948（日版）、SLUS_20967（美版）、SLES_53125（欧版）。

### Kuju London

- [PF2-BMP-Editor](https://github.com/htimsnhoj543678/PF2-BMP-Editor) - BWii《突袭战场 2》.pf2 文件编辑器。
- [Battalion-Wars-SFX-Editor](https://github.com/JasperZebra/Battalion-Wars-SFX-Editor) - 《突袭战场》音效编辑器。
- [MeltyTool (BattalionWars)](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Games/BattalionWars) - 《突袭战场》格式查看/导出。
- [battalion-level-editor](https://github.com/RenolY2/battalion-level-editor) - 《突袭战场》关卡编辑器。
- [battalion-tools](https://github.com/RenolY2/battalion-tools) - 《突袭战场》文件工具合集。
- [bw-model-viewer](https://github.com/RenolY2/bw-model-viewer) - 《突袭战场》模型查看器。
- [bwterrain-blender](https://github.com/RenolY2/bwterrain-blender) - 《突袭战场》地形 Blender 插件。
- [bw-restool](https://github.com/RenolY2/bw-restool) - 《突袭战场》资源工具。
- [bw-texture-conv](https://github.com/RenolY2/bw-texture-conv) - 《突袭战场》纹理转换工具。
- [bw-restool-GUI](https://github.com/JasperZebra/bw-restool-GUI) - 《突袭战场》统一工具，集成 restool 与纹理转换，自动识别 BW1/BW2 版本并处理 RES 解包与纹理转化。

### Larian Studios

#### Baldur's Gate 3

- [Norbyte's Baldur's Gate 3 Script Extender](https://github.com/Norbyte/bg3se) - 《博德之门 3》脚本扩展。
- [Native Mod Loader](https://www.nexusmods.com/baldursgate3/mods/944) - 《博德之门 3》原生 DLL 插件加载器。
- [BG3-DialogsBinary-Node-Editor](https://github.com/kitmods/BG3-DialogsBinary-Node-Editor) - BG3 对话二进制文件的节点式编辑器。

#### Divinity: Original Sin 2

- [DoS-2-Savegame-Editor](https://github.com/NovFR/DoS-2-Savegame-Editor) - 《神界：原罪 2》存档编辑器。
- [LSLib](https://github.com/Norbyte/lslib) - 操作《神界：原罪》和《博德之门 3》文件的工具集（含封包解压）。
- [Norbyte's Divinity Script Extender](https://github.com/Norbyte/ositools) - 《神界：原罪 2》脚本扩展工具包，为游戏脚本语言增加新功能。

### Level-5

- [dcdecomp (decomp)](https://github.com/adubbz/dcdecomp) - 《暗云》（PS2）匹配反编译。
- [Inazuma-Eleven-Toolbox](https://github.com/SwareJonge/Inazuma-Eleven-Toolbox) - 《闪电十一人》文件工具箱。
- [Metanoia](https://github.com/Ploaj/Metanoia) - Level-5 游戏的模型查看与研究工具。
- [MeltyTool (Level5)](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Libraries/Level5) - Level-5 格式查看/导出（如《暗云》《雷顿教授》）。
- [Albatross](https://github.com/Tiniifan/Albatross) - 《妖怪手表》系列编辑器，可修改妖怪阵营、技能、绝招等数据（适配 1/2/3 及 Blasters）。
- [blender-ymd-io](https://github.com/hinadevi/blender-ymd-io) - Blender 插件，反编译 .ez、转换 .ymd（Level-5 YMD 模型）。
  - 格式：.ez、.ymd（Level-5 YMD 模型格式）。
- [CfgBinEditor](https://github.com/Tiniifan/CfgBinEditor) - Level-5 Bin 编辑器。
- [EnumaLimunada](https://github.com/Tiniifan/EnumaLimunada) - 《闪电十一人 GO》模型转换器，将 IEGO CS/Galaxy 模型转回 IEGO 格式。
- [Fougere](https://github.com/Tiniifan/Fougere) - Level-5 游戏工具集。
- [GetNPCPos](https://github.com/Tiniifan/GetNPCPos) - 将小地图坐标转换为 Level-5 游戏中的 NPC 实际位置。
- [IEGOFormationEditor](https://github.com/Tiniifan/IEGOFormationEditor) - 《闪电十一人 GO》阵型编辑器，支持 GO、本纪、银河。
- [InazumaElevenGoMapenv](https://github.com/Tiniifan/InazumaElevenGoMapenv) - 《闪电十一人 GO》mapenv 文件编译/反编译。
- [InazumaElevenGoScript](https://github.com/Tiniifan/InazumaElevenGoScript) - 《闪电十一人 GO》Squirrel 脚本文档与研究，涵盖格式、事件系统、逆向笔记。
- [InazumaElevenMapEventEditor](https://github.com/Tiniifan/InazumaElevenMapEventEditor) - 《闪电十一人 GO》地图事件编辑器。
- [InazumaElevenSaveEditor](https://github.com/Tiniifan/InazumaElevenSaveEditor) - 《闪电十一人 GO》系列存档编辑器，支持 GO、本纪、银河。
- [InazumaDSEditor](https://github.com/NielsHotweels/InazumaDSEditor) - NDS《闪电十一人》1/2 ROM 编辑器，可直接修改 unitbase.dat/.STR、unitstat.dat。
- [inz_cond](https://github.com/Tiniifan/inz_cond) - Level-5 3DS 游戏条件编译/反编译，Base64 条件数据与可读 C/Squirrel 互转；支持《闪电十一人 GO》条件系统。
- [level5_material](https://github.com/Tiniifan/level5_material) - .mtr 与 .json 互转工具。
- [Level5Outline](https://github.com/Tiniifan/Level5Outline) - Level-5 outline 文件转换，.sil (XCSL) 与 JSON 互转便于编辑。
- [Level5ResourceEditor](https://github.com/Tiniifan/Level5ResourceEditor) - Level-5 资源编辑器（RES.bin）。
- [Lynx](https://github.com/Tiniifan/Lynx) - 《闪电十一人 GO 光/影》综合编辑器：基础数据、参数、商店、技能、脚本、地图与存档。
- [mini_map_converter](https://github.com/Tiniifan/mini_map_converter) - 《闪电十一人 GO》系列小地图格式转换（IEGO 与 CS/Galaxy 互转）。
- [MyTagsIE](https://github.com/Tiniifan/MyTagsIE) - CfgBinEditor 的增强标签定义，为《闪电十一人 GO》.cfg.bin 字段添加名称。
- [Nyanko](https://github.com/Tiniifan/Nyanko) - Level-5 文本编辑器。
- [Ocelot](https://github.com/Tiniifan/Ocelot) - 《闪电十一人 GO 光/影》地图事件编辑器，可视化编辑地图信息、事件、NPC、补给点。
- [Pingouin](https://github.com/Tiniifan/Pingouin) - Level-5 封档管理器。
- [projectz](https://github.com/Tiniifan/projectz) - 《闪电十一人 GO 光/影》Mod 模板/工具包，含 code.bin 修改模板、增强补丁与文档，集成 Squirrel。
- [Strikers2013Editor](https://github.com/obluda3/Strikers2013Editor) - 《闪电十一人 GO Strikers 2013》Mod/存档编辑器，可改招式与球员信息。
- [studio_eleven](https://github.com/Tiniifan/studio_eleven) - Level-5 3DS 文件格式的 Blender 插件。
  - 格式：XPRM（网格）、XPCK（封包）、XMTN（骨骼动画）、XIMA（UV 动画）、XMTM（材质动画）、XCMA（相机）。
  - 游戏：《闪电十一人 GO》系列、《妖怪手表》系列、《雷顿教授 VS 逆转裁判》。
- [StudioElevenLib](https://github.com/Tiniifan/StudioElevenLib) - Studio Eleven Blender 插件的附加 C# 库。
- [UltimateGalaxyRandomizer](https://github.com/Tiniifan/UltimateGalaxyRandomizer) - 《闪电十一人 GO 银河》随机化器，随机球员元素、位置、招式威力等。
- [ie3ogres (decomp)](https://github.com/CacaBueno64/ie3ogres) - 《闪电十一人 3 世界的挑战：魔神》NDS 匹配反编译。
- [yw-cond](https://github.com/n123git/yw-cond) - Web 版《妖怪手表》条件解析/反编译/生成工具，支持比 GO 更复杂的条件系统。
- [XtractQuery](https://github.com/onepiecefreak3/XtractQuery) - 命令行工具，反编译/重编 Level-5 3DS (.xq/.xs) 与 NDS (.cq/.lb/.gds) 脚本文件。

### Lionhead Studios (Black & White)

- [bw2-unstuff](https://github.com/openblack/bw2-unstuff) - 《黑与白 2》封包解包器。

### Macrospace

#### Fatal Force: Earth Assault

- [mff-extract](https://github.com/xNyaDev/mff-extract) - 命令行工具，解包《Fatal Force: Earth Assault》PAK 封包。
  - 格式：.pak 封包（J2ME 资源）。
  - 功能：列目录、按文件或全部解包、详细输出。

### Metropolis Software

#### Gorky 17

- [Gorky 17 *.dat and *.kdt extractor tool](https://www.moddb.com/games/gorky-17/downloads/gorky-17-dat-and-kdt-extractor-tool) - 提取《Gorky 17》*.dat 与 *.kdt 封包的工具（作者计划增加 GUI 与更多格式支持）。

### Microsoft Studios / Bungie / Turn 10

- [XbTool](https://github.com/Thealexbarney/XbTool) - Xbox 文件格式工具。
- [XbxDeTool](https://github.com/Nenkai/XbxDeTool) - Xbox 文件格式工具。

#### Halo

- [KSoft](https://github.com/KornnerStudios/KSoft) - Halo 引擎文件格式工具集。
- [ekur](https://github.com/TheHaloArchive/ekur) - Blam! 引擎（Halo）格式库与研究工具。
- [Reclaimer](https://github.com/Gravemind2401/Reclaimer) - Halo 资产提取与分析工具，支持 Halo 1/2/3/4、Reach、Online。
- [IndexV2](https://github.com/Wildenhaus/IndexV2) - 《光环：周年版》《光环 2 周年版》纹理/模型等提取工具。
- [h5_dumper](https://github.com/Surasia/h5_dumper) - Rust 编写的 Halo 5/Forge 标签导出器，递归处理 .module 输出标签。
- [HaloWarsDocs](https://github.com/HaloMods/HaloWarsDocs) - 《光环战争》1/2 Mod 文档与 010 模板。
- [XTraction - Halo 3/ODST texture extractor](https://www.moddb.com/games/halo-3/downloads/xtraction-halo-3-odst-texture-extractor-tool) - 《光环 3/ODST》纹理解包，导出 MAP 纹理为 TIFF，可编辑替换。
- [Stream Ripping Tools - Halo 3/4/ODST/CEA/HR Game Asset Extractors Converters Kit](https://www.moddb.com/games/halo-2/downloads/stream-ripping-tools-game-asset-extractors-converters-kit) - 2100 款游戏资产提取/转换工具合集，含 Halo 3/2/4/ODST/Reach 工具与文档。
- [Halo2 Gravemind Tool Extractor v1.6B](https://www.moddb.com/games/halo-2/downloads/halo2-gravemind-tool-extractor) - 《光环 2》资产（模型/音效/纹理/地图）提取器 v1.6B。
- [Bonobo [Version 1.0.0.3] Halo2/3/ODST/Reach Animation Extractor](https://www.moddb.com/games/halo-2/downloads/bonobo-version-1003) - 《光环 2/3/ODST/Reach》动画提取器 v1.0.0.3。
- [Composer Halo 4 Audio Extractor](https://www.moddb.com/games/halo-4/downloads/composer-halo-4-audio-extractor) - 配合 QuickBMS 解/转《光环 4》XMA 音频为 WAV 的工具，含所需脚本与文档。
- [3ds Max GBX Importer (Halo CE)](https://www.moddb.com/downloads/3ds-max-gbx-importer-halo-ce) - 3ds Max 插件，导入《光环：战斗进化》GBX 模型。
- [noclip.website (Halo: Combat Evolved)](https://github.com/magcius/noclip.website/tree/main/src/Halo1) - 浏览器版《光环：战斗进化》查看。
- [Halo 2 Xbox Modding Tools](https://www.moddb.com/games/halo-2/downloads/halo-2-xbox-modding-tools) - Xbox《光环 2》地图 Mod 工具合集（5 件套）。
- [Halo CE Batch Bitmap Extractor](https://www.moddb.com/downloads/halo-ce-batch-bitmap-extractor) - 《光环：战斗进化》批量位图提取器。

#### Destiny

- [alkahest](https://github.com/cohaereo/alkahest) - 《命运 2》资产查看多功能工具，着重还原渲染效果，支持 Tiger 引擎格式。
- [tiger-pkg](https://github.com/v4nguard/tiger-pkg) - 《命运》1/2 PKG 库与工具（解包/校验），支持 Destiny1 Alpha/TKK/RoI、Destiny2 Beta–Edge of Fate 及《Marathon》，覆盖 PS3/PS4/X360/XONE/Windows。
- [quicktag](https://github.com/v4nguard/quicktag) - 《命运》1/2 Tiger 结构扫描器，浏览标签/本地化与原始字符串、纹理与 Wwise 预览。
- [Charm](https://github.com/cohaereo/Charm) - 《命运 2》资产提取逆向工具，支持多版本 Tiger 与 Destiny 2（暗影要塞 至 Lightfall），用于艺术与保存。
- [d2-map-importer-addon](https://github.com/DeltaDesigns/d2-map-importer-addon) - Blender 4.0+ 插件，导入 Charm 抓取的 Destiny 2 地图，组装静态/动态/光照/地形并自动赋予装备着色器与贴图，兼容 DARE/DCG 骨架与 IK 玩家骨骼。
- [Destiny-Collada-Generator](https://github.com/DeltaDesigns/Destiny-Collada-Generator) - 通过官方 API 生成 Destiny 2 物品 Collada 的工具，导出几何、权重、UV、法线、切线、顶点色、染色槽及 PNG 纹理、着色器参数。
- [SBox-Destiny-2-Map-Importer](https://github.com/DeltaDesigns/SBox-Destiny-2-Map-Importer) - 将 Charm 抓取的 Destiny 2 地图导入 S&Box Hammer，包含材质/着色器/模型。
- [MIDA](https://github.com/DeltaDesigns/MIDA) - 面向《Marathon》的 Charm 分支，提取 Marathon 封包（目前大多功能不可用，状态不确定）。
- [destinydocs](https://github.com/cohaereo/destinydocs) - 《命运》1/2 内部文档。
- [DestinyDocs](https://github.com/MontagueM/DestinyDocs) - 《命运》文件文档（重点涵盖 Destiny 2 新版本），含 Charm Wiki、引擎概览、标签格式。
- [D2StaticDocs](https://github.com/nblockbuster/D2StaticDocs) - 《命运 2：凌光之刻》静态模型格式文档，覆盖主文件/子文件/材质表/关卡加载区。
- [destinypkgtool](https://github.com/v4nguard/destinypkgtool) - Rust 版 Destiny 1 PKG 库与工具（解包/校验）。
- [ddkf](https://github.com/v4nguard/ddkf) - Destiny 解密密钥查找器。
- [DestinyUnpackerCPP](https://github.com/nblockbuster/DestinyUnpackerCPP) - Destiny 1（PS4/PS3/X360）与 Destiny 2 PC 封包 C++ 解包器，支持 WEM 转换、TXTP 生成、十六进制命名、仅音乐提取。
- [destiny-unpacker-rs](https://github.com/nblockbuster/destiny-unpacker-rs) - Rust 版 Destiny 解包器（存档）。
- [D2StaticExtractor](https://github.com/nblockbuster/D2StaticExtractor) - Destiny 2 静态模型→FBX 提取器（凌光之刻及以后，已被 Charm 取代但仍可特定用途，存档）。
- [D2TextureRipper](https://github.com/nblockbuster/D2TextureRipper) - Destiny 2 批量纹理/图片提取器，支持 1.0.0.1 至 4.0.0.1（巫毒女王），含批处理。
- [MontevenDynamicExtractor](https://github.com/nblockbuster/MontevenDynamicExtractor) - MDE 分支，提取 Destiny 2 动态模型为 FBX，含纹理/骨骼/权重/批处理。
- [Destiny-API-Ripper-Extension](https://github.com/nblockbuster/Destiny-API-Ripper-Extension) - Destiny Collada Generator 与 Monteven Dynamic Extractor 的扩展与 GUI，自动化 API 抽取 Destiny 2 资产。
- [Destiny-Collada-Generator](https://github.com/nblockbuster/Destiny-Collada-Generator) - Collada 生成工具的另一个维护分支（DeltaDesigns 版本见上），导出 Destiny 2 物品几何/权重/UV/贴图等。
- [DestinyOSTListGen](https://github.com/nblockbuster/DestinyOSTListGen) - 生成 Destiny 音乐 GinsorID 列表（OSTs.db）的工具，利用 WwiseParser 解析音频包，支持差异比较与 SFX 过滤。
- [DestinyWwiseParserScript](https://github.com/nblockbuster/DestinyWwiseParserScript) - 针对 Destiny 1/2 的 WwiseParser JSON 生成/解析脚本，支持自动 WAV 导出与版本切换（D1/pre-BL）。
- [bungie-lua-decompiler](https://github.com/nblockbuster/bungie-lua-decompiler) - Tool to decompile Bungie's Lua scripts found in the Destiny 1 Alpha with format 14.

#### Gears of War

- [Gears of War Map Cooker Tool for Newbies](https://www.moddb.com/mods/gears-multiplayer-enhancement-mod/downloads/gears-of-war-map-cooker-tool-for-newbies) - .NET 工具，简化《战争机器》H.I.V.E 模式与多人增强 Mod 的地图打包。

#### Forza

- [ForzaTech-extraction-tools](https://github.com/Doliman100/ForzaTech-extraction-tools) - ForzaTech .carbin/.modelbin 结构文档与工具。

#### Age of Empires

- [Audio Modding Guide (AoE2DE)](https://steamcommunity.com/sharedfiles/filedetails/?id=1915891079) - 《帝国时代 II:DE》音频 Mod 全教程。
  - 主题：触发器、音效替换、音乐/语音/嘲讽、用 Wwise 编辑数据文件。
  - 工具：Ravioli Tools、vgmstream、Advanced Genie Editor。
- [halo (decomp)](https://github.com/halo-re/halo) - 《光环：战斗进化》（Xbox）匹配反编译。

### Mobius Digital (Outer Wilds)

- [noclip.website (Outer Wilds)](https://github.com/magcius/noclip.website/tree/main/src/OuterWilds) - 浏览器版《Outer Wilds》查看器。

### Midway

- [revenge (decomp)](https://github.com/svinsmoke212/revenge) - 《WCW/nWo Revenge》（N64）匹配反编译。

#### Area 51

- [engine-51](https://github.com/bigianb/engine-51) - 《51 区》（2005）引擎实验性工具。

#### Gauntlet

- [gdl-tools (haekb)](https://github.com/haekb/gdl-tools) - 《战斧：黑暗遗产》文件工具集。
- [gdl_wad_decoder](https://github.com/haekb/gdl_wad_decoder) - 《战斧：黑暗遗产》WAD 封包解码。
- [gdl_vbnk_decoder](https://github.com/haekb/gdl_vbnk_decoder) - 《战斧：黑暗遗产》语音包解码。
- [gl_rom_decoder](https://github.com/haekb/gl_rom_decoder) - 《战斧传奇》ROM 解码。
- [io_scene_gdl](https://github.com/haekb/io_scene_gdl) - 《战斧：黑暗遗产》场景格式 Blender 插件。
- [gdl_tools (MosesofEgypt)](https://github.com/MosesofEgypt/gdl_tools) - 《战斧：黑暗遗产》另一套工具集。
- [MeltyTool (Gauntlet)](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Games/GauntletDarkLegacy) - 《战斧：黑暗遗产》格式查看/导出。

#### NFL Blitz

- [NFL-Blitz-File-Editor](https://github.com/thompjake/NFL-Blitz-File-Editor) - 《NFL Blitz》数据文件编辑器。
- [NFL-Blitz-Play-Maker](https://github.com/thompjake/NFL-Blitz-Play-Maker) - 《NFL Blitz》战术本编辑器。
- [NFL_Blitz_Roster_Manager](https://github.com/thompjake/NFL_Blitz_Roster_Manager) - 《NFL Blitz》名单管理工具。
- [NFLBlitzDataEditor.Core](https://github.com/thompjake/NFLBlitzDataEditor.Core) - 《NFL Blitz》数据编辑核心库。

### Monolith Productions

#### F.E.A.R

- [F.E.A.R. 3dsmax 7 model import plugin](https://www.moddb.com/games/fear/downloads/3dsmax-7-model-import-plugin)
- [F.E.A.R. 2 unofficial extraction tools](https://www.moddb.com/games/fear-2/downloads/fear-2-unofficial-extraction-tools) - 非官方《F.E.A.R. 2》封包/纹理/音频提取工具。
- [Fear2Tools](https://github.com/Nenkai/Fear2Tools) - 《F.E.A.R 2 起源》LTArchive 解/打包与数据库编辑器。
- [FEAR Online 3dsmax script (F.E.A.R. 2)](https://www.moddb.com/games/fear-2/downloads/fear-online-3dsmax-script)
- [Video Tutorial: 3DSMax Plugin (F.E.A.R.)](https://www.moddb.com/games/fear/downloads/video-tutorial-3dsmax-plugin)
- [FEAR Database Extractor](https://www.moddb.com/games/fear/downloads/fear-database-extractor)
- [FEAR Public Tools v2](https://www.moddb.com/games/fear/downloads/fear-public-tools-v2) - FEAR SDK v2，可在 Steam 版制作单人关卡。
- [FEAR Tweaking Tool and Guide](https://www.moddb.com/games/fear/downloads/fear-tweaking-tool-and-guide) - 提高帧率的调整工具与指南。
- [ltar](https://github.com/cmbasnett/ltar) - Lithtech Jupiter 引擎 LTAR 封包 Python CLI。
- [Lithtech Jupiter Ex FX Decompiler (F.E.A.R.)](https://www.moddb.com/games/fear/downloads/lithtech-jupiter-ex-fx-decompiler)

#### Trespasser

- [Blender 2.6 Trespasser Exporter](https://www.moddb.com/games/trespasser/downloads/blender-26-trespasser-exporter-10) - 适配 Blender 2.6 的《Trespasser》模型导出脚本，输出 TPM 与 values.txt，并提供 UI 配置与基础网格参数。
- [Blender3D Trespasser Exporter 1.0](https://www.moddb.com/games/trespasser/downloads/blender3d-trespasser-exporter-10) - Blender 脚本，导出《Trespasser》模型，写出 TPM 和 values.txt，支持网格类型过滤 (v1.0)。

#### Blood

- [BLOOD ULTIMATE BUNDLE TOOLS KIT](https://www.moddb.com/mods/blood-modern-voxels-pak-for-mappers-and-moders/downloads/blood-ultimate-bundle-tools-kit) - 《Blood》Mod/全转换全套编辑器合集。
- [BLOOD UNOFFICIAL TOOLS](https://www.moddb.com/games/blood/downloads/blood-unofficial-tools) - 《Blood》非官方工具包，含 DOS 版 Mapedit/EditArt/ArEdit 文档。
- [Spill Some: The Blood Tool](https://www.moddb.com/games/blood/downloads/spill-some-the-blood-tool) - DOS/DOSBox 下运行的《Blood/隐秘通道》启动与演示工具，可自动重命名默认 demo 播放用户录制。

#### Blood 2: The Chosen

- [Updated 3dsmax plugin (Blood 2: The Chosen)](https://www.moddb.com/games/blood-2-the-chosen/downloads/updated-3dsmax-plugin) - 《Blood 2》/《Shogo》更新版 3ds Max 插件（来自 Monolith 旧 FTP）。
- [Blood 2 Modding tools](https://www.moddb.com/games/blood-2-the-chosen/downloads/blood-2-modding-tools) - 《Blood 2》完整 Mod 工具包，含 ABC 导出器等。
- [Blood 2 Toolset 64 bit fix](https://www.moddb.com/games/blood-2-the-chosen/downloads/blood-2-toolset-64-bit-fix) - 《Blood 2》工具集 64 位修复版（原安装器不支持 64 位 Windows）。
- [Milkshape ABC Plugin (Blood 2: The Chosen)](https://www.moddb.com/games/blood-2-the-chosen/downloads/milkshape-abc-plugin) - 《Blood 2》Milkshape ABC 导入/导出插件。

#### No One Lives Forever

- [Lithtech Jupiter Maya/3dsmax plugins (No One Lives Forever 2)](https://www.moddb.com/games/no-one-lives-forever-2-a-spy-in-harm/downloads/lithtech-jupiter-maya3dsmax-plugins) - Lithtech Jupiter 模型/关卡导入导出插件合集（3DS Max 3-7，Maya 4-7）。
- [Lithtech 2.2 toolset (No One Lives Forever)](https://www.moddb.com/games/no-one-lives-forever/downloads/lithtech-22-toolset) - Lithtech 2.0 工具的增强版（v2.2），含 .lta 支持与按键重绑定。
- [NOLF Tools (No One Lives Forever)](https://www.moddb.com/games/no-one-lives-forever/downloads/nolf-tools) - 《No One Lives Forever》官方 Mod 工具。
- [No One Lives Forever 2 Toolkit](https://www.moddb.com/games/no-one-lives-forever-2-a-spy-in-harm/downloads/no-one-lives-forever-2-toolkit) - 《NOLF 2》完整工具包，含编辑器与源码（按原样提供，无官方支持）。

#### Shogo: Mobile Armor Division

- [Shogo Mobile Armor Division Modding Tools](https://www.moddb.com/games/shogo-mobile-armor-division/downloads/shogo-mobile-armor-division-modding-tools) - 《Shogo》Mod 工具，含源码中使用的 API 帮助。
- [Shogo tools 64 bit](https://www.moddb.com/games/shogo-mobile-armor-division/downloads/shogo-tools-64-bit) - 《Shogo》64 位兼容 SDK 文件（官方安装器仅支持 16/32 位，这里提供解压版本）。

#### Serious Sam

- [SeriousSaveEditor](https://github.com/widberg/SeriousSaveEditor) - 《英雄萨姆》系列存档编辑器。

### Monolith Soft

*Japanese studio (distinct from Monolith Productions, USA).*

#### Xenoblade Chronicles

- [xenoblade (decomp)](https://github.com/xbret/xenoblade) - 《异度神剑》（Wii，日版）匹配反编译。
- [XenoTools](https://github.com/Nenkai/XenoTools) - 《异度神剑》文件格式工具。
- [bdat-rs](https://github.com/roccodev/bdat-rs) - Rust 库，读写《异度神剑》系列数据表 BDAT 格式。
- [xcnx-file-loader](https://github.com/roccodev/xcnx-file-loader) - 让 Switch《异度神剑》直接从 RomFS 读取自定义文件而非 ARD 封包的替换 Mod。
- [ard-tools](https://github.com/roccodev/ard-tools) - 处理 Switch《异度神剑》ARD/ARH 封包的工具集，含 ardain 库、CLI、FUSE 驱动 fuse-ard。

### Oddworld Inhabitants

- [Asset Tool (Oddworld: Abe's Exoddus)](https://www.moddb.com/games/oddworld-abes-exoddus/downloads/asset-tool) - 将《奇异世界：阿比逃亡记》过场转 MP4，并预览/导出《阿比大冒险》《阿比逃亡记》精灵的工具（需关卡文件与 ffmpeg）。
- [Sprite / CAM Extractor (Oddworld: Abe's Exoddus)](https://www.moddb.com/games/oddworld-abes-exoddus/downloads/sprite-cam-extractor) - 将 PC 版《阿比逃亡记/大冒险》的 cam 文件转换的工具。

### Naughty Dog

#### Crash Bandicoot 1-3 & CTR

- [ReBandicoot](https://github.com/kohtep/ReBandicoot) - 《古惑狼》逆向工具。
- [Crash-Bandicoot-Resources](https://github.com/Helias/Crash-Bandicoot-Resources) - 《古惑狼》文件格式与逆向资源大全，涵盖三部曲重制、Twinsanity、CTR、Crash Bash 及 PS1 原作，含 PAK/IGZ/NSD/NSF 文档、30+ 专用工具与 Mod/反编译框架。
- [CTR-tools](https://github.com/CTR-tools/CTR-tools) - PS1《古惑狼赛车》文件格式工具集。
- [CrashEdit](https://github.com/cbhacks/CrashEdit) - PS1《古惑狼》关卡与图形编辑器。
- [drnsf](https://github.com/cbhacks/drnsf) - 顽皮狗游戏（含古惑狼）格式研究工具。
- [crash-bandicoot-nsf](https://github.com/dehodson/crash-bandicoot-nsf) - 《古惑狼》NSF（Naughty Dog Streaming File）工具。
- [Crash-Bandicoot-2-Modelexport](https://github.com/warenhuis/Crash-Bandicoot-2-Modelexport) - 《古惑狼 2》模型导出。
- [crashutils](https://github.com/wurlyfox/crashutils) - 《古惑狼》格式工具合集。
- [noclip.website (Crash Bandicoot: Warped)](https://github.com/magcius/noclip.website/tree/main/src/CrashWarped) - 浏览器版《古惑狼 3》查看。
- [c2c (decomp)](https://github.com/ughman/c2c) - 《古惑狼 2：皮质博士的逆袭》匹配反编译。
- [crash-ps2 (decomp)](https://github.com/calmsacibis995/crash-ps2) - 《古惑狼：狂扁猴子》（PS2）匹配反编译。

#### Spyro the Dragon

- [spyroedit](https://github.com/LXShades/spyroedit) - PS1《小龙斯派罗》模拟器插件，可在 ePSXe/PCSX 等上修改关卡贴图/色调、天空、物体属性与场景位置。
- [spyro-1 (decomp)](https://github.com/TheMobyCollective/spyro-1) - 《小龙斯派罗》匹配反编译。

#### Jak and Daxter

- [jak1-vag-splitter](https://github.com/blahpy/jak1-vag-splitter) - 《杰克与达斯特 1》VAG 音频拆分工具。
- [JakAndDaxter1Sound](https://github.com/efimandreev0/JakAndDaxter1Sound) - 《杰克与达斯特 1》音频提取/播放工具。
- [Blender-Script-JaD-Actors](https://github.com/innocentmiau/Blender-Script-JaD-Actors) - 导入《杰克与达斯特》角色模型的 Blender 脚本。
- [JakAudioTools](https://github.com/jwetzell/JakAudioTools) - 《杰克与达斯特》系列音频提取/转换工具。
- [JakAudioTool](https://github.com/LuminarLight/JakAudioTool) - 《杰克与达斯特》音频 GUI 工具。
- [CTR-ModSDK (decomp)](https://github.com/CTR-tools/CTR-ModSDK) - 《古惑狼赛车》（PS1）匹配反编译。

### NanaOn-Sha

- [parappa2 (decomp)](https://github.com/parappadev/parappa2) - 《啪啦啪啦啪 2》（PS2）匹配反编译。
- [open-ribbon (decomp)](https://github.com/open-ribbon/open-ribbon) - 《振动节奏带》（PS1, PAL）匹配反编译。
- [Murugo/Misc-Game-Research (Vib-Ribbon)](https://github.com/Murugo/Misc-Game-Research/tree/main/PS1/Vib-Ribbon) - PS1《振动节奏带》逆向笔记。

### Nintendo EAD

*任天堂第一方作品，GC/Wii 时代大量使用 [JSYSTEM](#jsystem-gamecubewii) 中间件。*

#### Animal Crossing

*更多格式工具见 [JSYSTEM](#jsystem-gamecubewii)。*

- [010Editor-AnimalCrossing-Templates](https://github.com/Cuyler36/010Editor-AnimalCrossing-Templates) - 《动物之森》010 Editor 二进制模板。
- [AC-Audiobank-Dumper](https://github.com/Cuyler36/AC-Audiobank-Dumper/tree/main/AC%20Audiobank%20Dumper) - 《动物之森》音频库提取器。
- [ACNESCreator](https://github.com/Cuyler36/ACNESCreator) - 《动物之森》NES ROM 编辑器。
- [LibACNH](https://github.com/Slattz/LibACNH) - C++ 库，解析《集合啦！动物森友会》文件格式与算法。
- [ACSE](https://github.com/Cuyler36/ACSE) - NGC《动物之森》存档编辑器。
- [Animal-Crossing-Model-Editor](https://github.com/Cuyler36/Animal-Crossing-Model-Editor) - 《动物之森》3D 模型编辑器。
- [Animal-Crossing-Texture-Editor](https://github.com/Cuyler36/Animal-Crossing-Texture-Editor) - 《动物之森》纹理编辑工具。
- [Cross-View](https://github.com/Cuyler36/Cross-View) - 《动物之森》模型查看器。
- [RELDumper](https://github.com/Cuyler36/RELDumper) - 《动物之森》REL 文件导出工具。
- [af (decomp)](https://github.com/zeldaret/af) - 《动物森林》匹配反编译。
- [ac-decomp (decomp)](https://github.com/acreteam/ac-decomp) - 《动物之森》（NGC）匹配反编译。
- [afe-decomp (decomp)](https://github.com/acreteam/afe-decomp) - 《动物之森 e+》（日版）匹配反编译。

#### AST

*任天堂多款游戏使用的 PCM 音频格式。*

- [Nintendo-AST-Creator](https://github.com/gheskett/Nintendo-AST-Creator) - 任天堂 AST 音频文件生成器。
- [ast_to_wav](https://github.com/jdflyer/ast_to_wav) - AST→WAV 转换器。
- [MeltyTool (AST)](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Formats/Ast) - AST 音频查看/转换。
- [jatast](https://github.com/XAYRGA/jatast) - JAudio AST 格式工具。

#### Luigi's Mansion

*更多格式工具见 [JSYSTEM](#jsystem-gamecubewii)。*

- [Luigis-Mansion-Blender-Toolkit](https://github.com/Astral-C/Luigis-Mansion-Blender-Toolkit) - 《路易吉洋馆》模型 Blender 工具包。
- [Dolhouse](https://github.com/opeyx/Dolhouse) - NGC《路易吉洋馆》关卡编辑器。
- [Booldozer](https://github.com/Sage-of-Mirrors/Booldozer) - 《路易吉洋馆》碰撞编辑器。
- [LuigisMansion_Ghidra_NTSC](https://github.com/Sage-of-Mirrors/LuigisMansion_Ghidra_NTSC) - NGC《路易吉洋馆》NTSC-U 版 Ghidra 工程。
- [SuperLM](https://github.com/Sage-of-Mirrors/SuperLM) - 处理《路易吉洋馆》BIN/MP 格式的库。
- [noclip.website (Luigi's Mansion)](https://github.com/magcius/noclip.website/tree/main/src/LuigisMansion) - 浏览器版《路易吉洋馆》查看。

#### Pikmin

*更多工具见 [JSYSTEM](#jsystem-gamecubewii)。*

- [pikmin (decomp)](https://github.com/projectPiki/pikmin) - 《皮克敏》匹配反编译。
- [pik2wii (decomp)](https://github.com/projectPiki/pik2wii) - 《皮克敏 2 新游玩控制》（Wii 美版）匹配反编译。
- [pikmin2 (decomp)](https://github.com/projectPiki/pikmin2) - 《皮克敏 2》（NGC 美版）匹配反编译。
- [MODConv](https://github.com/intns/MODConv) - 《皮克敏 1》MOD 模型格式转换。
- [Pikmin1Toolset](https://github.com/NerduMiner/Pikmin1Toolset) - 《皮克敏 1》Mod 工具合集，含 mod2obj。
- [PikBinGen](https://github.com/RenolY2/PikBinGen) - 自定义《皮克敏》关卡的二进制生成器。
- [MeltyTool (Pikmin1)](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Games/Pikmin1) - 《皮克敏 1》格式查看/导出。
- [piki-tools](https://github.com/Minty-Meeo/piki-tools) - 《皮克敏》文件格式工具合集。

#### Pikmin 2

*更多《皮克敏 2》工具见 [JSYSTEM](#jsystem-gamecubewii)。*

- [PikminEnemyParms](https://github.com/AntonioAntonio-ai/PikminEnemyParms) - 《皮克敏 2》敌人参数 GUI 编辑器。
- [MeltyTool (Pikmin2)](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Games/Pikmin2) - 《皮克敏 2》格式查看/导出。
- [Pikmin-2-Symbol-Maps](https://github.com/Minty-Meeo/Pikmin-2-Symbol-Maps) - 《皮克敏 2》逆向用调试符号表。
- [pikmin-tools](https://github.com/RenolY2/pikmin-tools) - 《皮克敏 2》文件工具合集。
- [noclip.website (Pikmin 2)](https://github.com/magcius/noclip.website/tree/main/src/j3d) - 浏览器版《皮克敏 2》查看。

#### Mario Artist

*《马力欧艺术家》系列（N64DD 磁碟机）。*

- [leotools](https://github.com/jkbenaim/leotools) - 64DD 磁盘镜像提取与处理工具。
- [leo64dd_python](https://github.com/LuigiBlood/leo64dd_python) - Python 版 64DD 磁盘操作工具。
- [mfs_manager](https://github.com/LuigiBlood/mfs_manager) - 64DD MFS（Multi File System）管理器。
- [MeltyTool (MarioArtist)](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Games/MarioArtist) - 《马力欧艺术家》格式查看/导出。
- [ma3d1toOBJ](https://github.com/LuigiBlood/ma3d1toOBJ) - Mario Artist Polygon Studio 模型转 OBJ。

#### Mario Kart: Double Dash

*更多见 [JSYSTEM](#jsystem-gamecubewii)。*

- [MeltyTool (MarioKartDoubleDash)](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Games/MarioKartDoubleDash) - 《马里奥赛车 双刃》格式查看/导出。
- [mkdd-collision](https://github.com/RenolY2/mkdd-collision) - 《双刃》碰撞数据查看/编辑。
- [mkdd-track-editor](https://github.com/RenolY2/mkdd-track-editor) - 《双刃》全功能赛道编辑器。
- [DouBOL-Dash](https://github.com/shibbo/DouBOL-Dash) - 《双刃》BOL 赛道布局编辑工具。
- [noclip.website (Mario Kart: Double Dash)](https://github.com/magcius/noclip.website/tree/main/src/j3d) - 浏览器版《马里奥赛车 双刃》查看。
- [mkdd (decomp)](https://github.com/doldecomp/mkdd) - 《马里奥赛车 双刃》匹配反编译。

#### Super Mario 64

*更多见 [Fast3d/F3dex](#fast3df3dex-n64)。*

- [Quad64](https://github.com/DavidSM64/Quad64) - 《超级马里奥 64》关卡编辑器。
- [MeltyTool (SuperMario64)](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Games/SuperMario64) - 《超级马里奥 64》格式查看/导出。
- [SM64Paint](https://github.com/Trenavix/SM64Paint) - 《超级马里奥 64》纹理编辑器。
- [Hack64 Super Mario 64](https://hack64.net/wiki/doku.php?id=super_mario_64) - 《超马 64》格式文档。
- [sm64 (decomp)](https://github.com/n64decomp/sm64) - 《超级马里奥 64》匹配反编译。

#### Super Mario 64 DS

- [SM64DSe](https://github.com/Arisotura/SM64DSe) - 《超马 64 DS》关卡编辑器。
- [SM64DSe-Ultimate](https://github.com/Gota7/SM64DSe-Ultimate) - SM64DSe 增强版。
- [noclip.website (SM64DS)](https://github.com/magcius/noclip.website/tree/main/src/SuperMario64DS) - 浏览器版《超马 64 DS》查看。
- [MeltyTool (SuperMario64Ds)](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Games/SuperMario64Ds) - 《超马 64 DS》格式查看/导出。

#### Super Mario (Other)

*《阳光》《银河》等更多见 [JSYSTEM](#jsystem-gamecubewii)。*

- [bba-wd (decomp)](https://github.com/vabold/bba-wd) - 《脑锻炼 Wii Degree》匹配反编译。
- [bodyharvestdecomp (decomp)](https://github.com/deltaniumindustries/bodyharvestdecomp) - 《收获日》（N64）匹配反编译。
- [chameleontwistv1.0-jp (decomp)](https://github.com/chameleontwistret/chameleontwistv1.0-jp) - 《变色龙历险》（N64，日版）匹配反编译。
- [doshin-gc (decomp)](https://github.com/break-core/doshin-gc) - 《大头菜巨人》（NGC）匹配反编译。
- [pcopter_wii (decomp)](https://github.com/Bsquo/pcopter_wii) - 《无线电直升机》（Wii）匹配反编译。
- [KinokoDecomp-S (decomp)](https://github.com/Moddimation/KinokoDecomp-S) - 《奇诺比奥队长：宝藏追踪》Switch 版匹配反编译。
- [drmario64 (decomp)](https://github.com/angheloalf/drmario64) - 《马里奥医生 64》匹配反编译。
- [mariogolf64 (decomp)](https://github.com/monde-lointain/mariogolf64) - 《马里奥高尔夫》（N64）匹配反编译。
- [mk64 (decomp)](https://github.com/n64decomp/mk64) - 《马里奥赛车 64》匹配反编译。
- [mkds-re (decomp)](https://github.com/XorTroll/mkds-re) - 《马里奥赛车 DS》（欧版）逆向工程。
- [mkw (decomp)](https://github.com/snailspeed3/mkw) - 《马里奥赛车 Wii》匹配反编译。
- [marioparty (decomp)](https://github.com/mariopartyrd/marioparty) - 《马里奥派对》匹配反编译。
- [marioparty2 (decomp)](https://github.com/mariopartyrd/marioparty2) - 《马里奥派对 2》匹配反编译。
- [marioparty3 (decomp)](https://github.com/mariopartyrd/marioparty3) - 《马里奥派对 3》匹配反编译。
- [marioparty4 (decomp)](https://github.com/mariopartyrd/marioparty4) - 《马里奥派对 4》匹配反编译。
- [red-pro2 (decomp)](https://github.com/aboood40091/red-pro2) - 《新超级马里奥兄弟 U》v1.3.0（美版）匹配反编译。
- [OdysseyDecomp (decomp)](https://github.com/MonsterDruide1/OdysseyDecomp) - 《超级马里奥 奥德赛》全版本匹配反编译。
- [smstrikers-decomp (decomp)](https://github.com/yannicksuter/smstrikers-decomp) - 《超级马里奥足球》匹配反编译。
- [sms (decomp)](https://github.com/doldecomp/sms) - 《超级马里奥 阳光》匹配反编译。
- [smb-tools](https://github.com/PistonMiner/smb-tools) - 《超级马里奥兄弟》文件格式工具。
- [smstools](https://github.com/impiaaa/smstools) - 《超级马里奥 阳光》数据解码工具集。
- [Bin-editor-improvements](https://github.com/Muzzarino/Bin-editor-improvements) - 改进版《阳光》BIN 编辑器，修复正交模式并添加复制/平移/细分按钮，改进 UI，附摄像机引导编辑（WIP）。
- [Corona](https://github.com/shibbo/Corona) - 为《超级马里奥 阳光》设计的 C++ 代码注入工具包，可添加新敌人/物体/Boss/物品等。
- [flaaffy](https://github.com/arookas/flaaffy) - 《阳光》音频工具链，含运行时库与转换/制作工具。
- [Track-Studio](https://github.com/MapStudioProject/Track-Studio) - 《马里奥赛车 8》全功能赛道/路线编辑器。
- [CTR-Studio](https://github.com/MapStudioProject/CTR-Studio) - 3DS BCH/BCRES（《马里奥赛车 7》等）编辑器。
- [noclip.website (Super Mario Sunshine)](https://github.com/magcius/noclip.website/tree/main/src/j3d) - 浏览器版《超级马里奥 阳光》查看。
- [noclip.website (Super Mario Galaxy)](https://github.com/magcius/noclip.website/tree/main/src/SuperMarioGalaxy) - 浏览器版《超级马里奥 银河》查看。
- [noclip.website (Super Mario Galaxy 2)](https://github.com/magcius/noclip.website/tree/main/src/SuperMarioGalaxy) - 浏览器版《超级马里奥 银河 2》查看。
- [noclip.website (Mario Kart 64)](https://github.com/magcius/noclip.website/tree/main/src/MarioKart64) - 浏览器版《马里奥赛车 64》查看。
- [noclip.website (Mario Kart DS)](https://github.com/magcius/noclip.website/tree/main/src/nns_g3d) - 浏览器版《马里奥赛车 DS》查看。
- [noclip.website (Mario Kart Wii)](https://github.com/magcius/noclip.website/tree/main/src/MarioKartWii) - 浏览器版《马里奥赛车 Wii》查看。
- [noclip.website (Mario Kart 8 Deluxe)](https://github.com/magcius/noclip.website/tree/main/src/MarioKart8Deluxe) - 浏览器版《马里奥赛车 8 豪华版》查看。
- [ToadsTool](https://github.com/huderlem/ToadsTool) - 《马里奥高尔夫：蘑菇球场》文件编辑器（地图容器、文本、事件、区域、实体、遭遇）。
- [GSTExtract](https://github.com/shibbo/GSTExtract) - 解出《超级马里奥 银河》1/2 的 .gst 数据。
- [bea-extract](https://github.com/shibbo/bea-extract) - 提取《超级马里奥派对》BEA 文件。
- [M-LTool](https://github.com/efimandreev0/M-LTool) - 《马里奥与路易吉 RPG2/3》（NDS）封包解包工具。

#### New Super Mario Bros Wii

- [NSMBW-Decomp (decomp)](https://github.com/NSMBW-Community/NSMBW-Decomp) - 《新超级马里奥兄弟 Wii》匹配反编译。
- [BerryBush](https://github.com/hayden0729/berrybush) - 侧重 BRRES 导入/导出的 Blender 插件。
  - 游戏：《新超级马里奥兄弟 Wii》（BRRES 资产含角色/关卡/道具）。
  - 特性：BRRES 进/出、渲染引擎、材质编辑界面、导出前格式校验。

#### Zelda

*《风之杖》《黄昏公主》等更多见 [JSYSTEM](#jsystem-gamecubewii)。*

- [CloudModding OoT Wiki](https://wiki.cloudmodding.com/oot/Main_Page) - 《时之笛》技术 Wiki（331+ 文章，涵盖演员/物体/场景/格式/动画/音频/碰撞/反编译/Mod 指南）。
- [WindEditor](https://github.com/Sage-of-Mirrors/WindEditor) - 《塞尔达传说：风之杖》地图查看/编辑器。
- [bfntoolkit](https://github.com/NerduMiner/bfntoolkit) - 提取/重打包《风之杖》(NGC) BFN 字库，生成 PNG+JSON（重打包需另备 BTI 转换工具）。
- [noclip.website (Ocarina of Time)](https://github.com/magcius/noclip.website/tree/main/src/zelview) - 浏览器版《时之笛》查看。
- [noclip.website (Ocarina of Time Beta)](https://github.com/magcius/noclip.website/tree/main/src/zelview) - 浏览器版《时之笛》Beta 查看。
- [noclip.website (Majora's Mask 3D)](https://github.com/magcius/noclip.website/tree/main/src/OcarinaOfTime3D) - 浏览器版《穆修拉的假面 3D》查看。
- [noclip.website (Wind Waker)](https://github.com/magcius/noclip.website/tree/main/src/ZeldaWindWaker) - 浏览器版《风之杖》查看。
- [noclip.website (Twilight Princess)](https://github.com/magcius/noclip.website/tree/main/src/ZeldaTwilightPrincess) - 浏览器版《黄昏公主》查看。
- [noclip.website (Skyward Sword)](https://github.com/magcius/noclip.website/tree/main/src/ZeldaSkywardSword) - 浏览器版《天空之剑》查看。
- [EventWaker](https://github.com/Sage-of-Mirrors/EventWaker) - 《风之杖》地图事件编辑器。
- [Event_List_Editor](https://github.com/Sage-of-Mirrors/Event_List_Editor) - 《风之杖》event_list.dat 编辑器。

#### Wii Sports

- [wii-ipl (decomp)](https://github.com/koopthekoopa/wii-ipl) - Wii 菜单匹配反编译。
- [ogws (decomp)](https://github.com/doldecomp/ogws) - 《Wii Sports》匹配反编译。
- [noclip.website (Wii Sports)](https://github.com/magcius/noclip.website/tree/main/src/WiiSports) - 浏览器版《Wii Sports》查看。
- [noclip.website (Wii Sports Resort)](https://github.com/magcius/noclip.website/tree/main/src/WiiSports) - 浏览器版《Wii Sports Resort》查看。

#### Star Fox Adventures

- [noclip.website (Star Fox Adventures)](https://github.com/magcius/noclip.website/tree/main/src/StarFoxAdventures) - 浏览器版《星际火狐大冒险》查看。

#### Star Fox 64

- [sf64 (decomp)](https://github.com/sonicdcer/sf64) - 《星际火狐 64》匹配反编译。
- [sf64ex](https://github.com/jkbenaim/sf64ex) - 《星际火狐 64》ROM 文件提取器。

#### Star Fox 64 3D

- [SF643D_Tools](https://github.com/thtrandomlurker/SF643D_Tools) - 《星际火狐 64 3D》数据查看/修改工具合集。

#### Super Monkey Ball

- [noclip.website (Super Monkey Ball)](https://github.com/magcius/noclip.website/tree/main/src/SuperMonkeyBall) - 浏览器版《超级猴子球》查看。

#### F-Zero

- [fzerox (decomp)](https://github.com/inspectredc/fzerox) - 《F-Zero X》匹配反编译。
- [fzerox-expansion-kit (decomp)](https://github.com/inspectredc/fzerox-expansion-kit) - 《F-Zero X 扩展包》匹配反编译。

#### Chibi-Robo

- [cbr_decomp (decomp)](https://github.com/eavpsp/cbr_decomp) - 《机器人管家！》（NGC）匹配反编译。

#### Snowboard Kids

- [sk (decomp)](https://github.com/sonicdcer/sk) - 《滑雪少年》（N64）匹配反编译。
- [snowboardkids2-decomp (decomp)](https://github.com/cdlewis/snowboardkids2-decomp) - 《滑雪少年 2》（N64）匹配反编译。

#### Wave Race 64

- [wave-race-64 (decomp)](https://github.com/llonsit/wave-race-64) - 《激流快艇 64》匹配反编译。

#### The New Tetris

- [tnt (decomp)](https://github.com/kiritodv/tnt) - 《新俄罗斯方块》（N64）匹配反编译。

#### New Super Mario Bros DS

- [nsmb (decomp)](https://github.com/NSMB-Decomp/nsmb) - 《新超级马里奥兄弟》（NDS）匹配反编译。
- [noclip.website (New Super Mario Bros DS)](https://github.com/magcius/noclip.website/tree/main/src/nns_g3d) - 浏览器版《新超级马里奥兄弟 DS》查看。

#### Metroid Prime

- [noclip.website (Metroid Prime)](https://github.com/magcius/noclip.website/tree/main/src/MetroidPrime) - 浏览器版《银河战士 Prime》查看。
- [DreadGhidraPlugin](https://github.com/duncathan/DreadGhidraPlugin) - Ghidra 插件，辅助逆向《银河战士 生存恐惧》。
- [noclip.website (Metroid Prime 2)](https://github.com/magcius/noclip.website/tree/main/src/MetroidPrime) - 浏览器版《银河战士 Prime 2：回声》查看。
- [noclip.website (Metroid Prime 3)](https://github.com/magcius/noclip.website/tree/main/src/MetroidPrime) - 浏览器版《银河战士 Prime 3：堕落》查看。
- [noclip.website (Metroid Prime Hunters)](https://github.com/magcius/noclip.website/tree/main/src/MetroidPrimeHunters) - 浏览器版《银河战士 Prime 猎人》查看。
- [mzm (decomp)](https://github.com/metroidret/mzm) - 《银河战士 零点任务》匹配反编译。
- [mf (decomp)](https://github.com/metroidret/mf) - 《银河战士 融合》匹配反编译。
- [prime (decomp)](https://github.com/primedecomp/prime) - 《银河战士 Prime》匹配反编译。
- [echoes (decomp)](https://github.com/primedecomp/echoes) - 《银河战士 Prime 2：回声》匹配反编译。

#### Pokemon

- [noclip.website (Pokemon Snap)](https://github.com/magcius/noclip.website/tree/main/src/PokemonSnap) - 浏览器版《宝可梦随乐拍》查看。
- [noclip.website (Pokemon Platinum)](https://github.com/magcius/noclip.website/tree/main/src/nns_g3d) - 浏览器版《宝可梦 白金》查看。
- [noclip.website (Pokemon HeartGold/SoulSilver)](https://github.com/magcius/noclip.website/tree/main/src/nns_g3d) - 浏览器版《宝可梦 心金/魂银》查看。
- [camelotgcdatatool](https://github.com/gamemasterplc/camelotgcdatatool) - Camelot NGC 游戏（马里奥高尔夫/网球）数据编解码。
- [amnoid.de/gc](http://amnoid.de/gc/) - GameCube 文件格式文档与工具。
- [BMS-Analyzer](https://github.com/3e2j/BMS-Analyzer) - Wii/GC BMS → MIDI 转换器。
- [CaveGenerator](https://github.com/Fizz14/CaveGenerator) - 《皮克敏 2》洞窟生成工具。
- [NintyFont](https://github.com/hadashisora/NintyFont) - 任天堂二进制字体编辑器。
- [MarioKartToolbox](https://github.com/HaroohiePals/MarioKartToolbox) - 新版《马里奥赛车 DS》全功能编辑器。
- [GRPEdit](https://github.com/Garhoogin/GRPEdit) - 《马里奥赛车 DS》grpconf.tbl 编辑器。
- [picori](https://github.com/Julgodis/picori) - Picori 库（ピッコル），聚焦 GC/Wii 游戏的反编译/Mod/ROM Hack。
- [MasterOcarina](https://github.com/mzxrules/MasterOcarina) - 《塞尔达 64》工具合集。
- [zelda-internal-file-extractor](https://github.com/politerust/zelda-internal-file-extractor) - 《塞尔达 64》ROM 内部文件提取 CLI。
- [Zelda64Loader](https://github.com/Random06457/Zelda64Loader) - Ghidra 的《塞尔达 64》ROM 加载器。
- [zcamedit](https://github.com/sauraen/zcamedit) - 《塞尔达 64》（时之笛/穆修拉）过场摄像机 Blender 插件。
- [OoT-Anim-Copy](https://github.com/skawo/OoT-Anim-Copy) - 在 ZOBJ 之间拷贝《时之笛》动画。
- [OoT-NPC-Maker](https://github.com/skawo/OoT-NPC-Maker) - 《时之笛》NPC 生成工具。
- [PyZelda64-Text-Editor](https://github.com/skawo/PyZelda64-Text-Editor) - 跨平台《塞尔达 64》文本编辑器。
- [pycgfx](https://github.com/skyfloogle/pycgfx) - glTF → 3DS CGFX 转换工具。
- [zev](https://github.com/wareya/zev) - 《塞尔达 64》关卡查看器 ZEV。
- [ozmav](https://github.com/xdanieldzd/ozmav) - 旧 N64 模拟/Mod 工具（已停更，代码导出）。
- [SceneNavi](https://github.com/xdanieldzd/SceneNavi) - 《塞尔达 传说：时之笛》关卡编辑器（已停更）。
- [sharpocarina](https://github.com/xdanieldzd/sharpocarina) - 从 code.google 导出的《时之笛》工具（已停更）。
- [z64font](https://github.com/z64dev/z64font) - 首个 N64 《塞尔达》字体编辑器。
- [z64viewer](https://github.com/z64dev/z64viewer) - 现代 OpenGL HLE 渲染《塞尔达 64》模型。
- [zzrtl](https://github.com/z64dev/zzrtl) - 轻量《塞尔达 64》文件系统管理工具。
- [z64audio](https://github.com/z64tools/z64audio) - 较灵活的《塞尔达 64》音频转换器。
- [Z64Utils](https://github.com/zeldaret/Z64Utils) - Zelda64 引擎资产查看器。
- [NSMBHD Wiki (BCRES)](https://nsmbhd.net/wiki/BCRES/) - 3DS BCRES 格式文档。
- [CloudModding Wiki (OoT Animation)](https://wiki.cloudmodding.com/oot/Animation_Format) - 《时之笛》动画格式文档。
- [mm (decomp)](https://github.com/zeldaret/mm) - 《塞尔达传说：穆修拉的假面》匹配反编译。
- [oot (decomp)](https://github.com/zeldaret/oot) - 《塞尔达传说：时之笛》匹配反编译。
- [oot-vc (decomp)](https://github.com/zeldaret/oot-vc) - Wii VC 《时之笛》N64 模拟器（日版）匹配反编译。
- [oot3d (decomp)](https://github.com/zeldaret/oot3d) - 《塞尔达传说：时之笛 3D》匹配反编译。
- [tww (decomp)](https://github.com/zeldaret/tww) - 《塞尔达传说：风之杖》匹配反编译。
- [tmc (decomp)](https://github.com/zeldaret/tmc) - 《塞尔达传说：缩小帽》匹配反编译。
- [ph (decomp)](https://github.com/zeldaret/ph) - 《塞尔达传说：幻影沙漏》匹配反编译。
- [st (decomp)](https://github.com/yanis002/st) - 《塞尔达传说：灵魂轨迹》匹配反编译。
- [ss (decomp)](https://github.com/zeldaret/ss) - 《塞尔达传说：天空之剑》匹配反编译。
- [botw (decomp)](https://github.com/zeldaret/botw) - 《塞尔达传说：荒野之息》（Switch 1.5.0）匹配反编译。
- [las-decomp (decomp)](https://github.com/Owen-Splat/las-decomp) - 《塞尔达传说：织梦岛》Switch 重制版（2019）匹配反编译。
- [tp (decomp)](https://github.com/zeldaret/tp) - 《塞尔达传说：黄昏公主》匹配反编译。

### Ntreev Soft

- [PangLib](https://github.com/retreev/PangLib) - 交互 Pangya PC MMO 资源的工具集。
- [Pangya .iff formats](https://pixelde.su/blog/reverse-engineering-pangya-file-formats-2-iff/) - 讲解 Pangya IFF 格式的博客。
- [Pangya .dat formats](https://desu.blog/reverse-engineering-pangya-file-formats-1-dat) - 讲解 Pangya DAT 格式的博客。

### BioWare

#### Mass Effect

- [Gibbed.MassEffectAndromeda](https://github.com/gibbed/Gibbed.MassEffectAndromeda) - 《质量效应：仙女座》文件格式工具。

#### Dragon Age: Origins

- [Dragon Age Origins 3dsmax Import Export script](https://www.moddb.com/games/dragon-age-origins/downloads/dragon-age-origins-3dsmax-import-export-script) - 《龙腾世纪：起源》3ds Max 导入/导出脚本（v5.38，3ds Max 2013 效果最佳）。

#### Knights of the Old Republic

- [StarForge](https://github.com/Astral-C/StarForge) - 《旧共和国武士》文件格式工具。
- [Kotor Tool 1](https://www.moddb.com/games/star-wars-knights-of-the-old-republic/downloads/kotor-tool-1) - 《旧共和国武士》解包/规则修改/关卡自定义工具。

### Obsidian Entertainment

#### Neverwinter Nights 2

- [NWN2MDK](https://github.com/Arbos/nwn2mdk) - 《无冬之夜 2》Mod/开发工具包，含网格/动画 Blender 插件与命令行转换器。

### Panic (Playdate)

- [playdate-reverse-engineering](https://github.com/cranksters/playdate-reverse-engineering) - Playdate 掌机逆向笔记与工具。
- [noclip.website (A Short Hike)](https://github.com/magcius/noclip.website/tree/main/src/AShortHike) - 浏览器版《A Short Hike》查看。

### Paradox Interactive

- [io_pdx_mesh](https://github.com/ross-g/io_pdx_mesh) - 导入 Paradox 网格格式的 Blender 插件。

### Petroglyph Games

- [alo/ala max importer exporter (Star Wars: Empire at War)](https://www.moddb.com/groups/starwars-empire-at-war-fan-mod-group/downloads/aloala-max-importer-exporter) - 3ds Max ALO/ALA 导入导出插件。
- [Blender-ALAMAO-Plugin for 4.2LTS (Star Wars: Empire at War: Forces of Corruption)](https://www.moddb.com/games/star-wars-empire-at-war-forces-of-corruption/downloads/blender-alamao-plugin-for-42lts) - ALAMO 引擎模型(.alo)/动画(.ala) 读写 Blender 插件，适配《帝国战争：腐败力量》。
- [Grey Goo Official Asset Adding Tools](https://www.moddb.com/games/grey-goo/downloads/grey-goo-asset-adding-tools) - 《灰蛊》官方 SDK 与资产导入工具，含 32 位 3ds Max 插件与 .meg 处理工具。
- [3DS Max 7 and 8 Plugin for Map Editor (Star Wars: Empire At War)](https://www.moddb.com/games/star-wars-empire-at-war/downloads/3ds-max-7-and-8-plugin-for-map-editor) - 《帝国战争》地图编辑器 3ds Max 7/8 插件。
- [Star Wars Empire At War FOC DDS Tool](https://www.moddb.com/games/star-wars-empire-at-war-forces-of-corruption/downloads/star-wars-empire-at-war-foc-dds-tool) - 《帝国战争：腐败力量》DDS 纹理工具。
- [Star Wars Empire At War FOC DDS Viewer & Thumbplug _tga1.10](https://www.moddb.com/games/star-wars-empire-at-war-forces-of-corruption/downloads/star-wars-empire-at-war-foc-dds-viewer-thumbplug-tga110) - 《帝国战争：腐败力量》DDS 查看器与 TGA 缩略插件 v1.10。
- [Star Wars Empire At War FOC Alamo Object Importer 1.2](https://www.moddb.com/games/star-wars-empire-at-war-forces-of-corruption/downloads/alamo-object-importer-12) - 《帝国战争：腐败力量》3ds Max Alamo 对象导入器 v1.2。
- [Star Wars Empire At War FOC Alamo Viewer 1.2](https://www.moddb.com/games/star-wars-empire-at-war-forces-of-corruption/downloads/alamo-viewer-12) - 《帝国战争：腐败力量》Alamo 查看器 v1.2。

### PlatinumGames

- [platinumgames_stuff](https://github.com/Timo654/platinumgames_stuff) - 白金工作室游戏（含《猎天使魔女 3》《合金装备崛起》）Python 脚本合集。

#### Bayonetta

- [bayonetta_patch](https://github.com/Kerilk/bayonetta_patch) - 修改《猎天使魔女》可执行文件的补丁系统。
- [noesis_bayonetta_pc](https://github.com/Kerilk/noesis_bayonetta_pc) - 白金工作室模型/动画 Noesis 插件。
  - 游戏：猎天使魔女 1-3/起源、尼尔：机械纪元、合金装备崛起、疯狂世界、科拉传奇、曼哈顿变种忍者神龟、变形金刚：毁灭、星际火狐 0、异界锁链、神奇 101、猎天使魔女：救世之翼、必杀令、巴比伦陨落。
- [bayonetta_tools](https://github.com/Kerilk/bayonetta_tools) - Ruby 工具集，提取/转换白金工作室资产（模型/贴图/动画），支持猎天使魔女 1-3、尼尔机械纪元、异界锁链等。

#### Nier: Automata / Replicant

- [kaine](https://github.com/neptuwunium/kaine) - C# 库，处理《尼尔 复制人 ver.1.22》文件格式。
- [replicant_templates](https://github.com/WoefulWolf/replicant_templates) - 010 模板，覆盖《尼尔 复制人 ver.1.22474487139》ARC/PACK/BXON 及各类模型/材质/纹理格式。
- [replicant_toolkit](https://github.com/WoefulWolf/replicant_toolkit) - 《尼尔 复制人》文件格式工具包。
- [Blender2NieR](https://github.com/WoefulWolf/NieR2Blender2NieR) - Blender 导出 WMB/WTP/WTA/DAT/DTT 到《尼尔》系列的插件。
- [NieR2Blender](https://github.com/WoefulWolf/NieR2Blender_2_8) - 导入《尼尔 机械纪元/复制人》模型的 Blender 插件。
- [Replicant2Blender](https://github.com/WoefulWolf/Replicant2Blender) - 导入《尼尔 复制人 ver.1.22》网格包与纹理的 Blender 插件（alpha）。

### Primal Software

#### The I of the Dragon

- [Archive files plugin for Noesis (The I of the Dragon)](https://www.moddb.com/games/the-i-of-the-dragon/downloads/archive-files-plugin-for-noesis-v001) - Basic tools to work with archive resource files (.res).

### Procedural Arts

#### Façade

- [facade_editor](https://github.com/G4B33/facade_editor) - Randomizer, corruptor, and editor for Façade. Randomizes sounds, textures, cursors, animations, and subtitles; replaces custom sound files with automatic downsampling; decompiles .bin, .map, and .rul files (Jess rule language); enables built-in debug features.
- [Facade (decompiled)](https://github.com/VideoGameSmash12/Facade) - Decompiled back-end source code of Façade, which was written entirely in Java.

### Polytron (Fez)

- [noclip.website (Fez)](https://github.com/magcius/noclip.website/tree/main/src/Fez) - In-browser Fez viewer.

### Mithis Entertainment

#### Nexus: The Jupiter Incident

- [Nexus Mesh Importer](https://www.moddb.com/games/nexus-the-jupiter-incident/downloads/nexus-mesh-importer) - A plug-in for Milkshape 3d that'll allow you to work on existing Nexus ship mesh & tex files.
- [Nexus Texture Converter](https://www.moddb.com/games/nexus-the-jupiter-incident/downloads/nexus-texture-converter) - converts Nexus' proprietary .tex file format to regular .tga images .NET Framework 3.5 required

### Punchline

- [Murugo/Misc-Game-Research (Rule of Rose)](https://github.com/Murugo/Misc-Game-Research/tree/main/PS2/Rule%20of%20Rose) - Reverse engineering notes for Rule of Rose (PS2).

### People Can Fly

#### Painkiller

- [Painkiller 3ds Max Plugins (Upd270522)](https://www.moddb.com/games/painkiller/downloads/painkiller-3ds-max-plugins) - 3ds Max import/export plug-ins for Painkiller assets (Upd270522) by dilettante
- [HavokXML2HKE converter for Ragdoll physics 3ds Max (Painkiller)](https://www.moddb.com/games/painkiller/downloads/havokxml2hke-converter-for-ragdoll-physics) - Converter Havok-XML to *.HKE (Havok Exporter) for ragdoll physics by dilettante. HavokPcXsContentTools_X64_2010-2-0_20101115 for 3dsmax9 x64 is also included.
- [PainFull Extractor v1.3.2 (Painkiller)](https://www.moddb.com/games/painkiller/downloads/painfull-extractor-v132) - Unpacker for Painkiller & NecroVision game resources (.pak files). This program is outdated and should be run in the WindowsXP (SP 2) compatibly mode. Use Dragon UnPACKer or QuickBMS as an alternative.
- [Painkiller converters mpk/dat to ASE and ASE to mpk/dat](https://www.moddb.com/games/painkiller/downloads/painkiller-converters-mpk-to-ase-and-ase-to-mpk) - Console utilities to convert the Painkiller mpk and dat geometry format to and from Ascii Scene (ASE): ase2mpk, mpk2ase, blend, PKBlend, dat2ase, and mpk2dat.

#### Dreamkiller

- [Dreamkiller Mapping Tools for 3ds Max](https://www.moddb.com/games/dreamkiller/downloads/dreamkiller-mapping-tools) - DKStaticMeshImp.dli - 3dsMax static mesh import plugin. UnpackTEXT.exe - texture extractor.

### Piranha Bytes

- [ZenLib](https://github.com/ataulien/ZenLib) - Loading library for proprietary formats used by the engine in Gothic and Gothic II games.

### Polyphony Digital (Gran Turismo)

- [GTAllPaintEditor](https://github.com/Nenkai/GTAllPaintEditor) - Tool to edit Gran Turismo 6's allpaint.bin file for assigning custom paints to cars through GT Auto.
- [gt2-reversing](https://github.com/ginryuoku/gt2-reversing) - Reverse engineering tools for Gran Turismo 2.
- [PDTools](https://github.com/Nenkai/PDTools) - Utilities for extracting and modifying Gran Turismo game files.
- [GT4SaveEditor](https://github.com/Nenkai/GT4SaveEditor) - Save editor for Gran Turismo 4.
- [AdhocScriptEngine](https://github.com/Nenkai/AdhocScriptEngine) - Reverse engineering the adhoc script/assembly language & system of the Gran Turismo series.
- [esprima-dotnet](https://github.com/Nenkai/esprima-dotnet) - Fork of Esprima .NET to target the scripting language for Gran Turismo series, Adhoc.

### Rebel Act

- [3D tools for Severance v2.5](https://www.moddb.com/games/severance-blade-of-darkness/downloads/3d-tools-for-severance-v25) - Tools needed to import / export animations, obsjects and characters into the game. It's recommended to use also the TPTPT Scripts.
- [3D Tools & Scripts v1.2.1](https://www.moddb.com/games/severance-blade-of-darkness/downloads/3d-tools-scripts-v121) - Collection of 3DS Max tools and scripts for Severance: Blade of Darkness. Includes: TPBladeToolsChar for Max 2.5 (v1.2.0 Patch 1.2.1), BladeTools for Max 8 (v1.2.0 Patch 1.2.1), TPBladeCharEditorTools for Max 8 (v1.2.0 Patch 1.2.1), Python 2.4, and Py2exe for Python 2.4 (v1.2.1).
- [Blade of Darkness Mod Tools & Tutorials](https://www.moddb.com/games/severance-blade-of-darkness/downloads/blade-of-darkness-mod-tools-tutorials) - Comprehensive collection of tools, tutorials, demonstration files, textures, and maps for Severance: Blade of Darkness. Includes most resources needed to get started with making maps and characters. Collection organized by bigtruck.
- [Blade Tools English. Severance - SDK](https://www.moddb.com/games/severance-blade-of-darkness/downloads/blade-tools-english-severance-sdk) - SDK and modding tools for Severance: Blade of Darkness (English version).
- [Blade Tools Spanish. Blade SDK](https://www.moddb.com/games/severance-blade-of-darkness/downloads/blade-tools-spanish-blade-sdk) - Herramientas de edición del juego Blade: The Edge of Darkness.

### Rebellion Developments

- [AvP Editing Tools](https://www.moddb.com/games/aliens-vs-predator/downloads/avp-editing-tools) - Collection of modding tools for Aliens versus Predator including old modding programs and Rebellion's official Gold tools. Includes: AVPTweak, AVP Launcher, Fastfile Backup, Fastfile Explorer, Leadworks, Level Tweaker, nelev, Patch Editor, Patch Installer, PREtweak, Profile Tweaker, Ripley2, ScreamED, Texture Infector, and more.
- [AVP Gold Tools and Source Code (Aliens versus Predator - Classic)](https://www.moddb.com/games/aliens-vs-predator/downloads/avp-gold-tools-and-source-code) - Official editing tools by Rebellion for Aliens versus Predator Gold Edition, including game source code and complete instructions/guidelines. Essential for editing and creating new content....

#### Aliens vs. Predator 2

- [AVP2 official tools](https://www.moddb.com/games/aliens-vs-predator-2/downloads/avp2-official-tools) - AVP2's official tools created by Monolith. Mirrored here for archival purposes.

#### Aliens vs. Predator (2010)

- [Asura Engine Extractor (Aliens vs. Predator 2010)](https://www.moddb.com/games/avp2010/downloads/asura-engine-extractor) - A very experimental tool to unpack textures and repack it with live preview. The tool is open Source so anyone has the freedom to modify it. Enjoy!. Build with help of Codex

### Rare

- [sssv (decomp)](https://github.com/mkst/sssv) - Matching decompilation of Space Station Silicon Valley (N64).

#### Banjo-Kazooie

- [noclip.website (Banjo-Kazooie)](https://github.com/magcius/noclip.website/tree/main/src/BanjoKazooie) - In-browser Banjo-Kazooie viewer.
- [Banjo-Kazooie-Floor-Tool](https://github.com/oohnahleevay/Banjo-Kazooie-Floor-Tool) - Tool to modify floor collision properties in Banjo-Kazooie.
- [Banjo-s-Backpack](https://github.com/RareExports/Banjo-s-Backpack) - Level editor for Banjo-Kazooie (map and object editing).
- [Bottles_Glasses](https://github.com/RareExports/Bottles_Glasses) - Model and map renderer for Banjo-Kazooie and Banjo-Tooie.

#### Banjo-Tooie

- [noclip.website (Banjo-Tooie)](https://github.com/magcius/noclip.website/tree/main/src/BanjoTooie) - In-browser Banjo-Tooie viewer.
- [Bottles_Glasses](https://github.com/RareExports/Bottles_Glasses) - Model and map renderer for Banjo-Kazooie and Banjo-Tooie.
- [WumbasWigwam](https://github.com/RareExports/WumbasWigwam) - Level exporter for Banjo-Tooie (Blender import support).
- [BK2BT](https://github.com/Muzzarino/BK2BT) - Fast3DEX to Fast3DEX2 microcode converter for Banjo-Kazooie model files to Banjo-Tooie format. Includes model previewer and converter.

#### Donkey Kong 64

- [noclip.website (Donkey Kong 64)](https://github.com/magcius/noclip.website/tree/main/src/DonkeyKong64) - In-browser Donkey Kong 64 viewer.
- [DK64MapGenerator](https://github.com/GloriousLiar/DK64MapGenerator) - Tool for generating Donkey Kong 64 map and floor files from 3D meshes.
- [DK64-Viewer](https://github.com/RareExports/DK64-Viewer) - Model and map viewer for Donkey Kong 64.
- [dk64_lib](https://github.com/ThomasJRyan/dk64_lib) - Library for extracting data from Donkey Kong 64 ROMs.

#### Diddy Kong Racing

- [noclip.website (Diddy Kong Racing)](https://github.com/magcius/noclip.website/tree/main/src/DiddyKongRacing) - In-browser Diddy Kong Racing viewer.
- [diddy-kong-racing (decomp)](https://github.com/davidsm64/diddy-kong-racing) - Matching decompilation of Diddy Kong Racing.

#### GoldenEye 007

- [noclip.website (GoldenEye 007)](https://github.com/magcius/noclip.website/tree/main/src/GoldenEye007) - In-browser GoldenEye 007 viewer.
- [GoldEditor](https://github.com/carnivoroussociety/GoldEditor) - Setup editor for GoldenEye 007 game configurations.

#### Conker's Bad Fur Day

- [conker (decomp)](https://github.com/mkst/conker) - Matching decompilation of Conker's Bad Fur Day (N64).

#### Banjo-Kazooie (Xbox 360)

- [bk360 (decomp)](https://github.com/banjo360/bk360) - Matching decompilation of Banjo-Kazooie (Xbox 360).

### Raven Software

#### Heretic II

- [Quake Model to FlexModel Converter](https://www.moddb.com/games/heretic-ii/downloads/quake-model-to-flexmodel-converter-aka-convert) - Converts Quake models to FlexModel format. Preserves vertex placement only (no skeletal structure), suitable for static models, not animated player models.
- [FlexModel to Wavefront Object Converter (FM2OBJ)](https://www.moddb.com/games/heretic-ii/downloads/flexmodel-to-wavefront-object-converter-aka-fm2obj) - Exports Heretic II animation frames (e.g., conjure11, draw5) as 3D meshes in Alias/Wavefront OBJ format. Can export Corvus or Kiera in specific poses, with option to export each mesh node (head, arm, etc.) as separate meshes.
- [Heretic II Toolkit v1.06](https://www.moddb.com/games/heretic-ii/downloads/heretic-ii-toolkit-v106) - Official Heretic II modding toolkit. Usually included with the Heretic II CD, but available for download here (v1.06).

#### Soldier of Fortune

- [Official 3dsmax 3x plugin (Soldier of Fortune)](https://www.moddb.com/games/soldier-of-fortune/downloads/official-3dsmax-3x-plugin) - Official GHOUL exporter for 3DS Max 3.x. Includes Controller for 3D Studio Max (avg_ctrl.dlc), Softimage|3D import plugin, and GHOUL prep program.
- [.m32 to .tga/.adp to .wav file converters (Soldier of Fortune)](https://www.moddb.com/games/soldier-of-fortune/downloads/m32-to-tga-file-converter) - Convert your .m32 (SoF) texture files to manageable .tga texture files with an easy to use GUI. Also includes .adp to .wav for audio conversion. Also includes source code.
- [.m32 tool (Soldier of Fortune)](https://www.moddb.com/games/soldier-of-fortune/downloads/m32-tool) - .m32 tool is a texture conversion utility for Soldier of Fortune. Allows batch conversion of .tga files to .m32.
- [.os script decompiler v2.0 (Soldier of Fortune)](https://www.moddb.com/games/soldier-of-fortune/downloads/os-script-decompiler-v20) - Command line program that tries to convert .os files back into .ds file form.

### Runic Games

#### Torchlight

- [Nimet - Ogre3D Mesh Viewer (Torchlight)](https://www.moddb.com/games/torchlight/downloads/nimet-ogre3d-mesh-viewer) - Nimet is an advanced 3D model viewer for Ogre3D engine.
- [Cliffside tile set build 1.0.00 (Torchlight)](https://www.moddb.com/games/torchlight/downloads/cliffside-tile-set-build-1000) - Mod adding a new tile set and prop set called CliffSide for Torchlight. Outdoor set for creating areas based around mountains, forests, and water (v1.0.00).

#### Torchlight II

- [Modified PAK Extractor Tool](https://www.moddb.com/games/torchlight-ii/downloads/modified-pak-extractor-tool-by-jarcho) - Tool for extracting data files from Torchlight 2's DATA.PAK file. Developed by Jarcho, modified by timebomb. Enables modding by extracting game assets.
- [GUTS Tools and Assets](https://www.moddb.com/games/torchlight-ii/downloads/guts-tools-and-assets) - This .ZIP includes raw media, assets, and tools which will be useful to you when creating mods for Torchlight II. Below is a brief description of the resources you will find in this package.

### Runecraft

- [esa (decomp)](https://github.com/mkst/esa) - Matching decompilation of Evo's Space Adventures (PS1).

### 1C Company / Best Way

#### Men of War

- [Men of War 3DS Max Exporter Tools](https://www.moddb.com/games/men-of-war/downloads/men-of-war-3ds-max-exporter-tools) - 3DS Max exporter tools for Men of War. Supports 32-bit versions of 3DS Max 8, 9, 2008, and 2009 only. Mirrored here as the original Best Way download is no longer available.

#### Royal Quest Online

- [RQ.TOC.Tool](https://github.com/Ekey/RQ.TOC.Tool) - Tool for extracting archives from Royal Quest Online game files.

### Ironclad Games / Stardock

#### Sins of a Solar Empire

- [Sins 3D Max Import export](https://www.moddb.com/games/sins-of-a-solar-empire-rebellion/downloads/sins-3d-max-impotrt-export) - 3DS Max importer for Sins of a Solar Empire: Rebellion TXT mesh format. Exporter in progress. Trial alpha version.
- [sins TXT Tools with export (Sins of a Solar Empire: Rebellion)](https://www.moddb.com/games/sins-of-a-solar-empire-rebellion/downloads/sins-txt-tools-with-export) - This version with export to TXT! Alpha version...adds sins standart material with default settings
- [Forge Tools (Sins of a Solar Empire)](https://www.moddb.com/games/sins-of-a-solar-empire/downloads/forge-tools) - Official development tools for creating custom maps and modifications for Sins of a Solar Empire. Includes Galaxy Forge and Particle Forge tools used by the development team.
- [Map Conversion (Sins of a Solar Empire)](https://www.moddb.com/games/sins-of-a-solar-empire/downloads/map-conversion) - Convert maps between Sins versions with this user-created tool. Created by Ross Placing. Requires .Net 2.0; Updated for Sins 1.15/Entrenchment 1.01.

### Radical Entertainment

- [scarface-p3d](https://github.com/aap/scarface-p3d) - Code to deal with P3D files from "Scarface: The World is Yours".
- [map-data-editor](https://github.com/WeaselOnaStick/map-data-editor) - Blender 2.80+ addon for editing SHAR map data like road networks, fences, paths, locators, and level trees in The Simpsons: Hit & Run.

### Reflections Interactive

- [driver-tools](https://github.com/Fireboyd78/driver-tools) - 《Driver3》《Driver: Parallel Lines》《Driver: San Francisco》Mod 工具。
- [REDRIVER2](https://github.com/OpenDriver2/REDRIVER2) - 《Driver 2》PS1 逆向工程。
- [Driver model tools](https://www.moddb.com/games/driver-you-are-the-wheelman/downloads/driver-model-tools) - 包含模型提取/替换、Milkshape 3D 导入导出插件的工具集。

### Riot Games

- [yordle](https://github.com/neptuwunium/yordle) - 《英雄联盟》文件格式研究项目。
- [MindCorpViewer](https://github.com/autergame/MindCorpViewer?tab=readme-ov-file) - 《英雄联盟》SKN/SKL/DDS 模型查看器（已归档）。
- [MindCorpViewer-Rust](https://github.com/autergame/MindCorpViewer-Rust) - Rust 重写版《英雄联盟》模型查看器。

### Santa Monica Studio (God of War)

- [god_of_war_browser](https://github.com/mogaika/god_of_war_browser) - 基于 WebGL 的《战神》1/2（PS2/PS3/Vita）模型与纹理浏览器。
- [God of War 2018 PS4 Tools](https://forum.xentax.com/viewtopic.php?f=16&t=22897) - XeNTaX 论坛上的 PS4《战神》（2018）讨论与提取工具。（链接存档/失效）

### SCS Software (Euro Truck Simulator)

- [ETS2.SCS.Tool](https://github.com/Ekey/ETS2.SCS.Tool) - 《欧洲卡车模拟 2》SCS 封包解包工具。

### Sega

- [ogre-decomp (decomp)](https://github.com/hamzaxx370/ogre-decomp) - 《如龙 1》（PS2）匹配反编译。
- [tbg-decomp (decomp)](https://github.com/lhsazevedo/tbg-decomp) - 《东京巴士案内》（DC）匹配反编译。
- [SkiesofArcadiaLegends (decomp)](https://github.com/rainchus/SkiesofArcadiaLegends) - 《天空之阿卡迪亚传奇》（NGC）匹配反编译。
- [puyotools](https://github.com/nickworonekin/puyotools) - 访问各类游戏文件的工具/库，最初为《魔法气泡》制作。
- [puyo-pac](https://github.com/nickworonekin/puyo-pac) - 命令行创建/解包《魔法气泡 俄罗斯方块 2》PAC 封包。
- [PP20thDataExtractor](https://github.com/nickworonekin/PP20thDataExtractor) - 提取/构建 Wii/PSP《魔法气泡 20 周年》GAME.DAT。
- [JSRGraffitiTool](https://github.com/chrisderwahre/JSRGraffitiTool) - 《喷射电台》涂鸦文件 Mod 工具。
- [ParManager](https://github.com/Kaplas80/ParManager) - 《如龙》系列 PAR 封包工具。
- [yk_gmd_io](https://github.com/theturboturnip/yk_gmd_io) - Blender 3.2+ 插件，导入/导出《如龙》系列 .gmd。
- [PSO2-Aqua-Library](https://github.com/Shadowth117/PSO2-Aqua-Library) - 《梦幻之星 Online 2》Aqua 格式库，聚焦模型。
- [PSO2-Salon-Tool](https://github.com/Shadowth117/PSO2-Salon-Tool) - 编辑/转换 PSO2 .xxp/.cml 的程序。
- [FpkTool](https://github.com/Shadowth117/FpkTool) - PSO2 FPK（NGS 前）解/打包。
- [PSO2 Tools](https://github.com/dummycount/blender_pso2_tools) - PSO2 资产 Blender 插件（.aqp/.aqn、ICE 封包），支持模型搜索、封包浏览、自动贴图。

#### Creative Assembly

##### Alien: Isolation

- [Alien Isolation Animation Exporter](https://www.moddb.com/mods/alien-isolation-extractors/downloads/alien-isolation-animation-exporter) - 导出《异形：隔离》动画与骨骼。
- [Alien Isolation Model Exporter](https://www.moddb.com/mods/alien-isolation-extractors/downloads/alien-isolation-model-exporter) - 导出《异形：隔离》模型以便导入 Blender。
- [Alien Isolation Texture Exporter](https://www.moddb.com/mods/alien-isolation-extractors/downloads/texture-extractor) - 提取《异形：隔离》纹理（Cra0kalo 开发，MattFiler 修改）。
- [Alien Isolation Audio Converter](https://www.moddb.com/mods/alien-isolation-extractors/downloads/alien-isolation-audio-converter) - 《异形：隔离》音频转换器，包含 revorb、bnkextr、ww2ogg 及使用说明。
- [Alien Isolation BML Converter](https://www.moddb.com/mods/alien-isolation-extractors/downloads/alien-isolation-bml-converter) - 《异形：隔离》BML 转换器，可修改行为、武器等。
- [Alien Isolation UI Mod Tool](https://www.moddb.com/mods/alien-isolation-extractors/downloads/alien-isolation-ui-mod-tool) - 《异形：隔离》UI Mod 工具。

##### Total War Series

- [Texture 2 DDS Converter (Medieval II: Total War)](https://www.moddb.com/games/medieval-2-total-war/downloads/texture-2-dds-converter)
- [Vercengetorix's CAS Import/Export (Medieval II: Total War)](https://www.moddb.com/games/medieval-2-total-war/downloads/vercengetorix-s-cas-import-export) - Allows you to import and export .CAS files to and from 3ds Max.
- [CAS Exporter (Medieval II: Total War)](https://www.moddb.com/games/medieval-2-total-war/downloads/cas-exporter) - Public release of model and animation exporter for Rome: Total War and Medieval II: Total War.
- [Community Modding Framework (Total War: Warhammer II)](https://www.moddb.com/games/total-war-warhammer-ii/downloads/community-modding-framework-1104) - Community Modding Framework v1.10.4, authored by Crynsos. This mod acts as a central compatibility manager for all script mods that have been registered to prevent any potential conflicts. As a secondary function, this mod also serves as a bugfix for a long standing issue with new characters and ...
- [Symphony Sound Packer (Empire: Total War)](https://www.moddb.com/mods/foothold-in-india/downloads/symphony-sound-packer) - British Line Infantry starts shouting "Revolutionary Guard!" when you click them after installing a mod with new units? This tool should help you. All credits to crux3D.
- [Aqua-Toolset](https://github.com/Shadowth117/Aqua-Toolset) - 主要用于 PSO2 文件格式的工具集。
- [NaomiMod/games-ExtractTools](https://github.com/NaomiMod/games-ExtractTools) - Dreamcast/Naomi 街机 NaomiLib 模型 QuickBMS 脚本，支持《生死格斗 2》《头文字 D3》《真人快打 4》《超级猴子球》《网球》等。
- [NaomiLib Blender Addon](https://github.com/NaomiMod/blender-NaomiLib) - 导入 NaomiLib 3D 模型的 Blender 插件，支持 DC/Naomi 游戏（《疯狂出租车》《生死格斗 2》《漫威 vs 卡普空 2》《莎木 2》《网球》等）。
- [PCSX2 Patches](https://github.com/PCSX2/pcsx2_patches) - PCSX2 宽屏/隔行修复等补丁。
- [noclip.website (Jet Set Radio)](https://github.com/magcius/noclip.website/tree/main/src/JetSetRadio) - 浏览器版《喷射电台》查看。
- [Sonic-1-2-2013-Decompilation (decomp)](https://github.com/RSDKModding/RSDKv4-Decompilation) - 《索尼克 1&2》（2013 移动版）与 Retro Engine v4 匹配反编译。
- [Sonic-CD-11-Decompilation (decomp)](https://github.com/RSDKModding/RSDKv3-Decompilation) - 《索尼克 CD》（2011 移动版）与 Retro Engine v3 匹配反编译。
- [sa1 (decomp)](https://github.com/SAT-R/sa1) - 《索尼克 Advance》（GBA 欧版）匹配反编译。
- [sa2 (decomp)](https://github.com/SAT-R/sa2) - 《索尼克 Advance 2》匹配反编译。
- [sa3 (decomp)](https://github.com/SAT-R/sa3) - 《索尼克 Advance 3》匹配反编译。
- [Sonic-Mania-Decompilation (decomp)](https://github.com/RSDKModding/Sonic-Mania-Decompilation) - 《索尼克 Mania》（2017）匹配反编译。
- [RunnersDecomp (decomp)](https://github.com/itsmattkc/RunnersDecomp) - 《索尼克 跑酷》匹配反编译。
- [SonicRushAdventure-Decomp (decomp)](https://github.com/RushRE/SonicRushAdventure-Decomp) - 《索尼克疾驰大冒险》匹配反编译。

### Sonic Team

#### Sonic Adventure

- [SCHG:Sonic_Adventure](https://info.sonicretro.org/SCHG:Sonic_Adventure) - 《索尼克大冒险》社区破解指南。
- [sadtools](https://github.com/FraGag/sadtools) - 《索尼克大冒险》文件格式 CLI 工具。
- [sa_tools](https://github.com/X-Hax/sa_tools) - 《索尼克大冒险》系列 Mod 工具包，支持 SADX 与 SA2PC。
- [SonicAdventureBlenderIO](https://github.com/X-Hax/SonicAdventureBlenderIO) - Blender 4.0+ 插件，导出《索尼克大冒险》1/2 的 3D 格式（.nj/.gj/.njm/.nja）。

#### Sonic Heroes / Shadow

- [HeroesPowerPlant](https://github.com/igorseabra4/HeroesPowerPlant/wiki/Level-Editor) - 《索尼克英雄》《暗影刺猬》全功能关卡编辑器。
- [Heroes.SDK](https://github.com/Muzzarino/Heroes.SDK) - 运行时操作《索尼克英雄》的统一库，定义内部数据结构/函数，含多种格式解析器，主要用于 Reloaded II Mod，也可单独使用。

#### Other Sonic Games

- [SonicMania-SaveEditor](https://github.com/Erik-JS/SonicMania-SaveEditor) - 《索尼克 Mania》存档编辑器。
- [Sonic-Colors-Set-Editor](https://github.com/thesupersonic16/Sonic-Colors-Set-Editor) - 《索尼克 色彩》关卡配置编辑器。
- [HeroesCollisionTool](https://github.com/igorseabra4/HeroesCollisionTool) - 《索尼克英雄》碰撞编辑工具。
- [HeroesVisibilityEditor](https://github.com/igorseabra4/HeroesVisibilityEditor) - 《索尼克英雄》可见性编辑器。
- [BBSonicDSTool](https://github.com/efimandreev0/BBSonicDSTool) - 《索尼克 DS》文件格式工具。
- [blue-sphere](https://github.com/scurest/blue-sphere) - 《索尼克 3 & 纳克鲁斯》特别关文件工具。
- [Glitter](https://github.com/crash5band/Glitter) - 打开/修改/保存《索尼克 世代》GTE/GTM 粒子文件的格式库与编辑器。
- [libgens-sonicglvl](https://github.com/Muzzarino/libgens-sonicglvl) - PC 版《索尼克 世代》关卡编辑器与格式库。
- [SonLVL-RSDK](https://github.com/Lavesiime/SonLVL-RSDK) - RSDK v3/v4（《索尼克 CD》《索尼克 1/2》）关卡编辑器。
- [RSDK-Reverse](https://github.com/Rubberduckycooly/RSDK-Reverse) - Retro Engine（索尼克 CD/1/2）逆向工具。
- [rsdkv6-extract](https://github.com/RSDKModding/rsdkv6-extract) - RSDK v6 文件提取器。
- [HedgeLib](https://github.com/Radfordhound/HedgeLib) - 《索尼克》系列 Mod 的 C++ 库与工具集。
- [Marathon](https://github.com/hyperbx/Marathon) - 《索尼克》文件格式工具包与库。
- [Sonic-1-2-2013-Decompilation](https://github.com/RSDKModding/RSDKv4-Decompilation) - 《索尼克 1&2》（2013）完整反编译及 Retro Engine v4。
- [UnleashedRecomp](https://github.com/hedge-dev/UnleashedRecomp) - 通过静态重编译实现的《索尼克 解放》Xbox360 非官方 PC 移植。
- [noclip.website (Sonic Colors)](https://github.com/magcius/noclip.website/tree/main/src/rres) - 浏览器版《索尼克 色彩》查看。
- [Sonic Retro (SA2 Hacking Guide)](https://info.sonicretro.org/SCHG:Sonic_Adventure_2) - 《索尼克大冒险 2》破解指南。
- [AllStarsRacingTools](https://github.com/tge-was-taken/AllStarsRacingTools) - 《索尼克与世嘉全明星赛车》未完成工具（仅供参考）。
- [Shuriken](https://github.com/crash5band/Shuriken) - 索尼克系列 XNCP/YNCP UI 编辑器。
- [Sega_NN_tools](https://github.com/Argx2121/Sega_NN_tools) - 针对 Sega NN 库游戏的 Blender Python 工具集。
- [Sonic-Adventure-Animation-.JSON-Input-Output](https://github.com/Shadowth117/Sonic-Adventure-Animation-.JSON-Input-Output) - 将 SA Tools 提取的《索尼克大冒险/DX/2/2 Battle》动画在 3ds Max 与 JSON 间导入导出。

### Snowblind Studios

#### Baldur's Gate: Dark Alliance

- [bgda-explorer](https://github.com/bigianb/bgda-explorer) - PS2《博德之门：黑暗联盟》数据文件浏览器。
- [jbgda](https://github.com/bigianb/jbgda) - 基于 Java 的《黑暗联盟》工具。
- [frostbite](https://github.com/bigianb/frostbite) - Snowblind 引擎实验性实现。

### Sony (First Party)

- [ico-decomp (decomp)](https://github.com/rossydoubleunderscore/ico-decomp) - 《ICO》（PS2）匹配反编译。
- [medievil-decomp (decomp)](https://github.com/medievildecompilation/medievil-decomp) - 《魔剑传奇》（PS1）匹配反编译。
- [mkpsxiso](https://github.com/Lameguy64/mkpsxiso) - 面向 PS1 自制开发的 ISO 生成/提取工具，XML 构建镜像，支持混合 CD-XA；跨平台现代替代 PsyQ BUILDCD。
- [LibOrbisPkg](https://github.com/OpenOrbis/LibOrbisPkg) - PS4 PKG/SFO/PFS 等创建、检查、修改的库、GUI、CLI，开源替代索尼 SDK。
- [SGXDataBuilder](https://github.com/Nenkai/SGXDataBuilder) - 由标准音频生成 Sony SGX/SGXD 音频库，适用于 GT5/6、乐克乐克、捉猴日记等 PSP/PS3 游戏。
  - 输出：sgd/sgh/sgb；输入：WAV/AC3。
- [DriveClubFS](https://github.com/Nenkai/DriveClubFS) - 解包《DriveClub》.ndx+.dat 文件系统，提取 .rpk 资源包中的二进制/XML/纹理，支持 1.00/1.28/NPXX51272。
- [LibreFios](https://github.com/neptuwunium/LibreFios) - C# PSARC 库，处理 PS 系列 PSARC 封包。
- [memcardrex](https://github.com/ShendoXT/memcardrex) - 高级 PS1 记忆卡编辑器，支持多种存档格式。
- [mymc](https://github.com/uyjulian/mymc) - PS2 记忆卡镜像操作工具。
- [sfo](https://github.com/hippie68/sfo) - 读取/修改 SFO 参数的快速 C 程序，可自动化或从零生成 param.sfo（含 Windows 可执行）。
- [ps3-ckit](https://github.com/tge-was-taken/ps3-ckit) - PS3 C 代码注入框架，可在游戏中运行自定义代码/Hook。
- [dynlib](https://github.com/aerosoul94/dynlib) - PS4 用户态 ELF 逆向的 IDA 插件，加载 DYNLIBDATA、解混淆 NID、补全重定位。
- [PS4-Package-Assessor-Java](https://github.com/Cryptogenic/PS4-Package-Assessor-Java) - 评估并展示 PS3/PS4 PKG 信息的 Java 工具。
- [RORPSPTOOL](https://github.com/leeao/RORPSPTOOL) - 《Cars Race-O-Rama》PSP/DS .mif/.rbh 封包工具。
- [pysx](https://github.com/cmbasnett/pysx) - FF7（PSX）文件提取/转换 Python 工具。
- [NLG-File-Editor-Tool](https://github.com/KillzXGaming/NLG-File-Editor-Tool) - 《小小大星球 2》.dict/.data 封包提取与编辑工具。

### Square Enix

#### Final Fantasy

- [FFCC-Decomp (decomp)](https://github.com/zcanann/FFCC-Decomp) - Matching decompilation of Final Fantasy Crystal Chronicles.
- [ff7tool](https://github.com/jkbenaim/ff7tool) - Tool for viewing Final Fantasy VII world maps.
- [FF16Tools](https://github.com/Nenkai/FF16Tools) - Tools & Library for Final Fantasy XVI / 16 Engine games (FFXVI, FINAL FANTASY TACTICS - The Ivalice Chronicles).
  - Features: PAC unpacker/repacker, TEX to DDS conversion, DDS/image to TEX, NXD (Nex/ExcelDB) conversion, PZD (Panzer dialogue) conversion, save file unpack/pack, FlatBuffer schemas for KDB (KineDriver) & BNMB (Bonamik).
- [ffxvi-nex-layouts](https://github.com/Nenkai/ffxvi-nex-layouts) - Nex sheet layouts for FINAL FANTASY XVI, for use with FF16Tools.
- [fftivc-nex-layouts](https://github.com/Nenkai/fftivc-nex-layouts) - Nex sheet layouts for FINAL FANTASY TACTICS - The Ivalice Chronicles, for use with FF16Tools.
- [ff16.utility.modloader](https://github.com/Nenkai/ff16.utility.modloader) - Final Fantasy XVI / 16 Mod Loader for Reloaded-II using FF16Tools.
- [fftivc.utility.modloader](https://github.com/Nenkai/fftivc.utility.modloader) - FINAL FANTASY TACTICS - The Ivalice Chronicles Mod loader for Reloaded-II using FF16Tools.
- [FaithFramework](https://github.com/Nenkai/FaithFramework) - Mod Framework for FFXVI using Reloaded-II. Features: ImGui API, Nex Runtime Interface API, Resource Manager, Camera Manager (WorldToScreen/Camera Pos).

#### Chrono Cross

- [chrono-cross-decomp (decomp)](https://github.com/jdperos/chrono-cross-decomp) - Matching decompilation of Chrono Cross (100%, based on Radical Dreamers version).

#### Xenogears

- [xenogears-decomp (decomp)](https://github.com/ladysilverberg/xenogears-decomp) - Matching decompilation of Xenogears.
- [Noah (decomp)](https://github.com/yaz0r/Noah) - Non-matching decompilation of Xenogears.

#### Xenosaga

- [xenosaga (decomp)](https://github.com/squareman/xenosaga) - Matching decompilation of Xenosaga Episode 1 (PS2, USA).

#### Vagrant Story

- [rood-reverse (decomp)](https://github.com/ser-pounce/rood-reverse) - Matching decompilation of Vagrant Story.

#### Soul Blazer

- [RustyBlazer (decomp)](https://github.com/hellow554/RustyBlazer) - 《创世纪传说》（Soul Blazer）匹配反编译。

#### Sleeping Dogs

- [TheoryEngine](https://github.com/SDmodding/TheoryEngine) - 基于官方 PDB 逆向的《热血无赖 终极版》引擎重实现（WIP），以头文件形式便于工具/Mod 嵌入。

#### The World Ends With You

- [twewy (decomp)](https://github.com/Yotona/twewy) - 《美妙世界》（NDS）匹配反编译。

#### Babylon's Fall

- [BabylonsFallTools](https://github.com/Nenkai/BabylonsFallTools) - 《巴比伦的陨落》PKZL/.pkz 与 DAT 提取工具。

#### Hitman

- [re47 (decomp)](https://github.com/0danny/re47) - 《杀手：代号 47》（2000）匹配反编译。
- [HiTMAN Archive Manager](https://www.moddb.com/games/hitman-world-of-assassination/downloads/hitman-archive-manager) - 《杀手》系列 Mod 安装/提取 RPKG 封包的工具（v2 更名为 Hitman Archive Manager）。
- [OpenKH](https://github.com/OpenKH/OpenKh) - 《王国之心》系列全能逆向工具包，处理 MDLX/PMO 模型、PAM/ANB 动画、TXA 纹理、地图、战斗配置、消息等，含 50+ 专用编辑/转换器，支持 KH1/2、BBS、Re:Coded、DDD。
- [AudioMog](https://github.com/Yoraiz0r/AudioMog) - 免费音频 Mod 一体化工具，解/打包游戏音频；为 KH3 制作，也适用《旋律落幕》《FFXV》等。
- [KH2-Worldpoint-Editor](https://github.com/Kite2810/KH2-Worldpoint-Editor) - 编辑《王国之心 2》00Worldpoint.bin。
- [KH2Suite](https://github.com/Truthkey/KH2Suite) - 《王国之心 2/最终混合》Mod 辅助程序套件。
- [KHBBS_EXA_Editor](https://github.com/Truthkey/KHBBS_EXA_Editor) - 《王国之心 生日之睡》EXA 事件编辑器。
- [KH1FM_Toolkit](https://github.com/GovanifY/KH1FM_Toolkit) - 《王国之心 1 Final Mix》Mod 工具。
- [RECOM_Toolkit](https://github.com/GovanifY/RECOM_Toolkit) - 《王国之心 记忆之链 Re》Mod 工具。
- [Gibbed.EFX](https://github.com/gibbed/Gibbed.EFX) - 《最终幻想 XII》《皇家骑士团》EFX 文件工具与代码。
- [BBSPluginNoesis](https://github.com/Truthkey/BBSPluginNoesis) - 适配现代 VS 的《王国之心 生日之睡》Noesis 插件。
- [WOFFington](https://github.com/neptuwunium/WOFFington) - 处理《世界最终幻想》文件的库。
- [heretic](https://github.com/adamrt/heretic) - 《最终幻想 战略版》Mod 工具包。
- [KH-ReCOM-Tools](https://github.com/Murugo/KH-ReCOM-Tools) - 《王国之心 记忆之链 Re》（PS2）实验性工具集。
- [Murugo/Misc-Game-Research (Kingdom Hearts II)](https://github.com/Murugo/Misc-Game-Research/tree/main/PS2/Kingdom%20Hearts%20II%20Final%20Mix) - 《王国之心 2 最终混合》逆向笔记。
- [Murugo/Misc-Game-Research (Musashi: Samurai Legend)](https://github.com/Murugo/Misc-Game-Research/tree/main/PS2/Musashi%20Samurai%20Legend) - 《武藏传：武士传奇》逆向笔记。
- [kh1](https://github.com/ethteck/kh1) - 《王国之心》（PS2 日版）WIP 反编译。
- [noclip.website (Final Fantasy X)](https://github.com/magcius/noclip.website/tree/main/src/FinalFantasyX) - 浏览器版《最终幻想 X》查看。
- [Final Fantasy X HD translation tools](https://www.moddb.com/games/final-fantasy-x/downloads/final-fantasy-x-hd-translation-tools) - 《最终幻想 X HD》（PC）文本/图形提取与导入翻译工具。
- [noclip.website (Kingdom Hearts)](https://github.com/magcius/noclip.website/tree/main/src/KingdomHearts) - 浏览器版《王国之心》查看。
- [noclip.website (Kingdom Hearts II Final Mix)](https://github.com/magcius/noclip.website/tree/main/src/KingdomHearts2FinalMix) - 浏览器版《王国之心 2 最终混合》查看。
- [noclip.website (Dragon Quest VIII)](https://github.com/magcius/noclip.website/tree/main/src/DragonQuest8) - 浏览器版《勇者斗恶龙 8》查看。
- [SlimeMoriMori](https://github.com/onepiecefreak3/SlimeMoriMori) - GBA《勇者斗恶龙 怪兽篇：史莱姆大冒险》自定义压缩格式逆向工具。
- [fptTool](https://github.com/LinkOFF7/fptTool) - 《勇者斗恶龙 7》FPT 文本转换器。
- [kh2mdlx](https://github.com/GovanifY/kh2mdlx) - 《王国之心 2》3D 模型导入/导出。
- [kh2vif](https://github.com/GovanifY/kh2vif) - 《王国之心 2》OBJ→VIF 模型导入器。
- [KH2-Anm-Generator](https://github.com/Kite2810/KH2-Anm-Generator) - 《王国之心 2》自定义角色模型的自动动画过场生成器。
- [Hypercrown](https://github.com/Some1fromthedark/Hypercrown) - 将《王国之心 1》模型转换为通用格式并可转回原生以便打补丁。
- [CrystalEditor](https://github.com/Cuyler36/CrystalEditor) - WiiWare《FF 水晶编年史：吾王之命》存档编辑器。
- [ff7-decomp (decomp)](https://github.com/xeeynamo/ff7-decomp) - 《最终幻想 VII》PS1 匹配反编译。

### Sucker Punch

#### Sly Cooper

- [sly1 (decomp)](https://github.com/TheOnlyZac/sly1) - 《狡狐大冒险：神偷秘籍》（PS2）匹配反编译。
- [SlyTools](https://github.com/VelocityRa/SlyTools) - 《狡狐大冒险》PS2/PS3 研究与 Mod 工具。
- [Sly2ModelRE](https://github.com/froggestspirit/Sly2ModelRE) - 《狡狐大冒险 2》模型格式研究。
- [sly_dec.py](https://github.com/yukinogatari/Reverse-Engineering/blob/573fc1c20796fb40a982f11dfda4039eb480a34e/Sly%20Cooper/sly_dec.py) - 解密《狡狐大冒险》文件的 Python 脚本。
- [PS23DFormat (Sly 2)](https://web.archive.org/web/20160205080914/http://ps23dformat.wikispaces.com/Sly+2+Band+of+Thieves) - 《狡狐大冒险 2》3D 格式存档文档。
- [PS23DFormat Wiki Archive](https://archive.org/details/wiki-ps23dformat.wikispaces.com) - 覆盖 PS2 3D 格式的 PS23DFormat Wiki 全档。
- [SlyCineTrainer](https://github.com/slynders/SlyCineTrainer) - 《狡狐大冒险》系列摄像机动画训练器。

### Supercell

- [SCEditor](https://github.com/ToxicLand/SCEditor) - 创建/编辑 Supercell（部落冲突、皇室战争、荒野乱斗、海岛奇兵）SC 资产，可添加/修改角色、建筑等。
- [SCP-Unpacker](https://github.com/baraklevy20/SCP-Unpacker) - 解包 Supercell 新的 SCP 封包格式。
- [Supercell-Extractor](https://github.com/baraklevy20/Supercell-Extractor) - 高速提取 Supercell 游戏图形的工具。
- [sc-compression](https://github.com/jeanbmar/sc-compression) - Node.js Supercell 资产压缩/解压模块，支持 lzma/sc/sclz/sig/sc2/zstd，自动识别压缩签名。
- [gltf-Supercell-IO](https://github.com/Daniil-SV/gltf-Supercell-IO) - glTF Blender 插件，导入导出 Supercell Odin (.glb)。
- [SupercellFlash](https://github.com/sc-workshop/SupercellFlash) - 处理 Supercell 2D (.sc) 资产的 C++ 库。
- [X-coder](https://github.com/lilmuff2/X-coder) - Supercell SC 文件编码/解码，SC↔PNG，支持 Zstandard/LZMA、ZKTX、批量处理。

### SuperTuxKart

- [STK Blender Addons](https://github.com/supertuxkart/stk-blender) - SuperTuxKart `SPM` 网格与 Antarctica 引擎资产的导入导出插件套件。

### Telltale Games

- [TTG-Tools](https://github.com/zenderovpaulo95/TTG-Tools) - Telltale 游戏翻译/修改工具（[原版](https://github.com/bartlomiejduda/TTG_Tools)），支持 d3dtx↔dds/pvr、位图字体编辑/TTF 导出、ttarch/ttarch2 打包解包、lua/lenc 解密加密等；扩展支持至《萨姆与马克斯》重制、《行尸走肉 终极版》。
  - 游戏：Telltale Texas Hold'em、Bone 系列、Sam & Max 系列、Strong Bad、Wallace & Gromit、猴岛传说、Hector、Puzzle Agent、Poker Night、回到未来、侏罗纪公园、Law & Order、行尸走肉 1/2/Michonne/ANF、TWAU、无主之地传说、权力的游戏、我的世界：故事模式、蝙蝠侠等。
- [Telltale-Texture-Tool](https://github.com/Telltale-Modding-Group/Telltale-Texture-Tool) - Telltale Tool 游戏纹理 Mod GUI，D3DTX ↔ PNG/DDS/TGA 等。
- [Telltale-Script-Editor](https://github.com/Telltale-Modding-Group/Telltale-Script-Editor) - 非官方开源 Telltale 脚本编辑器。
- [D3DMESH-Converter](https://github.com/Telltale-Modding-Group/D3DMESH-Converter) - 将 .d3dmesh 模型与通用格式互转的工具（WIP）。
- [ttarch-docs](https://github.com/Telltale-Modding-Group/ttarch-docs) - Telltale 封档程序化读取文档。
- [IMAP-Editor](https://github.com/Telltale-Modding-Group/IMAP-Editor) - 编辑 Telltale 游戏中 .imap 文件的工具。
- [Unity_WBOX_Editor](https://github.com/Telltale-Modding-Group/Unity_WBOX_Editor) - 基于 Unity 的 `.wbox` 导航网格导入/生成工具。
- [TelltaleToolPaper](https://github.com/LucasSaragosa/TelltaleToolPaper) - 简述 Telltale 文件格式与引擎结构的小论文。
- [TelltaleGames_D3DMesh_Importer](https://github.com/WeaselOnaStick/TelltaleGames_D3DMesh_Importer) - RTB「几乎全能」Blender 模型导入器的重写版（WIP）。

### GSC Game World

#### S.T.A.L.K.E.R

- [Geometry Decompiler plugin for 3dsmax](https://www.moddb.com/games/stalker/downloads/geometry-decompiler-plugin-for-3dsmax) - 将《潜行者》地图几何导入 3ds Max 的插件（适配 7-8，9 未测）。
- [STALKER game archives unpacker](https://www.moddb.com/mods/old-good-stalker-evolution/downloads/stalker-game-archives-unpacker) - 《潜行者》档案解包工具，安装俄文版 Mod 需要。
- [STALKER Extractor](https://www.moddb.com/games/stalker/downloads/stalker-extractor) - 《潜行者》数据库解包器，兼容所有版本，可选择提取文件。
- [LtxParser](https://github.com/JKAnderson/LtxParser) - C# 库，加载《潜行者》系列 .ltx 配置树。
- [S.T.A.L.K.E.R Mod Tool](https://www.moddb.com/games/stalker/downloads/stalker-mod-tool) - 解出 .db 的 Mod 工具，解包后将 gamedata 置于主目录的 gamedata 文件夹。
- [Unpack Pack xr files Stalker (S.T.A.L.K.E.R.: Call of Pripyat)](https://www.moddb.com/games/stalker-call-of-pripyat/downloads/unpack-pack-xr-files-stalker) - 将常用 Pearl 脚本整合成单库，来自 AMK 站点。
- [XRay Exporter v2.03 (S.T.A.L.K.E.R. Shadow of Chernobyl)](https://www.moddb.com/games/stalker/downloads/xray-exporter-v203) - 官方 SDK0.4 导出插件，支持 3ds Max 7–2011、LightWave 7.5/8.0、Maya 7–2010。
- [XRay Exporter v2.03 (S.T.A.L.K.E.R.: Call of Pripyat)](https://www.moddb.com/games/stalker-call-of-pripyat/downloads/xray-exporter-v2031) - SDK 0.5/0.6/0.7 导出插件，支持 3ds Max 8–2011、LightWave 8.0、Maya 7–2010。
- [X-ray game asset tools pack FINAL](https://www.moddb.com/games/stalker/downloads/x-ray-game-asset-tools-pack-final) - 《潜行者》完整资产工具集：AI Wrapper 2.2、几何/模型转换、ACDC all.spawn 编辑、Milkshape/Maya 插件等。
- [Clear Sky: Game Database Unpacker](https://www.moddb.com/games/stalker/downloads/clear-sky-game-database-unpacker) - 解包《晴空》全部文件的工具。
- [STALKER utilities pack](https://www.moddb.com/games/stalker/downloads/stalker-utilities-pack) - 《潜行者》LTX 配置编辑工具包。
- [Updated Milkshape plugin](https://www.moddb.com/games/stalker/downloads/updated-milkshape-plugin) - 更新版 Milkshape 插件（2016-01-08）用于《潜行者》。
- [Database converter (S.T.A.L.K.E.R.: Call of Pripyat)](https://www.moddb.com/mods/call-of-chernobyl/downloads/cop-coc-db-converter) - COP/COC DB→gamedata 转换器。
- [Extractor de archivos para S.T.A.L.K.E.R.: Shadow of Chernobyl](https://www.moddb.com/games/stalker/downloads/extractor-de-archivos-para-stalker-shadow-of-chernobyl) - 轻量级《切尔诺贝利的阴影》全文件提取器。
- [General X Ray SDK CS-CoP Tools (S.T.A.L.K.E.R.: Call of Pripyat)](https://www.moddb.com/games/stalker-call-of-pripyat/downloads/general-x-ray-sdk-tools) - X-Ray SDK 工具合集，含 dds2tgaLE、2011 rev10192 转换、CS/CoP 编译器 2010 v3.0 等。

### Troika Games (Vampire: The Masquerade)

- [Vampire the Masquerade Bloodlines Blender 2.42 plugin](https://www.moddb.com/games/vampire-the-masquerade-bloodlines/downloads/vampire-the-masquerade-bloodlines-blender-242-plugin) - Blender 2.42 插件，导入导出《吸血鬼：避世 血族》MDLx 模型（含 UV）。
- [NOD Noesis Plugin (Vampire: The Masquerade – Redemption)](https://www.moddb.com/games/vampire-the-masquerade-redemption/downloads/nod-noesis-plugin) - 《吸血鬼：避世 救赎》NOD/NAD 模型/动画 Noesis 插件，支持完整导入导出。

### Terminal Reality (Nocturne)

- [NocturneDecomp (decomp)](https://github.com/NearlyTRex/NocturneDecomp) - 《Nocturne》匹配反编译。

#### BloodRayne

- [br2proj](https://github.com/PavelSharp/br2proj) - 《嗜血印 2》Blender 插件，导入 .tex 纹理、.smb 模型、.bfm/.skb 骨骼网格。

### THQ / Rainbow Studios

- [OpenBarnyard (decomp)](https://github.com/InfiniteC0re/OpenBarnyard) - 《开心农场》（Barnyard）及 TOSHI 2.0 引擎匹配反编译。
- [OpenToshi (decomp)](https://github.com/AdventureT/OpenToshi) - 《水母历险记》（de Blob）与 Toshi 引擎匹配反编译。
- [OpenJPOG (decomp)](https://github.com/AdventureT/OpenJPOG) - 《侏罗纪公园：建造历险》与 Toshi v1.0 引擎匹配反编译。

#### Cars

- [carsraceorama](https://github.com/leeao/carsraceorama) - 《赛车总动员 国民赛/赛车场风云》Noesis 插件，导入导出多平台模型：XNG、P3G、GCG、DXG、PSG、SLT。

#### MX vs ATV

- [3ds Export script (MX vs ATV Reflex)](https://www.moddb.com/games/mx-vs-atv-reflex/downloads/3ds-export-script) - 《MX vs ATV Reflex》3ds Max 导出插件。

#### Twisted Metal

- [tm1_decomp (decomp)](https://github.com/abelbriggs1/tm1_decomp) - 《横冲直撞》（PS1 日版）匹配反编译。
- [tmb_decomp (decomp)](https://github.com/abelbriggs1/tmb_decomp) - 《横冲直撞：黑色》（PS2）匹配反编译。
- [tmhc (decomp)](https://github.com/jacobleeharris/tmhc) - 《横冲直撞：海港城》（PS2）匹配反编译。

### 3D Realms

- [BioMenaceDecomp (decomp)](https://github.com/lethal-guitar/BioMenaceDecomp) - 《生化狂人》匹配反编译。
- [cosmore (decomp)](https://github.com/smitelli/cosmore) - 《宇宙奇遇记》匹配反编译（完成 96%）。

#### Duke Nukem 3D

- [Landscaping Tools (Duke Nukem 3D)](https://www.moddb.com/games/duke-nukem-3d/downloads/landscaping-tools) - 《毁灭公爵 3D》地形制作资源与示例地图（用于学习）。
- [Duke Nukem 3D source code](https://www.moddb.com/games/duke-nukem-3d/downloads/duke-nukem-3d-source-code) - 《毁灭公爵 3D》v1.5 源码与编译说明。

#### Duke Nukem: Manhattan Project

- [Duke Nukem Manhattan Project Mesh & Bones Editing Tool](https://www.moddb.com/games/duke-nukem-manhattan-project/downloads/duke-nukem-manhattan-project-mesh-bones-editing-tool) - 《毁灭公爵：曼哈顿计划》官方网格/骨骼编辑器。

#### Duke Nukem Forever (2001)

- [Blender to CPJ Plugin for DNF2001](https://www.moddb.com/mods/dnf2001-restoration-project/downloads/blender-to-cpj-plugin-for-dnf2001) - Blender 导出 DNF2001 专有 CPJ 格式的插件。
- [Updated Blender to CPJ Plugin (Duke Nukem Forever 2001)](https://www.moddb.com/mods/dnf2001-restoration-project/downloads/updated-blender-to-cpj-plugin) - 同上，更新版 CPJ 导出插件。

#### Duke Nukem Forever (2011)

- [MegaPackageExtractor](https://github.com/DaZombieKiller/MegaPackageExtractor) - 《毁灭公爵 永恒》（2011）MegaPackage.dat 解包器。

#### The Outforce

- [Outforce meshes extractor](https://www.moddb.com/games/the-outforce/downloads/outforce-meshes-extractor) - Mesh and model extractor for The Outforce. Created by szkaradek123.
- [The Outforce Box extractor tool](https://www.moddb.com/games/the-outforce/downloads/the-outforce-box-extractor-tool) - *.box archive extractor tool for the game "The Outforce"

### Techland

- [Call of Juarez: Bound In Blood - Map Pak Tool](https://www.moddb.com/mods/cojbib-map-pak-tool/downloads/call-of-juarez-bound-in-blood-map-pak-tool) - Convert CoJBiB custom maps into Pak file with required folder structure by the game. Portable (no installation) just start and create, Enjoy!

### Thekla Inc (The Witness)

- [noclip.website (The Witness)](https://github.com/magcius/noclip.website/tree/main/src/TheWitness) - In-browser The Witness viewer.
- [Braid Editor Universe Tools](https://www.moddb.com/games/braid/downloads/braid-editor-universe-tools) - For information on how to start and use the Braid Universe Tools, make sure you click the link to the official tutorial on ModDB, which you can find after the jump.

### Slitherine / Proxy Studios

- [Blender Gladius Addon v1.1 (Warhammer 40,000: Gladius - Relics of War)](https://www.moddb.com/mods/blender-gladius-addon/downloads/blender-gladius-addon-v11) - The first release. It should mostly work but may still have some bugs.

### Visceral Games (Dead Space, Dante's Inferno)

- [Gibbed.Visceral](https://github.com/gibbed/Gibbed.Visceral) - Tools and code for use with Visceral developed games (Dante's Inferno, Dead Space 2).
- [Noesis-Plugins (Durik256)](https://github.com/Durik256/Noesis-Plugins) - Community Noesis plugins collection including Visceral Games support.
- [MeltyTool (Visceral)](https://github.com/MeltyPlayer/MeltyTool/tree/main/FinModelUtility/Libraries/VisceralGames) - Format viewer/exporter for Visceral Games titles.
- [ZenHAX Thread](https://zenhax.com/viewtopic.php?t=15376) - Forum discussion and research on Visceral Games file formats. *(Link archived/dead)*
- [VisceralToolkit](https://github.com/Greavesy1899/VisceralToolkit) - Set of tools for editing Visceral Games after "The Godfather (2006)" including Dead Space and Dante's Inferno.

### Wargaming (World of Warships)

- [yretenai/Akizuki](https://github.com/neptuwunium/Akizuki/tree/csharp) - World of Warships file format research project.

### Ubisoft

- [rgh (decomp)](https://github.com/rghdecomp/rgh) - Matching decompilation of Rabbids Go Home (2009).
- [Rayman2Lib](https://github.com/szymski/Rayman2Lib) - Various tools for Rayman 2 modding and content extraction.
- [Rayman2FunBox](https://github.com/rtsonneveld/Rayman2FunBox) - Pack of a few fun mods for Rayman 2 on PC using memory editing, notably the First Person Mod.
- [raymap](https://github.com/byvar/raymap) - Map viewer/editor for OpenSpace games including Rayman 2, Rayman 3, Rayman Arena, and Tonic Trouble. Supports multiple platforms (PC, PS1, PS2, N64, GameCube, Xbox, iOS, DS, 3DS). Web version available at raym.app.
- [GangstarVegasTextTool](https://github.com/efimandreev0/GangstarVegasTextTool) - Tool to work with ".lng" archives from Gangstar Vegas games on any platforms.
- [Jormungandr](https://github.com/neptuwunium/Jormungandr) - Anvil Engine research and tools for Ubisoft's Anvil Engine (Assassin's Creed series).
- [Ubitunedec](https://github.com/ldeon/Ubitunedec) - Program for decoding and exporting .SPK audio files found in Ubisoft game .dat files. Can play back and decode sound and music encoded into the game files.
- [Ray1Editor](https://github.com/RayCarrot/Ray1Editor) - 2D game editor derived from Ray1Map for modifying maps in Rayman 1 games. Supports Rayman 1 PS1, PC (multiple versions), Educational, Designer, by his Fans, and 60 Levels versions.
- [CyArchiveTool](https://github.com/Surihix/CyArchiveTool) - Tool to extract and repack the .pack archive files from the PC version of the game Zone of Enders 2 MARS.
- [SabTool](https://github.com/BoBoBaSs84/SabTool) - CLI tool for managing files for The Saboteur.
- [FCI.FAT.Tool](https://github.com/Ekey/FCI.FAT.Tool) - Tool for extracting FAT/DAT archives from Far Cry Instincts.
- [Hawx Model Tool 1.04 (Tom Clancy's H.A.W.X.)](https://www.moddb.com/games/tom-clancys-hawx/downloads/hawx-model-tool-104) - The Original Hawx Modding tool, and the most asked for. This lets you modify the models, All the models in Tom Clancy's hawx. Made by lotsbiss
- [Complete UMP40 Source Code and Assets (Tom Clancy's Rainbow Six 3: Raven Shield)](https://www.moddb.com/mods/raven-shield-software-development-kit/downloads/complete-ump40-source-code-and-assets) - All the source code, textures, and models for Twi's custom UMP40 submachine gun. Great for learning to make custom guns!
- [Damage Triggers - mapping tool (Tom Clancy's Rainbow Six 3: Raven Shield)](https://www.moddb.com/games/tom-clancys-rainbow-six-3-raven-shield/downloads/damage-triggers-mapping-tool) - Mappers can use this simple tool to add damage ability to their triggers. Set it to kill players or tangos nearby, or to damage objects in your map. SOURCE CODE INCLUDED.
- [Flashlights for enemies - mapping tool (Tom Clancy's Rainbow Six 3: Raven Shield)](https://www.moddb.com/games/tom-clancys-rainbow-six-3-raven-shield/downloads/flashlights-for-enemies-mapping-tool) - Mappers can use this simple tool to give flashlights to tangos in their nighttime maps. Flashlights work in singleplayer and multiplayer.
- [.forge extractor/replacer by Turfster (Assassin's Creed)](https://www.moddb.com/mods/aci-texmod-clothes-mod/downloads/forge-extractorreplacer-by-turfster) - Data/files extractor for Assassin's Creed and Assassin's Creed II and some other games using Scimitar engine. It's also capable of replacing archived files, including textures. Its additional plugins are already installed. The program is made by Turfster and it belongs to him (and the full credit...

#### Anno 1800

- [Anno 1800 Mod Loader](https://github.com/magicalcookie/anno1800-mod-loader) - The one and only mod loader for Anno 1800. Supports loading of unpacked RDA files, XML merging, and Python mods.
- [Modding Tools for Anno](https://marketplace.visualstudio.com/items?itemName=JakobHarder.anno-modding-tools) - Visual Studio Code extension with utilities to build Anno 1800 mods.

### Bethesda

*The Elder Scrolls, Fallout series, and Starfield.*

- [BAE](https://www.nexusmods.com/starfield/mods/165) - Bethesda Archive Extractor application for BSA/BA2 archives.
- [BSA Browser](https://github.com/AlexxEG/BSA_Browser) - Bethesda Archive browser and extractor for BSA and BA2 archives.
- [Gibbed.Fallout4](https://github.com/gibbed/Gibbed.Fallout4) - Tools for Fallout 4 file formats.
- [xEdit](https://tes5edit.github.io) - Advanced graphical module editor and conflict detector for Bethesda games.
- [F2 TOOLS PAK BY LEONARDO (Fallout 2)](https://www.moddb.com/games/fallout-2/downloads/f2-tools-pak-by-leonardo) - Toolset for creating Fallout 2 mods. For more information, see Readme.txt in the archive. Archive contains: BIS mapper, Dims mapper, SFall script editor, Notepad++, Frame animator.
- [Fallout2 FRM converter v 2.0](https://www.moddb.com/games/fallout-2/downloads/fallout2-frm-converter-v-20) - Convert Fallout's FRM image files to the BMP, JPG, PNG, TGA, TIF, PBM, PGM and PPM files formats, and then convert BMP, TIF and PNG files back into FRM's! Use your own art in Fallout....
- [Wrye Bash](https://wrye-bash.github.io) - Swiss army knife for modding Bethesda games with features including mod installation, conflict manager, load order manager and automatic merging.
- [Synthesis](https://github.com/Mutagen-Modding/Synthesis) - Framework and GUI to empower people to create mods via code instead of by hand, mainly used to create patches.
- [Spriggit](https://github.com/Mutagen-Modding/Spriggit) - Tool to facilitate converting Bethesda plugin files to a text based format that can be stored in Git.
- [ck-cmd](https://github.com/aerisarn/ck-cmd) - Command-line helper for executing some Creation Kit/Engine commands.
- [hkxc](https://www.nexusmods.com/skyrimspecialedition/mods/126214) - CLI tool to convert between x86/x64 HKX and XML animation files.
- [HKX Conversion Tool](https://www.nexusmods.com/skyrimspecialedition/mods/128839) - hkxc Windows GUI for converting between HKX and XML animations files.
- [hkxPoser](https://www.nexusmods.com/skyrimspecialedition/mods/11783) - .hkx animation file editor.
- [DDS Texture Converter](https://www.nexusmods.com/skyrimspecialedition/mods/111378) - Application for bulk conversion and resizing of DDS textures.
- [DDS Texture Scanner](https://github.com/niston/TextureScan) - Application scanning for DDS textures with abnormal dimensions.
- [nifxml](https://github.com/niftools/nifxml) - Repository for the nif.xml file, which contains the NIF file format description for NetImmerse/Gamebryo NIF model format used in Elder Scrolls and Fallout games.
- [NifTools Blender Addon](https://github.com/niftools/blender_niftools_addon) - Blender add-on to enable import and export of NetImmerse file formats including .nif, .kf, and .egm used in Elder Scrolls and Fallout games.
- [PyNifly](https://github.com/BadDogSkyrim/PyNifly) - Export/import tools between Blender and the NIF format, using Bodyslide/Outfit Studio's Nifly layer. Supports Skyrim LE, Skyrim SE, Fallout 4, Fallout New Vegas, Fallout 76, and Fallout 3.
- [Material-Editor](https://github.com/ousnius/Material-Editor) - Small UI application to edit BGSM/BGEM material files used in Bethesda games.
- [noclip.website (Morrowind)](https://github.com/magcius/noclip.website/tree/main/src/Morrowind) - In-browser Morrowind viewer.
- [Daggerfall utilities](https://www.moddb.com/games/daggerfall/downloads/daggerfall-utilities) - Archive of tools for the DOS version of Daggerfall, including quest editing tools and character modification tools.
- [ES Plugin Cracker 0.001b (Elder Scrolls IV: Oblivion)](https://www.moddb.com/games/oblivion/downloads/es-plugin-cracker-0-001b) - Rudimentary Win32 application for loading plugins authored with a higher Construction Set version (v0.001b).
- [BodySlide and Outfit Studio](https://github.com/ousnius/BodySlide-and-Outfit-Studio) - Tool to convert, create, and customize outfits and bodies for Bethesda games.
- [Cathedral Assets Optimizer](https://www.nexusmods.com/skyrimspecialedition/mods/23316) - Tool to automatically optimize BSAs, meshes, textures and animations for Bethesda games.

### 2K Games / Firaxis Games

- [Civilization IV Plugins for 3DS Max 6](https://www.moddb.com/games/civilization-iv-original/downloads/civilization-iv-plugins-for-3ds-max-6) - Official plugin for 3DS Max 6 with support for 3D models used in Sid Meier's Civilization IV.
- [Civilization IV Plugins for 3DS Max 7+](https://www.moddb.com/games/civilization-iv-original/downloads/civilization-iv-plugins-for-3ds-max-7) - Official plugin for 3DS Max 7 and newer with support for 3D models used in Sid Meier's Civilization IV.

### 2K Czech / Illusion Softworks

- [mafia-re (decomp)](https://github.com/Marvisak/mafia-re) - Matching decompilation of Mafia: The City of Lost Heaven.
- [Max4dsTools](https://github.com/pudingus/Max4dsTools) - 3ds Max plugin for import and export of the 4ds model format used in Mafia: The City of Lost Heaven. Supports meshes, LODs, billboarding, sectors, portals, skinned models, materials, and glows.
- [mafia-formats](https://github.com/RoadTrain/mafia-formats) - 010 Editor templates for Mafia: The City of Lost Heaven file formats. Also partly for Hidden & Dangerous 2 and Wings of War.
- [EffectsBinEditor](https://github.com/legion2809/EffectsBinEditor) - Effects.bin editor for Mafia: The City of Lost Heaven written in C# (WPF application). Program to add or remove particle effects from a particular mission.

### Natsume (Harvest Moon)

- [hm64-decomp (decomp)](https://github.com/harvestwhisperer/hm64-decomp) - Matching decompilation of Harvest Moon 64 (N64).
- [hmawl (decomp)](https://github.com/ChrisNonyminus/hmawl) - Matching decompilation of Harvest Moon: A Wonderful Life (GameCube).

### Falcom (Ys)

- [YsViDecomp (decomp)](https://github.com/GrantBenR/YsViDecomp) - Matching decompilation of Ys VI (Steam).

### Working Designs (Lunar)

- [lunar2-psx-decomp (decomp)](https://github.com/Zackmon/lunar2-psx-decomp) - Matching decompilation of Lunar 2: Eternal Blue Complete (PS1).

### Toby Fox (Undertale)

- [UndertaleDecomp (decomp)](https://github.com/kittibyte/UndertaleDecomp) - Matching decompilation of UNDERTALE (Xbox One v1.13X).

### Terry Cavanagh

#### VVVVVV

- [extract.vvv](https://github.com/Swyter/extract.vvv) - Simple program to extract original music from VVVVVV game. Extracts all 15 tracks from `vvvvvvmusic.vvv` files and outputs them as OGG Vorbis format.

### Studio MDHR (Cuphead)

- [cuphead-decomp (decomp)](https://github.com/jmxamongusmodder/cuphead-decomp) - Matching decompilation of Cuphead.

### TaleWorlds Entertainment

#### Mount&Blade

- [mab-tools](https://github.com/Swyter/mab-tools) - 010 Editor binary templates for Mount&Blade 1.011 and Warband file formats. Includes templates for `.brf` (Binary Resource File), `.sco` (Scene Object), `options.dat` (gameplay and graphics settings including battle size), `controls.dat` (keymapping with support for two assignable key slots per action), and `sg*.sav` savegame files.
- [cartographer](https://github.com/Swyter/cartographer) - Mount&Blade strategic map editor. Allows real-time positioning of world parties/cities. Supports importing/exporting OBJ files, editing map.txt and module_parties.py, with first-person camera controls and terrain visualization.

### TT Games (LEGO Island)

- [isle (decomp)](https://github.com/isledecomp/isle) - Matching decompilation of LEGO Island (1997).
- [Lego-City-Undercover-Decompilation (decomp)](https://github.com/Nintendocustom/Lego-City-Undercover-Decompilation) - Matching decompilation of Lego City Undercover.
- [BionicleHeroesTools](https://github.com/REDxEYE/BionicleHeroesTools) - Blender plugin for importing Bionicle Heroes files. Supports NUP and HGP model formats and PAK archive extraction. Requires Blender 3.1 to 3.5.
- [LegoTools](https://github.com/REDxEYE/LegoTools) - Tools for working with LEGO game file formats.

### Acclaim Entertainment (Turok)

- [turok3 (decomp)](https://github.com/Drahsid/turok3) - Matching decompilation of Turok 3: Shadow of Oblivion (N64).

### Whoopee Camp (Tomba!)

- [psx_tomba (decomp)](https://github.com/hansbonini/psx_tomba) - Matching decompilation of Tomba! (PS1, 100%).

### Team Shanghai Alice (Touhou)

- [ReC98 (decomp)](https://github.com/nmlgc/ReC98) - Matching decompilation of Touhou PC-98 games (74% complete).

### 5th Cell

- [locksmith (decomp)](https://github.com/redraincatching/locksmith) - Matching decompilation of Lock's Quest.

### Asmik Ace Entertainment (LSD: Dream Emulator)

- [lsddecomp (decomp)](https://github.com/FirecatFG/lsddecomp) - Matching decompilation of LSD: Dream Emulator (PS1).

### Stainless Games (Carmageddon)

- [dethrace (decomp)](https://github.com/dethrace-labs/dethrace) - Matching decompilation of Carmageddon (1997).

### Gumi (Brave Frontier)

- [client (decomp)](https://github.com/decompfrontier/client) - 《勇者前线》客户端匹配反编译。

### Ninja Kiwi (Bloons TD)

- [BTD5-Decomp (decomp)](https://github.com/NKHook/BTD5-Decomp) - 《气球塔防 5》匹配反编译。

### Eutechnyx (Ford Racing)

- [Gt2 (decomp)](https://github.com/dashr9230/Gt2) - 《福特赛车》（2000）匹配反编译。
- [Caper (decomp)](https://github.com/dashr9230/Caper) - 《偷天换日》（2001）匹配反编译。

### Eurocom

- [eurochef](https://github.com/eurotools/eurochef) - Eurocom EngineX(T) Rust 工具/库，支持贴图、实体、地图提取、filelist 重打包、EDB→Euroland4 反编译及 Blender 插件。
  - 游戏：Sphinx Demo、吸血鬼猎人巴菲、被诅咒的木乃伊、Spyro: A Hero's Tail、机器人总动员、Concrete Jungle、蝙蝠侠开战时刻、冰川时代 2/3、加勒比海盗 3、特务小强、蜘蛛侠 4、007 等。
  - 格式：EDB、ELX、SFX、filelist(v4–v10)；平台：PC/Xbox/X360/NGC/Wii/PS2。
- [eurosound-editor](https://github.com/eurotools/eurosound-editor) - 复刻 EuroSound 的 .NET EngineX 音频编辑器。
- [eurosound-explorer](https://github.com/eurotools/eurosound-explorer) - 查看与提取 Eurocom SFX 音频的 C# 工具。
- [eurotext](https://github.com/eurotools/eurotext) - 编辑/查看 EngineX 文本表格的工具。
- [binary-templates](https://github.com/eurotools/binary-templates) - EDB/SFX 等 010 模板。
- [hashcodes](https://github.com/eurotools/hashcodes) - Eurocom 游戏哈希列表。
- [blender-addon](https://github.com/eurotools/blender-addon) - Blender 导入导出 Eurocom .ESE（模型/皮肤/动画/相机/脚本）。
- [euroland_exporters](https://github.com/eurotools/euroland_exporters) - 同上，ESE 进/出，含地图与脚本。
- [euroland-elf-texture-extractor](https://github.com/eurotools/euroland-elf-texture-extractor) - 提取随机 EuroLand *.elf 纹理（针对无法直接用 EuroLand.exe 的版本）。
- [sphinx-savegame-editor](https://github.com/eurotools/sphinx-savegame-editor) - 《斯芬克斯与被诅咒的木乃伊》存档编辑器。
- [sphinxtools](https://github.com/Swyter/sphinxtools) - NGC 版《斯芬克斯》解包与 Mod 工具，含 EDB/SFX 模板与 IMA ADPCM 音频分离。
- [gforce-tools](https://github.com/Swyter/gforce-tools) - 新版 EngineX 模板与 Filelist 提取脚本（支持版本 7，覆盖 Athens 2004、Spyro、Robots、Predator、蝙蝠侠、冰川时代、加勒比海盗 3、木乃伊 3、007：量子危机、特务小强、死亡空间：解放、蜘蛛侠 4 原型、黄金眼 007）。

### Hasbro Interactive (Frogger)

- [frogger-psx (decomp)](https://github.com/HighwayFrogs/frogger-psx) - 《青蛙过河》（1997，PS1，100%）匹配反编译。

### H2O Entertainment (Aidyn Chronicles)

- [aidyn (decomp)](https://github.com/blackgamma7/aidyn) - 《艾丁编年史：第一法师》（N64）匹配反编译。

### Bohemia Interactive

- [BI Editing Tools 2 (ARMA 2)](https://www.moddb.com/games/arma-2/downloads/bi-editing-tools-2) - 《武装突袭 2》官方全套编辑工具（安装会覆盖 Arma1 旧版工具，用户数据不受影响，不能用来打包 Arma1 内容）。

### Bugbear Entertainment (FlatOut)

- [bfstool](https://github.com/xNyaDev/bfstool) - 处理 BFS（Bugbear File System）封包的工具。
  - 游戏：FlatOut 1/2/Head On、Ultimate Carnage、Rally Trophy、Tough Trucks、Sega Rally Revo 等。
  - 格式：.bfs（BFS v1/v2，zlib 压缩）。
  - 功能：列出/提取/创建封包，glob 过滤，未知文件 CRC32/MD5/SHA1 校验，压缩优化。
- [FlatOutW32BGMTool](https://github.com/gaycoderprincess/FlatOutW32BGMTool) - 处理 FlatOut 系列 .w32（赛道）/.bgm（车辆）文件的工具。
  - Games: FlatOut 1/2/Ultimate Carnage, Rally Trophy, Tough Trucks.
  - Formats: .w32 (maps/tracks), .bgm (vehicles), .fbx (import/export), collision (.cdb.gen).
  - Features: Export/import FBX、格式转换（FO2↔FO1、FOUC↔其它）、赛道编辑、材质/着色器导出、BVH 区域修改。
- [blender_flatout2_trackai_importer](https://github.com/gmazy/blender_flatout2_trackai_importer) - Blender addon for importing trackai.bin files from FlatOut 2.
- [xnya game-mods cryptutil collection](https://github.com/xNyaDev/game-mods) - Encryption key dumping utilities for BugBear games (in *_cryptutil directories).
  - `xnya_rallytrophy_cryptutil`: Dump encryption keys from Rally Trophy for decrypted execution.
  - `xnya_retrodemo_cryptutil`: Dump encryption keys from Bugbear Retro Demo 2002 for decrypted execution.
  - Integration: Works with bfstool for archive handling.

### Bugbear Entertainment (Team6 Engine - FlatOut 3)

- [team6tool](https://github.com/ermaccer/team6tool) - Tool for extracting models and textures from Team6 engine games.
  - Games: FlatOut 3, ESR, Pizza Dude (Team6 engine v2 only).
  - Formats: .dcm (models), .dct (textures, exports as DDS).
  - Features: 提取载具/角色/物件到 OBJ，保留材质（不含环境贴图）。

### Blizzard Entertainment (World of Warcraft)

- [wow.export](https://github.com/Kruithne/wow.export) - 《魔兽世界》模型/贴图导出工具集。
- [WoWDBDefs](https://github.com/wowdev/WoWDBDefs) - 《魔兽世界》客户端 DBD 定义，用于数据提取。
- [OWLib](https://github.com/overtools/OWLib) - 提取《守望先锋》模型/地图/文件的 DataTool。
- [noclip.website (World of Warcraft - Vanilla, The Burning Crusade, Wrath of the Lich King)](https://github.com/magcius/noclip.website/tree/main/src/WorldOfWarcraft) - 浏览器版《魔兽世界》（旧世/燃烧/巫妖王）查看。
- [3DS/Obj MDX Converter](https://www.moddb.com/games/warcraft-iii/downloads/3ds-obj-mdx-converter) - 《魔兽争霸 III》MDX↔3DS/OBJ 转换。
- [Starcraft Modding Tools](https://www.moddb.com/games/starcraft/downloads/starcraft-modding-tools) - 《星际争霸》四件套 Mod 工具（Arsenal III 等）教程所用文件。
- [WoW Model Viewer 5.0.7 (World of Warcraft)](https://www.moddb.com/games/world-of-warcraft/downloads/wow-model-viewer-5-0-7) - 《魔兽世界》3D 模型查看器，显示游戏数据中的生物、角色、特效、物件、物品等。
- [Blizzard DATA unpacker (Warcraft: Orcs & Humans)](https://www.moddb.com/games/warcraft-orcs-humans/downloads/blizzard-data-unpacker) - 解包暴雪老游戏 DATA 封档（魔兽争霸1、黑荆棘、维京人等，部分文件或损坏），附 C 源码。

### Westwood Studios / EA Los Angeles

- [Command & Conquer: Renegade (source release)](https://github.com/electronicarts/CnC_Renegade) - 《C&C 叛逆者》官方源码与工具（存档，GPLv3 附加条款）。
  - 工具：Level Edit（关卡编辑器）、FDS（独立服务器）。
  - 依赖：DirectX 8+、RAD Bink、RAD Miles、NvDXTLib、Umbra、GameSpy、SafeDisk API、Microsoft Cab、RTPatch、Lightscape。
- [C&C big extractor](https://www.moddb.com/groups/tiberium-essence-fans/downloads/cc-big-extractor) - 提取 C&C BIG 封包，支持将军/资料片、泰伯利亚之战、红警3/起义、泰伯利亚黄昏等。
- [Command & Conquer 3 Asset Extractor](https://www.moddb.com/groups/tiberium-essence-fans/downloads/command-conquer-3-asset-extractor) - 《C&C3》资产提取器，可解出模型（W3DAnimation/Collision/Container/Hierarchy/Mesh）、纹理、音频等。

### Mojang Studios

- [NBTSerializer](https://github.com/gigaherz/NBTSerializer) - 《Minecraft》NBT 序列化库。

### Grasshopper Manufacture (No More Heroes, Killer7)

- [No-More-RSL](https://github.com/Timo654/No-More-RSL) - Grasshopper .RSL 封包解/打包器，适用于大多数该格式的作品（如《英雄不再》《杀手 7》）。

### Free Radical Design (TimeSplitters)

- [tspak](https://github.com/OpenRadical/tspak) - 提取《时空分裂者》.pak 的小工具，支持 P4CK（1&2 PS2）、P5CK（未来完美）、P8CK（2 NGC/Xbox）。

### Enhance Games (Rez)

- [Rezun](https://github.com/XAYRGA/Rezun) - 解包《Rez Infinite》.dat/.bnk。

### Gravity (Ragnarok Online)

- [libgrf](https://github.com/cmbasnett/libgrf) - 读取《仙境传说》GRF 封包的库。
- [grf-python](https://github.com/cmbasnett/grf-python) - libgrf 的 Python 封装。

### Her Interactive (Nancy Drew)

- [AVFExt](https://github.com/puggsoy/AVFExt) - Her Interactive（特别是《南希·德鲁》系列）AVF 转换/提取器。

### HeroForge (HeroForge)

- [HeroForge_parser](https://github.com/REDxEYE/HeroForge_parser) - 解析 HeroForge 角色 CKB 文件的库。
- [HeroBuilder](https://github.com/REDxEYE/HeroBuilder) - 将 HeroForge 角色导入 Blender 的插件（使用导出的 CKB）。

### Yostar / Revived Witch

- [unneko](https://github.com/lico-n/unneko) - 《复苏的魔女》nekodata 提取工具，支持正式与补丁文件。

### CyberStep (CosmicBreak)

- [CB.KAR.Tool](https://github.com/Ekey/CB.KAR.Tool) - 《宇宙激战》KAR 封包提取工具。

### Firesprite (Run Sackboy! Run!)

- [RSBR.PAK.Tool](https://github.com/Ekey/RSBR.PAK.Tool) - 《Run Sackboy! Run!》安卓/iOS PAK(OBB) 解包。

### Bandai Namco (Dragon Ball)

- [binunpack](https://github.com/shibbo/binunpack) - Python3 编写的《龙珠：比克大魔王的复仇》BIN 封包解包。
- [DBFModToolCollection](https://github.com/Tiniifan/DBFModToolCollection) - 《龙珠 融合》Mod 工具合集，处理游戏文件与封包。
- [C&C: Renegade Official Modding Tools](https://www.moddb.com/games/cc-renegade/downloads/cc-renegade-official-modding-tools) - 《C&C 叛逆者》官方 Mod 工具。
- [CnC Renegade Tools](https://www.moddb.com/games/cc-renegade/downloads/cnc-renegade-tools) - Westwood 发布的《叛逆者》Mod 工具。
- [Final Big (C&C: Generals)](https://www.moddb.com/games/cc-generals/downloads/final-big) - 《C&C 将军》BIG 封包工具。
- [Final Big 3 (C&C: Generals)](https://www.moddb.com/games/cc-generals/downloads/final-big-3) - 《C&C 将军》Final Big 3（v0.2，2003-03-05）。
- [Gmax+RenX+Renegade Public Tools (C&C: Generals Zero Hour)](https://www.moddb.com/games/cc-generals-zero-hour/downloads/gmaxrenxrenegade-public-tools) - 《将军 绝命时刻》Gmax/RenX/叛逆者 三件套建模工具。

## 🔗 Related Lists

- [Awesome Modding](https://github.com/loicreynier/awesome-modding.bak) - 游戏 Mod 与自定义资源列表。
- [Awesome Game Decompilations](https://github.com/CharlotteCross1998/awesome-game-decompilations) - 精选游戏反编译项目列表。
- [Awesome Game Datasets](https://github.com/leomaurodesenv/game-datasets) - 游戏研究数据集与资源。
- [Awesome Reverse Engineering](https://github.com/tylerha97/awesome-reversing) - 逆向工程资源列表。
- [Awesome Software Reverse Engineering](https://github.com/ReversingID/Awesome-Reversing/blob/master/_software.md) - 逆向工程软件与工具大全。
- [Awesome Gamedev](https://github.com/ellisonleao/magictools) - 游戏开发资源精选。

## 📄 License

[CC0](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，你可以自由复制、修改、分发本项目内容而无任何版权/相关权利限制。

## 🙏 Acknowledgments

致谢 [MeltyPlayer/awesome-game-file-formats](https://github.com/MeltyPlayer/awesome-game-file-formats) 原作者，本仓库为其 fork 的汉化与补充版。


