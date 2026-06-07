# FM-Radio-Receiver-Audio-Amplifier-Module
Compact USB-powered FM receiver with integrated stereo audio amplification,  on-board 3.3 V regulation and user control interface.

<img width="804" height="540" alt="image" src="https://github.com/user-attachments/assets/6bf7b8e0-f763-4e0d-a513-c42b79a1c5bf" />

---

## Overview

This project implements a compact FM radio receiver and audio amplifier module powered directly from a USB Type-C connection.

The design combines the RDA5807FP FM receiver IC with a TDA2822-based stereo audio amplifier to create a complete FM radio platform suitable for educational, prototyping, and DIY applications.

The module supports both headphone and speaker operation through a selectable audio output path and includes onboard user controls for tuning and station management.

---

## Features

- FM broadcast reception (87.5 MHz – 108 MHz)
- USB Type-C powered
- RDA5807FP FM receiver
- AMS1117-3.3 voltage regulator
- Integrated stereo audio amplification
- Headphone output
- Speaker output terminals
- Selectable audio output mode
- Volume control
- On-board user buttons
- Power status LED
- Compact PCB design

---

## Applications

- FM radio receivers
- Educational electronics projects
- Audio amplifier demonstrations
- RF learning platforms
- DIY radio projects
- Embedded audio systems
- Portable radio prototypes

---

## Technical Specifications

| Parameter | Value |
|------------|------------|
| FM Frequency Range | 87.5 MHz – 108 MHz |
| Supply Voltage | 5 V USB |
| FM Receiver IC | RDA5807FP |
| Audio Amplifier | TDA2822 |
| Regulated Voltage | 3.3 V |
| Headphone Output | 3.5 mm Jack |
| Speaker Output | Terminal Block |
| PCB Dimensions | 76.36 mm × 50 mm |

---

## System Architecture

<img width="915" height="320" alt="image" src="https://github.com/user-attachments/assets/5be602ac-f69b-4d9e-b530-180330e73085" />

---

## Design Highlights

### FM Reception

The RDA5807FP performs:

- RF amplification
- Frequency synthesis
- FM demodulation
- Stereo decoding
- Automatic station seeking

### Audio Amplification

The TDA2822 amplifier stage provides:

- Stereo amplification
- Single-supply operation
- Direct speaker drive capability
- Low component count

### Power Architecture

The module is powered directly from USB Type-C.

The AMS1117-3.3 regulator provides a dedicated supply for:

- RF circuitry
- Digital logic
- Frequency control functions

---

## Main Components

| Component | Function |
|------------|------------|
| RDA5807FP | FM receiver |
| TDA2822 | Audio amplifier |
| AMS1117-3.3 | Voltage regulator |
| USB Type-C | Power input |
| Trimmers | Volume control |

---

## Hardware Images

### 3D

<img width="846" height="496" alt="image" src="https://github.com/user-attachments/assets/ef7fa876-72a8-44ce-8251-296bc62a47e1" />

### PCB Top Side

<img width="663" height="498" alt="image" src="https://github.com/user-attachments/assets/3c577190-96e0-4bc3-b959-f7795db0adf8" />

### PCB Bottom Side

<img width="661" height="492" alt="image" src="https://github.com/user-attachments/assets/781d8760-665f-4ed2-9c03-aa6b92a85ed7" />

---

## User Controls

| Control | Function |
|----------|----------|
| KEY1 | Volume adjustment |
| KEY2 | Volume adjustment |
| KEY3 | Station control |
| KEY4 | Station control |
| KEY5 | MUTE |
| SW2 | Output selection |
| VR1 | Volume adjustment |
| VR2 | Volume adjustment |
