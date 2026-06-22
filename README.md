# LHSP - Luan's Homebrewed Switch Pack

**A lightweight and clean pack** for Nintendo Switch.

Made for those who want something simple, without bloat and up-to-date.

### Current Pack Contents

| Item                          | Version                 |
|-------------------------------|-------------------------|
| Pack Version                  | 2.2.0                   |
| Supported Firmware            | 22.5.0                  |
| Atmosphère                    | 1.11.2 (Basic Support)  |
| Hekate                        | 6.5.3 (Nyx 1.9.3)       |

### Included Homebrews

| Homebrew                      | Version                 |
|-------------------------------|-------------------------|
| Hekate                        | 6.5.3                   |
| Atmosphère                    | 1.11.2                  |
| sys-patch (sigpatches)        | 1.6.2.3                 |
| Ultrahand Overlay             | 2.5.1                   |
| nx-ovlloader                  | 2.0.2                   |
| sys-clk                       | 2.0.1                   |
| DBI                           | 895 (multilingual)      |
| Goldleaf                      | 1.2.0                   |
| Sphaira                       | 1.0.0                   |

**Bundled tools** (ship with Atmosphère / nx-ovlloader): Daybreak (firmware updater), Haze (USB MTP file transfer), Reboot to Payload, and Ultrahand-Reload.

---

### How to Install

1. Download the latest version [here](https://github.com/LuGB18/LHSP/releases)
2. Extract the .zip file directly to the root of your SD card
3. Start the console with Hekate (payload)
4. Choose **EmuMMC** (default)

Done.

### Hekate Boot Options

- **EmuMMC** → Default (recommended)
- **SysMMC** → Not configured by default

If you want to boot into SysMMC, edit the `/bootloader/hekate_ipl.ini` file.

---

### ⚠️ Important Notice (Exosphere)

Your EmuMMC comes with **serial and product info blanked** for security.  
This significantly reduces the risk of a ban if you use sigpatches.

If you want to disable this protection, edit the `/exosphere.ini` file.

---

### Notes

- Atmosphère is in **Basic Support** on FW 22.5.0. Use at your own risk.
- This pack **does not include themes (including HEKATE ones), extra overlays, or unnecessary homebrews**.
- I **do not condone piracy**.

---

**License:** [GPL-3.0](LICENSE)
