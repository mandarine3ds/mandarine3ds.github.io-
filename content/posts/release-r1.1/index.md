+++
author = "Mandarine Team"
title = 'Mandarine 1.1'
date = 2025-01-28
description = "Release notes for version r1.1"
+++

- PC: Changed how pausing the emulator is handled to allow frame  (@OpenSauce04)
- Android: Implemented custom layout customization GUI (@DavidRGriswold)
- Code/CI: Update to Clang 18
- PC: Flatpak shortcut creation fixes  (@OpenSauce04, this for future flatpak implementation)
- externals: update submodules
- shader_jit_a64: Optimize conditional tests (@Wunkolo)
- Android: Some UI rebrands
- Android: Fix padding if settings UI is too small
- PC: Numerous fixes for hotkey shortcuts (@OpenSauce04)
- qt: Fix default language not being set to the main one the system uses (@kleidis)
- Android: Add static theme option (@kleidis)
- GSP_GPU: Do not always debug GXCommandProcessed on TriggerCmdReqQueue 
- gradle: update some dependencies 
- PC: Rebrand Report Compatibility to Report Issues 
- Android: Implement support for automatic resolution scale
- Android & PC: Rebrand Custom CPU Ticks names (A config reset is suggested here)
- Android & PC: Add Steps per hour system setting (@szdarkhack)
- vk_stream_buffer: Refactor Vulkan stream buffer memory type selection (@i0x404)
- act: Add more command names and implement GetErrorCode (@DaniElectra)
- core: Remove some usages of global system instace by PLGLDR port (@raphaelthegreat)
- Android & PC: Added Reverse Side by Side Sterioscopic 3D mode (@OpenSauce04)
- Android: Fix pause emulator button crashing the emulator
- shader_jit_a64: Compact host executable memory (@Wunkolo)
- Code: Apply another minimal updates and improvements
- ---

Android multiplayer is actually being worked on (WIP). If you wanna help, check multiplayer branch.
