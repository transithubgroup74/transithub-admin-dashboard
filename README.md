# TransitHub — Admin Dashboard

Web dashboard for TransitHub staff to manage the platform — bookings, schedules, routes, buses, drivers, passengers, staff roles, revenue, and payments.

A single self-contained **HTML / CSS / JavaScript** file (no build step).

## Features

- 🔐 Staff login with role-based access (Super Admin, Manager, Operator, Conductor)
- 📋 Bookings overview
- 🗺️ Manage routes and schedules
- 🚌 Manage buses and drivers
- 👥 View passengers
- 💰 Revenue and payments reporting
- 📤 CSV export

## Usage

It's a plain HTML file — just open `index.html` in a browser:

```bash
# from this folder
start index.html      # Windows
# or simply double-click index.html
```

No installation or server required.

## Roles

| Staff ID | Role |
|----------|------|
| TH-ADM-001 | Super Admin |
| TH-MGR-002 | Manager |
| TH-OPR-003 / 004 | Operator |
| TH-CON-005 | Conductor |

> Credentials are placeholders for the prototype. Before launch, the dashboard will be wired to the [backend](https://github.com/transithubgroup74/transithub-backend) so all data is live and staff auth is handled server-side.

---

Part of the **TransitHub** project: [mobile app](https://github.com/transithubgroup74/transithub-app) · [backend](https://github.com/transithubgroup74/transithub-backend) · this dashboard.
