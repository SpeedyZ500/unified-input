# unified-input
**unified-input** is an input API that aims to standardize how games and devices handle input across controllers, keyboards, mice, sensors, and more. It supports flexible, declarative configuration and powerful fallback logic — designed to replace or augment legacy APIs like XInput.

## 🚀 Purpose

Modern input APIs are fragmented and inflexible. `unified-input` exists to:
- Abstract input behavior behavior awayy from device specifics
- Support modern sensors and outputs (e.g., gyro, RGB, rumble, mic)
- Enable consistent input mappping across games, devices, and platforms
- Provide developers and tinkerers a way to easily build, customize, and extend input systems - even for nontraditional or experimental harware
- provide a framework from which sensor interpretation can be built, and used

## 🔧 Planned Features
- [ ] Declaritive `.json` device escripters
- [ ] Input groups with tag-based matching (`["movment", "hz"]`, etc.)
- [ ] Axis, button, trigger, stick, adn sensor support
- [ ] Configureable input group resolution (e.g. `sl`, `sr`, `tl`, `tr`, etc.)
- [ ] Two-way communication for outputs (rumble, aurio, RGB, video/GUI)
- [ ] Gyro-first design with clean sensor abstraction (`g.a`, `g.r`, `g.m`)
- [ ] Cross-Platform compatibility via C++ core and config files
- [ ] Group sets and standardize labels for persistent game profiels
- [ ] Dynamic fallback resolution for missing or incomplete hardware document/declaration/configuration
- [ ] Modular sturcture for use in games, mods, standalone tools, and more

## 📅 Roadmap
- [ ] Define base JSON schema for inputs and outputs
- [ ] Build Wii Remote test app to capture raw inputs
- [ ] Implement group/tag-based resolution system
- [ ] Create unified descriptor for Joy-Con, PS4, Xbox controllers
- [ ] Create a React Native app for virtual touchscreen controller
- [ ] Create a Minecraft mod demo using Wii Remote + Nunchuk for input
- [ ] Document and open-source the API for use in other systems

## Potential Use Cases

- Enable cross-game input configurations with tag-driven in-game remapping
- Build a cross-platform controller layer that maps gyro aiming to mouse input
- Create a virtual control interface for touchscreen-based devices

> **Note:** This project is in early evelopment. Structure and features are subject to change as implementation evolves.
