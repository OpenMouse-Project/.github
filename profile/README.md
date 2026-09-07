# OpenMouse

OpenMouse is an open-source project for reading and controlling gaming mice and keyboards across vendors, independent of each manufacturer's proprietary software.

![OpenMouse control panel](https://raw.githubusercontent.com/OpenMouse-Project/.github/main/profile/screenshot.jpg)

## Repositories

- **[openmouse](https://github.com/OpenMouse-Project/openmouse)** — Browser-based control panel for supported gaming mice: change DPI, polling rate, and sensor settings without installing a driver.
- **[mouse-protocol](https://github.com/OpenMouse-Project/mouse-protocol)** — Mouse and keyboard device protocol implementations used by OpenMouse, covering devices from Logitech, Razer, Pulsar, and others.
- **[Desktop](https://github.com/OpenMouse-Project/Desktop)** — OpenMouse desktop app (Tauri).
- **[OpenMouse-Bridge](https://github.com/OpenMouse-Project/OpenMouse-Bridge)** — Lightweight cross-platform background service providing device communication, application detection, and automatic profile switching on Windows and Linux.
- **[openmouse-docs](https://github.com/OpenMouse-Project/openmouse-docs)** — Documentation site for OpenMouse ([docs.openmouse.app](https://docs.openmouse.app)).
- **[openmouse-landing-page](https://github.com/OpenMouse-Project/openmouse-landing-page)** — Marketing site and public info pages for OpenMouse ([openmouse.app](https://openmouse.app)).
- **[openmouse-support-desk](https://github.com/OpenMouse-Project/openmouse-support-desk)** — Support desk for OpenMouse users.

## Status

OpenMouse is under active development. Protocol support varies by device — some drivers offer full read/write control (RGB, DPI, debounce, polling rate), while others are currently read-only. See individual repositories for device-specific details.

## Contributing

Issues and pull requests are welcome. If you'd like to add support for a new device, reverse-engineering notes and driver examples in the existing repositories are a good starting point.
