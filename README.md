<div align="center">

# PIXBIT

### Don't just play games. Build them.

**An open-source ESP32 handheld game console made for learning: solder it, code it, play it, then build your own games, robots and gadgets on the same hardware.**

![ESP32](https://img.shields.io/badge/ESP32-WROOM-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Open hardware](https://img.shields.io/badge/open-hardware-0ea5e9?style=for-the-badge)
![STEM](https://img.shields.io/badge/STEM-education-8b5cf6?style=for-the-badge)
![Status](https://img.shields.io/badge/status-hardware%20v1-f59e0b?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge)

<img src="images/pixbit-hero.png" width="85%" alt="PIXBIT handheld console"/>

</div>

---

## Why PIXBIT

Students usually learn coding, electronics and PCB design in separate classes and never see how they fit together. PIXBIT puts all of it in one device people actually want to use: a game console. You learn embedded programming by writing games, electronics by reading the board you're holding, and hardware design by modifying the open schematic.

**Built for** students, makers, educators, robotics clubs and anyone who wants their first real embedded project to be fun.

## Hardware (v1)

<table>
<tr>
<td width="50%"><img src="images/pcb-3d-render.png" alt="PIXBIT PCB 3D render"/><br/><sub>PCB 3D render</sub></td>
<td width="50%"><img src="images/pcb-layout.png" alt="PIXBIT PCB layout, 160 × 75 mm"/><br/><sub>Layout: 160 × 75 mm, 2 layers</sub></td>
</tr>
</table>

- **ESP32 module** with Wi-Fi + Bluetooth, for multiplayer and wireless projects
- **Color display** via FPC connector
- **D-pad + 2 action buttons**, plus 2 menu buttons
- **USB-C** for charging and programming
- **Battery-powered** with a power switch
- **microSD slot** for games and assets
- **Speaker** for audio
- **Expansion connector** for sensors and modules
- Status LEDs and a reset button

Full schematic: [`HARDWARE/pixbit-schematic-v1.pdf`](HARDWARE/pixbit-schematic-v1.pdf)

## Repository layout

```text
HARDWARE/   Schematic and hardware notes
FIRMWARE/   Firmware (in progress)
images/     Renders used in this README
```

## Roadmap

- [x] Schematic v1
- [x] PCB layout v1
- [ ] Gerbers + BOM for ordering
- [ ] Bring-up firmware: display, buttons, audio, SD card
- [ ] Starter game library + "write your first game" tutorial
- [ ] Lesson plans for classrooms

## Get involved

PIXBIT is developed in the open. Ideas, firmware, games and lesson plans are all welcome:

- ⭐ **Star the repo** to follow progress
- 💡 [Open an issue](https://github.com/Prateek-elec/PIXBIT/issues) with a feature idea or a game you'd build
- 🔧 Send a pull request

## License

[MIT](LICENSE) © Prateek Sarkar
