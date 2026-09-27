# MACROPeX-AiR — Design Journal

## Project Summary

| Project Name | Time Taken | Design Tool |
|---|---|---|
| MACROPeX-AiR | ~14 hours 30 minutes | EasyEDA Pro |
<img width="2160" height="3256" alt="PCB_PCB1_2026-09-28" src="https://github.com/user-attachments/assets/e44999f2-c056-426c-9079-b882c7a42187" />

## Build Log

### Hour 1–2 — Component Selection & Import
Started by bringing in the core parts for the macro pad — picked the **RP2040** as the main MCU, imported a USB-C connector, and pulled in some 3D LED models so I could get a feel for how the board would actually look once populated. Also tweaked a few design choices around this point before committing to the layout direction.

### Hour 3–5 — Schematic Design
Spent the next few hours connecting everything together on the schematic — wiring the RP2040 up to USB-C, power, and the LEDs. This was the bulk of the "getting the electrical design right" phase before moving into anything physical.

### Hour 5.5–7 — Keys & Switches Setup
Moved over to picking out the switches for the macro pad and went through their datasheets carefully, editing footprints and spacing so everything would line up cleanly during assembly — no one wants misaligned keys on a macro pad.

### Hour 7–8 — Encoders
Added the rotary encoders into the design — placed them and wired them in alongside the switch matrix.

### Hour 8–10 — PCB Layout
Switched to the PCB view and worked through placing all the components on the board — keys, encoders, MCU, USB-C, and LEDs — arranging everything so it would both route cleanly and match the physical key layout.

### Hour 10–12.5 — Routing & Error Fixing
Routed the whole board and worked through the DRC errors that came up along the way until the board came back clean.

### Hour 12.5–14.5 — 3D Enclosure Design
Finished up by designing the 3D outer shell/frame for the macro pad — the case that houses the PCB — to match the board outline and key placement.

## Notes
- Tool used throughout: **EasyEDA Pro**
- MCU: RP2040
.
