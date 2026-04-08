# PlantCare Documentation

This repository contains the public-facing documentation for PlantCare.

PlantCare is an environmental monitor focused on CO2, temperature, and
humidity. It combines a local web interface with alarms, Matrix LED warnings,
remote notifications, charts, logs, and optional integrations such as
Telegram, Shelly, and Bluetooth sensors.

## Start Here

- English user guide: [docs/user-guide/en/README.md](docs/user-guide/en/README.md)
- Overview and first access:
  [docs/user-guide/en/sections/overview.md](docs/user-guide/en/sections/overview.md)
- First alarm flow:
  [docs/user-guide/en/flows/basic/add-first-alarm.md](docs/user-guide/en/flows/basic/add-first-alarm.md)
- Telegram setup flow:
  [docs/user-guide/en/flows/basic/setup-telegram-notifications.md](docs/user-guide/en/flows/basic/setup-telegram-notifications.md)

## Video Demos

- [This Device Warns Me About High CO2 and Sends It to Telegram](https://youtu.be/uUkitUXndD8?si=6oeI0EoqvSQORf07)
- [PlantCare Full Interface Tour: Alerts, Telegram, BLE, Shelly, and System Pages](https://youtu.be/ElIpB5tRcJQ)

## What PlantCare Can Do

- monitor CO2, temperature, and humidity in real time
- show local warnings on the device Matrix LED
- send alerts through Telegram, Pushover, and webhooks
- trigger Shelly devices from alarm rules
- add BLE sensors to the monitored device list
- review charts, data logs, and system health pages from the browser

## Repository Layout

```text
PlantNotifier/
├── README.md
└── docs/
    ├── README.md
    └── user-guide/
        ├── README.md
        └── en/
```

## Notes

- This repository is documentation-only.
- The current scope is the English user guide and supporting screenshots.
