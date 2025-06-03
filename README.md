# MesureVVS
=============

MesureVVS is an Android application designed for use with a cardboard VR headset. Its purpose is to help assess post-stroke patients' perception of verticality, which can be affected by balance disorders.

## 🧠 Project Overview

Patients wear a VR headset and observe a rotating luminous bar. They must indicate when they believe the bar is perfectly vertical. The app records the angle at that moment, helping to detect impairments in verticality perception.

Two visual modes are available:
- **Simple mode**: a rotating bar on a black background.
- **Dynamic mode**: a rotating bar with a background of moving luminous dots.

## 📱 Dual Device Setup

The application requires **two Android smartphones**:
- One acts as the **VR headset** displaying the rotating bar.
- The other acts as a **remote control**, allowing the clinician to:
  - Start/stop the measurement.
  - Rotate the bar manually.
  - Save data in `.csv` format.

## 👨‍💻 Technologies

- Android (Java)
- Bluetooth communication
- OpenGL
- CSV export

## 🧪 Context

This project was developed as part of a **one-month full-time student project** in a team of four, in collaboration with researchers specializing in balance disorders.

## 🧩 My Role

I was responsible for:
- Implementing **Bluetooth communication** between the two devices.
- Developing the **interface and logic** of the remote control.
- Handling the **link between remote commands and 3D actions**, including the control of the luminous bar's rotation.

