# Lab 1 – OOP + ESP32 + Wokwi

This repository is a template for the **first lab on Object-Oriented Programming and IoT (ESP32)**.

## Task for students

1. Open this repository in **GitHub Codespaces** or clone it locally with VS Code + PlatformIO.
2. Explore the project structure:
   - `src/LED.h` – LED class declaration
   - `src/LED.cpp` – LED class implementation
   - `src/main.cpp` – usage of the LED class
3. Make sure the code compiles and runs:
   - `led1` on GPIO2 should blink every 500 ms.
   - `led2` on GPIO4 should blink every 1000 ms.
4. Modify the code:
   - Add a third LED object with a different pin and interval.
   - Add `Serial.println` messages when LEDs change state.
5. Run the project:
   - either on a real ESP32 DevKit board
   - or using **Wokwi** simulation (see `diagram.json` and `wokwi.toml`).

## Report

In the end of the lab, update this README:

- Add screenshots of:
  - the running Wokwi simulation (or a photo of the real board),
  - Serial Monitor output.
- Briefly describe:
  - what you changed in the code,
  - what you learned about classes and objects in C++.