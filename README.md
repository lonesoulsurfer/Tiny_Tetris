# Tiny Tetris: pocket Tetris on an ATtiny85

Tiny Tetris is a pocket-size Tetris game. It uses an ATtiny85 microcontroller and a small SSD1306 OLED screen.

![Tiny Tetris](https://github.com/user-attachments/assets/c730171b-4f79-44d4-ad87-c4a1735abb3c)

## Build guide and video

- Step-by-step build guide on Instructables: [Tiny Tetris - ATtiny85 Project](https://www.instructables.com/Tiny-Tetris-ATtiny85-Project/)
- How to make a programmer for the ATtiny85: [Programmer for ATtiny 85](https://www.instructables.com/Programmer-for-ATtiny-85/) (and the [ATtiny_85_Programmer](https://github.com/lonesoulsurfer/ATtiny_85_Programmer) repository)
- Video on YouTube: [Tiny Tetris](https://www.youtube.com/watch?v=bwNg85aia90)

## What you need

### Hardware

- All parts are in the [parts list](Parts%20List.pdf).
- The schematic is [Schematic.png](Schematic.png). The board layout is [Board.png](Board.png).
- The Gerber files for the PCB are in [Gerber Files](Gerber%20Files/). You can send them to a PCB maker.

### Software

- Arduino IDE, with ATtiny85 support
- A programmer for the ATtiny85

You do not need to install libraries. The sketch uses only standard Arduino and AVR files.

## Program the ATtiny85

The Instructables guide above shows each step of the programming, with photos. In short:

1. Open `Arduino Sketch/ATtiny-Tetris-Gold/ATtiny-Tetris-Gold.ino` in the Arduino IDE.
2. Put the ATtiny85 in your programmer.
3. Set the board and programmer settings that the guide tells you.
4. Click **Sketch → Upload Using Programmer**.

## How to play

Before the game starts:

- Hold **DROP** to turn the "ghost" piece on or off.
- Hold **DROP** and **ROTATE** together to turn "challenge mode" on or off.

## Files in this repository

| Folder or file | Contents |
|----------------|----------|
| `Arduino Sketch/ATtiny-Tetris-Gold/` | Game code |
| `Eagle Files/` | Eagle files for the PCB |
| `Gerber Files/` | Gerber files for the PCB, ready to order |
| `Parts List.pdf` | Parts list |
| `Schematic.png`, `Board.png` | Schematic and board layout |

## Credits

- Game code: **ATtiny Tetris Gold** by Andy Jackson, Anthony Russell, Tobozo, Neven Boyanov and Jarosław Mazurkiewicz. More information: [jm.iq.pl/tetris](https://jm.iq.pl/tetris).
- PCB and build: Marcus ([lonesoulsurfer](https://github.com/lonesoulsurfer)).

## Support

Do you like this project? You can support my work on [GitHub Sponsors](https://github.com/sponsors/lonesoulsurfer).

## Licence

- **Hardware** (PCB, Gerber files and schematic): [CERN Open Hardware Licence v2, Strongly Reciprocal](LICENSE).
- **Game code:** the terms of the original authors. You may use it for **non-commercial** purposes only.
- [LICENSING.md](LICENSING.md) gives the details.
