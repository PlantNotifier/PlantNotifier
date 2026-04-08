# PlantCare Documentation

This repository contains the public-facing documentation for PlantCare.

PlantCare is an environmental monitor focused on CO2, temperature, and
humidity. It combines a local web interface with alarms, Matrix LED warnings,
remote notifications, charts, logs, and optional integrations such as
Telegram, Shelly, and Bluetooth sensors.

`PlantCare` is the product name. `PlantNotifier` is the GitHub repository name
that currently hosts this documentation.

## Click Here First

- [Documentation map](docs/README.md) - best starting point if you want to browse
- [English user guide](docs/user-guide/en/README.md) - main entry page with task, screen, and support links

## Quick Click Paths

- New to PlantCare: [Overview and first access](docs/user-guide/en/sections/overview.md)
- Need to get the device online: [Get online and connect to home Wi-Fi](docs/user-guide/en/flows/basic/get-online-and-connect-home-wifi.md)
- Want your first alert quickly: [Add your first alarm rule](docs/user-guide/en/flows/basic/add-first-alarm.md)
- Want Telegram notifications: [Set up Telegram notifications](docs/user-guide/en/flows/basic/setup-telegram-notifications.md)
- Want a page-by-page UI guide: [Click by screen](docs/user-guide/en/README.md#click-by-screen)
- Need help, login, or behavior notes: [Click for support](docs/user-guide/en/README.md#click-for-support)

## Recommended Path

1. Start at [docs/README.md](docs/README.md).
2. Open [docs/user-guide/en/README.md](docs/user-guide/en/README.md).
3. Pick one of the navigation sections there:
   `Click Here First`, `Click By Goal`, `Click By Screen`, or `Click For Support`.

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
