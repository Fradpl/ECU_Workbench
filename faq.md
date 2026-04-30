---
title: FAQ
layout: default
nav_order: 6
---

# FAQ
{: .no_toc }

<details open markdown="block">
  <summary>Contents</summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

---

## Do I need proprietary hardware?

No. ECU Workbench works with any **J2534-compatible Passthru adapter**. You are not locked into a specific brand of hardware.

---

## Can I use my license on multiple computers?

Yes. Licensing is account-based — log in with your MCU Innovations account on any machine.

---

## My license status looks wrong after purchase. What do I do?

Go to the **Account** page in ECU Workbench and click **Refresh License Data** to pull the latest information from the server.

---

## What is the Development update channel?

The Development channel receives builds earlier than the Stable channel. These may include new features or ECU support that hasn't been fully validated yet. Switch channels in **Settings → Updates**.

---

## How do I roll back to the previous version?

In **Settings → Updates**, click **Roll Back**. This restores the version that was installed before the last update.

---

## Windows SmartScreen warns about the installer. Is it safe?

Yes. The installer is signed and has its own permanent reputation with Windows. If you see a SmartScreen prompt on a first-time install, click **More info → Run anyway**.

---

## Is my ECU data backed up before writing?

ECU Workbench does not automatically back up before a write — you must manually perform a **Read Flash** first. Always do this before writing any modified file.

---

## What file format does ECU Workbench use?

ECU flash images are standard binary (`.bin`) files. Modified files must pass the built-in pre-flash safety checks before they can be written.
