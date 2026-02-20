# CHIP-8 Emulator (C++ / SDL2)

A fully functional CHIP-8 emulator written in modern C++ using SDL2 for rendering and input handling.

This project emulates the original CHIP-8 virtual machine, including full opcode implementation, ROM loading, rendering, and keyboard input mapping.

---

## Features

- Complete CHIP-8 CPU implementation
- Function pointer opcode dispatch table
- 4KB memory model
- Stack & subroutine support
- Timers (delay & sound)
- SDL2-based rendering
- Keyboard input mapping
- Configurable cycle delay and window scaling

---

## Controls

The CHIP-8 keypad is mapped to your keyboard as follows:

| CHIP-8 | Keyboard |
|---------|----------|
| 1 2 3 C | 1 2 3 4 |
| 4 5 6 D | Q W E R |
| 7 8 9 E | A S D F |
| A 0 B F | Z X C V |

---

## Build Instructions (Linux)

Make sure SDL2 is installed:

```bash
sudo apt install libsdl2-dev

```

I followed Austin Morians site for this - https://austinmorlan.com/posts/chip8_emulator/
