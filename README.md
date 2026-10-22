# PS4 AirPlay Audio Receiver (Apple Music)

A lightweight Fake PKG (FPKG) receiver for jailbroken PlayStation 4 consoles. Cast Apple Music audio directly from your iOS device with synchronized metadata, high-resolution album artwork, and real-time audio visualizers.

---

## Features

* **AirPlay Audio Streaming:** Low-latency, high-fidelity wireless audio playback.
* **Full Metadata Sync:** Displays track title, artist name, and album information in real time.
* **High-Res Album Artwork:** Fetches and renders full-resolution cover art directly on your display.
* **20 Built-in Visualizers & Themes:** Switch between audio spectrum analyzers, waveform monitors, dynamic background ambient gradients, retro VU meters, and minimal dark/light themes.

> **Note:** This application operates exclusively as an **Audio/Metadata receiver**. Video mirroring and AirPlay screen sharing are not supported.

---

## Tested Environment & Compatibility

| Component                  | Tested Configuration                                                 |
| :------------------------- | :------------------------------------------------------------------- |
| **PlayStation 4 Firmware** | **13.52** (Jailbroken / GoldHEN / Mira)                              |
| **Tested Sender Devices**  | iPhone 15 Pro Max, iPhone 14 Pro Max                                 |
| **Tested OS Version**      | **iOS 26.6**                                                         |
| **Network**                | Same local network (Ethernet LAN or 5 GHz Wi-Fi recommended)         |

---

## Installation

1. Download the latest `.fpkg` file from the **Releases** section.
2. Copy the `.fpkg` directly to the root of an **exFAT** or **FAT32** formatted USB drive.
3. Insert the USB drive into your jailbroken PS4.
4. On the PS4 home screen, navigate to:  
   `Settings` > `GoldHEN` (or `Debug Settings`) > `Package Installer`
5. Select the package to install.

---

## How to Use

1. Launch the app from your PS4 dashboard.
2. Verify that your iPhone and PS4 are on the same local network.
3. Open **Apple Music** (or swipe down to **Control Center**) on your iPhone.
4. Tap the **AirPlay** icon and choose your PS4 receiver from the speaker list.
5. Control playback directly from your iPhone.

### Controller Shortcuts

* **D-Pad Left / Right:** Cycle through the 20 visualizers and visual themes.
* **Triangle ($\Delta$):** Toggle UI metadata text on/off (clean visualizer mode).
* **Options:** Open in-app audio buffer and display settings.

---

## Known Limitations

* Supports audio streaming and static album metadata only (no AirPlay screen mirroring or DRM video streaming).
* Verified exclusively on **iOS 26.6**; backwards compatibility with older iOS revisions is untested.
* Requires a stable local connection to prevent audio buffer underruns.
