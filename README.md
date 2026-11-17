<div align="center">

<img src="docs/banner.png" alt="PIXBIT" width="100%"/>

### Don't just play games. Build them.

**An open-source ESP32 handheld game console made for learning: solder it, code it, play it, then build your own games, robots and gadgets on the same hardware.**

![ESP32](https://img.shields.io/badge/ESP32-WROOM-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Open hardware](https://img.shields.io/badge/open-hardware-0ea5e9?style=for-the-badge)
![STEM](https://img.shields.io/badge/STEM-education-8b5cf6?style=for-the-badge)
![Status](https://img.shields.io/badge/status-hardware%20v1-f59e0b?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge)

</div>

---

## 🔥 Why it hits different

- 🎮 **A real console you build yourself:** solder the board, flash the firmware, play.
- 🧠 **Learn embedded by making games:** buttons, display, audio and SD card, all yours to program.
- 🔓 **Fully open:** schematic, PCB and firmware live right here.
- 🏫 **Made for classrooms and clubs:** the first embedded project people actually finish.

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

---

<div align="center">

### If this made you go *"wait, that's sick"* 👀

**Drop a ⭐ so more builders find it, and share it with someone who'd build one.**

[![Share on X](https://img.shields.io/badge/share%20on-X-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/intent/tweet?text=An%20open-source%20ESP32%20handheld%20you%20solder%2C%20code%20and%20play%20%F0%9F%8E%AE&url=https%3A%2F%2Fgithub.com%2FPrateek-elec%2FPIXBIT)
[![Share on LinkedIn](https://img.shields.io/badge/share%20on-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/sharing/share-offsite/?url=https%3A%2F%2Fgithub.com%2FPrateek-elec%2FPIXBIT)
[![Follow](https://img.shields.io/badge/follow-@Prateek--elec-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Prateek-elec)

</div>
