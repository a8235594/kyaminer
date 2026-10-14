# 🦆 KYAMINER

### An AI duck watching over your mining farm.

**Free basic management for up to 5 rigs · HiveOS rig enrollment · AI-assisted operations**

## [Open KYAMINER →](https://kyaminer.com/)

[New here? Read the 3-minute enrollment guide →](docs/getting-started.en.md)

Manage rigs, flight sheets and overclock settings from your desktop or phone, with AI-assisted troubleshooting.

[Visit KYAMINER](https://kyaminer.com/) · [Telegram community](https://t.me/+xdKYKNbnFSM0NGNl) · [中文](README.md)

> This repository contains product information, documentation and issue reporting. KYAMINER is a commercial hosted service. Core application source code and self-hosting packages are not published here.

## Product preview

Screenshots show the actual interface with fictional demonstration data. They do not contain customer data or represent actual or promised earnings.

### Dashboard: hashrate, connectivity, revenue and electricity

![KYAMINER dashboard with fictional hashrate, device status and electricity estimates](assets/dashboard-demo.png)

### Mobile: check your Worker Ducks anywhere

<img src="assets/mobile-workers-demo.png" alt="Mobile Worker Duck list with demonstration devices" width="390">

### Duck King: explore before activating

![Duck King feature preview: operations, monitoring, automated updates, relays and reports](assets/duck-king-preview.png)

Users without authorization can explore the preview. Operations require activation and a bound dedicated instance. AI credits and Advanced access are managed separately.

[Open KYAMINER](https://kyaminer.com/) · [Enrollment guide](docs/getting-started.en.md)

## Features

- Multiple farms, rig status, GPU health and hashrate history.
- Wallet and flight-sheet management, including HiveOS clipboard imports.
- Overclock templates, per-GPU configuration and thermal control records.
- Mining logs, command execution and optional interactive terminals.
- AI Duck for conversational troubleshooting within account permissions.
- Advanced Duck King monitoring, reports and update workflows, depending on account access.
- Estimated daily revenue, electricity costs and net revenue.
- Mobile browser access and English/Chinese interfaces.

## Free allowance, service time and access

In the interface, **Duck Nest** means a farm, **Worker Duck** means a rig, **Flight Duck** means a flight sheet, and **Duck Eggs** refers to wallet management.

| Account status | Access policy |
| --- | --- |
| Owns 0–5 Worker Ducks, including the fifth | Basic device management is free and is not restricted by service-time expiry |
| Owns more than 5, with valid service time | Flight Duck deployment is available; service time continues counting down |
| Owns more than 5, with expired service time | Only Flight Duck deployment is blocked; other features retain their existing access permissions |

- Counts all devices owned by the account, including offline devices. Devices shared by other owners are excluded.
- Expiry does not stop existing mining jobs. Status, logs, overclocking, restart and other operations are not disabled by this policy.
- Deployment checks cover the web interface, batch operations, Duck King and automated updates. Queued deployments are checked again before delivery. Saving or editing a Flight Duck is not blocked by this policy.
- **No automatic charges currently apply.** Service time continues counting down; existing top-up and reward records are preserved.
- **AI Duck credits and Duck King Advanced access are managed separately** and are not included in the five-device free allowance.
- Users without Advanced authorization may explore the feature preview but cannot perform operations. Activation and a bound dedicated instance are required. Previewing does not load real rig or conversation data or incur AI usage fees.

## Advanced edition · Dedicated deployment

The advanced edition offers dedicated deployment services and integration with third-party messaging apps. Use a familiar chat interface to check farm status, receive alerts and daily reports, and access authorized rig-management tools.

Supported messaging platforms, deployment environments and features are confirmed based on available integrations. Dedicated deployment is a service offering; it does not make the core source code public or provide an open-source self-hosting package. Contact us through the [Telegram community](https://t.me/+xdKYKNbnFSM0NGNl).

## Get started

1. Register or sign in at [kyaminer.com](https://kyaminer.com/).
2. Create a farm and generate its enrollment command.
3. Run the command on a HiveOS rig you own or are authorized to manage.
4. Check one test rig before enrolling additional machines.

Keep enrollment commands and credentials private. Features and compatibility depend on the rig image and mining software.

## Estimates, not payouts

Algorithms are reported separately. Revenue estimates use supported Kryptex data and are not actual pool settlements. Electricity estimates use online GPU power and your USDT/kWh rate, excluding other system power consumption.

## Support

Use Issues for reproducible bugs and feature requests. Never post credentials, API keys, enrollment commands or private logs. See [support guidelines](SUPPORT.md).

KYAMINER is an independent project and is not affiliated with or endorsed by HiveOS. Product names and trademarks belong to their respective owners.
