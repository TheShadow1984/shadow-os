# Shadow-OS
A custom OS fully written in Rust

## Introduction
This will be an operating system written in Rust. It is designed to explore low-level programming and hardware interaction, and to be independent of larger systems. It features a minimal kernel and basic input/output. The project's main focus is learning and experimentation, with plans to add more advanced features in the future. A custom desktop environment may be added later.

## Core / Essential Tasks
- [ ] Set up Rust OS project with `bootloader` crate
- [ ] Implement kernel entry point (`kernel_main`)
- [ ] Initialize VGA text output
- [ ] Implement basic printing macros (`println!`)
- [ ] Implement panic handler
- [ ] Set up memory management (basic paging)
- [ ] Implement simple keyboard driver
- [ ] Implement basic input event loop
- [ ] Implement simple window structure
- [ ] Implement desktop manager for window handling
- [ ] Create initial mini-apps:
  - [ ] Terminal
  - [ ] Clock
  - [ ] Notes app
- [ ] Set up build and test workflow (cargo + qemu)
- [ ] Add README and LICENSE files
- [ ] Ensure OS boots reliably in QEMU

## Future Features / Optional Enhancements
- [ ] Add frame buffer graphics support
- [ ] Implement mouse support
- [ ] Add color and basic UI elements for windows
- [ ] Implement multitasking / scheduler
- [ ] Expand desktop environment:
  - [ ] Custom window manager
  - [ ] Icons and desktop layout
  - [ ] Simple file explorer
  - [ ] App launcher
- [ ] Networking support (TCP/IP stack)
- [ ] Persistent storage / file system support
- [ ] Sound output / basic audio support
- [ ] Hardware abstraction improvements for ESP microcontrollers
- [ ] Add more mini-apps (calculator, editor, games)
- [ ] Optimize performance and memory usage
- [ ] Documentation for kernel APIs and app development


## License Information
© 2026 Shadow – All Rights Reserved

This project is for demonstration purposes and for learning only.
Do not copy, modify, or redistribute any part of this code without permission.
