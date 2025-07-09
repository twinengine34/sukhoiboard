# Sukhoi Board

Sukhoi Board is a 40% ortholinear mechanical keyboard that blends compact layout with fighter jet aesthetics. Inspired by the precision engineering of the Sukhoi aircraft family, this board carries the same philosophy—lightweight, powerful, and built to perform.

This board features a fully ortholinear matrix, programmable via QMK, and designed to be either soldered or hotswap depending on your preference. The case includes a subtle engraved Sukhoi logo on the top plate, making it not just a tool, but a statement piece.

---

## About the Board

Sukhoi Board isn’t your typical minimalist keyboard. It takes the core idea of an ortholinear layout and wraps it in a shell of aviation-grade aesthetics. The design process included weeks of testing different switch layouts, plate mount styles, and case fitments. The result is a compact but mighty board that’s flight-ready for any desk.

You can drop this board into any workflow: coding, writing, gaming, or just pretending to be in a cockpit while answering emails. The key spacing is optimized for fast finger travel and a consistent typing rhythm, even during long sessions.

---

## Features

- 40-key ortholinear grid layout  
- Engraved Sukhoi logo on top plate  
- USB-C connectivity with ESD protection  
- QMK/VIA compatible  
- Rotary encoder support  
- Optional OLED display  
- Custom-designed PCB with clear silkscreen labeling  
- MX-style switch compatibility  
- Designed with hotswap and soldered variants  
- Screw-together case with 3D printable and CNC options  

---

## Gallery

### Schematic View

| Image | Description |
|-------|-------------|
| ![image](https://github.com/user-attachments/assets/22f22833-a96a-4afb-bccc-2a8a74ac3f25) | Full schematic showing row-column matrix, MCU, encoder, and reset switch |

---

### PCB Layout

| Image | Description |
|-------|-------------|
| ![image](https://github.com/user-attachments/assets/88219f5c-ab85-48a2-a5b8-4b688bd7714c) | PCB layout with routed traces, encoder mount, and hotswap sockets |

---

### 3D Render

| Image | Description |
|-------|-------------|
| ![3drender](https://github.com/user-attachments/assets/example-3d.png) | Fusion 360 render of assembled Sukhoi Board with top-down view |

---

## Build Notes

The board was designed in KiCad 7 and modeled in Fusion 360. Dimensions were based on typical 40% boards, but extra care was taken to align the encoder and OLED cleanly into the top right. You can print the case on an FDM printer using PLA+ or CNC it from aluminum if you're extra.

Mounting uses M2 screws through standoffs into a recessed screw boss design. There is a slot for USB-C clearance and backplate vents for passive airflow. Plate cutouts were adjusted to reduce switch wobble, and the encoder is fully flush with the case top.

---

## Future Plans

The Sukhoi Board is version 1. Future plans include:

- Bluetooth low-power edition using nRF52  
- Per-key RGB under each switch  
- Jet gray anodized aluminum top  
- Official case files for resin printing  
- A dedicated VIA layout JSON hosted in this repo  

---

## License

Sukhoi Board is open-source hardware. All design files, including PCB, case, and firmware, are shared under the MIT License. Commercial resale is not permitted without credit.

---

Built to fly. Tuned for typing.
