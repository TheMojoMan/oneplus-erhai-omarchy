# Status — Omarchy on OnePlus Pad 3 (erhai)

## What works

**First start**
* The first boot walks you through setting up your user account. I have added a graphical user interface and an on-screen keyboard (osk) so no external keyboard is needed.

**Screen & graphics**
* Full **3392×2400** edge-to-edge panel, crisp 2× HiDPI scaling.
* Brightness control.
* Short press of the power button: screen **completely** off (not just the
  backlight); press again to wake — takes 3-4 seconds.
* **Hardware accellerated graphics** for the desktop, games and apps.
* **External monitor** over USB-C, also through a hub with HDMI.
* **Hardware video decoding** in the browsers — smooth playback, less battery.

**Input**
* Multi-touch touchscreen — see **Touchscreen & pen** below.
* Magnetic **keyboard** with trackpad, plus any USB/Bluetooth keyboard or
  mouse. Connects instantly; auto-rotation pauses while it is attached.
* Fold the keyboard cover over the screen: screen and touchscreen switch off
  with a click, folding back wakes them (one-time setup prompt).
* A one-finger swipe from the bottom edge shows the on-screen keyboard (osk).
* A one-finger swipe from the right or left edge switches workspaces.

**Touchscreen & pen**
* **Pen** — the **OnePlus Pencil 2** pairs over Bluetooth and works; the magnetic
  pen dock charges it (**CPS8601**) and stops at 100 %.

**Sensors & LED**
* All sensors functional.

**Internet & power**
* **Wi-Fi** and **Bluetooth** built in (USB Wi-Fi sticks also work).
* **USB-C**: hubs, storage, external displays and charging — even while the
  tablet hosts USB devices.
* **Fast charging**, on both erhai models: **SuperVOOC** (Southchip **SC8547A**
  charge pump) and **PPS/PD** (**PMIH0108**); the models differ only in the
  battery gauge (**TI bq27z561** vs **Qualcomm QBG**).
* **Bypass charging**: run from the charger with the battery held (quick
  settings; also automatic at the charge limit).
* Honest **battery percentage**, temperature and current; configurable charge limit.

**Sound & camera**
* **Six speakers** (stereo), plus sound through USB-C/DP monitors.
* **Internal microphones** (stereo).
* **Rear and front camera** -> use shipped app **ErhaiCam** (autofocus, autoexposure, camera switching, video with sound).

**System**
* **dual-boot with Android**.
* **OTA (over-the-air) updates** of kernel and apps.
* **Suspend** Press power key to turn off display - background tasks keep running. Choose 'Suspend' in shutdown menu to save more energy: display off, all tasks halted and CPU put to sleep.

**Gaming**
* **Steam** Install -> Package -> steam, choose 'Proton Experimental (ARM64)' in Compatibility setting.

**Other**
**Waydroid** Install -> Package -> waydroid-erhai. Do **NOT** install package 'waydroid'. It ships old graphics driver which make the tablet freeze!

## What does not work (yet)
* **144 Hz** — removed on purpose (the panel misbehaves sometimes at this rate).
* **USB-C headphones**

## Tips & known quirks

* Wifi takes about 10 sec to come up after desktop loads. 5 GHz show up later than
  2.4 GHz networks (be patient).
* Reboot to Android does not work when tablet is hot. Let it cool down then retry.
* If the tablet ever freezes -> hold POWER + VOL-UP for ~15 sec to reboot.
* Running LLMs on the NPU **overheats** tablet which leads to severe screen quirks -
  always use a cooler!!!
* Don't disable the touchscreen, sound or camera "autostart" services.
* Use the integrated Omarchy update function: Super + Space -> Update.

---

Back to [README](../README.md) · Next → [Credits](credits.md)
