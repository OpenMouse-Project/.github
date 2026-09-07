# OpenMouse

OpenMouse is an open-source project for reading and controlling gaming mice and keyboards across vendors, independent of each manufacturer's proprietary software.

## What's here

- **Mouse & keyboard protocol drivers** — reverse-engineered HID/USB protocols for devices from vendors including Wooting, Pulsar, Glorious, and others, unified under a common data model.
- **OpenMouse Desktop** — a cross-platform app (built with Tauri) for viewing and configuring connected devices.

## Status

OpenMouse is under active development. Protocol support varies by device — some drivers offer full read/write control (RGB, DPI, debounce, polling rate), while others are currently read-only. See individual repositories for device-specific details.

## Contributing

Issues and pull requests are welcome. If you'd like to add support for a new device, reverse-engineering notes and driver examples in the existing repositories are a good starting point.
