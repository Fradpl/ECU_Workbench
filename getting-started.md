---
title: Getting Started
layout: default
nav_order: 2
---

# Getting Started
{: .no_toc }

<details open markdown="block">
  <summary>Contents</summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

---

## Installation

1. Download the web installer from [mcuinnovations.com](https://mcuinnovations.com/software/ecuwb/).
2. Run the installer — it downloads and installs the latest version automatically.
3. Launch **ECU Workbench** from the Start menu or desktop shortcut.

The installer manages the Microsoft Visual C++ Redistributable automatically.

---

## Account & Licensing

ECU Workbench requires an MCU Innovations account. Your license follows your account, so you can work across multiple machines.

1. Open the app and click **Log In**.
2. Enter your MCU Innovations email and password.
3. Your license is activated automatically once authenticated.

> If your license status looks stale, use the **Refresh License Data** button on the Account page.

---

## Connecting an Adapter

ECU Workbench works with any **J2534-compatible Passthru adapter**.

1. Install your adapter's J2534 driver.
2. Open ECU Workbench and go to the **Home** screen.
3. Select your adapter from the adapter dropdown.
4. Select the appropriate protocol for your ECU.

---

## First Flash Operation

{: .warning }
Always **read and back up** your ECU before writing any modified file.

1. Connect your adapter and select your protocol.
2. Power on the vehicle (key on, engine off) as prompted.
3. Click **Read Flash** to back up the current ECU image.
4. Load your modified `.bin` file using the Bin File Browser.
5. Verify the file passes the pre-flash safety checks.
6. Click **Write Flash** and follow the on-screen prompts.

---

## Updates

ECU Workbench checks for updates automatically on startup.

- **Stable** (default) — production releases
- **Development** — earlier builds with new features; may be less stable

Switch channels in **Settings → Updates**. Use **Check Now** to check manually, or **Roll Back** to return to the previous version.
