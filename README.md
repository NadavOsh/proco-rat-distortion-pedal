# proco-rat-distortion-pedal
Analog distortion pedal based on the ProCo RAT, featuring op-amp clipping, tone control, and custom PCB design




<img width="1196" height="806" alt="image" src="https://github.com/user-attachments/assets/2a209a4f-d454-4e02-96fb-f14957e0d6a9" />



<img width="1241" height="788" alt="image" src="https://github.com/user-attachments/assets/30ea79b2-f518-4365-b180-dac7f0bee000" />








# ProCo RAT Distortion Pedal (Hardware Design)

## Overview
This project is a custom hardware implementation of the classic ProCo RAT distortion pedal.

The design is based on a high-gain op-amp stage combined with diode clipping and a tone-shaping filter, producing a wide range of distortion from overdrive to aggressive fuzz-like tones.

The project demonstrates analog audio circuit design, signal shaping, and PCB implementation.

---

## 🎸 Features
- High-gain distortion using op-amp amplification
- Symmetrical diode clipping
- Adjustable tone control (low-pass filter behavior)
- Volume control (output level)
- Custom PCB design

---

## 🔧 Hardware Architecture

### Core Blocks
- **Input Stage**
  - High input impedance for guitar signal
  - AC coupling to remove DC offset

- **Gain Stage**
  - Op-amp-based amplification
  - Adjustable gain via potentiometer (Distortion control)

- **Clipping Stage**
  - Diodes in feedback path
  - Produces characteristic RAT distortion

- **Tone Control**
  - Passive/active filter shaping high frequencies
  - Controls brightness of the output signal

- **Output Stage**
  - Volume control potentiometer
  - Output coupling capacitor

---

## ⚙️ How It Works

1. The guitar signal enters a high-impedance input stage.
2. The op-amp amplifies the signal to high gain levels.
3. Diodes clip the signal symmetrically, generating distortion.
4. The tone filter shapes the frequency response.
5. The output stage adjusts the final signal level.

---

## 🔌 Power Supply
- Typical operation: 9V DC
- Single-supply analog design
- Virtual ground (biasing) used for op-amp operation

---

## 🧠 Design Notes
- The distortion character is mainly defined by:
  - Op-amp gain
  - Clipping diodes
- Tone control acts as a variable low-pass filter
- Proper biasing is required for single-supply operation
- Component selection significantly affects sound character

---

## 🧪 Testing & Verification
- Audio signal tested using guitar input
- Output observed using oscilloscope
- Verified clipping behavior and waveform shaping
- Listening tests performed for tonal evaluation

---

## ⚠️ Limitations / Improvements
- Power filtering can be improved to reduce noise
- Op-amp selection can be optimized for different tonal characteristics
- Could add switchable clipping modes

---

## 📁 Files Included
- Schematic (PDF)
- PCB layout
- BOM
- Gerber Files
- Pick and Place

---
