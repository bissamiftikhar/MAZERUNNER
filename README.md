# Maze Runner Game (Assembly Language - IAPX88)

This is a text-based maze game developed in Assembly Language using the IAPX88 instruction set. It runs in 16-bit real mode and is compatible with **DOSBox** or any 8086 emulator. The game features maze rendering, a scoring and lives system, random number generation, and a side menu with player stats.

## 🎮 Game Features

- 🧱 Fully rendered maze using video memory (`0xB800`)
- 👤 Display of Player Name and Score
- 💓 Lives and Timer display
- 🪙 Random treasure placement
- 🎉 Win and Game Over screens
- 🦸‍♂️ Secret “SUPERMAN MODE” activated upon winning
- 🎓 Developed as part of Assembly Language coursework

## 🛠️ Technologies Used

- Assembly Language (8086)
- DOSBox (for running/testing)
- BIOS Interrupts (`INT 1Ah` for system time)
- Direct video memory manipulation (`0xB800` segment)
- Procedural programming with subroutines

## 📁 File Structure

