# Summer Night — Interactive Art Tree

A mixed-media sculpture combining sculptural craft with embedded electronics: a "tree" built from a 
natural branch, fitted with LED "fireflies," piezo buzzer "crickets," and a moonlit LED lamp, driven by 
two Digispark ATTiny85 microcontrollers.

**Full write-up (build process, materials, photos):** [https://www.instructables.com/A-Mechanical-Midsummer-Night]

## How it works

- **Fireflies**: 5 LEDs, individually wired and controlled by a Digispark ATTiny85, mounted along the 
  tree's branches to simulate flickering fireflies at night.
- **Crickets**: 2 piezo buzzers, driven by a second Digispark ATTiny85, generate a cricket-like chirping 
  sound.
- **Moon**: A powerful LED wall light mounted on a support stick, wired to a wall socket, acts as a 
  standalone "full moon" light source for the piece.

## Hardware

- 2x Digispark ATTiny85 microcontrollers
- 5x LEDs (fireflies)
- 2x piezo buzzers (crickets)
- PCB boards + female PCB headers
- Soldering iron, solder, and extra wire
- Long male-to-female / male-to-male / female-to-female jumper wires
- LED wall light (moon)
- Long cable for wall socket connection

## Software

- Programmed using the Digispark ATTiny85 (Arduino IDE with Digispark board support)

## Build notes

The electronics were built as two independent circuits (fireflies and crickets), each on its own PCB 
with its own ATTiny85, then physically integrated into the sculptural tree structure — separate from 
the moon light, which runs directly off a wall socket rather than the microcontrollers.

